# Hello-World

An interactive AI interface that lets you explore how input-validation levels shape
human–computer interaction in conversational AI systems.

## Demo

Open `index.html` in any modern browser. No build step or server required — it runs
entirely in the browser.

## What it demonstrates

The interface provides a chat window paired with three selectable validation modes:

| Mode | Behaviour |
|------|-----------|
| **None** | All inputs accepted — no restrictions applied |
| **Minimal** | Inputs must be at least 3 characters long |
| **Strict** | Inputs must be ≥ 5 characters and contain only letters, numbers, spaces, and basic punctuation |

Switching between modes in real time shows how validation gates affect the conversation:
which messages are blocked, which edge cases reach the AI, and how the absence of
validation widens the accessible input space.

## Purpose

This demo supports a narrative on AI systems and human–computer interaction, specifically
examining how **low validation environments** differ from hardened production systems.
Real deployments must balance openness (to serve diverse human expression) against
robustness (to handle malformed or harmful input gracefully).
