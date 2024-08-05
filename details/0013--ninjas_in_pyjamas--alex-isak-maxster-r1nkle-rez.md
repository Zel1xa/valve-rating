### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1574.2<br />
<br />
Final Rank Value (1574.2) = Starting Rank Value (1690.6) + Head To Head Adjustments (-116.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.627[<sup>1</sup>](#table2)
- Bounty Collected: 0.570[<sup>2</sup>](#table1)
- Opponent Network: 0.342[<sup>2</sup>](#table1)
- LAN Wins: 0.979[<sup>2</sup>](#table1)

The average of these factors is 0.629<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1690.6
- 400 + ( ( 0.629 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1690.6


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
|           39 |       36 | 2024-08-04 | Astralis        | L   | 1.000      | -            | -                | -                | -         |   -10.62 | alex, isak, maxster, r1nkle, REZ               |
|           38 |       60 | 2024-08-03 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.42 | alex, isak, maxster, r1nkle, REZ               |
|           37 |       99 | 2024-08-02 | FaZe            | W   | 1.000      | 0.581        | 0.631 (0.367)    | -                | 1 (1.000) |    20.71 | alex, isak, maxster, r1nkle, REZ               |
|           36 |      143 | 2024-08-01 | Cloud9          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.30 | alex, isak, maxster, r1nkle, REZ               |
|           35 |      195 | 2024-07-31 | G2              | L   | 1.000      | -            | -                | -                | -         |    -3.28 | alex, isak, maxster, r1nkle, REZ               |
|           34 |      548 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -29.71 | alex, isak, maxster, r1nkle, REZ               |
|           33 |      622 | 2024-07-18 | MOUZ NXT        | W   | 1.000      | 0.500        | -                | 0.987 (0.494)    | -         |     1.61 | alex, isak, maxster, r1nkle, REZ               |
|           32 |      749 | 2024-07-16 | Nexus           | W   | 1.000      | 0.500        | -                | 0.458 (0.229)    | -         |     0.28 | alex, isak, maxster, r1nkle, REZ               |
|           31 |     1016 | 2024-06-16 | fnatic          | L   | 0.867      | -            | -                | -                | -         |   -19.05 | alex, isak, maxster, r1nkle, REZ               |
|           30 |     1076 | 2024-06-14 | paiN            | W   | 0.856      | 0.548        | 0.325 (0.152)    | 0.856 (0.402)    | 1 (0.856) |     5.31 | alex, isak, maxster, r1nkle, REZ               |
|           29 |     1082 | 2024-06-14 | 9z              | W   | 0.854      | 0.548        | 0.404 (0.189)    | 0.607 (0.284)    | 1 (0.854) |     7.89 | alex, isak, maxster, r1nkle, REZ               |
|           28 |     1248 | 2024-06-09 | The MongolZ     | L   | 0.819      | -            | -                | -                | -         |    -4.23 | alex, isak, maxster, r1nkle, REZ               |
|           27 |     1308 | 2024-06-08 | FURIA           | W   | 0.813      | 0.715        | 0.284 (0.165)    | 0.481 (0.280)    | 1 (0.813) |    12.66 | alex, isak, maxster, r1nkle, REZ               |
|           26 |     1362 | 2024-06-07 | fnatic          | W   | 0.807      | 0.715        | 0.371 (0.214)    | 0.697 (0.402)    | 1 (0.807) |     8.50 | alex, isak, maxster, r1nkle, REZ               |
|           25 |     1419 | 2024-06-06 | Sashi           | W   | 0.800      | 0.715        | 0.184 (0.105)    | 0.983 (0.563)    | 1 (0.800) |     2.63 | alex, isak, maxster, r1nkle, REZ               |
|           24 |     1445 | 2024-06-06 | The MongolZ     | L   | 0.799      | -            | -                | -                | -         |    -3.63 | alex, isak, maxster, r1nkle, REZ               |
|           23 |     1458 | 2024-06-06 | Astralis        | W   | 0.798      | 0.715        | 0.389 (0.222)    | 0.413 (0.236)    | 1 (0.798) |    17.20 | alex, isak, maxster, r1nkle, REZ               |
|           22 |     1495 | 2024-06-05 | HEROIC          | W   | 0.793      | 0.715        | 0.225 (0.128)    | -                | 1 (0.793) |    12.46 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1506 | 2024-06-05 | ENCE            | W   | 0.792      | 0.715        | 0.174 (0.099)    | 0.432 (0.245)    | 1 (0.792) |     6.02 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1958 | 2024-05-19 | Sangal          | L   | 0.680      | -            | -                | -                | -         |   -19.92 | alex, isak, maxster, r1nkle, REZ               |
|           19 |     1985 | 2024-05-18 | Metizport       | L   | 0.674      | -            | -                | -                | -         |   -20.94 | alex, isak, maxster, r1nkle, REZ               |
|           18 |     2055 | 2024-05-16 | Sangal          | W   | 0.660      | 0.500        | -                | 0.866 (0.286)    | -         |     1.14 | alex, isak, maxster, r1nkle, REZ               |
|           17 |     2378 | 2024-05-05 | FlyQuest        | L   | 0.585      | -            | -                | -                | -         |   -16.85 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2386 | 2024-05-04 | HEROIC          | W   | 0.579      | 0.889        | 0.225 (0.116)    | -                | -         |     7.86 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2400 | 2024-05-03 | BOSS            | W   | 0.573      | -            | -                | -                | -         |     0.22 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |     2430 | 2024-05-02 | PERA            | L   | 0.566      | -            | -                | -                | -         |   -17.48 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           13 |     2475 | 2024-04-30 | HEROIC          | L   | 0.553      | -            | -                | -                | -         |   -10.08 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           12 |     2783 | 2024-04-18 | brazylijski luz | L   | 0.473      | -            | -                | -                | -         |   -14.76 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     2929 | 2024-04-12 | OG              | L   | 0.432      | -            | -                | -                | -         |   -13.24 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     2954 | 2024-04-11 | BetBoom         | L   | 0.426      | -            | -                | -                | -         |   -10.89 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     3050 | 2024-04-09 | Gods Reign      | W   | 0.413      | -            | -                | -                | -         |     0.09 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3182 | 2024-04-04 | Aurora          | L   | 0.380      | -            | -                | -                | -         |    -6.09 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3191 | 2024-04-04 | Metizport       | W   | 0.379      | -            | -                | -                | -         |     0.14 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3222 | 2024-04-03 | Aurora          | L   | 0.373      | -            | -                | -                | -         |    -6.18 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3242 | 2024-04-03 | Sampi           | L   | 0.371      | -            | -                | -                | -         |   -11.55 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3259 | 2024-04-02 | FAVBET          | W   | 0.367      | -            | -                | -                | -         |     0.07 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            3 |     3267 | 2024-04-02 | Monte           | W   | 0.366      | -            | -                | -                | -         |     0.21 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            2 |     3352 | 2024-03-27 | 500             | W   | 0.327      | -            | -                | -                | -         |     0.04 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3360 | 2024-03-27 | Verdant         | W   | 0.327      | -            | -                | -                | -         |     0.15 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($81,768.62)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-06-16 |      0.869 | $7,000.00      | $6,079.63       |
| 2024-06-09 |      0.819 | $56,000.00     | $45,888.89      |
| 2024-05-12 |      0.633 | $12,000.00     | $7,593.33       |
| 2024-04-14 |      0.446 | $26,250.00     | $11,706.77      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
