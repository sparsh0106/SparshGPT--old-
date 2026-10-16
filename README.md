# SparshGPT Desktop Prototype

This repository contains an earlier desktop version of SparshGPT, built with CustomTkinter. It provides a text prompt window and an image URL plus caption window that send requests to an OpenAI-compatible chat-completions proxy.

The current web-based version is maintained in [sparsh0106/SparshGPT](https://github.com/sparsh0106/SparshGPT).

## Run locally

Install the dependencies:

```bash
python -m pip install -r requirements.txt
```

Set the `api_key` environment variable before launching the app.

**Linux or macOS**
```bash
export api_key="your_api_key"
python t.py
```

**Windows PowerShell**
```powershell
$env:api_key = "your_api_key"
python t.py
```

The text and image inputs are sent to the configured API service. Use a credential you control, keep it out of source control, and avoid submitting sensitive information.

## Repository contents

- `t.py` — CustomTkinter interface and chat-completions requests.
- `requirements.txt` — Python dependencies.
