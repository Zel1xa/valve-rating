### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1573.8<br />
<br />
Final Rank Value (1573.8) = Starting Rank Value (1688.0) + Head To Head Adjustments (-114.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.626[<sup>1</sup>](#table2)
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
|           39 |       62 | 2024-08-04 | Astralis        | L   | 1.000      | -            | -                | -                | -         |   -10.66 | alex, isak, maxster, r1nkle, REZ               |
|           38 |       86 | 2024-08-03 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.41 | alex, isak, maxster, r1nkle, REZ               |
|           37 |      125 | 2024-08-02 | FaZe            | W   | 1.000      | 0.581        | 0.624 (0.363)    | -                | 1 (1.000) |    20.59 | alex, isak, maxster, r1nkle, REZ               |
|           36 |      169 | 2024-08-01 | Cloud9          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.30 | alex, isak, maxster, r1nkle, REZ               |
|           35 |      221 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.28 | alex, isak, maxster, r1nkle, REZ               |
|           34 |      574 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -29.64 | alex, isak, maxster, r1nkle, REZ               |
|           33 |      648 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | -                | 0.961 (0.481)    | -         |     1.66 | alex, isak, maxster, r1nkle, REZ               |
|           32 |      775 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.447 (0.223)    | -         |     0.29 | alex, isak, maxster, r1nkle, REZ               |
|           31 |     1042 | 2024-06-16 | fnatic          | L   | 0.861      | -            | -                | -                | -         |   -18.86 | alex, isak, maxster, r1nkle, REZ               |
|           30 |     1102 | 2024-06-14 | paiN            | W   | 0.849      | 0.548        | 0.324 (0.151)    | 0.839 (0.390)    | 1 (0.849) |     5.21 | alex, isak, maxster, r1nkle, REZ               |
|           29 |     1108 | 2024-06-14 | 9z              | W   | 0.847      | 0.548        | 0.404 (0.188)    | 0.591 (0.274)    | 1 (0.847) |     7.79 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1274 | 2024-06-09 | The MongolZ     | L   | 0.813      | -            | -                | -                | -         |    -4.19 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1334 | 2024-06-08 | FURIA           | W   | 0.807      | 0.715        | 0.284 (0.164)    | 0.468 (0.270)    | 1 (0.807) |    12.58 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1388 | 2024-06-07 | fnatic          | W   | 0.800      | 0.715        | 0.371 (0.212)    | 0.680 (0.389)    | 1 (0.800) |     8.49 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1445 | 2024-06-06 | Sashi           | W   | 0.794      | 0.715        | 0.184 (0.104)    | 0.958 (0.544)    | 1 (0.794) |     2.63 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1471 | 2024-06-06 | The MongolZ     | L   | 0.793      | -            | -                | -                | -         |    -3.59 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1484 | 2024-06-06 | Astralis        | W   | 0.791      | 0.715        | 0.389 (0.220)    | 0.403 (0.228)    | 1 (0.791) |    17.02 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1521 | 2024-06-05 | HEROIC          | W   | 0.787      | 0.715        | 0.224 (0.126)    | -                | 1 (0.787) |    12.26 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1532 | 2024-06-05 | ENCE            | W   | 0.785      | 0.715        | 0.173 (0.097)    | 0.422 (0.237)    | 1 (0.785) |     6.05 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1984 | 2024-05-19 | Sangal          | L   | 0.674      | -            | -                | -                | -         |   -19.55 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     2011 | 2024-05-18 | Metizport       | L   | 0.667      | -            | -                | -                | -         |   -20.34 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     2081 | 2024-05-16 | Sangal          | W   | 0.654      | 0.500        | -                | 0.858 (0.281)    | -         |     1.28 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2404 | 2024-05-05 | FlyQuest        | L   | 0.579      | -            | -                | -                | -         |   -16.68 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2412 | 2024-05-04 | HEROIC          | W   | 0.573      | 0.889        | 0.224 (0.114)    | -                | -         |     7.73 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2426 | 2024-05-03 | BOSS            | W   | 0.567      | -            | -                | -                | -         |     0.22 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2456 | 2024-05-02 | PERA            | L   | 0.559      | -            | -                | -                | -         |   -17.28 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2501 | 2024-04-30 | HEROIC          | L   | 0.546      | -            | -                | -                | -         |   -10.01 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2809 | 2024-04-18 | brazylijski luz | L   | 0.467      | -            | -                | -                | -         |   -14.56 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2955 | 2024-04-12 | OG              | L   | 0.426      | -            | -                | -                | -         |   -13.05 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2980 | 2024-04-11 | BetBoom         | L   | 0.420      | -            | -                | -                | -         |   -10.73 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     3076 | 2024-04-09 | Gods Reign      | W   | 0.407      | -            | -                | -                | -         |     0.09 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3208 | 2024-04-04 | Aurora          | L   | 0.374      | -            | -                | -                | -         |    -5.88 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3217 | 2024-04-04 | Metizport       | W   | 0.372      | -            | -                | -                | -         |     0.19 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3248 | 2024-04-03 | Aurora          | L   | 0.367      | -            | -                | -                | -         |    -5.96 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3268 | 2024-04-03 | Sampi           | L   | 0.365      | -            | -                | -                | -         |   -11.35 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3285 | 2024-04-02 | FAVBET          | W   | 0.360      | -            | -                | -                | -         |     0.07 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3293 | 2024-04-02 | Monte           | W   | 0.359      | -            | -                | -                | -         |     0.21 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3378 | 2024-03-27 | 500             | W   | 0.321      | -            | -                | -                | -         |     0.05 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3386 | 2024-03-27 | Verdant         | W   | 0.320      | -            | -                | -                | -         |     0.15 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($81,107.69)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-06-16 |      0.862 | $7,000.00      | $6,033.94       |
| 2024-06-09 |      0.813 | $56,000.00     | $45,523.33      |
| 2024-05-12 |      0.626 | $12,000.00     | $7,515.00       |
| 2024-04-14 |      0.439 | $26,250.00     | $11,535.42      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
