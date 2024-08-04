### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1573.3<br />
<br />
Final Rank Value (1573.3) = Starting Rank Value (1690.7) + Head To Head Adjustments (-117.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.627[<sup>1</sup>](#table2)
- Bounty Collected: 0.571[<sup>2</sup>](#table1)
- Opponent Network: 0.345[<sup>2</sup>](#table1)
- LAN Wins: 0.981[<sup>2</sup>](#table1)

The average of these factors is 0.631<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1690.7
- 400 + ( ( 0.631 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1690.7


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
|           39 |       11 | 2024-08-04 | Astralis        | L   | 1.000      | -            | -                | -                | -         |   -10.56 | alex, isak, maxster, r1nkle, REZ               |
|           38 |       35 | 2024-08-03 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.41 | alex, isak, maxster, r1nkle, REZ               |
|           37 |       74 | 2024-08-02 | FaZe            | W   | 1.000      | 0.581        | 0.638 (0.371)    | 0.402 (0.233)    | 1 (1.000) |    20.90 | alex, isak, maxster, r1nkle, REZ               |
|           36 |      118 | 2024-08-01 | Cloud9          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.30 | alex, isak, maxster, r1nkle, REZ               |
|           35 |      170 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.27 | alex, isak, maxster, r1nkle, REZ               |
|           34 |      523 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -29.71 | alex, isak, maxster, r1nkle, REZ               |
|           33 |      597 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | -                | 1.000 (0.500)    | -         |     1.60 | alex, isak, maxster, r1nkle, REZ               |
|           32 |      724 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.465 (0.233)    | -         |     0.28 | alex, isak, maxster, r1nkle, REZ               |
|           31 |      991 | 2024-06-16 | fnatic          | L   | 0.874      | -            | -                | -                | -         |   -19.18 | alex, isak, maxster, r1nkle, REZ               |
|           30 |     1051 | 2024-06-14 | paiN            | W   | 0.862      | 0.548        | 0.327 (0.154)    | 0.867 (0.410)    | 1 (0.862) |     5.45 | alex, isak, maxster, r1nkle, REZ               |
|           29 |     1057 | 2024-06-14 | 9z              | W   | 0.861      | 0.548        | 0.405 (0.191)    | 0.618 (0.292)    | 1 (0.861) |     8.03 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1223 | 2024-06-09 | The MongolZ     | L   | 0.826      | -            | -                | -                | -         |    -4.28 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1283 | 2024-06-08 | FURIA           | W   | 0.820      | 0.715        | 0.284 (0.167)    | 0.490 (0.288)    | 1 (0.820) |    12.73 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1337 | 2024-06-07 | fnatic          | W   | 0.814      | 0.715        | 0.371 (0.216)    | 0.708 (0.412)    | 1 (0.814) |     8.59 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1394 | 2024-06-06 | Sashi           | W   | 0.807      | 0.715        | 0.184 (0.106)    | 0.962 (0.555)    | 1 (0.807) |     2.67 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1420 | 2024-06-06 | The MongolZ     | L   | 0.806      | -            | -                | -                | -         |    -3.67 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1433 | 2024-06-06 | Astralis        | W   | 0.805      | 0.715        | 0.390 (0.225)    | 0.421 (0.242)    | 1 (0.805) |    17.42 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1470 | 2024-06-05 | HEROIC          | W   | 0.800      | 0.715        | 0.229 (0.131)    | -                | 1 (0.800) |    12.68 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1481 | 2024-06-05 | ENCE            | W   | 0.799      | 0.715        | 0.169 (0.096)    | -                | 1 (0.799) |     5.90 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1933 | 2024-05-19 | Sangal          | L   | 0.687      | -            | -                | -                | -         |   -20.14 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     1960 | 2024-05-18 | Metizport       | L   | 0.680      | -            | -                | -                | -         |   -21.15 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     2030 | 2024-05-16 | Sangal          | W   | 0.667      | 0.500        | -                | 0.861 (0.287)    | -         |     1.15 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2353 | 2024-05-05 | FlyQuest        | L   | 0.592      | -            | -                | -                | -         |   -17.01 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2361 | 2024-05-04 | HEROIC          | W   | 0.586      | 0.889        | 0.229 (0.119)    | -                | -         |     8.02 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2375 | 2024-05-03 | BOSS            | W   | 0.580      | -            | -                | -                | -         |     0.23 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2405 | 2024-05-02 | PERA            | L   | 0.573      | -            | -                | -                | -         |   -17.69 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2450 | 2024-04-30 | HEROIC          | L   | 0.559      | -            | -                | -                | -         |   -10.13 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2758 | 2024-04-18 | brazylijski luz | L   | 0.480      | -            | -                | -                | -         |   -14.97 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2904 | 2024-04-12 | OG              | L   | 0.439      | -            | -                | -                | -         |   -13.45 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2929 | 2024-04-11 | BetBoom         | L   | 0.433      | -            | -                | -                | -         |   -11.03 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     3025 | 2024-04-09 | Gods Reign      | W   | 0.420      | -            | -                | -                | -         |     0.10 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3157 | 2024-04-04 | Aurora          | L   | 0.387      | -            | -                | -                | -         |    -6.27 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3166 | 2024-04-04 | Metizport       | W   | 0.386      | -            | -                | -                | -         |     0.14 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3197 | 2024-04-03 | Aurora          | L   | 0.380      | -            | -                | -                | -         |    -6.38 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3217 | 2024-04-03 | Sampi           | L   | 0.378      | -            | -                | -                | -         |   -11.77 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3234 | 2024-04-02 | FAVBET          | W   | 0.374      | -            | -                | -                | -         |     0.07 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3242 | 2024-04-02 | Monte           | W   | 0.373      | -            | -                | -                | -         |     0.21 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3327 | 2024-03-27 | 500             | W   | 0.334      | -            | -                | -                | -         |     0.05 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3335 | 2024-03-27 | Verdant         | W   | 0.334      | -            | -                | -                | -         |     0.15 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($82,460.03)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-06-16 |      0.875 | $7,000.00      | $6,127.43       |
| 2024-06-09 |      0.826 | $56,000.00     | $46,271.30      |
| 2024-05-12 |      0.640 | $12,000.00     | $7,675.28       |
| 2024-04-14 |      0.453 | $26,250.00     | $11,886.02      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
