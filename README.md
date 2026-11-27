# FWG Studio · Free OBS Starting Soon screen

<p><img src="docs/branding/fwg-studio-display.svg" alt="FWG Studio" width="220" height="220"></p>

An official free Gridline sample from [FWG Studio on itch.io](https://forgeworldgaming.itch.io/): a static Starting Soon screen for OBS and a matching About panel for your channel page. Both PNGs are unwatermarked and use generic text, so you can use them as supplied.

FWG Studio creates and maintains this resource. The abstract background artwork is AI-assisted; the layout, typography, and UI graphics are part of the Studio composition. See the original [licence](LICENSE.txt) and [attribution notice](ATTRIBUTION.txt).

## Preview

![Gridline Starting Soon screen with graphite and lime abstract artwork on a white background](assets/starting.png)

<img src="assets/about.png" width="320" height="80" alt="Matching Gridline About channel panel with a lime accent">

## What you get

| File | Dimensions | Use |
| --- | --- | --- |
| [assets/starting.png](assets/starting.png) | 1920 × 1080 | A full-screen, static Starting Soon scene in OBS |
| [assets/about.png](assets/about.png) | 640 × 160 | An About panel, designed to display at 320 × 80 where your platform supports custom panel images |

This sample contains two static PNGs. It does not include editable SVGs, name personalization, a webcam frame, animation, chat, or alerts. The About panel belongs on your channel page; it is not a webcam overlay.

## Put the Starting Soon screen in OBS

Download this repository with **Code → Download ZIP**, extract it, and keep the folder somewhere permanent.

1. In OBS, create or select a scene named **Starting Soon**.
2. Under **Sources**, choose **+ → Image**, then select `assets/starting.png` from the extracted folder.
3. Fit the image to your canvas, check that the text is visible, and make a short local recording before going live.

A 1920 × 1080 canvas matches the artwork. With a different canvas size, keep the image’s proportions and inspect the edges. [OBS Image sources support PNG](https://obsproject.com/kb/image-sources).

The screen’s “Starting Soon” text is artwork. You still choose when to start the broadcast and when to switch to your live scene.

See [the complete setup steps](docs/OBS-setup.md) for fitting, source order, audio checks, and adding the About panel.

## Use the About panel

Upload `assets/about.png` where your streaming platform supports a custom channel-panel image. Use the platform’s accompanying text field for your introduction, schedule, or channel details. The PNG’s generic “About” heading does not need a channel name to work.

## Prefer a scene with motion?

Follow the [OBS walkthrough](https://forgeworldgaming.itch.io/gridline-free-stream-sample/devlog/1810496/from-a-static-starting-soon-screen-to-an-animated-one-in-obs) to add the free PNG as an Image source or a local animated HTML scene as a Browser Source.

The [Gridline Animated OBS Overlay Pack](https://forgeworldgaming.itch.io/gridline-animated-obs) includes customizable local HTML scenes with a one-time purchase on itch.io. The [Gridline membership on Gumroad](https://fwgworld.gumroad.com/l/gridline-obs-membership) costs **US$13 per month** and includes downloads and use during your paid period.

FWG Studio's hosted OBS themes use separate plans. This free sample is available without a purchase.

## Licence and original guidance

The original [FWG Studio Free Sample Licence](LICENSE.txt) permits use and personalization on channels and social accounts you own or operate as one creator or business, including monetized streams. It restricts resale, sublicensing, and redistribution of the asset files. Public display within your channel output is permitted. Read the full licence before using or sharing the files; this summary does not replace it.

The original licence and attribution text are preserved unchanged. The original supplied setup guidance is also retained in [docs/original-sample-readme.md](docs/original-sample-readme.md). No standalone font files are included in this repository.

OBS and streaming-platform names belong to their owners. No affiliation or endorsement is claimed.

