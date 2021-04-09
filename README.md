# talon_sublime
Basic syntax highlighting for TalonScript in Sublime Text 3. See documentation here: http://www.sublimetext.com/docs/3/syntax.html.

The syntax highlighting rules are defined in the `Talon.sublime-syntax` file in this repository. These rules should automatically apply to any files with the `.talon` file extension. 

This repository also contains a Comments Metadata file: https://sublime-text-unofficial-documentation.readthedocs.io/en/latest/reference/comments.html for comment support.


# Installation

```
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
git clone git@github.com:2shea/talon_sublime.git
```
Restart Sublime. Talon should appear in the list of supported languages for syntax highlighting.

## Sample:

<img width="587" alt="image" src="https://user-images.githubusercontent.com/3289426/114251147-d680cd00-9954-11eb-9520-287f9f938a7b.png">

# Troubleshooting

If you delete any of these files and start seeing errors trying to load files that no longer exist, close sublime and clear out the sublime session, and restart sublime:

```
cd ~/Library/Application\ Support/Sublime Text 3/Local
rm Session.sublime_session
```
