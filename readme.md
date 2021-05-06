# Rooftop Academy

Esto es un proyecto de _ejemplo_ para el curso de **Rooftop Academy**

## Instalación
Lo primero que debes hacer el clonar el proyecto
```
git clone https://github.com/Adosio14/rooftop-test-dosio
```
## Reiniciar la url del repositorio

```
git remote set-url origin https://github.com/Adosio14/rooftop-test-dosio
```
y probamos con

```
git remote -v
git pull origin main
```
## Como forzar (no hacer nunca)
debemos estar seguros de que esto no va a afectar ni arruinar nada
```
git pull origin main --allow-unrelated-histories
```
## Como poner código formateado con su correspondiente lenguaje
se coloca la extension (js por ejemplo) despues de los backticks
```js 
var ejemplo = false
```

- Garabato García
- Genaro de las monatañas
- Rooftop Academy

### Manejo de directorios y archivos
para ingresar a una carpeta:
```
cd C:/Carpeta
```

Para volver a la carpeta anterior
```
cd ..
```

Para listar archivos y carpetas

#### Para Windows
```
dir
```


#### Para linux/mac

```
ls
```

 --- 
 ---
 ---

### Para trabajar con GIT

Si es la primera vez que usamos git deberemos configurar credenciales para hacer commits y pushear
```
git config --global user.name "Nombre-apellido"
git config --global user.email email@ejemplo.com
```

Cuando empecemos a trabajr debemos iniciar git en nuestra carpeta del **proyecto** y **no** en la de **proyectos**
```
git init
```
Para configurar el repositorio remoto
```
git remote add https://github.com/usuario/nombre-repo
```

Para agregar **todos** los archivos a git
```
git add .
```
Para hacer un commit
```
git commit -m "explicación de cambios"
```

Para un push **por primera vez**
```
git push -u origin main
```
Para hacer un push normalmente
```
git push origin main
```

Para saber el estado de nuestro stage
```
git status
```
Para saber a que url/repositorio va nuestro proyecto
```
git remote -v
```