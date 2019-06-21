# DiffTool

## Method 1
False/True Questions
 * The function "nvm_remove_tgt" has changed its return type.
 * A new argument was added to the "nvm_remove_tgt" function.
 * The type of the variable "dev" was changed.
 * The variable "nvm_dev *dev" was deleted.
 * The call to the method "mutex_unlock" was removed.
 * The "return 1" instruction inside the "if(!t)" condition was removed.
 * Added call to method "kref_put".
 * The assignment of the variable "t = nvm_find_target(dev, remove->tgtname)" was removed.
 * Added call to method "down_read(&nvm_lock)".
## Method 2
False/True Questions
 * The declaration of the variable "i" was deleted.
 * Changed the assignment of the variable "count".
 * The variable "user_count" was deleted.
 * The variable "uaddr" was deleted.
 * The conditional "if(user_count < 0)" was added.
 * The “return -ENXIO” instruction inside the “if(end>count)” condition was removed.
 * The cycle "for(i=offset; i<end; i++)" was added.
 * The return value of the method "rockchip_drm_gem_object_mmap_iommu" has been modified.
 * The return "ret" inside the conditional "if(ret)" was deleted.
 * The variable "offset" was added.

## Method 3
False/True Questions
 * The variable "uaddr" was deleted.
 * The variable "usize" was deleted.
 * The variable "nr_pages" was added.
 * The "off" variable was removed.
 * The conditional "if(!pages)" was added.
 * The logic function "| |" was changed to "&&".
 * The cycle "do{ }while(usize > 0)" was added.
 * The returned value of the method "_arm_iommu_nmap_attrs" was modified.
 * The conditional "if(err)" was added.
 * The "usize" statement was deleted.

## Method 4
False/True Questions
 * The variable "start_pfn" was deleted.
 * The variable "nid" in the method call "_add_pages" was removed.
 * The variable "nr_pages" in the method call "_add_pages" was added.
 * The argument "want_memblock" was added to the method statement "arch_add_memory(...)".
 * The "restrictions" argument was added to the method call "_add_pages".
 * The return instruction of the method "arch_add_memory" was modified.
 * The variable "nr_pages" was added.
 * The declaration of the variable "start_pfn" was deleted.
 * The variable "altmap" was removed when calling the function "_add_pages".
 * The conditional "if(!want_memblock)" was added.
