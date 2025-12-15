---
title: A beginner's introduction
weight: 2
---

This doc is for nontechnical users wanting to personalize their Kobo ereader. If you're someone who already had a Github account before your ereader, then go ahead and [start here](/docs/install-Koreader). If you're still wondering what the hell GitHub is and what people mean when they refer to the root, then you're in a good spot. 

## Create a new folder in `.kobo`

We're going to introduce a bunch of concepts by first working on a task: creating a screensaver folder in your `.kobo` directory. This task is intended to give you firmer footing on how file structures work before we install Koreader, which is famously a pain in the ass. 

### Step 1: Plug in your Kobo via USB to your PC

First thing's first: at the end of the day all devices are just a bunch of folders and files that you can view in your File Explorer, and your Kobo is no different. So, let's plug it in:

![Image that shows directory for plugged-in Kobo](images/beginners-directory.png)

The screenshot shows a plugged in Kobo (`KOBOeReader(D:)`) and all the folders that make up my Kobo's **root directory**. The difference between a root directory and regular directory is that **root** indicates the top-most level in a file structure. Sometimes people will call something root when it's not, so tread carefully and always clarify what folder they mean.

As you can see, I have a bunch of directories (or folders, but we'll use the term directories throughout these docs) that you may or may not have. `.adds` is where Nickelmenu and Koreader will eventually live; `Books` is where I keep all my epubs (which live in subdirectories by genre); `.fonts` is where I've added my own fonts; and so on. 

But let's ignore all that for now and move on to the second step.

### Step 2: Create a folder in `.kobo`

1. Select `.kobo` to open the main Kobo directory. A bunch of stuff appears; take a look, then ignore all of it for now:

    ![Image that shows an uncollapsed .kobo directory](./images/kobo-directory.png)

2. Create a new folder called `screensaver`. This is where you'll add new images so when your Kobo is asleep or powered off, you'll have something custom on display. Your directory should look like this:

    ![Image that shows an uncollapsed .kobo directory, but with a new folder called `screensaver`](./images/screensaver-dotkobo.png)

    Re: `.kobo`: This is one of two directories you'll be using quite a bit. 

    * Generally speaking, making changes to the `.kobo` directory introduces new behaviors and ~outcomes for your default Kobo software. 
    * You may occasionally need to add something to `.kobo` even if you're modifying something in Koreader, so be cognizant of what folder you're adding shit to in future procedures.

### Step 3. Add an image

Find an image and add it to screensavers. A copy from the downloaded image on your PC and a paste into the new folder will do:

![Image of screensaver folder with some images](./images/screensaver-folder.png)

I use a Kobo Libra Color, and the resolution size that gets the full screen effect is 926x1200. Don't know what aspect ratio that is, so can't help anyone there. As far as I can tell image titles and file extensions (that is the `.png` and `.jpg`) aren't super important, though IIRC my Kobo didn't load any  `.webp` images.

### Step 4. Safely eject

Any time you want to test if some modification worked, you need to safely eject. To safely eject, right click on `KOBOeReader (D:)` and choose **Eject**. Don't just unplug your device. 

![Image of menu options with Eject highlighted](./images/safely-eject.png)

Your Kobo will update, then turn on. Put your Kobo in sleep mode and the image you added should appear. :)

### Let's review really quick

Earlier I said that tinkering with devices is just playing with files and folders. Everything you do here on out will follow this broad procedure:

1. Plug in your Kobo
2. Either create a new folder and add some files to it, or add a folder to an existing folder, or even just edit some text in an existing file... or add a new file. You get the picture, lol. 
3. Eject your Kobo safely
4. Wait for an update, then see the results

There is a diabolical fifth step that involves troubleshooting and repeating all of these steps until you get the results you want. You will get a crash page sometimes... But the good news is Kobo is super forgiving with the DIY hacker spirit, so worry not. :)
 
## What's next?

You have two options for the next part of your journey. You can either:

* [Get an introduction to tools](/docs/the-tools) like VS Code, GitHub, Koreader.
  *  These aren't prerequisites and many might see it as overkill, though I do not.
  *  In other words this doc is just _my opinion_ and the suggestions that come from that, and won't be recommended in any forum.
* Or jump right into [getting started with installing Koreader](/docs/install-Koreader). 