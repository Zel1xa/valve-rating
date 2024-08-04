### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1574.7<br />
<br />
Final Rank Value (1574.7) = Starting Rank Value (1678.9) + Head To Head Adjustments (-104.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.605[<sup>1</sup>](#table2)
- Bounty Collected: 0.571[<sup>2</sup>](#table1)
- Opponent Network: 0.346[<sup>2</sup>](#table1)
- LAN Wins: 0.982[<sup>2</sup>](#table1)

The average of these factors is 0.626<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1678.9
- 400 + ( ( 0.626 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1678.9


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
|           38 |        2 | 2024-08-03 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.30 | alex, isak, maxster, r1nkle, REZ               |
|           37 |       41 | 2024-08-02 | FaZe            | W   | 1.000      | 0.581        | 0.643 (0.373)    | 0.403 (0.234)    | 1 (1.000) |    21.15 | alex, isak, maxster, r1nkle, REZ               |
|           36 |       84 | 2024-08-01 | Cloud9          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.32 | alex, isak, maxster, r1nkle, REZ               |
|           35 |      135 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.16 | alex, isak, maxster, r1nkle, REZ               |
|           34 |      488 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -29.68 | alex, isak, maxster, r1nkle, REZ               |
|           33 |      565 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | -                | 1.000 (0.500)    | -         |     1.67 | alex, isak, maxster, r1nkle, REZ               |
|           32 |      689 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.465 (0.233)    | -         |     0.30 | alex, isak, maxster, r1nkle, REZ               |
|           31 |      955 | 2024-06-16 | fnatic          | L   | 0.879      | -            | -                | -                | -         |   -19.03 | alex, isak, maxster, r1nkle, REZ               |
|           30 |     1015 | 2024-06-14 | paiN            | W   | 0.867      | 0.548        | 0.328 (0.156)    | 0.865 (0.411)    | 1 (0.867) |     5.76 | alex, isak, maxster, r1nkle, REZ               |
|           29 |     1021 | 2024-06-14 | 9z              | W   | 0.866      | 0.548        | 0.406 (0.193)    | 0.619 (0.294)    | 1 (0.866) |     8.32 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1187 | 2024-06-09 | The MongolZ     | L   | 0.831      | -            | -                | -                | -         |    -4.20 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1247 | 2024-06-08 | FURIA           | W   | 0.825      | 0.715        | 0.284 (0.168)    | 0.491 (0.290)    | 1 (0.825) |    13.04 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1301 | 2024-06-07 | fnatic          | W   | 0.819      | 0.715        | 0.371 (0.217)    | 0.709 (0.415)    | 1 (0.819) |     8.93 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1358 | 2024-06-06 | Sashi           | W   | 0.812      | 0.715        | 0.184 (0.107)    | 0.964 (0.560)    | 1 (0.812) |     2.81 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1384 | 2024-06-06 | The MongolZ     | L   | 0.811      | -            | -                | -                | -         |    -3.55 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1397 | 2024-06-06 | Astralis        | W   | 0.810      | 0.715        | 0.353 (0.204)    | -                | 1 (0.810) |    16.70 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1434 | 2024-06-05 | HEROIC          | W   | 0.805      | 0.715        | 0.229 (0.132)    | -                | 1 (0.805) |    13.01 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1445 | 2024-06-05 | ENCE            | W   | 0.804      | 0.715        | 0.170 (0.098)    | 0.401 (0.230)    | 1 (0.804) |     6.11 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1897 | 2024-05-19 | Sangal          | L   | 0.692      | -            | -                | -                | -         |   -20.22 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     1924 | 2024-05-18 | Metizport       | L   | 0.685      | -            | -                | -                | -         |   -20.87 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     1994 | 2024-05-16 | Sangal          | W   | 0.672      | 0.500        | -                | 0.862 (0.290)    | -         |     1.20 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2317 | 2024-05-05 | FlyQuest        | L   | 0.597      | -            | -                | -                | -         |   -17.05 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2325 | 2024-05-04 | HEROIC          | W   | 0.591      | 0.889        | 0.229 (0.121)    | -                | -         |     8.32 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2339 | 2024-05-03 | BOSS            | W   | 0.585      | -            | -                | -                | -         |     0.24 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2369 | 2024-05-02 | PERA            | L   | 0.578      | -            | -                | -                | -         |   -17.82 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2414 | 2024-04-30 | HEROIC          | L   | 0.564      | -            | -                | -                | -         |    -9.98 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2721 | 2024-04-18 | brazylijski luz | L   | 0.485      | -            | -                | -                | -         |   -15.12 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2867 | 2024-04-12 | OG              | L   | 0.444      | -            | -                | -                | -         |   -13.57 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2892 | 2024-04-11 | BetBoom         | L   | 0.438      | -            | -                | -                | -         |   -11.00 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     2988 | 2024-04-09 | Gods Reign      | W   | 0.425      | -            | -                | -                | -         |     0.10 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3120 | 2024-04-04 | Aurora          | L   | 0.392      | -            | -                | -                | -         |    -6.17 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3129 | 2024-04-04 | Metizport       | W   | 0.391      | -            | -                | -                | -         |     0.21 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3160 | 2024-04-03 | Aurora          | L   | 0.385      | -            | -                | -                | -         |    -6.28 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3180 | 2024-04-03 | Sampi           | L   | 0.383      | -            | -                | -                | -         |   -11.91 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3197 | 2024-04-02 | FAVBET          | W   | 0.379      | -            | -                | -                | -         |     0.08 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3205 | 2024-04-02 | Monte           | W   | 0.377      | -            | -                | -                | -         |     0.24 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3290 | 2024-03-27 | 500             | W   | 0.339      | -            | -                | -                | -         |     0.05 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3298 | 2024-03-27 | Verdant         | W   | 0.339      | -            | -                | -                | -         |     0.16 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($72,449.87)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.880 | $7,000.00      | $6,161.30       |
| 2024-06-09 |      0.831 | $56,000.00     | $46,542.22      |
| 2024-05-12 |      0.644 | $12,000.00     | $7,733.33       |
| 2024-04-14 |      0.458 | $26,250.00     | $12,013.02      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
