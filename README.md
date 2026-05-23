# alpha_learning
The goal is to create an iPad App specifically for Children with learning disabilities, that adapts automatically based on performance. 

Yes, unfortunately, I am a vibecoder - sorry guys; I study education, not SWE.


## Documentation: Concept Paper "Project Alpha"

---

### 1. Vision & Pedagogical Core
"Alpha" is a GDPR-compliant, open-source educational software designed for the iPad. It targets highly diverse, inclusive German language classes, specifically focusing on students learning German as a second language (DaZ) and those with special educational needs.

*   **Adaptive Learning:** Automatically guides students within their Zone of Proximal Development (ZPD).
*   **Didactic Foundation:** Built on a continuous support cycle (Diagnosis → Intervention → Evaluation) combined with the "Wember-Raute" developmental framework.

---

### 2. Student Workflow (The Learning Pipeline)

*   **Daily Routine:** Students engage in a dedicated 10–15 minute daily iPad learning session.
*   **Accessibility:** Visual icons prompt students to plug in headphones. All text features high-quality audio playback and bilingual support (e.g., German/Turkish) to bridge language gaps.
*   **Privacy First:** Students log in locally using only their first name. The app converts this into an anonymous ID (e.g., #4829) for the teacher's dashboard. All data remains strictly on the device (edge computing).
*   **Smart Diagnostics:** A curated assessment identifies the student's current skill level. To prevent frustration, the test automatically stops when multiple errors occur, defining their exact learning threshold. Teachers can also set manual pre-filters.
*   **Practice & Instruction:** Core topics are explained simply, followed by varied exercises like digital flashcards or racing games. Students must achieve a 90% mastery rate to advance to the next tier.
*   **Evaluation:** Every session concludes with a brief retention check. If a student is inactive for more than two weeks, the app automatically triggers a re-diagnostic test.
*   **Gamification:** Uses a minimalist avatar system with unlockable accessories to maintain focus and eliminate distracting visual clutter. Progress animations celebrate achievements without highlighting setbacks.

---

### 3. Special Education Fallback Systems
Instead of displaying error messages when a student struggles, the app dynamically shifts its instructional focus to support them:

*   **Motor Skills Fallback:** If the on-device handwriting recognition fails repeatedly due to motor control difficulties, the app switches to motor training (e.g., tracing animated lines).
*   **Speech & Articulation Fallback:** Students speak answers into an on-device speech-to-text AI. If articulation issues are detected, the app shifts to speech therapy support, offering slowed-down syllabic audio and mouth-movement animations. A non-verbal touch menu with three image options serves as a final safety net.

---

### 4. Teacher Dashboard

*   **Local Syncing:** Anonymous student data snippets are transferred securely to the teacher's device via a local QR code scan or school Mobile Device Management (MDM).
*   **Actionable Insights:** The dashboard aggregates data for 10–15 students to automatically generate a teaching matrix. It provides concrete grouping and material recommendations for subsequent offline lessons, tailored to specific speech, motor, and learning support needs.
