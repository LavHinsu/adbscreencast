# adbscreencast
adbscreencast is a bash scrip that uses adb screenrecord and mplayer to cast android screen to your linux desktop.

To run the file, git clone or copy paste code to a file. 
The while loop is used because adb screenrecord has a max 3 minute limit. to overcome this, you can either do what i did, or recompile from source after changing the limit. this is an easier solution to that problem

make the file executable by using

`cd yourdirectory`
`chmod +x adbcast`

to run the file:

`sh adbcast`


# Images
 
![Alt text](/adbcastdemo.png?raw=true "DEMO 1")
![Alt text](/adbcastreadme.png?raw=true "DEMO 2")
