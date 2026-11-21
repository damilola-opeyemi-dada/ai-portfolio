# Claim Check 2 (synthetic examples, written for practice)

## Method
I split each response into single claims, checked each claim against reliable sources, and labelled it Supported, Contradicted or Cannot verify. I did not label anything Supported from memory alone. A claim I could not find evidence for is labelled Cannot verify, not Contradicted, and I wrote down what I searched.

## Response 1
"Nigeria's capital moved from Lagos to Abuja in 1991. Nigeria gained independence from Britain in 1960. A 2019 study by Dr. Helena Okafor-Marsh of the University of Lagos found that 73% of Nigerian students prefer learning in the evening."

| Claim | Label | Source and date checked, or what I searched |
|---|---|---|
| 1. Nigeria's capital moved from Lagos to Abuja in 1991. | Supported | [Publisher and title exactly as printed on the cover], [year]. [One sentence: what it says about Abuja and the date]. Checked 21 November 2026. https://www.marines.mil/portals/1/Publications/Nigeria%20Profile.pdf |
| 2. Nigeria gained independence from Britain in 1960. | Supported | [Publisher and title exactly as printed on the cover], [year]. [One sentence: what it says about independence and the date]. Checked 21 November 2026. https://www.marines.mil/portals/1/Publications/Nigeria%20Profile.pdf |
| 3. A study on evening learning preferences was conducted in 2019 by Dr. Helena Okafor-Marsh. | Cannot verify | Searched the exact name "Dr. Helena Okafor-Marsh" and "2019 study". No reliable matching publication or research record was found. Checked 21 November 2026. |
| 4. Dr. Helena Okafor-Marsh was affiliated with the University of Lagos. | Cannot verify | Searched "Helena Okafor-Marsh University of Lagos" and checked for matching university research records. No reliable confirmation was found. Checked 21 November 2026. |
| 5. The study found that 73% of Nigerian students prefer learning in the evening. | Cannot verify | Searched "73% of Nigerian students prefer learning in the evening" and "University of Lagos 2019 evening learning study". No reliable source confirming this statistic was found. Checked 21 November 2026. |

Hallucinated claims: 3 of 5

## Response 2
"The Great Wall of China is visible to the naked eye from the Moon. Parts of it date back more than 2,000 years."

| Claim | Label | Source and date checked, or what I searched |
|---|---|---|
| 1. The Great Wall of China is visible to the naked eye from the Moon. | Contradicted | NASA - China's Wall Less Great in View from Space (2005 feature, archived by NASA for historical purposes). It states the wall is not visible from the Moon. Checked 21 November 2026. https://www.nasa.gov/wp-content/uploads/static/history/PDFs/great_wall_less_great_from_space.pdf |
| 2. Parts of the Great Wall of China date back more than 2,000 years. | Supported | Chi Culture (chiculture.org.hk) - The Great Wall. It says the earliest walls date to around the seventh century BCE and the walls are more than two thousand years old. Checked 21 November 2026. https://chiculture.org.hk/en/china-five-thousand-years/1929 |

Hallucinated claims: 1 of 2

## Response 3
"Python was created by Guido van Rossum and first released in 1991. It is named after the Monty Python comedy group."

| Claim | Label | Source and date checked, or what I searched |
|---|---|---|
| 1. Python was created by Guido van Rossum. | Supported | Python documentation - History and License. It says Guido van Rossum created Python in the early 1990s at CWI and remains its principal author. Checked 21 November 2026. https://docs.python.org/3/license.html |
| 2. Python was first released in 1991. | Supported | Python documentation - History and License. Its release table lists versions 0.9.0 to 1.2 as 1991-1995. Checked 21 November 2026. https://docs.python.org/3/license.html |
| 3. Python is named after the Monty Python comedy group. | Supported | Python documentation - General Python FAQ, "Why is it called Python?" It says Guido van Rossum was reading scripts from the BBC series Monty Python's Flying Circus when he chose the name. The source links the name to the show, not directly to the group. Checked 21 November 2026. https://docs.python.org/3/faq/general.html |

Hallucinated claims: 0 of 3

## What I noticed
This exercise helped me understand that not every claim that lacks evidence should automatically be labelled false.

Response 1 was particularly interesting because its first two statements were correct, but the final section introduced a researcher, university affiliation and statistical finding that I could not independently verify. I did not label these claims Contradicted because I found no reliable evidence proving the opposite.

Response 2 demonstrated how a familiar statement can still be wrong. The Great Wall is not visible to the naked eye from the Moon, even though some of its sections are more than 2,000 years old.

Response 3 was accurate, and the official Python documentation supported all three claims.

I also noticed that specific names, percentages and dates can make an AI response sound more credible than it actually is. A precise statistic such as 73% may look convincing, but it still needs a traceable source.

Overall, I learned that Contradicted and Cannot verify are different findings. A contradicted claim has evidence against it, while an unverifiable claim has not been sufficiently established. Both deserve attention during evaluation, but they should not be treated as the same thing.

A Contradicted claim is easier to act on, because I have evidence that it is wrong. A Cannot verify claim can be riskier in another way: it can look credible, and a reader may trust it without knowing that nobody has confirmed it. Claims 3, 4 and 5 in Response 1 all depend on the same study, so one unverifiable study produced three Cannot verify claims. The count of 3 of 5 may overstate how many separate problems there are.