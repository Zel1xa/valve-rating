### Roster Details<br />
Team Name: DMS<br />
Roster: AW, h1te, kAlash, sFade8, sm3t<br />
Global Rank: [89](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  910.0<br />
<br />
Final Rank Value (910.0) = Starting Rank Value (901.9) + Head To Head Adjustments (8.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.399[<sup>2</sup>](#table1)
- Opponent Network: 0.175[<sup>2</sup>](#table1)
- LAN Wins: 0.115[<sup>2</sup>](#table1)

The average of these factors is 0.244<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 901.9
- 400 + ( ( 0.244 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 901.9


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
|           43 |      373 | 2024-07-26 | AMKAL           | L   | 1.000      | -            | -                | -                | -         |    -5.07 | AW, h1te, kAlash, sFade8, sm3t |
|           42 |      377 | 2024-07-26 | Revenant        | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.259 (0.168)    | 1 (1.000) |    13.86 | AW, h1te, kAlash, sFade8, sm3t |
|           41 |      415 | 2024-07-25 | 3DMAX           | L   | 1.000      | -            | -                | -                | -         |    -2.13 | AW, h1te, kAlash, sFade8, sm3t |
|           40 |      439 | 2024-07-24 | Eternal Fire    | L   | 1.000      | -            | -                | -                | -         |    -0.55 | AW, h1te, kAlash, sFade8, sm3t |
|           39 |      586 | 2024-07-19 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -12.44 | AW, h1te, kAlash, sFade8, sm3t |
|           38 |      633 | 2024-07-18 | Space           | L   | 1.000      | -            | -                | -                | -         |   -16.25 | AW, h1te, kAlash, sFade8, sm3t |
|           37 |      763 | 2024-07-16 | ALTERNATE aTTaX | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.537 (0.233)    | 0 (0.000) |    13.21 | AW, h1te, kAlash, sFade8, sm3t |
|           36 |     1168 | 2024-06-12 | Verdant         | L   | 0.835      | -            | -                | -                | -         |   -14.48 | AW, h1te, kAlash, sFade8, sm3t |
|           35 |     1191 | 2024-06-11 | Zero Tenacity   | L   | 0.828      | -            | -                | -                | -         |    -7.72 | AW, h1te, kAlash, sFade8, sm3t |
|           34 |     1369 | 2024-06-07 | Zero Tenacity   | L   | 0.802      | -            | -                | -                | -         |    -7.72 | AW, h1te, kAlash, sFade8, sm3t |
|           33 |     1473 | 2024-06-06 | CYBERSHOKE      | L   | 0.792      | -            | -                | -                | -         |   -15.81 | AW, h1te, kAlash, sFade8, sm3t |
|           32 |     1569 | 2024-06-04 | Sampi           | L   | 0.779      | -            | -                | -                | -         |   -14.43 | AW, h1te, kAlash, sFade8, sm3t |
|           31 |     1587 | 2024-06-03 | ARCRED          | L   | 0.774      | -            | -                | -                | -         |   -13.80 | AW, h1te, kAlash, sFade8, sm3t |
|           30 |     1596 | 2024-06-02 | Zero Tenacity   | L   | 0.768      | -            | -                | -                | -         |    -7.77 | AW, h1te, kAlash, sFade8, sm3t |
|           29 |     1608 | 2024-06-02 | fnatic          | W   | 0.767      | 0.143        | 0.371 (0.041)    | 0.680 (0.074)    | 0 (0.000) |    22.58 | AW, h1te, kAlash, sFade8, sm3t |
|           28 |     1626 | 2024-06-01 | ENCE            | W   | 0.762      | 0.143        | 0.173 (0.019)    | 0.422 (0.046)    | 0 (0.000) |    21.73 | AW, h1te, kAlash, sFade8, sm3t |
|           27 |     1639 | 2024-06-01 | Zero Tenacity   | L   | 0.761      | -            | -                | -                | -         |    -6.77 | AW, h1te, kAlash, sFade8, sm3t |
|           26 |     1645 | 2024-06-01 | ENCE            | W   | 0.760      | 0.143        | 0.173 (0.019)    | -                | 0 (0.000) |    22.04 | AW, h1te, kAlash, sFade8, sm3t |
|           25 |     1666 | 2024-05-31 | Spirit Academy  | W   | 0.755      | -            | -                | -                | 0 (0.000) |     5.99 | AW, h1te, kAlash, sFade8, sm3t |
|           24 |     1697 | 2024-05-30 | Nemiga          | W   | 0.747      | 0.372        | 0.314 (0.087)    | 0.704 (0.196)    | 0 (0.000) |    18.46 | AW, h1te, kAlash, sFade8, sm3t |
|           23 |     1715 | 2024-05-29 | Verdant         | W   | 0.742      | 0.372        | 0.015 (0.004)    | 0.287 (0.079)    | 0 (0.000) |    11.76 | AW, h1te, kAlash, sFade8, sm3t |
|           22 |     1788 | 2024-05-26 | GUN5            | L   | 0.719      | -            | -                | -                | -         |   -10.73 | AW, h1te, kAlash, sFade8, sm3t |
|           21 |     1817 | 2024-05-24 | VP.Prodigy      | L   | 0.707      | -            | -                | -                | -         |   -12.00 | AW, h1te, kAlash, sFade8, sm3t |
|           20 |     1826 | 2024-05-24 | BetBoom         | L   | 0.705      | -            | -                | -                | -         |    -1.66 | AW, h1te, kAlash, sFade8, sm3t |
|           19 |     1836 | 2024-05-23 | B8              | L   | 0.700      | -            | -                | -                | -         |    -5.03 | AW, h1te, kAlash, sFade8, sm3t |
|           18 |     1915 | 2024-05-21 | EYEBALLERS      | W   | 0.688      | 0.435        | -                | 0.488 (0.146)    | 0 (0.000) |     9.53 | AW, h1te, kAlash, sFade8, sm3t |
|           17 |     1919 | 2024-05-21 | MOUZ NXT        | W   | 0.687      | 0.435        | 0.139 (0.041)    | 0.962 (0.287)    | 0 (0.000) |    14.71 | AW, h1te, kAlash, sFade8, sm3t |
|           16 |     1974 | 2024-05-19 | Space           | L   | 0.674      | -            | -                | -                | -         |   -12.76 | AW, h1te, kAlash, sFade8, sm3t |
|           15 |     2004 | 2024-05-18 | 777             | W   | 0.667      | -            | -                | -                | -         |     5.34 | AW, h1te, kAlash, sFade8, sm3t |
|           14 |     2016 | 2024-05-18 | Sampi           | W   | 0.666      | 0.435        | 0.027 (0.008)    | 1.000 (0.290)    | -         |    10.51 | AW, h1te, kAlash, sFade8, sm3t |
|           13 |     2054 | 2024-05-17 | MOUZ NXT        | L   | 0.659      | -            | -                | -                | -         |    -6.46 | AW, h1te, kAlash, sFade8, sm3t |
|           12 |     2075 | 2024-05-16 | B8              | L   | 0.655      | -            | -                | -                | -         |    -5.26 | AW, h1te, kAlash, sFade8, sm3t |
|           11 |     2127 | 2024-05-15 | Monte           | L   | 0.647      | -            | -                | -                | -         |    -8.18 | AW, h1te, kAlash, sFade8, sm3t |
|           10 |     2187 | 2024-05-14 | Rare Atom       | W   | 0.641      | -            | -                | -                | -         |     8.86 | AW, h1te, kAlash, sFade8, sm3t |
|            9 |     2198 | 2024-05-14 | Sangal          | W   | 0.639      | 0.435        | 0.219 (0.061)    | 0.846 (0.235)    | -         |    15.27 | AW, h1te, kAlash, sFade8, sm3t |
|            8 |     2214 | 2024-05-13 | Heimo           | W   | 0.633      | -            | -                | -                | -         |     4.93 | AW, h1te, kAlash, sFade8, sm3t |
|            7 |     2267 | 2024-05-11 | CYBERSHOKE      | W   | 0.620      | -            | -                | -                | -         |     9.82 | AW, h1te, kAlash, sFade8, sm3t |
|            6 |     2533 | 2024-04-28 | Alliance        | L   | 0.533      | -            | -                | -                | -         |    -9.18 | AW, h1te, kAlash, sFade8, sm3t |
|            5 |     2582 | 2024-04-26 | BLEED           | L   | 0.520      | -            | -                | -                | -         |    -4.78 | AW, h1te, kAlash, sFade8, sm3t |
|            4 |     2787 | 2024-04-18 | Apeks           | L   | 0.468      | -            | -                | -                | -         |    -6.85 | AW, h1te, kAlash, sFade8, sm3t |
|            3 |     2797 | 2024-04-18 | EYEBALLERS      | W   | 0.468      | -            | -                | -                | -         |     6.94 | AW, h1te, kAlash, sFade8, sm3t |
|            2 |     3984 | 2024-02-27 | kONO            | L   | 0.128      | -            | -                | -                | -         |    -2.53 | AW, h1te, kAlash, sFade8, sm3t |
|            1 |     3988 | 2024-02-27 | B8              | W   | 0.128      | -            | -                | -                | -         |     2.96 | AW, h1te, kAlash, sFade8, sm3t |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,027.14)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
