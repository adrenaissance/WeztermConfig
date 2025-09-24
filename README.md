# WeztermConfig
When configuring a machine for the first time, wezterm and neovim are a must for me. For the neovim configuration you can have a look [here](github.com/adrenaissance/NeovimConfig). Here you can find the the `wezterm.lua`, which is the only necessary piece needed to configure wezterm. This is a very basic configuration as I don't need much more. You can obviously adjust it to your preference. You can have a look [here](https://wezterm.org/config/files.html#configuration-files) for more info.

## How to
Here you can find how you can setup your wezterm configuration on unix like environments (MACOS, LINUX)

**Using a script**
```bash
mkdir -p ~/.config
git clone "github.com/adrenaissance/WeztermConfig.git" ~/.config
mv ~/.config/WeztermConfig ~/.config/wezterm
```

**manual setup**
1. Create the .config directory into your `$HOME` directory if not already done so
2. Create the `wezterm` directory into your `.config` directory if not already done so
3. Create a `wezterm.lua` file inside of your `wezterm` directory.
4. Copy the `wezterm.lua` file in this repo into the newly created `wezterm.lua` file.
