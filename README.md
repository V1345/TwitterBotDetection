Advanced Social Media Bot Detection System

This repository contains the implementation of an advanced social media bot detection system using Large Language Models (LLMs) and a mixture-of-experts framework. The system leverages multi-modal data, including user metadata, tweet content, and graph-based relations, to classify accounts as bots or humans. It uses cutting-edge machine learning techniques, including QLoRA fine-tuning and Relational Graph Convolutional Networks (RGCNs).

Project Overview

The project is designed to detect bots on Twitter with high precision and recall, utilizing the Twibot-22 dataset. The detection process involves:
	•	Multi-modal data processing (user metadata, tweet content, and graph-based relationships).
	•	Fine-tuned large language models (e.g., LLaMA 3.1) for enhanced classification accuracy.
	•	Scalable preprocessing of over 88 million tweets using Apache Spark.

Key Features
	•	Mixture-of-Experts Framework: Specialized models for metadata, tweet content, and graph-based features.
	•	State-of-the-Art Models: Use of LLaMA 3.1 and QLoRA fine-tuning for efficiency and scalability.
	•	Multi-Modal Data: Integration of textual, relational, and metadata information for improved detection performance.
