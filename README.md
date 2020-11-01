<h1 align="center">Brute.MD5 v1.0</h1>
<p align="center">
    <a href="https://python.org">
    <img src="https://img.shields.io/badge/Python-3.7-green.svg">
  </a>
  <a>
    <img src="https://img.shields.io/badge/License-BSD%203-lightgrey.svg">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Release-1.0-blue.svg">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Open%20Source-%E2%9D%A4-brightgreen.svg">
  </a>
</p>


## How To Use in Linux
```bash
# Install dependencies 
$ Install latest python 3.x

# Clone this repository
$ git clone https://github.com/Rafly1337/Brute.MD5-v1.0.git

# Go into the repository
$ cd brute-md5

# Installing dependencies
$ python -m pip install pyfiglet argparse

# Getting Help Menu
$ python brute_md5.py --help

# Cracking MD5 Hash Without saving Result
$ python brute_md5.py -p <Hash> -w <Wordlist.txt>
$ Note: Wordlist.txt must be in same place where cracker is stored

# Cracking Example
$ python brute_md5.py -p 99003a570e9267d585eaebeb63d51337 -w passwd.txt

# Cracking MD5 Hash & saving Result
$ python brute_md5.py -p <Hash> -w <Wordlist.txt> -o <File_name.txt>
$ Note: Wordlist.txt must be in same place where cracker is stored

# Cracking Example
$ python brute_md5.py -p 99003a570e9267d585eaebeb63d51337 -w passwd.txt -o hash.txt
```


### Note : Procedure for cracking is same in all OS

## Screenshots:
#### Getting Help
![](/img/1._getting_help.png)

#### Cracking Hash Without Saving Result 
![](/img/2._cracking_hash.png)

#### Cracking Hash & Saving Result 
![](/img/3._cracking_hash_saving_result.png)

#### Result Got Saved in .txt file 
![](/img/4.saved_result_txt.png)

## Contact 
twiter.com/raflyghost

