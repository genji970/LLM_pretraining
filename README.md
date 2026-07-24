# LLM_pretraining
repo for llm pretrainig. For record progress

In progress


1)scaling
   paper 1-1)
       training compute optimal large language models : number of tokens and model size should go together. Notes :used Huber loss.

2) Data
   paper 2-1) FineWeb
         2-1-1) related site : https://huggingface.co/spaces/HuggingFaceFW/blogpost-fineweb-v1?utm_source=chatgpt.com
         2-1-2) data process library for huge data : https://github.com/huggingface/datatrove
         2-1-3) For collecting good quality data
            2-1-3-1) Not low perplexit always good performance.
               2-1-3-1-1) For medical, math, etc there data has different distribution to wikipedia(clean data). But they are helpful to such domains.
            2-1-3-2) For each dataset, choose small and train model with them.
               2-1-3-2-1) require test on multi benchmark for preveting overfitting.

   
   
