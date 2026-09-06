# Lesson 3.6: Ethics in Digital Coaching and AI

## Learning Outcomes

By the end of this lesson, you should be able to:

- Identify key data privacy obligations for coaches using digital platforms
- Explain client data encryption concepts at a practical level
- Apply relevant GDPR principles to a coaching practice
- Describe appropriate and inappropriate uses of AI in coaching
- Implement client consent processes for AI-powered coaching features
- Distinguish between AI as a coaching tool vs. AI as a coaching replacement

---

## Data Privacy for Coaches

When you move your coaching practice to a digital platform, you take on data privacy responsibilities that may be new to you. Client worksheet answers often contain deeply personal information: fears, relationship struggles, health concerns, financial worries, and vulnerable reflections. Protecting this data is both an ethical obligation and, in many jurisdictions, a legal requirement.

### What Data Do Digital Coaching Platforms Handle?

Client data in a digital coaching practice typically includes:

- **Identity data:** Name, email address, phone number
- **Session data:** Notes, session recordings (if applicable), session summaries
- **Worksheet data:** All client responses to worksheets, including wheel-of-life ratings, journal entries, values card sorts, thought records
- **Behavioral data:** When clients complete worksheets, how long they spend, how often they engage
- **Payment data:** If you process payments through the platform (typically handled by PCI-compliant payment processors, not stored directly)

Each category has different sensitivity levels and may have different regulatory requirements.

### Encryption: What Coaches Need to Know

You do not need to become a cybersecurity expert, but you should understand the basics of how client data is protected.

**Encryption in transit (TLS/SSL):** When a client fills out a worksheet on their phone, the data travels from their device to the server. TLS encryption ensures that no one can intercept and read that data during transmission. You can verify this by checking that the platform URL starts with "https://" rather than "http://". This is the minimum standard for any professional coaching platform.

**Encryption at rest:** Data stored on servers should also be encrypted. This means that even if someone gained access to the server's storage, they could not read the data without the encryption key. CoachSheets encrypts sensitive client fields (notes, phone numbers, worksheet answers) using industry-standard AES-256 encryption.

**End-to-end encryption (E2EE):** Some platforms offer E2EE, meaning even the platform provider cannot read the data. This is the highest standard but is rare in coaching platforms because it limits features like AI summaries (which need to read the data to process it).

A clear explanation of encryption types is available at the Electronic Frontier Foundation's Surveillance Self-Defense guide: https://ssd.effomod.org/en/module/introduction-to-data-security/.

## GDPR Basics for Coaches

The General Data Protection Regulation (GDPR) applies to any coach who works with clients in the European Union, regardless of where the coach is located. Even if you are based in the US or Australia, if you have EU clients, GDPR applies to your practice.

### Key GDPR Principles Relevant to Coaches

**Lawful basis for processing:** You must have a valid reason to collect and store client data. For coaches, the most common bases are "consent" (the client agreed) and "legitimate interests" (the data is necessary for providing coaching services).

**Data minimization:** Collect only the data you actually need for coaching. If you do not need a client's date of birth, do not ask for it. Review each field in your intake worksheet and ask: "Do I really need this?"

**Right to access:** Clients can request to see all data you hold about them. You must respond within one month. This includes worksheet answers, session notes, and any AI-generated summaries.

**Right to erasure (right to be forgotten):** Clients can request that you delete their data. You must comply unless there is a legal reason to retain it (such as tax records for payment information).

**Data breach notification:** If client data is exposed (e.g., a hacked account, a lost laptop with client files), you must notify affected clients and, in many cases, the data protection authority within 72 hours.

The UK Information Commissioner's Office provides clear guidance specifically designed for small organizations and sole traders: https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/. The EU GDPR text and resources are at https://gdpr.eu/.

### Practical Steps for GDPR Compliance

1. **Document your data processing.** Create a simple document listing what client data you collect, where it is stored, and why.
2. **Get clear consent.** Add a consent statement to your intake process: "I consent to my data being stored securely on the CoachSheets platform for the purpose of coaching. I understand I can request access to or deletion of my data at any time."
3. **Have a breach response plan.** Know who to contact and what to do if data is exposed.
4. **Review your platform's data processing agreement.** CoachSheets and other platforms should provide a Data Processing Agreement (DPA) that outlines their responsibilities.

## AI in Coaching: Appropriate and Inappropriate Uses

Artificial intelligence is increasingly integrated into coaching platforms. CoachSheets uses AI to generate session summaries based on worksheet answers and session notes. This is a powerful feature, but it comes with ethical boundaries.

### Appropriate AI Uses in Coaching

**AI as pattern recognizer:** AI can identify patterns across a client's worksheet answers over time. "Over the past 4 weeks, your energy score has increased from 4 to 7, but your stress scale has remained constant at 6." This is data aggregation, not diagnosis.

**AI as summarizer:** AI can draft a session summary that the coach reviews and edits. This saves time while keeping the coach in control.

**AI as question suggester:** Based on a client's worksheet answers, AI might suggest follow-up questions the coach could ask. The coach decides which questions are appropriate.

### NEVER Appropriate AI Uses in Coaching

**AI as diagnostician:** AI must never diagnose mental health conditions, learning disabilities, or medical issues. Coaching is not therapy or medicine, and AI is not qualified to make clinical assessments. The boundary is clear: AI identifies patterns; humans interpret them.

**AI as replacement for coaching judgment:** An AI-generated summary is a starting point, not a final product. The coach must review, interpret, and apply their professional judgment. Never send an AI-generated summary to a client or use it in a session without personal review.

**AI as therapist:** No AI should be presented as providing therapy, counseling, or mental health treatment. If a client's worksheet answers suggest they need clinical support, that is a coach's judgment call, not an AI's.

The International Coaching Federation has published guidance on artificial intelligence in coaching. Key points include transparency with clients about AI use, maintaining human judgment as primary, and ongoing monitoring of AI outputs for accuracy and bias. Read the full guidance: https://coachingfederation.org/blog/artificial-intelligence-coaching.

## Client Consent for AI Features

Clients have the right to know when and how AI is used in their coaching. A best-practice consent process includes:

1. **Disclosure at intake:** "This coaching platform uses AI to generate session summaries based on your worksheet answers. These summaries are reviewed by your coach before use."
2. **Opt-out option:** Some clients may not want AI involved in their coaching. Provide a way to disable AI features for their account.
3. **Transparency in output:** If a session summary was AI-generated, the coach should disclose this: "I used an AI tool to draft this summary, then reviewed and edited it."
4. **Data use clarity:** Clients should know whether their worksheet data is used to train AI models. Most coaching platforms (including CoachSheets) do not use client data for model training, but confirm with your platform.

The ICF Code of Ethics emphasizes competence, confidentiality, and informed consent. These principles extend naturally to AI tools. Review the full code: https://coachingfederation.org/ethics/code-of-ethics.

## Practical Ethics Checklist for Digital Coaches

- [ ] I have read my platform's privacy policy and data processing agreement.
- [ ] My intake process includes a clear consent statement about data storage and AI use.
- [ ] I have a process for responding to data access and deletion requests.
- [ ] I review AI-generated content before using it with clients.
- [ ] I never present AI outputs as clinical diagnoses or professional medical advice.
- [ ] I have a data breach response plan.
- [ ] My clients know they can opt out of AI features.
- [ ] I comply with GDPR (or equivalent regulation) for all clients, regardless of location.

---

## Assignment

1. Draft a client consent statement (200-300 words) for your coaching practice that covers data storage, AI use, and client rights. Include an opt-out option for AI features.

2. Review your platform's privacy policy and data processing agreement. Write a 300-word summary of how your platform protects client data and where your responsibilities as the coach begin and end.

3. Research the ICF Code of Ethics and identify three specific principles that relate to the use of AI or digital tools in coaching. Write a brief paragraph on each explaining how it applies.

4. Create a simple data breach response plan. Include: who to notify, what information to share, and the timeline for notification.

---

## Knowledge Check

- What is the difference between encryption in transit and encryption at rest? Why do both matter?
- Does GDPR apply to you if you are based in the United States but have one client in Germany?
- What is data minimization and how does it apply to worksheet design?
- List three appropriate uses of AI in coaching and three never-appropriate uses.
- What should a coach disclose to a client about AI use in their coaching practice?
- What is the ICF's position on human judgment relative to AI in coaching?
- How quickly must you respond to a client's data access request under GDPR?
- When should a coach disable AI features for a specific client?
