# GPSDash Support

**Record your routes. Keep control of your data.**

GPSDash is a local-first GPS route recorder for iPhone and iPad. Record walks, hikes, rides, drives, and boat trips; review saved routes on a map; and import or export GPX files.

No account or server is required for local recording and route review.

This repository is the public support and issue tracker for GPSDash. It is not the application’s source-code repository.

## Documentation and Links

| Resource | English | Français | Español |
|---|---|---|---|
| GPSDash overview | [Website](https://dashapps.app/gpsdash/) | [Site Web](https://dashapps.app/fr/gpsdash/) | [Sitio web](https://dashapps.app/es/gpsdash/) |
| User manual | [User Manual](https://dashapps.app/gpsdash/user-manual/) | [Guide d’utilisation](https://dashapps.app/fr/gpsdash/user-manual/) | [Manual de usuario](https://dashapps.app/es/gpsdash/user-manual/) |
| Privacy policy | [Privacy Policy](https://dashapps.app/gpsdash/privacy-policy/) | [Politique de confidentialité](https://dashapps.app/fr/gpsdash/privacy-policy/) | [Política de privacidad](https://dashapps.app/es/gpsdash/privacy-policy/) |
| Optional GPXDash server | [Learn about GPXDash](https://dashapps.app/gpxdash/) | [Découvrir GPXDash](https://dashapps.app/fr/gpxdash/) | [Conoce GPXDash](https://dashapps.app/es/gpxdash/) |

[Download GPSDash on the App Store](https://apps.apple.com/ca/app/gpsdash/id6822049384)

Features described on this page may depend on your installed version. Check the documentation for the version available to you.

## Get Help

- **Questions or private support:** [dash.app.support@gmail.com](mailto:dash.app.support@gmail.com)
- **Bugs and feature requests:** [Open an issue](https://github.com/marcoue/GPSDash-Support/issues/new)
- **Existing reports:** [Browse issues](https://github.com/marcoue/GPSDash-Support/issues)

You may submit questions and reports in **English, French, or Spanish**.

Before opening an issue, check the user manual and existing reports to see whether your question has already been answered.

## Report a Bug

Please include:

- Your iPhone or iPad model.
- Your iOS or iPadOS version.
- Your GPSDash version and build number.
- The steps needed to reproduce the problem.
- What you expected and what happened instead.
- Whether the app was in the foreground, in the background, or the device was locked.
- The recording mode and Auto Pause settings, if relevant.
- A screenshot with personal information removed, if helpful.

For GPS reception problems, mention whether you were indoors or outdoors and whether Precise Location was enabled. You do not need to disclose your actual location.

For an optional server-connection problem, also include the GPXDash server version and the error message, with sensitive details removed.

### Bug Report Template

```text
Device:
iOS/iPadOS version:
GPSDash version/build:
GPXDash version, if applicable:

Steps to reproduce:
1.
2.
3.

Expected result:

Actual result:

Recording mode and Auto Pause settings, if relevant:

Foreground/background/locked:

Additional information:
```

## Protect Your Privacy

**GitHub issues and attachments are public.**

Do not post:

- Private routes, GPS coordinates, or unredacted GPX files.
- Home, work, or other sensitive locations.
- Server credentials, pairing codes, QR codes, device tokens, or gateway secrets.
- Private server addresses, sharing links, or screenshots containing account information.
- Unreviewed diagnostic logs or crash reports.

For troubleshooting that requires sensitive information, contact support privately first.

GPSDash’s **Settings → About & Support → Send Logs to Developers** action lets you deliberately submit diagnostics with a contact email. Review any diagnostic file before attaching it to a public issue.

## Optional GPXDash Server

**GPXDash is private, self-hosted, and entirely optional.**

It is a companion you run on infrastructure you control—not a centrally hosted GPS tracking service operated by us. GPSDash remains usable as a local route recorder without it.

With a compatible GPXDash installation, you can:

- Follow uploaded recordings in a browser.
- Upload selected past tracks.
- Organize server-side tracks with folders and tags.
- Create optional sharing links with expiration and revocation.

Connecting does not automatically upload your existing track library. New recordings started while a server connection is configured are queued for upload; you choose which past tracks to send.

Phone and server libraries remain independent. Deleting a local track does not automatically delete its server copy, and hiding live position does not stop uploads.

[Explore GPXDash](https://dashapps.app/gpxdash/)

## Feature Requests

Have an idea? [Open a feature request](https://github.com/marcoue/GPSDash-Support/issues/new) describing:

- What you want to accomplish.
- What makes the current workflow difficult.
- How the proposed feature would help.

Please keep each request focused on one topic.

## Recording and Connectivity Notes

- GPS accuracy and availability depend on your device, permissions, surroundings, and iOS.
- Background recording requires appropriate location permissions and remains subject to iOS execution limits.
- Force-quitting the app interrupts recording.
- Local recording and saved-track access work without a server connection; map imagery and place-name lookup may require internet access.
- Optional weather, iCloud Drive backups, and GPXDash uploads use their respective connected services.
- GPSDash records routes; it is not a turn-by-turn navigation or emergency-location service.
