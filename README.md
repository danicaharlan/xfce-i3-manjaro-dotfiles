# xfce-i3-manjaro-dotfiles
dotfiles for my work-in-progress manjaro xfce4 install with i3-gaps as the wm

![rice-2021-07-20](https://user-images.githubusercontent.com/61087445/126407925-925af0e2-9126-4b9e-8f3e-63c3aef797c4.jpg)


dependencies:
  i3-gaps nitrogen picom
  
:: replace xfwm4 with i3, and xfdesktop with nitrogen

:: open your xfce4 settings window and select session and startup

:: select current session and set xfwm4 and xfdesktop to never restart

:: select application autostart and click on the + / add button

:: an add application window will open, name it 'i3wm', description - something descriptive, commands, i3, trigger - on login

:: do the same for nitrogen, put the name as 'Nitrogen' and for the command, put 'nitrogen --restore'

:: open keyboard options in xfce4 settings, select application shortcuts, remove all shortcuts

:: reboot

:: vim ~/.config/i3/config and replace it with my dotfile :)

:: open your app drawer and click on picom

:: super + shift + r

:: enjoy!
