### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1573.8<br />
<br />
Final Rank Value (1573.8) = Starting Rank Value (1690.9) + Head To Head Adjustments (-117.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.627[<sup>1</sup>](#table2)
- Bounty Collected: 0.571[<sup>2</sup>](#table1)
- Opponent Network: 0.346[<sup>2</sup>](#table1)
- LAN Wins: 0.980[<sup>2</sup>](#table1)

The average of these factors is 0.631<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1690.9
- 400 + ( ( 0.631 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1690.9


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
|           39 |       15 | 2024-08-04 | Astralis        | L   | 1.000      | -            | -                | -                | -         |   -10.57 | alex, isak, maxster, r1nkle, REZ               |
|           38 |       39 | 2024-08-03 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.41 | alex, isak, maxster, r1nkle, REZ               |
|           37 |       78 | 2024-08-02 | FaZe            | W   | 1.000      | 0.581        | 0.635 (0.369)    | 0.401 (0.233)    | 1 (1.000) |    20.83 | alex, isak, maxster, r1nkle, REZ               |
|           36 |      122 | 2024-08-01 | Cloud9          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.30 | alex, isak, maxster, r1nkle, REZ               |
|           35 |      174 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.28 | alex, isak, maxster, r1nkle, REZ               |
|           34 |      527 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -29.72 | alex, isak, maxster, r1nkle, REZ               |
|           33 |      601 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | -                | 1.000 (0.500)    | -         |     1.59 | alex, isak, maxster, r1nkle, REZ               |
|           32 |      728 | 2024-07-16 | Nexus           | W   | 1.000      | -            | -                | -                | -         |     0.28 | alex, isak, maxster, r1nkle, REZ               |
|           31 |      995 | 2024-06-16 | fnatic          | L   | 0.872      | -            | -                | -                | -         |   -19.14 | alex, isak, maxster, r1nkle, REZ               |
|           30 |     1055 | 2024-06-14 | paiN            | W   | 0.860      | 0.548        | 0.326 (0.154)    | 0.868 (0.409)    | 1 (0.860) |     5.40 | alex, isak, maxster, r1nkle, REZ               |
|           29 |     1061 | 2024-06-14 | 9z              | W   | 0.858      | 0.548        | 0.405 (0.191)    | 0.617 (0.291)    | 1 (0.858) |     7.97 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1227 | 2024-06-09 | The MongolZ     | L   | 0.824      | -            | -                | -                | -         |    -4.26 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1287 | 2024-06-08 | FURIA           | W   | 0.818      | 0.715        | 0.284 (0.166)    | 0.490 (0.286)    | 1 (0.818) |    12.70 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1341 | 2024-06-07 | fnatic          | W   | 0.811      | 0.715        | 0.371 (0.215)    | 0.708 (0.411)    | 1 (0.811) |     8.55 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1398 | 2024-06-06 | Sashi           | W   | 0.805      | 0.715        | 0.184 (0.106)    | 0.961 (0.553)    | 1 (0.805) |     2.65 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1424 | 2024-06-06 | The MongolZ     | L   | 0.804      | -            | -                | -                | -         |    -3.65 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1437 | 2024-06-06 | Astralis        | W   | 0.802      | 0.715        | 0.390 (0.224)    | 0.421 (0.241)    | 1 (0.802) |    17.36 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1474 | 2024-06-05 | HEROIC          | W   | 0.798      | 0.715        | 0.226 (0.129)    | -                | 1 (0.798) |    12.59 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1485 | 2024-06-05 | ENCE            | W   | 0.796      | 0.715        | 0.168 (0.096)    | 0.439 (0.250)    | 1 (0.796) |     5.99 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1937 | 2024-05-19 | Sangal          | L   | 0.685      | -            | -                | -                | -         |   -20.07 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     1964 | 2024-05-18 | Metizport       | L   | 0.678      | -            | -                | -                | -         |   -21.08 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     2034 | 2024-05-16 | Sangal          | W   | 0.665      | 0.500        | -                | 0.861 (0.286)    | -         |     1.14 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2357 | 2024-05-05 | FlyQuest        | L   | 0.590      | -            | -                | -                | -         |   -16.95 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2365 | 2024-05-04 | HEROIC          | W   | 0.584      | 0.889        | 0.226 (0.117)    | -                | -         |     7.96 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2379 | 2024-05-03 | BOSS            | W   | 0.578      | -            | -                | -                | -         |     0.23 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2409 | 2024-05-02 | PERA            | L   | 0.570      | -            | -                | -                | -         |   -17.62 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2454 | 2024-04-30 | HEROIC          | L   | 0.557      | -            | -                | -                | -         |   -10.12 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2762 | 2024-04-18 | brazylijski luz | L   | 0.477      | -            | -                | -                | -         |   -14.90 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2908 | 2024-04-12 | OG              | L   | 0.437      | -            | -                | -                | -         |   -13.38 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2933 | 2024-04-11 | BetBoom         | L   | 0.431      | -            | -                | -                | -         |   -10.99 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     3029 | 2024-04-09 | Gods Reign      | W   | 0.418      | -            | -                | -                | -         |     0.10 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3161 | 2024-04-04 | Aurora          | L   | 0.385      | -            | -                | -                | -         |    -6.21 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3170 | 2024-04-04 | Metizport       | W   | 0.383      | -            | -                | -                | -         |     0.14 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3201 | 2024-04-03 | Aurora          | L   | 0.378      | -            | -                | -                | -         |    -6.32 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3221 | 2024-04-03 | Sampi           | L   | 0.376      | -            | -                | -                | -         |   -11.69 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3238 | 2024-04-02 | FAVBET          | W   | 0.371      | -            | -                | -                | -         |     0.07 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3246 | 2024-04-02 | Monte           | W   | 0.370      | -            | -                | -                | -         |     0.21 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3331 | 2024-03-27 | 500             | W   | 0.332      | -            | -                | -                | -         |     0.05 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3339 | 2024-03-27 | Verdant         | W   | 0.331      | -            | -                | -                | -         |     0.15 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($82,218.62)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-06-16 |      0.873 | $7,000.00      | $6,110.74       |
| 2024-06-09 |      0.824 | $56,000.00     | $46,137.78      |
| 2024-05-12 |      0.637 | $12,000.00     | $7,646.67       |
| 2024-04-14 |      0.450 | $26,250.00     | $11,823.44      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
