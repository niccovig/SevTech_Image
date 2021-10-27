# SevTech Docker Image

This is a sample docker-compose yaml file to get a full up and running server istance of SevTech Ages.

## Installation

---

### Linux

Clone and enter the repository

    git clone https://github.com/TheRealLorenz/SevTech_Image.git
    cd SevTech_Image

Execute the setup script

    chmod +x setup.sh
    ./setup.sh

This will create a folder for game data and will download the .zip server file

### Windows

If you appear to have git installed on powershell clone and enter the repository

    git clone https://github.com/TheRealLorenz/SevTech_Image.git
    cd SevTech_Image

Otherwise download the .zip file and extract it in a folder of your choice.

Then execute the .ps1 script either by executing it via powershell

    ./setup.ps1

Or by double clicking it.

## Running the server

---

### Linux

Simply run

    docker-compose up

*with '-d' if you wanto to detach the container from the terminal*

And you're done!

## Windows

WIP
