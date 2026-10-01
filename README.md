# 🌸 graceful-douhua-3e4fce.netlify.app — Voice-First Welfare Agent for Rural Women

> **Built for PromptWars × HackArena — "The Invisible Woman" Challenge Track**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Web Speech API](https://img.shields.io/badge/Web_Speech_API-Chrome-4285F4?logo=google-chrome&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)

---

## 📌 Problem Statement

In India, approximately **48% of rural women have never used the internet**. While government welfare schemes (such as free LPG cylinders, direct monthly cash transfers, and housing subsidies) are designed to provide economic relief, the existing access channels depend heavily on:

- English or formal administrative text
- Complex multi-step web forms and CAPTCHAs
- Intermediaries and cyber café brokers

As a result, the women most entitled to social safety nets are effectively locked out by design.

---

## 💡 Solution: "Akka" (அக்கா)

**Akka (Saheli AI)** is a zero-literacy, voice-first welfare assistant engineered natively in colloquial spoken Tamil. It removes the entire digital divide:

1. **Zero UI Friction:** No text boxes, no typing, no menus. Users speak with a single tap on a high-contrast glowing microphone.
2. **Empathetic Verification Loop:** Evaluates eligibility through simple, sequential verbal questions mimicking a trusted village counselor.
3. **Simulated Automated e-Seva Pipeline:** Converts oral eligibility into an end-to-end simulated submission—running document checks, Aadhaar KYC validation, and issuing an official government token and digital receipt.

---

## ✨ Key Features

- **🗣️ Native Tamil Speech Processing:** Uses the browser-native Web Speech API configured for Tamil (`ta-IN`) with bi-directional synthesis.
- **🌐 Bilingual & Dialect Friendly:** Instant toggle between colloquial Tamil script and Tanglish (Tamil in English alphabet) for broader usability.
- **🏛️ Multi-Scheme Coverage:**
  - **PM Ujjwala Yojana 2.0:** Free LPG connection and initial refill support.
  - **Kalaignar Magalir Urimai Thogai:** ₹1,000 monthly basic income support for female heads of household.
  - **PM Awas Yojana (Gramin):** Rural housing financial assistance.
- **⚡ Simulated Auto e-Seva Agent:** Automatic 3-stage progress bar representing document scanning, biometric KYC, and government portal dispatch.
- **🧾 Instant Digital Receipt:** Generates a printable verification pass featuring application token ID, beneficiary name, and SMS notification alerts.
- **🎨 Accessible UI Design:** High-contrast warm saffron and emerald festival palette with pulse-glow audio triggers.

---

## 🏗️ Architecture & Conversational Flow
