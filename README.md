
# AI-Driven Plagiarism Detection Agent

This project is an AI-powered plagiarism detection agent developed using IBM Watsonx.ai and Granite foundation models. It helps identify paraphrased or AI-generated content in student assignments to maintain academic integrity.

## Overview

Academic institutions face growing challenges in detecting sophisticated forms of plagiarism. This agent goes beyond keyword or string-matching by using large language models to compare content contextually. It can detect rewritten, restructured, or AI-generated submissions by learning from previous assignments and instructor feedback.

## Key Features

- Detects AI-generated and paraphrased content
- Uses instructor-specific grading patterns for context-aware detection
- Provides similarity scores and rewrite suggestions
- Built with Granite-3-3-8b-instruct model on IBM Watsonx.ai
- Deployable within IBM Cloud with Watson Machine Learning and Object Storage

## Technologies

- IBM Watsonx.ai Studio
- IBM Granite Foundation Model
- NLP and Semantic Similarity Detection
- IBM Cloud Object Storage

## Usage

Deploy the agent in IBM Watsonx.ai, upload historical data, and interact via prompts like:
- "Does this content match previous submissions?"
- "Is this paragraph AI-generated?"

## License

This project is licensed under the MIT License.
