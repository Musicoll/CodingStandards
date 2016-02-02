# The Coding Standards of Kiwi

### Indentation

* The tabs should be replaced by 4 spaces.
* We should use the *Allman* style.

### Naming

* Member method names are written with camel-case, and never begin with a capital letter. For example : `getMethod()`.
* Member variables names are written with snake-case, but and always begins with "m\_" . For example : `m_member_variable`.
* Class names are written in camel-case, but always begin with a capital letter. For example : `ClassName`.
* Non-member variables and function parameters names are written with snake-case, and never begin with a capital letter not an underscore. For example : `nonmember_variable`.
* If you really have to write a macro for some reason, then make it all caps with underscores. For example : `MY_MACRO`.
* Enum names and members are written with camel-case, but always begin with a capital letter. For example : `MyEnum`.

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

* The class declaration should display the public members before the protected members and before the private members.
For example :  
```c++
class Node
{
    public:
      ...
    protected:
      ...
    private:
      ...
};
```
*nb : Please avoid the public variables.*

### Namespaces

* All the codes should be included within the namespace `kiwi`.  
For example :
```c++
namespace kiwi
{
  ...
}
```
