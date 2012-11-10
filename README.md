# Sublime Text 2 lsl syntax

Syntax highlighting and code completion for Sublime Text 2 
<<<<<<< HEAD

#Installation

## Using Sublime Package Control

### Step 1: Install Package Control

Package Control is an essential Sublime Text 2 plugin and can be found here:  http://wbond.net/sublime_packages/package_control

To install Package Control, simply open up Sublime Text 2, press CTRL + ` (that's the dash key to the left of your 1 key), and then copy the following text into the command line interface that appears and hit enter:
```python
import urllib2,os; pf='Package Control.sublime-package'; ipp=sublime.installed_packages_path(); os.makedirs(ipp) if not os.path.exists(ipp) else None; urllib2.install_opener(urllib2.build_opener(urllib2.ProxyHandler())); open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read()); print 'Please restart Sublime Text to finish installation'
```
You will need to restart Sublime Text 2 to complete installation.

### Step 2: Add this GitHub Repository to Package Control

The sublime-text-2-lsl plugin is not, by default, available in Package Control, so we need to add it.

Open up Package Control in Sublime Text 2 by pressing CTRL + SHIFT + P and scroll down to the option `Package Control: Add Repository`

When you click on the `Add Repository` option, a textbox will open at the bottom of the Sublime Text 2 window.  Enter the name of this repository without the .git extension:  `https://github.com/JKolya/sublime-text-2-lsl`

Press enter.

### Step 3: Install sublime-text-2-lsl via Package Control

Now we've added sublime-text-2-lsl to our list of available packages, but we haven't installed it yet.

Re-open Package Control by pressing CTRL + SHIFT + P and scrolling down to `Package Control: Install Package`

Search for the package `sublime-text-2-lsl` and double click on it.

That's it, sublime-text-2-lsl is installed and ready to go.  No restart of Sublime Text 2 is necessary.

##Using Git

You can locate your Sublime Text 2 `Packages` directory. When inside the `Packages` directory type:

`git clone https://github.com/JKolya/sublime-text-2-lsl.git sublime-text-2-lsl`

Restart Sublime Text 2 and the theme is installed.

# Snippets

Most of the snippets where taken from [the lsl TextMate bundle](http://forums-archive.secondlife.com/54/ae/89389/1.html).
=======

###

Most of the snippets where taken from [the lsl TextMate bundle](http://forums-archive.secondlife.com/54/ae/89389/1.html).