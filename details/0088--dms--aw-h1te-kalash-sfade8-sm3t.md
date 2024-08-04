### Roster Details<br />
Team Name: DMS<br />
Roster: AW, h1te, kAlash, sFade8, sm3t<br />
Global Rank: [88](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  906.0<br />
<br />
Final Rank Value (906.0) = Starting Rank Value (902.9) + Head To Head Adjustments (3.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.400[<sup>2</sup>](#table1)
- Opponent Network: 0.183[<sup>2</sup>](#table1)
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
|           43 |      335 | 2024-07-26 | AMKAL           | L   | 1.000      | -            | -                | -                | -         |    -4.96 | AW, h1te, kAlash, sFade8, sm3t |
|           42 |      339 | 2024-07-26 | Revenant        | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.267 (0.174)    | 1 (1.000) |    13.92 | AW, h1te, kAlash, sFade8, sm3t |
|           41 |      377 | 2024-07-25 | 3DMAX           | L   | 1.000      | -            | -                | -                | -         |    -2.17 | AW, h1te, kAlash, sFade8, sm3t |
|           40 |      401 | 2024-07-24 | Eternal Fire    | L   | 1.000      | -            | -                | -                | -         |    -0.53 | AW, h1te, kAlash, sFade8, sm3t |
|           39 |      548 | 2024-07-19 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -12.52 | AW, h1te, kAlash, sFade8, sm3t |
|           38 |      595 | 2024-07-18 | Space           | L   | 1.000      | -            | -                | -                | -         |   -16.49 | AW, h1te, kAlash, sFade8, sm3t |
|           37 |      725 | 2024-07-16 | ALTERNATE aTTaX | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.560 (0.243)    | 0 (0.000) |    13.24 | AW, h1te, kAlash, sFade8, sm3t |
|           36 |     1130 | 2024-06-12 | Verdant         | L   | 0.847      | -            | -                | -                | -         |   -14.72 | AW, h1te, kAlash, sFade8, sm3t |
|           35 |     1153 | 2024-06-11 | Zero Tenacity   | L   | 0.840      | -            | -                | -                | -         |    -7.86 | AW, h1te, kAlash, sFade8, sm3t |
|           34 |     1331 | 2024-06-07 | Zero Tenacity   | L   | 0.814      | -            | -                | -                | -         |    -7.88 | AW, h1te, kAlash, sFade8, sm3t |
|           33 |     1435 | 2024-06-06 | CYBERSHOKE      | L   | 0.805      | -            | -                | -                | -         |   -15.97 | AW, h1te, kAlash, sFade8, sm3t |
|           32 |     1531 | 2024-06-04 | Sampi           | L   | 0.791      | -            | -                | -                | -         |   -14.70 | AW, h1te, kAlash, sFade8, sm3t |
|           31 |     1549 | 2024-06-03 | ARCRED          | L   | 0.786      | -            | -                | -                | -         |   -15.28 | AW, h1te, kAlash, sFade8, sm3t |
|           30 |     1558 | 2024-06-02 | Zero Tenacity   | L   | 0.781      | -            | -                | -                | -         |    -7.94 | AW, h1te, kAlash, sFade8, sm3t |
|           29 |     1570 | 2024-06-02 | fnatic          | W   | 0.779      | 0.143        | 0.371 (0.041)    | 0.708 (0.079)    | 0 (0.000) |    22.94 | AW, h1te, kAlash, sFade8, sm3t |
|           28 |     1588 | 2024-06-01 | ENCE            | W   | 0.774      | 0.143        | 0.169 (0.019)    | -                | 0 (0.000) |    21.97 | AW, h1te, kAlash, sFade8, sm3t |
|           27 |     1601 | 2024-06-01 | Zero Tenacity   | L   | 0.773      | -            | -                | -                | -         |    -6.92 | AW, h1te, kAlash, sFade8, sm3t |
|           26 |     1607 | 2024-06-01 | ENCE            | W   | 0.772      | 0.143        | 0.169 (0.019)    | -                | 0 (0.000) |    22.30 | AW, h1te, kAlash, sFade8, sm3t |
|           25 |     1628 | 2024-05-31 | Spirit Academy  | W   | 0.767      | -            | -                | -                | 0 (0.000) |     6.11 | AW, h1te, kAlash, sFade8, sm3t |
|           24 |     1659 | 2024-05-30 | Nemiga          | W   | 0.759      | 0.372        | 0.317 (0.090)    | 0.734 (0.207)    | 0 (0.000) |    18.83 | AW, h1te, kAlash, sFade8, sm3t |
|           23 |     1677 | 2024-05-29 | Verdant         | W   | 0.754      | 0.372        | 0.015 (0.004)    | 0.299 (0.084)    | 0 (0.000) |    11.94 | AW, h1te, kAlash, sFade8, sm3t |
|           22 |     1750 | 2024-05-26 | GUN5            | L   | 0.731      | -            | -                | -                | -         |   -10.83 | AW, h1te, kAlash, sFade8, sm3t |
|           21 |     1779 | 2024-05-24 | VP.Prodigy      | L   | 0.720      | -            | -                | -                | -         |   -12.13 | AW, h1te, kAlash, sFade8, sm3t |
|           20 |     1788 | 2024-05-24 | BetBoom         | L   | 0.718      | -            | -                | -                | -         |    -1.65 | AW, h1te, kAlash, sFade8, sm3t |
|           19 |     1798 | 2024-05-23 | B8              | L   | 0.712      | -            | -                | -                | -         |    -5.08 | AW, h1te, kAlash, sFade8, sm3t |
|           18 |     1877 | 2024-05-21 | EYEBALLERS      | W   | 0.700      | 0.435        | -                | 0.509 (0.155)    | 0 (0.000) |     9.60 | AW, h1te, kAlash, sFade8, sm3t |
|           17 |     1881 | 2024-05-21 | MOUZ NXT        | W   | 0.699      | 0.435        | 0.139 (0.042)    | 1.000 (0.304)    | 0 (0.000) |    14.98 | AW, h1te, kAlash, sFade8, sm3t |
|           16 |     1936 | 2024-05-19 | Space           | L   | 0.687      | -            | -                | -                | -         |   -12.97 | AW, h1te, kAlash, sFade8, sm3t |
|           15 |     1966 | 2024-05-18 | 777             | W   | 0.680      | -            | -                | -                | -         |     5.51 | AW, h1te, kAlash, sFade8, sm3t |
|           14 |     1978 | 2024-05-18 | Sampi           | W   | 0.678      | 0.435        | 0.027 (0.008)    | 1.000 (0.295)    | -         |    10.79 | AW, h1te, kAlash, sFade8, sm3t |
|           13 |     2016 | 2024-05-17 | MOUZ NXT        | L   | 0.671      | -            | -                | -                | -         |    -6.55 | AW, h1te, kAlash, sFade8, sm3t |
|           12 |     2037 | 2024-05-16 | B8              | L   | 0.667      | -            | -                | -                | -         |    -5.33 | AW, h1te, kAlash, sFade8, sm3t |
|           11 |     2089 | 2024-05-15 | Monte           | L   | 0.660      | -            | -                | -                | -         |    -8.28 | AW, h1te, kAlash, sFade8, sm3t |
|           10 |     2149 | 2024-05-14 | Rare Atom       | W   | 0.653      | 0.143        | -                | 0.480 (0.045)    | -         |     5.10 | AW, h1te, kAlash, sFade8, sm3t |
|            9 |     2160 | 2024-05-14 | Sangal          | W   | 0.651      | 0.435        | 0.219 (0.062)    | 0.861 (0.244)    | -         |    15.44 | AW, h1te, kAlash, sFade8, sm3t |
|            8 |     2176 | 2024-05-13 | Heimo           | W   | 0.646      | -            | -                | -                | -         |     5.00 | AW, h1te, kAlash, sFade8, sm3t |
|            7 |     2229 | 2024-05-11 | CYBERSHOKE      | W   | 0.633      | -            | -                | -                | -         |     9.98 | AW, h1te, kAlash, sFade8, sm3t |
|            6 |     2495 | 2024-04-28 | Alliance        | L   | 0.546      | -            | -                | -                | -         |    -9.42 | AW, h1te, kAlash, sFade8, sm3t |
|            5 |     2544 | 2024-04-26 | BLEED           | L   | 0.532      | -            | -                | -                | -         |    -4.84 | AW, h1te, kAlash, sFade8, sm3t |
|            4 |     2749 | 2024-04-18 | Apeks           | L   | 0.480      | -            | -                | -                | -         |    -6.95 | AW, h1te, kAlash, sFade8, sm3t |
|            3 |     2759 | 2024-04-18 | EYEBALLERS      | W   | 0.480      | -            | -                | -                | -         |     7.05 | AW, h1te, kAlash, sFade8, sm3t |
|            2 |     3946 | 2024-02-27 | kONO            | L   | 0.141      | -            | -                | -                | -         |    -2.80 | AW, h1te, kAlash, sFade8, sm3t |
|            1 |     3950 | 2024-02-27 | B8              | W   | 0.140      | -            | -                | -                | -         |     3.23 | AW, h1te, kAlash, sFade8, sm3t |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,042.39)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
