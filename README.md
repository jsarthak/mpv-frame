MPV video player snap for Ubuntu core to play videos on kiosk devices.

Procedure to build:
`git clone https://github.com/jsarthak/mpv-frame`
`cd mpv-frame`
`snapcraft`

Steps to install and run:
  - Copy the .snap file over to the ubuntu-core machine
  - install using:
    `sudo snap install <file>.snap --devmode --dangerous`
  - Run 
    `sudo snap run mpv-frame <videofile>
