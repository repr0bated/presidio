# Presidio Gemini Context

## Focus Area
**Privacy/PII**

## Why Index?
Informs your `redaction` logic for HIPAA, GDPR, and SOC2 compliance. Reference for PII identification and anonymization.

## Project Description
Context aware, pluggable and customizable PII de-identification service for text and images.

## Key Concepts
- **Analyzer**: Detects PII entities in text/images.
- **Anonymizer**: Replaces/redacts detected PII.
- **Image Redactor**: Handles PII in images.
- **Structured**: Handles PII in structured data.

## Conventions
- **Language**: Python
- **Architecture**: Modular services (Analyzer, Anonymizer).
