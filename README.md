# Discord Theme to have the laggiest experience ever!

DMs           |  Servers
:-------------------------:|:-------------------------:
![Shows the DMs and Groups with the style applied](https://github.com/user-attachments/assets/84cbb1c5-212a-4c0e-9e48-52ca3e00b59d) |  ![Shows a random channel in a server with the style applied](https://github.com/user-attachments/assets/d6c44499-1665-470a-8c6c-3a66e3b84a41)


> [!NOTE]
> Previews are capped to around 16 fps, and the [Demonstration](https://github.com/MiniDiscordThemes/Demonstration) theme made it ***even*** more laggier.

> [!WARNING]
> ## CODE CAN BE BROKEN: if needed, file an issue following the template.
> I will try to optimize the theme when I have more time on my hand, however the code is currently a mess (I am **not** keen to do a full rewrite).

# How To Install:

1- With QuickCSS (or any CSS editors from your client):

`@import url("https://raw.githubusercontent.com/kruoni/HoverForever/refs/heads/main-theme/discord-theme.css")`

2- With the raw link (for use with Vencord's online theme, or any other online import using raw links):

`https://raw.githubusercontent.com/kruoni/HoverForever/refs/heads/main-theme/discord-theme.css`

3- Save as a css file:

Save this link as a file and you'll get a .css file ready to be used: https://raw.githubusercontent.com/kruoni/HoverForever/refs/heads/main-theme/discord-theme.css

## Customization

### The :root variables are: 
```
:root {
    --avatar-wrapper-background: /*YOUR OWN IMAGE*/;
    --avatar-wrapper-background-size: 216px;
    --app-background: transparent; /* change to #232328 to remove transparency*/
}
```
Check below for more details. 

### You can change the Image that appears on the avatar Wrapper.
It respects Discord's banners' size (600x240px). I tried to make it fit the wrapper, so custom sizes might be jamky.
```
:root {
    --avatar-wrapper-background: /*YOUR OWN IMAGE*/;
    --avatar-wrapper-background-size: 216px;
}
```
![image](https://github.com/user-attachments/assets/f6e56e8f-7686-4375-91f4-313c20ac17b7)


### Transparency is enabled by default (for *Vencord*, you have to enable "window transparency" in its settings, for other clients, I sadly do not know how to do so, so check for a setting mentioning transparency).

![image](https://github.com/user-attachments/assets/bd6063c2-91cc-49d4-bd24-755ed3c8fe9f)

To disable the effect, just change the value in the :root part:
```
    --app-background: transparent; /* change to #232328 to remove transparency*/
```
