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
- Definition of "technical term": WRITE YOUR OWN DEFINITION HERE (FIX 1)
- How to combine the two counts: WRITE YOUR OWN RULE HERE (FIX 2)

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
- Clarity: 3/5. It uses technical terms such as Rayleigh scattering and short-wavelength without explaining their meanings to an ordinary reader.
- Re-count using my definition of "technical term" (FIX 3): LIST THE TERMS YOU COUNTED AND GIVE THE FINAL CLARITY SCORE HERE

## 5. Score table

| Response | Accuracy | Instruction | Clarity | Total |
|----------|----------|-------------|---------|-------|
| A        | 1        | 5           | 3       | 9     |
| B        | 5        | 5           | 5       | 15    |
| C        | 5        | 2           | 3       | 10    |

## 6. Final ranking

1. B. Highest overall score and follows all instructions.
2. C. Scientifically correct but loses points for breaking the sentence limit and using unexplained technical terms.
3. A. Follows the format but gives incorrect scientific information.

## 7. What changed from version 1 and why

- Response A's Clarity changed from 4 to 3 because its second sentence repeats the first without adding meaning.
- Response C's Instruction Following is 2 because the hard limit rule caps the score.
- Response B is unchanged because it meets all three criteria.

## 8. Takeaway

Good AI evaluation requires consistent scoring, clear evidence and rules that prevent the same mistake from being penalised under multiple criteria.