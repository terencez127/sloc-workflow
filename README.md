sloc-workflow
=============
This is a Alfred 2 workflow that calculates SLOC(Source Line Of Code) in the current folder in finder. 

USAGE
------
Just simply import the workflow to your alfred.

Command Syntax
--------------
    sloc .
Return sloc of all files in the folder
  
    sloc postfix1 postfix2 ...

  Return sloc of files with given postfixes. For example, the command below will return sloc of all .java and .py files in the current folder:
  
    sloc java py
