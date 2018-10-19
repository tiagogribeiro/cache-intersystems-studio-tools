# Added Tools of Studio Caché - Intersystems
Adding tools in studio Caché Intersystems

**New Feature v1.3**
- Added signaling of class that exists test in project tree.
- Does not signaling in namespace tree.

**New Feature v1.2**
- To configure the plugin use the terminal command: </br>
YOURNAMESPACE> do ##class(%SourceControl.Instalation.Manager).menu()

**New Feature v1.1**
- Create a class test from the options menu.
- Open test class by the class of the

-----

Fork of https://github.com/intersystems-ru/cache-tort-git and adding tools for automatize proccess of developing

- Import and compile all sources imported
- Compile and run test automatized

Added menu tools in Studio 
- Testar - Default menu in language "Portuguese-Brasil", case your language be english, it's this mapped and installing in initializing studio plugin.

Added item:
- Test after compile.
- Test suite test complete.
- Test last tested.
- Clear results of unit tests results.
- Clear data of plugin. (populate - This plugin soon it will be available in GitHub, it's not default class %Populate)
- Enable and Disabled auto test after compile.

# Configuration
In environment shared is necessary configure the mapping globas of data configuration(ECP).
- ^Git.Compile - Data of sources for compile after import

It's not necessary configuration if not is shared environment

Import class and compile the class imported, after configure your version control with class(%SourceControl.Git).
Reload your studio, then it will installed language according your language defined in Caché DataBase.

In the namespace enable in source control of the class: "%SourceControl.Git", after all options exist in studio.
(Is necessary reboot in studio)

The tests must be inside the "test" package for automation testing.

# Testing in: 
- 2013.1.1
- 2016.1.3.306.0.
- 2017.1.0 Build 720

# Installing
- Enable written in database "CacheLIB" by Portal Caché DataBases
- Import project in namespace %SYS
- In version control enable: %SourceControl.Git

Important, if you do not compile due to error 'SlackConfiguration does not exist' 
It is necessary to configure integration with Slack, rename the 
'% SourceControl.Autotamtion.Integration.SlackConfigurationSample' class to 
'% SourceControl.Autotamtion.Integration.SlackConfiguration' and recompile the '% SourceControl'

If you did not want the integration to be enabled, just rename the file and do not do any service configuration.

The version control configuration should follow the repository: 
https://github.com/intersystems-ru/cache-tort-git 

