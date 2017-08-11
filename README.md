# Added Tools of Studio Caché - Intersystems
Adding tools in studio Caché Intersystems

Fork of https://github.com/intersystems-ru/cache-tort-git and adding tools for automatize proccess of developing

- Import and compile all sources imported
- Compile and run test automatized

Added menu tools in Studio 
- Testar - Default menu in language "Portuguese-Brasil", case your language be english, it's this mapped and installing in initializing studio plugin.

# Configuration
In environment shared is necessary configure the mapping globas of data configuration(ECP).
- ^Git.Compile - Data of sources for compile after import

It's not necessary configuration if not is shared environment

Import class and compile the class imported, after configure your version control with class(%SourceControl.Git).
Reload your studio, then it will installed language according your language defined in Caché DataBase.
