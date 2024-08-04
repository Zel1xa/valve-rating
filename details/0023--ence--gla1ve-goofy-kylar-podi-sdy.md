### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1346.8<br />
<br />
Final Rank Value (1346.8) = Starting Rank Value (1466.1) + Head To Head Adjustments (-119.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.564[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.254[<sup>2</sup>](#table1)
- LAN Wins: 0.805[<sup>2</sup>](#table1)

The average of these factors is 0.521<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1466.1
- 400 + ( ( 0.521 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1466.1


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
|           45 |      267 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.28 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      294 | 2024-07-26 | True Rippers       | W   | 1.000      | 0.650        | -                | 0.171 (0.111)    | 1 (1.000) |     0.85 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      334 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.534 (0.347)    | 1 (1.000) |     5.63 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      344 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -12.14 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      361 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      374 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.517 (0.336)    | 1 (1.000) |    13.00 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |      974 | 2024-06-16 | Falcons            | L   | 0.874      | -            | -                | -                | -         |   -11.00 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |     1038 | 2024-06-14 | Complexity         | W   | 0.862      | 0.500        | 0.310 (0.134)    | 0.380 (0.164)    | 1 (0.862) |    21.57 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |     1047 | 2024-06-14 | MIBR               | W   | 0.861      | 0.500        | 0.209 (0.090)    | 0.659 (0.284)    | 1 (0.861) |    16.19 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1380 | 2024-06-06 | HEROIC             | L   | 0.808      | -            | -                | -                | -         |    -5.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1391 | 2024-06-06 | Astralis           | L   | 0.807      | -            | -                | -                | -         |    -3.46 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1427 | 2024-06-05 | Sashi              | W   | 0.802      | 0.715        | 0.184 (0.106)    | 0.962 (0.552)    | 1 (0.802) |     8.29 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1440 | 2024-06-05 | The MongolZ        | L   | 0.801      | -            | -                | -                | -         |    -1.04 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1449 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.801      | -            | -                | -                | -         |    -6.09 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1556 | 2024-06-01 | DMS                | L   | 0.776      | -            | -                | -                | -         |   -21.97 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1565 | 2024-06-01 | KOI                | W   | 0.775      | -            | -                | -                | -         |     3.55 | gla1ve, Goofy, Kylar, podi, sdy    |
|           29 |     1575 | 2024-06-01 | DMS                | L   | 0.774      | -            | -                | -                | -         |   -22.32 | gla1ve, Goofy, Kylar, podi, sdy    |
|           28 |     1854 | 2024-05-21 | Liquid             | L   | 0.700      | -            | -                | -                | -         |    -7.31 | dycha, gla1ve, Goofy, hades, Kylar |
|           27 |     1940 | 2024-05-18 | fnatic             | W   | 0.681      | 0.769        | 0.371 (0.194)    | 0.708 (0.371)    | -         |    13.40 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     1963 | 2024-05-17 | Gaimin Gladiators  | W   | 0.676      | 0.769        | 0.038 (0.020)    | 0.351 (0.183)    | -         |     2.29 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     1974 | 2024-05-17 | fnatic             | L   | 0.674      | -            | -                | -                | -         |    -7.42 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2332 | 2024-05-04 | FURIA              | L   | 0.588      | -            | -                | -                | -         |    -3.74 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2346 | 2024-05-03 | GamerLegion        | L   | 0.581      | -            | -                | -                | -         |   -14.81 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2366 | 2024-05-02 | Monte              | W   | 0.575      | 0.889        | 0.059 (0.030)    | 0.161 (0.082)    | 1 (0.575) |     1.78 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2394 | 2024-05-01 | Bad News Kangaroos | W   | 0.568      | 0.889        | 0.017 (0.008)    | -                | 1 (0.568) |     0.56 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2425 | 2024-04-30 | GamerLegion        | L   | 0.560      | -            | -                | -                | -         |   -14.74 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2686 | 2024-04-19 | AMKAL              | L   | 0.488      | -            | -                | -                | -         |   -12.79 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     2773 | 2024-04-17 | Enterprise         | W   | 0.474      | 0.384        | 0.039 (0.007)    | 0.625 (0.114)    | -         |     0.83 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     2944 | 2024-04-10 | OG                 | L   | 0.428      | -            | -                | -                | -         |   -12.34 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     3029 | 2024-04-08 | FORZE              | L   | 0.414      | -            | -                | -                | -         |   -12.39 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3137 | 2024-04-04 | Aurora Young Blud  | W   | 0.387      | -            | -                | -                | -         |     0.34 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3431 | 2024-03-19 | FURIA              | L   | 0.282      | -            | -                | -                | -         |    -1.71 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3447 | 2024-03-18 | paiN               | L   | 0.274      | -            | -                | -                | -         |    -4.85 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3454 | 2024-03-17 | KOI                | W   | 0.270      | -            | -                | -                | 1 (0.270) |     0.95 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3474 | 2024-03-17 | Imperial           | L   | 0.268      | -            | -                | -                | -         |    -6.28 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3605 | 2024-03-12 | B8                 | L   | 0.235      | -            | -                | -                | -         |    -6.59 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     3618 | 2024-03-11 | HEROIC             | L   | 0.229      | -            | -                | -                | -         |    -2.72 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     3628 | 2024-03-11 | Metizport          | W   | 0.228      | -            | -                | -                | -         |     0.31 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     4030 | 2024-02-22 | Astralis           | W   | 0.107      | -            | -                | -                | 1 (0.107) |     2.60 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     4052 | 2024-02-21 | Vitality           | L   | 0.101      | -            | -                | -                | -         |    -0.34 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4085 | 2024-02-20 | GamerLegion        | W   | 0.094      | -            | -                | -                | -         |     0.06 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4105 | 2024-02-19 | ex-Guild Eagles    | W   | 0.088      | -            | -                | -                | -         |     0.07 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4113 | 2024-02-19 | Spirit             | L   | 0.087      | -            | -                | -                | -         |    -0.22 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4318 | 2024-02-09 | Falcons            | L   | 0.022      | -            | -                | -                | -         |    -0.40 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4352 | 2024-02-06 | MOUZ               | L   | 0.002      | -            | -                | -                | -         |    -0.01 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($54,893.68)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.874 | $10,000.00     | $8,744.44       |
| 2024-06-09 |      0.828 | $8,000.00      | $6,624.44       |
| 2024-05-23 |      0.714 | $12,500.00     | $8,928.82       |
| 2024-05-12 |      0.641 | $7,000.00      | $4,489.72       |
| 2024-04-14 |      0.455 | $15,000.00     | $6,818.75       |
| 2024-03-20 |      0.289 | $10,000.00     | $2,887.50       |
| 2024-02-11 |      0.035 | $40,000.00     | $1,400.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
