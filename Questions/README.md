# DiffTool

## Method 3
False/True Questions
 * La función “nvm_remove_tgt” ha cambiado su tipo de retorno ().
 * Se agregó un nuevo argumento a la función nvm_remove_tgt. 
 * Se modificó el tipo de la variable “dev”.
 * Se eliminó la variable “nvm_dev *dev”.
 * La llamada al método “mutex_unlock” fue eliminada.
 * Se eliminó la instrucción “return 1” dentro de la condición “if(!t)”.
 * Se agregó la llamada al método “kref_put”.
 * Se eliminó la asignación de la variable “t = nvm_find_target(dev, remove->tgtname)”.
 * Se agregó la llamada al método “down_read(&nvm_lock)”.
