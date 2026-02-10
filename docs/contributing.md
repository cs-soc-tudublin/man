---
title: Contributing to man
created: 2026-02-10T15:41:23
modified: 2026-02-10T15:54:54
tags:
   - general
---

# Contributing to `man`

`man`, or `manpage` is CS++'s operational docs.

These docs focus on the non-technical area of CS++ and covers everything from role definitions, tasks, events and other procedures we might need to successfully run the society.

This wiki is maintained through a Git repository that can be found [here](https://github.com/cs-soc-tudublin/man), and is best edited through [Obsidian](https://obsidian.md/).

# Cloning the Repo

First, clone the repo. For this you will need git installed and configures

```bash
git clone github.com/cs-soc-tudublin/man.git
```

Then open Obsidian and set **`man/docs`** as your vault directory! Setting it to just **`man`** will include more files than you need, but will still work.

# Modifying a Page

Find the page you want, and modify it. Once that it done, use `CTRL + P` or `CMD + P` to open the 'Command Palette' and search for `Git: Commit-and-Sync`. Once this is selected, press `ENTER` and it will automatically send your changes up to GitHub which will automatically deploy them after about 2 minutes!

# Creating a Page

This is the most common task outside of modifying pages.

Find the directory you want to put the new page in, right click it and press `New Note`. This will create the file and it's title will become the filename.

Once you've done that, press `CTRL + P` or `CMD + P` (depending on OS) to open the 'Command Palette' and search 'docs'. You should see an option that says `Clerk: Create a docs page`. Press `ENTER` while this is highlighted and you will get a pop-up.

Enter the Page title (Which is displayed on the website) and any tags (Like the category this page is in. I.e. `handover`), then click 'Submit'. This will create the relevant `Properties` that are needed to properly display the page.

Once you have finished creating your page, follow the same procedure found in `Modifying a Page` above.

# Creating a Directory

To be finalised
