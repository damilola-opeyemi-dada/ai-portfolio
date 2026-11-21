# Claim Check 1 (synthetic examples, written for practice)

## Method
I split each response into single claims, checked each claim against a reliable source, and labelled it Supported, Contradicted or Cannot verify. I did not label anything Supported from memory alone.

## Response 1
"The Eiffel Tower was completed in 1889 for the World's Fair in Paris. It stands over 300 metres tall. It is located in Berlin."

| Claim | Label | Source and date checked |
|---|---|---|
| 1. The Eiffel Tower was completed in 1889. | Supported | [Official Eiffel Tower website - History](https://toureiffel.paris/en/the-monument/history). Checked 20 November 2026. |
| 2. The Eiffel Tower was built for the World's Fair in Paris. | Cannot verify | Searched the official Eiffel Tower website History page for "World's Fair" and "Exposition Universelle". Not found. Checked 20 November 2026. |
| 3. The Eiffel Tower stands over 300 metres tall. | Supported | [Official Eiffel Tower website - Current height](https://www.toureiffel.paris/en/the-monument/key-figures) is 330 metres. Checked 20 November 2026. |
| 4. The Eiffel Tower is located in Berlin. | Contradicted | [Official Eiffel Tower website](https://toureiffel.paris/en/the-monument/history) confirms its location in Paris, France. Checked 20 November 2026. |

Hallucinated claims: 2 of 4

## Response 2
"Chinua Achebe was a Nigerian novelist best known for Things Fall Apart, published in 1958. He won the Nobel Prize in Literature in 1986."

| Claim | Label | Source and date checked |
|---|---|---|
| 1. Chinua Achebe was a Nigerian novelist. | Supported | [Library of Congress - An Evening with Chinua Achebe](https://www.loc.gov/item/2021687528). Checked 20 November 2026. |
| 2. He was best known for Things Fall Apart. | Supported | [Oxford Academic - Chinua Achebe's Things Fall Apart: A Casebook](https://academic.oup.com/book/48533). Checked 21 November 2026. |
| 3. Things Fall Apart was published in 1958. | Supported | [Oxford Academic - Chinua Achebe's Things Fall Apart: A Casebook](https://academic.oup.com/book/48533). Checked 21 November 2026. |
| 4. He won the Nobel Prize in Literature in 1986. | Contradicted | [Nobel Prize official website](https://www.nobelprize.org/prizes/literature/1986/summary/) confirms Wole Soyinka was the 1986 Literature laureate. Checked 20 November 2026. |

Hallucinated claims: 1 of 4

## Response 3
"Water boils at 100 degrees Celsius at sea level. At the top of Mount Everest, water boils at a higher temperature than at sea level."

| Claim | Label | Source and date checked |
|---|---|---|
| 1. Water boils at 100 degrees Celsius at sea level. | Supported | [International Association for the Properties of Water and Steam (IAPWS)](https://www.iapws.org/faq/boil.html). Checked 20 November 2026. |
| 2. At the top of Mount Everest, water boils at a higher temperature than at sea level. | Contradicted | [Pew Research Center](https://www.pewresearch.org/short-reads/2015/09/14/does-waters-boiling-point-change-with-altitude-americans-arent-sure/) - Water boils at lower temperatures at higher elevations. Checked 21 November 2026. |

Hallucinated claims: 1 of 2

## Response 4
"Mount Kilimanjaro is in Tanzania and is the highest mountain in Africa. It is about 5,895 metres high."

| Claim | Label | Source and date checked |
|---|---|---|
| 1. Mount Kilimanjaro is in Tanzania. | Supported | [National Geographic - Kilimanjaro](https://education.nationalgeographic.org/resource/kilimanjaro). Checked 20 November 2026. |
| 2. Mount Kilimanjaro is the highest mountain in Africa. | Supported | [UNESCO World Heritage Centre - Kilimanjaro National Park](https://whc.unesco.org/en/list/403). Checked 20 November 2026. |
| 3. Mount Kilimanjaro is about 5,895 metres high. | Supported | [UNESCO World Heritage Centre - Kilimanjaro National Park](https://whc.unesco.org/en/list/403). Checked 20 November 2026. |

Hallucinated claims: 0 of 3

## What I noticed
This exercise showed me that an AI response can contain several correct facts and still include a serious hallucination.

Response 1 gives accurate information about the Eiffel Tower's construction and height but incorrectly places it in Berlin.

Response 2 correctly identifies Chinua Achebe and his famous novel but falsely claims he won the 1986 Nobel Prize. Wole Soyinka received that award.

Response 3 contains a scientific error because water boils at a lower temperature at higher altitudes due to reduced atmospheric pressure.

Response 4 contains three supported claims and no identified hallucinations.

I learned that checking every individual claim is more reliable than judging an entire response based on how accurate or convincing it sounds.

The most important lesson is that one false statement can undermine an otherwise accurate AI response.

The false claims were written in the same confident tone as the true ones, so they could not be spotted by style. Some were near misses. In Response 2, the 1986 Nobel Prize in Literature did go to a Nigerian writer, but to Wole Soyinka, not Chinua Achebe. I used the label "Cannot verify" once. The official Eiffel Tower History page did not say the tower was built for the World's Fair, so I could not confirm that claim from that source. This does not prove it is false, only that I could not verify it there.