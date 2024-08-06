### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1574.0<br />
<br />
Final Rank Value (1574.0) = Starting Rank Value (1690.0) + Head To Head Adjustments (-116.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.627[<sup>1</sup>](#table2)
- Bounty Collected: 0.569[<sup>2</sup>](#table1)
- Opponent Network: 0.341[<sup>2</sup>](#table1)
- LAN Wins: 0.979[<sup>2</sup>](#table1)

The average of these factors is 0.629<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1690.0
- 400 + ( ( 0.629 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1690.0


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
|           39 |       39 | 2024-08-04 | Astralis        | L   | 1.000      | -            | -                | -                | -         |   -10.63 | alex, isak, maxster, r1nkle, REZ               |
|           38 |       63 | 2024-08-03 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.42 | alex, isak, maxster, r1nkle, REZ               |
|           37 |      102 | 2024-08-02 | FaZe            | W   | 1.000      | 0.581        | 0.629 (0.365)    | -                | 1 (1.000) |    20.67 | alex, isak, maxster, r1nkle, REZ               |
|           36 |      146 | 2024-08-01 | Cloud9          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.30 | alex, isak, maxster, r1nkle, REZ               |
|           35 |      198 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.28 | alex, isak, maxster, r1nkle, REZ               |
|           34 |      551 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -29.70 | alex, isak, maxster, r1nkle, REZ               |
|           33 |      625 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | -                | 0.986 (0.493)    | -         |     1.61 | alex, isak, maxster, r1nkle, REZ               |
|           32 |      752 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.457 (0.229)    | -         |     0.29 | alex, isak, maxster, r1nkle, REZ               |
|           31 |     1019 | 2024-06-16 | fnatic          | L   | 0.865      | -            | -                | -                | -         |   -19.00 | alex, isak, maxster, r1nkle, REZ               |
|           30 |     1079 | 2024-06-14 | paiN            | W   | 0.853      | 0.548        | 0.325 (0.152)    | 0.857 (0.401)    | 1 (0.853) |     5.29 | alex, isak, maxster, r1nkle, REZ               |
|           29 |     1085 | 2024-06-14 | 9z              | W   | 0.852      | 0.548        | 0.404 (0.189)    | 0.606 (0.283)    | 1 (0.852) |     7.86 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1251 | 2024-06-09 | The MongolZ     | L   | 0.817      | -            | -                | -                | -         |    -4.21 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1311 | 2024-06-08 | FURIA           | W   | 0.811      | 0.715        | 0.284 (0.165)    | 0.480 (0.279)    | 1 (0.811) |    12.64 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1365 | 2024-06-07 | fnatic          | W   | 0.805      | 0.715        | 0.371 (0.213)    | 0.696 (0.401)    | 1 (0.805) |     8.48 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1422 | 2024-06-06 | Sashi           | W   | 0.798      | 0.715        | 0.184 (0.105)    | 0.982 (0.561)    | 1 (0.798) |     2.63 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1448 | 2024-06-06 | The MongolZ     | L   | 0.797      | -            | -                | -                | -         |    -3.61 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1461 | 2024-06-06 | Astralis        | W   | 0.796      | 0.715        | 0.389 (0.222)    | 0.413 (0.235)    | 1 (0.796) |    17.14 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1498 | 2024-06-05 | HEROIC          | W   | 0.791      | 0.715        | 0.225 (0.127)    | -                | 1 (0.791) |    12.39 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1509 | 2024-06-05 | ENCE            | W   | 0.790      | 0.715        | 0.174 (0.098)    | 0.432 (0.244)    | 1 (0.790) |     6.01 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1961 | 2024-05-19 | Sangal          | L   | 0.678      | -            | -                | -                | -         |   -19.85 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     1988 | 2024-05-18 | Metizport       | L   | 0.671      | -            | -                | -                | -         |   -20.87 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     2058 | 2024-05-16 | Sangal          | W   | 0.658      | 0.500        | -                | 0.866 (0.285)    | -         |     1.14 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2381 | 2024-05-05 | FlyQuest        | L   | 0.583      | -            | -                | -                | -         |   -16.80 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2389 | 2024-05-04 | HEROIC          | W   | 0.577      | 0.889        | 0.225 (0.115)    | -                | -         |     7.81 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2403 | 2024-05-03 | BOSS            | W   | 0.571      | -            | -                | -                | -         |     0.22 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2433 | 2024-05-02 | PERA            | L   | 0.564      | -            | -                | -                | -         |   -17.41 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2478 | 2024-04-30 | HEROIC          | L   | 0.550      | -            | -                | -                | -         |   -10.06 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2786 | 2024-04-18 | brazylijski luz | L   | 0.471      | -            | -                | -                | -         |   -14.69 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2932 | 2024-04-12 | OG              | L   | 0.430      | -            | -                | -                | -         |   -13.18 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2957 | 2024-04-11 | BetBoom         | L   | 0.424      | -            | -                | -                | -         |   -10.84 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     3053 | 2024-04-09 | Gods Reign      | W   | 0.411      | -            | -                | -                | -         |     0.09 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3185 | 2024-04-04 | Aurora          | L   | 0.378      | -            | -                | -                | -         |    -6.04 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3194 | 2024-04-04 | Metizport       | W   | 0.377      | -            | -                | -                | -         |     0.13 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3225 | 2024-04-03 | Aurora          | L   | 0.371      | -            | -                | -                | -         |    -6.13 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3245 | 2024-04-03 | Sampi           | L   | 0.369      | -            | -                | -                | -         |   -11.48 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3262 | 2024-04-02 | FAVBET          | W   | 0.365      | -            | -                | -                | -         |     0.07 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3270 | 2024-04-02 | Monte           | W   | 0.363      | -            | -                | -                | -         |     0.21 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3355 | 2024-03-27 | 500             | W   | 0.325      | -            | -                | -                | -         |     0.04 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3363 | 2024-03-27 | Verdant         | W   | 0.325      | -            | -                | -                | -         |     0.15 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($81,543.62)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-06-16 |      0.866 | $7,000.00      | $6,064.07       |
| 2024-06-09 |      0.817 | $56,000.00     | $45,764.44      |
| 2024-05-12 |      0.631 | $12,000.00     | $7,566.67       |
| 2024-04-14 |      0.444 | $26,250.00     | $11,648.44      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
