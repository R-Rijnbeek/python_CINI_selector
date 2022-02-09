# python_CINI_selector

This repository that build and is the standard CINI selector for differrent use. It is not a package but it is useful to use it in different python projects.

In the future it is possible to build a standard python package with it.

## prerequisites

Has anaconda installed on windows. And configured you system variables ($path) of anaconda on windows: 
* C:\ProgramData\Anaconda3
* C:\ProgramData\Anaconda3\Scripts
* C:\ProgramData\Anaconda3\Library\bin

## Instalation protocol

1. Clone the github repository.
```
$ git clone https://github.com/R-Rijnbeek/python_CINI_selector.git
```

2. Enter the project folder.
```
$ cd python_CINI_selector
```

3. Build the virtual environment on the repository by running:
```
$ build.bat
```

4. To activate the environmet and run the test scripts:
```
$ activate ./env
$ python TEST/CINI_Test_File.py
```

If it works. Then you can use the 'cini' directory as a local package

## Notes to know: 

1. The dependencies to use all features of this repository are writed on the environmet.yml file
2. If you will only use the content of the 'cini' directory. Than you need only a python environmet with the 'json' package installed on it:
    * ANACONDA => https://anaconda.org/jmcmurray/json
3. This repository is tested with windows 10 and anaconda version 4.9.2.
