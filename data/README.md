# SportFolder Data 

This is the directory containing all data for the sportsfolder project. Most 
files are markdown with names corresponding to their section. To learn more 
about markdown check out 
[this guide](https://gitbookio.gitbooks.io/markdown/content/index.html)


## data.json

JSON data is used for minute details not rendered from markdown. The fields 
are self explanatory in many respects, however, if you search index.jade 
for the corresponding object notation, you may find the use of that particular 
field.

| images     | Images stored as background for the site. Currently the only used field is title. |
|------------|-----------------------------------------------------------------------------------|
| title      | The title of the site, currently `SportFolder`                                    |
| activities | Describes the activities icons used above that display.                           |
| tennis     | The title of the tennis section                                                   |

## activities.md

Contains information about the activities, to be rendered bellow the icons in 
the **activities** section.

## tennis.md

Describes the contents of [TennisFolder](http://tennisfolder.com) and should 
be used to tell more about it.

## title.md

The information that is shown below the title section and SportFolder logo.


# PS

Feel free to modify the templates directly, just don't modify anything in 
the static directory -- other than images perhaps.