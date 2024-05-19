# Unofficial Pelican Panel Installer Beta 0.0.1
A shell script to install Pelican Panel on a VPS or Virtual Machine. (Still in development) 🚧

### Requirements:   
- Ubuntu 24.04 (Recommended) ✅  
- VPS or Virtual Machine ✅  
- IP Address ✅  
- SSL SUPPORT ❌  

## Usage  

**Only IP Addresses are supported at the moment because another script will need to be used for SSL creation**

Download and run the installer to your VM or VPS. The installer will ask you some questions.

### Download and set executable
```shell
wget https://raw.githubusercontent.com/dazeb/pelican-installer/main/install_pelican.sh
chmod +x install_pelican.sh
```

### Run the script
```shell
./install_pelican.sh
```

You can run the script more than once. For instance, if you want to create a new admin user after forgetting to create one initially, you can run the script again without negative consequences.  

## Run Webserver Config (nginx support)  

### Download and set executable
```shell
wget https://raw.githubusercontent.com/dazeb/pelican-installer/main/webserver_config_nginx.sh
chmod +x webserver_config_nginx.sh
```

### Run the config script
```shell
./webserver_config_nginx.sh
```

# Wings Installer  

### Requirements:   
- Ubuntu 24.04 (Recommended) ✅  
- VPS, Virtual Machine, LXC with nesting enabled ✅  
- IP Address ✅  
- SSL SUPPORT ❌  

Same as before, download and run the script.  

### Download and set executable
```shell
wget https://raw.githubusercontent.com/dazeb/pelican-installer/main/install_wings.sh
chmod +x install_wings.sh
```

### Run the script
```shell
./install_wings.sh
```

The script will ask you to copy the configuration from your Pelican host. Paste the config in the file and press `ctrl+x`, then `y`, then `enter` and the script will proceed.

Go into your admin panel, add the node, and create the server.
