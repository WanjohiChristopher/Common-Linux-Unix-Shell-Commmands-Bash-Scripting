# Common-Linux-Unix-Shell-Commmands-Bash-Scripting

Shell- user interface for running commands/Scripting language to automate tasks.

# Shells
```
-Default one is Bash
-Others include:sh,ksh,tcsh,zsh and fish.

~ means home directory.
copying files ND SAVING TEM IN BACKUP
cp seasonal/summer.csv backup/summer.bck

moving a file to backup

mv seasonal/spring.csv seasonal/summer.csv backup
```
```
Renaming Files

mv winter.csv winter.csv.bck

Deleting files

rm seasonal/summer.csv
```
# Bash Shell(Bourne again shell)

For checking default shell on your command line type:


![Shell](https://user-images.githubusercontent.com/55980747/139646135-a1f39f07-0a94-4807-9004-809a4956e260.png)




If you don't have bash simply type 'bash' on the CLI(command line)


# Shell command applications
```
   -Running batch jobs (ETL)
   -Getting information
   -printing files and strings
   -compression and archiving
   -performing network operations
   ```
 # Shell Commands for Getinfo:
  
 ![getinfo](https://user-images.githubusercontent.com/55980747/139648865-d87f9d12-8fc5-4545-b7cc-149a9ac05654.png)
 
 # Shell commands for working with files
 

![carbon](https://user-images.githubusercontent.com/55980747/139649703-50602ba7-a1d6-4f28-90f3-3553efde7399.png)

# Shell commands for Navigating and working with Directories

![carbon (1)](https://user-images.githubusercontent.com/55980747/139650462-32ff3c3e-550e-408a-9312-3a80c0b15414.png)

# Shell Cmds for printing file and string content
![carbon (2)](https://user-images.githubusercontent.com/55980747/139651078-d6f5393a-6ef3-44f3-9f45-cae185fa31b7.png)

# Shell Cmds for Compressing and Archiving Files


![files](https://user-images.githubusercontent.com/55980747/139651455-dd185151-4dcc-40da-8699-a317466922f3.png)

# Shell commands for Neworking apps
![NETWORKS](https://user-images.githubusercontent.com/55980747/139651959-6d5dbb89-34ce-45bc-a0ae-1a0799133db2.png)

# Shell Pipes,Variables and Filters
```
ls | sort -r

man ls | head -20
```
Filters -transforms input data into output data

       -wc,cat,more,head,sort,grep and also can be chained together.
         
Pipe - denoted by |

     -used for chaining filter commands
     -```command1|command2```
     
     -output of the first cmd is input of the second command
     -basically pipe means pipeline
     
         ``` ls | sort -r represnts reverse sorting```
         
Variables-scope limited to shell

         -use set to list all shell variables
         
         -```set | head -4```
         
         -assigning variables with = not having spaces var=value
         
         ``` name='chris'
             #printing we use 
             echo $name```
             
         -deleting variables 
         ``` unset name```
Environment Variables -have extended scope

                     ``` export variablenme ```
                     -listing all env variables use ```env```
                     
                     ``` env | grep variablename```
                     
         
         


# Shell SCripting basics
-list of commands interpreted by a scripting lng.
-scripts used for automating processes
-shell script is an executable text file with an interpreter directive
``` shebang``` directive:

its usually represented as:
```
#!interpreter [optional argument]
```
Interpreter- is the absolute path to an executable program

optional-argument-single argument string






  

![shell](https://user-images.githubusercontent.com/55980747/139660016-d0ac5505-a6d4-4096-a90a-29a71b3236c7.png)

# MetaCharacters in Bash Shell

![metacha](https://user-images.githubusercontent.com/55980747/139666489-a6974881-96c8-4348-a646-d590d93b8018.png)

# Input/Output Redirection
-used for redirecting
![carbon (3)](https://user-images.githubusercontent.com/55980747/139667671-c3232ddd-418c-40bf-b79d-a63c5fe879ec.png)


# Batch vs.Concurrent modes

Batch mode:

commands run squentially

first runs then second

``` command1;command2```

Concurrent mode:

commands run in parallel

Command works works on background and pass input to command2 in foreground.

``` command1 & command2```


