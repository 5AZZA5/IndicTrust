# IndicTrust

**An experimental toolkit for evaluating language-specific reliability failures in AI systems.**

## Overview

AI systems may respond differently to semantically equivalent prompts written in different languages, scripts, or combinations of languages.

IndicTrust investigates whether these differences produce meaningful reliability failures, initially focusing on:

- English
- Romanized Hindi
- Hindi-English code-switching

The goal is to develop reproducible evaluations that detect, classify, and track language-specific failures in AI applications.

## Research Question

Can a controlled evaluation pipeline reliably identify meaningful differences in AI responses to semantically equivalent English, Romanized Hindi, and Hindi-English prompts?

## Initial Objectives

1. Build a human-reviewed multilingual test dataset.
2. Evaluate AI responses using task-appropriate criteria.
3. Record reproducible experiments.
4. Investigate and classify language-specific failures.
5. Convert verified failures into regression tests.
6. Compare results across model and prompt versions.

## Technology

- Python
- Git and GitHub
- pytest
- pandas
- FastAPI
- Streamlit

## Current Status

**Stage:** Initial setup and research validation.

No claims about detection accuracy, uniqueness, or competitive advantage have been established. These will require experiments and comparisons with existing tools.

## Planned Development

1. Validate the research hypothesis.
2. Investigate existing evaluation tools and benchmarks.
3. Create the initial test dataset.
4. Implement the evaluation engine.
5. Develop and validate failure diagnostics.
6. Add regression testing and experiment tracking.
7. Build an interface and evaluate practical usefulness.

## License

No license has been selected yet.