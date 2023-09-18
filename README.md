# Custom Terminal Config With Starship

After trying a few different ways to customize my Terminal, such as Oh My Zsh!, PowerUser10k, and using iTerm2, I decided to return to the default app and find try a different approach. After some searching, I found Starship, and below are the steps I took to give Terminal the look and capability I need.

*Note: I use a Mac and the prompt icon I'm using is available of Apple's [SF Symbols](https://developer.apple.com/sf-symbols/). If you're on another system, you may or may not need to choose a different prompt icon.

# How to copy my config:
1. Download the starship.toml file from my repo above.
2. Find the downloaded file on your system.
3. Move the file into a folder of your choice within your User folder. My config file is in a **zsh** folder I created at this path:
```markdown
<your-home-folder>/.config/zsh/starship.toml
```
4. Use a text editor app to create a text file named **".zshrc"** if you don't already have it in your home folder. Don't forget to add the "." before the letters.
5. Copy the following settings:
```markdown
# Starship Init
eval "$(starship init zsh)"


# Starship TOML Path
export STARSHIP_CONFIG=<path-to-your-file>/starship.toml
``` 
6. Change the "\<path-to-your-file>" to your own path to the file.
7. Save the file.
8. Open your terminal and you should see the following:

![Cusomized Starship Terminal Prompt](/ss0.png "Cusomized Starship Terminal Prompt")


You can change the prompt symbol by opening the **"starship.toml"** file in a text editor app and  adding whatever prompt symbol you want in place of the chevron right symbol.

Further cusomizations can be done by following the instructions on the [Starship Configuration](https://starship.rs/config/#prompt) page.

**Happy Terminal-ing!** 😁