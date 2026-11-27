# Set up the free Gridline sample in OBS

This resource contains a static Starting Soon screen and an About channel panel. Use the screen as an OBS Image source and the panel on a channel page that supports custom panel images.

## 1. Keep the files in a stable folder

Extract the repository ZIP before adding files to OBS. Keep the extracted folder in a location you intend to keep, such as a dedicated stream-assets folder. OBS will use the selected image’s path; if you move or rename the file later, select it again in the source’s Properties.

The files you need are:

- [`assets/starting.png`](../assets/starting.png): 1920 × 1080.
- [`assets/about.png`](../assets/about.png): 640 × 160, designed for a 320 × 80 panel display.

Read [LICENSE.txt](../LICENSE.txt) before use. It allows creator use, including monetized channels, and restricts redistribution of the asset files.

## 2. Add the Starting Soon screen

1. Open OBS and create or select a scene named **Starting Soon**.
2. In **Sources**, choose **+ → Image**. Give it a clear name, such as **Gridline Starting Screen**.
3. In the image source’s Properties, browse to the extracted `assets/starting.png` and confirm the selection.

Use an **Image** source for this PNG. It is static artwork and does not need a Browser source. [Official OBS Image source documentation](https://obsproject.com/kb/image-sources) lists PNG support and the image-file property.

## 3. Fit it without stretching

A 1920 × 1080 canvas matches this screen. Select the image source and use **Transform → Fit to Screen** if you need to fit it to the canvas. On Windows, the default shortcut is **Ctrl+F**; on macOS, it is **Cmd+F**.

If your canvas has a different aspect ratio, inspect the result rather than stretching the image to fill every edge. Keep the text readable and decide whether unused space or deliberate cropping better fits your layout. The [official OBS Sources Guide](https://obsproject.com/kb/sources-guide) covers transforms, fitting, and cropping.

Check the Sources list if you cannot see the screen. Its eye icon must show it as visible, and another full-screen source above it can cover it. In this dedicated Starting Soon scene, put the image above any captures it should cover.

## 4. Test picture and audio

Make a short local recording before broadcasting. Watch it back and check:

- The whole screen is visible and the message is readable.
- No private window or notification appears over the artwork.
- The microphone, desktop audio, and any music behave as intended.
- Switching to your live scene shows the capture you expect.

An image that covers a game does not prove that the game’s audio or your microphone has stopped. Check the Audio Mixer and listen to the recording.

Showing the Starting Soon image does not start the broadcast. When you are ready, use your normal OBS broadcast controls and select your live scene yourself.

## 5. Add the About panel to your channel

Where your streaming platform supports a custom panel image, upload `assets/about.png`. It is designed for display at **320 × 80**, using a **640 × 160** source image.

Add your channel introduction in the platform’s accompanying panel-text field. This panel is for your channel page and is not an OBS camera frame.

## If something looks wrong

- **The image is missing:** reopen the source’s Properties and select `starting.png` from its current folder.
- **The image is hidden:** check the eye icon, active scene, and sources above it.
- **The edges or text are cut off:** inspect the transform and crop; try Fit to Screen in a test scene.
- **The image does not move:** this PNG is static by design.

Use an OBS **Image** source for the free PNG. The [OBS walkthrough](https://forgeworldgaming.itch.io/gridline-free-stream-sample/devlog/1810496/from-a-static-starting-soon-screen-to-an-animated-one-in-obs) shows how to set up the PNG and add a local animated HTML scene as a **Browser** source.

For four customizable animated scenes, choose the [one-time Gridline pack on itch.io](https://forgeworldgaming.itch.io/gridline-animated-obs) or subscribe to the [downloadable Gridline membership](https://fwgworld.gumroad.com/l/gridline-obs-membership) for **US$13 per month**. The membership covers downloads and use during your paid period.

The [US$65 one-time personalization service on Contra](https://contra.com/s/LsZvZbFR-personalize-four-1080p-obs-scenes-for-your-channel) covers customization for four 1080p scenes. For animated HTML, use the paid Gridline download or an active membership that includes it. Your licence must permit private editing. For static PNGs, provide a 1920 × 1080 background you have permission to share for editing and display on your channel.

## Sources and ownership

- [OBS Image Sources](https://obsproject.com/kb/image-sources): PNG support and image-file settings.
- [OBS Sources Guide](https://obsproject.com/kb/sources-guide): visibility, stacking, transforms, and cropping.
- [Original sample guidance](original-sample-readme.md), [licence](../LICENSE.txt), and [attribution notice](../ATTRIBUTION.txt): asset dimensions, permitted use, and AI-assisted artwork disclosure.

This is an official FWG Studio resource. OBS and streaming-platform names belong to their owners; no affiliation or endorsement is claimed.
