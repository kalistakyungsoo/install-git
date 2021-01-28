[<img src="https://git-scm.com/images/logo@2x.png" width="234px" alt="Git - Free and Open Source distributed version control system">](https://git-scm.com)

# Installation and Configuration
Need to distibuted your project in control system space? First you must to download this software on [Git Downloads](https://git-scm.com/downloads)

This page consists of:
* How to install Git server on [Windows](#windows)
* How to install Git server on [Linux/Unix](#linux)
* [Initial](#initial-configuration) configuration after installation

Please, make sure that you have [downloaded](#download-source) Git according to the OS on your PC before running.

## Windows
This important to know your architecture computer. You have to download 32 bit version or 64 bit version, depending on your PC.

Open the Git file installer, and you can follow the guide on that executable file. Make sure to choose what you need and adjust it according on your specification PC.

[<img src="git/file-1.png" width="500px">](get-file-installer)

Click button `run` on this message-box to run that executable file.

[<img src="git/file-2.png" width="500px">](click-run)

After reading this GNU General Public Git license information, click the `next` button.

[<img src="git/file-3.png" width="500px">](git-license)

Select destination location, then click the `next` button.

[<img src="git/file-4.png" width="500px">](git-location)

Select components as shown below, then click the `next` button.

[<img src="git/file-5.png" width="500px">](git-components)

Choose default editor as shown below if you have installed VS Code or customize the one that you have, then click the `next` button.

[<img src="git/file-6.png" width="500px">](git-editor)

Adjusting the name of the initial branch as shown below, then click the `next` button.

[<img src="git/file-7.png" width="500px">](git-branch)

Adjusting the path environment as shown below, then click the `next` button.

[<img src="git/file-8.png" width="500px">](git-path-environment)

Choose HTTPS transport backend as shown below, then click the `next` button.

[<img src="git/file-9.png" width="500px">](git-lib-conn)

Configure the line ending conversions as shown below, then click the `next` button.

[<img src="git/file-91.png" width="500px">](git-line)

Configure the terminal emulator as shown below, then click the `next` button.

[<img src="git/file-92.png" width="500px">](git-terminal)

Choose default as shown below, then click the `next` button.

[<img src="git/file-93.png" width="500px">](git-pull)

Choose a credential helper as shown below, then click the `next` button.

[<img src="git/file-94.png" width="500px">](git-credential)

Configure extra option as shown below, then click the `next` button.

[<img src="git/file-95.png" width="500px">](git-ext-opt)

Ignore the following options, then click the `next` button.

[<img src="git/file-96.png" width="500px">](git-opt)

Wait until the process is complete.

[<img src="git/file-97.png" width="500px">](git-load)

Finally, you've installed Git.

[<img src="git/file-98.png" width="500px">](git-complete)

Open the command prompt, and use the command as shown below to know the Git version:

```
git --version
```

[<img src="git/file-99.png" width="500px">](git-version)


## Linux
Installing Git on the Debian family of distributions can use the command:
```diff
- sudo apt install git
```
or
```
sudo apt-get install git
```
on Fedora
```
yum install git
```
After that, you can check the version of git installed with:
```
git --version
```

## Initial Configuration

Before use the Git, configure *name* and *email* in your terminal or command prompt. Example:
```
git config --global user.name "Kalista Setiawan"
git config --global user.email setiawankalista501@gmail.com
```

[<img src="git/file-991.png" width="500px">](git-configure)

Let's make your first repository in Git. First, open `Git Bash` as shown below

[<img src="git/file-993.png" width="300px">](git-bash)

Use the command:
```
git init latihan-1
```
[<img src="git/file-994.png" width="500px">](git-lat1)

Set new file(s) or folder(s) in your local repository and let's try to add these files into Git Repository use the command:
```
git add <file>
```
[<img src="git/file-995.png" width="500px">](git-add-file)

Or on Windows you can go to your folder, click the `right` on mouse, and select `git bash`.

[<img src="git/file-992.png" width="500px">](git-bash)

Use the command as shown below to initialize your local repository according to the folder you open:
```
git init .
```

To add all your file(s) or folder(s) use the command:
```
git add .
```

## Basic Commands

* `$ git init` // Initialize local Git Repository
* `$ git add <file>` // Add file(s) to Index
* `$ git status` // Check status of working tree
* `$ git commit` // Commit changes in index
* `$ git push` // Push to remote Repository
* `$ git pull` // Pull latest from remote repository
* `$ git clone` // Copy or clone repository into a new directory
  
## Download Source
You can go easily to get the file by click this list.
* Download for [Windows](https://git-scm.com/download/win)
* Download for [Linux/Unix](https://git-scm.com/download/linux)

## References
* How To Install Git Windows - `Vladimir Kaplarevic` at [phoenixnap.com](https://phoenixnap.com/kb/how-to-install-git-windows)
* Cara Install Git dan Konfigurasi Awal yang Harus Dilakukan - `Ahmad Muhardian` at [petanikode.com](https://www.petanikode.com/git-install/)

## Summarized By

Author: Kalista Setiawan | Date: 21/12/2020

If you have any suggestions and critics - please contact me. <setiawankalista501@gmail.com>
