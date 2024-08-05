### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1358.3<br />
<br />
Final Rank Value (1358.3) = Starting Rank Value (1474.4) + Head To Head Adjustments (-116.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.563[<sup>1</sup>](#table2)
- Bounty Collected: 0.463[<sup>2</sup>](#table1)
- Opponent Network: 0.269[<sup>2</sup>](#table1)
- LAN Wins: 0.804[<sup>2</sup>](#table1)

The average of these factors is 0.525<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1474.4
- 400 + ( ( 0.525 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1474.4


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
|           45 |       14 | 2024-08-04 | 9INE               | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.539 (0.234)    | -         |     2.67 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      316 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.40 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      343 | 2024-07-26 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.80 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      383 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.532 (0.346)    | 1 (1.000) |     5.52 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      393 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -12.27 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      410 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.83 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |      423 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.517 (0.336)    | 1 (1.000) |    12.84 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |     1023 | 2024-06-16 | Falcons            | L   | 0.866      | -            | -                | -                | -         |   -11.25 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |     1087 | 2024-06-14 | Complexity         | W   | 0.854      | 0.500        | 0.342 (0.146)    | 0.378 (0.161)    | 1 (0.854) |    21.38 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1096 | 2024-06-14 | MIBR               | W   | 0.853      | 0.500        | 0.208 (0.089)    | 0.657 (0.280)    | 1 (0.853) |    15.63 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1429 | 2024-06-06 | HEROIC             | L   | 0.801      | -            | -                | -                | -         |    -5.90 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1440 | 2024-06-06 | Astralis           | L   | 0.800      | -            | -                | -                | -         |    -3.00 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1476 | 2024-06-05 | Sashi              | W   | 0.795      | 0.715        | 0.184 (0.105)    | 0.996 (0.566)    | 1 (0.795) |     7.97 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1489 | 2024-06-05 | The MongolZ        | L   | 0.794      | -            | -                | -                | -         |    -1.06 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1498 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.793      | -            | -                | -                | -         |    -5.95 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1605 | 2024-06-01 | DMS                | L   | 0.768      | -            | -                | -                | -         |   -21.85 | gla1ve, Goofy, Kylar, podi, sdy    |
|           29 |     1614 | 2024-06-01 | KOI                | W   | 0.767      | -            | -                | -                | -         |     3.34 | gla1ve, Goofy, Kylar, podi, sdy    |
|           28 |     1624 | 2024-06-01 | DMS                | L   | 0.766      | -            | -                | -                | -         |   -22.17 | gla1ve, Goofy, Kylar, podi, sdy    |
|           27 |     1903 | 2024-05-21 | Liquid             | L   | 0.693      | -            | -                | -                | -         |    -5.45 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     1989 | 2024-05-18 | fnatic             | W   | 0.673      | 0.769        | 0.371 (0.192)    | 0.706 (0.365)    | -         |    13.09 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     2012 | 2024-05-17 | Gaimin Gladiators  | W   | 0.669      | 0.769        | 0.037 (0.019)    | 0.346 (0.178)    | -         |     2.16 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2023 | 2024-05-17 | fnatic             | L   | 0.667      | -            | -                | -                | -         |    -7.51 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2381 | 2024-05-04 | FURIA              | L   | 0.580      | -            | -                | -                | -         |    -3.73 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2395 | 2024-05-03 | GamerLegion        | L   | 0.574      | -            | -                | -                | -         |   -14.76 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2415 | 2024-05-02 | Monte              | W   | 0.568      | 0.889        | 0.057 (0.029)    | -                | 1 (0.568) |     1.65 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2443 | 2024-05-01 | Bad News Kangaroos | W   | 0.560      | 0.889        | 0.017 (0.008)    | 0.225 (0.112)    | 1 (0.560) |     0.57 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2474 | 2024-04-30 | GamerLegion        | L   | 0.553      | -            | -                | -                | -         |   -14.66 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     2735 | 2024-04-19 | AMKAL              | L   | 0.480      | -            | -                | -                | -         |   -12.71 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     2822 | 2024-04-17 | Enterprise         | W   | 0.467      | 0.384        | -                | 0.624 (0.112)    | -         |     0.78 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     2993 | 2024-04-10 | OG                 | L   | 0.420      | -            | -                | -                | -         |   -12.18 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3078 | 2024-04-08 | FORZE              | L   | 0.407      | -            | -                | -                | -         |   -12.20 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3186 | 2024-04-04 | Aurora Young Blud  | W   | 0.380      | -            | -                | -                | -         |     0.37 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3480 | 2024-03-19 | FURIA              | L   | 0.275      | -            | -                | -                | -         |    -1.70 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3496 | 2024-03-18 | paiN               | L   | 0.266      | -            | -                | -                | -         |    -4.86 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3503 | 2024-03-17 | KOI                | W   | 0.262      | -            | -                | -                | 1 (0.262) |     0.88 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3523 | 2024-03-17 | Imperial           | L   | 0.260      | -            | -                | -                | -         |    -6.22 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     3654 | 2024-03-12 | B8                 | L   | 0.227      | -            | -                | -                | -         |    -6.41 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     3667 | 2024-03-11 | HEROIC             | L   | 0.222      | -            | -                | -                | -         |    -2.70 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     3677 | 2024-03-11 | Metizport          | W   | 0.220      | -            | -                | -                | -         |     0.20 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     4079 | 2024-02-22 | Astralis           | W   | 0.099      | -            | -                | -                | 1 (0.099) |     2.52 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4101 | 2024-02-21 | Vitality           | L   | 0.094      | -            | -                | -                | -         |    -0.32 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4134 | 2024-02-20 | GamerLegion        | W   | 0.086      | -            | -                | -                | -         |     0.05 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4154 | 2024-02-19 | ex-Guild Eagles    | W   | 0.081      | -            | -                | -                | -         |     0.06 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4162 | 2024-02-19 | Spirit             | L   | 0.080      | -            | -                | -                | -         |    -0.21 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4367 | 2024-02-09 | Falcons            | L   | 0.015      | -            | -                | -                | -         |    -0.27 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($54,124.93)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.867 | $10,000.00     | $8,669.44       |
| 2024-06-09 |      0.821 | $8,000.00      | $6,564.44       |
| 2024-05-23 |      0.707 | $12,500.00     | $8,835.07       |
| 2024-05-12 |      0.634 | $7,000.00      | $4,437.22       |
| 2024-04-14 |      0.447 | $15,000.00     | $6,706.25       |
| 2024-03-20 |      0.281 | $10,000.00     | $2,812.50       |
| 2024-02-11 |      0.028 | $40,000.00     | $1,100.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
