# DiffTool

## Method 1
False/True Questions
 * La función “nvm_remove_tgt” ha cambiado su tipo de retorno.
 * Se agregó un nuevo argumento a la función nvm_remove_tgt. 
 * Se modificó el tipo de la variable “dev”.
 * Se eliminó la variable “nvm_dev *dev”.
 * La llamada al método “mutex_unlock” fue eliminada.
 * Se eliminó la instrucción “return 1” dentro de la condición “if(!t)”.
 * Se agregó la llamada al método “kref_put”.
 * Se eliminó la asignación de la variable “t = nvm_find_target(dev, remove->tgtname)”.
 * Se agregó la llamada al método “down_read(&nvm_lock)”.
## Method 2
False/True Questions
 * Se eliminó la declaración de la variable “i”.
 * Cambió la asignación de la variable “count”.
 * Se eliminó la variable “user_count”.
 * Se eliminó la variable “uaddr”.
 * Se agregó un nueva condicional “if(user_count < 0)”.
 * Se eliminó “return -ENXIO” dentro de la condicional “if(end>count)”.
 * Se agregó un ciclo “for(i=offset; i<end; i++)”.
 * Se modificó el valor que de retorno del metodo “rockchip_drm_gem_object_mmap_iommu”.
 * Se eliminó el retorno “ret” dentro de la condicional “if(ret)”.
 * Se agregó la variable “offset”.

## Method 3
False/True Questions
 * Se eliminó la variable “uaddr”.
 * Se eliminó la variable “usize”.
 * Se agregó la variable “nr_pages”.
 * Se eliminó la variable “off”.
 * Se agregó un nueva condicional “if(!pages)”.
 * Se modificó la función lógica “| |” por “&&”.
 * Se agregó el ciclo “do{ }while(usize > 0)”.
 * Se modificó el valor retornado del método “_arm_iommu_nmap_attrs”.
 * Se agregó la condicional “if(err)”.
 * Se eliminó la declaracion “usize”.

## Method 4
False/True Questions
 * Se eliminó la variable “start_pfn”.
 * Se eliminó la variable “nid” en la llamada al metodo “_add_pages”.
 * Se agregó la variable “nr_pages” en la llamada al metodo “_add_pages”
 * Se agregó el argumento “want_memblock” en la declaración del método “arch_add_memory(...)”
 * Se agregó el argumento “restrictions” a la llamada del método “_add_pages”.
 * La instrucción de retorno del método “arch_add_memory” fue modificado.
 * Se agregó la variable “nr_pages”.
 * Se eliminó la declaración de la variable “start_pfn”.
 * Se eliminó la variable “altmap” al llamar a la función “_add_pages”
 * Se agregó un nueva condicional “if(!want_memblock)”.
