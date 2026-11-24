# Project 4: AI Data Annotation and Quality Assessment

## Objectives
- Write annotation guidelines that two people can apply in the same way.
- Label a small dataset, then measure how often two annotators agree.
- Find where the guidelines are weak, and report the limits of the result honestly.

## Problem statement
AI systems learn from labelled data. If annotators label the same item differently, the training data is inconsistent and the model learns from noise. Teams need written guidelines and a way to measure whether people follow them in the same way.

## Methodology
1. I chose a labelling task: sort short customer messages into Complaint, Question, Praise or Other.
2. I wrote annotation guidelines (version 1) with a definition and examples for each label, and six rules for hard cases (see annotation-guidelines.md).
3. I prepared 20 synthetic messages, including some designed to be hard: sarcasm, mixed feelings, and a problem together with a question (see messages.md).
4. I labelled all 20 alone, using only the guidelines (see labels-annotator-1.md).
5. A friend labelled the same 20 alone, without seeing my labels (see labels-annotator-2.md).
6. I compared the two sets row by row, calculated the agreement, and looked at the cases where the guidelines may be weak (see quality-report.md).

## Evaluation criteria
- Agreement: the number of messages with the same label from both annotators, divided by 20.
- Guideline weaknesses: messages where the rules conflict, or where the two annotators used different reasons for the same label.

## Results
- Agreement: 20 of 20 messages (100%).
- Label counts, the same for both annotators: Complaint 8, Question 4, Praise 4, Other 4.
- Time taken: 10 minutes for me and 20 minutes for the second annotator.

## Findings
- On these 20 messages, the guidelines were consistent. Both annotators used the hard-case rules often, and cited rules 2, 3, 4 and 5.
- 100% agreement does not show that the labels are correct, or that the guidelines would work on real messages. I wrote the test set, and several messages were close to the examples in the guidelines.
- Rules 2 and 3 can conflict. For message 18 ("The rider was rude, but my parcel arrived on time and in perfect condition"), we both chose Praise by rule 3, but a shop would probably want to act on the rude rider.
- For message 14 ("Thanks, but I am still waiting for my refund"), we gave the same label for different reasons, which shows the guidelines do not clearly cover a polite opening followed by a problem.

## Recommendations
- Change rule 3 so that a reported problem the shop must act on is labelled Complaint, whatever the order of the message.
- Add a rule for a polite opening followed by an unresolved problem.
- Test version 2 on new messages with at least three annotators, and compare the agreement with this round. I have not done this yet.

## Files in this project
- annotation-guidelines.md: the labels, examples and rules (version 1).
- messages.md: the 20 synthetic messages.
- labels-annotator-1.md: my labels, with notes.
- labels-annotator-2.md: my friend's labels, with notes.
- quality-report.md: the agreement table, what the number does and does not show, and proposed changes.

## Honest status
- All messages are synthetic examples written for practice. No real customer data was used. This is not client work.
- The first draft of the guidelines and the 20 messages were drafted with AI help. I applied the guidelines and labelled the messages myself.
- I have not tested the proposed changes. This project is a first round and is still in progress.

## Limitations
- 20 messages, one second annotator, one round.
- I wrote the messages, so the test is easier than real data.
- I did not use a formal agreement measure such as Cohen's kappa. I counted matching labels only.