### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1573.2<br />
<br />
Final Rank Value (1573.2) = Starting Rank Value (1690.9) + Head To Head Adjustments (-117.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.627[<sup>1</sup>](#table2)
- Bounty Collected: 0.572[<sup>2</sup>](#table1)
- Opponent Network: 0.346[<sup>2</sup>](#table1)
- LAN Wins: 0.981[<sup>2</sup>](#table1)

The average of these factors is 0.631<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1690.9
- 400 + ( ( 0.631 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1690.9


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
|           39 |        0 | 2024-08-04 | Astralis        | L   | 1.000      | -            | -                | -                | -         |   -10.57 | alex, isak, maxster, r1nkle, REZ               |
|           38 |       13 | 2024-08-03 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.42 | alex, isak, maxster, r1nkle, REZ               |
|           37 |       52 | 2024-08-02 | FaZe            | W   | 1.000      | 0.581        | 0.639 (0.371)    | 0.402 (0.234)    | 1 (1.000) |    20.86 | alex, isak, maxster, r1nkle, REZ               |
|           36 |       95 | 2024-08-01 | Cloud9          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.30 | alex, isak, maxster, r1nkle, REZ               |
|           35 |      146 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.28 | alex, isak, maxster, r1nkle, REZ               |
|           34 |      499 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -29.74 | alex, isak, maxster, r1nkle, REZ               |
|           33 |      576 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | -                | 1.000 (0.500)    | -         |     1.59 | alex, isak, maxster, r1nkle, REZ               |
|           32 |      700 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.465 (0.233)    | -         |     0.28 | alex, isak, maxster, r1nkle, REZ               |
|           31 |      967 | 2024-06-16 | fnatic          | L   | 0.875      | -            | -                | -                | -         |   -19.24 | alex, isak, maxster, r1nkle, REZ               |
|           30 |     1027 | 2024-06-14 | paiN            | W   | 0.863      | 0.548        | 0.327 (0.155)    | 0.866 (0.410)    | 1 (0.863) |     5.46 | alex, isak, maxster, r1nkle, REZ               |
|           29 |     1033 | 2024-06-14 | 9z              | W   | 0.862      | 0.548        | 0.405 (0.192)    | 0.618 (0.292)    | 1 (0.862) |     8.03 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1199 | 2024-06-09 | The MongolZ     | L   | 0.827      | -            | -                | -                | -         |    -4.30 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1259 | 2024-06-08 | FURIA           | W   | 0.821      | 0.715        | 0.284 (0.167)    | 0.490 (0.288)    | 1 (0.821) |    12.71 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1313 | 2024-06-07 | fnatic          | W   | 0.815      | 0.715        | 0.371 (0.216)    | 0.708 (0.413)    | 1 (0.815) |     8.56 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1370 | 2024-06-06 | Sashi           | W   | 0.808      | 0.715        | 0.184 (0.106)    | 0.962 (0.556)    | 1 (0.808) |     2.66 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1396 | 2024-06-06 | The MongolZ     | L   | 0.807      | -            | -                | -                | -         |    -3.69 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1409 | 2024-06-06 | Astralis        | W   | 0.806      | 0.715        | 0.391 (0.225)    | 0.421 (0.243)    | 1 (0.806) |    17.44 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1446 | 2024-06-05 | HEROIC          | W   | 0.801      | 0.715        | 0.229 (0.131)    | -                | 1 (0.801) |    12.65 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1457 | 2024-06-05 | ENCE            | W   | 0.800      | 0.715        | 0.169 (0.097)    | -                | 1 (0.800) |     5.88 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1909 | 2024-05-19 | Sangal          | L   | 0.688      | -            | -                | -                | -         |   -20.20 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     1936 | 2024-05-18 | Metizport       | L   | 0.682      | -            | -                | -                | -         |   -20.80 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     2006 | 2024-05-16 | Sangal          | W   | 0.668      | 0.500        | -                | 0.861 (0.288)    | -         |     1.13 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2329 | 2024-05-05 | FlyQuest        | L   | 0.593      | -            | -                | -                | -         |   -17.04 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2337 | 2024-05-04 | HEROIC          | W   | 0.587      | 0.889        | 0.229 (0.119)    | -                | -         |     8.00 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2351 | 2024-05-03 | BOSS            | W   | 0.581      | -            | -                | -                | -         |     0.23 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2381 | 2024-05-02 | PERA            | L   | 0.574      | -            | -                | -                | -         |   -17.73 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2426 | 2024-04-30 | HEROIC          | L   | 0.561      | -            | -                | -                | -         |   -10.18 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2734 | 2024-04-18 | brazylijski luz | L   | 0.481      | -            | -                | -                | -         |   -15.01 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2880 | 2024-04-12 | OG              | L   | 0.440      | -            | -                | -                | -         |   -13.48 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2905 | 2024-04-11 | BetBoom         | L   | 0.434      | -            | -                | -                | -         |   -11.06 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     3001 | 2024-04-09 | Gods Reign      | W   | 0.421      | -            | -                | -                | -         |     0.10 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3133 | 2024-04-04 | Aurora          | L   | 0.388      | -            | -                | -                | -         |    -6.31 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3142 | 2024-04-04 | Metizport       | W   | 0.387      | -            | -                | -                | -         |     0.19 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3173 | 2024-04-03 | Aurora          | L   | 0.381      | -            | -                | -                | -         |    -6.42 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3193 | 2024-04-03 | Sampi           | L   | 0.379      | -            | -                | -                | -         |   -11.80 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3210 | 2024-04-02 | FAVBET          | W   | 0.375      | -            | -                | -                | -         |     0.07 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3218 | 2024-04-02 | Monte           | W   | 0.374      | -            | -                | -                | -         |     0.22 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3303 | 2024-03-27 | 500             | W   | 0.335      | -            | -                | -                | -         |     0.05 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3311 | 2024-03-27 | Verdant         | W   | 0.335      | -            | -                | -                | -         |     0.15 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($82,567.84)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-06-16 |      0.876 | $7,000.00      | $6,134.88       |
| 2024-06-09 |      0.827 | $56,000.00     | $46,330.93      |
| 2024-05-12 |      0.641 | $12,000.00     | $7,688.06       |
| 2024-04-14 |      0.454 | $26,250.00     | $11,913.98      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
