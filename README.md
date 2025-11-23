# Spraakzaak

**Transcribe. Understand. Improve.**

Spraakzaak is a modular system for processing, organizing, and evaluating meeting transcripts, designed for public sector organizations.  

The goal is to make meetings more accessible through automatic transcription, speaker recognition, and summarization, with focus on privacy, modularity, and scalability.

## Project Structure

Spraakzaak has three main components, each maintained in a separate repository:

### Front-end – *Spraakzaak App*

A web application for uploading or recording meetings, scheduling transcriptions, and viewing or summarizing meetings.

**Repository:** [spraakzaak-frontend](https://github.com/responsibleIT/spraakzaak-frontend)

### Back-end – *Spraakzaak Backend*
Handles the core processing tasks:
- Speech-to-text transcription  
- Diarisation (speaker recognition)  
- Meeting summarization  

It supports multiple **workers** for horizontal scalability, models (ASR, diarisation, summarization, validation), and can be deployed **on-premise**.

**Repository:** [spraakzaak-backend](https://github.com/responsibleIT/spraakzaak-backend)

### Evaluator – *Spraakzaak Evaluator*
Used to collect performance metrics such as:
- **WER** – Word Error Rate  
- **DER** – Diarisation Error Rate  

These metrics are based on human-annotated meetings and are used to evaluate and improve the system’s accuracy.

**Repository:** [spraakzaak-evaluator](https://github.com/responsibleIT/spraakzaak-evaluator)

## Project Status

This is a **public project**, but **not open source**. Thus, participation or contributions are subject to approval by the project partners:

- **Gemeente Amsterdam (City of Amsterdam)**  
- **Responsible IT Lab, Amsterdam University of Applied Sciences (HvA)**

## Contact

For questions or participation inquiries:

- **Marcio Fückner** – Researcher and Lecturer  
  ✉️ [m.fuckner@hva.nl](mailto:m.fuckner@hva.nl)

- **Virgill van der Meer** – Gemeente Amsterdam  
  ✉️ [v.van.der.meer@amsterdam.nl](mailto:v.vandermeer@amsterdam.nl)
