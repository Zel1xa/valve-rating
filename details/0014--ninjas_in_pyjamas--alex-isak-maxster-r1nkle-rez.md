### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Global Rank: [14](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1550.1<br />
<br />
Final Rank Value (1550.1) = Starting Rank Value (1616.7) + Head To Head Adjustments (-66.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.591[<sup>1</sup>](#table2)
- Bounty Collected: 0.550[<sup>2</sup>](#table1)
- Opponent Network: 0.318[<sup>2</sup>](#table1)
- LAN Wins: 0.919[<sup>2</sup>](#table1)

The average of these factors is 0.595<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1616.7
- 400 + ( ( 0.595 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1616.7


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
|           34 |        0 | 2024-08-03 | G2              | L   | 1.000      | -            | -                | -                | -         |    -2.98 | alex, isak, maxster, r1nkle, REZ               |
|           33 |       34 | 2024-08-02 | FaZe            | W   | 1.000      | 0.581        | 0.644 (0.374)    | 0.418 (0.243)    | 1 (1.000) |    22.26 | alex, isak, maxster, r1nkle, REZ               |
|           32 |       64 | 2024-08-01 | Cloud9          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.37 | alex, isak, maxster, r1nkle, REZ               |
|           31 |      113 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -2.82 | alex, isak, maxster, r1nkle, REZ               |
|           30 |      465 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -29.49 | alex, isak, maxster, r1nkle, REZ               |
|           29 |      539 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | 0.139 (0.070)    | 1.000 (0.500)    | -         |     1.85 | alex, isak, maxster, r1nkle, REZ               |
|           28 |      663 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.441 (0.220)    | -         |     0.32 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1132 | 2024-06-09 | The MongolZ     | L   | 0.833      | -            | -                | -                | -         |    -3.56 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1190 | 2024-06-08 | FURIA           | W   | 0.827      | 0.715        | 0.284 (0.168)    | 0.508 (0.301)    | 1 (0.827) |    14.01 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1241 | 2024-06-07 | fnatic          | W   | 0.820      | 0.715        | 0.290 (0.170)    | 0.627 (0.368)    | 1 (0.820) |     6.16 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1297 | 2024-06-06 | Sashi           | W   | 0.814      | 0.715        | 0.184 (0.107)    | 0.998 (0.581)    | 1 (0.814) |     3.31 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1324 | 2024-06-06 | The MongolZ     | L   | 0.813      | -            | -                | -                | -         |    -3.00 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1337 | 2024-06-06 | Astralis        | W   | 0.811      | 0.715        | 0.353 (0.205)    | 0.396 (0.230)    | 1 (0.811) |    17.92 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1374 | 2024-06-05 | HEROIC          | W   | 0.807      | 0.715        | 0.230 (0.133)    | 0.388 (0.224)    | 1 (0.807) |    14.06 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1385 | 2024-06-05 | ENCE            | W   | 0.805      | 0.715        | 0.170 (0.098)    | 0.415 (0.239)    | 1 (0.805) |     6.74 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     1859 | 2024-05-18 | Metizport       | L   | 0.687      | -            | -                | -                | -         |   -20.67 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     1929 | 2024-05-16 | Sangal          | W   | 0.674      | 0.500        | 0.219 (0.074)    | 0.823 (0.277)    | -         |     1.59 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2251 | 2024-05-05 | FlyQuest        | L   | 0.599      | -            | -                | -                | -         |   -16.52 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2259 | 2024-05-04 | HEROIC          | W   | 0.593      | 0.889        | 0.230 (0.121)    | -                | 1 (0.593) |     9.73 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2273 | 2024-05-03 | BOSS            | W   | 0.587      | -            | -                | -                | 1 (0.587) |     0.34 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2303 | 2024-05-02 | PERA            | L   | 0.579      | -            | -                | -                | -         |   -17.74 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2348 | 2024-04-30 | HEROIC          | L   | 0.566      | -            | -                | -                | -         |    -8.63 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2655 | 2024-04-18 | brazylijski luz | L   | 0.486      | -            | -                | -                | -         |   -15.11 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2801 | 2024-04-12 | OG              | L   | 0.446      | -            | -                | -                | -         |   -13.49 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2826 | 2024-04-11 | BetBoom         | L   | 0.440      | -            | -                | -                | -         |   -10.24 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     2922 | 2024-04-09 | Gods Reign      | W   | 0.427      | -            | -                | -                | -         |     0.15 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3054 | 2024-04-04 | Aurora          | L   | 0.394      | -            | -                | -                | -         |    -5.07 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3063 | 2024-04-04 | Metizport       | W   | 0.392      | -            | -                | -                | -         |     0.29 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3094 | 2024-04-03 | Aurora          | L   | 0.387      | -            | -                | -                | -         |    -5.15 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3114 | 2024-04-03 | Sampi           | L   | 0.385      | -            | -                | -                | -         |   -11.89 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3131 | 2024-04-02 | FAVBET          | W   | 0.380      | -            | -                | -                | -         |     0.12 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3139 | 2024-04-02 | Monte           | W   | 0.379      | -            | -                | -                | -         |     0.34 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3223 | 2024-03-27 | 500             | W   | 0.341      | -            | -                | -                | -         |     0.07 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3231 | 2024-03-27 | Verdant         | W   | 0.340      | -            | -                | -                | -         |     0.23 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($66,450.02)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.20) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.833 | $56,000.00     | $46,638.15      |
| 2024-05-12 |      0.646 | $12,000.00     | $7,753.89       |
| 2024-04-14 |      0.459 | $26,250.00     | $12,057.99      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
