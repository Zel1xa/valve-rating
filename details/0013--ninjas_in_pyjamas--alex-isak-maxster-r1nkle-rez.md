### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1574.4<br />
<br />
Final Rank Value (1574.4) = Starting Rank Value (1678.1) + Head To Head Adjustments (-103.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.605[<sup>1</sup>](#table2)
- Bounty Collected: 0.570[<sup>2</sup>](#table1)
- Opponent Network: 0.345[<sup>2</sup>](#table1)
- LAN Wins: 0.981[<sup>2</sup>](#table1)

The average of these factors is 0.625<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1678.1
- 400 + ( ( 0.625 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1678.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |        5 | 2024-08-03 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.30 | alex, isak, maxster, r1nkle, REZ               |
|           37 |       44 | 2024-08-02 | FaZe            | W   | 1.000      | 0.581        | 0.640 (0.372)    | 0.402 (0.234)    | 1 (1.000) |    21.09 | alex, isak, maxster, r1nkle, REZ               |
|           36 |       87 | 2024-08-01 | Cloud9          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.32 | alex, isak, maxster, r1nkle, REZ               |
|           35 |      138 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.16 | alex, isak, maxster, r1nkle, REZ               |
|           34 |      491 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -29.66 | alex, isak, maxster, r1nkle, REZ               |
|           33 |      568 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | -                | 1.000 (0.500)    | -         |     1.67 | alex, isak, maxster, r1nkle, REZ               |
|           32 |      692 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.465 (0.233)    | -         |     0.30 | alex, isak, maxster, r1nkle, REZ               |
|           31 |      959 | 2024-06-16 | fnatic          | L   | 0.876      | -            | -                | -                | -         |   -18.96 | alex, isak, maxster, r1nkle, REZ               |
|           30 |     1019 | 2024-06-14 | paiN            | W   | 0.864      | 0.548        | 0.327 (0.155)    | 0.866 (0.410)    | 1 (0.864) |     5.72 | alex, isak, maxster, r1nkle, REZ               |
|           29 |     1025 | 2024-06-14 | 9z              | W   | 0.863      | 0.548        | 0.406 (0.192)    | 0.619 (0.293)    | 1 (0.863) |     8.29 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1191 | 2024-06-09 | The MongolZ     | L   | 0.828      | -            | -                | -                | -         |    -4.17 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1251 | 2024-06-08 | FURIA           | W   | 0.822      | 0.715        | 0.284 (0.167)    | 0.491 (0.288)    | 1 (0.822) |    13.02 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1305 | 2024-06-07 | fnatic          | W   | 0.815      | 0.715        | 0.371 (0.216)    | 0.708 (0.413)    | 1 (0.815) |     8.90 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1362 | 2024-06-06 | Sashi           | W   | 0.809      | 0.715        | 0.184 (0.107)    | 0.962 (0.557)    | 1 (0.809) |     2.79 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1388 | 2024-06-06 | The MongolZ     | L   | 0.808      | -            | -                | -                | -         |    -3.52 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1401 | 2024-06-06 | Astralis        | W   | 0.807      | 0.715        | 0.352 (0.203)    | -                | 1 (0.807) |    16.61 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1438 | 2024-06-05 | HEROIC          | W   | 0.802      | 0.715        | 0.229 (0.131)    | -                | 1 (0.802) |    12.93 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1449 | 2024-06-05 | ENCE            | W   | 0.801      | 0.715        | 0.169 (0.097)    | 0.400 (0.229)    | 1 (0.801) |     6.09 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1901 | 2024-05-19 | Sangal          | L   | 0.689      | -            | -                | -                | -         |   -20.13 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     1928 | 2024-05-18 | Metizport       | L   | 0.682      | -            | -                | -                | -         |   -20.78 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     1998 | 2024-05-16 | Sangal          | W   | 0.669      | 0.500        | -                | 0.862 (0.288)    | -         |     1.20 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2321 | 2024-05-05 | FlyQuest        | L   | 0.594      | -            | -                | -                | -         |   -16.97 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2329 | 2024-05-04 | HEROIC          | W   | 0.588      | 0.889        | 0.229 (0.120)    | -                | -         |     8.25 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2343 | 2024-05-03 | BOSS            | W   | 0.582      | -            | -                | -                | -         |     0.24 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2373 | 2024-05-02 | PERA            | L   | 0.575      | -            | -                | -                | -         |   -17.73 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2418 | 2024-04-30 | HEROIC          | L   | 0.561      | -            | -                | -                | -         |    -9.96 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2726 | 2024-04-18 | brazylijski luz | L   | 0.482      | -            | -                | -                | -         |   -15.02 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2872 | 2024-04-12 | OG              | L   | 0.441      | -            | -                | -                | -         |   -13.48 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2897 | 2024-04-11 | BetBoom         | L   | 0.435      | -            | -                | -                | -         |   -10.93 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     2993 | 2024-04-09 | Gods Reign      | W   | 0.422      | -            | -                | -                | -         |     0.10 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3125 | 2024-04-04 | Aurora          | L   | 0.389      | -            | -                | -                | -         |    -6.11 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3134 | 2024-04-04 | Metizport       | W   | 0.388      | -            | -                | -                | -         |     0.20 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3165 | 2024-04-03 | Aurora          | L   | 0.382      | -            | -                | -                | -         |    -6.21 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3185 | 2024-04-03 | Sampi           | L   | 0.380      | -            | -                | -                | -         |   -11.81 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3202 | 2024-04-02 | FAVBET          | W   | 0.375      | -            | -                | -                | -         |     0.08 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3210 | 2024-04-02 | Monte           | W   | 0.374      | -            | -                | -                | -         |     0.23 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3295 | 2024-03-27 | 500             | W   | 0.336      | -            | -                | -                | -         |     0.05 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3303 | 2024-03-27 | Verdant         | W   | 0.336      | -            | -                | -                | -         |     0.16 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($72,140.50)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.877 | $7,000.00      | $6,139.91       |
| 2024-06-09 |      0.828 | $56,000.00     | $46,371.11      |
| 2024-05-12 |      0.641 | $12,000.00     | $7,696.67       |
| 2024-04-14 |      0.455 | $26,250.00     | $11,932.81      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
