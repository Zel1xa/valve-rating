### Roster Details<br />
Team Name: DMS<br />
Roster: AW, h1te, kAlash, sFade8, sm3t<br />
Global Rank: [90](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  908.1<br />
<br />
Final Rank Value (908.1) = Starting Rank Value (903.0) + Head To Head Adjustments (5.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.399[<sup>2</sup>](#table1)
- Opponent Network: 0.182[<sup>2</sup>](#table1)
- LAN Wins: 0.115[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 903.0
- 400 + ( ( 0.246 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 903.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           43 |      352 | 2024-07-26 | AMKAL           | L   | 1.000      | -            | -                | -                | -         |    -5.04 | AW, h1te, kAlash, sFade8, sm3t |
|           42 |      356 | 2024-07-26 | Revenant        | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.267 (0.174)    | 1 (1.000) |    13.86 | AW, h1te, kAlash, sFade8, sm3t |
|           41 |      394 | 2024-07-25 | 3DMAX           | L   | 1.000      | -            | -                | -                | -         |    -2.16 | AW, h1te, kAlash, sFade8, sm3t |
|           40 |      418 | 2024-07-24 | Eternal Fire    | L   | 1.000      | -            | -                | -                | -         |    -0.54 | AW, h1te, kAlash, sFade8, sm3t |
|           39 |      565 | 2024-07-19 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -12.52 | AW, h1te, kAlash, sFade8, sm3t |
|           38 |      612 | 2024-07-18 | Space           | L   | 1.000      | -            | -                | -                | -         |   -16.43 | AW, h1te, kAlash, sFade8, sm3t |
|           37 |      742 | 2024-07-16 | ALTERNATE aTTaX | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.557 (0.242)    | 0 (0.000) |    13.17 | AW, h1te, kAlash, sFade8, sm3t |
|           36 |     1147 | 2024-06-12 | Verdant         | L   | 0.841      | -            | -                | -                | -         |   -14.68 | AW, h1te, kAlash, sFade8, sm3t |
|           35 |     1170 | 2024-06-11 | Zero Tenacity   | L   | 0.834      | -            | -                | -                | -         |    -7.86 | AW, h1te, kAlash, sFade8, sm3t |
|           34 |     1348 | 2024-06-07 | Zero Tenacity   | L   | 0.808      | -            | -                | -                | -         |    -7.88 | AW, h1te, kAlash, sFade8, sm3t |
|           33 |     1452 | 2024-06-06 | CYBERSHOKE      | L   | 0.799      | -            | -                | -                | -         |   -15.91 | AW, h1te, kAlash, sFade8, sm3t |
|           32 |     1548 | 2024-06-04 | Sampi           | L   | 0.786      | -            | -                | -                | -         |   -14.55 | AW, h1te, kAlash, sFade8, sm3t |
|           31 |     1566 | 2024-06-03 | ARCRED          | L   | 0.781      | -            | -                | -                | -         |   -15.24 | AW, h1te, kAlash, sFade8, sm3t |
|           30 |     1575 | 2024-06-02 | Zero Tenacity   | L   | 0.775      | -            | -                | -                | -         |    -7.94 | AW, h1te, kAlash, sFade8, sm3t |
|           29 |     1587 | 2024-06-02 | fnatic          | W   | 0.773      | 0.143        | 0.371 (0.041)    | 0.706 (0.078)    | 0 (0.000) |    22.77 | AW, h1te, kAlash, sFade8, sm3t |
|           28 |     1605 | 2024-06-01 | ENCE            | W   | 0.768      | 0.143        | 0.168 (0.018)    | 0.438 (0.048)    | 0 (0.000) |    21.85 | AW, h1te, kAlash, sFade8, sm3t |
|           27 |     1618 | 2024-06-01 | Zero Tenacity   | L   | 0.767      | -            | -                | -                | -         |    -6.93 | AW, h1te, kAlash, sFade8, sm3t |
|           26 |     1624 | 2024-06-01 | ENCE            | W   | 0.766      | 0.143        | 0.168 (0.018)    | -                | 0 (0.000) |    22.17 | AW, h1te, kAlash, sFade8, sm3t |
|           25 |     1645 | 2024-05-31 | Spirit Academy  | W   | 0.761      | -            | -                | -                | 0 (0.000) |     6.01 | AW, h1te, kAlash, sFade8, sm3t |
|           24 |     1676 | 2024-05-30 | Nemiga          | W   | 0.754      | 0.372        | 0.316 (0.089)    | 0.731 (0.205)    | 0 (0.000) |    18.61 | AW, h1te, kAlash, sFade8, sm3t |
|           23 |     1694 | 2024-05-29 | Verdant         | W   | 0.748      | 0.372        | 0.015 (0.004)    | 0.298 (0.083)    | 0 (0.000) |    11.78 | AW, h1te, kAlash, sFade8, sm3t |
|           22 |     1767 | 2024-05-26 | GUN5            | L   | 0.726      | -            | -                | -                | -         |   -10.86 | AW, h1te, kAlash, sFade8, sm3t |
|           21 |     1796 | 2024-05-24 | VP.Prodigy      | L   | 0.714      | -            | -                | -                | -         |   -12.14 | AW, h1te, kAlash, sFade8, sm3t |
|           20 |     1805 | 2024-05-24 | BetBoom         | L   | 0.712      | -            | -                | -                | -         |    -1.67 | AW, h1te, kAlash, sFade8, sm3t |
|           19 |     1815 | 2024-05-23 | B8              | L   | 0.706      | -            | -                | -                | -         |    -5.12 | AW, h1te, kAlash, sFade8, sm3t |
|           18 |     1894 | 2024-05-21 | EYEBALLERS      | W   | 0.694      | 0.435        | -                | 0.507 (0.153)    | 0 (0.000) |     9.42 | AW, h1te, kAlash, sFade8, sm3t |
|           17 |     1898 | 2024-05-21 | MOUZ NXT        | W   | 0.693      | 0.435        | 0.139 (0.042)    | 1.000 (0.301)    | 0 (0.000) |    14.80 | AW, h1te, kAlash, sFade8, sm3t |
|           16 |     1953 | 2024-05-19 | Space           | L   | 0.681      | -            | -                | -                | -         |   -12.97 | AW, h1te, kAlash, sFade8, sm3t |
|           15 |     1983 | 2024-05-18 | 777             | W   | 0.674      | -            | -                | -                | -         |     5.39 | AW, h1te, kAlash, sFade8, sm3t |
|           14 |     1995 | 2024-05-18 | Sampi           | W   | 0.673      | 0.435        | 0.027 (0.008)    | 1.000 (0.292)    | -         |    10.57 | AW, h1te, kAlash, sFade8, sm3t |
|           13 |     2033 | 2024-05-17 | MOUZ NXT        | L   | 0.666      | -            | -                | -                | -         |    -6.57 | AW, h1te, kAlash, sFade8, sm3t |
|           12 |     2054 | 2024-05-16 | B8              | L   | 0.661      | -            | -                | -                | -         |    -5.37 | AW, h1te, kAlash, sFade8, sm3t |
|           11 |     2106 | 2024-05-15 | Monte           | L   | 0.654      | -            | -                | -                | -         |    -8.28 | AW, h1te, kAlash, sFade8, sm3t |
|           10 |     2166 | 2024-05-14 | Rare Atom       | W   | 0.647      | -            | -                | -                | -         |     8.89 | AW, h1te, kAlash, sFade8, sm3t |
|            9 |     2177 | 2024-05-14 | Sangal          | W   | 0.645      | 0.435        | 0.219 (0.061)    | 0.877 (0.246)    | -         |    15.32 | AW, h1te, kAlash, sFade8, sm3t |
|            8 |     2193 | 2024-05-13 | Heimo           | W   | 0.640      | -            | -                | -                | -         |     4.95 | AW, h1te, kAlash, sFade8, sm3t |
|            7 |     2246 | 2024-05-11 | CYBERSHOKE      | W   | 0.627      | -            | -                | -                | -         |     9.90 | AW, h1te, kAlash, sFade8, sm3t |
|            6 |     2512 | 2024-04-28 | Alliance        | L   | 0.540      | -            | -                | -                | -         |    -9.34 | AW, h1te, kAlash, sFade8, sm3t |
|            5 |     2561 | 2024-04-26 | BLEED           | L   | 0.526      | -            | -                | -                | -         |    -4.84 | AW, h1te, kAlash, sFade8, sm3t |
|            4 |     2766 | 2024-04-18 | Apeks           | L   | 0.475      | -            | -                | -                | -         |    -6.93 | AW, h1te, kAlash, sFade8, sm3t |
|            3 |     2776 | 2024-04-18 | EYEBALLERS      | W   | 0.474      | -            | -                | -                | -         |     6.95 | AW, h1te, kAlash, sFade8, sm3t |
|            2 |     3963 | 2024-02-27 | kONO            | L   | 0.135      | -            | -                | -                | -         |    -2.69 | AW, h1te, kAlash, sFade8, sm3t |
|            1 |     3967 | 2024-02-27 | B8              | W   | 0.134      | -            | -                | -                | -         |     3.10 | AW, h1te, kAlash, sFade8, sm3t |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,035.24)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
