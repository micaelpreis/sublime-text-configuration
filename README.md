# sublime_text_configuration
### My Personal Sublime Text Configuration

In this guide, I will show you how to set up your **Sublime Text 3** just like mine.

<p align="center">
  <img src="https://github.com/micaelpreis/sublime_text_configuration/blob/master/images/material-theme.png"/>
  <img src="https://github.com/micaelpreis/sublime_text_configuration/blob/master/images/seti_ui.png"/>
</p>

### 1. Installing Package Control
First let's start by installing Package Control. If you already have it installed you can skip the following step.

To install Package Control, go to **View > Show Console** and execute the following command.

	import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)

### 2. Packages Installed

There is a couple of Packages that I found to be really helpful and that can improve my productivity by a lot.

In the list below you can see what packages I have currently installed on my Sublime Text.

> All Autocomplete  
> Better JavaScript  
> BracketHighlighter  
> Color Highlighter  
> ColorPicker  
> Emmet  
> Git  
> GitGutter  
> Javascript Completions  
> jQuery  
> Markdown Preview  
> Material Theme  
> Material Theme - Appbar  
> PackageResourceViewer  
> Rails Developer Snippets  
> Rspec  
> Ruby on Rails snippets  
> Seti_UI  
> SidebarEnchancements  
> SublimeERB  
> SublimeLinter  
> SublimeLinter-contrib-htmlhint  
> SublimeLinter-contrib-ruby-lint  
> SublimeLinter-csslint  
> Terminal  

**Note:** To install packages just press (ctrl+shift+p) on Windows or Linux or (command+shift+p) on Mac OS, then select **Install Package**, search for the package you want and install it.

### 3. Configuration File

In the file "preferences.sublime-settings" present on the folder "Files", you can see my configuration file.

In there, all of my configurations for Sublime Text are present together with the configurations for the themes: Material and Seti.

To apply this configurations just copy paste them to your own file located on **Preferences > Settings-User**.
