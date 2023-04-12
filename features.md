# features

## Collaboration

Its a real time system allowing you or many to edit the HTML.

You can still use git, your just exposing the ability to edit the HTML over the web.

## Proxy

You can put the files on the server and expose it for collaboration, and also commit to git.

you can also pull from git.

## Git LFS

For large local files you need Git LFS. All git lfs does is convert or images, vidoes, etc to a pointer in the git file system. Those pointers point to the asset that is stored in S3.

We will add minio so that you can run your own Minio Server and Git Server.

## Files

The left pane is the File System view.  Its a view of the files on the server.

So you can see what you have to work with.

You can rename files, move files, etc. 

You can search for file contents. Useful when you need to make an edit and are not sure where it is. 

## File tracking

Lets just say someone renames an Image or Video File. Then because we use CDC we can tell the User via the File Tree, or we can update the file name used in the HTML automatically.

When you want to change the video that is used on many web pages, you can just change it in the File View, and all pages using it are updated.

## Asset Registry

You can also do the opposite. If the Remote Url to the Video changes, then the Server will notice that and let you know. 

## Server side includes 

Server has a basic config that models the server side includes, and then serves the final html.

All this allows users to make html and html includes.  html includes is a really old and simple way of reusing html in many pages.

This relies on the CSS being atomic to each html file - need to check this ! Find example on suneditor


## TODO

- docker build or frontend
- Server for backend and frontend
- CDC File system watcher
- CDC Client for CLI ( all desktops ) and Froentend ( wasm )
- Github ations releaser based on tags.
