# Jandi-Linux

# Install

```
git clone https://github.com/KYHSGeekCode/Jandi-Linux.git
cd Jandi-Linux
cat x?? > Jandi
chmod +x Jandi
```

# Run
```
./Jandi
```

# Desktop launcher
```
[Desktop Entry]
Encoding=UTF-8
Name=Jandi
Comment=Jandi
Type=Application
Exec=nohup /<path>/Jandi-linux-x64/Jandi &
Icon=/<path>/Jandi-linux-x64/resources/app/icon.png
```
Make this file in desktop and copy it to `/usr/share/applications/`.


# How to make it?

1. Install https://github.com/nativefier/nativefier

2. Run:
```
nativefier -n Jandi https://web.jandi.com/
```
