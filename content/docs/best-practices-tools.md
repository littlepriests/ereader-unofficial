---
title: Best practices and tools
weight: 3
---

There are certain tools that can make your life easier while you personalize. I'll describe each and why you might want to take some time signing up for new tools. 

## Back-up folder

I recommend creating a folder to house all the resources (images, files, plugins, installers etc) in an area on your PC. I keep mine in a folder named **Kobo Resources**. It has screensaver images, icons, books, and a copy of my entire `KOBOeReader(D:)` directory. 

When you start tinkering with devices, it's good practice to have a back up somewhere so should you nuke your software, you can drag and drop your back up from a save point. 

## GitHub

Creators of plugins and patches will typically host them in GitHub repositories. You can think of a repository (or repo) as a landing page for packages of code that make your device do something it doesn't do out of the box.

I strongly recommend [creating a GitHub account](https://github.com/signup) so you can star repos for plugins you're using. Here are some other benefits of just having a GitHub account: 

* You can [file issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/creating-an-issue) with creators of certain plugins, which alerts them of potential buggy or unexpected behavior. Other users can help since issues are public.
* If you want to create your own plugins and patches, you can house them in your own GitHub repo, where users can star and circulate them to other readers.

Everything cool happens on GitHub, honestly. I have repos saved for pirating, adding apps to my phone, and using other open source software. It's neat. 

## VS Code, TextEdit, and Notepad

If procedures for a particular plugin say to open a file in a text editor, they usually mean something that lets you edit files in plain text. The typical recommendation is your operating system's text editor (like TextEdit and Notepad), but I recommend [installing VS Code](https://code.visualstudio.com/download). 

* VS Code is an interface that lets you manage files and folders without juggling multiple File Explorer windows.
* You can search, open, and edit files directly in VS Code without opening other windows.
* It's customizable and out of the box it gives you a clean interface for handling code.

One use case where VS Code really helped me was updating icons in Koreader. I had to find the original file names in a deeply nested folder inside `.kobo`, then create a new folder that overwrites those icons for Koreader. The file names had to be the same. I use VS Code in split window view so I could more easily edit icon names without losing my windows in a file explorer.

Another use case is tracking your changes. VS Code differentiates new files, folders, and images from existing resources. If you add a folder but forgot where you put it, VS Code will have it highlighted until you save. 

## Let's review really quick

Here's my suggested PEMDAS before we start downloading files and messing with our device:

1. Create a back up folder on your PC for your Kobo device.
2. Sign up for a GitHub account so you can bookmark repos.
3. Familiarize yourself with a text editor, and maybe consider installing VS Code. 

Once you've done one or all of these things, you're in a good place to [install Koreader](/docs/install-koreader) and [customize your Kobo](/docs/customize-koreader)