# LingoVela: Live Translate — troubleshooting

Change one thing at a time and repeat a short test. Record the app version and mode before changing settings so the result can be reproduced.

## On Device fails without internet

Check both translation models and offline speech recognition support for the chosen pair. Initial model download and subscription activation must be completed online.

## Private Cloud Compute is unavailable

Check the installed app version, device, iOS 27+/Apple Intelligence requirements, separate consent and Apple quota. Do not assume an iOS 26-capable device supports this mode.

## The transcript changes while I speak

Treat live text as provisional until the turn is complete. Pause before the other person responds and verify important terms.

## Listening stops

Check microphone permission, the active audio route, interruptions and the session state. Restart a short test rather than continuing a conversation with missing input.

## Translation is delayed or incorrect

Use shorter turns, reduce background speech and confirm the chosen languages. Online modes also depend on connectivity and service availability.

## Credits decrease unexpectedly

Check which mode is active. Both documented online modes consume credits; On Device is the zero-credit mode. End unused sessions.

## Escalate with a small example

If the issue persists, include a sanitized reproduction and the observed result in a support request. Do not infer the cause from a single failed test or switch to a different processing mode without checking its data handling.

See [privacy and support](PRIVACY_AND_SUPPORT.md).

---
[Documentation home](README.md) · [Official product website](https://lingovela.arte-soft.com/)

Reviewed 2026-11-04 against public product materials. Interface wording and availability can change with the installed version.
