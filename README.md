# Discord Theme where hovering is key! 

https://github.com/user-attachments/assets/5868e1fa-a43a-4ea0-82ba-3d0b77bbc478


# How To Install:

1- With QuickCSS (or any CSS editors from your client):
```
@import url("https://raw.githubusercontent.com/kruoni/HoverForever/refs/heads/visual-refresh/discord-theme.css");
```
2- With the raw link (for use with Vencord's online theme, or any other online import using raw links):
```
https://raw.githubusercontent.com/kruoni/HoverForever/refs/heads/visual-refresh/discord-theme.css
```
3- Save as a css file:

Save this link as a file and you'll get a .css file ready to be used: 
```
https://raw.githubusercontent.com/kruoni/HoverForever/refs/heads/visual-refresh/discord-theme.css
```
## Customization

### The :root variables are: 
```
:root {
    --avatar-wrapper-background: /*YOUR IMAGE HERE*/;
    --avatar-wrapper-background-size: 216px;

    /* SERVER AND CHANNEL SIDEBAR COLOR */
    --app-background: transparent;
    /* change to var(--color-bg-dark2) for dark mode, or var(--color-bg-light2) for light mode, to remove transparency */

    /* LIGHT MODE */
    --color-bg-light1: #eee8df;
    --color-bg-light2: #dad5cf;
    --color-border-light: #242322;
    --color-panel-light: #dad5cfb0;
    --text-color-light: #282724;
    --text-color-light-active: #363430;
    --background-accent-light: #dddae0;
    --background-modifier-hover-light: #d6c9e24d;
    --color-shadow-light: #9797a6;

    /* DARK MODE */
    --color-bg-dark1: #1a1a1d;
    --color-bg-dark2: #222228;
    --color-border-dark: #c0c0c0;
    --color-panel-dark: #222228b0;
    --text-color-dark: #eae4db;
    --text-color-dark-active: #d8cbbc;
    --background-accent-dark: #dddae0;
    --background-modifier-hover-dark: #d6c9e24d;
    --color-shadow-dark: #18151b;

    /* VARIOUS COLORS */
    --color-accent-button: #6823ae65;
    --color-accent-button-hover: #460f7d80;
    --color-channel-icon: #6823ae;
}
```
Check below for more details. 

### You can change the Image that appears on the avatar Wrapper.
It respects Discord's banners' size (600x240px). I tried to make it fit the wrapper, so custom sizes might be janky.
```
:root {
    --avatar-wrapper-background: /*YOUR IMAGE HERE*/;
    --avatar-wrapper-background-size: 270px;
}
```
![image](https://github.com/user-attachments/assets/c2e63bd6-17dd-47f0-9413-a56b5c017bab) ![image](https://github.com/user-attachments/assets/76df8d6c-305c-4c01-aa4f-b80fa36cf02e)


### Transparency is enabled by default (for *Vencord*, you have to enable "window transparency" in its settings, for other clients, I sadly do not know how to do so, so check for a setting mentioning transparency).

![image](https://github.com/user-attachments/assets/bd6063c2-91cc-49d4-bd24-755ed3c8fe9f)

To disable the effect, just change the value in the :root part:
```
:root {
    /* SERVER AND CHANNEL SIDEBAR COLOR */
    --app-background: transparent;
    /* change to var(--color-bg-dark2) for dark mode, or var(--color-bg-light2) for light mode, to remove transparency */
}
```
> [!WARNING]
> ## CODE CAN BE BROKEN: if needed, file an issue following the template.
> I will try to optimize the theme when I have more time on my hand, however the code is currently a mess (I am **not** keen to do a full rewrite).
