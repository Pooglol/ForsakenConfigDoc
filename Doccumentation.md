# FYI
**Things are still being added so wait :P**

<img width="245" height="243" alt="image" src="https://github.com/user-attachments/assets/2dd3cf42-aa05-466e-984e-c70c84748417" />



Hey there! Have you ever wanted to do something like make a skin, create a map, lms ETC.
Well this doccumentation will show how and help you get started

# Configurations
<img width="127" height="30" alt="image" src="https://github.com/user-attachments/assets/cc608ab7-f4a5-4d13-8108-991735dfac02" />

# LMS
Here is how to make a LMS (Last Man standing)

<img width="258" height="258" alt="image" src="https://github.com/user-attachments/assets/e99b223e-aeea-437e-baa7-e1fbb5dc8b3c" />

Firstly go into your **Configuations** or **Config** by going into your character config
Next... Go in to a Killer (or skin)'s config, and it should look like this if you're doing a killer...

<img width="836" height="577" alt="image" src="https://github.com/user-attachments/assets/0d7d71bd-b088-4592-89f5-2cdb0d797f80" />

And you're doing a skin

<img width="797" height="365" alt="image" src="https://github.com/user-attachments/assets/fdd42890-ff6b-432c-bed0-73a59666e34b" />

**Now firstly were will be doing a LMS between 2 characters(or skins)**

Now that you're there paste in this
```lua
	["Relations"] = { "007n7" },
  -- or this
    Relations = {
        "FriendElliot"
    }, 
    -- if you're doing a skin just put in the folder name of the skin
    
```
Now this will be based on who the LMS is with, so for this we're doing 007n7 and NOLI. Now paste in this
```lua
    LastManStandingEmotionalData = {
        ThemeID = "rbxassetid://0", -- your lms sound id here
        ThemeProperties = {
            Volume = 0.75 -- how loud you want the LMS to be
        }, 
        RoundTime = 10 -- put in how long the lms is in seconds in here
    }, 
```


This will add in the custom LMS and have it working!

**Now for a skin/character vs anyone**
Literally just paste in this
```lua
    LastManStandingData = {
        ThemeID = "rbxassetid://0", -- your lms sound id here
        ThemeProperties = {
            Volume = 0.75 -- how loud you want the LMS to be
        }, 
        RoundTime = 10 -- put in how long the lms is in seconds in here
    }, 
```

Here is how to paste it in if you live under a rock btw

https://files.catbox.moe/jrs679.mp4


**FYI**
putting in both WILL work. But there are big differences between the both of these

# Exclusivity
**Hey!** wanna make a dev exclusive skin or killer?
do these steps!
Firstly go into your **Configuations** or **Config** by going into your character config
Next... Go in to a Killer (or skin)'s config, and it should look like this if you're doing a killer...

<img width="836" height="577" alt="image" src="https://github.com/user-attachments/assets/0d7d71bd-b088-4592-89f5-2cdb0d797f80" />

And you're doing a skin

<img width="797" height="365" alt="image" src="https://github.com/user-attachments/assets/fdd42890-ff6b-432c-bed0-73a59666e34b" />

Paste in this!
```lua
    Exclusive = true, 
```

Works for skins and characters btw

Here is a video if you **STILL** live under a rock

https://files.catbox.moe/211oxn.mp4

_dont ask why im searching up blackcats >:(_

