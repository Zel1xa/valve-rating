### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1692.2<br />
<br />
Final Rank Value (1692.2) = Starting Rank Value (1952.1) + Head To Head Adjustments (-259.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.616[<sup>2</sup>](#table1)
- Opponent Network: 0.419[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.759<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1952.1
- 400 + ( ( 0.759 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1952.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           53 |      213 | 2024-07-28 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -26.71 | 910, bLitz, mzinho, Senzu, Techno |
|           52 |      231 | 2024-07-28 | Eternal Fire      | W   | 1.000      | 0.650        | 0.746 (0.485)    | 0.474 (0.309)    | 1 (1.000) |    11.77 | 910, bLitz, mzinho, Senzu, Techno |
|           51 |      245 | 2024-07-27 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.494 (0.321)    | 1 (1.000) |     1.81 | 910, bLitz, mzinho, Senzu, Techno |
|           50 |      275 | 2024-07-26 | Aurora            | W   | 1.000      | 0.650        | 0.425 (0.276)    | 0.809 (0.526)    | 1 (1.000) |     6.41 | 910, bLitz, mzinho, Senzu, Techno |
|           49 |      313 | 2024-07-25 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -28.50 | 910, bLitz, mzinho, Senzu, Techno |
|           48 |      335 | 2024-07-24 | ENCE              | W   | 1.000      | 0.650        | -                | 0.415 (0.270)    | 1 (1.000) |     3.61 | 910, bLitz, mzinho, Senzu, Techno |
|           47 |      346 | 2024-07-24 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -30.77 | 910, bLitz, mzinho, Senzu, Techno |
|           46 |      393 | 2024-07-23 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           45 |      544 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |   -23.01 | 910, bLitz, mzinho, Senzu, Techno |
|           44 |      548 | 2024-07-18 | M80               | W   | 1.000      | 1.000        | 0.188 (0.188)    | 0.608 (0.608)    | 1 (1.000) |     1.74 | 910, bLitz, mzinho, Senzu, Techno |
|           43 |      560 | 2024-07-18 | MIBR              | W   | 1.000      | 1.000        | 0.210 (0.210)    | 0.682 (0.682)    | 1 (1.000) |     3.12 | 910, bLitz, mzinho, Senzu, Techno |
|           42 |      632 | 2024-07-17 | G2                | L   | 1.000      | -            | -                | -                | -         |    -9.22 | 910, bLitz, mzinho, Senzu, Techno |
|           41 |      781 | 2024-07-11 | CatEvil           | L   | 1.000      | -            | -                | -                | -         |   -31.46 | 910, bLitz, mzinho, Senzu, Techno |
|           40 |      784 | 2024-07-11 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -31.43 | 910, bLitz, mzinho, Senzu, Techno |
|           39 |      787 | 2024-07-11 | Steel Helmet      | W   | 1.000      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           38 |      957 | 2024-06-15 | Falcons           | L   | 0.873      | -            | -                | -                | -         |   -25.29 | 910, bLitz, mzinho, Senzu, Techno |
|           37 |      990 | 2024-06-14 | Aurora            | L   | 0.866      | -            | -                | -                | -         |   -25.39 | 910, bLitz, mzinho, Senzu, Techno |
|           36 |     1003 | 2024-06-14 | Party Astronauts  | W   | 0.864      | -            | -                | -                | 1 (0.864) |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           35 |     1132 | 2024-06-09 | Ninjas in Pyjamas | W   | 0.833      | 0.715        | 0.204 (0.121)    | 0.502 (0.299)    | 1 (0.833) |     3.56 | 910, bLitz, mzinho, Senzu, Techno |
|           34 |     1207 | 2024-06-08 | Astralis          | W   | 0.826      | 0.715        | 0.353 (0.209)    | -                | 1 (0.826) |     6.70 | 910, bLitz, mzinho, Senzu, Techno |
|           33 |     1307 | 2024-06-06 | Astralis          | L   | 0.813      | -            | -                | -                | -         |   -19.62 | 910, bLitz, mzinho, Senzu, Techno |
|           32 |     1324 | 2024-06-06 | Ninjas in Pyjamas | W   | 0.813      | 0.715        | 0.204 (0.118)    | 0.502 (0.292)    | -         |     3.00 | 910, bLitz, mzinho, Senzu, Techno |
|           31 |     1346 | 2024-06-06 | HEROIC            | W   | 0.811      | 0.715        | 0.230 (0.133)    | -                | -         |     3.10 | 910, bLitz, mzinho, Senzu, Techno |
|           30 |     1376 | 2024-06-05 | ENCE              | W   | 0.806      | -            | -                | -                | -         |     0.97 | 910, bLitz, mzinho, Senzu, Techno |
|           29 |     1393 | 2024-06-05 | Sashi             | W   | 0.805      | 0.715        | -                | 0.998 (0.574)    | -         |     0.48 | 910, bLitz, mzinho, Senzu, Techno |
|           28 |     1477 | 2024-06-02 | BLEED             | W   | 0.785      | -            | -                | -                | -         |     1.33 | 910, bLitz, mzinho, Senzu, Techno |
|           27 |     1510 | 2024-06-01 | BLEED             | W   | 0.778      | -            | -                | -                | -         |     1.21 | 910, bLitz, mzinho, Senzu, Techno |
|           26 |     1589 | 2024-05-29 | Aurora            | W   | 0.758      | 0.500        | 0.425 (0.161)    | 0.809 (0.307)    | -         |     2.95 | 910, bLitz, mzinho, Senzu, Techno |
|           25 |     1610 | 2024-05-28 | Gaimin Gladiators | W   | 0.751      | -            | -                | -                | -         |     0.16 | 910, bLitz, mzinho, Senzu, Techno |
|           24 |     1882 | 2024-05-18 | ATOX              | W   | 0.684      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           23 |     1917 | 2024-05-16 | Chinggis Warriors | W   | 0.677      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           22 |     2186 | 2024-05-08 | Virtus.pro        | L   | 0.620      | -            | -                | -                | -         |   -15.19 | 910, bLitz, mzinho, Senzu, Techno |
|           21 |     2395 | 2024-04-28 | Vitality          | L   | 0.552      | -            | -                | -                | -         |   -10.14 | 910, bLitz, mzinho, Senzu, Techno |
|           20 |     2471 | 2024-04-25 | G2                | W   | 0.532      | 0.889        | 1.000 (0.473)    | -                | -         |     9.65 | 910, bLitz, mzinho, Senzu, Techno |
|           19 |     2490 | 2024-04-24 | Falcons           | W   | 0.525      | -            | -                | -                | -         |     1.03 | 910, bLitz, mzinho, Senzu, Techno |
|           18 |     2617 | 2024-04-19 | Rare Atom         | W   | 0.492      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           17 |     2666 | 2024-04-18 | TYLOO             | W   | 0.486      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           16 |     2677 | 2024-04-18 | Rare Atom         | W   | 0.485      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           15 |     3106 | 2024-04-03 | Lynn Vision       | W   | 0.385      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           14 |     3119 | 2024-04-03 | LYG               | W   | 0.384      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           13 |     3145 | 2024-04-02 | ATOX              | W   | 0.379      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           12 |     3149 | 2024-04-02 | LYG               | L   | 0.378      | -            | -                | -                | -         |   -11.88 | 910, bLitz, mzinho, Senzu, Techno |
|           11 |     3291 | 2024-03-22 | paiN              | L   | 0.306      | -            | -                | -                | -         |    -9.23 | 910, bLitz, mzinho, Senzu, Techno |
|           10 |     3313 | 2024-03-21 | Vitality          | L   | 0.300      | -            | -                | -                | -         |    -5.79 | 910, bLitz, mzinho, Senzu, Techno |
|            9 |     3323 | 2024-03-21 | Natus Vincere     | L   | 0.299      | -            | -                | -                | -         |    -4.20 | 910, bLitz, mzinho, Senzu, Techno |
|            8 |     3342 | 2024-03-20 | Legacy            | W   | 0.292      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            7 |     3360 | 2024-03-19 | Lynn Vision       | W   | 0.285      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|            6 |     3366 | 2024-03-18 | AMKAL             | W   | 0.279      | -            | -                | -                | -         |     0.09 | 910, bLitz, mzinho, Senzu, Techno |
|            5 |     3388 | 2024-03-17 | Gaimin Gladiators | L   | 0.274      | -            | -                | -                | -         |    -8.58 | 910, bLitz, mzinho, Senzu, Techno |
|            4 |     3401 | 2024-03-17 | Eternal Fire      | L   | 0.272      | -            | -                | -                | -         |    -6.88 | 910, bLitz, mzinho, Senzu, Techno |
|            3 |     3832 | 2024-02-27 | Lynn Vision       | W   | 0.149      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|            2 |     3868 | 2024-02-25 | FlyQuest          | W   | 0.137      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            1 |     3874 | 2024-02-25 | MAG               | W   | 0.136      | -            | -                | -                | -         |     0.00 | 910, bLitz, mzinho, Senzu, Techno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($325,971.18)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $70,000.00     | $70,000.00      |
| 2024-07-21 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-16 |      0.879 | $3,000.00      | $2,637.64       |
| 2024-06-09 |      0.833 | $200,000.00    | $166,564.81     |
| 2024-06-02 |      0.785 | $50,000.00     | $39,244.21      |
| 2024-05-12 |      0.646 | $23,500.00     | $15,184.70      |
| 2024-03-31 |      0.367 | $20,000.00     | $7,339.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
