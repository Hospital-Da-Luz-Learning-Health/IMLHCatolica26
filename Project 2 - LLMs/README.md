# Project 2 - Aplications of LLMS to Clinical Notes

**Title:** Prompt Engineering with Large Language Models for Clinical Text Analysis

**Due Date:** July 17 (final presentation)

**Deliverables:** 
1. Notebook
2. Presentation (Combined with Project 1 presentation)




## Overview
In this project, you will apply the skills learned throughout the course to work hands-on with clinical text using Large Language Models (LLMs). The focus is on prompt engineering to explore how LLMs summarize clinical notes, extract key entities, and support clinical understanding.

You will modify prompts, compare results, and reflect on the utility and limitations of generative AI in a healthcare setting.

## Objectives
- Apply large language models (LLMs) to analyze real-world clinical text.
- Develop effective prompts for summarization, entity extraction, and question answering.
- Critically assess LLM-generated outputs for clinical relevance, accuracy, and completeness.

## Learning Goals
By completing this project, you will:
- Understand how LLMs can process and structure unstructured clinical data.
- Gain practical experience with Hugging Face models and prompt design.
- Learn to iteratively refine prompts and evaluate AI outputs.
- Identify the strengths and limitations of LLMs for clinical natural language processing (NLP).


## Getting Started
1. Open the Notebook

    - Start from the provided Google Colab notebook:
👉[notebook](https://colab.research.google.com/github/Hospital-Da-Luz-Learning-Health/MLCatolica25/blob/main/Project%202%20-%20LLMs/MLCat_Project2.ipynb).

2. Load an LLM

    - Use Hugging Face’s transformers library to load a suitable LLM. We will use the MedGemma LLM.

3. Review the Sample Clinical Note

    Familiarize yourself with the included de-identified sample note.
    - You may optionally use your own de-identified or synthetic note.

4. Experiment with Prompts
    
    Edit only the prompt text (not the model code) to:

    - Summarize the note
    - Answer specific clinical questions
    - Extract relevant entities (e.g., diagnosis, medications, procedures)

5. Compare Outputs
    
    For each task try at least two different prompts.
    - Compare how changes in instruction affect model performance.

6. Reflect on Results

    Consider output quality: Is the summary clinically coherent? Are entities accurate?

    - Leave your observations and insights in a markdown cell of the notebook.

## Best Practices for Prompting
- Be explicit: Specify the format, audience (e.g., patient, clinician), or required detail.
- Provide context: Include necessary clinical background in the prompt.
- Use examples: Demonstrate what kind of output is expected.
- Iterate: Tweak and improve prompts based on the output you receive.
- Cross-check: Compare responses across different models if time permits.

## Reflection Questions (Include in Notebook or Slides)
- How did different prompts affect the structure and accuracy of outputs?
- Which model(s) performed best for each task?
- What challenges did you face in extracting structured information from unstructured text?
- How could these techniques be improved for real clinical workflows?