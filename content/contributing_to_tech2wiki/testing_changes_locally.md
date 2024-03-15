---
sort: 700
---

# Testing changes locally

You can test the changes locally by using a local installation of Ruby and Jekyll.

## Running Ruby/Jekyll on Windows

To run the Tech2wiki locally on you Windows (virtual) machine additional software is required

### Requirements

- Microsoft Windows 10
- [Ruby+Devkit 2.7.x (x64)](https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-2.7.2-1/rubyinstaller-devkit-2.7.2-1-x64.exe)
- [GitHub Desktop](https://central.github.com/deployments/desktop/desktop/latest/win32)
- [Microsoft Visual Studio Code](https://code.visualstudio.com/docs/?dv=win)

Optional

- [Github Pages Markdown Cheatsheet](/assets/pdf/markdown-cheatsheet-online.pdf) to peek at while creating content
- [7Zip](https://www.7-zip.org/download.html) for ease of (de)crunching files
- [GIMP](https://download.gimp.org/pub/gimp/v2.10/windows/) to beautify the visual content

### Creating a local Jekyll instance

- Download the [Ruby+Devkit 2.7.x (x64)](https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-2.7.2-1/rubyinstaller-devkit-2.7.2-1-x64.exe)
- Run the setup using the default values
- Have the installer run the `ridk install`, as per default installation
- Press `Enter` to use the default
- Start a new `cmd.exe` to ensure that the environment variables are freshly loaded.
- start `gem install jekyll bundler` on the command line interface

### Starting a local copy of the website

Start `cmd.exe`

Navigate in the command line to the cloned copy of the [Tech2Wiki repository]({{ site.repo }})

`cd c:\development\tech2wiki.com`

Start the Jekyll in webserver mode

`bundler exec jekyll serve`

When hitting a `GemNotFound` error please run the `bundler update`

Start a web browser for `http://127.0.0.1:4000`

You can easily modify the website by changing the markdown files prior to uploading it to your GitHub repository.

_Note:_ It may take some seconds before the changes are visible in your local instance of the website.

---

## Running Ruby/Jekyll on Linux

To run the Tech2wiki locally on your Linux (virtual) machine additional software is required.

[insert instructions]

---

## Running Ruby/Jekyll on MacOS

To run the Tech2wiki locally on your MacOS (virtual) machine additional software is required.

[insert instructions]

---
