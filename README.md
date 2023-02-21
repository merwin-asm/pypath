# PyPath - Linux

<p align="right"> <img src="https://komarev.com/ghpvc/?username=meriwn-pypath&label=Project%20views&color=0e75b6&style=flat" alt="darkmash-org" /> </p>


## Install

        pip install pyPathLinux


## How To Use:

```python
import pyPath 

my_path = pyPath()

```
### make_redirecting_bashfile()

For making a  Bash file which will call a target python file.

args:
    
    filename,
    target_pyfile="",
    content_edited=None,
    allow_args=False,
    max_num_args=0

Use:

```python 
print(my_path.addfile_to_path("/home/programming/test_123_2.sh",
        "test_123_2.sh",
        exe=True))

```

### addfile_to_path()

For adding file to path.

args:

    path,
    file_name,
    exe=False,
    permissions=None


### seek_to_path()

returns the items in the path.

### path_var_exists()

return if a path exists.

args:

    path

### add_dir_to_path_TEMP()

Adds a dir to path Temp.

agrs:
    
    path

### add_dir_to_path_PERMANENT()

Adds a dir to path.

args:

    path,
    path_to_bashrc
