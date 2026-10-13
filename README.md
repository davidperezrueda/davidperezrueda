David Perez
Newton, NJ · 862-312-1376 · David.perezrueda2007@gmail.com · github.com/davidperezrueda
Mathematics student and Air National Guard aerospace propulsion apprentice with active Secret clearance, independent research on language-model interpretability, and founding-engineer experience building an iOS SaaS product used by real businesses. Seeking internships in software engineering, machine learning, or data analysis.
Education
Rowan University — B.S. Mathematics · Expected May 2030
Kittatinny Regional High School — Graduated 2025 · School Chess Champion (2023, 2024) · Competitive Math League
Military Service
New Jersey Air National Guard — Aerospace Propulsion Apprentice (3-Level) · Feb 2025–Present · Active Secret Clearance
• Completed Air Force technical training and earned the 3-level apprentice rating in aerospace propulsion
• Inspect, maintain, and troubleshoot aircraft engine systems following technical orders and strict safety procedures
Projects
ToolBelt — Multi-Tenant SaaS for Service Businesses · Founding Engineer · Feb 2026–Present · In use by [N] businesses via TestFlight; App Store release in review Swift, SwiftUI, SwiftData, Node.js/Express, Firestore, Stripe, Twilio, Plaid, Anthropic API
• Founded and architected an iOS + Node/Express platform giving businesses AI-driven SMS scheduling, payments, and accounting; authored ~86% of commits, including all API middleware, 38 of 46 route modules, and ~37 core services
• Built Stripe Connect payments, POS, and invoicing; Twilio SMS with A2P 10DLC compliance; and an LLM SMS assistant (Anthropic API, tool calling) that books real appointments
• Designed security in from day one: certificate pinning, field-level PII encryption, TOTP 2FA, passkeys, and Firestore rules; set up CI and test infrastructure (619 tests) and onboarded a second engineer through a pull-request workflow
WhiteBoard — AI Math Tutor for Classroom Whiteboards · Team of 3 · In Progress · Demos: youtu.be/c2K597ax6zc · youtu.be/PlvWIMPFnVc Python, OpenCV, PyTorch, ONNX Runtime, SymPy, Next.js
• Built a computer-vision pipeline that watches a whiteboard by webcam, reads each new line of handwritten math to LaTeX, checks it against the previous step, and projects a mark beside mistakes
• Benchmarked recognition models and designed a two-tier system: a fast ONNX model (~110 ms/line) that escalates uncertain lines to a 2B-parameter vision-language model, reaching 76–78% accuracy on real board images
• Built OpenCV change detection that separates new writing from hands and bodies blocking the board; validated on recorded classroom video
• Implemented camera-to-projector calibration (ChArUco markers, homography) and a Next.js projector page; 180+ automated tests
Escalation Tipping Points Under Emotion-Direction Steering in Small Language Models · Independent Research, Rowan Mathematics · In Progress Python, PyTorch, Hugging Face Transformers, NumPy; Markov chains, spectral analysis, bootstrap statistics
• Modeled a steered LLM playing a repeated crisis game as an exact 6-state Markov chain built from model log-probabilities, and defined an escalation tipping point (α*) via stationary distributions, spectral gaps, and hitting times
• Pilot on Qwen 2.5 3B found a tipping point at α* ≈ 0.44, with fear-direction steering cutting low-escalation mass to 0.18 versus a 0.89 mean for random directions of equal strength
• Identified and corrected three measurement artifacts (letter echo, option-order bias, phrase echo) through paraphrasing and six-way counterbalancing; preparing an OSF pre-registration and workshop submission
Experience
Receptionist — Body and Skin Spa, Augusta, NJ · 2023–Present
• Manage appointment scheduling, client communication, inventory ordering, and POS transactions for a family-owned spa
Receptionist / Food Runner — Alpha Fitness Gym, Newton, NJ & Mountain House, Branchville, NJ · 2024–2025
• Managed memberships, transactions, and inventory; ran the expo line and coordinated orders with kitchen staff
Community Outreach Member — Center for Prevention (Incorruptibles), Newton, NJ · 2022–2025
• Designed and delivered presentations to deter adolescent substance use; built and ran surveys of students and faculty
Technical Skills
Languages: Python, Swift, TypeScript/JavaScript Computer Vision & ML: OpenCV, PyTorch, Hugging Face Transformers, ONNX Runtime, camera calibration, model benchmarking Mobile & Backend: SwiftUI, SwiftData, Node.js, Express, Firebase/Firestore, Next.js, React APIs: Stripe Connect, Twilio, Plaid, Anthropic API, Google Calendar API, WebAuthn/passkeys Math: Markov chains, spectral analysis, bootstrap statistics, SymPy, LaTeX Tools: Git/GitHub (branches, pull requests), pytest, GitHub Actions CI
