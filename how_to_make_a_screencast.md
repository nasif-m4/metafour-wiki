# How to make a simple screencast

We are going to talk about making a simple screencast. We shall assume for the time being the system to be debian variant. The ideas can be applied to other operating systems as well.

## Install necessary softwares

### Sublime text
---

1. *Sublime text*
    1. Go to sublime text [website](https://www.sublimetext.com/3) and download the version for your operating system (Do not use the portable version).
    i.e. For 64 bit Linux based system download the **64 bit** version.
    > To find out about your linux version, type this in terminal and hit enter

    ```bash
    uname -a
    ```
    i.e. Here is a sample output
    ```txt
    Linux tanjim-m4 4.4.0-89-generic #112-Ubuntu SMP Mon Jul 31 19:38:41 UTC 2017 x86_64 x86_64 x86_64 GNU/Linux
    ```
    Notice the x86_64, it means 64 bit.

2. Go to downloaded location of the package, and extract the package

```bash
tar xvjf sublime_text_3.tar.bz2
```
3. Using super user privilege copy the extracted folder to `/opt` folder. `cp <sublime text folder name> /opt -r`. i.e.

```bash
cp sublime_text_3 /opt -r
```
Now, sublime text should be available from your app panel. If not, give it a minute or two.

### SimpleScreenRecorder
---

```bash
sudo add-apt-repository ppa:maarten-baert/simplescreenrecorder
sudo apt update
sudo apt install simplescreenrecorder
```

### Install sublime text `Package Control`
Open sublime text. Then follow the instructions given [here](https://packagecontrol.io/installation) to install `Package Control`

Once `Package Control` is installed, install `Plain Tasks` package by
> pressing `Ctrl` + `Shift` + `P` <br>
> typing `package control` and hitting `enter` <br>
> typing `plain tasks` and hitting `enter`

![](http://i.imgur.com/zs0PIy9.gif)

### Making screencast
Open `SimpleScreenRecorder` and make screencast.

![](http://i.imgur.com/CCqX1vm.gif)

[Sample screencast made for 365tickets](https://drive.google.com/a/metafour.com/file/d/0Bwos8LoJf-HPQWpIYXZuUm84ZkE/view?usp=sharing)