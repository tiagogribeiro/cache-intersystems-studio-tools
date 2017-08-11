# Added Tools of Studio Caché - Intersystems
Adding tools in studio Caché Intersystems

Fork of https://github.com/intersystems-ru/cache-tort-git and adding tools for automatize proccess of developing

- Import and compile all sources imported
- Compile and run test automatized

Added menu tools in Studio 
- Testar - Menu in language "Portuguese - Brazil"
Added item:
- Test after compile.
- Test suite test complete.
- Test last tested.
- Clear results of unit tests results.
- Clear data of plugin. (populate - This plugin soon it will be available in GitHub, it's not default class %Populate)
- Enable and Disabled auto test after compile.

It's necessary class test.Agent for testing automatized with compile. (This class it will be available in GitHub)

# Configuration
In environment shared is necessary configure the mapping globas of data configuration(ECP).
- ^Studio.Option - Data of options menu Studio
- ^Git.Compile - Data of sources for compile after import

It's not necessary configuration if not is shared environment

# Testing in: 
- 2013.1.1
- 2016.1.3.306.0.

# Installing
- Import project in namespace %SYS
- In version control enable: %SourceControl.Git
