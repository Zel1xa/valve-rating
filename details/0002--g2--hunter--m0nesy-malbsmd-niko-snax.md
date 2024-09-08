### Roster Details<br />
Team Name: G2<br />
Roster: huNter-, m0NESY, malbsMd, NiKo, Snax<br />
Global Rank: [2](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1942.4<br />
<br />
Final Rank Value (1942.4) = Starting Rank Value (1977.7) + Head To Head Adjustments (-35.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.781[<sup>2</sup>](#table1)
- Opponent Network: 0.484[<sup>2</sup>](#table1)
- LAN Wins: 0.994[<sup>2</sup>](#table1)

The average of these factors is 0.815<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1977.7
- 400 + ( ( 0.815 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1977.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           43 |       83 | 2024-09-05 | 3DMAX             | W   | 1.000      | 0.889        | 0.509 (0.452)    | 0.951 (0.846)    | 1 (1.000) |     1.60 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           42 |      142 | 2024-09-03 | KOI               | W   | 1.000      | 0.889        | -                | 0.317 (0.282)    | 1 (1.000) |     0.11 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           41 |      786 | 2024-08-16 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |   -19.44 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           40 |      879 | 2024-08-13 | paiN              | W   | 1.000      | 1.000        | 0.420 (0.420)    | 0.935 (0.935)    | 1 (1.000) |     3.11 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      924 | 2024-08-12 | Astralis          | W   | 1.000      | 1.000        | 0.343 (0.343)    | 0.317 (0.317)    | 1 (1.000) |     3.21 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      950 | 2024-08-11 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.557 (0.557)    | 1 (1.000) |    14.97 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      976 | 2024-08-10 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -29.88 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           36 |     1199 | 2024-08-03 | Ninjas in Pyjamas | W   | 0.961      | -            | -                | -                | 1 (0.961) |     1.50 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           35 |     1290 | 2024-08-01 | FaZe              | W   | 0.946      | 0.581        | 0.587 (0.322)    | 0.494 (0.271)    | 1 (0.946) |     6.62 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           34 |     1334 | 2024-07-31 | Ninjas in Pyjamas | W   | 0.940      | -            | -                | -                | 1 (0.940) |     1.33 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           33 |     1644 | 2024-07-21 | Natus Vincere     | L   | 0.875      | -            | -                | -                | -         |   -13.25 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           32 |     1689 | 2024-07-20 | Virtus.pro        | W   | 0.867      | 1.000        | 0.520 (0.451)    | 0.288 (0.250)    | 1 (0.867) |     2.57 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           31 |     1756 | 2024-07-18 | Spirit            | W   | 0.855      | 1.000        | 1.000 (0.855)    | 0.557 (0.476)    | 1 (0.855) |    13.60 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           30 |     1856 | 2024-07-17 | The MongolZ       | W   | 0.846      | 1.000        | 0.864 (0.731)    | 0.695 (0.588)    | -         |     7.15 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           29 |     2271 | 2024-06-13 | Vitality          | L   | 0.621      | -            | -                | -                | -         |   -11.43 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           28 |     2727 | 2024-06-02 | Vitality          | W   | 0.548      | 0.624        | 1.000 (0.342)    | -                | -         |     7.69 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           27 |     2749 | 2024-06-01 | 9z                | W   | 0.542      | -            | -                | -                | -         |     0.93 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           26 |     2786 | 2024-05-31 | FaZe              | W   | 0.536      | -            | -                | -                | -         |     4.35 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           25 |     2836 | 2024-05-29 | Liquid            | W   | 0.523      | -            | -                | -                | -         |     1.80 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           24 |     2859 | 2024-05-28 | MOUZ              | W   | 0.516      | 0.624        | 1.000 (0.322)    | -                | -         |     6.59 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           23 |     2883 | 2024-05-27 | Vitality          | L   | 0.509      | -            | -                | -                | -         |    -8.68 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           22 |     2894 | 2024-05-27 | Falcons           | W   | 0.508      | -            | -                | -                | -         |     1.25 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           21 |     3433 | 2024-05-09 | MOUZ              | L   | 0.388      | -            | -                | -                | -         |    -7.66 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     3459 | 2024-05-08 | 3DMAX             | W   | 0.380      | 0.889        | -                | 0.951 (0.322)    | -         |     2.25 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     3477 | 2024-05-07 | BIG               | W   | 0.374      | -            | -                | -                | -         |     0.17 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     3654 | 2024-04-28 | M80               | W   | 0.315      | -            | -                | -                | -         |     0.08 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     3689 | 2024-04-27 | Falcons           | W   | 0.306      | -            | -                | -                | -         |     0.73 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     3712 | 2024-04-26 | M80               | L   | 0.300      | -            | -                | -                | -         |    -9.36 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     3741 | 2024-04-25 | The MongolZ       | L   | 0.293      | -            | -                | -                | -         |    -5.70 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3761 | 2024-04-24 | TYLOO             | W   | 0.286      | -            | -                | -                | -         |     0.01 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     4062 | 2024-04-13 | MOUZ              | L   | 0.212      | -            | -                | -                | -         |    -4.35 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     4075 | 2024-04-12 | Virtus.pro        | W   | 0.205      | -            | -                | -                | -         |     0.47 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     4145 | 2024-04-10 | HEROIC            | W   | 0.193      | -            | -                | -                | -         |     0.24 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     4205 | 2024-04-09 | Lynn Vision       | W   | 0.186      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     4236 | 2024-04-08 | Liquid            | L   | 0.179      | -            | -                | -                | -         |    -5.11 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     4245 | 2024-04-07 | 9z                | W   | 0.178      | -            | -                | -                | -         |     0.34 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     4437 | 2024-03-30 | Natus Vincere     | L   | 0.122      | -            | -                | -                | -         |    -1.79 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     4444 | 2024-03-29 | MOUZ              | W   | 0.115      | -            | -                | -                | -         |     1.23 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     4541 | 2024-03-24 | Virtus.pro        | W   | 0.080      | -            | -                | -                | -         |     0.18 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4553 | 2024-03-23 | Gaimin Gladiators | W   | 0.074      | -            | -                | -                | -         |     0.01 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4571 | 2024-03-22 | Cloud9            | L   | 0.066      | -            | -                | -                | -         |    -2.09 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4581 | 2024-03-21 | Natus Vincere     | L   | 0.062      | -            | -                | -                | -         |    -0.91 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4590 | 2024-03-21 | FURIA             | W   | 0.061      | -            | -                | -                | -         |     0.25 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($303,706.75)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-18 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-08-04 |      0.967 | $22,500.00     | $21,759.90      |
| 2024-07-21 |      0.875 | $175,000.00    | $153,076.39     |
| 2024-06-16 |      0.640 | $10,000.00     | $6,402.78       |
| 2024-06-02 |      0.548 | $100,000.00    | $54,805.56      |
| 2024-05-12 |      0.407 | $32,000.00     | $13,031.11      |
| 2024-04-14 |      0.219 | $20,000.00     | $4,386.57       |
| 2024-03-31 |      0.128 | $80,000.00     | $10,244.44      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
