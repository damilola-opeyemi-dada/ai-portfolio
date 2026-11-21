# Project 2: AI Hallucination Detection

## Objectives
- Break AI responses into single claims and check each claim against a source.
- Label every claim Supported, Contradicted or Cannot verify, and record the source or what I searched.
- Show the difference between a claim that is wrong and a claim that cannot be confirmed.

## Problem statement
AI responses can mix true statements with false ones in the same confident tone. Judging a whole response by how convincing it sounds misses the false claim. Checking claim by claim makes the problem visible.

## Method
1. I split each response into single claims, one fact per row.
2. I looked each claim up in a source and recorded the source name, what it says, the web address and the date I checked.
3. I labelled each claim:
   - Supported: a source confirms it.
   - Contradicted: a source says the opposite.
   - Cannot verify: I could not find evidence either way. I wrote down what I searched.
4. I counted hallucinated claims as Contradicted plus Cannot verify.

## Files in this project
- claim-check-01.md: 4 synthetic responses (Eiffel Tower, Chinua Achebe, boiling water, Mount Kilimanjaro).
- claim-check-02.md: 3 synthetic responses (Nigeria facts with an invented study, the Great Wall, Python).

## Results
| Check | Response | Claims | Hallucinated |
|---|---|---|---|
| 1 | Eiffel Tower | 4 | 1 |
| 1 | Chinua Achebe | 4 | 1 |
| 1 | Boiling water | 2 | 1 |
| 1 | Mount Kilimanjaro | 3 | 0 |
| 2 | Nigeria and an invented study | 5 | 3 |
| 2 | The Great Wall | 2 | 1 |
| 2 | Python | 3 | 0 |

## Findings
- False claims were written in the same confident tone as true ones. I could not spot them by style.
- Some false claims were near misses, such as a Nobel Prize given to the wrong Nigerian writer.
- A precise statistic from an invented study looked credible, but I could not verify the study or the researcher.
- Contradicted and Cannot verify are different findings. A contradicted claim has evidence against it. An unverifiable claim has not been established.
- Three of the five claims in one response depended on the same unverifiable study, so the count of 3 may overstate how many separate problems there are.

## Honest status
- All responses are synthetic examples written for practice. This is not client work.
- The study and researcher in claim check 2 were invented for the exercise.
- This project is still in progress.

## Limitations
- I checked 7 short responses, so these results show the method, not how often a real AI hallucinates.
- Most claims were checked against one source each.
- I labelled unverifiable claims Cannot verify based on my own searches, and a different searcher might find evidence that I did not.