# Hi, I'm David Perez-Rueda

Mathematics student at Rowan University, Aerospace Propulsion Apprentice in the New Jersey Air National Guard, and founding engineer of ToolBelt. I build production software and study how language models behave under internal steering.

My main projects are in private repositories. Below is what each one does, what it's built with, and where it stands. I'm happy to walk through code or grant temporary access on request.

---

## ToolBelt — Multi-Tenant SaaS for Service Businesses
**Founding Engineer · Feb 2026–Present · In use by businesses via TestFlight; App Store release in review**

AI-driven SMS appointment scheduling, payments, and accounting for salons, medical offices, and contractors.

- Started the project and authored ~86% of commits: SwiftUI iOS client, Node/Express API (all middleware, 38 of 46 route modules, ~37 core services), and the Firestore data model
- Stripe Connect payments, POS, and invoicing; Twilio SMS with A2P 10DLC and TCPA compliance
- An LLM SMS assistant (Anthropic API, tool calling) that books, reschedules, and confirms real appointments from plain-text messages
- Security from day one: certificate pinning, field-level PII encryption, TOTP 2FA, passkeys, Firestore security rules, append-only consent audit logs
- 619 automated tests (unit + Firestore emulator integration) running in GitHub Actions CI

`Swift` `SwiftUI` `SwiftData` `Node.js` `Express` `Firestore` `Stripe` `Twilio` `Plaid` `Anthropic API`

---

## WhiteBoard — AI Math Tutor for Classroom Whiteboards
**Team of 3 · In Progress**

A webcam watches a classroom whiteboard, reads each new line of handwritten math, checks it against the previous step, and projects a mark next to mistakes.

▶️ **Demos:** [Video 1](https://youtu.be/c2K597ax6zc) · [Video 2](https://youtu.be/PlvWIMPFnVc)

- Two-tier recognition: a fast ONNX model (~110 ms per line) that escalates uncertain lines to a 2B-parameter vision-language model; 76–78% accuracy on real board images
- OpenCV change detection that separates new writing from hands and bodies blocking the board
- Camera-to-projector calibration (ChArUco markers, homography) so marks land beside the right line
- Prefers saying "unknown" over wrongly marking a correct step in front of a class
- 180+ automated tests

`Python` `OpenCV` `PyTorch` `ONNX Runtime` `SymPy` `Next.js`

---

## Research — Escalation Tipping Points Under Emotion-Direction Steering
**Independent research, Rowan Mathematics · In Progress**

Do emotion-associated steering directions push small language models past an escalation tipping point in a repeated crisis game?

- The game is modeled as an exact 6-state Markov chain whose transition matrix is computed from model log-probabilities, with no sampling
- The tipping point α* is defined through the stationary distribution; the spectral gap and hitting times characterize the transition
- Pilot (Qwen 2.5 3B): α* ≈ 0.44. Fear steering cut low-escalation mass to 0.18, versus a 0.89 mean for random directions of equal strength
- Found and corrected three measurement artifacts (letter echo, option-order bias, phrase echo)
- Code and data will be released publicly with the paper

`Python` `PyTorch` `Hugging Face Transformers` `NumPy` `Markov chains` `Spectral analysis`

---

## Skills
**Languages:** Python, Swift, TypeScript/JavaScript
**ML & CV:** PyTorch, Transformers, ONNX Runtime, OpenCV, activation steering, model evaluation
**Backend & Mobile:** SwiftUI, Node.js, Express, Firebase/Firestore, Next.js, React
**Math:** Markov chains, spectral analysis, bootstrap statistics, SymPy, LaTeX

📫 David.perezrueda2007@gmail.com
