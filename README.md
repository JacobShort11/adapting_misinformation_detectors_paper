# Adapting Misinformation Detectors to Counter LLM-Generated Fake News
### Research Paper for my Master's in Artificial Intelligence & Machine Learning

<p align="center">
  <img src="./img.png" alt="img">
</p>


### Code Structure
- **data_preparation.ipynb:** data cleaning and exploration.

- **bert_politifact.ipynb:** training, validation, testing, and resampling BERT models on human & LLMFake PolitiFact datasets.
- **bert_gossipcop.ipynb:** training, validation, testing, and resampling BERT models on human & LLMFake GossipCop datasets.
- **bert_coaid.ipynb:** training, validation, testing, and resampling BERT models on human & LLMFake CoAID datasets.

- **phi_politifact.ipynb:** testing PHI3 on human & LLMFake PolitiFact datasets.
- **phi_gossipcop.ipynb:** testing PHI3 on human & LLMFake GossipCop datasets.
- **phi_coaid.ipynb:** testing PHI3 on human & LLMFake CoAID datasets.

- **nb_politifact.ipynb:** training and testing NB on human & LLMFake PolitiFact datasets.
- **nb_gossipcop.ipynb:** training and testing NB on human & LLMFake GossipCop datasets.
- **nb_coaid.ipynb:** training and testing NB on human & LLMFake CoAID datasets.

- **misclassification_analysis.ipynb:** analysis into why models are misclassifying certain texts.

- **statistical_tests.ipynb:** Wilcoxon rank sign tests on performance metrics.
