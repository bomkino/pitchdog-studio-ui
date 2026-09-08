# PitchdogStudioUI — prepared canonical package

Resource-free SwiftUI/AppKit chrome, extracted with its source history from Galileo.
Library sources match Galileo component revision b946f486dcea597fdcc939ec7d6b39d66809c9b3.
This local repository has no remote and is not published. Both applications retain
their guarded pilot configuration until package publication and permanent pins are
authorized and verified. The existing development source is not silently superseded.

`swift test` checks pure palette contracts.
On a Mac, `swift run StudioUISpecimen`
opens a developer-only control specimen. Neither command installs or replaces an app.

The host supplies appearance, resolved accent, contrast, motion and active-window state.
There are no preferences, documents, sessions, source clocks, codecs, media caches,
resource bundles, plugins, font files, renderer dependencies or network operations here.

Fields retain app-owned parsing, captured targets, focus and undo. The slider retains
NSSlider's native control/accessibility surface and captures its callbacks for a gesture.
Ordinary choices use genuine Buttons or a Menu containing a Picker.

## Provenance and acceptance

New code written for pitch.dog in this implementation. No Luminare, CodeEdit, IINA or
external skill code is copied. The LICENSE file is copied byte-for-byte from Galileo. No license change is made. It does not
relicense either application's existing controllers.

Prototype tokens are not human-approved. Palette tests are not visual, keyboard,
VoiceOver, packaged-app, minimum-OS or physical-device acceptance. The specimen is
not bundled with Galileo or Drift. Public package publication remains a separate gate.
