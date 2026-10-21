# Betakati

A static Arabic personal contact-card interface built with Flutter. It displays a profile image, a name/title, and phone/email information in a compact card layout.

## Implementation

lib/main.dart defines the Material interface using a CircleAvatar and contact rows. Assets and the Cairo font are declared in pubspec.yaml. This project demonstrates layout and typography; it has no authentication, database, profile editor, or backend. The contact rows display text rather than implementing phone/email actions.

## Run locally

Install Flutter with Dart 3.10.8 or a compatible SDK:

```sh
flutter pub get
flutter run -d chrome
flutter build web --release --no-web-resources-cdn
```

No service configuration is needed. The source embeds personal profile/contact content. Review that content and use deliberately public or synthetic contact details before distributing a build or recording screenshots. This documentation does not reproduce those values.

## Screenshot and review status

A public portfolio screenshot is intentionally omitted because the current screen includes personal contact information. Capture the actual app after preparing an approved public profile; do not substitute a fabricated interface. The web release built successfully with Flutter 3.38.9 and its interface rendered locally; profile contents were withheld from the capture/report. Native platform support is not established by the presence of template runner folders.
