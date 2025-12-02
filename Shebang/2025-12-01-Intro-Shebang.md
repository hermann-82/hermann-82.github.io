<h1> Introduction to Shebang <h1>

```console

 * Difference between Bourne shell (sh) and Debian Almquist shell (dash)

  A shebang statement is a line that you can specify at a top of a shell script.
  it is start with #!. It is use to specify what shell a script is writen to.
    #!/bin/bash

** Exit code

A success command return a value of 0 and a failed command return a value >0.
The exit code is store is a variable called $?
To see the value of the exit code run the command echo $?

To specify the exit code number at the end of a script, just write at the end of it 
exit plus the number you want it to return when failed.

## Function

A function is a peace of code that is use to execute a particular function that can be reuse or repropose through out the script.
So anywhere between the script throuland the code, we simply need to call a function by it's name and 
pass in the mission name as an argument or call function parametter.


The script now will have two different parts called function definition and main part of the script which is the main call.
This call the script.

The return statement is use instead of the exit statement in a script that has multiple calls in Main.
So that if an error occur the script wont stop or exit, it will continue till the end of the scripts (Main calls)
At the end you will be able to see where the script fail and go back to fix it.


