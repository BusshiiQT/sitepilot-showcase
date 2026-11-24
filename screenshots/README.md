# Product screenshot notes

These captures show a scan of **Cedar Lane Studio**, a fictional ceramics business. The local demo served a homepage without an HTML title, a working About page, a Contact link returning HTTP 404, and a Workshops link outside the scanner's review scope. A reserved example hostname appears in the screenshots.

| Capture | Content |
| --- | --- |
| [Scan entry](01-scan-entry.png) | The existing homepage and website input, under the provisional Kaevro brand. |
| [Diagnostic report](02-diagnostic-report.png) | Two successfully checked pages, two confirmed issues, and guidance for the broken link. |
| [Expanded evidence](03-finding-evidence.png) | Actual observations from the controlled scan, including About's HTTP 200 and Contact's HTTP 404. |

Playwright captured the existing application in a 1440 × 1000 desktop viewport at 2× pixel density. The exports are cropped for readability. The demo used a controlled HTTP fixture and the application's own scanner and report UI.

For future captures, use a clean browser profile, the same synthetic scenario, and the same viewport. Review exported pixels at full size, keep browser chrome and development panels out of frame, and remove metadata before adding images to the showcase. The internal repair workflow has no product screen to capture.
