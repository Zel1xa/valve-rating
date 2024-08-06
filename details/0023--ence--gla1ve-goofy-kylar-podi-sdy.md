### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1336.4<br />
<br />
Final Rank Value (1336.4) = Starting Rank Value (1478.5) + Head To Head Adjustments (-142.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.266[<sup>2</sup>](#table1)
- LAN Wins: 0.802[<sup>2</sup>](#table1)

The average of these factors is 0.524<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1478.5
- 400 + ( ( 0.524 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1478.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |       29 | 2024-08-05 | PARIVISION         | L   | 1.000      | -            | -                | -                | -         |   -25.58 | gla1ve, Goofy, Kylar, podi, sdy    |
|           45 |       42 | 2024-08-04 | 9INE               | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.523 (0.227)    | -         |     2.69 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      344 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.34 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      371 | 2024-07-26 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      411 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.590 (0.384)    | 1 (1.000) |     5.57 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      421 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -12.14 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      438 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.90 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |      451 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.538 (0.350)    | 1 (1.000) |    12.87 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |     1051 | 2024-06-16 | Falcons            | L   | 0.859      | -            | -                | -                | -         |   -11.36 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |     1115 | 2024-06-14 | Complexity         | W   | 0.847      | 0.500        | 0.341 (0.144)    | 0.364 (0.154)    | 1 (0.847) |    21.07 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1124 | 2024-06-14 | MIBR               | W   | 0.846      | 0.500        | 0.208 (0.088)    | 0.633 (0.268)    | 1 (0.846) |    15.22 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1457 | 2024-06-06 | HEROIC             | L   | 0.794      | -            | -                | -                | -         |    -6.03 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1468 | 2024-06-06 | Astralis           | L   | 0.793      | -            | -                | -                | -         |    -3.07 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1504 | 2024-06-05 | Sashi              | W   | 0.788      | 0.715        | 0.184 (0.103)    | 0.958 (0.540)    | 1 (0.788) |     7.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1517 | 2024-06-05 | The MongolZ        | L   | 0.787      | -            | -                | -                | -         |    -1.08 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1526 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.786      | -            | -                | -                | -         |    -6.04 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1633 | 2024-06-01 | DMS                | L   | 0.761      | -            | -                | -                | -         |   -21.70 | gla1ve, Goofy, Kylar, podi, sdy    |
|           29 |     1642 | 2024-06-01 | KOI                | W   | 0.760      | -            | -                | -                | -         |     3.21 | gla1ve, Goofy, Kylar, podi, sdy    |
|           28 |     1652 | 2024-06-01 | DMS                | L   | 0.759      | -            | -                | -                | -         |   -22.01 | gla1ve, Goofy, Kylar, podi, sdy    |
|           27 |     1931 | 2024-05-21 | Liquid             | L   | 0.685      | -            | -                | -                | -         |    -5.51 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     2017 | 2024-05-18 | fnatic             | W   | 0.666      | 0.769        | 0.371 (0.190)    | 0.680 (0.348)    | -         |    12.81 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     2040 | 2024-05-17 | Gaimin Gladiators  | W   | 0.662      | 0.769        | 0.037 (0.019)    | 0.331 (0.168)    | -         |     2.07 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2051 | 2024-05-17 | fnatic             | L   | 0.660      | -            | -                | -                | -         |    -7.59 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2409 | 2024-05-04 | FURIA              | L   | 0.573      | -            | -                | -                | -         |    -3.78 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2423 | 2024-05-03 | GamerLegion        | L   | 0.567      | -            | -                | -                | -         |   -14.68 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2443 | 2024-05-02 | Monte              | W   | 0.561      | 0.889        | 0.057 (0.028)    | -                | 1 (0.561) |     1.58 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2471 | 2024-05-01 | Bad News Kangaroos | W   | 0.553      | 0.889        | 0.016 (0.008)    | 0.217 (0.107)    | 1 (0.553) |     0.54 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2502 | 2024-04-30 | GamerLegion        | L   | 0.546      | -            | -                | -                | -         |   -14.56 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     2763 | 2024-04-19 | AMKAL              | L   | 0.473      | -            | -                | -                | -         |   -12.55 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     2850 | 2024-04-17 | Enterprise         | W   | 0.459      | 0.384        | -                | 0.641 (0.113)    | -         |     0.76 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     3021 | 2024-04-10 | OG                 | L   | 0.413      | -            | -                | -                | -         |   -12.00 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3106 | 2024-04-08 | FORZE              | L   | 0.400      | -            | -                | -                | -         |   -12.00 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3214 | 2024-04-04 | Aurora Young Blud  | W   | 0.373      | -            | -                | -                | -         |     0.51 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3508 | 2024-03-19 | FURIA              | L   | 0.267      | -            | -                | -                | -         |    -1.70 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3524 | 2024-03-18 | paiN               | L   | 0.259      | -            | -                | -                | -         |    -4.84 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3531 | 2024-03-17 | KOI                | W   | 0.255      | -            | -                | -                | 1 (0.255) |     0.82 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3551 | 2024-03-17 | Imperial           | L   | 0.253      | -            | -                | -                | -         |    -6.13 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     3682 | 2024-03-12 | B8                 | L   | 0.220      | -            | -                | -                | -         |    -6.21 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     3695 | 2024-03-11 | HEROIC             | L   | 0.214      | -            | -                | -                | -         |    -2.69 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     3705 | 2024-03-11 | Metizport          | W   | 0.213      | -            | -                | -                | -         |     0.27 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     4107 | 2024-02-22 | Astralis           | W   | 0.092      | -            | -                | -                | 1 (0.092) |     2.32 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4129 | 2024-02-21 | Vitality           | L   | 0.087      | -            | -                | -                | -         |    -0.30 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4162 | 2024-02-20 | GamerLegion        | W   | 0.079      | -            | -                | -                | -         |     0.05 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4182 | 2024-02-19 | ex-Guild Eagles    | W   | 0.074      | -            | -                | -                | -         |     0.05 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4190 | 2024-02-19 | Spirit             | L   | 0.072      | -            | -                | -                | -         |    -0.19 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4395 | 2024-02-09 | Falcons            | L   | 0.008      | -            | -                | -                | -         |    -0.14 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,384.65)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.860 | $10,000.00     | $8,597.22       |
| 2024-06-09 |      0.813 | $8,000.00      | $6,506.67       |
| 2024-05-23 |      0.700 | $12,500.00     | $8,744.79       |
| 2024-05-12 |      0.627 | $7,000.00      | $4,386.67       |
| 2024-04-14 |      0.440 | $15,000.00     | $6,597.92       |
| 2024-03-20 |      0.274 | $10,000.00     | $2,740.28       |
| 2024-02-11 |      0.020 | $40,000.00     | $811.11         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
