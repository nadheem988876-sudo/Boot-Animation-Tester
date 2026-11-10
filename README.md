# Boot Animation Tester

Preview an Android `bootanimation.zip` on your screen exactly like a phone plays it at boot, with no flashing and no rebooting.

## Download

Get the APK from the [Releases page](../../releases/latest).

## Why this exists

Most boot animation previewers get stuck on a looping part, because they wait for a boot that never finishes. This one simulates a **20-second boot**, so looping parts finish and the animation ends the way it does on a real phone.

## Features

- Reads `desc.txt` and plays the parts and loops in order
- Uses the frame rate from the file and doesn't skip frames
- Portrait animations (e.g. 720x1280) are shown in a phone-shaped frame
- Landscape animations (1920x1080, 1920x1280) are shown in a plain black box
- Both axes are scaled equally, so nothing looks stretched
- Fullscreen mode with a restart button (top left) and an exit button (top right)
- **Record**: plays the whole boot and saves it as an MP4 at the animation's own resolution (portrait stays portrait, landscape stays landscape). The file is named `*ZipName*_recording.mp4` and goes to your Downloads folder

## Privacy

Everything runs on your device. Your zip is read locally and is never uploaded anywhere.

## Usage

1. Install the APK.
2. Open the app and choose your `bootanimation.zip`.
3. Watch it play, or tap Record to save a video.

## Feedback

Found a bug or have an idea? Open an [issue](../../issues).

## License

MIT
