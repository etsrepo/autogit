autogit
=======

Automatic git checkins from your text editor saves.

`autogit` will automatically commit a version of a file to a local git repository everytime a change is saved in a text or code editor.

### Why use autogit?

Some simple reasons:

* simple insurance against accidental changes or deletions.
* makes it easier to support smarter undo, backtracking, or exploratory programming.
* resume a task or track a task by seeing changes at a fine-grain level as they happened.
* light-weight, stays invisible until you need it.

Some deeper reasons:

* **Better Task Resumption:** research suggests that resuming an interrupted task or reviewing a change made by another is made easier when changes can be reviewed in an time-ordered manner (in comparision to a flat commit).

* **Auto-blog:** [automark](https://github.com/chrisparnin/automark) is a sister project that can examine a git repository and then automatically generate a markdown file, in a format suitable for publishing a blog post.

* **Personal Analytics:** Watts Humphrey has advocated the idea of tracking personal activity for self-improvement, using methods such as the Personal Software Process.  Using services, such as [codealike](http://codealike.com/) or [codeivate](http://www.codeivate.com/), you can track things like time spent editing, etc.  Tracking the *actual* changes can take this analysis to another level.

* **Api Analytics:** Frequent mistakes are made when programming or using particular apis.  This can be analyzed: "You spent 3 hours figuring out how to correctly use pygit2.create_commit(), create github issue?"


### Supported Editors

autogit is available as a set of plugins for the following editors:

* Visual Studio

* Sublime Text 2

Future editor support is planned.  [Pull requests](https://github.com/chrisparnin/autogit/pulls) or suggestions in [issues](https://github.com/chrisparnin/autogit/issues/new) are welcome!

### Installing autogit

autogit is at an *experimental* stage. 

#### Visual Studio

You can install autogit from the Visual Studio gallery:
http://visualstudiogallery.msdn.microsoft.com/45a3d62b-955e-43cb-9d91-255a837d5f35

#### Sublime Text 2

You can install autogit from the Package Control site:
https://sublime.wbond.net/packages/autogit
