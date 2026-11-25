# Quality Assessment: Agreement Between Two Annotators

## Setup
- Task: label 20 synthetic customer messages as Complaint, Question, Praise or Other.
- Guidelines: annotation-guidelines.md (version 1).
- Annotator 1: me. 10 minutes. 9 rows had a note.
- Annotator 2: a friend. 20 minutes. They wrote a note on every row.
- Both of us labelled alone, using only the guidelines and the list of messages. Annotator 2 did not see my labels, and I did not see theirs until both sets were finished.

## Agreement table
| # | Annotator 1 | Annotator 2 | Match |
|---|---|---|---|
| 1 | Complaint | Complaint | Yes |
| 2 | Question | Question | Yes |
| 3 | Praise | Praise | Yes |
| 4 | Other | Other | Yes |
| 5 | Complaint | Complaint | Yes |
| 6 | Complaint | Complaint | Yes |
| 7 | Other | Other | Yes |
| 8 | Question | Question | Yes |
| 9 | Complaint | Complaint | Yes |
| 10 | Praise | Praise | Yes |
| 11 | Other | Other | Yes |
| 12 | Question | Question | Yes |
| 13 | Complaint | Complaint | Yes |
| 14 | Complaint | Complaint | Yes |
| 15 | Question | Question | Yes |
| 16 | Praise | Praise | Yes |
| 17 | Other | Other | Yes |
| 18 | Praise | Praise | Yes |
| 19 | Complaint | Complaint | Yes |
| 20 | Complaint | Complaint | Yes |

## Result
Agreement: 20 of 20 messages (100%).

Label counts (the same for both annotators): Complaint 8, Question 4, Praise 4, Other 4.

## What this number does and does not show
- It shows that two people, using only the written rules, reached the same labels on these 20 messages. The guidelines were consistent on this set.
- It does not show that the labels are correct. Two people can agree on a label that is wrong.
- It does not show that the guidelines would work on real customer messages. I chose the 20 messages to test the rules, and the guidelines contain examples close to several of them. Easy agreement was likely.
- With 20 messages and one second annotator, the sample is too small for a firm conclusion.

## Where the guidelines may be weak
1. **Message 18** ("The rider was rude, but my parcel arrived on time and in perfect condition."). Both annotators used rule 3 (label the part that comes last) and chose Praise. But a shop would want to act on a rude rider, and rule 3 hides that problem because the praise comes last. We agreed, but the label may be wrong for the business.
2. **Message 14** ("Thanks, but I am still waiting for my refund."). We gave the same label for different reasons. I used rule 4 (sarcasm), and Annotator 2 cited a reported problem. The guidelines do not say how to treat a polite opening followed by a problem.
3. **Notes.** I wrote notes on 9 of 20 rows, and Annotator 2 wrote a note on all 20. Rules 2, 3, 4 and 5 were each cited at least twice, so the hard-case rules were used often.

## Proposed changes for version 2 (not tested)
- Change rule 3: if a message reports a problem the shop must act on, label it Complaint, whatever order the parts come in. This would change the label for message 18 to Complaint.
- Add a rule: a polite opening such as "Thanks, but..." followed by an unresolved problem is a Complaint.

I have not applied these changes. Version 2 needs a new round with new messages and a second annotator before I can say whether it improves agreement. I did not change any labels from this round to make the numbers look better.

## Limitations
- The 20 messages and the first draft of the guidelines were drafted with AI help. I applied the guidelines and labelled the messages myself.
- All messages are synthetic. No real customer data was used.
- One second annotator, one round, 20 messages, so the agreement score is only a first signal.