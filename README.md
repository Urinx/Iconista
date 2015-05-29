# Iconista

Learn more at http://urinx.github.io/app/iconista/

The best & most beautiful way to set your Mac OS X beautiful!

![0](./screenshots/0.png)

What
----
It's easy, save, and fast tool that helps you to change your Mac Os X default applications icon, for it looks like horrible and ugly.

Which can do the followings:
* Replace the system applications icon with default themes
* Replace the some third part apps icon
* Set the files or folders icon
* Set the wallpaper

Install
-------
Download the soure code and then unzip it.
```
git clone https://github.com/Urinx/Iconista/archive/master.zip
```
Go to `build` folder, and `Iconista` is the main program.
```
cd build/
sudo ./Iconista
```
That's all, it's very easy, right?

How
---
For help, you can do this:
```
sudo ./Iconista -h
```
Install the default icon theme:
```
sudo ./Iconista -i
```
Restore the origin system icon:
```
sudo ./Iconista -r
```
Delete/hide the app in Launchpad:
```
sudo ./Iconista -d "Safari"
```
Set icon for file or folder:
```
sudo ./Iconista -f /path/to/file /path/to/icon
```
Install the specified theme(This is NOT support now):
```
sudo ./Iconista -s "theme_name"
```

Demo
----
![4](./screenshots/4.gif)

Screenshots
-----------
![0](./screenshots/0.png)
![1](./screenshots/1.png)
![2](./screenshots/2.png)

Themes
------
There is only a default theme for now, but more themes will be added in the furtrue.

![3](./screenshots/3.png)

The icon of default theme is come from [BlackVariant (Patrick)](http://blackvariant.deviantart.com), free for non-commercial use.

License
-------
> Copyright (C) 2013-2015 Eular <uri.lqy@gmail.com>
> Licensed under the Apache License, Version 2.0 (the "License");
