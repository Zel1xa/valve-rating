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
Final Rank Value (1573.3) = Starting Rank Value (1688.0) + Head To Head Adjustments (-114.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.627[<sup>1</sup>](#table2)
- Bounty Collected: 0.568[<sup>2</sup>](#table1)
- Opponent Network: 0.332[<sup>2</sup>](#table1)
- LAN Wins: 0.978[<sup>2</sup>](#table1)

The average of these factors is 0.626<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1688.0
- 400 + ( ( 0.626 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1688.0


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
|           39 |       49 | 2024-08-04 | Astralis        | L   | 1.000      | -            | -                | -                | -         |   -10.64 | alex, isak, maxster, r1nkle, REZ               |
|           38 |       71 | 2024-08-03 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.40 | alex, isak, maxster, r1nkle, REZ               |
|           37 |      108 | 2024-08-02 | FaZe            | W   | 1.000      | 0.581        | 0.625 (0.363)    | -                | 1 (1.000) |    20.63 | alex, isak, maxster, r1nkle, REZ               |
|           36 |      152 | 2024-08-01 | Cloud9          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.30 | alex, isak, maxster, r1nkle, REZ               |
|           35 |      204 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.27 | alex, isak, maxster, r1nkle, REZ               |
|           34 |      557 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -29.68 | alex, isak, maxster, r1nkle, REZ               |
|           33 |      631 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | -                | 0.962 (0.481)    | -         |     1.62 | alex, isak, maxster, r1nkle, REZ               |
|           32 |      758 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.447 (0.223)    | -         |     0.29 | alex, isak, maxster, r1nkle, REZ               |
|           31 |     1025 | 2024-06-16 | fnatic          | L   | 0.862      | -            | -                | -                | -         |   -18.92 | alex, isak, maxster, r1nkle, REZ               |
|           30 |     1085 | 2024-06-14 | paiN            | W   | 0.850      | 0.548        | 0.324 (0.151)    | 0.839 (0.391)    | 1 (0.850) |     5.23 | alex, isak, maxster, r1nkle, REZ               |
|           29 |     1091 | 2024-06-14 | 9z              | W   | 0.848      | 0.548        | 0.404 (0.188)    | 0.591 (0.275)    | 1 (0.848) |     7.82 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1257 | 2024-06-09 | The MongolZ     | L   | 0.814      | -            | -                | -                | -         |    -4.19 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1317 | 2024-06-08 | FURIA           | W   | 0.808      | 0.715        | 0.284 (0.164)    | 0.469 (0.271)    | 1 (0.808) |    12.59 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1371 | 2024-06-07 | fnatic          | W   | 0.801      | 0.715        | 0.371 (0.212)    | 0.680 (0.390)    | 1 (0.801) |     8.45 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1428 | 2024-06-06 | Sashi           | W   | 0.795      | 0.715        | 0.184 (0.104)    | 0.958 (0.545)    | 1 (0.795) |     2.62 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1454 | 2024-06-06 | The MongolZ     | L   | 0.794      | -            | -                | -                | -         |    -3.60 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1467 | 2024-06-06 | Astralis        | W   | 0.792      | 0.715        | 0.389 (0.220)    | 0.403 (0.228)    | 1 (0.792) |    17.06 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1504 | 2024-06-05 | HEROIC          | W   | 0.788      | 0.715        | 0.224 (0.126)    | -                | 1 (0.788) |    12.29 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1515 | 2024-06-05 | ENCE            | W   | 0.786      | 0.715        | 0.173 (0.097)    | 0.422 (0.237)    | 1 (0.786) |     6.04 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1967 | 2024-05-19 | Sangal          | L   | 0.675      | -            | -                | -                | -         |   -19.75 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     1994 | 2024-05-18 | Metizport       | L   | 0.668      | -            | -                | -                | -         |   -20.40 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     2064 | 2024-05-16 | Sangal          | W   | 0.655      | 0.500        | -                | 0.846 (0.277)    | -         |     1.16 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2387 | 2024-05-05 | FlyQuest        | L   | 0.579      | -            | -                | -                | -         |   -16.70 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2395 | 2024-05-04 | HEROIC          | W   | 0.574      | 0.889        | 0.224 (0.114)    | -                | -         |     7.75 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2409 | 2024-05-03 | BOSS            | W   | 0.568      | -            | -                | -                | -         |     0.22 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2439 | 2024-05-02 | PERA            | L   | 0.560      | -            | -                | -                | -         |   -17.31 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2484 | 2024-04-30 | HEROIC          | L   | 0.547      | -            | -                | -                | -         |   -10.02 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2792 | 2024-04-18 | brazylijski luz | L   | 0.467      | -            | -                | -                | -         |   -14.59 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2938 | 2024-04-12 | OG              | L   | 0.427      | -            | -                | -                | -         |   -13.07 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2963 | 2024-04-11 | BetBoom         | L   | 0.421      | -            | -                | -                | -         |   -10.75 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     3059 | 2024-04-09 | Gods Reign      | W   | 0.408      | -            | -                | -                | -         |     0.09 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3191 | 2024-04-04 | Aurora          | L   | 0.374      | -            | -                | -                | -         |    -5.89 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3200 | 2024-04-04 | Metizport       | W   | 0.373      | -            | -                | -                | -         |     0.18 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3231 | 2024-04-03 | Aurora          | L   | 0.368      | -            | -                | -                | -         |    -5.98 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3251 | 2024-04-03 | Sampi           | L   | 0.366      | -            | -                | -                | -         |   -11.38 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3268 | 2024-04-02 | FAVBET          | W   | 0.361      | -            | -                | -                | -         |     0.07 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3276 | 2024-04-02 | Monte           | W   | 0.360      | -            | -                | -                | -         |     0.21 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3361 | 2024-03-27 | 500             | W   | 0.322      | -            | -                | -                | -         |     0.04 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3369 | 2024-03-27 | Verdant         | W   | 0.321      | -            | -                | -                | -         |     0.15 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($81,196.75)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-06-16 |      0.863 | $7,000.00      | $6,040.09       |
| 2024-06-09 |      0.814 | $56,000.00     | $45,572.59      |
| 2024-05-12 |      0.627 | $12,000.00     | $7,525.56       |
| 2024-04-14 |      0.440 | $26,250.00     | $11,558.51      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
