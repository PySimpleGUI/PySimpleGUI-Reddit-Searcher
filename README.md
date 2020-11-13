# PySimpleGUI Reddit Searcher with GUI

## Search Your Favorite Reddit Subs


![image](https://user-images.githubusercontent.com/46163555/99123363-04dcc500-25ce-11eb-971b-fa5a7bbea999.png)



## Requirements

To use the GUI you'll need to install PySimpleGUI (http://www.PySimpleGUI.org for instructions)

One of these will install it for you.
```
pip install PySimpleGUI
pip3 install PySimpleGUI
```

You will also need to install the PRAW package which provides the APIs for accessing Reddit

## PRAW Credentials

You must signup with Reddit to in order to get own Reddit API credentials.

To sign up go to - https://www.reddit.com/prefs/apps/ 

For security reasons, the credentials are not stored in the source code, but instead in a "settings file".  The User Settings APIs were added to PySimpleGUI in Nov 2020 and are perfect for storing login credentials.  
    
When you first start the program, it will figure out that you don't have any credentials defined and will show you this settings window:
   
![image](https://user-images.githubusercontent.com/46163555/99124186-aca6c280-25cf-11eb-9aa2-0e8bbb696c00.png)


You can also use the "Settings" button in the main window to bring up the settings window.  

## Search History

The items you search for are stored in the settings file as well.  This makes future searches easier as you can select the search term from a drop-down list instead of typing them in.


## Running

Once the packages are installed, you only need to run the single Python file found in this repository - `Reddit_Searcher.py`

When running on Windows, launching with `pythonw` instead of plain `python` will start the program without showing a console window.



## Hungry for more?

If you want more examples like this one to help in creating your GUI, then be sure and check out the many programs found at http://Demos.PySimpleGUI.org. 

![logo500](https://user-images.githubusercontent.com/46163555/71866174-62150980-30d3-11ea-8a27-451849cd88ed.png)
