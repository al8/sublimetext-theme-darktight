A dark theme that also compresses display elements for tightness

based on Default.sublime-theme

The easiest way to install this package is using the sublime package control located at: http://wbond.net/sublime_packages/package_control

You installing it by pasting into console (ctrl+`, next to the "1" key)

import urllib2,os;pf='Package Control.sublime-package';ipp=sublime.installed_packages_path();os.makedirs(ipp) if not os.path.exists(ipp) else None;open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read())


then ctrl+shift+p
package control: add repository:
		"https://github.com/al8/sublimetext-theme-darktight"

and then

ctrl+shift+p package control: install package
choose sublimetext-theme-darktight

The theme is now installed. To use, ctrl+shift+p "preferences user global settings" to open the preferences file.
If the file is empty, add everything below including the braces. If other items are in the file, add a line similar to below:
{
    "theme": "Dark Tight.sublime-theme"
}
