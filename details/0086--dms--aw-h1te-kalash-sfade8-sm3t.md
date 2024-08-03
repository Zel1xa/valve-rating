### Roster Details<br />
Team Name: DMS<br />
Roster: AW, h1te, kAlash, sFade8, sm3t<br />
Global Rank: [86](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  909.5<br />
<br />
Final Rank Value (909.5) = Starting Rank Value (902.9) + Head To Head Adjustments (6.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.399[<sup>2</sup>](#table1)
- Opponent Network: 0.184[<sup>2</sup>](#table1)
- LAN Wins: 0.114[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 902.9
- 400 + ( ( 0.246 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 902.9


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
|           42 |      277 | 2024-07-26 | AMKAL           | L   | 1.000      | -            | -                | -                | -         |    -5.10 | AW, h1te, kAlash, sFade8, sm3t |
|           41 |      281 | 2024-07-26 | Revenant        | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.275 (0.179)    | 1 (1.000) |    13.46 | AW, h1te, kAlash, sFade8, sm3t |
|           40 |      319 | 2024-07-25 | 3DMAX           | L   | 1.000      | -            | -                | -                | -         |    -2.31 | AW, h1te, kAlash, sFade8, sm3t |
|           39 |      343 | 2024-07-24 | Eternal Fire    | L   | 1.000      | -            | -                | -                | -         |    -0.57 | AW, h1te, kAlash, sFade8, sm3t |
|           38 |      490 | 2024-07-19 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -13.71 | AW, h1te, kAlash, sFade8, sm3t |
|           37 |      537 | 2024-07-18 | Space           | L   | 1.000      | -            | -                | -                | -         |   -15.95 | AW, h1te, kAlash, sFade8, sm3t |
|           36 |      664 | 2024-07-16 | ALTERNATE aTTaX | W   | 1.000      | 0.435        | 0.032 (0.014)    | 0.580 (0.252)    | 0 (0.000) |    12.84 | AW, h1te, kAlash, sFade8, sm3t |
|           35 |     1043 | 2024-06-12 | Verdant         | L   | 0.853      | -            | -                | -                | -         |   -15.06 | AW, h1te, kAlash, sFade8, sm3t |
|           34 |     1237 | 2024-06-07 | Zero Tenacity   | L   | 0.820      | -            | -                | -                | -         |    -8.12 | AW, h1te, kAlash, sFade8, sm3t |
|           33 |     1339 | 2024-06-06 | CYBERSHOKE      | L   | 0.811      | -            | -                | -                | -         |   -15.85 | AW, h1te, kAlash, sFade8, sm3t |
|           32 |     1434 | 2024-06-04 | Sampi           | L   | 0.798      | -            | -                | -                | -         |   -14.75 | AW, h1te, kAlash, sFade8, sm3t |
|           31 |     1452 | 2024-06-03 | ARCRED          | L   | 0.793      | -            | -                | -                | -         |   -15.25 | AW, h1te, kAlash, sFade8, sm3t |
|           30 |     1461 | 2024-06-02 | Zero Tenacity   | L   | 0.787      | -            | -                | -                | -         |    -8.07 | AW, h1te, kAlash, sFade8, sm3t |
|           29 |     1472 | 2024-06-02 | fnatic          | W   | 0.785      | 0.143        | 0.290 (0.032)    | 0.627 (0.070)    | 0 (0.000) |    21.35 | AW, h1te, kAlash, sFade8, sm3t |
|           28 |     1490 | 2024-06-01 | ENCE            | W   | 0.780      | 0.143        | 0.170 (0.019)    | -                | 0 (0.000) |    21.96 | AW, h1te, kAlash, sFade8, sm3t |
|           27 |     1502 | 2024-06-01 | Zero Tenacity   | L   | 0.779      | -            | -                | -                | -         |    -7.10 | AW, h1te, kAlash, sFade8, sm3t |
|           26 |     1508 | 2024-06-01 | ENCE            | W   | 0.779      | 0.143        | 0.170 (0.019)    | -                | 0 (0.000) |    22.34 | AW, h1te, kAlash, sFade8, sm3t |
|           25 |     1529 | 2024-05-31 | Spirit Academy  | W   | 0.773      | -            | -                | -                | 0 (0.000) |     6.19 | AW, h1te, kAlash, sFade8, sm3t |
|           24 |     1560 | 2024-05-30 | Nemiga          | W   | 0.766      | 0.372        | 0.318 (0.091)    | 0.719 (0.205)    | 0 (0.000) |    18.64 | AW, h1te, kAlash, sFade8, sm3t |
|           23 |     1578 | 2024-05-29 | Verdant         | W   | 0.760      | 0.372        | 0.015 (0.004)    | 0.310 (0.088)    | 0 (0.000) |    12.05 | AW, h1te, kAlash, sFade8, sm3t |
|           22 |     1650 | 2024-05-26 | GUN5            | L   | 0.738      | -            | -                | -                | -         |   -10.85 | AW, h1te, kAlash, sFade8, sm3t |
|           21 |     1679 | 2024-05-24 | VP.Prodigy      | L   | 0.726      | -            | -                | -                | -         |   -12.22 | AW, h1te, kAlash, sFade8, sm3t |
|           20 |     1688 | 2024-05-24 | BetBoom         | L   | 0.724      | -            | -                | -                | -         |    -1.67 | AW, h1te, kAlash, sFade8, sm3t |
|           19 |     1698 | 2024-05-23 | B8              | L   | 0.719      | -            | -                | -                | -         |    -5.17 | AW, h1te, kAlash, sFade8, sm3t |
|           18 |     1777 | 2024-05-21 | EYEBALLERS      | W   | 0.706      | 0.435        | -                | 0.528 (0.162)    | 0 (0.000) |     9.81 | AW, h1te, kAlash, sFade8, sm3t |
|           17 |     1781 | 2024-05-21 | MOUZ NXT        | W   | 0.705      | 0.435        | 0.139 (0.043)    | 1.000 (0.307)    | 0 (0.000) |    15.02 | AW, h1te, kAlash, sFade8, sm3t |
|           16 |     1835 | 2024-05-19 | Space           | L   | 0.693      | -            | -                | -                | -         |   -12.92 | AW, h1te, kAlash, sFade8, sm3t |
|           15 |     1865 | 2024-05-18 | 777             | W   | 0.686      | -            | -                | -                | -         |     5.48 | AW, h1te, kAlash, sFade8, sm3t |
|           14 |     1877 | 2024-05-18 | Sampi           | W   | 0.685      | 0.435        | 0.028 (0.008)    | 1.000 (0.298)    | -         |    10.96 | AW, h1te, kAlash, sFade8, sm3t |
|           13 |     1915 | 2024-05-17 | MOUZ NXT        | L   | 0.678      | -            | -                | -                | -         |    -6.71 | AW, h1te, kAlash, sFade8, sm3t |
|           12 |     1936 | 2024-05-16 | B8              | L   | 0.673      | -            | -                | -                | -         |    -5.43 | AW, h1te, kAlash, sFade8, sm3t |
|           11 |     1988 | 2024-05-15 | Monte           | L   | 0.666      | -            | -                | -                | -         |    -8.66 | AW, h1te, kAlash, sFade8, sm3t |
|           10 |     2048 | 2024-05-14 | Rare Atom       | W   | 0.659      | 0.143        | -                | 0.495 (0.047)    | -         |     5.08 | AW, h1te, kAlash, sFade8, sm3t |
|            9 |     2059 | 2024-05-14 | Sangal          | W   | 0.658      | 0.435        | 0.219 (0.063)    | 0.823 (0.235)    | -         |    15.46 | AW, h1te, kAlash, sFade8, sm3t |
|            8 |     2075 | 2024-05-13 | Heimo           | W   | 0.652      | -            | -                | -                | -         |     5.09 | AW, h1te, kAlash, sFade8, sm3t |
|            7 |     2128 | 2024-05-11 | CYBERSHOKE      | W   | 0.639      | -            | -                | -                | -         |    10.12 | AW, h1te, kAlash, sFade8, sm3t |
|            6 |     2393 | 2024-04-28 | Alliance        | L   | 0.552      | -            | -                | -                | -         |    -9.48 | AW, h1te, kAlash, sFade8, sm3t |
|            5 |     2441 | 2024-04-26 | BLEED           | L   | 0.539      | -            | -                | -                | -         |    -4.91 | AW, h1te, kAlash, sFade8, sm3t |
|            4 |     2646 | 2024-04-18 | Apeks           | L   | 0.487      | -            | -                | -                | -         |    -7.08 | AW, h1te, kAlash, sFade8, sm3t |
|            3 |     2656 | 2024-04-18 | EYEBALLERS      | W   | 0.486      | -            | -                | -                | -         |     7.16 | AW, h1te, kAlash, sFade8, sm3t |
|            2 |     3835 | 2024-02-27 | kONO            | L   | 0.147      | -            | -                | -                | -         |    -2.93 | AW, h1te, kAlash, sFade8, sm3t |
|            1 |     3839 | 2024-02-27 | B8              | W   | 0.147      | -            | -                | -                | -         |     3.40 | AW, h1te, kAlash, sFade8, sm3t |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,050.58)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
