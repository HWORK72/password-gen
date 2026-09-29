🇷🇺 [Читать на русском](README_RU.md)

A lightweight web microservice designed for generating cryptographically secure, high-entropy passwords resilient to distributed brute-force and dictionary attacks.

### Key Architectural Highlights:
* **CSPRNG-Backed Randomness:** Leverages the native `secrets` module providing hardware-backed cryptographic randomness immune to algorithmic predictability.
* **Custom Entropy Modeling:** Configurable character spaces supporting uppercase, lowercase, numeric, symbolic, and whitespace tokens with enforced entropy thresholds.
* **Clean Web Runtime:** Streamlined Flask routing serving instantaneous generation pipelines to client frontends.
* **Cloud-Ready Configuration:** Pre-configured deployment architecture optimized for hosted PythonAnywhere environments.

### Tech Stack:
* Python 3.12
* Flask (Microframework runtime)
* Secrets / Cryptographic primitives
* HTML5 / CSS3 (Frontend presentation)

### Quick Start:
```bash
pip install -r requirements.txt
python flask_app(8).py
