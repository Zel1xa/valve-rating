### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1574.2<br />
<br />
Final Rank Value (1574.2) = Starting Rank Value (1690.5) + Head To Head Adjustments (-116.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.627[<sup>1</sup>](#table2)
- Bounty Collected: 0.570[<sup>2</sup>](#table1)
- Opponent Network: 0.342[<sup>2</sup>](#table1)
- LAN Wins: 0.979[<sup>2</sup>](#table1)

The average of these factors is 0.629<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1690.5
- 400 + ( ( 0.629 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1690.5


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
|           39 |       37 | 2024-08-04 | Astralis        | L   | 1.000      | -            | -                | -                | -         |   -10.62 | alex, isak, maxster, r1nkle, REZ               |
|           38 |       61 | 2024-08-03 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.42 | alex, isak, maxster, r1nkle, REZ               |
|           37 |      100 | 2024-08-02 | FaZe            | W   | 1.000      | 0.581        | 0.630 (0.366)    | -                | 1 (1.000) |    20.71 | alex, isak, maxster, r1nkle, REZ               |
|           36 |      144 | 2024-08-01 | Cloud9          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.30 | alex, isak, maxster, r1nkle, REZ               |
|           35 |      196 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.28 | alex, isak, maxster, r1nkle, REZ               |
|           34 |      549 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -29.70 | alex, isak, maxster, r1nkle, REZ               |
|           33 |      623 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | -                | 0.987 (0.494)    | -         |     1.62 | alex, isak, maxster, r1nkle, REZ               |
|           32 |      750 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.458 (0.229)    | -         |     0.28 | alex, isak, maxster, r1nkle, REZ               |
|           31 |     1017 | 2024-06-16 | fnatic          | L   | 0.867      | -            | -                | -                | -         |   -19.04 | alex, isak, maxster, r1nkle, REZ               |
|           30 |     1077 | 2024-06-14 | paiN            | W   | 0.855      | 0.548        | 0.325 (0.152)    | 0.856 (0.402)    | 1 (0.855) |     5.31 | alex, isak, maxster, r1nkle, REZ               |
|           29 |     1083 | 2024-06-14 | 9z              | W   | 0.853      | 0.548        | 0.404 (0.189)    | 0.607 (0.284)    | 1 (0.853) |     7.88 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1249 | 2024-06-09 | The MongolZ     | L   | 0.819      | -            | -                | -                | -         |    -4.23 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1309 | 2024-06-08 | FURIA           | W   | 0.813      | 0.715        | 0.284 (0.165)    | 0.481 (0.280)    | 1 (0.813) |    12.66 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1363 | 2024-06-07 | fnatic          | W   | 0.806      | 0.715        | 0.371 (0.214)    | 0.697 (0.402)    | 1 (0.806) |     8.50 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1420 | 2024-06-06 | Sashi           | W   | 0.800      | 0.715        | 0.184 (0.105)    | 0.983 (0.563)    | 1 (0.800) |     2.63 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1446 | 2024-06-06 | The MongolZ     | L   | 0.799      | -            | -                | -                | -         |    -3.62 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1459 | 2024-06-06 | Astralis        | W   | 0.798      | 0.715        | 0.389 (0.222)    | 0.413 (0.236)    | 1 (0.798) |    17.19 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1496 | 2024-06-05 | HEROIC          | W   | 0.793      | 0.715        | 0.225 (0.128)    | -                | 1 (0.793) |    12.44 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1507 | 2024-06-05 | ENCE            | W   | 0.792      | 0.715        | 0.174 (0.098)    | 0.432 (0.245)    | 1 (0.792) |     6.02 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1959 | 2024-05-19 | Sangal          | L   | 0.680      | -            | -                | -                | -         |   -19.90 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     1986 | 2024-05-18 | Metizport       | L   | 0.673      | -            | -                | -                | -         |   -20.92 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     2056 | 2024-05-16 | Sangal          | W   | 0.660      | 0.500        | -                | 0.866 (0.286)    | -         |     1.14 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2379 | 2024-05-05 | FlyQuest        | L   | 0.585      | -            | -                | -                | -         |   -16.84 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2387 | 2024-05-04 | HEROIC          | W   | 0.579      | 0.889        | 0.225 (0.116)    | -                | -         |     7.85 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2401 | 2024-05-03 | BOSS            | W   | 0.573      | -            | -                | -                | -         |     0.22 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2431 | 2024-05-02 | PERA            | L   | 0.566      | -            | -                | -                | -         |   -17.47 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2476 | 2024-04-30 | HEROIC          | L   | 0.552      | -            | -                | -                | -         |   -10.07 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2784 | 2024-04-18 | brazylijski luz | L   | 0.473      | -            | -                | -                | -         |   -14.75 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2930 | 2024-04-12 | OG              | L   | 0.432      | -            | -                | -                | -         |   -13.23 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2955 | 2024-04-11 | BetBoom         | L   | 0.426      | -            | -                | -                | -         |   -10.88 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     3051 | 2024-04-09 | Gods Reign      | W   | 0.413      | -            | -                | -                | -         |     0.09 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3183 | 2024-04-04 | Aurora          | L   | 0.380      | -            | -                | -                | -         |    -6.08 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3192 | 2024-04-04 | Metizport       | W   | 0.379      | -            | -                | -                | -         |     0.14 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3223 | 2024-04-03 | Aurora          | L   | 0.373      | -            | -                | -                | -         |    -6.17 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3243 | 2024-04-03 | Sampi           | L   | 0.371      | -            | -                | -                | -         |   -11.54 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3260 | 2024-04-02 | FAVBET          | W   | 0.366      | -            | -                | -                | -         |     0.07 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3268 | 2024-04-02 | Monte           | W   | 0.365      | -            | -                | -                | -         |     0.21 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3353 | 2024-03-27 | 500             | W   | 0.327      | -            | -                | -                | -         |     0.04 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3361 | 2024-03-27 | Verdant         | W   | 0.327      | -            | -                | -                | -         |     0.15 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($81,726.44)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-06-16 |      0.868 | $7,000.00      | $6,076.71       |
| 2024-06-09 |      0.819 | $56,000.00     | $45,865.56      |
| 2024-05-12 |      0.632 | $12,000.00     | $7,588.33       |
| 2024-04-14 |      0.446 | $26,250.00     | $11,695.83      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
