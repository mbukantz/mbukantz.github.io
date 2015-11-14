---
layout: post
title: "Sublime 201: Tips, Tricks, and Packages"
date: 2015-11-12 20:39:08 -0500
comments: true
categories: flatiron_school
---

<p>In our second week at Flatiron School, Jeff <a href="http://jeffslutzky.github.io/blog/2015/10/04/sublime-hints-and-shortcuts/">blogged</a> some cool tips and tricks about using Sublime text editor.  Austin also <a href="http://gilmoursa.github.io/blog/Package%20Control/">blogged</a> about using Package Control to enhance the Sublime experience.  After using Sublime for a couple of months and doing some thorough research, I wanted to share a second edition of useful Sublime hints, shortcuts, and packages.</p>

<h3>Selectors</h3>

<p>You can select a single line of text by clicking and dragging with your trackpad, and you can do the same for multiple snippets of text by holding down your command key.  However, there are several shortcuts that Sublime provides us to more efficiently select text.  Here are a few examples:</p>

  <ul>
    <li>Command + D - Select a single word or select the next instance of the word</li>
    <li>Command + L - Select the line that you are on</li>
    <li>Command + Control + M - Select anything within the brackets</li>
    <li>Command + Control + G - Select any instance of the highlighted text</li>
  </ul><br>

<h3>Command Palette</h3>

<p>If you press Command + Shift + P in Sublime, it will open up the Command Palette.  The Command Palette will allow you to do many tasks such as installing packages, renaming a file, or saving all files.  With its easy to use search bar, the Command Palette is a great tool for developers.  Here is a snapshot of how to search for installing new packages:</p>

<img src="../images/install_packages.png"><br><br>

<h3>Advanced New File (Package Control)</h3>

<p>Speaking of package control, there is a neat package that allows you to create new files straight from Sublime.  As opposed to going to terminal to "touch" a new file, you can download the "Advanced New File" package from the Command Palette.  By clicking Command + Option + n, you can enter a new file name and/or path from the bottom of Sublime.</p><br>

<h3>Spell Checker</h3>

  <p>While I was writing this blog post, I was catching spelling errors left and right.  After a quick Google search, I discovered that you can enable spell check within Sublime.  In order to add spell checker when writing a blog post or another text-heavy document, you can append spell checker to the user preferences by copying the following command:</p>

<i>"spell_check": true,</i>

<h3>CSS Sorting</h3>

<p>Another nice to know feature in Sublime is sorting CSS stylesheets.  This can come in handy when you have long selector statements, as it is much easier to read and find the selector you are looking for when it is alphabetized.  Here is an example of before and after snapshots:</p>

<b>Before:</b><br><img src="../images/png_before.png"><br><br>
<b>After: </b><br><img src="../images/png_after.png">

<h3>Switching Tabs</h3>

When working on projects with many directories and files, like a Rails app, it sometimes is hard to navigate between each file.  However, there are some helpful commands that allow for easier navigation:

<ul>
  <li>Command T- Selects all tabs that are currently open and allows searching through each tab</li>
  <li>Command + Shift + [ - Will bring you to the previous tab</li>
  <li>Command + Shift + }- Will bring you to the next tab</li>
</ul><br>


<h3>Cross-file editing</h3>
Lets say you want to change a variable in a project, but this variable is referenced in several files in several instances.  This is where cross-file editing in Sublime can be very useful.  If you hit Command + Shift + F in Sublime, you are able to find all instances of the variable.  In the "Where" section, you would classify the folders, files, and filters you would like to apply your to your replace function.  Lastly, you can replace with the updated variable.  Here is a snapshot of how this would look:

<br><img src="../images/cross-file.png"><br>

In conclusion, I hope this was a helpful overview of some neat Sublime shorcuts, tips, and packages.  I will leave you with one more tool, <a href="https://github.com/titoBouzout/SideBarEnhancements/tree/st3">SideBar Enhancements</a>, which will also improve your workflow.  











