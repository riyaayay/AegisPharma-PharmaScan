# AegisPharma-PharmaScan
Aegis-Pharma PharmaScan: Multi-Agent AI for Rural Drug Safety and Healthcare Feedback
Project Description
Aegis-Pharma PharmaScan is a multi-agent AI system designed for proactive monitoring of adverse drug reactions (ADRs) and collection of rural healthcare feedback via voice, chat, and SMS. This project leverages an extensive CSV-based knowledge base of drug side effects, advanced vector search with local embeddings, and modular agent orchestration implemented in Python using LangChain.

The system serves rural populations by identifying potential drug safety concerns, enabling regulated ADR reporting, and engaging communities for feedback on healthcare services and government schemes.

Features
Processes drug ADR data from CSV files with rich metadata

Multi-agent design with roles: sentinel, analyst, scribe, and communicator

Local vector search using sentence-transformer embeddings (no API rate limits)

Simulated voice/SMS follow-ups to users for data enrichment

Designed for multilingual and culturally sensitive rural interactions

Demo-ready with modular components for easy testing and extension

Installation
Requires Python 3.8+

Install dependencies using:

bash
pip install -r requirements.txt
Usage
Clone or download the repository

Place Drugs - Sheet2.csv in the working directory

Set your OpenAI API key as an environment variable (optional for advanced text generation)

Run the main Python script to start agent workflows and conduct sample ADR detection tests

bash
python main.py
Project Structure
text
├── Drugs - Sheet2.csv       # Drug ADR data file
├── main.py                  # Main multi-agent pipeline script
├── README.md                # Project documentation
├── requirements.txt         # Dependencies list
└── demo/                    # Demo audio and scenario scripts
Contributing
Contributions are welcome! Please fork the repo and submit pull requests with improvements, bug fixes, or new features.

License
This project is licensed under the MIT License.

Contact
For questions or support, contact: riyarathod415@gmail.com
