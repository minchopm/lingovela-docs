# LingoVela — choose a translation mode

Release status at review: the public site says App Store release is in preparation. The following describes its published mode distinctions, not a guarantee that every mode is available on every installed build.

| Requirement | OpenAI Online | On Device | Private Cloud Compute |
| --- | --- | --- | --- |
| Internet during processing | Required | Not for compatible prepared local processing | Required |
| Active subscription | Required | Required | Required |
| AI credits | Required | No AI credits for local translation | Required |
| Data processing | Voice and translation requests go to OpenAI | Compatible local translation and supported offline speech recognition | Text, including locally transcribed speech, goes to Apple after separate consent |
| Additional conditions | Service connectivity and balance | Downloaded models and support for the chosen language pair and speech recognition | Compatible iOS 27+ / Apple Intelligence device and Apple usage quota |

The public site says raw audio and images are not uploaded to Apple in Private Cloud Compute mode. That does not make it offline: locally transcribed text still goes to Apple. On Device and Private Cloud Compute are different modes with different requirements.

## A practical choice sequence

1. Confirm which modes your installed build and device actually expose.
2. Check the two languages in the selected mode. Interface localization and translation support are separate.
3. Decide whether online processing is acceptable for the conversation.
4. For offline use, download the needed models and test fresh speech with connectivity unavailable.
5. Check subscription status and, for online modes, available credits before the conversation.

If a mode is unavailable, do not assume another mode is equivalent. It may use a different provider, language capability or billing path.

## Offline preparation checklist

- Activate the required subscription while online.
- Download compatible translation models for the intended pair.
- Confirm supported offline speech recognition, not just text translation.
- Test a new sentence from each speaker with connectivity unavailable.
- Verify the transcript, translated text and intended spoken output.
- Have an alternative communication method if the pair or device is unsupported.

A saved conversation being readable offline is not proof that a new voice conversation can be translated offline.

## Credits and subscription are separate

The published monthly plan includes 2,000 AI credits. Both documented online modes use credits; On Device does not. Credits meter model usage rather than a fixed number of minutes. Speech length, output audio, text and model rates can change the amount spent.

The site describes session reservations and refunds of unused reserved credits at session end. End the session and inspect the final balance before estimating usage. Consumable top-ups add credits without removing the subscription requirement. Prices and taxes vary by storefront; the purchase screen is the current reference.

## Saved history and privacy

The site describes saved conversations on the device and an anonymous device account for access and credits. Local history is distinct from the provider processing live requests. Check the active mode before speaking and avoid assuming cross-device history sync or a cloud backup.

[Documentation home](README.md) · [Troubleshooting](TROUBLESHOOTING.md) · [Official site](https://lingovela.arte-soft.com/)

Reviewed 2026-11-04. LingoVela is independently published by Arte Soft EOOD.
