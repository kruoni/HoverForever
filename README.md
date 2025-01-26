# Discord Theme to have the laggiest experience ever! (uses [surCord](https://github.com/SlippingGittys-Discord-Themes/surCord) for the time being).
## Check the other branch for more frequent updates + a full theme without requiring surCord

DMs           |  Servers
:-------------------------:|:-------------------------:
![Shows the DMs and Groups with the style applied](https://github.com/user-attachments/assets/cb11d17f-3d49-4e33-ac17-c90d54d708a4)  |  ![Shows a random channel in a server with the style applied](https://github.com/user-attachments/assets/b0d8fd7e-3431-4dee-86ba-61a848484049)

*Preview might be prone to change. (I am not updating this branch anymore, however it will still be the main one until I feel like my theme is ready to be pushed)

> [!NOTE]
> I do plan to make it compatible with the default discord theme so I don't have to rely on SlippingGitty's code.

# How To Install:
1- With QuickCSS (or any CSS editors from your client):
`@import url("https://raw.githubusercontent.com/kruoni/HoverForever/refs/heads/main-surcord/discord-theme.css")`

2- With the raw link (for use with Vencord's online theme):
`https://raw.githubusercontent.com/kruoni/HoverForever/refs/heads/main-surcord/discord-theme.css`

3- Save the raw file
Same link as before (`https://raw.githubusercontent.com/kruoni/HoverForever/refs/heads/main-surcord/discord-theme.css`) but here you can save the page as a file, recommended if you want to make changes to the theme without polluting your quick css, but you'll have to check for updates.

## Customization
### You can change the Image that appears on the avatar Wrapper.
It respects Discord's banners' size (600x240px). I tried to make it fit the wrapper, so custom sizes might be jamky.
```
:root {
    --avatar-wrapper-background: /*YOUR OWN IMAGE*/;
    --avatar-wrapper-background-size: 216px /*MAKE THE IMAGE FIT THE WHOLE WRAPPER HORIZONTALLY*/;
}
```
![image](https://github.com/user-attachments/assets/2cb90838-c234-4f18-801d-90bde830c7eb)

### Transparency is enabled by default (on **Vencord**, don't forget to enable window transparency in its settings).

![image](https://github.com/user-attachments/assets/68ba8a8b-aac5-48a2-b02a-0b69cc38506e)

To remove it, you have to remove the part all the way at the bottom of the code.

> [!WARNING]
> ## CODE CAN BE A LITTLE BIT BROKEN: file an issue if so (please follow the template). 
> I will try to optimize the theme when I have more time on my hand, however, I don't even understand my own code, so this will be fun (and im **not** really keen to do a full rewrite).
