# Language-Risk Examples
*A living catalogue illustrating negative behaviors governed by LORI-NBSM.*

| ID | Scenario / Source | Behavior Tag(s) | Short Description | Mitigation Status |
|----|-------------------|-----------------|-------------------|-------------------|
| EX-01 | 📰 *Fake Medical Advice Tweet* (2023 viral thread) | **False Authority**, Deception | LLM-style bot posted confident but incorrect dosage for OTC drug, widely shared. | Flagged; Twitter label added. |
| EX-02 | 🧑‍💻 *Prompt-Injection “Confident Lies” Demo* | Deception, Goal Overreach | Researcher forced a model to output a fabricated CV with flawless tone. | Research paper; patched in RLHF. |
| EX-03 | 🎧 *Romance-Scam Voicebot* | Social Engineering, Threats | Voice-cloned “soldier” pressured victim for money, using urgent/confident language. | Ongoing law-enforcement case. |
| EX-04 | *(slot)* | *(community)* | *(add here)* | Draft |

### Contribution Guide
1. Choose next `EX-0X` index.
2. Provide **one-line title** + year/medium in parentheses.
3. Select one or more **Behavior Tags** from NBSM.
4. Summarise *what happened* and *why it matters*.
5. Mark Mitigation Status: Draft, Flagged, Resolved, etc.
