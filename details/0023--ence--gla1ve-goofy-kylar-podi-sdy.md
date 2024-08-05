### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1357.5<br />
<br />
Final Rank Value (1357.5) = Starting Rank Value (1474.1) + Head To Head Adjustments (-116.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.564[<sup>1</sup>](#table2)
- Bounty Collected: 0.463[<sup>2</sup>](#table1)
- Opponent Network: 0.269[<sup>2</sup>](#table1)
- LAN Wins: 0.804[<sup>2</sup>](#table1)

The average of these factors is 0.525<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1474.1
- 400 + ( ( 0.525 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1474.1


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
|           45 |        2 | 2024-08-04 | 9INE               | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.539 (0.234)    | -         |     2.67 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      303 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.47 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      330 | 2024-07-26 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.81 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      370 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.534 (0.347)    | 1 (1.000) |     5.50 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      380 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -12.29 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      397 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.84 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |      410 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.518 (0.337)    | 1 (1.000) |    12.78 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |     1010 | 2024-06-16 | Falcons            | L   | 0.870      | -            | -                | -                | -         |   -11.22 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |     1074 | 2024-06-14 | Complexity         | W   | 0.857      | 0.500        | 0.342 (0.147)    | 0.380 (0.163)    | 1 (0.857) |    21.49 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1083 | 2024-06-14 | MIBR               | W   | 0.857      | 0.500        | 0.209 (0.089)    | 0.659 (0.282)    | 1 (0.857) |    15.75 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1416 | 2024-06-06 | HEROIC             | L   | 0.804      | -            | -                | -                | -         |    -5.89 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1427 | 2024-06-06 | Astralis           | L   | 0.803      | -            | -                | -                | -         |    -2.99 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1463 | 2024-06-05 | Sashi              | W   | 0.798      | 0.715        | 0.184 (0.105)    | 0.961 (0.549)    | 1 (0.798) |     8.04 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1476 | 2024-06-05 | The MongolZ        | L   | 0.797      | -            | -                | -                | -         |    -1.07 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1485 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.796      | -            | -                | -                | -         |    -5.99 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1592 | 2024-06-01 | DMS                | L   | 0.771      | -            | -                | -                | -         |   -21.96 | gla1ve, Goofy, Kylar, podi, sdy    |
|           29 |     1601 | 2024-06-01 | KOI                | W   | 0.771      | -            | -                | -                | -         |     3.38 | gla1ve, Goofy, Kylar, podi, sdy    |
|           28 |     1611 | 2024-06-01 | DMS                | L   | 0.770      | -            | -                | -                | -         |   -22.29 | gla1ve, Goofy, Kylar, podi, sdy    |
|           27 |     1890 | 2024-05-21 | Liquid             | L   | 0.696      | -            | -                | -                | -         |    -5.45 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     1976 | 2024-05-18 | fnatic             | W   | 0.677      | 0.769        | 0.371 (0.193)    | 0.708 (0.368)    | -         |    13.16 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     1999 | 2024-05-17 | Gaimin Gladiators  | W   | 0.672      | 0.769        | 0.038 (0.019)    | 0.349 (0.180)    | -         |     2.20 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2010 | 2024-05-17 | fnatic             | L   | 0.670      | -            | -                | -                | -         |    -7.54 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2368 | 2024-05-04 | FURIA              | L   | 0.584      | -            | -                | -                | -         |    -3.77 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2382 | 2024-05-03 | GamerLegion        | L   | 0.577      | -            | -                | -                | -         |   -14.82 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2402 | 2024-05-02 | Monte              | W   | 0.571      | 0.889        | 0.057 (0.029)    | -                | 1 (0.571) |     1.68 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2430 | 2024-05-01 | Bad News Kangaroos | W   | 0.564      | 0.889        | 0.017 (0.008)    | 0.226 (0.113)    | 1 (0.564) |     0.58 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2461 | 2024-04-30 | GamerLegion        | L   | 0.556      | -            | -                | -                | -         |   -14.73 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     2722 | 2024-04-19 | AMKAL              | L   | 0.484      | -            | -                | -                | -         |   -12.78 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     2809 | 2024-04-17 | Enterprise         | W   | 0.470      | 0.384        | -                | 0.625 (0.113)    | -         |     0.79 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     2980 | 2024-04-10 | OG                 | L   | 0.423      | -            | -                | -                | -         |   -12.26 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3065 | 2024-04-08 | FORZE              | L   | 0.410      | -            | -                | -                | -         |   -12.30 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3173 | 2024-04-04 | Aurora Young Blud  | W   | 0.383      | -            | -                | -                | -         |     0.37 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3467 | 2024-03-19 | FURIA              | L   | 0.278      | -            | -                | -                | -         |    -1.73 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3483 | 2024-03-18 | paiN               | L   | 0.270      | -            | -                | -                | -         |    -4.89 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3490 | 2024-03-17 | KOI                | W   | 0.265      | -            | -                | -                | 1 (0.265) |     0.90 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3510 | 2024-03-17 | Imperial           | L   | 0.263      | -            | -                | -                | -         |    -6.28 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     3641 | 2024-03-12 | B8                 | L   | 0.230      | -            | -                | -                | -         |    -6.50 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     3654 | 2024-03-11 | HEROIC             | L   | 0.225      | -            | -                | -                | -         |    -2.74 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     3664 | 2024-03-11 | Metizport          | W   | 0.224      | -            | -                | -                | -         |     0.20 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     4066 | 2024-02-22 | Astralis           | W   | 0.103      | -            | -                | -                | 1 (0.103) |     2.61 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4088 | 2024-02-21 | Vitality           | L   | 0.097      | -            | -                | -                | -         |    -0.33 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4121 | 2024-02-20 | GamerLegion        | W   | 0.090      | -            | -                | -                | -         |     0.06 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4141 | 2024-02-19 | ex-Guild Eagles    | W   | 0.084      | -            | -                | -                | -         |     0.06 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4149 | 2024-02-19 | Spirit             | L   | 0.083      | -            | -                | -                | -         |    -0.21 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4354 | 2024-02-09 | Falcons            | L   | 0.018      | -            | -                | -                | -         |    -0.33 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($54,466.60)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.870 | $10,000.00     | $8,702.78       |
| 2024-06-09 |      0.824 | $8,000.00      | $6,591.11       |
| 2024-05-23 |      0.710 | $12,500.00     | $8,876.74       |
| 2024-05-12 |      0.637 | $7,000.00      | $4,460.56       |
| 2024-04-14 |      0.450 | $15,000.00     | $6,756.25       |
| 2024-03-20 |      0.285 | $10,000.00     | $2,845.83       |
| 2024-02-11 |      0.031 | $40,000.00     | $1,233.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
