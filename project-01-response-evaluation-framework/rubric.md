# Evaluation Rubric (Version 2)

## 1. Evaluation criteria

### Accuracy
- 1: Contains two or more factual errors, or the main explanation is incorrect.
- 3: The main explanation is correct but contains one factual error or an important missing detail.
- 5: All factual claims are correct and the answer addresses the question.
- 2 and 4: Fall between the neighbouring descriptions.

### Instruction Following
- 1: Misses two or more explicit instructions.
- 3: Misses exactly one explicit instruction.
- 5: Follows every explicit instruction.
- 2 and 4: Fall between the neighbouring descriptions.

### Clarity
- 1: Has three or more repeated sentences or three or more unexplained technical terms.
- 3: Has one or two repeated sentences or one or two unexplained technical terms.
- 5: Has zero repeated sentences and zero unexplained technical terms.
- 2 and 4: Fall between the neighbouring descriptions.
- Definition of "technical term":  A word is technical when it is mostly used in a particular subject or profession and an ordinary 12-year-old might not understand it without someone explaining what it means.
- How to combine the two counts: Take the bigger number, not add them together, because we should avoid counting the same clarity problem twice.

## 2. Rules

**Priority rule:** Accuracy comes first. Any response scoring 2 or below cannot rank above a response scoring 4 or 5 in Accuracy.

**Hard limit rule:** If a response breaks a strict word or sentence limit, its Instruction Following score cannot exceed 2.

**Tie-break rule:** If two responses have the same Accuracy score, the response with the higher total score across all three criteria ranks first.

## 3. Instruction checklist (written before scoring)

Prompt: "Explain in two sentences why the sky is blue."

1. Explain why the sky is blue.
2. Use exactly two sentences.

I check these separately before assigning an Instruction Following score.

## 4. Scoring

### Response A
- Accuracy: 1/5. It incorrectly claims that the sky gets its blue colour from the ocean.
- Instruction Following: 5/5. It answers the question in exactly two sentences.
- Clarity: 3/5. It is easy to understand, but the second sentence repeats the first idea without adding useful information.

### Response B
- Accuracy: 5/5. It correctly explains how air molecules scatter blue light more than red light.
- Instruction Following: 5/5. It answers the question in exactly two sentences and follows the requested format.
- Clarity: 5/5. It explains the science in simple language without unnecessary details.

### Response C
- Accuracy: 5/5. Its scientific explanation is correct.
- Instruction Following: 2/5. It uses five sentences instead of the required two, breaking the strict length limit.
- Clarity: 1/5. It has 0 repeated sentences but 3 unexplained technical terms (short-wavelength, long-wavelength and Rayleigh scattering), so the bigger count is 3.
- Re-count using my definition of "technical term": I counted short-wavelength, long-wavelength and Rayleigh scattering as three separate terms, because a 12-year-old may not understand them without an explanation. With 0 repeated sentences and 3 unexplained terms, the bigger number is 3, which gives a Clarity score of 1/5.

## 5. Score table

| Response | Accuracy | Instruction | Clarity | Total |
|----------|----------|-------------|---------|-------|
| A        | 1        | 5           | 3       | 9     |
| B        | 5        | 5           | 5       | 15    |
| C        | 5        | 2           | 1       | 8     |

## 6. Final ranking

1. B. Highest overall score and follows all instructions.
2. C. Scientifically correct but loses points for breaking the sentence limit and using unexplained technical terms.
3. A. Follows the format but gives incorrect scientific information.

Note: A has a higher total than C (9 against 8), but the priority rule ranks C above A, because A's Accuracy score is 1.

## 7. What changed from version 1 and why

- Response A's Clarity changed from 4 to 3 because its second sentence repeats the first without adding meaning.
- Response C's Instruction Following is 2 because the hard limit rule caps the score.
- Response B is unchanged because it meets all three criteria.

## 8. Takeaway

Good AI evaluation requires consistent scoring, clear evidence and rules that prevent the same mistake from being penalised under multiple criteria.

## Known limitations
- Response C is correct and well ordered, but it scores 1/5 for Clarity because it uses three technical terms. This may be too harsh, because it explains short-wavelength and long-wavelength by example. A later version of this rubric could count a term as explained if the response gives an example.