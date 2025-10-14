# Your Honor, ChatGPT Made Me Do It  
### The New Ethics Crisis in Law

[![Python](https://img.shields.io/badge/Python-3.10-blue.svg)](https://www.python.org/)  
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![Google Colab](https://img.shields.io/badge/Open_in-Colab-orange.svg)](https://colab.research.google.com/drive/1sqPSVzniabv2fOe7DQ-CPyD6MXZje2f2?usp=sharing)  
[![Dataset](https://img.shields.io/badge/Dataset-Kaggle-lightblue.svg)](https://www.kaggle.com/datasets/umerhaddii/ai-hallucination-cases-data-2025)  

---

## Overview  

This project visualizes and interprets the rise of **AI hallucinations in legal cases**, using **Damien Charlotin’s global database of AI-related court incidents**.  
It documents real-world legal decisions where **generative AI tools like ChatGPT** produced fabricated citations or misleading content that reached the courtroom.  

The story unfolds through **three data panels** that reveal how quickly generative AI entered legal practice, who used it, and how judges have responded.

The central thesis:  
> The legal profession is adopting AI faster than it can regulate its truth.

---

## Methodology  

**Data Source:**  
- [AI Hallucination Cases Dataset (Kaggle)](https://www.kaggle.com/datasets/umerhaddii/ai-hallucination-cases-data-2025)  
- Curated by **Damien Charlotin**  
- Covers **400+ court decisions** worldwide  
- Includes: case name, jurisdiction, decision date, responsible party, AI tool used, and outcome  

**Biases & Limitations:**  
- **Reporting bias:** Unpublicized cases likely missing  
- **Jurisdiction bias:** Overrepresentation of English-speaking courts  
- **Role imbalance:** Lawyers and pro se litigants dominate  
- **Temporal lag:** Manual updates create delays  

**Analysis Workflow:**  
1. Data cleaned and explored in **Google Colab**  
2. Code generated with **Gemini** and **GPT-5** for visualizations  
3. Time series and categorical breakdowns plotted in **Seaborn** and **Matplotlib**  
4. Persona prompt-engineering principles applied to shape AI explanations and tone  

---

## Persona Prompt Engineering  

This project applied controlled **AI persona prompting** to balance analytical tone and ethical critique.  
Example technique:  
- *Role Definition:* “You are a data journalist uncovering the impact of AI misuse in law.”  
- *Constraint Framing:* “Use neutral, verifiable language suitable for legal audiences.”  
- *Perspective Anchoring:* Each panel narrates data as if voiced by a judicial analyst rather than a data scientist.  

This method ensured **clarity, accuracy, and credibility** when synthesizing AI-assisted insights.

---

## Three-Panel Data Story  

### Panel 1 – The Meteoric Rise of Cases and LLMs  
- Maps the **monthly increase in AI-related legal incidents** since 2023.  
- Aligns case spikes with **major LLM releases** (GPT-4, Claude 2, GPT-4o).  
- Highlights correlation between **model sophistication** and **hallucination detectability**.  

### Panel 2 – Who Chat-ed the Cases?  
- Breaks down offenders by **role** (lawyers vs pro se litigants).  
- Reveals that **both professionals and laypeople** rely on AI for legal writing.  
- Raises ethical questions about **due diligence and informed AI use**.  

### Panel 3 – How Do We Punish Misuse?  
- Examines judicial **responses and sanctions**.  
- Finds that **most cases faced no penalties**, suggesting slow adaptation by courts.  
- Indicates growing movement toward **accountability standards for AI use** in filings.  

---

## Results and Insights  

- **High-profile precedent:** The 2023 *Avianca v. ChatGPT* case, where lawyers submitted six fabricated citations and were fined $5,000.  
- **Pattern detected:** As models become more fluent and multimodal, hallucinations grow harder to detect.  
- **Judicial gap:** Sanctions are rare; courts treat misuse as negligence, not intent.  
- **Ethical takeaway:** The line between human and machine authorship in legal reasoning is blurring faster than regulation can respond.  

---

## Files Description  

| File | Description |
|------|--------------|
| `IPHS200_MKocaman_MP1.pdf` | Project write-up and background analysis on dataset biases and limitations |
| `iphs200_mkocaman_mp1 (2).pdf` | Presentation slides summarizing three data panels, visual results, and final reflections |
| `colab_notebook_link` | [Google Colab Notebook](https://colab.research.google.com/drive/1sqPSVzniabv2fOe7DQ-CPyD6MXZje2f2?usp=sharing) |
| `dataset_link` | [Kaggle Dataset](https://www.kaggle.com/datasets/umerhaddii/ai-hallucination-cases-data-2025) |

---

## Usage Instructions  

1. Open the Colab notebook above.  
2. Run the notebook cell-by-cell to reproduce the visualizations.  
3. Modify dataset filters (e.g., jurisdiction, party type) to create alternative views.  
4. Use results for academic writing, ethics discussions, or AI-policy presentations.  

---

## Installation  

```bash
# clone repository
git clone https://github.com/murathan9165/iphs200-3-panel-story-mp-1.git
cd iphs200-3-panel-story-mp-1

# install dependencies
pip install pandas matplotlib seaborn
```

---

## Contributing  

Contributions are welcome for:  
- New panels expanding global AI-law intersections  
- Updated datasets tracking post-2025 cases  
- Alternative visual storytelling approaches  

Please submit a pull request with a short summary of your changes.

---

## License  

This project is released under the **MIT License**.  
Feel free to reuse and adapt with credit to **Murathan Kocaman (Kenyon College)**.

---

## Citation  

If referencing this project in academic work:  

> Kocaman, M. (2025). *Your Honor, ChatGPT Made Me Do It: The New Ethics Crisis in Law.* Kenyon College IPHS200 Data Story Project. GitHub Repository: [https://github.com/murathan9165/iphs200-3-panel-story-mp-1](https://github.com/murathan9165/iphs200-3-panel-story-mp-1)
