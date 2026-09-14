# Supported Players & Media Sources

SL Now Playing receives media information from supported applications and playback sources running on your Windows PC.

The information available to SL Now Playing depends on the player or source being used.

---

## Supported Sources

SL Now Playing is designed to work with a variety of media sources, including supported:

- Music applications
- Desktop media players
- Web browsers
- Streaming services
- YouTube playback

The exact information available may vary between applications.

For example, some sources may provide complete artist and track information while others provide only limited media information.

---

## Browser Playback

SL Now Playing can detect supported media playback from compatible web browsers.

This includes music and media played through supported websites and streaming services.

Browser-based playback may require additional integration for certain services.

---

## YouTube

YouTube is supported through the SL Now Playing browser integration.

For the best YouTube experience, make sure the required **SL Now Playing Browser Bridge** is installed and active.

The Browser Bridge allows SL Now Playing to identify YouTube playback more accurately than standard Windows media detection alone.

Without the Browser Bridge, Windows may expose YouTube only as generic media playback and some information or features may not be available.

---

## Firefox Browser Bridge

SL Now Playing provides a Browser Bridge for Firefox to improve browser and YouTube detection.

The Browser Bridge must be active while using supported browser playback with SL Now Playing.

### Important

If the Browser Bridge is temporarily loaded into Firefox for testing or development, Firefox may remove it after the browser or Windows is restarted.

The released version of SL Now Playing will provide the appropriate installation method for the Browser Bridge.

---

## Windows Media Detection

Some applications provide their currently playing media information directly through Windows.

SL Now Playing can use this information where supported.

The amount and quality of information available depends on what the application reports to Windows.

---

## Track Information

Depending on the playback source, SL Now Playing may receive information such as:

- Track title
- Artist
- Playback status
- Other available media information

Not every player provides every type of information.

This does not necessarily indicate a problem with SL Now Playing.

---

## Discord

SL Now Playing provides limited support for media playback inside Discord through Windows Media Detection.

### Supported

Embedded YouTube videos played directly inside Discord can be detected by SL Now Playing when no higher-priority supported media source is active.

Discord is treated as a lower-priority Windows Media source and does not override higher-priority sources such as Spotify or directly detected YouTube playback.

### Currently Not Supported

Other Discord media files are currently not supported.

This includes media files played directly through Discord that are not embedded YouTube content.

---

## A Player Is Not Detected

If your media is playing but SL Now Playing does not detect it:

1. Make sure the SL Now Playing PC Application is running.
2. Make sure your HUD and PC application are connected.
3. Start playback before checking the HUD.
4. If using browser playback, make sure the required Browser Bridge is active.
5. Try restarting the player or browser.

For more help:

[Troubleshooting](troubleshooting.md)

---

## Compatibility

Player and browser compatibility may change when third-party applications or services are updated.

TEKIZMO may update SL Now Playing to maintain or improve compatibility.

This page will be updated as additional players and playback sources are tested and officially supported.

---

[← HUD Guide](hud-guide.md) | [Documentation Home](../README.md) | [Troubleshooting →](troubleshooting.md)

---

**TEKIZMO – Virtual Innovations**

Simple • Smart • Connected
