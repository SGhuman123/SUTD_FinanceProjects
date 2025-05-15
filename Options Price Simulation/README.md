# Simulation of Option Pricing Algorithm

Implemented four option pricing methods:

𝟭. 𝗠𝗼𝗻𝘁𝗲 𝗖𝗮𝗿𝗹𝗼 𝘀𝗶𝗺𝘂𝗹𝗮𝘁𝗶𝗼𝗻
𝟮. 𝗕𝗶𝗻𝗼𝗺𝗶𝗮𝗹 𝗢𝗽𝘁𝗶𝗼𝗻 𝗽𝗿𝗶𝗰𝗶𝗻𝗴 𝗺𝗼𝗱𝗲𝗹
𝟯. 𝗕𝗹𝗮𝗰𝗸-𝗦𝗰𝗵𝗼𝗹𝗲𝘀
𝟰. 𝗣𝘂𝘁-𝗰𝗮𝗹𝗹 𝗽𝗮𝗿𝗶𝘁𝘆

The options are to be priced on a stock with 𝘀𝗽𝗲𝗰𝗶𝗳𝗶𝗰 𝗽𝗮𝗿𝗮𝗺𝗲𝘁𝗲𝗿𝘀, eg: 𝟮𝟬% 𝗮𝗻𝗻𝘂𝗮𝗹𝗶𝘇𝗲𝗱 𝘃𝗼𝗹𝗮𝘁𝗶𝗹𝗶𝘁𝘆, 𝘀𝘁𝗼𝗰𝗸 𝗽𝗿𝗶𝗰𝗲 𝗼𝗳 $𝟮𝟬𝟬, 𝟯% 𝗮𝗻𝗻𝘂𝗮𝗹𝗶𝘇𝗲𝗱 𝗱𝗶𝘃𝗶𝗱𝗲𝗻𝗱, and 𝟲% 𝗮𝗻𝗻𝘂𝗮𝗹𝗶𝘇𝗲𝗱 𝗿𝗶𝘀𝗸-𝗳𝗿𝗲𝗲 𝗿𝗮𝘁𝗲. 𝗘𝘂𝗿𝗼𝗽𝗲𝗮𝗻 𝗽𝘂𝘁 and 𝗰𝗮𝗹𝗹 𝗼𝗽𝘁𝗶𝗼𝗻𝘀 with a 𝘀𝘁𝗿𝗶𝗸𝗲 𝗽𝗿𝗶𝗰𝗲 𝗼𝗳 $𝟮𝟬𝟱 and an 𝗲𝘅𝗽𝗶𝗿𝘆 𝗼𝗳 𝗼𝗻𝗲 𝘆𝗲𝗮𝗿 & 𝘀𝗲𝘃𝗲𝗻 𝗺𝗼𝗻𝘁𝗵𝘀 are considered.

For the 𝗠𝗼𝗻𝘁𝗲 𝗖𝗮𝗿𝗹𝗼 𝘀𝗶𝗺𝘂𝗹𝗮𝘁𝗶𝗼𝗻, 𝗼𝗽𝘁𝗶𝗼𝗻 𝗽𝗿𝗶𝗰𝗲𝘀 are determined for 𝘃𝗮𝗿𝘆𝗶𝗻𝗴 𝗻𝘂𝗺𝗯𝗲𝗿𝘀 𝗼𝗳 𝗶𝘁𝗲𝗿𝗮𝘁𝗶𝗼𝗻𝘀 (𝗡), (i.e: 𝟭,𝟬𝟬𝟬, 𝟭𝟬,𝟬𝟬𝟬, & 𝟭𝟬𝟬,𝟬𝟬𝟬). We reported 𝗼𝗽𝘁𝗶𝗼𝗻 𝗽𝗿𝗶𝗰𝗲𝘀, 𝗽𝗿𝗶𝗰𝗶𝗻𝗴 the 𝗽𝘂𝘁 𝗼𝗽𝘁𝗶𝗼𝗻 using 𝗽𝘂𝘁-𝗰𝗮𝗹𝗹 𝗽𝗮𝗿𝗶𝘁𝘆 and the 𝗰𝗮𝗹𝗹 𝗼𝗽𝘁𝗶𝗼𝗻 𝘃𝗮𝗹𝘂𝗲 from the 𝗠𝗼𝗻𝘁𝗲 𝗖𝗮𝗿𝗹𝗼 𝘀𝗶𝗺𝘂𝗹𝗮𝘁𝗶𝗼𝗻, and vice versa. The 𝗱𝗶𝗳𝗳𝗲𝗿𝗲𝗻𝗰𝗲 𝗯𝗲𝘁𝘄𝗲𝗲𝗻 the 𝗽𝘂𝘁-𝗰𝗮𝗹𝗹 𝗽𝗮𝗿𝗶𝘁𝘆 𝗽𝗿𝗶𝗰𝗲 and the 𝘀𝗶𝗺𝘂𝗹𝗮𝘁𝗲𝗱 𝗼𝗽𝘁𝗶𝗼𝗻 𝗽𝗿𝗶𝗰𝗲 is 𝗮𝗻𝗮𝗹𝘆𝘇𝗲𝗱.

In the 𝗕𝗶𝗻𝗼𝗺𝗶𝗮𝗹 𝗢𝗽𝘁𝗶𝗼𝗻 𝗽𝗿𝗶𝗰𝗶𝗻𝗴, 𝗼𝗽𝘁𝗶𝗼𝗻 𝗽𝗿𝗶𝗰𝗲𝘀 for 𝗽𝘂𝘁 and 𝗰𝗮𝗹𝗹 are found for 𝗱𝗶𝗳𝗳𝗲𝗿𝗲𝗻𝘁 𝗻𝘂𝗺𝗯𝗲𝗿𝘀 𝗼𝗳 𝘁𝗶𝗺𝗲 𝘀𝘁𝗲𝗽𝘀 in the 𝗯𝗶𝗻𝗼𝗺𝗶𝗮𝗹 𝘁𝗿𝗲𝗲 (𝟭𝟬𝟬, 𝟱𝟬𝟬, 𝟭,𝟬𝟬𝟬). Similar to the Monte Carlo section, 𝗽𝘂𝘁-𝗰𝗮𝗹𝗹 𝗽𝗮𝗿𝗶𝘁𝘆 𝗽𝗿𝗶𝗰𝗲𝘀 are to be 𝗰𝗮𝗹𝗰𝘂𝗹𝗮𝘁𝗲𝗱 and the 𝗱𝗶𝗳𝗳𝗲𝗿𝗲𝗻𝗰𝗲 𝗮𝗻𝗮𝗹𝘆𝘇𝗲𝗱.

We conclude by 𝗰𝗼𝗺𝗽𝗮𝗿𝗶𝗻𝗴 the 𝗠𝗼𝗻𝘁𝗲 𝗖𝗮𝗿𝗹𝗼 and 𝗕𝗶𝗻𝗼𝗺𝗶𝗮𝗹 𝗼𝗽𝘁𝗶𝗼𝗻 prices with those from the 𝗕𝗹𝗮𝗰𝗸-𝗦𝗰𝗵𝗼𝗹𝗲𝘀 𝗺𝗼𝗱𝗲𝗹. The 𝗴𝗼𝗮𝗹 is to 𝗶𝗱𝗲𝗻𝘁𝗶𝗳𝘆 𝘄𝗵𝗶𝗰𝗵 𝗺𝗼𝗱𝗲𝗹, is 𝗰𝗹𝗼𝘀𝗲𝘀𝘁 𝗶𝗻 𝘃𝗮𝗹𝘂𝗲 𝘁𝗼 𝘁𝗵𝗲 𝗕𝗹𝗮𝗰𝗸-𝗦𝗰𝗵𝗼𝗹𝗲𝘀 𝗼𝗽𝘁𝗶𝗼𝗻 𝗽𝗿𝗶𝗰𝗲.
