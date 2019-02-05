# iCloud-NoSync
An Automator utility to have iCloud Sync ignore an entire folder without losing access to the folder path

# What is it?
Tired of iCloud (or `bird`) constantly running in the background uploading and downloading files excessively - especially ones you don't need synced? This workflow adds an 'iCloud-NoSync' option to your context menu in Finder that adds the iCloud `.nosync` extension to any folder and then creates a symbolic link with the original name to the new folder so it doesn't mess up applications that depend on the folder. **this is especially useful for `node_modules` folders!!!**

# How it works
- Download the repository and unzip it
- Copy the `iCloud-NoSync.workflow` file to your `~/Library/Services` folder

# How to use it
- Open Finder and find a folder you don't want to sync to iCloud
- Right-click the folder
- Choose `iCloud-NoSync` from the bottom of the context menu
