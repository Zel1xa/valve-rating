### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Global Rank: [15](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [12]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1476.7<br />
<br />
Final Rank Value (1476.7) = Starting Rank Value (1557.9) + Head To Head Adjustments (-81.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.594[<sup>1</sup>](#table2)
- Bounty Collected: 0.517[<sup>2</sup>](#table1)
- Opponent Network: 0.313[<sup>2</sup>](#table1)
- LAN Wins: 0.827[<sup>2</sup>](#table1)

The average of these factors is 0.563<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1557.9
- 400 + ( ( 0.563 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1557.9


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
|           33 |        7 | 2024-08-01 | Cloud9          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.46 | alex, isak, maxster, r1nkle, REZ               |
|           32 |       56 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -2.09 | alex, isak, maxster, r1nkle, REZ               |
|           31 |      412 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -28.58 | alex, isak, maxster, r1nkle, REZ               |
|           30 |      492 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | 0.141 (0.070)    | 1.000 (0.500)    | 0 (0.000) |     2.67 | alex, isak, maxster, r1nkle, REZ               |
|           29 |      621 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.504 (0.252)    | -         |     0.55 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1117 | 2024-06-09 | The MongolZ     | L   | 0.846      | -            | -                | -                | -         |    -2.72 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1179 | 2024-06-08 | FURIA           | W   | 0.840      | 0.715        | 0.286 (0.172)    | 0.494 (0.297)    | 1 (0.840) |    16.68 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1240 | 2024-06-07 | fnatic          | W   | 0.833      | 0.715        | 0.292 (0.174)    | 0.568 (0.338)    | 1 (0.833) |     8.12 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1299 | 2024-06-06 | Sashi           | W   | 0.827      | 0.715        | 0.186 (0.110)    | 0.970 (0.574)    | 1 (0.827) |     4.56 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1325 | 2024-06-06 | The MongolZ     | L   | 0.826      | -            | -                | -                | -         |    -2.19 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1339 | 2024-06-06 | Astralis        | W   | 0.824      | 0.715        | 0.359 (0.211)    | 0.385 (0.227)    | 1 (0.824) |    19.96 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1378 | 2024-06-05 | HEROIC          | W   | 0.820      | 0.715        | 0.208 (0.122)    | 0.380 (0.223)    | 1 (0.820) |    16.72 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1389 | 2024-06-05 | ENCE            | W   | 0.818      | 0.715        | 0.173 (0.102)    | 0.403 (0.236)    | 1 (0.818) |     9.26 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1869 | 2024-05-19 | Sangal          | L   | 0.707      | -            | -                | -                | -         |   -19.58 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     1896 | 2024-05-18 | Metizport       | L   | 0.700      | -            | -                | -                | -         |   -20.73 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     1967 | 2024-05-16 | Sangal          | W   | 0.687      | 0.500        | 0.221 (0.076)    | 0.823 (0.283)    | -         |     2.08 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2301 | 2024-05-05 | FlyQuest        | L   | 0.612      | -            | -                | -                | -         |   -15.96 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2309 | 2024-05-04 | HEROIC          | W   | 0.606      | 0.889        | 0.208 (0.112)    | 0.380 (0.205)    | 1 (0.606) |    11.51 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2323 | 2024-05-03 | BOSS            | W   | 0.600      | -            | -                | -                | 1 (0.600) |     0.49 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2354 | 2024-05-02 | PERA            | L   | 0.592      | -            | -                | -                | -         |   -17.95 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2401 | 2024-04-30 | HEROIC          | L   | 0.579      | -            | -                | -                | -         |    -7.20 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2717 | 2024-04-18 | brazylijski luz | L   | 0.499      | -            | -                | -                | -         |   -15.41 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2865 | 2024-04-12 | OG              | L   | 0.459      | -            | -                | -                | -         |   -13.64 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2891 | 2024-04-11 | BetBoom         | L   | 0.453      | -            | -                | -                | -         |    -9.44 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     2987 | 2024-04-09 | Gods Reign      | W   | 0.440      | 0.684        | 0.042 (0.013)    | -                | -         |     0.21 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3119 | 2024-04-04 | Aurora          | L   | 0.407      | -            | -                | -                | -         |    -4.17 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3129 | 2024-04-04 | Metizport       | W   | 0.405      | -            | -                | -                | -         |     0.42 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3161 | 2024-04-03 | Aurora          | L   | 0.400      | -            | -                | -                | -         |    -4.23 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3185 | 2024-04-03 | Sampi           | L   | 0.398      | -            | -                | -                | -         |   -12.20 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3204 | 2024-04-02 | FAVBET          | W   | 0.393      | -            | -                | -                | -         |     0.17 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3212 | 2024-04-02 | Monte           | W   | 0.392      | -            | -                | -                | -         |     0.51 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3298 | 2024-03-27 | 500             | W   | 0.354      | -            | -                | -                | -         |     0.12 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3306 | 2024-03-27 | Verdant         | W   | 0.353      | -            | -                | -                | -         |     0.35 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($67,676.15)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.846 | $56,000.00     | $47,366.67      |
| 2024-05-12 |      0.659 | $12,000.00     | $7,910.00       |
| 2024-04-14 |      0.472 | $26,250.00     | $12,399.48      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
