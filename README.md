# Lifora — Community Healthcare Continuity & Care Coordination Platform
### Smart India Hackathon 2026 | Problem ID: SIH26133

> **Right Care. Right Place. Right Time.**  
> A Rural-First, Multilingual, Community-Assisted Digital Healthcare Continuity and Care Coordination Platform designed for underserved communities in India. Designed to close the referral loop, coordinate primary to secondary care, and support frontline health workers (ASHAs) with responsible clinical decision support.

---

## 🌟 Key Highlights

- **Rural-First & Low-Literacy Friendly**: Designed specifically for rural and underserved patients with large touch-friendly action cards, clear icons with descriptive text, simple language, high-contrast visual design, and mobile-first responsiveness (including iPhone SE 320px–375px).
- **Multilingual Healthcare (English, हिन्दी, ગુજરાતી)**: Instant in-browser language switching across all portals, buttons, medical profiles, forms, and alerts with persistent language preference.
- **Featured Patient Profile (Lakshmi Devi)**: Dedicated patient profile for Lakshmi Devi (Patient ID: `AP-1001`, Age: 62, Status: Active) with hypertension and diabetes management, vitals history, compartmentalized medical records, prescriptions, and follow-ups.
- **Closed-Loop Healthcare Continuity**: Referrals do not end with sending patient data; the system tracks the patient across `SENT → ACCEPTED → EN ROUTE → RECEIVED → TREATMENT → COMPLETED` and automatically creates follow-up visits for community health workers upon discharge.
- **Responsible AI Clinical Decision Support**: Priority urgency indicators (Routine, Priority, Urgent) with multi-factor vitals evaluation (blood pressure, blood glucose, heart rate, SpO₂, age risk, and symptom keywords). Always provides transparent reasoning and clear non-diagnostic disclaimers.
- **Centralized Shared State & Persistence**: Pure frontend architecture using in-memory state with immediate `localStorage` synchronization and cross-tab reactive updates.
- **Low-Connectivity / Offline-Ready Demo**: Supports local registration queueing with on-device caching and one-click synchronization once connectivity is restored.
- **Zero-Setup Deployment**: Built with vanilla HTML5, CSS3, and modern ES6 JavaScript. No bundlers, npm packages, or server runtimes required — run directly in any browser or deploy on GitHub Pages in seconds.

---

## 📂 Project Structure

```
├── index.html     # Single-page application markup with 7 integrated portals & multilingual data-i18n
├── styles.css     # Complete design system, rural-first tokens, mobile responsive styles & theme
├── script.js      # Central routing engine, mock database, translations dictionary, AI decision support
└── README.md      # Project overview and hackathon documentation
```

---

## 🚀 Portals & Architecture

1. **Patient Portal**:
   - **Dashboard**: Rural-first touch cards (My Health, My Records, Appointment, Follow-up, Find Hospital, Emergency Help, My Medicines, Health ID & QR).
   - **My Health Profile**: Lakshmi Devi (AP-1001, Age 62, Active) complete vitals and demographic record.
   - **Medical Records**: Compartmentalized into Medical Vault, Medical History, Prescriptions, and Reports.
   - **Appointments & Referrals**: Active facility referrals and scheduled clinic visits.
   - **Follow-up**: Due follow-up care instructions and reminders.
   - **Digital Health ID & QR**: Scannable QR Health ID and consent controls.
   - **Emergency Assistance**: 1-click emergency contacts alert and local helpline access.
   - **Consent & Privacy & Access History**: Granular data sharing permissions and audit logs.

2. **Health Worker Portal (ASHA)**:
   - Community dashboard, 4-step registration wizard (Patient Information, Symptoms & Vitals, Health Details, Next Steps & Assessment), patient records, AI-assisted priority assessment, closed-loop facility referral dispatch, follow-up management, offline mode.

3. **Healthcare Staff Portal (Hospital)**:
   - Clinical Dashboard, Live patient queue, incoming referral acceptance & progression pipeline, emergency registration, patient identification, ward & bed management, authorized medical records.

4. **Healthcare Services Portal**:
   - Service Dashboard, facility locator, hospital & clinic availability, real-time blood group inventory tracking, essential medicines availability index, ambulance dispatch.

5. **Ambulance Portal**:
   - Pre-arrival emergency alert transmission, en-route vitals broadcasting, ETA tracking, and hospital handover confirmation.

6. **Hospital Admin Portal**:
   - Emergency department KPIs, workload charts, discharge distribution donut, staff duty rosters, and audit logs.

7. **Public Website**:
   - Health portal education, workflow walkthrough, emergency help guidance, and community contact.

---

## 💻 How to Run Locally

1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari).
3. Click **"⚡ Quick Demo Sign In (1-Click Access)"** or use:
   - **Phone**: `9265470008` (Demo OTP: `140706`)
   - **Email**: `PS21058@gmail.com` (Demo OTP: `041005`)

---

## 🌐 Deploy to GitHub Pages (1 Minute)

1. Push these files to your GitHub repository `main` branch.
2. Go to repository **Settings** → **Pages**.
3. Under **Build and deployment** → **Branch**, select `main` and `/ (root)`.
4. Click **Save**. Your live demo will be published at `https://<username>.github.io/<repo-name>/`.

---

## 🏆 SIH 2026 Team Deliverable
- **Platform**: Lifora (SIH26133)
- **Built for**: Smart India Hackathon 2026

