# MacOS Bootable Installer

## Use Terminal to create the bootable installer

<ol>
<li> Plug in the USB flash drive or other volume that you're using for the bootable installer. </li>
<li> Open Terminal, which is in the Utilities folder of your Applications folder. </li>
<li> Type or paste one of the commands below into Terminal, then press Return to enter the command. Each command assumes that the installer is in your Applications folder, and MyVolume is the name of the USB flash drive or other volume you're using. If the volume has a different name, replace MyVolume in the command with the name of your volume. </li>
<li> When prompted, type your administrator password. The terminal doesn't show any characters as you type. Then press Return. </li>
<li> When prompted, type Y to confirm that you want to erase the volume, then press Return. The terminal shows the progress as the volume is erased. </li>
<li> After the volume is erased, you may see an alert that the terminal would like to access files on a removable volume. Click OK to allow the copy to proceed. </li>
<li> When the Terminal says that it's done, the volume will have the same name as the installer you downloaded, such as Install macOS Ventura. You can now quit Terminal and eject the volume. </li>
</ol>

## Commands

Depending on which macOS you downloaded, enter one of the following commands in Terminal as instructed above.
If your Mac is using macOS Sierra or earlier, the command should conclude with ```--applicationpath``` followed by the appropriate installer path, as shown in the command below for El Capitan.

### Ventura
```
sudo /Applications/Install\ macOS\ Ventura.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume
```
### Monterey
```
sudo /Applications/Install\ macOS\ Monterey.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume
```
### Big Sur
```
sudo /Applications/Install\ macOS\ Big\ Sur.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume
```
### Catalina
```
sudo /Applications/Install\ macOS\ Catalina.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume
```
### Mojave
```
sudo /Applications/Install\ macOS\ Mojave.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume
```
### High Sierra
```
sudo /Applications/Install\ macOS\ High\ Sierra.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume
```
### El Capitan
```
sudo /Applications/Install\ OS\ X\ El\ Capitan.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume --applicationpath /Applications/Install\ OS\ X\ El\ Capitan.app
```


