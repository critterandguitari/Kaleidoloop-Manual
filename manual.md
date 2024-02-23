# Kaleidoloop User Manual

Kaleidoloop is portable sound recorder manipulator! Use this manual to help record and play back sounds!

## Getting Started

### Safety First!
As with all audio recording devices, make all cable connections and slowly turn up the volume. This will avoid unexpected bursts of sound from your speakers or headphones. Protect your ears!

### Quick Setup
You probably want to get started right away! Here are a few steps to get you making music.
   
1. Use Batteries or connect the USB power supply to an outlet, then to the USB-C jack on rear panel.  
2. Power on by pressing and holding the top-right button until the LEDs flash.
3. Record a sound by pressing the center button. The center LED turns red during recording. 
4. Press the button again to stop recording.
5. Playback begins in a loop.
6. Use the mode button change playback mode and use the knobs to manipulate plaback.

## The Front Panel


## Using Your Kaleidoloop

### Power

First connect the USB-C power adapter. Connect the adapter to a power outlet, and then connect its plug to the leftmost port on the back of Kaleidoloop. 

Once Kaleidoloop is connected to power it will automatically power on. The LEDs (M) will illuminate, which means the unit is powered. If Kaleidoloop is already connected to power, press the Power Switch (E) for one second, or until the LEDs turn on. 

The same button is used to power down. Hold the button for one second, or until the LEDs turn purple. Don't fret! Everything you've recorded is saved.

### Sound Output

Kaleidoloop outputs audio from the speaker or the top right 1/4" audio Output Jack. Connect a 1/4" patch cable to speaker or mixer. When a cable is attached the speaker is disabled.

Audio format: 48 kHz, 16-bit.

### Sound Input

Kaleidoloop inputs audio from the top left 1/4"  audio Input Jack. Connect a cable to an instrument, synthesizer, mixer, microphone, electric guitar... 

Audio format: 48 kHz, 16-bit.

### Navigating

Everytime you record a loop it is stored in a growing list of loops. Navigate these sounds using the next and previous buttons.

### Volume Control

Turn it up!

### Record

Press the center button to begin recording. Press again to stop recording. When you stop recording the sound will immediately being looping. Playback will continue during record, so if you are recording with the mic and don't want it bleeding thru, turn it down.


## File Management 

### Disk Mode 

Let's say you like the loops you've made and would like to hear them on a computer. If Kaleidoloop is powered from a power outlet, turn it off. If it is powered from a computer's usb port, you're halfway there! Connect a USB-C cable (like the one used to power the unit) to a computer's USB port). 

While Kaleidoloop is on and connected to the computer, press the NEXT button and while holding it down press the MODE button.  Release both buttons and the Kaleidoloop will enter disk mode.

In Disk Mode, Kaleidoloop itself is no longer in recording mode. The LEDs will flash red/green/blue to indicate disk mode. The buttons will not have their normal functions. Instead each will emit a test tone when pressed. This is purely for testing procedures. Do not be alarmed if you press a button and hear a beep. 

### File Management in Disk Mode

On your computer, open a file browser (Finder for Mac, Explorer for Windows). In the disks, select 'KALEIDOLOOP'. In the 'recordings' folder are all the recorded loops.


**Important**: When you are done using Disk Mode, first eject the KALEIDOLOOP drive from your computer as you would for a standard USB drive or external hard drive. 

Exit Disk Mode with the same key combo: pressing NEXT and while holding it down pressing MODE.

![](images/modes.png)


### Loading Your Own Loops
The Kaleidoloop will save its recordings with numbers: 1.wav, 2.wav, and so on. You can add your own files to the SD card using Disk Mode. The files can be named whatever you would like, but know that the Kaleidoloop will sort the files by number first and then letter as shown here:

![](images/recordings.png)

Some file tips:

* Please avoid 'spaces' in file names. Use hyphens and/or underscores instead: *0_cool-drums.wav*. 
* Files should be in 48KHz 16-bit .wav format.

## Setup Examples


## Specifications	

### Audio Settings

Kaleidoloop records and plays back audio at 16-bit 48kHz. Recorded audio files are in the WAV format. 

### MicroSD Card

The operating system and all recordings are stored on the Kaleidoloop' microSD card. Each unit comes with an 8 GB card installed. This card can be inserted into a Windows computer to browse files and make changes, just like in Disk Mode. This feature is not supported on Mac, but using Kaleidoloop in Disk Mode will accomplish the same task. 

There is a 1 GB partition for the operating system and a 7 GB partition for audio recordings. At 16-bit 48khz, that's about 20 hours of record time. 

If a larger partition for audio recordings is desired, you may use a larger microSD card as long as it is first flashed with the operating system. Kaleidoloop will detect the remaining space upon its first boot up. The remaining space will become the new audio recording partition. 

### USB 2.0 Jack

There is a USB 3.0 jack on the rear next to the microSD card slot. This jack does not have a specific purpose at the time of this release. Stay tuned for future OS updates.

## Burning microSD Card Disk Image

Burning a new disk image on the micro SD card will reset your Kaleidoloop to the factory state. This is useful to update to the latest Kaleidoloop OS, or to fix a problem with the microSD card.

This will completely wipe the microSD card clean, so make sure to backup anything on there that you need. See **Disk Mode** for information on downloading your files or moving them to a USB drive. You can also use a brand new card if you wanted to keep your old OS available.

Follow these steps to burn a new microSD card:

1. Download the microSD card disk image to your computer: 
<br> [](asdf)
<br> Current OS release: Kaleidoloop v1.0. Requires 8GB or larger microSD card.

1. Download the flasher program to your computer: https://www.balena.io/etcher/
1. Power down Kaleidoloop. Disconnect the USB-C cable. 
1. Locate the thin slit in the rear of the enclosure (between the USB-C port and the USB 3.0 port.)
1. Eject the microSD card: Use a pin, paperclip, guitar pick, or another microSD card to first press the black microSD card in, then let spring out gently.
1. Insert microSD into your computer (you may need an adapter or card reader)
1. Use the Etcher program to burn the OS file on to the SD Card. When Etcher is finished your computer may display a message similar to 'This disk is not readable.' This message is normal and you may click 'Eject' to proceed.
1. Remove the microSD card from your computer and reinsert it in Kaleidoloop. Make sure that the microSD card is going into the socket on the circuit board, as it is easy to drop it into the device. If you can wiggle it a lot, it probably is not in socket. Use the same tool to press it in until you hear/feel a 'click.'
1. Restart Kaleidoloop to confirm your new card is working. The first time it boots from a newly flashed SD card, the OS will resize the storage partition to the available space on the card. The LEDs will be red during this brief process. 