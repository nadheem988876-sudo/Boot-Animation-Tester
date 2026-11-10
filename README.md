# Boot-Animation-Tester
Android boot animation tester without flashing and rebooting 

Boot Animation Tester
Plays an Android bootanimation.zip on screen the way a phone plays it at boot, so you can check an animation without flashing anything.
Android app: download the APK from the Releases page.
Why
Other boot animation previewers get stuck on a looping part that waits for the boot to finish. This one simulates a 20 second boot, so looping parts finish the loop they are in and the animation ends like it does on a real phone.
What it does
Reads desc.txt and plays the parts and loops in order, at the frame rate in the file, without skipping frames.
Portrait animations (for example 720x1280) are shown in a phone-shaped frame. Landscape ones (1920x1080, 1920x1280) are shown in a plain black box. Both axes are scaled equally.
Fullscreen with a restart button (top left) and an exit button (top right).
Record plays the whole boot and saves it as an MP4 at the animation's own resolution (portrait stays portrait, landscape stays landscape). The file is named <zip name>_recording.mp4 and goes to your Downloads folder.
Everything runs on your device. The zip is read locally and is not uploaded anywhere.
