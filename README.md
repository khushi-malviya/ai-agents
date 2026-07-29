# AI Agents — Example Projects

A collection of small Python AI agent examples and experiments organized by day. These scripts are intended for learning, prototyping, and demonstration purposes.

## Project Overview

- **Purpose:** Demonstrate small AI agent patterns such as voice assistants, web scraping, document reading, and basic agent scaffolding.
- **Language:** Python 3.10+ recommended.
- **Status:** Example / educational code — not production-ready.

## Repository Structure

- [Day1/basic_ai_agent.py](Day1/basic_ai_agent.py) — minimal AI agent scaffold and demonstration.
- [Day2/ai_voice_assistant.py](Day2/ai_voice_assistant.py) — voice assistant core logic.
- [Day2/ai_voice_assistant_ui.py](Day2/ai_voice_assistant_ui.py) — optional Streamlit UI for the voice assistant.
- [Day3/ai_web_scraper.py](Day3/ai_web_scraper.py) — a basic web scraping example.
- [Day3/ai_web_scrapper_faiss.py](Day3/ai_web_scrapper_faiss.py) — an example integrating FAISS for vector search.
- [Day4/ai_document_reader.py](Day4/ai_document_reader.py) — document ingestion and simple QA example.

## Quick Start

1. Create a virtual environment and activate it:

```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS / Linux
source .venv/bin/activate
```

2. Install dependencies (if a `requirements.txt` exists). If not, install the libraries used by the example you want to run (e.g., `requests`, `beautifulsoup4`, `faiss-cpu`, `streamlit`).

```bash
pip install -r requirements.txt
```

3. Run an example script:

```bash
python Day1/basic_ai_agent.py
python Day2/ai_voice_assistant.py
python Day3/ai_web_scraper.py
python Day4/ai_document_reader.py
```

Note: Some scripts may require API keys or extra setup (microphone access, local model files, or third-party service credentials). Check the top of each script for configuration notes.

## Usage Notes

- Edit scripts directly to adjust model choices, API keys, or data paths.
- For the Streamlit UI, run:

```bash
streamlit run Day2/ai_voice_assistant_ui.py
```

- For FAISS-based examples, ensure the appropriate version of `faiss` is installed for your platform.

## Contributing

Contributions are welcome. Suggested workflow:

1. Fork the repository
2. Create a feature branch
3. Add or update examples and tests
4. Open a pull request with a clear description

Keep changes focused and backwards-compatible with the example scripts.

## License

This repository is provided for educational purposes. If you would like a specific license applied, add a `LICENSE` file and update this section.

## Contact

For questions or suggestions, open an issue or contact the repository owner.

---

Happy prototyping!
