# Single Voxel Group

## To do

 - Add members
 - Add profile pics and line of description
 - Add email address

## Running locally for development

### Visual Studio Code (GUI)

1. Visit https://code.visualstudio.com/, and download the version appropriate to your operating system.
2. Install [Live Server Extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in Visual Studio Code after it has been installed successfully. To do so, go to the Extension tab on the left navigation bar. Search “Live Server”, and the extension should show up on the list. Click on install.
3. After the extension has been installed, click the "Go Live" button appeared at the bottom right corner. This button should appear every time you open the files folder that contains the website.
4. A web browser should be launched, and now you should be able to preview the website within the local live server environment.

### Python (CLI)

**Note**: You'll need to first install [Python 3](https://www.python.org/downloads/). 

Alternatively, you can launch a live server in command line using Python. 

1. Open a command prompt or terminal window, and navigate to the directory where you want to launch the HTTP server:

```
cd /path/to/website/folder
```

2. Enter the following command:

```
$ python3 -m http.server
Serving HTTP on 0.0.0.0 port 8000 (http://0.0.0.0:8000/) ...
```

3. An HTTP server has started and now you can visit the HTTP address (http://0.0.0.0:8000).