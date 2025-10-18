🧠 NER-BERT-Experiments

This repository contains three independent Named Entity Recognition (NER) experiments in Portuguese, using BERT models with a CRF layer, with varying architectures and performance. All were trained with 10-fold cross-validation and evaluate the impact of different approaches on NER and Text Classification performance.

Available Models Experiment Model Description Location 🥇 1st Place BertcomCRF Portuguese-based BERT model + CRF BertcomCRF-1st-place/ 🥈 2nd Place BertsemCRF Optimized semantic version with BIO alignment adjustments BertsemCRF-2nd-place/ 🥉 3rd Place ModerBERTCRF Lighter architecture (ModernBERT) with CRF ModerBERTCRF-3rd-place/

🚀 How to run the experiments

Clone the repository:

git clone https://github.com/ThezGianTz/NER-BERT-Experiments.git cd NER-BERT-Experiments

Go to the directory of a specific model and run:

cd BertcomCRF-1st-place pip install -r requirements.txt python "BertcomCRF - 1st place.py"

Repeat the same procedure in BertsemCRF-2nd-place/ and ModerBERTCRF-3rd-place/.
