# AI Photo Booth

An event booth where a visitor takes a photo and receives a personalised picture, with their face placed into a branded illustration.

## How it works
1. Visitor chooses a template (male / female) on the booth screen.
2. The webcam captures a photo.
3. The app sends the photo and a strict prompt to an image-generation AI that replaces only the person in the template and keeps pose, clothing, lighting and layout unchanged.
4. The result is shown on screen, then printed or shared by QR code.

## Key points
- A tightly controlled prompt prevents face distortion and layout changes.
- Fixed templates keep every output on-brand.
- Built for live use: fast, simple, kiosk friendly.

## Tech
ASP.NET Core MVC, webcam capture in the browser, image-generation API, QR code.

*Screenshots: to be added (use sample faces only).*
