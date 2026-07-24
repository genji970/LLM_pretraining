# LLM Pretraining

Repository for recording progress on implementing LLM pretraining from scratch.

## In Progress

### 1. Scaling

- **Paper 1-1: Training Compute-Optimal Large Language Models**
    - The number of training tokens and model size should be scaled together.
    - Note: The paper used Huber loss for fitting the scaling-law model.

### 2. Data

- **Paper 2-1: FineWeb**
    - **2-1-1. Related resources**
        - [FineWeb blog post](https://huggingface.co/spaces/HuggingFaceFW/blogpost-fineweb-v1)
    - **2-1-2. Large-scale data processing library**
        - [Hugging Face DataTrove](https://github.com/huggingface/datatrove)
    - **2-1-3. Collecting high-quality data**
        - **Perplexity-based evaluation**
            - Low perplexity does not always lead to better downstream performance.
            - Medical, mathematical, and other specialized data may have distributions different from Wikipedia.
            - Even when such data has high perplexity under a Wikipedia-trained model, it may still be useful for domain-specific tasks.
        - **Small-model evaluation**
            - Train small models on representative subsets of candidate datasets.
            - Evaluate the models on multiple downstream benchmarks.
            - Using diverse benchmarks helps prevent overfitting the data-selection process to a single benchmark.
   
   
