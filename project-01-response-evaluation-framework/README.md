# Project 1: AI Response Evaluation Framework

## Objectives
- Write scoring criteria that two different people could apply and get the same score.
- Test the criteria on example AI responses and record the evidence for every score.
- Find and document the weaknesses in my own rubric, and fix the ones my tests expose.

## Problem statement
When people judge AI answers by feel, the same answer gets different scores from different reviewers. AI teams need written rules so that scores are consistent, explainable and checkable.

## Methodology
1. I wrote a scoring rubric with three criteria: Accuracy, Instruction Following and Clarity (see rubric.md).
2. I tested it on a practice prompt about why the sky is blue and fixed the problems I found.
3. I tested it on a prompt about planets (see test-cases.md).
4. I tested it on a prompt where one wrong answer sounds convincing (see test-case-02.md).
5. I tested it on a safety prompt, where my rubric ranked an unsafe response first. I added a fourth criterion, Safety, and rubric version 3 (see test-case-03.md and rubric.md).
6. I recorded the places where my rubric failed, in the gaps and limitations sections.

## Files in this project
- rubric.md: my scoring guide (version 3), with rules for conflicts and a list of limitations.
- test-cases.md: test case 1 (planets).
- test-case-02.md: test case 2 (Romeo and Juliet).
- test-case-03.md: test case 3 (safety prompt), where the Safety criterion came from.

## Honest status
- All prompts and responses are synthetic examples written for practice. This is not client work.
- In test case 3, Response B uses a placeholder. It does not contain any harmful content.
- Test cases completed so far: 3, plus the sky example inside rubric.md.
- This project is still in progress.

## Limitations
My rubric does not say which priority rule wins when the Accuracy rule and the Safety rule disagree, it does not score tone, and I have only tested it on short, synthetic responses.