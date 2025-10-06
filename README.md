<img src="images/icon.png" width="80" height="80" />

# Allumeria Translator

Allumeria Translator can be used to translate and merge Allumeria's (By Unomelon Games) keys.txt files. Enter the default (untranslated) keys.txt file's path, your recent translation keys.txt file's path and the path where the new merged output .txt file is added to. The tool will go through all of the keys and update them if a translation is found and if not, the keys with missing translations are listed. -set command can be used to directly set or update translations within the program.

Before using the program create a translation folder to \Steam\steamapps\common\Allumeria Playtest\res\translations

Official guide for translations: https://steamcommunity.com/sharedfiles/filedetails/?id=3576375349

If you face any issues with the program or have ideas for it, you can join Allumeria's official Discord server where I have a post at translations > Allumeria Translator https://discord.gg/Ddh3acCtVx

    === Allumeria Translator Commands ===

    -help                    : Show this help message

    -paths                   : Set file paths for default (untranslated), translated, and output files.
                               To overwrite the translated file, set its path to be the same as the output file.
    -pathlist                : Display the currently set file paths for default, translated, and output files.
    -overwrite               : Set the output file path to be the same as the translated file.
                               All modifications from updates will be applied directly to the translated file.

    -check                   : Compare default and translated files to see if an update is needed
    -merge                   : Merge a new keys file with your old translations
    -print                   : Display contents of a file
    
    -find <text>             : Searches the output file for any key or translation containing the given text
    -get <key>               : Search the output file for a specific key
    -set <key> <translation> : Manually set or update the translation of a specific key in the output file
    -auto                    : Automatically go through all untranslated keys in the output file.
                               Ignored keys are skipped. Type '-' to skip a key without changing its translation.
                               
    -ignore <key>            : Add a key to the ignored keys list. Ignored keys will not be counted
                               as missing translations.
    -unignore <key>          : Remove a key from the ignored keys list so it will be counted
                               as a missing translation again.
    -ignorelist              : Display all keys that are currently ignored. 

    -clear                   : Clear the screen
    -exit                    : Exit the program
