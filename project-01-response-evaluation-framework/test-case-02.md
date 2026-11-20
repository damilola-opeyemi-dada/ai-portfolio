# Test Case 2 (synthetic example, written for practice)

Prompt: "In one sentence, say who wrote Romeo and Juliet and in which century."

## Responses being scored (synthetic examples written for practice)

Response A: William Shakespeare wrote Romeo and Juliet in the 16th century.

Response B: Christopher Marlowe wrote Romeo and Juliet in the 16th century.

Response C: William Shakespeare wrote Romeo and Juliet in the 18th century. He was also born in Stratford-upon-Avon.

## Instruction checklist
1. Give an author of Romeo and Juliet.
2. Give a century.
3. Answer in one sentence.

## Scoring

### Response A
- Accuracy: 5/5. Evidence: It has 0 factual errors. Shakespeare wrote Romeo and Juliet, generally dated to the late 16th century.
- Instruction Following: 5/5. Evidence: It meets 3 of 3 instructions: it gives an author, gives a century and uses one sentence.
- Clarity: 5/5. Evidence: It has 1 sentence, 0 repeated sentences and 0 unexplained technical terms.
- Total: 15/15

### Response B
- Accuracy: 2/5. Evidence: It has 1 factual error. Christopher Marlowe did not write the play; William Shakespeare did. The century is correct. The author is the main fact the prompt asks for, so this falls between my anchor for 1 (the main explanation is incorrect) and my anchor for 3 (the main explanation is correct but has one error).
- Instruction Following: 5/5. Evidence: It meets 3 of 3 instructions: it gives an author, gives a century and uses one sentence. The wrong author is scored under Accuracy only.
- Clarity: 5/5. Evidence: It has 1 sentence, 0 repeated sentences and 0 unexplained technical terms.
- Total: 12/15

### Response C
- Accuracy: 3/5. Evidence: It has 1 factual error. Shakespeare is the correct author and Stratford-upon-Avon is his birthplace, but the play was written in the 16th century, not the 18th.
- Instruction Following: 2/5. Evidence: It misses 1 of 3 instructions (it uses 2 sentences against a limit of 1), which would score 3, but the hard limit rule caps the score at 2.
- Clarity: 5/5. Evidence: It has 2 sentences, 0 repeated sentences and 0 unexplained technical terms.
- Total: 10/15

## Ranking
1. A (15/15): It is accurate and follows every instruction.
2. B (12/15): It follows the format, but it names the wrong author (Marlowe).
3. C (10/15): It names the right author, but it gives the wrong century and uses two sentences instead of one.

Note: My rubric has no rule for ranking an Accuracy of 2 against an Accuracy of 3, so I ranked B above C by total score.

## Rules I used
- Priority rule: I compared A (Accuracy 5) with B (Accuracy 2). The rule says B cannot rank above A, and it did not. It did not change the order, because A also had the higher total. It did not apply to B against C, because C's Accuracy is 3.
- Hard limit rule: Applied to C. It uses 2 sentences against a limit of 1, so its Instruction Following score is capped at 2.
- Tie-break rule: Not used, because no two responses have the same Accuracy score.

## Gaps I found in my rubric
- My rubric does not say which fact counts as the "main" one when a prompt asks for two facts. I scored the wrong author (Response B) as 2 and the wrong century (Response C) as 3, but both responses have exactly one wrong fact out of two.
- My rubric has no rule for ranking an Accuracy of 2 against an Accuracy of 3. I ranked B above C by total score, but both are partly wrong, so this ranking is not strongly supported.
- My Clarity criterion gave 5/5 to all three responses, so it did not help compare them. This is the same weakness I found in test case 1.