### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Global Rank: [14](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1547.6<br />
<br />
Final Rank Value (1547.6) = Starting Rank Value (1659.1) + Head To Head Adjustments (-111.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.629[<sup>1</sup>](#table2)
- Bounty Collected: 0.552[<sup>2</sup>](#table1)
- Opponent Network: 0.344[<sup>2</sup>](#table1)
- LAN Wins: 0.918[<sup>2</sup>](#table1)

The average of these factors is 0.611<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1659.1
- 400 + ( ( 0.611 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1659.1


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
|           35 |       21 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -2.94 | alex, isak, maxster, r1nkle, REZ               |
|           34 |      374 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -29.55 | alex, isak, maxster, r1nkle, REZ               |
|           33 |      448 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | -                | 1.000 (0.500)    | -         |     1.77 | alex, isak, maxster, r1nkle, REZ               |
|           32 |      575 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.465 (0.233)    | -         |     0.32 | alex, isak, maxster, r1nkle, REZ               |
|           31 |      842 | 2024-06-16 | fnatic          | L   | 0.900      | -            | -                | -                | -         |   -18.61 | alex, isak, maxster, r1nkle, REZ               |
|           30 |      902 | 2024-06-14 | paiN            | W   | 0.888      | 0.548        | 0.333 (0.162)    | 0.797 (0.388)    | 1 (0.888) |     6.48 | alex, isak, maxster, r1nkle, REZ               |
|           29 |      908 | 2024-06-14 | 9z              | W   | 0.886      | 0.548        | 0.408 (0.198)    | 0.625 (0.304)    | 1 (0.886) |     9.36 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1074 | 2024-06-09 | The MongolZ     | L   | 0.852      | -            | -                | -                | -         |    -3.87 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1134 | 2024-06-08 | FURIA           | W   | 0.846      | 0.715        | 0.284 (0.172)    | 0.495 (0.300)    | 1 (0.846) |    14.47 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1188 | 2024-06-07 | fnatic          | W   | 0.839      | 0.715        | 0.371 (0.223)    | 0.633 (0.380)    | 1 (0.839) |    10.20 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1245 | 2024-06-06 | Sashi           | W   | 0.833      | 0.715        | 0.185 (0.110)    | 0.973 (0.580)    | 1 (0.833) |     3.27 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1271 | 2024-06-06 | The MongolZ     | L   | 0.832      | -            | -                | -                | -         |    -3.21 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1284 | 2024-06-06 | Astralis        | W   | 0.830      | 0.715        | 0.394 (0.234)    | 0.386 (0.229)    | 1 (0.830) |    18.20 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1321 | 2024-06-05 | HEROIC          | W   | 0.826      | 0.715        | 0.234 (0.138)    | -                | 1 (0.826) |    14.76 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1332 | 2024-06-05 | ENCE            | W   | 0.824      | 0.715        | 0.173 (0.102)    | 0.404 (0.238)    | 1 (0.824) |     7.25 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1784 | 2024-05-19 | Sangal          | L   | 0.713      | -            | -                | -                | -         |   -20.69 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     1811 | 2024-05-18 | Metizport       | L   | 0.706      | -            | -                | -                | -         |   -21.38 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     1881 | 2024-05-16 | Sangal          | W   | 0.693      | 0.500        | 0.219 (0.076)    | 0.824 (0.285)    | -         |     1.33 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2204 | 2024-05-05 | FlyQuest        | L   | 0.618      | -            | -                | -                | -         |   -17.20 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2212 | 2024-05-04 | HEROIC          | W   | 0.612      | 0.889        | 0.234 (0.127)    | -                | 1 (0.612) |     9.81 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2226 | 2024-05-03 | BOSS            | W   | 0.606      | -            | -                | -                | 1 (0.606) |     0.29 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2256 | 2024-05-02 | PERA            | L   | 0.598      | -            | -                | -                | -         |   -18.41 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2301 | 2024-04-30 | HEROIC          | L   | 0.585      | -            | -                | -                | -         |    -9.09 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2609 | 2024-04-18 | brazylijski luz | L   | 0.505      | -            | -                | -                | -         |   -15.74 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2755 | 2024-04-12 | OG              | L   | 0.465      | -            | -                | -                | -         |   -14.11 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2780 | 2024-04-11 | BetBoom         | L   | 0.459      | -            | -                | -                | -         |   -10.99 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     2876 | 2024-04-09 | Gods Reign      | W   | 0.446      | -            | -                | -                | -         |     0.13 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3008 | 2024-04-04 | Aurora          | L   | 0.413      | -            | -                | -                | -         |    -5.84 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3017 | 2024-04-04 | Metizport       | W   | 0.411      | -            | -                | -                | -         |     0.26 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3048 | 2024-04-03 | Aurora          | L   | 0.406      | -            | -                | -                | -         |    -5.95 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3068 | 2024-04-03 | Sampi           | L   | 0.404      | -            | -                | -                | -         |   -12.53 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3085 | 2024-04-02 | FAVBET          | W   | 0.399      | -            | -                | -                | -         |     0.10 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3093 | 2024-04-02 | Monte           | W   | 0.398      | -            | -                | -                | -         |     0.30 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3178 | 2024-03-27 | 500             | W   | 0.360      | -            | -                | -                | -         |     0.06 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3186 | 2024-03-27 | Verdant         | W   | 0.359      | -            | -                | -                | -         |     0.20 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($85,048.47)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.26) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-06-16 |      0.901 | $7,000.00      | $6,306.38       |
| 2024-06-09 |      0.852 | $56,000.00     | $47,702.93      |
| 2024-05-12 |      0.665 | $12,000.00     | $7,982.06       |
| 2024-04-14 |      0.478 | $26,250.00     | $12,557.10      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
