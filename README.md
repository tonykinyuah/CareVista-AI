Care Vista is a clinical intelligence tool designed to solve the "data fatigue" faced by modern nurses. While Electronic Health Records (EHRs) provide massive amounts of patient data, they often fail to provide actionable insights. Care Vista uses Gemini 3 Pro to bridge this gap.

🌟 Key Features
FHIR to ADPIE Pipeline: Instantly converts raw HL7 FHIR JSON data into a structured Nursing Care Plan (Assessment, Diagnosis, Planning, Implementation, Evaluation).

Clinical Reasoning with Gemini 3 Pro: Unlike standard templates, our app uses Gemini 3’s high-level reasoning to identify patient risks (e.g., detecting hypertension from vital sign trends) and suggest prioritized nursing interventions.

Safety-First Design: The system is explicitly instructed to highlight critical lab values and prioritize safety-focused risk diagnoses.

🛠️ How we built it (The "Vibe Coding" Journey)
We built Care Vista using the Google AI Studio Build Mode.

Frontend: Rapidly prototyped with React and Tailwind CSS using natural language prompts.

Intelligence: Integrated Gemini 3 Pro as the core reasoning engine. We used System Instructions to "lock in" the clinical persona, ensuring the model always adheres to medical standards and patient safety protocols.

Efficiency: By leveraging Gemini 3 Flash for the UI logic, we maintained a low-latency experience for the end-user.

📈 Potential Impact
In a typical hospital shift, a nurse spends significant time manually charting and planning. Care Vista can reduce the time spent creating initial care plans by up to 70%, allowing nurses to spend more time at the bedside.
