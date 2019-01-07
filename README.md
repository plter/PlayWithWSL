# PlayWithWSL
Play with wsl 

# What is WSL?  
Windows subsystem for linux 

# Work flow   

1. Turn on wsl feature with commond `Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux` or check the `wsl` item in control panel.  
2. Search `ubuntu` with Widnows Store and install it.
3. Launch `ubuntu` and config your username and password. 

# GUI applications (Optional)  

1. `sudo apt update`  
2. `sudo apt install ttf-wqy-zenhei`
3. `sudo apt install xfce4`
4. `wget -qO- https://dl.bintray.com/tigervnc/stable/tigervnc-1.9.0.x86_64.tar.gz | sudo tar xz --strip 1 -C /`
5. Launch vncserver with command `vncserver -geometry 800x600`
6. Use a vnc viewer to connect the vncserver.

