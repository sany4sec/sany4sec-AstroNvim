# AstroNvim Setup

### Configured by :  Rabius sany

### First Install some package and tools

```bash
sudo apt install fd-find ripgrep cargo python3.12-venv np fonts-powerline gdu btm 7zip git wget
```

### Install latest version of nvim

```bash
wget https://github.com/neovim/neovim/releases/download/v0.9.5/nvim-linux64.tar.gz

```

### Setup the New neovim

```bash
$ 7z x nvim-linux64.tar.gz # to extract the gz file
$ 7z x nvim-linux64.tar # to extract the tar file
$ sudo mv nvim-linux64  /opt # move the extracted "nvim-linux64" to "/opt" directory
$ sudo ln -s /opt/nvim-linux64/bin/nvim /usr/bin/nvim  # Make a soft link to /usr/bin/nvim 

```

### Now start the vim

```bash
nvim
```

### Now install the AstroNvim config

> Make a backup of your current nvim folder

```bash
mv ~/.config/nvim ~/.config/nvim.bak
```

> Clone the config file to you ~/.config/nvim folder

```bash
git clone https://github.com/sany4sec/sany4sec-AstroNvim.git ~/.config/nvim

```

> Now run the new AstroNvim And Enjoy

```bash
nvim 
```

### For more : https://docs.astronvim.com/
