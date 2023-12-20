# Development Environment Setup Guide

## Check Versions

Ensure that you have the following tools installed and check their versions:

```bash
# Node.js
node -v

# npm
npm -v

# Firebase
firebase --version

# Composer
composer --version

# PHP
php --version

# Conda
conda --version

# Python
python -v

# Ruby
ruby --version

# SQLite3
sqlite3 --version
```

## Anaconda Commands

Manage Python environments with Anaconda:

```bash
# Initialize Anaconda
conda init

# Activate an environment
conda activate (name of environment)

# Deactivate the current environment
conda deactivate

# Display information about environments
conda info --envs

# Remove an environment
conda env remove -n (programming environment name)
```

## Visual Studio Code Commands

Enhance your Visual Studio Code workflow:

```bash
# Wrap with abbreviation
Ctrl + Shift + P

# Comment lines
Ctrl + L
```

## npm Commands

Useful npm commands for React development:

```bash
# Start local server
npm start

# Install React Router DOM for scroll nav
npm install react-router-dom

# Install React Icons for icon support
npm install react-icons

# Install React Slick Carousel
npm install react-slick slick-carousel
```

## npm GitHub Pages Deployment

Commands for deploying to GitHub Pages:

```bash
# Install gh-pages (run before deploying remotely)
npm install gh-pages --save-dev

# Deploy updates
npm run deploy -- -m "minor updates"
```

If there is an error in Babel, run the following commands:

```bash
npm install --save-dev @babel/plugin-proposal-private-property-in-object
rm -rf node_modules
npm install
```

## Laravel Commands

Run a Laravel development server:

```bash
php artisan serve
```

## Sanity.io

Set up a Sanity.io project:

```bash
# Create a new Sanity.io project
npm create sanity@latest -- --template get-started --project 3x7fujsa --dataset production --provider google

# Run the development server
npm run dev
```

## Command Prompt (CMD) Commands

Useful commands for CMD:

```bash
# Check IP addresses
netstat

# Repair registry
sfc /scannow
```

## Git Bash Commands

Basic Git Bash commands for version control:

```bash
# Update local repository
git pull

# Add all updates
git add -A

# Commit changes
git commit -m "commit for push in repo"

# Push to online repository
git push

# Check branches
git branch

# Change branch
git switch
```

## Docker Commands

Commands for working with Docker:

```bash
# Pull Pi-hole image
docker pull pihole/pihole

# Create Docker network
docker network create pihole_network
```

## Ubuntu Server Commands

Common commands for Ubuntu Server:

```bash
# Install a package
sudo apt install (name of install package)

# Reboot
sudo reboot

# Check network interfaces
ifconfig

# Shutdown
sudo shutdown -h now
```

## PuTTY Pi-hole

Manually download Pi-hole:

```bash
# Download Pi-hole
wget -O basic-install.sh https://install.pi-hole.net

# Run Pi-hole installation
sudo bash basic-install.sh
```

Other useful Pi-hole commands:

```bash
# List all files in a directory
ls -al

# Flush Pi-hole logs
pihole flush

# Update Pi-hole
pihole –up

# Display disk space usage
df -h

# Reconfigure Pi-hole
pihole -r
```

To manage Pi-hole log files, edit the log rotation configuration:

```bash
sudo nano /etc/logrotate.d/pihole

/var/log/pihole.log {
    daily
    rotate 7
    compress
    delaycompress
    missingok
    notifempty
    create 644 pihole pihole
}
```
