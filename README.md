# SimpleMaterialBinTool

* I made a script that might help you to unpack/pack a dragon render file [I got the source code from here](https://github.com/ddf8196/MaterialBinTool).

# Tutorial

* Download the Termux application from the [official source]() or from [f-droid]().

* Open Termux and run the command below:

Repair termux repository
```
termux-change-repo
```

Update available packages
```
pkg update -y && pkg upgrade -y
```

Install the git package
```
pkg install git -y
```

Run the following command to clone the repository
```
git clone https://github.com/rz-modder0/SimpleMaterialBinTool
```

* Run the command below to open MaterialBinTool:

Open the folder
```
cd SimpleMaterialBinTool
```

Before you can run the script, you must run the `installer` first
```
sh installer
```

After the `installer` finishes installing packages, you need to ensure that the correct packages are installed
```
java -version
```

If a message like this appears, then the package you installed is correct
```
openjdk version "17-internal" 2021-09-14
OpenJDK Runtime Environment (build 17-internal+0-adhoc..src)
OpenJDK Server VM (build 17-internal+0-adhoc..src, mixed mode)
```

Run the following command to open the main script
```
sh main
```

# Closing

* I got the MaterialBinTool file from [here](https://github.com/ddf8196/MaterialBinTool/releases).

* I made this script just for those of you who are still confused about how to unpack/repack a dragon render file.

* I apologize if there are wrong words or sentences, because currently I use Google Translate to translate my language into English, Thank you.
