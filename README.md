## Usage ##

1. Create mailing.bat file and add it to PATH in your OS:

> @ECHO OFF
> set directory_name=%1
> mkdir %directory_name%
> cd %directory_name%
> git clone https://github.com/Dhofca/cmailing.git .

2. Type
> mailing PROJECT_NAME