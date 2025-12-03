# 7CCSMCMP Coursework – Part 2
**Computer Programming for Data Scientists**  

---

## 📘 Overview

This repository contains the coursework submission for the 2nd part of the MSc module **7CCSMCMP: Computer Programming for Data Scientists** at King's College London. It comprises three Jupyter notebooks, each solving a distinct real-world problem using Python, Pandas, NetworkX, NLP libraries, and visualization tools.

---

## 📂 Repository Structure

```bash
7ccsmcmp-coursework-2/
│
├── activity1_covid_analysis/          # Activity 1 – COVID-19 Data Exploration
│   └── CW2_A1.ipynb
│
├── activity2_network_graph/           # Activity 2 – Matrix-based Graph Generation
│   └── CW2_A2.ipynb
│
├── activity3_turing_nlp/              # Activity 3 – NLP on Turing Award Winners
│   └── CW2_A3.ipynb
│
└── README.md                          # Project documentation
```


## 📊 Activities Summary

### Activity 1 – COVID-19 Data Analysis  
📁 `activity1_covid_analysis/CW2_A1.ipynb`

- Retrieves UK COVID-19 data via the **UKHSA API** (with fallback CSV support).
- Builds and cleans **Pandas DataFrames** containing daily case and death counts.
- Applies:
  - Datetime conversion
  - Missing value handling
  - 7-day rolling averages
- Visualizes trends using **native Pandas plotting**:
  - Regional and national case patterns
  - Cumulative trajectories and plateaus
- Includes analytical commentary throughout.

---

### Activity 2 – Network Graph Generation  
📁 `activity2_network_graph/CW2_A2.ipynb`

- Constructs a **matrix-based graph** using **NetworkX**.
- Randomly selects foreground/background nodes:
  - Background nodes → connected to all 8 neighbours
  - Foreground nodes → connected to 4 cardinal neighbours
- Computes key graph metrics:
  - Graph density
  - Degree centrality
- Visualizes the graph using **Matplotlib**.
- Exports the graph structure as a **JSON file** with node and edge properties.

---

### Activity 3 – NLP on ACM Turing Award Recipients  
📁 `activity3_turing_nlp/CW2_A3.ipynb`

- Gathers award recipient data via the **Wikidata and Wikipedia APIs**.
- Builds a structured dataset including:
  - Name, gender, intro text, birth date/place, education, employer
- Applies NLP techniques using **NLTK**:
  - Tokenization and stopword removal
  - Stemming (Porter, Snowball) and lemmatization
  - Synonym and antonym extraction using **WordNet**
  - Bigram frequency analysis
- Visualizes word, sentence, and paragraph counts using **Matplotlib subplots**:
  - Custom colors
  - Rotated axis labels
  - Inline value annotations
  - Mixed horizontal and vertical bar layouts

---

 ## Author

**Ammar Arfan**  
MSc Data Science  
King’s College London  
Module: *7CCSMCMP Coursework: Computer Programming for Data Scientists*  
Supervisor: Dr. Sophia Tsoka   
Email: [K24101560@kcl.ac.uk](mailto:K24101560@kcl.ac.uk)

---

## License
This repository is a part of MSc-level coursework submitted to King’s College London. It is shared strictly for educational and professional portfolio purposes and must not be reused or redistributed for academic credit.
