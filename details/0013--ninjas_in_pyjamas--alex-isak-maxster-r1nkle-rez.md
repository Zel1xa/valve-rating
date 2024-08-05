### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1574.5<br />
<br />
Final Rank Value (1574.5) = Starting Rank Value (1691.4) + Head To Head Adjustments (-116.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.627[<sup>1</sup>](#table2)
- Bounty Collected: 0.570[<sup>2</sup>](#table1)
- Opponent Network: 0.347[<sup>2</sup>](#table1)
- LAN Wins: 0.979[<sup>2</sup>](#table1)

The average of these factors is 0.631<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1691.4
- 400 + ( ( 0.631 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1691.4


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
|           39 |       28 | 2024-08-04 | Astralis        | L   | 1.000      | -            | -                | -                | -         |   -10.62 | alex, isak, maxster, r1nkle, REZ               |
|           38 |       52 | 2024-08-03 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.42 | alex, isak, maxster, r1nkle, REZ               |
|           37 |       91 | 2024-08-02 | FaZe            | W   | 1.000      | 0.581        | 0.632 (0.367)    | -                | 1 (1.000) |    20.73 | alex, isak, maxster, r1nkle, REZ               |
|           36 |      135 | 2024-08-01 | Cloud9          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.30 | alex, isak, maxster, r1nkle, REZ               |
|           35 |      187 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.29 | alex, isak, maxster, r1nkle, REZ               |
|           34 |      540 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -29.70 | alex, isak, maxster, r1nkle, REZ               |
|           33 |      614 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | -                | 1.000 (0.500)    | -         |     1.60 | alex, isak, maxster, r1nkle, REZ               |
|           32 |      741 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.464 (0.232)    | -         |     0.28 | alex, isak, maxster, r1nkle, REZ               |
|           31 |     1008 | 2024-06-16 | fnatic          | L   | 0.868      | -            | -                | -                | -         |   -19.08 | alex, isak, maxster, r1nkle, REZ               |
|           30 |     1068 | 2024-06-14 | paiN            | W   | 0.857      | 0.548        | 0.325 (0.153)    | 0.867 (0.407)    | 1 (0.857) |     5.33 | alex, isak, maxster, r1nkle, REZ               |
|           29 |     1074 | 2024-06-14 | 9z              | W   | 0.855      | 0.548        | 0.405 (0.190)    | 0.615 (0.288)    | 1 (0.855) |     7.90 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1240 | 2024-06-09 | The MongolZ     | L   | 0.821      | -            | -                | -                | -         |    -4.23 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1300 | 2024-06-08 | FURIA           | W   | 0.815      | 0.715        | 0.284 (0.165)    | 0.487 (0.284)    | 1 (0.815) |    12.68 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1354 | 2024-06-07 | fnatic          | W   | 0.808      | 0.715        | 0.371 (0.214)    | 0.706 (0.408)    | 1 (0.808) |     8.51 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1411 | 2024-06-06 | Sashi           | W   | 0.802      | 0.715        | 0.184 (0.105)    | 0.996 (0.571)    | 1 (0.802) |     2.63 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1437 | 2024-06-06 | The MongolZ     | L   | 0.800      | -            | -                | -                | -         |    -3.63 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1450 | 2024-06-06 | Astralis        | W   | 0.799      | 0.715        | 0.390 (0.223)    | 0.419 (0.239)    | 1 (0.799) |    17.23 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1487 | 2024-06-05 | HEROIC          | W   | 0.794      | 0.715        | 0.225 (0.128)    | -                | 1 (0.794) |    12.48 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1498 | 2024-06-05 | ENCE            | W   | 0.793      | 0.715        | 0.168 (0.095)    | 0.438 (0.248)    | 1 (0.793) |     5.95 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1950 | 2024-05-19 | Sangal          | L   | 0.682      | -            | -                | -                | -         |   -19.96 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     1977 | 2024-05-18 | Metizport       | L   | 0.675      | -            | -                | -                | -         |   -20.97 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     2047 | 2024-05-16 | Sangal          | W   | 0.661      | 0.500        | -                | 0.877 (0.290)    | -         |     1.13 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2370 | 2024-05-05 | FlyQuest        | L   | 0.586      | -            | -                | -                | -         |   -16.88 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2378 | 2024-05-04 | HEROIC          | W   | 0.581      | 0.889        | 0.225 (0.116)    | -                | -         |     7.88 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2392 | 2024-05-03 | BOSS            | W   | 0.575      | -            | -                | -                | -         |     0.22 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2422 | 2024-05-02 | PERA            | L   | 0.567      | -            | -                | -                | -         |   -17.52 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2467 | 2024-04-30 | HEROIC          | L   | 0.554      | -            | -                | -                | -         |   -10.10 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2775 | 2024-04-18 | brazylijski luz | L   | 0.474      | -            | -                | -                | -         |   -14.80 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2921 | 2024-04-12 | OG              | L   | 0.433      | -            | -                | -                | -         |   -13.28 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2946 | 2024-04-11 | BetBoom         | L   | 0.427      | -            | -                | -                | -         |   -10.91 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     3042 | 2024-04-09 | Gods Reign      | W   | 0.414      | -            | -                | -                | -         |     0.09 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3174 | 2024-04-04 | Aurora          | L   | 0.381      | -            | -                | -                | -         |    -6.17 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3183 | 2024-04-04 | Metizport       | W   | 0.380      | -            | -                | -                | -         |     0.14 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3214 | 2024-04-03 | Aurora          | L   | 0.375      | -            | -                | -                | -         |    -6.26 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3234 | 2024-04-03 | Sampi           | L   | 0.372      | -            | -                | -                | -         |   -11.59 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3251 | 2024-04-02 | FAVBET          | W   | 0.368      | -            | -                | -                | -         |     0.07 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3259 | 2024-04-02 | Monte           | W   | 0.367      | -            | -                | -                | -         |     0.21 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3344 | 2024-03-27 | 500             | W   | 0.328      | -            | -                | -                | -         |     0.04 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3352 | 2024-03-27 | Verdant         | W   | 0.328      | -            | -                | -                | -         |     0.15 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($81,881.12)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-06-16 |      0.870 | $7,000.00      | $6,087.41       |
| 2024-06-09 |      0.821 | $56,000.00     | $45,951.11      |
| 2024-05-12 |      0.634 | $12,000.00     | $7,606.67       |
| 2024-04-14 |      0.447 | $26,250.00     | $11,735.94      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
