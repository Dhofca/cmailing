## Description ##
Simple mailing boilerplate for non-responsive mailing which I like to use. 

## Usage ##

1. Create mailing.bat file and add it as envoirment variable in your OS:

```
@ECHO OFF
set directory_name=%1
mkdir %directory_name%
cd %directory_name%
git clone https://github.com/Dhofca/cmailing.git .
```
2. In your command line type:
```
mailing PROJECT_NAME
```
