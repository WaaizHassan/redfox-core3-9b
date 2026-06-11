🦊 Redfox‑Core3:9B
A balanced, fast, personality‑tuned AI model built on Gemma2‑9B
Redfox‑Core3:9B is the core personality model of the Redfox ecosystem — designed for clean reasoning, coding assistance, and a calm, balanced conversational tone.
This version is built on Google’s Gemma2‑9B, providing strong performance, low latency, and excellent instruction‑following while keeping the signature Redfox feel.

🔥 Features
Balanced Redfox Core personality  
Smart, helpful, calm, and consistent — the default Redfox experience.

Gemma2‑9B foundation  
Strong reasoning, efficient inference, and high‑quality responses.

Fast + lightweight  
Runs well on consumer GPUs and even CPU‑only setups with quantization.

Offline‑friendly  
Works fully locally through Ollama.

Safe + compliant  
No harmful instructions, no jailbreak behavior, no unsafe tuning.

🧠 Use Cases
Coding help

Debugging

General reasoning

Writing + productivity

Chatting

Terminal assistants

Local AI agents

Redfox ecosystem tools (Nile, SqueezeBox, etc.)

🚀 Usage
After installing via Ollama:

Code
ollama run redfox-core3:9b
Or run with a prompt:

Code
ollama run redfox-core3:9b "Explain how binary search works"
📦 Model Architecture
Base model: Gemma2‑9B

Type: Instruction‑tuned

Personality layer: Redfox Core3

Quantization: Depends on user system (Q4_K_M recommended for most GPUs)

📄 Modelfile
This model uses a Modelfile that layers the Redfox Core3 personality on top of Gemma2‑9B.
You can view or modify the Modelfile in this repository.

📚 License
This model is built on Gemma2‑9B, which is licensed under Apache 2.0.
You must include the Apache 2.0 license when redistributing.

Redfox‑Core3 personality layer © 2026 Waaiz.

🤝 Credits
Base model: Google — Gemma2‑9B

Personality + tuning: Waaiz (Redfox Project)

Packaging: Ollama Modelfile format

🦊 About Redfox
Redfox is a lightweight, fast, personality‑driven AI ecosystem designed for:

local agents

coding tools

terminal assistants

offline workflows

clean UI + developer‑friendly design

Redfox‑Core3:9B is the mainline model powering the ecosystem.
