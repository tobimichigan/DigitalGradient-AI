# DigitalGradient-AI
A Hybrid Multi-Agent Retrieval-Augmented Generation Framework for Scalable Semantic Search and Intelligent Customer Support Systems


<p ><h1 align="center">ABSTRACT</h1></p>

<p>
This research & development innovation presents a novel hybrid architecture that integrates classical machine learning, deep neural networks, and large-scale transformer-based models into a unified multi-agent Retrieval-Augmented Generation (RAG) system. The proposed framework leverages a fine-tuned large language model based on NVIDIA’s Nemotron architecture, enhanced with parameter-efficient fine-tuning via Low-Rank Adaptation (LoRA), enabling high-performance inference without full model retraining.
The system pipeline is composed of structured stages including data preprocessing, stratified data splitting, feature engineering using TF-IDF and dimensionality reduction, and model training via both ensemble methods (Gradient Boosting, Random Forest, Logistic Regression) and deep neural architectures (multi-layer perceptrons). A vector-based semantic retrieval layer is constructed using dense embeddings and approximate nearest neighbor indexing, followed by cross-encoder re-ranking to improve contextual relevance.
A key contribution is the integration of a multi-agent orchestration layer, where specialized agents (billing, technical, and general support) are dynamically routed using intent classification heuristics. The system incorporates knowledge base retrieval, contextual grounding, and response generation using RAG, while enforcing privacy through rule-based PII guardrails and enabling escalation through simulated ticketing APIs.
Experimental evaluation demonstrates improved accuracy, relevance ranking, and robustness across training, validation, test, and holdout datasets, with effective mitigation of overfitting through early stopping, ensembling, and regularization techniques. The framework mirrors real-world cloud AI infrastructures and provides a scalable blueprint for deploying intelligent, domain-aware conversational systems in enterprise environments.
</p>

<p>Demo Link: https://handsonlabs.org/DigitalOceanGradient_AI/DigitalGradientAI_v2.html</p>
<h2 align="left"> 
<h1> MLP Training Curves: Training vs Validation Loss Curves </h1>
  <br>
 <a href=""><img src="https://github.com/tobimichigan/DigitalGradient-AI/blob/main/model_plots/mlp_training_curves.png" alt="Fig. Training vs Validation Loss Curves" width="1020"></a> 
  <br> 
   <br>
</h2>

<p>These plots track: Ltrain(t),Lval(t) train (t),L val (t) over epochs. A monotonic decrease in training loss indicates effective gradient-based optimization. A validation loss curve that stabilizes or slightly increases signals: onset of overfitting, model memorization vs generalization boundary, If curves converge: The model is well-regularized Optimization landscape is stable, If they diverge:High variance model

</p>
