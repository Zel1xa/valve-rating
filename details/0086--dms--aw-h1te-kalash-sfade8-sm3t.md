### Roster Details<br />
Team Name: DMS<br />
Roster: AW, h1te, kAlash, sFade8, sm3t<br />
Global Rank: [86](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  904.6<br />
<br />
Final Rank Value (904.6) = Starting Rank Value (902.5) + Head To Head Adjustments (2.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.400[<sup>2</sup>](#table1)
- Opponent Network: 0.183[<sup>2</sup>](#table1)
- LAN Wins: 0.114[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 902.5
- 400 + ( ( 0.246 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 902.5


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
|           43 |      300 | 2024-07-26 | AMKAL           | L   | 1.000      | -            | -                | -                | -         |    -4.93 | AW, h1te, kAlash, sFade8, sm3t |
|           42 |      304 | 2024-07-26 | Revenant        | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.266 (0.173)    | 1 (1.000) |    13.94 | AW, h1te, kAlash, sFade8, sm3t |
|           41 |      342 | 2024-07-25 | 3DMAX           | L   | 1.000      | -            | -                | -                | -         |    -2.20 | AW, h1te, kAlash, sFade8, sm3t |
|           40 |      366 | 2024-07-24 | Eternal Fire    | L   | 1.000      | -            | -                | -                | -         |    -0.54 | AW, h1te, kAlash, sFade8, sm3t |
|           39 |      513 | 2024-07-19 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -13.35 | AW, h1te, kAlash, sFade8, sm3t |
|           38 |      563 | 2024-07-18 | Space           | L   | 1.000      | -            | -                | -                | -         |   -16.22 | AW, h1te, kAlash, sFade8, sm3t |
|           37 |      693 | 2024-07-16 | ALTERNATE aTTaX | W   | 1.000      | 0.435        | 0.032 (0.014)    | 0.561 (0.244)    | 0 (0.000) |    13.05 | AW, h1te, kAlash, sFade8, sm3t |
|           36 |     1094 | 2024-06-12 | Verdant         | L   | 0.852      | -            | -                | -                | -         |   -14.83 | AW, h1te, kAlash, sFade8, sm3t |
|           35 |     1117 | 2024-06-11 | Zero Tenacity   | L   | 0.845      | -            | -                | -                | -         |    -7.91 | AW, h1te, kAlash, sFade8, sm3t |
|           34 |     1295 | 2024-06-07 | Zero Tenacity   | L   | 0.819      | -            | -                | -                | -         |    -7.91 | AW, h1te, kAlash, sFade8, sm3t |
|           33 |     1399 | 2024-06-06 | CYBERSHOKE      | L   | 0.809      | -            | -                | -                | -         |   -16.12 | AW, h1te, kAlash, sFade8, sm3t |
|           32 |     1495 | 2024-06-04 | Sampi           | L   | 0.796      | -            | -                | -                | -         |   -14.85 | AW, h1te, kAlash, sFade8, sm3t |
|           31 |     1513 | 2024-06-03 | ARCRED          | L   | 0.791      | -            | -                | -                | -         |   -15.36 | AW, h1te, kAlash, sFade8, sm3t |
|           30 |     1522 | 2024-06-02 | Zero Tenacity   | L   | 0.785      | -            | -                | -                | -         |    -7.96 | AW, h1te, kAlash, sFade8, sm3t |
|           29 |     1534 | 2024-06-02 | fnatic          | W   | 0.784      | 0.143        | 0.371 (0.041)    | 0.709 (0.079)    | 0 (0.000) |    23.07 | AW, h1te, kAlash, sFade8, sm3t |
|           28 |     1552 | 2024-06-01 | ENCE            | W   | 0.779      | 0.143        | 0.170 (0.019)    | -                | 0 (0.000) |    22.06 | AW, h1te, kAlash, sFade8, sm3t |
|           27 |     1565 | 2024-06-01 | Zero Tenacity   | L   | 0.778      | -            | -                | -                | -         |    -6.94 | AW, h1te, kAlash, sFade8, sm3t |
|           26 |     1571 | 2024-06-01 | ENCE            | W   | 0.777      | 0.143        | 0.170 (0.019)    | -                | 0 (0.000) |    22.40 | AW, h1te, kAlash, sFade8, sm3t |
|           25 |     1592 | 2024-05-31 | Spirit Academy  | W   | 0.772      | -            | -                | -                | 0 (0.000) |     6.16 | AW, h1te, kAlash, sFade8, sm3t |
|           24 |     1623 | 2024-05-30 | Nemiga          | W   | 0.764      | 0.372        | 0.318 (0.090)    | 0.695 (0.198)    | 0 (0.000) |    18.58 | AW, h1te, kAlash, sFade8, sm3t |
|           23 |     1641 | 2024-05-29 | Verdant         | W   | 0.759      | 0.372        | 0.015 (0.004)    | 0.299 (0.085)    | 0 (0.000) |    12.00 | AW, h1te, kAlash, sFade8, sm3t |
|           22 |     1714 | 2024-05-26 | GUN5            | L   | 0.736      | -            | -                | -                | -         |   -10.93 | AW, h1te, kAlash, sFade8, sm3t |
|           21 |     1743 | 2024-05-24 | VP.Prodigy      | L   | 0.724      | -            | -                | -                | -         |   -12.25 | AW, h1te, kAlash, sFade8, sm3t |
|           20 |     1752 | 2024-05-24 | BetBoom         | L   | 0.723      | -            | -                | -                | -         |    -1.65 | AW, h1te, kAlash, sFade8, sm3t |
|           19 |     1762 | 2024-05-23 | B8              | L   | 0.717      | -            | -                | -                | -         |    -5.12 | AW, h1te, kAlash, sFade8, sm3t |
|           18 |     1841 | 2024-05-21 | EYEBALLERS      | W   | 0.705      | 0.435        | -                | 0.510 (0.156)    | 0 (0.000) |     9.79 | AW, h1te, kAlash, sFade8, sm3t |
|           17 |     1845 | 2024-05-21 | MOUZ NXT        | W   | 0.704      | 0.435        | 0.139 (0.043)    | 1.000 (0.306)    | 0 (0.000) |    15.04 | AW, h1te, kAlash, sFade8, sm3t |
|           16 |     1900 | 2024-05-19 | Space           | L   | 0.691      | -            | -                | -                | -         |   -12.97 | AW, h1te, kAlash, sFade8, sm3t |
|           15 |     1930 | 2024-05-18 | 777             | W   | 0.685      | -            | -                | -                | -         |     5.56 | AW, h1te, kAlash, sFade8, sm3t |
|           14 |     1942 | 2024-05-18 | Sampi           | W   | 0.683      | 0.435        | 0.027 (0.008)    | 1.000 (0.297)    | -         |    10.86 | AW, h1te, kAlash, sFade8, sm3t |
|           13 |     1980 | 2024-05-17 | MOUZ NXT        | L   | 0.676      | -            | -                | -                | -         |    -6.63 | AW, h1te, kAlash, sFade8, sm3t |
|           12 |     2001 | 2024-05-16 | B8              | L   | 0.672      | -            | -                | -                | -         |    -5.37 | AW, h1te, kAlash, sFade8, sm3t |
|           11 |     2053 | 2024-05-15 | Monte           | L   | 0.664      | -            | -                | -                | -         |    -8.33 | AW, h1te, kAlash, sFade8, sm3t |
|           10 |     2113 | 2024-05-14 | Rare Atom       | W   | 0.658      | 0.143        | -                | 0.479 (0.045)    | -         |     5.11 | AW, h1te, kAlash, sFade8, sm3t |
|            9 |     2124 | 2024-05-14 | Sangal          | W   | 0.656      | 0.435        | 0.219 (0.062)    | 0.862 (0.246)    | -         |    15.46 | AW, h1te, kAlash, sFade8, sm3t |
|            8 |     2140 | 2024-05-13 | Heimo           | W   | 0.650      | -            | -                | -                | -         |     5.04 | AW, h1te, kAlash, sFade8, sm3t |
|            7 |     2193 | 2024-05-11 | CYBERSHOKE      | W   | 0.637      | -            | -                | -                | -         |    10.01 | AW, h1te, kAlash, sFade8, sm3t |
|            6 |     2459 | 2024-04-28 | Alliance        | L   | 0.550      | -            | -                | -                | -         |    -9.48 | AW, h1te, kAlash, sFade8, sm3t |
|            5 |     2507 | 2024-04-26 | BLEED           | L   | 0.537      | -            | -                | -                | -         |    -4.88 | AW, h1te, kAlash, sFade8, sm3t |
|            4 |     2712 | 2024-04-18 | Apeks           | L   | 0.485      | -            | -                | -                | -         |    -6.95 | AW, h1te, kAlash, sFade8, sm3t |
|            3 |     2722 | 2024-04-18 | EYEBALLERS      | W   | 0.485      | -            | -                | -                | -         |     7.15 | AW, h1te, kAlash, sFade8, sm3t |
|            2 |     3908 | 2024-02-27 | kONO            | L   | 0.145      | -            | -                | -                | -         |    -2.90 | AW, h1te, kAlash, sFade8, sm3t |
|            1 |     3912 | 2024-02-27 | B8              | W   | 0.145      | -            | -                | -                | -         |     3.35 | AW, h1te, kAlash, sFade8, sm3t |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,048.44)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
