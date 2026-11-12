# HANDSTYLER

Handstyler is an Android app for making graffiti handstyles.

I'm a graffiti writer and a graphic designer, painting since 2008, on Linux.
Not a programmer, a team or a company, so feedback is very appreciated.

## Download

-File: Handstyler-2.0.apk

-Sha256: 
c11f04c53eb2d2063c472c0288714b898975f7a68c7017f12483624e89135ca9  Handstyler-2.0.apk

-Virustotal: https://www.virustotal.com/gui/file/c11f04c53eb2d2063c472c0288714b898975f7a68c7017f12483624e89135ca9

Download: https://github.com/NKNW-Lab/Handstyler/releases/download/2.0/Handstyler-2.0.apk

-Page: https://nknwlab.com/

The sha256 is the fingerprint of that exact file. Verify it with
`sha256sum -c SHA256SUMS`.

## Source Code & Transparency

The source is published for transparency and security verification. Anyone
can inspect it to confirm the app is clean and free of telemetry, spyware
or third-party tracking.

## License

NKNW_LAB Source-Available License. See LICENSE.txt.

Free to read, audit, build and modify. Redistribution is allowed as long as
NKNW Lab stays credited and modified builds are marked as unofficial. No
ads or trackers may be injected.

The name, logo and graphics are covered separately, same terms.

Contact: static.void14@gmail.com

## Layout

`www/` is the app: plain HTML, CSS and JS, no framework and no bundler.
`android/` is the Capacitor project. The APK is built from `www/`.
`fonts/` holds Press Start 2P (SIL OFL).
The copies in the root (`index.html`, `Tags.html`, `images/`) are manual
backups. The build only reads `www/`.

## Build

Gradle
AndroidStudio
