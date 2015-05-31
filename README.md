## Creating an Alias 

In this case, we are assigning the name 'chrome' to the path which will launch the chrome browser application.

    alias chrome="C:\Program Files (x86)\Google\Chrome\Application\chrome.exe"

In instances, where there are spaces in the file location, we will need to use the short hand names for folder locations.


    alias chrome="C:\Progra~2\Google\Chrome\Application\chrome.exe"

As you can see, Program Files (x86), became Progra~2, in order for the alias to work successfully.

To find the short hand name for your directory, use the command below.
    
    dir x/ C:\

This will return a list of all directories in that location.

     PROGRA~1 Program Files
     PROGRA~2 Program Files (x86)

To view the aliases you have created, go to the location where you installed cmder and navigate to the following:

    \cmder\config\aliases

