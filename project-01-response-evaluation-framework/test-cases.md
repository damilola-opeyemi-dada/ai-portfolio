# Test Case 1 (synthetic example, written for practice)

Prompt: "Name three planets in our solar system. Use a numbered list, one word per item."

## Responses being scored (synthetic examples written for practice)

Response A:
1. Mars
2. Venus
3. Jupiter

Response B:
1. Mars
2. Sirius
3. Saturn

Response C:
Here are three planets: Mars, Venus and Jupiter. Each one orbits the Sun.

## Instruction checklist
1. Name planets from our solar system.
2. Name exactly three.
3. Use a numbered list.
4. Use one word per item.

## Scoring

### Response A
- Accuracy: 5/5. Evidence: All three names are real planets in our solar system.
- Instruction Following: 5/5. Evidence: It meets 4 of 4 instructions: it names planets, lists exactly three, uses a numbered list and uses one word per item.
- Clarity: 5/5. Evidence: There are zero repeated sentences and zero unexplained technical terms, and the list is easy to understand.
- Total: 15/15.

### Response B
- Accuracy: 3/5. Evidence: Mars and Saturn are planets, but Sirius is a star, not a planet.
- Instruction Following: 5/5. Evidence: It meets 4 of 4 instructions: it names three items, uses a numbered list and uses one word per item. Naming Sirius is scored under Accuracy only, so the same flaw is not penalised twice.
- Clarity: 5/5. Evidence: There are zero repeated sentences and zero unexplained technical terms, so the list is easy to read.
- Total: 13/15.

### Response C
- Accuracy: 5/5. Evidence: All three names are real planets in our solar system.
- Instruction Following: 1/5. Evidence: It misses 2 of 4 instructions (no numbered list, and no items to hold one word each).
- Clarity: 5/5. Evidence: It has 2 sentences, 0 repeated sentences and 0 unexplained technical terms.
- Total: 11/15.

## Ranking
1. A (15/15): It is accurate and follows every instruction.
2. B (13/15): It follows the format, but it names Sirius, which is a star and not a planet.
3. C (11/15): It is accurate, but it does not use a numbered list.

Note: I ranked these by total score, because my rubric has no rule for an Accuracy of 3 against an Accuracy of 5. This ranking feels questionable, because B contains a factual error while C is fully accurate. This is a gap in my rubric.

## Gaps I found in my rubric
- My rubric has no rule for ranking a response with Accuracy 3 against one with Accuracy 5. I ranked by total score instead, but this may not be fair.
- My rubric does not say what to do when an instruction cannot be checked, for example "one word per item" when the response has no list.
- My rubric does not say whether naming a wrong item (Sirius) is only an Accuracy problem or also an Instruction Following problem. I scored it under Accuracy only.