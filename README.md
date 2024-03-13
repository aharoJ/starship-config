<h1 align="center"><b> Angel J. Haro 
<img src="https://docs.google.com/uc?export=download&id=1JqFc6WL-cTtJBQgW9tusQAZhQ3H9hGae" alt="" height="25" >
<img src="https://docs.google.com/uc?export=download&id=1HsBpakQVutfOmxBcPbGpKdo_oGEoKJZT" alt="" height="35" >
</h1>

<!-- START  -->
<div align="center">
<a href="https://aharoj.io"><img src="https://img.shields.io/badge/website-000000?style=for-the-badge&logo=Portfolio&logoColor=white" alt="Gmail" /></a>&nbsp;
<a href="https://discord.gg/HDDQ6pUMHt"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>&nbsp;
<a href="https://twitter.com/aharoJ"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" /></a>&nbsp;
<a href="https://www.linkedin.com/in/aharoJ/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Linkedin" /></a>&nbsp;
<a href="https://leetcode.com/aharoJ/"><img src="https://img.shields.io/badge/-LeetCode-FFA116?style=for-the-badge&logo=LeetCode&logoColor=black" alt="LeetCode" /></a>&nbsp;
<br/>
</div>  
<!-- END -->

<h1 align="center"> <a href=https://aharoj.io> Visit Portfolio </a> </h1>


# dot-starship
This is my custom starship.toml config file, designed to enhance the appearance of my command line prompt. I spent hours researching colors that are appealing to programmers and hand-picking the hacked icons to create a visually pleasing and functional prompt. Each module has been carefully configured to suit my needs, and I've added personal touches like custom symbols for success and error messages. I hope you find it useful!

> OverView 
![](z/starship_alacritty.png)


> visual flags with icons
- [save][->] green 
- [re-do][<-] red 
![](z/starship_visual_errors.png)


> new icons | coloschme

![](z/starship_icons.png)


--- 

## Quick Guide
### Step 0: Install `Homebrew`


```brew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

> skip if already installed

### Step 1: Install starship


``` brew
brew install starship
```

### Step 2: Copy File  
> Copy file into your ~/.config/starship/starship.toml:

#### [my starship file](https://github.com/aharoJ/starship-config/blob/main/starship.toml)


### Step 3: Configure your own shell
[I use Fish Shell](https://fishshell.com)

- #### [configure your shell](https://starship.rs/guide/#%F0%9F%9A%80-installation)

### Step 4: Install Hacked Nerd Font
- ### [install hacked fonts](https://www.nerdfonts.com/font-downloads)


## Recommended Configurations
- ### Alacritty
- ### Tmux 
- ### Fish Shell
> Currently Updating my dot-files


--- 

### DEV DOCS 
#### Current Version
- please integrate **TMUX** to have the full experience
- script clean up with `active` && `non-active` toml scripts

#### Version 0.0.1
- Timer - Colors 
- All Icons for All Languages


#### Version 0.0.2
- A more sutle and simplistic version to pair with **TMUX**
- Removed Timer
- Remove most Icons 
- Remove most Language Icon Support
    - If you want to keep do `disabled = false` 
- Removed Battery
