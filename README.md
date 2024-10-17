## Multi-Stage Retrieval System for HotpotQA Dataset
This project demonstrates a multi-stage retrieval system designed for the HotpotQA dataset. It involves embedding models to retrieve relevant text chunks and ranking models to rerank the passages for optimal performance. The project evaluates the retrieval system using metrics like Recall@K.

## Features
Dataset: Utilizes the lucadiliello/hotpotqa dataset for multi-hop question answering.

Preprocessing: Chunking of large context passages into smaller parts.

Models: Supports small and large versions of embedding and ranking models from Hugging Face and NVIDIA.

Evaluation: Computes Recall@K to assess retrieval performance.
