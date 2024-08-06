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
Final Rank Value (1573.8) = Starting Rank Value (1689.3) + Head To Head Adjustments (-115.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.627[<sup>1</sup>](#table2)
- Bounty Collected: 0.569[<sup>2</sup>](#table1)
- Opponent Network: 0.340[<sup>2</sup>](#table1)
- LAN Wins: 0.978[<sup>2</sup>](#table1)

The average of these factors is 0.628<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1689.3
- 400 + ( ( 0.628 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1689.3


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
|           39 |       43 | 2024-08-04 | Astralis        | L   | 1.000      | -            | -                | -                | -         |   -10.64 | alex, isak, maxster, r1nkle, REZ               |
|           38 |       67 | 2024-08-03 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.41 | alex, isak, maxster, r1nkle, REZ               |
|           37 |      106 | 2024-08-02 | FaZe            | W   | 1.000      | 0.581        | 0.626 (0.364)    | -                | 1 (1.000) |    20.63 | alex, isak, maxster, r1nkle, REZ               |
|           36 |      150 | 2024-08-01 | Cloud9          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.30 | alex, isak, maxster, r1nkle, REZ               |
|           35 |      202 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.27 | alex, isak, maxster, r1nkle, REZ               |
|           34 |      555 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -29.69 | alex, isak, maxster, r1nkle, REZ               |
|           33 |      629 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | -                | 0.984 (0.492)    | -         |     1.62 | alex, isak, maxster, r1nkle, REZ               |
|           32 |      756 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.457 (0.229)    | -         |     0.29 | alex, isak, maxster, r1nkle, REZ               |
|           31 |     1023 | 2024-06-16 | fnatic          | L   | 0.863      | -            | -                | -                | -         |   -18.94 | alex, isak, maxster, r1nkle, REZ               |
|           30 |     1083 | 2024-06-14 | paiN            | W   | 0.851      | 0.548        | 0.324 (0.151)    | 0.857 (0.400)    | 1 (0.851) |     5.26 | alex, isak, maxster, r1nkle, REZ               |
|           29 |     1089 | 2024-06-14 | 9z              | W   | 0.849      | 0.548        | 0.404 (0.188)    | 0.604 (0.281)    | 1 (0.849) |     7.83 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1255 | 2024-06-09 | The MongolZ     | L   | 0.815      | -            | -                | -                | -         |    -4.19 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1315 | 2024-06-08 | FURIA           | W   | 0.809      | 0.715        | 0.284 (0.164)    | 0.479 (0.277)    | 1 (0.809) |    12.62 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1369 | 2024-06-07 | fnatic          | W   | 0.802      | 0.715        | 0.371 (0.213)    | 0.695 (0.399)    | 1 (0.802) |     8.46 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1426 | 2024-06-06 | Sashi           | W   | 0.796      | 0.715        | 0.184 (0.105)    | 0.980 (0.558)    | 1 (0.796) |     2.62 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1452 | 2024-06-06 | The MongolZ     | L   | 0.794      | -            | -                | -                | -         |    -3.59 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1465 | 2024-06-06 | Astralis        | W   | 0.793      | 0.715        | 0.389 (0.221)    | 0.412 (0.234)    | 1 (0.793) |    17.08 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1502 | 2024-06-05 | HEROIC          | W   | 0.789      | 0.715        | 0.225 (0.127)    | -                | 1 (0.789) |    12.32 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1513 | 2024-06-05 | ENCE            | W   | 0.787      | 0.715        | 0.173 (0.098)    | 0.431 (0.243)    | 1 (0.787) |     6.02 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1965 | 2024-05-19 | Sangal          | L   | 0.676      | -            | -                | -                | -         |   -19.77 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     1992 | 2024-05-18 | Metizport       | L   | 0.669      | -            | -                | -                | -         |   -20.79 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     2062 | 2024-05-16 | Sangal          | W   | 0.656      | 0.500        | -                | 0.865 (0.284)    | -         |     1.14 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2385 | 2024-05-05 | FlyQuest        | L   | 0.580      | -            | -                | -                | -         |   -16.73 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2393 | 2024-05-04 | HEROIC          | W   | 0.575      | 0.889        | 0.225 (0.115)    | -                | -         |     7.76 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2407 | 2024-05-03 | BOSS            | W   | 0.569      | -            | -                | -                | -         |     0.22 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2437 | 2024-05-02 | PERA            | L   | 0.561      | -            | -                | -                | -         |   -17.34 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2482 | 2024-04-30 | HEROIC          | L   | 0.548      | -            | -                | -                | -         |   -10.03 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2790 | 2024-04-18 | brazylijski luz | L   | 0.468      | -            | -                | -                | -         |   -14.62 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2936 | 2024-04-12 | OG              | L   | 0.428      | -            | -                | -                | -         |   -13.10 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2961 | 2024-04-11 | BetBoom         | L   | 0.422      | -            | -                | -                | -         |   -10.78 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     3057 | 2024-04-09 | Gods Reign      | W   | 0.409      | -            | -                | -                | -         |     0.09 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3189 | 2024-04-04 | Aurora          | L   | 0.375      | -            | -                | -                | -         |    -5.97 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3198 | 2024-04-04 | Metizport       | W   | 0.374      | -            | -                | -                | -         |     0.13 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3229 | 2024-04-03 | Aurora          | L   | 0.369      | -            | -                | -                | -         |    -6.06 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3249 | 2024-04-03 | Sampi           | L   | 0.367      | -            | -                | -                | -         |   -11.41 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3266 | 2024-04-02 | FAVBET          | W   | 0.362      | -            | -                | -                | -         |     0.07 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3274 | 2024-04-02 | Monte           | W   | 0.361      | -            | -                | -                | -         |     0.20 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3359 | 2024-03-27 | 500             | W   | 0.323      | -            | -                | -                | -         |     0.04 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3367 | 2024-03-27 | Verdant         | W   | 0.322      | -            | -                | -                | -         |     0.15 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($81,290.50)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-06-16 |      0.864 | $7,000.00      | $6,046.57       |
| 2024-06-09 |      0.815 | $56,000.00     | $45,624.44      |
| 2024-05-12 |      0.628 | $12,000.00     | $7,536.67       |
| 2024-04-14 |      0.441 | $26,250.00     | $11,582.81      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
