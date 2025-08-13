<img alt="KLORIUS" src="/docs/images/Klorius.png">

# KLORIUS 
### Wireless-Dongle w/ ZMK Studio
This Configuration support Wireless connection between two halves and communication to a *ProMicro NRF52840*

<img alt="KLOR Layouts" src="/docs/images/klor-layouts-single.png">


## HOW TO USE

- Fork this Repository
- Navigate to Actions and enable it.
- `git clone` your repo, to create a local copy on your PC.
- `git push` your repo with desired changes.
- Navigate to "Actions" on GitHub.
- Download and unzip the `firmware.zip` archive that contains the latest firmware.
- Connect the left half of the KLOR to your PC, press reset twice.
- The keyboard should now appear as a mass storage device.
- Drag n drop the `setting-reset-nice_nano_v2-zmk.uf2` file from the archive onto the storage device.
- Repeat this process with the right half and with the dongle.
- At this point repeat the process but with the right file for each board.


## KNOWN ISSUES

- The encoder on the secondary side doesn't work yet. This is a limitation of ZMK.
- Display does not work on both side, working on this.