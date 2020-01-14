# PySimpleGUI Reddit Searcher with GUI

## Search Your Favorite Reddit Subs

![SNAG-0673](https://user-images.githubusercontent.com/46163555/72322826-4da5b380-3675-11ea-8bdd-de20c05f1f7e.jpg)



## Requirements

To use the GUI you'll need to install PySimpleGUI (http://www.PySimpleGUI.org for instructions)

One of these will install it for you.
```
pip install PySimpleGUI
pip3 install PySimpleGUI
```

You will also need to install the PRAW package which provides the APIs for accessing Reddit

## PRAW Credentials

You must signup with Reddit to in oder to get own Reddit API credentials.

To sign up go to - https://www.reddit.com/prefs/apps/ 

For security reasons, the credentiaols are not stored in the course code, but instead a file named `praw.cfg` that has this format.
    
Store your praw credentials this file, located in the same folder as this program in this format:

```
{ "client_id": "get from PRAW signup",
"client_secret": "get from PRAW signup",
"user_agent": "same as user name on Reddit", 
"username": "same as user name on Reddit",
"password": "your Reddit password"}  
```


## Running

Once the pacakges are installed, you only need to run the single Python file found in this repository - `Reddit_Searcher.py`

When running on Windows, launching with `pythonw` instead of plain `python` will start the program without showing a console window.



## Hungry for more?

If you want more examples like tthis one to help in creating your GUI, then be sure and check out the many programs found at http://Demos.PySimpleGUI.org. 

![logo500](https://user-images.githubusercontent.com/46163555/71866174-62150980-30d3-11ea-8a27-451849cd88ed.png)
