# Souna's Arch Tools 🐧🛠️
Welcome ! Here's one of the tools I use on my Arch installation, and it's obviously subject to evolution and improvement.

The main goal of this kind of repo is to keep "backups" in case I break anything.

Also it'll be very useful for my **future custom arch install interactive script** 🔥.

### Oh ? Interested by using it ? Nothing special but.. Why not.

Just clone the repo by typing the following lines in a terminal

```bash
git clone https://github.com/SounaVR/slstatus.git
cd slstatus
sudo make install
```

Now you can use `ln -sf` to a folder in your PATH and add it to your startup file once you're done configuring it.

### Editing the config 🎨

Edit the `config.def.h` to suit your needs, then do

```bash
rm config.h
make
```