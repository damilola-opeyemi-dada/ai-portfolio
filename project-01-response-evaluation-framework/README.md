# Project 1: AI Response Evaluation Framework

## Objectives
- Write scoring criteria that two different people could apply and get the same score.
- Test the criteria on example AI responses and record the evidence for every score.
- Find and document the weaknesses in my own rubric.

## Problem statement
When people judge AI answers by feel, the same answer gets different scores from different reviewers. AI teams need written rules so that scores are consistent, explainable and checkable.

## Methodology
1. I wrote a scoring rubric with three criteria: Accuracy, Instruction Following and Clarity (see rubric.md).
2. I tested it on a practice prompt about why the sky is blue and fixed the problems I found.
3. I tested it again on a new prompt about planets (see test-cases.md).
4. I tested it on a third prompt where one wrong answer sounds convincing (see test-case-02.md).
5. I recorded the places where my rubric failed, in the Gaps section of each test case.

## Files in this project
- rubric.md: my scoring guide, with rules for conflicts and a list of limitations.
- test-cases.md: test case 1 (planets), with the responses, scores, evidence, ranking and gaps.
- test-case-02.md: test case 2 (Romeo and Juliet), with the responses, scores, evidence, rules used, ranking and gaps.

## Honest status
- All prompts and responses are synthetic examples written for practice. This is not client work.
- Test cases completed so far: 2 full test cases (planets, and Romeo and Juliet), plus the sky example inside rubric.md.
- This project is still in progress.

## Limitations
My rubric has no rule for ranking an Accuracy of 2 or 3 against each other or against a higher score, my Clarity criterion does not separate short answers, and I have only tested it on three short, factual prompts.