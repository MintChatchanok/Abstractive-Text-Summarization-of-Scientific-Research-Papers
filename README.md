# 🧠 Abstractive Text Summarization of Scientific Research Papers
Using T5 Transformer-Based Models

This project explores abstractive summarization of domain-specific scientific research papers (IEEE format) using a pretrained T5 Transformer model. It includes data preprocessing, extractive scoring, and final generation of human-readable summaries that condense complex technical content.

# Project Highlights

📄 Corpus: Curated abstracts and full texts from IEEE scientific papers

🔍 Pipeline:
- Text preprocessing & filtering
- Sentence scoring via TF-IDF and positional weighting
- Abstractive summarization using Hugging Face's T5-base

🧪 Evaluation:
- ROUGE & BLEU scores
- Human comparison
- Explainability via SHAP & LIME

# Project Structure
<pre>abstractive-summarization/
├── src/                  
├── data/                 
├── models/     
├── README.md
└── requirements.txt </pre>

# Quick Start
<pre>git clone https://github.com/yourusername/abstractive-summarization.git
cd abstractive-summarization
pip install -r requirements.txt
python src/summarize_t5.py --input data/sample-paper.txt </pre>
