# Tools For Analyzing Features 

## Features 
### 1. [SHAP](https://github.com/slundberg/shap)
- A game theoretic approach to explain the output of any machine learning model
- Functions
  - Natural language example (transformers)
  - Tree ensemble example (XGBoost/LightGBM/CatBoost/scikit-learn/pyspark models)
  - Deep learning example with GradientExplainer (TensorFlow/Keras/PyTorch models)
  - Model agnostic example with KernelExplainer (explains any function)
### 2. [Bokeh](https://docs.bokeh.org/en/latest/docs/user_guide.html) 
- Interactive Data Visualization in the browser, from Python
- Functions 
  - Scatter plots
  - Lines and curves
  - ...
### 3. [Scattertext](https://github.com/JasonKessler/scattertext)
- Beautiful visualizations of how language differs among document types
- Functions
  -  Visualizing differences based on only term frequencies
  - Visualizing query-based categorical differences
  - Visualizing any kind of term score
  - Custom term positions
  - Emoji analysis
  - Visualizing SentencePiece tokens
  - Visualizing scikit-learn text classification weights
  - Creating lexicalized semiotic squares
  - Visualizing topic models
  - Creating T-SNE-style word embedding projection plots
  - Using SVD to visualize any kind of word embeddings
  - Exporting plot to matplotlib
  - Using the same scale for both axes





## Model Visualization
### 1. [Transformer Interpretability Beyond Attention Visualization](https://github.com/hila-chefer/Transformer-Explainability)
- [CVPR 2021] Official PyTorch implementation for Transformer Interpretability Beyond Attention Visualization, a novel method to visualize classifications by Transformer based networks.
- Functions 
  - Reproducing results on ViT
    - Segmentation Results
    - Perturbation Results  
  - Reproducing results on BERT

### 2. [BertViz](https://github.com/jessevig/bertviz)
- BertViz: Visualize Attention in NLP Models (BERT, GPT2, BART, etc.)
- Functions
  - Head View : The head view visualizes attention for one or more attention heads in the same layer. 
  - Model View : The model view shows a bird's-eye view of attention across all layers and heads.
  - Neuron View : The neuron view visualizes individual neurons in the query and key vectors and shows how they are used to compute attention.
### 3. [Thermostat](https://github.com/DFKI-NLP/thermostat)
- Collection of NLP model explanations and accompanying analysis tools
- Functions 
  - Visualizing attributions as a heatmap
  - Get simple tuple-based heatmap
  - ...

### 4. [Transformers Interpret](https://github.com/cdpierse/transformers-interpret#transformers-intepret)
- Model explainability that works seamlessly with 🤗 transformers. Explain your transformers model in just 2 lines of code.
- Functions 
  - Sequence Classification Explainer and Pairwise Sequence Classification
  - MultiLabel Classification Explainer
  - Zero Shot Classification Explainer
  - Question Answering Explainer
  - Token Classification (NER) explainer
