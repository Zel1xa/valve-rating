### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1347.0<br />
<br />
Final Rank Value (1347.0) = Starting Rank Value (1466.9) + Head To Head Adjustments (-119.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.565[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.255[<sup>2</sup>](#table1)
- LAN Wins: 0.806[<sup>2</sup>](#table1)

The average of these factors is 0.522<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1466.9
- 400 + ( ( 0.522 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1466.9


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
|           45 |      264 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.33 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      291 | 2024-07-26 | True Rippers       | W   | 1.000      | 0.650        | -                | 0.171 (0.111)    | 1 (1.000) |     0.85 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      331 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.534 (0.347)    | 1 (1.000) |     5.62 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      341 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -12.18 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      358 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.80 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      371 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.516 (0.336)    | 1 (1.000) |    12.99 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |      970 | 2024-06-16 | Falcons            | L   | 0.877      | -            | -                | -                | -         |   -11.00 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |     1034 | 2024-06-14 | Complexity         | W   | 0.865      | 0.500        | 0.311 (0.134)    | 0.380 (0.164)    | 1 (0.865) |    21.65 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |     1043 | 2024-06-14 | MIBR               | W   | 0.864      | 0.500        | 0.210 (0.091)    | 0.659 (0.285)    | 1 (0.864) |    16.27 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1376 | 2024-06-06 | HEROIC             | L   | 0.811      | -            | -                | -                | -         |    -5.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1387 | 2024-06-06 | Astralis           | L   | 0.810      | -            | -                | -                | -         |    -3.45 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1423 | 2024-06-05 | Sashi              | W   | 0.805      | 0.715        | 0.184 (0.106)    | 0.964 (0.555)    | 1 (0.805) |     8.33 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1436 | 2024-06-05 | The MongolZ        | L   | 0.805      | -            | -                | -                | -         |    -1.05 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1445 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.804      | -            | -                | -                | -         |    -6.11 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1552 | 2024-06-01 | DMS                | L   | 0.779      | -            | -                | -                | -         |   -22.06 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1561 | 2024-06-01 | KOI                | W   | 0.778      | -            | -                | -                | -         |     3.58 | gla1ve, Goofy, Kylar, podi, sdy    |
|           29 |     1571 | 2024-06-01 | DMS                | L   | 0.777      | -            | -                | -                | -         |   -22.40 | gla1ve, Goofy, Kylar, podi, sdy    |
|           28 |     1850 | 2024-05-21 | Liquid             | L   | 0.703      | -            | -                | -                | -         |    -7.32 | dycha, gla1ve, Goofy, hades, Kylar |
|           27 |     1936 | 2024-05-18 | fnatic             | W   | 0.684      | 0.769        | 0.371 (0.195)    | 0.709 (0.373)    | -         |    13.46 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     1959 | 2024-05-17 | Gaimin Gladiators  | W   | 0.679      | 0.769        | 0.038 (0.020)    | 0.353 (0.184)    | -         |     2.31 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     1970 | 2024-05-17 | fnatic             | L   | 0.677      | -            | -                | -                | -         |    -7.46 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2328 | 2024-05-04 | FURIA              | L   | 0.591      | -            | -                | -                | -         |    -3.77 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2342 | 2024-05-03 | GamerLegion        | L   | 0.584      | -            | -                | -                | -         |   -14.88 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2362 | 2024-05-02 | Monte              | W   | 0.579      | 0.889        | 0.060 (0.031)    | 0.162 (0.083)    | 1 (0.579) |     1.80 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2390 | 2024-05-01 | Bad News Kangaroos | W   | 0.571      | 0.889        | 0.017 (0.009)    | -                | 1 (0.571) |     0.57 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2421 | 2024-04-30 | GamerLegion        | L   | 0.564      | -            | -                | -                | -         |   -14.82 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2681 | 2024-04-19 | AMKAL              | L   | 0.491      | -            | -                | -                | -         |   -12.87 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     2768 | 2024-04-17 | Enterprise         | W   | 0.477      | 0.384        | 0.039 (0.007)    | 0.624 (0.114)    | -         |     0.84 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     2939 | 2024-04-10 | OG                 | L   | 0.431      | -            | -                | -                | -         |   -12.42 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     3024 | 2024-04-08 | FORZE              | L   | 0.417      | -            | -                | -                | -         |   -12.48 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3132 | 2024-04-04 | Aurora Young Blud  | W   | 0.390      | -            | -                | -                | -         |     0.34 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3426 | 2024-03-19 | FURIA              | L   | 0.285      | -            | -                | -                | -         |    -1.73 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3442 | 2024-03-18 | paiN               | L   | 0.277      | -            | -                | -                | -         |    -4.89 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3449 | 2024-03-17 | KOI                | W   | 0.273      | -            | -                | -                | 1 (0.273) |     0.96 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3469 | 2024-03-17 | Imperial           | L   | 0.271      | -            | -                | -                | -         |    -6.34 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3599 | 2024-03-12 | B8                 | L   | 0.238      | -            | -                | -                | -         |    -6.68 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     3612 | 2024-03-11 | HEROIC             | L   | 0.232      | -            | -                | -                | -         |    -2.75 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     3622 | 2024-03-11 | Metizport          | W   | 0.231      | -            | -                | -                | -         |     0.31 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     4024 | 2024-02-22 | Astralis           | W   | 0.110      | -            | -                | -                | 1 (0.110) |     2.68 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     4046 | 2024-02-21 | Vitality           | L   | 0.104      | -            | -                | -                | -         |    -0.35 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4079 | 2024-02-20 | GamerLegion        | W   | 0.097      | -            | -                | -                | -         |     0.06 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4099 | 2024-02-19 | ex-Guild Eagles    | W   | 0.092      | -            | -                | -                | -         |     0.07 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4107 | 2024-02-19 | Spirit             | L   | 0.090      | -            | -                | -                | -         |    -0.23 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4311 | 2024-02-09 | Falcons            | L   | 0.025      | -            | -                | -                | -         |    -0.45 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4345 | 2024-02-06 | MOUZ               | L   | 0.005      | -            | -                | -                | -         |    -0.02 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,206.88)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.877 | $10,000.00     | $8,775.00       |
| 2024-06-09 |      0.831 | $8,000.00      | $6,648.89       |
| 2024-05-23 |      0.717 | $12,500.00     | $8,967.01       |
| 2024-05-12 |      0.644 | $7,000.00      | $4,511.11       |
| 2024-04-14 |      0.458 | $15,000.00     | $6,864.58       |
| 2024-03-20 |      0.292 | $10,000.00     | $2,918.06       |
| 2024-02-11 |      0.038 | $40,000.00     | $1,522.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
