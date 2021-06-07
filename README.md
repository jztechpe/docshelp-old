# docshelp
Repository that contains JZ TECH help documentation for end users

# How to contribute?
1. Install Ruby on your machine. If Linux it is already installed. If Windows, use this https://rubyinstaller.org/downloads.

2. Install NodeJs on your machine.

3. Install VSCode on your machine.

4. Open VSCODE on your folder where you want to start changing the theme.

5. Use Git Clone command inside vscode.

6. npm install

7. And then you follow these instructions

First run this command to install ruby bundler package.
```
gem install bundler
```

Then execute this:
```
bundle exec jekyll s --livereload
```
**if the console show an error like this:** "Unable to load the EventMachine C extension; To use the pure-ruby reactor, require 'em/pure_ruby'"
run 
```
gem uninstall eventmachine
```
```
gem install eventmachine --platform ruby"
```

Open C:\Ruby27-x64\lib\ruby\gems\2.7.0\gems\eventmachine-1.2.7-x64-mingw32\lib\eventmachine.rb

Insert 
```
require 'em/pure_ruby' if not defined?(EventMachine) 
```
at the top of the file

(based on https://jekyll-theme-docs.netlify.app/docs/development)

This will build and then open a local server like localhost:4944 and then you can open a browser, to see the live updates you make to the files.

8. To commit your changes, in VSCODE use the Git Commit command to update your local repo, then Git Push to upload to the server remote repo.

