# Vital-Go Technologies

Continuous care, guided by earlier clinical insight.

Vital-Go connects a wearable health band to a patient's care team. Live readings and weeks of trends sit next to alerts set to that person's own baseline, so a change can be seen before the next visit. Voice Access handles readings, visits, and alerts in the app: say it, and it gets done.

Clinical decisions stay with a licensed professional. The product surfaces patterns for review.

[vital-go.com](https://vital-go.com) · [support@vital-go.com](mailto:support@vital-go.com) · [Book a demo](https://vital-go.com/book-a-demo)

## What we build

| | |
| --- | --- |
| Wearable | A health band captures signals continuously and sends them over an encrypted connection. |
| Health record | Readings build a history the person and their care team can review over time. |
| Clinical intelligence | Changes are flagged against a personal baseline. Alert rules are approved by the person's doctor. |
| Care app | Patients, doctors, and care teams share one picture: live context, trends, visits, and voice access. |

## How the work is organized

Engineering is split across three private repositories.

| Repository | What it holds |
| --- | --- |
| Vital-Go-Device | Firmware for the health band: provisioning, secure connection, sensing, and updates. |
| Vital-Go-Backend | The API: readings, alerts, care workflows, and device management. |
| Vital-Go-Frontend | The website and the patient, doctor, and admin app. |

## Security and support

Readings and records travel over encrypted connections. Sign-in supports passkeys and an authenticator code. Patients, doctors, and admins each see only what their role allows, and access to health records is logged.

Report a vulnerability to [support@vital-go.com](mailto:support@vital-go.com). Please describe what you observed and how to reproduce it. Do not file a public issue for a security report.

Product and account questions go to the same address.
