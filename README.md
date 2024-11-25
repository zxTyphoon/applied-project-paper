# AI-Based Chatbot Development for Freudenberg & Co. KG  

This repository contains the LaTeX source code for the project report titled **"Development and Implementation of an AI-Based Chatbot for Freudenberg & Co. KG"**.  
**Note**: The project report is written in **German**, and all explanations and documentation within the project files are in German.  

## Abstract  

### German  
Diese Projektarbeit widmet sich der Entwicklung und Implementierung eines auf KI basierenden Chatbots bei Freudenberg & Co. KG (FCO).  
Ziel des Projekts ist es, die Effizienz innerhalb der Corporate IT Abteilung durch den Einsatz moderner KI-Technologien signifikant zu steigern.  

Im Rahmen dieser Arbeit wird eine umfassende Analyse gruppenweiter Anwendungsfälle durchgeführt, um spezifische Anforderungen von FCO zu identifizieren.  
Zur optimalen Umsetzung des Projekts werden verschiedene Large Language Models (LLMs) und Embedding-Modelle auf der SAP Business Technology Platform evaluiert. Dabei stehen insbesondere die Kriterien Antwortqualität, Antwortzeit und Kosten im Fokus, welche durch die Ergebnisse einer Umfrage unter internen Nutzern gewichtet wurden.  
Auf Basis der Analyse erweisen sich das Large Language Model **LLaMA3-70b** und das Embedding-Modell **text-embedding-3-large** als die am besten geeigneten Optionen.  

Anschließend erfolgt die Implementierung eines internen Chatbots mithilfe von SAP AI Core, der in der Lage ist, präzise und effiziente Antworten auf spezifische Anfragen zu liefern.  
Der Chatbot soll den Arbeitsalltag der Kollegen erleichtern und langfristig einen wertvollen Beitrag zur Verbesserung der internen Prozesse bei FCO leisten.  

### English  
This project report focuses on the development and implementation of an AI-based chatbot at Freudenberg & Co. KG (FCO).  
The primary goal of the project is to significantly enhance the efficiency of the Corporate IT department by leveraging modern AI technologies.  

The report includes a comprehensive analysis of group-wide AI use cases to identify specific requirements at FCO.  
To ensure optimal implementation, various Large Language Models (LLMs) and embedding models are evaluated on the SAP Business Technology Platform, focusing on response quality, response time, and cost.  
Based on these evaluations, the LLM **LLaMA3-70b** and the embedding model **text-embedding-3-large** were identified as the most suitable options.  

The implementation phase involves building an internal chatbot using SAP AI Core. This chatbot is designed to provide precise and efficient answers to specific queries, aiming to simplify employees' daily work and contribute to the long-term improvement of internal processes at FCO.  

## Repository Structure  

The following structure organizes the LaTeX files and assets used in the project:  

```plaintext
applied-project-paper/  
├── img/                   # Directory for all images and diagrams  
│   └── ...                # (Image files)  
├── textPages/             # Folder containing all chapter content  
│   ├── abstract.tex       # Abstract section  
│   ├── acknowledge.tex    # Acknowledgements  
│   ├── einleitung.tex     # Introduction  
│   ├── grundlagenteil.tex # Theoretical background  
│   ├── analyse.tex        # Analysis chapter  
│   ├── umsetzung.tex      # Implementation chapter  
│   ├── evaluation.tex     # Evaluation results  
│   └── fazit.tex          # Conclusion  
├── README.md              # This README file  
├── acronyms.tex           # List of acronyms used in the report  
├── bibliography.bib       # BibTeX file for references  
├── config.tex             # Configuration file for LaTeX settings  
├── master.pdf             # Compiled version of the report (output)  
├── master.tex             # Main LaTeX file to compile the report  
├── titlepage.tex          # Title page layout  



