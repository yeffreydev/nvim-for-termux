# NVIM configuration
### config path for windows
<code>C:\Users\<user>\AppData\local\nvim\ </code>
crear una variable del sistema called START_NVIM_PATH
path for init pluggins make dir <code>C:\Users\<user>\AppData\local\nvim\.vim\plugged</code>

## para setear una env variable
<code>setx START_NVIM_PATH "C:\Users\yeffr\AppData\Local\nvim\.vim\plugged"</code>
si no funciona abre el editor de variables de entorno del sistema y agrega la variable de entorno START_NVIM_PATH

## configuration for termux - Android
paht for configuration <code>~/.config/nvim/</code>
path for init pluggins make dir <code>~/.config/nvim/.vim/plugged</code>

para agregar la variable de entorno en termux 
agrega la siguiente linea en el archivo <code>~/.bashrc</code>
<code>export START_NVIM_PATH=~/.config/nvim/.vim/plugged</code>
