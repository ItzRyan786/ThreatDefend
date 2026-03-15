Project Overview: ThreatDefend Forensic Node
ThreatDefend is a multi-layered cybersecurity analysis tool designed to detect sophisticated phishing and social engineering attacks that traditional signature-based systems often miss. By combining Machine Learning, Heuristic Behavioral Scoring, and Real-time Intelligence APIs, it provides a "Defense-in-Depth" approach to forensic log analysis.

Core Intelligence Layers
The system operates on three distinct analytical planes:

The Neural Engine (AI Layer):
Utilizes a specialized BERT-Tiny model (Natural Language Processing) to analyze the syntax and intent of messages. It looks for patterns common in "spam" or "scam" communications—such as impersonal greetings, unusual grammatical structures, and typical phishing narratives—even if the keywords are slightly altered.

The Heuristic "Bruh" Shield:
A custom rule-set designed for the modern web. It scores "Zero-Day" threats by identifying behavioral red flags:

Masked Redirects: Detects when legitimate services (Google, Firebase, Cloudflare Pages) are used to host malicious login portals.

Psychological Pressure: Scans for high-urgency language and "lockout" threats.

Out-of-Band Evasion: Flags efforts to move communication to unmonitored channels like WhatsApp or Telegram.

The Universal Unmasker (URL Intel):
A pre-emptive defense layer that automatically de-shortens links (Bitly, TinyURL). It uses a "Silent GET" method to force redirects to reveal their final destination. This unmasked URL is then cross-referenced with the VirusTotal API for global reputation hits.

Technical Architecture
The project is built using a modern, lightweight stack designed for high-speed local deployment:

Backend: FastAPI (Python) for asynchronous request handling.

AI Framework: Hugging Face Transformers for local neural inference.

Frontend: A high-end "Cyber-Vanguard" dashboard styled with Tailwind CSS, utilizing Glassmorphism and HUD-style animations.

Intelligence Node: Integrated with VirusTotal v3 API for real-time domain reputation.

Why It’s Unique
Unlike standard antivirus software that relies on a database of "known bad" files, ThreatDefend identifies intent. If a scammer creates a brand-new link that no one has reported yet, the system’s heuristic and AI layers can still flag it as "Suspicious" based on the structural DNA of the attack.



