# LLM Prompt Attacks – Jailbreaks & Injection Techniques

This repository explores multiple prompt injection and jailbreak techniques used to test the security of large language models (LLMs). These experiments are designed to simulate adversarial scenarios and evaluate how well models resist manipulative or malicious prompts.

> 🧪 This is part of an educational portfolio in LLM red teaming and GenAI threat research.

---

## 📂 Attack Files Included

- `dan-jailbreak.md` – Dual-role persona jailbreak using the DAN (Do Anything Now) format.
- `ignore-instructions.md` – Classic "Ignore previous instructions" override attack.
- `grandma-mode.md` – Roleplay-based social engineering prompt.
- `reverse-psychology.md` – Subversive prompts using denial or sarcasm cues.

---

## 🧠 Purpose

Each attack demonstrates a different class of vulnerability:

| Attack Type          | Technique                              | Risk Area                        |
|----------------------|----------------------------------------|----------------------------------|
| DAN Jailbreak        | Role/Persona Injection                 | Identity hijack, unfiltered output |
| Ignore Instructions  | Direct instruction override            | Prompt precedence manipulation   |
| Grandma Mode         | Roleplay & emotional disguise          | Indirect content leakage         |
| Reverse Psychology   | Psychological misdirection             | Filter evasion via sarcasm       |

---

## 🖼️ Screenshots

If available, screenshots of model outputs (successful or blocked) are stored in the `screenshots/` folder.

---

## 🛡️ Defense Ideas (General)

- Persona locking and role verification
- Prompt parsing with semantic intent detection
- Filter bypass pattern matching (e.g., dual format, reverse logic)
- OWASP Top 10 for LLM guidelines enforcement

---

## 📚 References

- [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
- [LLM Attacks Database](https://llm-attacks.org/)
- [PromptAttack.dev](https://promptattack.dev/)
- Red team tools like Promptfoo, PyRIT, LangChain-Evals

---

## ⚠️ Disclaimer

All tests were conducted using public LLM APIs and open-source models for **educational and ethical research only**. This content is not intended to promote misuse or illegal activity.

---

🧠 Maintained by a cybersecurity enthusiast learning LLM red teaming and AI threat modeling.
