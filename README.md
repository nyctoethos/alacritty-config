# alacritty-config
Back up for my alacritty config
This is also gonna be a setup for alacritty because i had trouble setting it up the first time around so hopefully this will make my life easier or someone elses life easier

Installation

Install the terminal with your favorite package manager 
example 
```
arch linux
sudo pacman -S alacritty
deb
sudo apt-get install alacritty

```

For some reason i have no idea why i could NOT! find the default config anywhere on my computer
I followed the documentation and i know it doesnt create it for me and its probably just a skill issue i ended up finding a default config somewhere on github (according to this reddit post they stopped adding configs v0.13 [r/unixporn](https://www.reddit.com/r/unixporn/comments/nyjhzq/alacritty_customization/))which ill link down below and ill also link my config that has transparency so you use either or 


step two configuration

cd into your .config folder and mkdir called alacritty 
```
cd ~/.config/ mkdir alacritty

```
it should look like this

```
~/.config/alacritty
```

then use your favorite text editor to make a file called 
``` 
alacritty.toml
```
step three get the configs
```
[my config](https://github.com/nyctoethos/alacritty-config/blob/main/my-config)
[default config](https://github.com/nyctoethos/alacritty-config/blob/main/default%20config)
```

step four 
copy the configs over to the alacritty.toml folder

And your done!

This is my first time using alacritty i normally use kitty if you use my configs for alacritty they are pretty blank because i like a extremelly fast terminal i also had some issues with migrating from yml to toml I really like alacritty but i feel like it should be more out of the box instead of breaking on a fresh install of sway its whatever though makes you better at the terminal! 
thanks for reading!
