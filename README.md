# Desktop Client

The desktop client's purpose is to interface and visualize telemetry data obtained from
the microcontrollers onboard UAVs and UGVs

The desktop client is a React application built with [create-react-app](https://github.com/facebook/create-react-app). It is wrapped in an
[electron](https://electronjs.org/) app that allows the React app to be ran in a desktop application.

This is the [tutorial that I used](https://flaviocopes.com/react-electron/) to set up this app.

## Requirements
* `npm version 6.11.3` or higher
* `node version v12.10.0` or higher
* If your using a windows machine, you're going to need to run the setup and run-time commands in [WSL (Windows subsystem)](https://docs.microsoft.com/en-us/windows/wsl/install-win10)

## Getting started
1. Clone the repo with `git clone https://github.com/uvic-aero/dt-client.git`
2. Set your current directory to `dt-client` with `cd dt-client`
3. Install node
  * OSX: 
    * run `brew update` followed by
    * `brew install node`
    * verify your version is up to date with `node --version`
  * Linux/WSL: 
    * `sudo apt update` followed by  
    * `sudo apt install` and finally,
    * verify your version is up to date with `nodejs --version`
4. Install npm
  * OSX: 
    * `npm` should already be installed, so just verify the version with `npm --version`
  * Linux/WSL: 
    * `sudo apt install npm`
    * verify your version is up to date with `npm --version`
5. Install dependencies for the react-electron application with `npm install` 
6. Start the electron-react desktop app `npm start` 
