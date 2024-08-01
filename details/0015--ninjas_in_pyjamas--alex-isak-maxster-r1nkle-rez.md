### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Global Rank: [15](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [12]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1475.6<br />
<br />
Final Rank Value (1475.6) = Starting Rank Value (1556.8) + Head To Head Adjustments (-81.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.594[<sup>1</sup>](#table2)
- Bounty Collected: 0.517[<sup>2</sup>](#table1)
- Opponent Network: 0.311[<sup>2</sup>](#table1)
- LAN Wins: 0.827[<sup>2</sup>](#table1)

The average of these factors is 0.562<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1556.8
- 400 + ( ( 0.562 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1556.8


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
|           33 |        3 | 2024-08-01 | Cloud9          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.21 | alex, isak, maxster, r1nkle, REZ               |
|           32 |       53 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -2.08 | alex, isak, maxster, r1nkle, REZ               |
|           31 |      410 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -28.56 | alex, isak, maxster, r1nkle, REZ               |
|           30 |      492 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | 0.141 (0.070)    | 1.000 (0.500)    | 0 (0.000) |     2.68 | alex, isak, maxster, r1nkle, REZ               |
|           29 |      619 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.504 (0.252)    | -         |     0.55 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1115 | 2024-06-09 | The MongolZ     | L   | 0.846      | -            | -                | -                | -         |    -2.71 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1177 | 2024-06-08 | FURIA           | W   | 0.840      | 0.715        | 0.286 (0.172)    | 0.494 (0.297)    | 1 (0.840) |    16.68 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1238 | 2024-06-07 | fnatic          | W   | 0.834      | 0.715        | 0.292 (0.174)    | 0.529 (0.316)    | 1 (0.834) |     8.14 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1297 | 2024-06-06 | Sashi           | W   | 0.827      | 0.715        | 0.187 (0.110)    | 0.970 (0.574)    | 1 (0.827) |     4.58 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1323 | 2024-06-06 | The MongolZ     | L   | 0.826      | -            | -                | -                | -         |    -2.18 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1337 | 2024-06-06 | Astralis        | W   | 0.825      | 0.715        | 0.359 (0.212)    | 0.385 (0.227)    | 1 (0.825) |    19.99 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1376 | 2024-06-05 | HEROIC          | W   | 0.820      | 0.715        | 0.208 (0.122)    | 0.380 (0.223)    | 1 (0.820) |    16.76 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1387 | 2024-06-05 | ENCE            | W   | 0.819      | 0.715        | 0.174 (0.102)    | 0.403 (0.236)    | 1 (0.819) |     9.26 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1867 | 2024-05-19 | Sangal          | L   | 0.707      | -            | -                | -                | -         |   -19.57 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     1894 | 2024-05-18 | Metizport       | L   | 0.700      | -            | -                | -                | -         |   -20.73 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     1965 | 2024-05-16 | Sangal          | W   | 0.687      | 0.500        | 0.221 (0.076)    | 0.823 (0.283)    | -         |     2.08 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2299 | 2024-05-05 | FlyQuest        | L   | 0.612      | -            | -                | -                | -         |   -15.95 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2307 | 2024-05-04 | HEROIC          | W   | 0.606      | 0.889        | 0.208 (0.112)    | 0.380 (0.205)    | 1 (0.606) |    11.54 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2321 | 2024-05-03 | BOSS            | W   | 0.600      | -            | -                | -                | 1 (0.600) |     0.49 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2352 | 2024-05-02 | PERA            | L   | 0.593      | -            | -                | -                | -         |   -17.96 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2399 | 2024-04-30 | HEROIC          | L   | 0.579      | -            | -                | -                | -         |    -7.18 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2715 | 2024-04-18 | brazylijski luz | L   | 0.500      | -            | -                | -                | -         |   -15.42 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2863 | 2024-04-12 | OG              | L   | 0.459      | -            | -                | -                | -         |   -13.65 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2889 | 2024-04-11 | BetBoom         | L   | 0.453      | -            | -                | -                | -         |    -9.44 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     2985 | 2024-04-09 | Gods Reign      | W   | 0.440      | 0.684        | 0.042 (0.013)    | -                | -         |     0.22 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3117 | 2024-04-04 | Aurora          | L   | 0.407      | -            | -                | -                | -         |    -4.16 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3127 | 2024-04-04 | Metizport       | W   | 0.406      | -            | -                | -                | -         |     0.42 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3159 | 2024-04-03 | Aurora          | L   | 0.400      | -            | -                | -                | -         |    -4.22 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3183 | 2024-04-03 | Sampi           | L   | 0.398      | -            | -                | -                | -         |   -12.21 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3202 | 2024-04-02 | FAVBET          | W   | 0.394      | -            | -                | -                | -         |     0.17 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3210 | 2024-04-02 | Monte           | W   | 0.392      | -            | -                | -                | -         |     0.51 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3296 | 2024-03-27 | 500             | W   | 0.354      | -            | -                | -                | -         |     0.12 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3304 | 2024-03-27 | Verdant         | W   | 0.354      | -            | -                | -                | -         |     0.36 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($67,702.33)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.846 | $56,000.00     | $47,382.22      |
| 2024-05-12 |      0.659 | $12,000.00     | $7,913.33       |
| 2024-04-14 |      0.473 | $26,250.00     | $12,406.77      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
