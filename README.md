
# PyKey-Gen
[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)]()
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)]()
[![forthebadge](https://forthebadge.com/images/badges/built-with-swag.svg)]()
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)]()
## what is PyKey-Gen?
**PyKey-Gen** is An Secure Key Generate (as _Integer_) With help of **Time Variations** and Expired within Minute

## How to Use?
### Install using pip
Frist it Need to **Install** (using Pip) <br>
Open **CMD** and Enter Below Command
```
pip install pykey-gen
```

### Import the _PyKey_Gen_
Before use The **Module**, It has To **import** like Below way
```
import pykey_gen as key
```
## Generate The Key 
For Generate a key it has Function **gen_key()**, this Function retrun Key
```python3
>>> import pykey_gen as key
>>> KEY=key.gen_key()
>>> KEY
'666141546045'
```
## Print The Key 
For Print a key It has Function **print_key()** , This Function Print Key 


```python3
>>> import pykey_gen as key
>>> key.print_key()
Key:-  666141546045
```

## Check The Key
If there is a Key To Verfield or Check its Has a Function **check_key(Key)**, It has **One Argument** as Key . Where we Enter a Key and This Function Check the Key is Expired or Not _(Key IS Expired within Minute)_
and retrun **boolean True or False**

```python3
>>> import pykey_gen as key
>>> Key=key.gen_key()
>>> key.check_key(Key)
True
```
In above Code, Where Generate a Key and stored In variable Key And ChecK The Key 

**Note:-** _Every Computer Generate Same Key In Same Time _(as Per Clock)_ and If Frist Computer Generate a Key . Within a Minute . Same key Enter in Second  Computer Will Accept It_
<br>
**Note:-** _This is An **Offline** Key Generate_
<br>
**Can Use in :-** _Product Registration Key and It will Expired within Minute_

# Also Aviable In Other Language

Click on it 
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)](https://github.com/prajwalkedari/Secure-Key-Gen/tree/main/Java)
[![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)](https://github.com/prajwalkedari/Secure-Key-Gen/tree/main/C++)
[![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](https://github.com/prajwalkedari/Secure-Key-Gen/tree/main/JavaScript)
[![Bash](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)](https://github.com/prajwalkedari/Secure-Key-Gen/tree/main/Bash)

  
## 🔗 Links
[![linkedin](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/prajwalkedari/PyKey-Gen)
[![Gitlab](https://img.shields.io/badge/GitLab-330F63?style=for-the-badge&logo=gitlab&logoColor=white)](https://gitlab.com/PrajwalKedari/pykeygen)
[![Bitbucket](https://img.shields.io/badge/Bitbucket-0747a6?style=for-the-badge&logo=bitbucket&logoColor=white)](https://bitbucket.org/prajwalkedari/pykey-gen)
