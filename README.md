# AI Portfolio

I am Damilola. I am building practical skills in AI training and evaluation: judging AI responses, finding errors, and testing how reliable and safe AI systems are.

## About this repo
This repository holds five projects from a first round of work. Projects 2 and 4 use synthetic examples I wrote for practice. Projects 3 and 5 use real answers from free chatbots. None of it is client work. Each project has its own README with an honest status and a list of limitations.

## Projects
1. [Response Evaluation Framework](project-01-response-evaluation-framework): a scoring rubric (version 3) with three test cases, and a record of where the rubric failed.
2. [Hallucination Detection](project-02-hallucination-detection): seven short AI responses split into claims and checked against named sources, with Supported, Contradicted and Cannot verify labels.
3. [Model Comparison and Benchmarking](project-03-model-comparison-benchmarking): Gemini and DeepSeek compared on five prompts with my rubric. Result: 88 and 91 out of 100, too close to call.
4. [Data Annotation and Quality](project-04-data-annotation-quality): annotation guidelines, 20 synthetic messages, and an agreement check between two annotators. Result: 20 of 20 matched, with the limits of that number explained.
5. [Safety and Red Teaming](project-05-safety-red-teaming): ten low-severity test prompts run on two models. The models failed on different prompts, so neither was clearly safer.

## What I learned
- A rubric needs written rules and evidence for every score, and testing shows where it fails.
- A claim I cannot verify is not the same as a claim that is false.
- A small test can show a method but cannot decide which model is better.
- High agreement between two annotators shows consistency, not correctness.
- A safe model must help with harmless requests as well as decline harmful ones.

## Status
First round complete. Next: Python-based evaluation exercises and a second round that fixes the weaknesses my own tests found.