### Roster Details<br />
Team Name: Liquid<br />
Roster: jks, NAF, Twistzz, ultimate, YEKINDAR<br />
Global Rank: [9](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [8]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [1]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1672.6<br />
<br />
Final Rank Value (1672.6) = Starting Rank Value (1595.7) + Head To Head Adjustments (76.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.707[<sup>1</sup>](#table2)
- Bounty Collected: 0.623[<sup>2</sup>](#table1)
- Opponent Network: 0.202[<sup>2</sup>](#table1)
- LAN Wins: 0.807[<sup>2</sup>](#table1)

The average of these factors is 0.585<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1595.7
- 400 + ( ( 0.585 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1595.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |       33 | 2024-08-03 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.371 (0.215)    | 1 (1.000) |    25.60 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           37 |      112 | 2024-08-01 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.371 (0.215)    | 1 (1.000) |    26.86 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           36 |      156 | 2024-07-31 | Virtus.pro       | W   | 1.000      | 0.581        | 0.497 (0.289)    | 0.323 (0.188)    | 1 (1.000) |    19.11 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           35 |     1669 | 2024-05-29 | G2               | L   | 0.755      | -            | -                | -                | -         |    -3.20 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     1694 | 2024-05-28 | Falcons          | W   | 0.748      | 0.624        | 0.223 (0.104)    | -                | 1 (0.748) |     6.42 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     1712 | 2024-05-27 | 9z               | L   | 0.742      | -            | -                | -                | -         |   -16.59 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     1723 | 2024-05-27 | Complexity       | W   | 0.741      | 0.624        | 0.342 (0.158)    | 0.380 (0.176)    | 1 (0.741) |    13.69 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     1797 | 2024-05-23 | Eternal Fire     | L   | 0.713      | -            | -                | -                | -         |    -8.85 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     1841 | 2024-05-22 | Astralis         | W   | 0.705      | 0.769        | 0.390 (0.212)    | 0.421 (0.228)    | -         |    15.55 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     1886 | 2024-05-21 | ENCE             | W   | 0.698      | 0.769        | 0.169 (0.091)    | 0.400 (0.215)    | -         |     5.36 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     1942 | 2024-05-19 | AMKAL            | W   | 0.686      | 0.769        | -                | 0.475 (0.250)    | -         |     2.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     1957 | 2024-05-18 | OG               | W   | 0.681      | 0.769        | 0.139 (0.073)    | -                | -         |     1.03 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     2247 | 2024-05-10 | Astralis         | L   | 0.626      | -            | -                | -                | -         |    -5.70 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     2291 | 2024-05-08 | FlyQuest         | W   | 0.613      | 0.889        | -                | 0.294 (0.160)    | 1 (0.613) |     2.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     2359 | 2024-05-04 | MOUZ             | L   | 0.587      | -            | -                | -                | -         |    -3.44 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     2421 | 2024-05-01 | Monte            | W   | 0.567      | -            | -                | -                | 1 (0.567) |     0.63 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     2444 | 2024-04-30 | FURIA            | W   | 0.560      | 0.889        | 0.284 (0.141)    | 0.490 (0.244)    | 1 (0.560) |    10.56 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     2688 | 2024-04-19 | M80              | L   | 0.489      | -            | -                | -                | -         |   -13.64 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     2738 | 2024-04-18 | M80              | W   | 0.483      | -            | -                | -                | -         |     1.67 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     2741 | 2024-04-18 | Legacy           | W   | 0.481      | -            | -                | -                | -         |     0.60 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     2788 | 2024-04-17 | Akimbo           | W   | 0.475      | -            | -                | -                | -         |     0.14 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     2793 | 2024-04-17 | straykids        | W   | 0.475      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     2906 | 2024-04-12 | FaZe             | L   | 0.438      | -            | -                | -                | -         |    -5.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     2991 | 2024-04-10 | MOUZ             | L   | 0.424      | -            | -                | -                | -         |    -2.61 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     3069 | 2024-04-08 | G2               | W   | 0.411      | 0.624        | 1.000 (0.257)    | 0.498 (0.128)    | 1 (0.411) |    11.67 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     3079 | 2024-04-07 | HEROIC           | W   | 0.410      | -            | -                | -                | 1 (0.410) |     6.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     3751 | 2024-03-07 | SAW              | L   | 0.199      | -            | -                | -                | -         |    -5.73 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     3833 | 2024-03-04 | Complexity       | L   | 0.181      | -            | -                | -                | -         |    -2.37 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     3869 | 2024-03-03 | BOSS             | W   | 0.173      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     3882 | 2024-03-02 | FURIA            | L   | 0.167      | -            | -                | -                | -         |    -1.73 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     3897 | 2024-03-01 | BESTIA           | W   | 0.162      | -            | -                | -                | -         |     0.20 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     3968 | 2024-02-26 | Nouns            | W   | 0.136      | -            | -                | -                | -         |     0.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     3970 | 2024-02-26 | BOSS             | W   | 0.135      | -            | -                | -                | -         |     0.05 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     3983 | 2024-02-25 | Wildcard         | W   | 0.129      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     3988 | 2024-02-25 | Nouns            | L   | 0.128      | -            | -                | -                | -         |    -3.96 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     4047 | 2024-02-22 | Party Astronauts | W   | 0.109      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     4049 | 2024-02-22 | MIGHT            | W   | 0.109      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     4055 | 2024-02-22 | ex-CatEvil       | W   | 0.109      | -            | -                | -                | -         |     0.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($124,523.43)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.38) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-06-02 |      0.780 | $6,000.00      | $4,682.64       |
| 2024-05-23 |      0.713 | $100,000.00    | $71,252.31      |
| 2024-05-12 |      0.640 | $32,000.00     | $20,467.41      |
| 2024-04-14 |      0.452 | $10,000.00     | $4,517.13       |
| 2024-03-10 |      0.221 | $5,000.00      | $1,103.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
