# custom-vim
Personalización del editor de código Vim

## Ubicación 
El archivo de configuración de **VIM** es 
``` 
$ ~/.vimrc 
```
En caso de que este archivo no exista, solo tendremos que crearlo. 

Si estamos utilizando **NVIM**, el archivo de configuración será 
``` 
$ ~/.config/nvim/init.vim 
``` 

## Instalación 

En caso de no tener Vundle instalado, deberemos de instalarlo para que tome los plugins correctamente. Para ello clonaremos 
el repositorio de Vundle de GitHub

```
$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

A continuación instalamos y actualizamos los plugins ejecutando el comando siguiente en Vim
```
:PluginUpdate
```

## Referencias

* [Gestor de plugins Vundle](https://github.com/VundleVim/Vundle.vim) 
* [NERDTree](https://github.com/preservim/nerdtree) 
