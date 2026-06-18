# MBVision — Privacy Policy

**Effective date:** 18 June 2026

This Privacy Policy describes how **MBVision** (the "App") for Apple Vision
Pro handles information when you use it. We designed the App to keep your
personal data on your device and inside your own iCloud account whenever
possible.

We do **not** sell your data, we do **not** use third-party advertising or
analytics SDKs, and we do **not** track you across other apps or websites.

---

## 1. Data we do NOT collect

The App does **not** collect:

- Your name, email address, phone number, or postal address
- Your precise or approximate location
- Advertising identifiers (IDFA)
- Photos, videos, contacts, or files outside what you explicitly open in the
  App
- Persona, eye-tracking, face, or environment scans
- Data used for advertising, profiling, or cross-app tracking

The App contains **no third-party analytics, advertising, or tracking SDKs.**

---

## 2. Data the App uses on your device

To function, the App accesses the following on-device capabilities. Data
from these capabilities is processed locally on your Apple Vision Pro and
is not sent to our servers unless explicitly stated below.

### a. Spatial data (ARKit)

The App uses Apple's **ARKit** to detect horizontal surfaces (floor, table)
and to anchor 3D content in your physical space. This includes plane
detection and world-tracking data.

- **Purpose:** position virtual 3D models in your room.
- **Storage:** processed in real time, not recorded or transmitted.
- **Sharing:** never leaves your device.

### b. Hand-tracking data

Hand-tracking is used to recognise pinch and drag gestures so you can
manipulate 3D content.

- **Purpose:** gesture input.
- **Storage:** real-time only, not recorded.
- **Sharing:** never leaves your device.

### c. Microphone and speech

If you use the in-app **AI assistant** by voice, the App captures audio
from the microphone and transcribes it using Apple's on-device speech
services.

- **Purpose:** convert your spoken question into text so the assistant can
  answer it.
- **Storage:** audio is not saved by the App. The resulting text question
  may be sent to our AI backend — see Section 3.
- **Control:** microphone access can be revoked at any time in
  Settings → Apps → MBVision → Microphone.

You can use the assistant by typing instead of speaking.

### d. Local network (iPhone companion)

If you pair the optional iPhone companion, the App uses Apple's Bonjour
service over your Wi-Fi network to discover and connect to the companion.

- **Purpose:** pair the iPhone for remote step control.
- **Data exchanged:** step navigation commands and workflow state — no
  personal information.
- **Sharing:** stays on your local network. Nothing is sent to our servers
  for this feature.

### e. Group activities (SharePlay)

If you start a SharePlay session, the App uses Apple's Group Activities
framework to align 3D content placement between participants.

- **Purpose:** synchronised viewing during FaceTime / SharePlay.
- **Data:** anchor offsets only. Audio/video is handled by Apple's
  FaceTime, not by the App.

---

## 3. Data sent to our servers

### a. AI assistant queries

When you ask a question via the in-app assistant (by voice or text), the
text of your question and a small amount of conversation context are sent
to our AI backend operated by **SKF Magnetic Mechatronics**.

- **What is sent:** the transcribed text of your question, the selected
  language, and minimal context about the current workflow step.
- **What is NOT sent:** your name, account identifier, raw microphone
  audio, camera feed, location, or environment scans.
- **Retention:** queries may be logged for short periods for service
  reliability and abuse prevention, after which they are deleted or
  anonymised. They are not used to build advertising profiles and not sold
  to any third party.

### b. Machine condition-monitoring data

The condition-monitoring features fetch industrial machine telemetry
(vibration, rotation, spectral data) from a backend operated by
**SKF Magnetic Mechatronics**.

This is **read-only equipment data** belonging to the operating site, not
personal data about you. Authentication, where required, follows your
organisation's standard credentials.

### c. iCloud (Apple)

Workflows, 3D assets, and your preferences are synchronised through
**Apple iCloud (CloudKit)** under your personal iCloud account. We do not
operate this storage — it is provided by Apple, and access is governed by
Apple's privacy policy.

- We can read content you publish to the shared workflow library, but we
  cannot read your private iCloud data.
- You can stop syncing at any time by signing out of iCloud or disabling
  iCloud Drive in visionOS settings.

### d. Push notifications

The App registers for **Apple Push Notification service (APNs)** to know
when new workflow content is available in iCloud. Push tokens are managed
by Apple; we use them only to notify your device that content has changed.

---

## 4. Permissions you control

You can grant or revoke each permission at any time in
**Settings → Apps → MBVision** on your Apple Vision Pro:

| Permission           | Used for                                      |
| -------------------- | --------------------------------------------- |
| Microphone           | Voice questions to the AI assistant           |
| Speech Recognition   | Transcribing voice questions on-device        |
| Local Network        | Connecting to the optional iPhone companion   |
| Notifications        | Alerting you when new content is available    |
| iCloud / iCloud Drive| Syncing workflows and preferences             |

Revoking a permission disables only the related feature; the rest of the
App continues to work.

---

## 5. Children's privacy

The App is intended for professional use by adults (technicians, engineers,
trainers). It is not directed at children under 13, and we do not knowingly
collect data from children.

---

## 6. Data security

- All network traffic between the App and our backends is encrypted with
  **HTTPS / TLS**.
- We follow industry-standard practices to protect data on our servers.
- Locally cached content is stored in the App's protected sandbox provided
  by visionOS.

No method of transmission or storage is 100% secure; we cannot guarantee
absolute security, but we work continuously to protect your information.

---

## 7. International users

Our backend services are operated by **SKF Magnetic Mechatronics** and may
be hosted in the European Union. By using the App you understand that
queries you send to the AI assistant or telemetry endpoints may be
processed in countries other than your own.

If you are located in the European Economic Area (EEA), the United Kingdom,
or Switzerland, you have rights under the **GDPR** to access, correct, or
delete personal data we hold about you, and to lodge a complaint with your
local data-protection authority. To exercise these rights, contact us at
the address below.

---

## 8. Changes to this policy

We may update this Privacy Policy from time to time. When we do, we will
revise the **Effective date** at the top of this page. Material changes
will also be highlighted inside the App.

---

## 9. Contact

If you have questions about this Privacy Policy or your data:

- **Email:** apple.developer@skfs2m.com
- **Postal address:** SKF Magnetic Mechatronics, France

---

_© SKF Magnetic Mechatronics. All rights reserved._
