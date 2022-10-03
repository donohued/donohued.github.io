---
title: Hey, How Are Ya?
date: 2022-10-1 1:13:00 -500
categories: [Random,Life]
tags: [blog,programming,ai,art,life]
---

# Welcome

Welcome to the future of my internet presence. I'm kind of just figuring out everything at the moment, so here is a list of my pc specs I guess.

* Zotac Gaming RTX 2070
* Corsair Vengeance RGB PRO 32GB
* AMD Ryzen 7 2700X
* MSI Performance Gaming AMD X470

Yeah that is actually about it for the main PC parts. The case is nothing special and the cooler is stock. I want get a new case at some point in the future, and maybe upgrade my storage too. Idk man, i feel like a child for sime reason, typing this all out. Like, HEY LOOK AT ME. idk man.

## Code

Here is a little code sample from a game thing I have been working of for a little while now. Out of context it may not make much sense. but that's okay. I will be posting aaaaaaaall about it on this website soon. :) 

```c#
public static void PrepLevel(LevelObject level, int warpID){
        //Static method to start the level loading process.
        //run animations for hiding the loading (black screen) ((move elsewhere???))
        if(loadedLevel){
            Destroy(loadedLevel);
            curLevelObject = null;
            levelWarps = new List<Warp>();
        }
        instance.LoadLevel(level, warpID);
    }
```

You can see how I just insert my random thoughts into my code a little bit. Kind od silly goofy ahh. By the way, I have quickly learned that visual studio code does NOT have any sort of spell check. Maybe there is an extension or something I can install.

## Photos

Here is a little bit of AI generated art that I have created. Most of this was actually from earlier today (or yesterday, i guess). Ill be adding more AI art in the future, and maybe even art projects that are not AI generated in the future.

So I am still having some problems? The theme im using came with a github actions file that is meant to perform certain tasks to build the site from the markdown and everything. However, it is instead givving me an error, adn the image files are not wanting to load when I run serve the Jekyll app locally.