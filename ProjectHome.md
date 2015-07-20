A project to coordinate developers working toward the following goal:

> To submit such changes as are necessary into the [Android Open Source Project](http://source.android.com) and [VirtualBox](http://www.virtualbox.org) upstream codebases in order that the image produced by performing a simple "lunch vbox\_x86-eng; make android\_disk\_vdi" on the AOSP master branch, when run on a core (i.e. open source) VirtualBox host, is a full-featured Android developer platform of similar utility to the emulator.

Some of the specific goals of the project are:

  * Full mouse support, including VirtualBox's emulated USB tablet (allowing the host mouse to be used without capture)
  * Ethernet support, including an ethernet state monitor
  * File sharing between the host OS and the Android guest
  * Power management support
  * An appropriately-defined "Android" OS Type in VirtualBox
  * Hardware OpenGL acceleration through VirtualBox's OpenGL driver
  * Camera support (using host USB devices)
  * Sound support, including audio-in

In order to be completely successful, it is our goal that all of the above be accomplished within the relevant upstream codebase(s) without any additional patching required.

