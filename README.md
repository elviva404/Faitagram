# Faitagram - Don't Use This (Doesn't work anymore)-
A Bruter for FAcebook, twITter, and InstAGRAM. Made with python, developed from brut3k1t.

[You will need python!]

CREDIT:

  This project was developed from brut3k1t,which was made by ex0dus-0x.
  Here is the page : https://github.com/ex0dus-0x/brut3k1t
  Since this script was not functionning, and was not ready for a attack, so I decided to develop this program from his.


I am not responsible for your action.



----------------  How To Use ----------------

Get the requirements:

    python setup.py

Command:

    python faitagram -s [service] -u [username] -w [wordlist] -d [delay(Optional)]

Examples:

  

    python faitagram -s facebook -u MeMeBigBoy@gmail.com -w /root/passwd.txt -d 10

    (Execute faitagram) (facebook)  (Email of the target)  (wordlist path)   (delay[10secs])


    python faitagram -s instagram -u justin -w wlist

    (Execute faitagram) (Instagram) (username) (wordlist)
  

    python faitagram -s twitter -u hellohahahha -w wlist -d 3

    (Execute faitagram) (Twitter)  (Username)  (wordlist) (delay[3secs])
  

Memorize:

    -s, -u, -w parameters are musts, and -d is optional.

    -d in default is 1 sec.

    In facebook, you would have to type the email in the -u.

    In facebook, the script will ask you the Name of the target.

Specific tutorial will be on NullByte, I would put a link after I make a tutorial:

   https://null-byte.wonderhowto.com/forum/hacking-facebook-twitter-instagram-account-passwords-with-bruteforce-0181808/

How it works:

   This script uses selenium web driver, and Xvfb and pyvirtualdisplay to make the web driver invisible so you can keep doing work, this script also uses STEM as the proxy.


# Faitagram Technical Documentation

**Last updated:** 2022-01-26\
_Document generation aided by **Documatic**

Automatic Documentation

* [Introduction](#introduction)
* [Code Overview](#code-overview)

## Introduction

This is a technical document detailing
        at a high-level
        what Faitagram does, how it operates,
        and how it is built.

The outline of this document was generated
        by **Documatic**.
<!---Documatic-section-group: arch-start--->


## Project Architecture


<!---Documatic-section-group: arch-end--->

<!---Documatic-section-group: helloworld-start--->


## Code Overview

The codebase has a flat structure, with 1 code files.
<!---Documatic-section-helloworld: setup-start--->

No exact compatable Python version has been detected.
Versions below 3.8 are compatable.


Run `pip install -e .` in top-level directory to install
package in local directory.
Install from pypi with `pip install main`.



<!---Documatic-section-helloworld: setup-end--->

<!---Documatic-section-helloworld: entrypoints-start--->


## Entrypoints

There are no source code entrypoints in top-level `__main__`/`__init__` files.


<!---Documatic-section-helloworld: entrypoints-end--->

<!---Documatic-section-group: concept-start--->
## Concepts
<!---Documatic-section-group: concept-end--->

<!---Documatic-section-group: helloworld-end--->

<!---Documatic-section-group: dev-start--->


## Developers
<!---Documatic-section-dev: setup-start--->





<!---Documatic-section-dev: setup-end--->

<!---Documatic-section-dev: ci-start--->
No CI/CD config files were detected.


<!---Documatic-section-dev: ci-end--->

<!---Documatic-section-group: dev-end--->

### **Faitagram/**

setup.py has 0 functions.