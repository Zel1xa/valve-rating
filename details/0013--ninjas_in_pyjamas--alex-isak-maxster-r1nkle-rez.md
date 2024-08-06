### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1573.4<br />
<br />
Final Rank Value (1573.4) = Starting Rank Value (1687.8) + Head To Head Adjustments (-114.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.627[<sup>1</sup>](#table2)
- Bounty Collected: 0.568[<sup>2</sup>](#table1)
- Opponent Network: 0.331[<sup>2</sup>](#table1)
- LAN Wins: 0.978[<sup>2</sup>](#table1)

The average of these factors is 0.626<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1687.8
- 400 + ( ( 0.626 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1687.8


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
|           39 |       58 | 2024-08-04 | Astralis        | L   | 1.000      | -            | -                | -                | -         |   -10.65 | alex, isak, maxster, r1nkle, REZ               |
|           38 |       82 | 2024-08-03 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.40 | alex, isak, maxster, r1nkle, REZ               |
|           37 |      121 | 2024-08-02 | FaZe            | W   | 1.000      | 0.581        | 0.624 (0.363)    | -                | 1 (1.000) |    20.61 | alex, isak, maxster, r1nkle, REZ               |
|           36 |      165 | 2024-08-01 | Cloud9          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.30 | alex, isak, maxster, r1nkle, REZ               |
|           35 |      217 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.27 | alex, isak, maxster, r1nkle, REZ               |
|           34 |      570 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -29.65 | alex, isak, maxster, r1nkle, REZ               |
|           33 |      644 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | -                | 0.961 (0.481)    | -         |     1.65 | alex, isak, maxster, r1nkle, REZ               |
|           32 |      771 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.447 (0.223)    | -         |     0.29 | alex, isak, maxster, r1nkle, REZ               |
|           31 |     1038 | 2024-06-16 | fnatic          | L   | 0.861      | -            | -                | -                | -         |   -18.90 | alex, isak, maxster, r1nkle, REZ               |
|           30 |     1098 | 2024-06-14 | paiN            | W   | 0.849      | 0.548        | 0.324 (0.151)    | 0.839 (0.390)    | 1 (0.849) |     5.22 | alex, isak, maxster, r1nkle, REZ               |
|           29 |     1104 | 2024-06-14 | 9z              | W   | 0.848      | 0.548        | 0.404 (0.188)    | 0.591 (0.274)    | 1 (0.848) |     7.81 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1270 | 2024-06-09 | The MongolZ     | L   | 0.813      | -            | -                | -                | -         |    -4.19 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1330 | 2024-06-08 | FURIA           | W   | 0.807      | 0.715        | 0.284 (0.164)    | 0.468 (0.270)    | 1 (0.807) |    12.59 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1384 | 2024-06-07 | fnatic          | W   | 0.800      | 0.715        | 0.371 (0.212)    | 0.680 (0.389)    | 1 (0.800) |     8.45 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1441 | 2024-06-06 | Sashi           | W   | 0.794      | 0.715        | 0.184 (0.104)    | 0.958 (0.544)    | 1 (0.794) |     2.63 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1467 | 2024-06-06 | The MongolZ     | L   | 0.793      | -            | -                | -                | -         |    -3.59 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1480 | 2024-06-06 | Astralis        | W   | 0.792      | 0.715        | 0.389 (0.220)    | 0.403 (0.228)    | 1 (0.792) |    17.04 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1517 | 2024-06-05 | HEROIC          | W   | 0.787      | 0.715        | 0.224 (0.126)    | -                | 1 (0.787) |    12.28 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1528 | 2024-06-05 | ENCE            | W   | 0.786      | 0.715        | 0.173 (0.097)    | 0.422 (0.237)    | 1 (0.786) |     6.04 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1980 | 2024-05-19 | Sangal          | L   | 0.674      | -            | -                | -                | -         |   -19.68 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     2007 | 2024-05-18 | Metizport       | L   | 0.667      | -            | -                | -                | -         |   -20.35 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     2077 | 2024-05-16 | Sangal          | W   | 0.654      | 0.500        | -                | 0.846 (0.277)    | -         |     1.18 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2400 | 2024-05-05 | FlyQuest        | L   | 0.579      | -            | -                | -                | -         |   -16.68 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2408 | 2024-05-04 | HEROIC          | W   | 0.573      | 0.889        | 0.224 (0.114)    | -                | -         |     7.74 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2422 | 2024-05-03 | BOSS            | W   | 0.567      | -            | -                | -                | -         |     0.22 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2452 | 2024-05-02 | PERA            | L   | 0.560      | -            | -                | -                | -         |   -17.29 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2497 | 2024-04-30 | HEROIC          | L   | 0.546      | -            | -                | -                | -         |   -10.00 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2805 | 2024-04-18 | brazylijski luz | L   | 0.467      | -            | -                | -                | -         |   -14.56 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2951 | 2024-04-12 | OG              | L   | 0.426      | -            | -                | -                | -         |   -13.05 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2976 | 2024-04-11 | BetBoom         | L   | 0.420      | -            | -                | -                | -         |   -10.74 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     3072 | 2024-04-09 | Gods Reign      | W   | 0.407      | -            | -                | -                | -         |     0.09 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3204 | 2024-04-04 | Aurora          | L   | 0.374      | -            | -                | -                | -         |    -5.88 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3213 | 2024-04-04 | Metizport       | W   | 0.373      | -            | -                | -                | -         |     0.19 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3244 | 2024-04-03 | Aurora          | L   | 0.367      | -            | -                | -                | -         |    -5.96 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3264 | 2024-04-03 | Sampi           | L   | 0.365      | -            | -                | -                | -         |   -11.35 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3281 | 2024-04-02 | FAVBET          | W   | 0.360      | -            | -                | -                | -         |     0.07 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3289 | 2024-04-02 | Monte           | W   | 0.359      | -            | -                | -                | -         |     0.21 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3374 | 2024-03-27 | 500             | W   | 0.321      | -            | -                | -                | -         |     0.04 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3382 | 2024-03-27 | Verdant         | W   | 0.321      | -            | -                | -                | -         |     0.15 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($81,121.75)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-06-16 |      0.862 | $7,000.00      | $6,034.91       |
| 2024-06-09 |      0.813 | $56,000.00     | $45,531.11      |
| 2024-05-12 |      0.626 | $12,000.00     | $7,516.67       |
| 2024-04-14 |      0.440 | $26,250.00     | $11,539.06      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
