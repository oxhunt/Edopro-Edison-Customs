Follow this guide to setup: https://github.com/ProjectIgnis/CardScripts/wiki/Enviroment-Setup-and-required-programs#keeping-your-files-in-a-repository

# Software
Use Datacorn to modify the database

# Selected card ids

every card has its original id which has been modified by making it 9 digits long and prefixed with a 7. In case of less than 8 digits ids, zeros have been added as padding.

examples:
- 9126351  -> 709126351
- 44509529 -> 744509529


# How to apply these modifications to your EdoPro
Add these to the config.json file.

```
{
    "url": "https://github.com/oxhunt/Edopro-Edison-Customs",
    "repo_name": "Edison Cards",
    "should_update": true,
    "should_read": true
}
```