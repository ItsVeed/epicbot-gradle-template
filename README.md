# Gradle template for epicbot client

# Features
- Will autodetect your scripts folder and move compiled jars into it
- Will add all required dependencies to your scripts for you

# Adding a script

1) To add a script go to your settings.gradle.kts file and add the following line of code
   ```include("scripts:{your script name}")```

2) then make a directory for your new script under the scripts folder make sure your script has the following stucture ```scripts/{name of your script}/src/main/java/Main.java```

# Building the script

1) click on this icon in intelij ![](https://i.imgur.com/JT3Wh0R.png)
2) go to the scripts dropdown and search for the build run that and your ready to run your script

# Setting up in intelij
1) got to file -> Project from version control ![](https://i.imgur.com/OolQMeB.png)
2) when on this dialogue copy this [url](https://github.com/ItsVeed/epicbot-gradle-template.git) into the URL box and click clone
3) thats it now use the template as described above
