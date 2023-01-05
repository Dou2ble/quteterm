# Quteterminal

A Suckless alternative to QTerminal. It uses PyQt5 and QTermWidget.
Since it uses the qt framework it works natively in both wayland and x11.
The config is written in jsonc (JSON with Comments)




# Initial Setup
git clone the repo:
```bash
git clone git@github.com:Dou2ble/quteterm.git
```
```bash
cd quteterm
```

install the required pip packages:
```bash
pip install -r requirements.txt
```

move the config file to the right destination:
```bash
mkdir -p ~/.config/quteterm
```
```bash
mv config.jsonc ~/.config/quteterm
```

chmod the executable:
```bash
chmod +x quteterm
```

run the executable
```bash
./quteterm
```

# TODO:
- [ ] Add copy & paste functionality
