# Blurfox

## basic setups

1. go to `about:support` and open the profile folder.
2. In the profile folder, make a new folder called 'chrome'.
3. download userChrome.css from the repo and put it on chrome folder.

#### Optional 
Make a new userContent.css on chrome folder. If you are going to use extensions like Stylus, this step isn't necessary. 

4. go to `about:config`
5. And set this flag `browser.tabs.allow_transparent_browser` as `true`.

## For Linux
The blur effect depends on the compositor not the browser. Hence the name is Invisiblefox. I won't explain that on here because every desktop envirnoment uses differnt methods for the blur. 

At least I can say I tested on two DEs. 
- Gnome + Blur-my-Shell
- Hyprland

## For Windows
For Windows, you need MICA for everyone. For Acrylic effect, use blurfox-windows, and for MICA effect, use blurfox-mica. 

Get the MICA for everyone here 
[[https://github.com/MicaForEveryone/MicaForEveryone]]

Set everything default and only set the visual style as MICA or Acrylic. 

## For macOS
Although the goal of this theme is just adding a transparency or blur and works with other themes for firefox, achieving blur on macOS requires crazy layout modifications. Therefore, most of your themes won't work with this code. I don't really recomment to use this code with other themes. 


