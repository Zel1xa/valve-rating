### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1437.6<br />
<br />
Final Rank Value (1437.6) = Starting Rank Value (1499.5) + Head To Head Adjustments (-61.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.594[<sup>1</sup>](#table2)
- Bounty Collected: 0.517[<sup>2</sup>](#table1)
- Opponent Network: 0.312[<sup>2</sup>](#table1)
- LAN Wins: 0.713[<sup>2</sup>](#table1)

The average of these factors is 0.534<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1499.5
- 400 + ( ( 0.534 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1499.5


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
|           32 |       49 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -1.71 | alex, isak, maxster, r1nkle, REZ               |
|           31 |      406 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -27.93 | alex, isak, maxster, r1nkle, REZ               |
|           30 |      488 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | 0.141 (0.070)    | 1.000 (0.500)    | 0 (0.000) |     3.28 | alex, isak, maxster, r1nkle, REZ               |
|           29 |      615 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.504 (0.252)    | 0 (0.000) |     0.69 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1111 | 2024-06-09 | The MongolZ     | L   | 0.848      | -            | -                | -                | -         |    -2.23 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1173 | 2024-06-08 | FURIA           | W   | 0.842      | 0.715        | 0.286 (0.172)    | 0.495 (0.298)    | 1 (0.842) |    18.05 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1234 | 2024-06-07 | fnatic          | W   | 0.835      | 0.715        | 0.292 (0.174)    | 0.529 (0.316)    | 1 (0.835) |     9.56 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1293 | 2024-06-06 | Sashi           | W   | 0.829      | 0.715        | 0.187 (0.111)    | 0.971 (0.575)    | 1 (0.829) |     5.59 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1319 | 2024-06-06 | The MongolZ     | L   | 0.827      | -            | -                | -                | -         |    -1.75 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1333 | 2024-06-06 | Astralis        | W   | 0.826      | 0.715        | 0.359 (0.212)    | 0.385 (0.228)    | 1 (0.826) |    21.07 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1372 | 2024-06-05 | HEROIC          | W   | 0.821      | 0.715        | 0.209 (0.123)    | 0.381 (0.224)    | 1 (0.821) |    18.18 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1383 | 2024-06-05 | ENCE            | W   | 0.820      | 0.715        | 0.174 (0.102)    | 0.403 (0.237)    | 1 (0.820) |    10.89 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1863 | 2024-05-19 | Sangal          | L   | 0.708      | -            | -                | -                | -         |   -18.89 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     1890 | 2024-05-18 | Metizport       | L   | 0.702      | -            | -                | -                | -         |   -20.38 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     1961 | 2024-05-16 | Sangal          | W   | 0.688      | 0.500        | 0.221 (0.076)    | 0.823 (0.283)    | -         |     2.68 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2295 | 2024-05-05 | FlyQuest        | L   | 0.613      | -            | -                | -                | -         |   -15.12 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2303 | 2024-05-04 | HEROIC          | W   | 0.608      | 0.889        | 0.209 (0.113)    | 0.381 (0.206)    | 1 (0.608) |    12.81 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2317 | 2024-05-03 | BOSS            | W   | 0.602      | -            | -                | -                | 1 (0.602) |     0.66 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2348 | 2024-05-02 | PERA            | L   | 0.594      | -            | -                | -                | -         |   -17.77 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2395 | 2024-04-30 | HEROIC          | L   | 0.581      | -            | -                | -                | -         |    -5.95 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2711 | 2024-04-18 | brazylijski luz | L   | 0.501      | -            | -                | -                | -         |   -15.35 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2859 | 2024-04-12 | OG              | L   | 0.460      | -            | -                | -                | -         |   -13.42 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2885 | 2024-04-11 | BetBoom         | L   | 0.454      | -            | -                | -                | -         |    -8.41 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     2981 | 2024-04-09 | Gods Reign      | W   | 0.441      | 0.684        | 0.042 (0.013)    | -                | -         |     0.30 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3113 | 2024-04-04 | Aurora          | L   | 0.408      | -            | -                | -                | -         |    -3.34 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3123 | 2024-04-04 | Metizport       | W   | 0.407      | -            | -                | -                | -         |     0.57 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3155 | 2024-04-03 | Aurora          | L   | 0.402      | -            | -                | -                | -         |    -3.37 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3179 | 2024-04-03 | Sampi           | L   | 0.399      | -            | -                | -                | -         |   -12.13 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3198 | 2024-04-02 | FAVBET          | W   | 0.395      | -            | -                | -                | -         |     0.23 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3206 | 2024-04-02 | Monte           | W   | 0.394      | -            | -                | -                | -         |     0.70 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3292 | 2024-03-27 | 500             | W   | 0.355      | -            | -                | -                | -         |     0.17 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3300 | 2024-03-27 | Verdant         | W   | 0.355      | -            | -                | -                | -         |     0.49 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($67,833.23)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.848 | $56,000.00     | $47,460.00      |
| 2024-05-12 |      0.661 | $12,000.00     | $7,930.00       |
| 2024-04-14 |      0.474 | $26,250.00     | $12,443.23      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
