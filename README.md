# Development Environment Setup Guide

## Check Versions

Ensure that you have the following tools installed and check their versions:

- Node.js: `node -v`
- npm: `npm -v`
- Firebase: `firebase --version`
- Composer: `composer --version`
- PHP: `php --version`
- Conda: `conda --version`
- Python: `python --version`

## Anaconda Commands

Useful Anaconda commands for managing environments:

- Initialize Anaconda: `conda init`
- Activate an environment: `conda activate (name of environment)`
- Deactivate the current environment: `conda deactivate`
- Display information about environments: `conda info --envs`
- Remove an environment: `conda env remove -n (programming environment name)`

## Visual Studio Code Commands

Handy Visual Studio Code keyboard shortcuts:

- Wrap with abbreviation: `Ctrl + Shift + P`
- Comment lines: `Ctrl + L`

## npm Commands

Useful npm commands for React development:

- Start local server: `npm start`
- Install React Router DOM: `npm install react-router-dom`
- Install React Icons: `npm install react-icons`

## npm GitHub Pages Deployment

Commands for deploying to GitHub Pages:

- Install gh-pages: `npm install gh-pages --save-dev` (run before deploying remotely)
- Deploy updates: `npm run deploy -- -m "minor updates"`

## Sanity.io

Commands for setting up a Sanity.io project:

- Create a new Sanity.io project: `npm create sanity@latest -- --template get-started --project 3x7fujsa --dataset production --provider google`
- Run the development server: `npm run dev`

## Command Prompt (CMD) Commands

Useful commands for CMD:

- Check IP addresses: `netdata`
- Repair registry: `sfc /scannow`

## Git Bash Commands

Basic Git Bash commands for version control:

- Update local repository: `git pull`
- Add all updates: `git add -A`
- Commit changes: `git commit -m "commit for push in repo"`
- Push to online repository: `git push`
- Check branches: `git branch`
- Change branch: `git switch`

## Docker Commands

Commands for working with Docker:

- Pull Pi-hole image: `docker pull pihole/pihole`
- Create Docker network: `docker network create pihole_network`

## Ubuntu Server Commands

Common commands for Ubuntu Server:

- Install a package: `sudo apt install (name of install package)`
- Reboot: `sudo reboot`
- Check network interfaces: `ifconfig`
