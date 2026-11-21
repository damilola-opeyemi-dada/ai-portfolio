# Claim Check 2 (synthetic examples, written for practice)

## Method
I split each response into single claims, checked each claim against reliable sources, and labelled it Supported, Contradicted or Cannot verify. I did not label anything Supported from memory alone. A claim I could not find evidence for is labelled Cannot verify, not Contradicted, and I wrote down what I searched.

## Response 1
"Nigeria's capital moved from Lagos to Abuja in 1991. Nigeria gained independence from Britain in 1960. A 2019 study by Dr. Helena Okafor-Marsh of the University of Lagos found that 73% of Nigerian students prefer learning in the evening."

| Claim | Label | Source and date checked, or what I searched |
|---|---|---|
| 1. Nigeria's capital moved from Lagos to Abuja in 1991. | Supported | Library of Congress, Country Profile: Nigeria (2008). Confirms that Abuja became the capital on 12 December 1991. Checked 21 November 2026. |
| 2. Nigeria gained independence from Britain in 1960. | Supported | Library of Congress, Country Profile: Nigeria (2008). Confirms independence on 1 October 1960. Checked 21 November 2026. |
| 3. A study on evening learning preferences was conducted in 2019 by Dr. Helena Okafor-Marsh. | Cannot verify | Searched the exact name "Dr. Helena Okafor-Marsh" and "2019 study". No reliable matching publication or research record was found. Checked 21 November 2026. |
| 4. Dr. Helena Okafor-Marsh was affiliated with the University of Lagos. | Cannot verify | Searched "Helena Okafor-Marsh University of Lagos" and checked for matching university research records. No reliable confirmation was found. Checked 21 November 2026. |
| 5. The study found that 73% of Nigerian students prefer learning in the evening. | Cannot verify | Searched "73% of Nigerian students prefer learning in the evening" and "University of Lagos 2019 evening learning study". No reliable source confirming this statistic was found. Checked 21 November 2026. |

Hallucinated claims: 3 of 5

## Response 2
"The Great Wall of China is visible to the naked eye from the Moon. Parts of it date back more than 2,000 years."

| Claim | Label | Source and date checked, or what I searched |
|---|---|---|
| 1. The Great Wall of China is visible to the naked eye from the Moon. | Contradicted | NASA – China's Wall Less Great in View from Space. NASA explains that the Great Wall is not visible from the Moon. Checked 21 November 2026. |
| 2. Parts of the Great Wall of China date back more than 2,000 years. | Supported | 

Academy of Chinese Studies – The Great Wall. Explains that the earliest sections date back to around the seventh century BCE. Checked 21 November 2026. |

Hallucinated claims: 1 of 2

## Response 3
"Python was created by Guido van Rossum and first released in 1991. It is named after the Monty Python comedy group."

| Claim | Label | Source and date checked, or what I searched |
|---|---|---|
| 1. Python was created by Guido van Rossum. | Supported | Official Python documentation – History and License. Identifies Guido van Rossum as Python's creator and principal author. Checked 21 November 2026. |
| 2. Python was first released in 1991. | Supported | Official Python documentation – History and License. Its release history identifies the first releases as beginning in 1991. Checked 21 November 2026. |
| 3. Python is named after the Monty Python comedy group. | Supported | Official Python documentation – General Python FAQ. Explains that Guido van Rossum chose the name after reading scripts from Monty Python's Flying Circus. Checked 21 November 2026. |

Hallucinated claims: 0 of 3

## What I noticed
This exercise helped me understand that not every claim that lacks evidence should automatically be labelled false.

Response 1 was particularly interesting because its first two statements were correct, but the final section introduced a researcher, university affiliation and statistical finding that I could not independently verify. I did not label these claims Contradicted because I found no reliable evidence proving the opposite.

Response 2 demonstrated how a familiar statement can still be wrong. The Great Wall is not visible to the naked eye from the Moon, even though some of its sections are more than 2,000 years old.

Response 3 was accurate, and the official Python documentation supported all three claims.

I also noticed that specific names, percentages and dates can make an AI response sound more credible than it actually is. A precise statistic such as 73% may look convincing, but it still needs a traceable source.

Overall, I learned that Contradicted and Cannot verify are different findings. A contradicted claim has evidence against it, while an unverifiable claim has not been sufficiently established. Both deserve attention during evaluation, but they should not be treated as the same thing.