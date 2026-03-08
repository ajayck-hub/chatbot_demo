# Chatbot

A simple string-matching conversation bot programmed entirely in Python, using Regular Expressions (regex) to map user input keywords to specific fallback responses.

## Features
- **Dictionary-Based Engine**: Identifies key phrases (`hello`, `hi`, `help`, `bye`) and maps them to human-readable responses string outputs via `re.search`.
- **Default Fallback**: Triggers an unconditional fallback text map when zero keywords match the phrase to maintain conversational fluidity.
- **Lowercased Ingest**: Automatically transforms user input so that it functions independently of title casing.
- **Interactive Shell**: Keeps Python waiting in an active while loop so the user can continually ask queries.

## Prerequisites
- Python 3.x
- `re` (Standard Python Library)

## Usage
Run the file via the terminal:

```bash
python chatbot.py
```

Begin typing any queries! When you are finished, enter `bye` to terminate the script loop.
