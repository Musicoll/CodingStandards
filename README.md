# The Coding Standards of Kiwi

### Headers

* The define declaration must be in the form `KIWI_"NAME"_H_INCLUDED`.  
For example :   
```c++
#ifndef KIWI_DSP_CHAIN_H_INCLUDED
#define KIWI_DSP_CHAIN_H_INCLUDED
...
#endif // KIWI_DSP_CHAIN_H_INCLUDED
```
*nb : Don't forget to comment the ```#endif``` line.*


### Namespaces

* All the codes should be included within the namespace `kiwi`.  
For example :
```c++
namespace kiwi
{
  ...
}
```
