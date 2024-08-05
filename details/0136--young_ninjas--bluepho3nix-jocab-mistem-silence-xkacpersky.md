### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: BluePho3nix, jocab, MisteM, Silence, xKacpersky<br />
Global Rank: [136](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [93]( ../standings_europe.md)<br />
<br />
Final Rank Value:  771.0<br />
<br />
Final Rank Value (771.0) = Starting Rank Value (748.4) + Head To Head Adjustments (22.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.336[<sup>1</sup>](#table2)
- Bounty Collected: 0.314[<sup>2</sup>](#table1)
- Opponent Network: 0.030[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 748.4
- 400 + ( ( 0.170 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 748.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |       15 | 2024-08-04 | Alliance        | W   | 1.000      | 0.143        | 0.017 (0.002)    | 0.296 (0.042)    | 0 (0.000) |    19.25 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           19 |       32 | 2024-08-04 | 1WIN            | L   | 1.000      | -            | -                | -                | -         |    -6.48 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           18 |      754 | 2024-07-16 | Johnny Speeds   | L   | 1.000      | -            | -                | -                | -         |    -2.07 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           17 |     2655 | 2024-04-21 | Nexus           | L   | 0.495      | -            | -                | -                | -         |    -5.90 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           16 |     2678 | 2024-04-20 | Passion UA      | L   | 0.488      | -            | -                | -                | -         |    -2.82 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           15 |     2765 | 2024-04-18 | Nexus           | W   | 0.475      | 0.500        | 0.014 (0.003)    | 0.464 (0.110)    | 0 (0.000) |     9.34 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           14 |     3109 | 2024-04-07 | 3DMAX           | L   | 0.400      | -            | -                | -                | -         |    -0.08 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           13 |     3592 | 2024-03-14 | ex-sYnck        | L   | 0.239      | -            | -                | -                | -         |    -6.16 | BluePho3nix, dex, maxster, MisteM, Silence      |
|           12 |     3696 | 2024-03-10 | 500             | W   | 0.214      | 0.358        | 0.001 (0.000)    | 0.096 (0.007)    | 0 (0.000) |     2.93 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           11 |     3725 | 2024-03-09 | AURA            | W   | 0.207      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     1.18 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           10 |     3794 | 2024-03-06 | HEROIC          | L   | 0.188      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            9 |     3840 | 2024-03-05 | fnatic          | L   | 0.181      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            8 |     3842 | 2024-03-05 | Permitta        | L   | 0.180      | -            | -                | -                | -         |    -1.50 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            7 |     3853 | 2024-03-04 | Aurora          | W   | 0.174      | 0.500        | 0.422 (0.037)    | 0.788 (0.069)    | 0 (0.000) |     5.45 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            6 |     3868 | 2024-03-03 | BIG             | W   | 0.168      | 0.500        | 0.155 (0.013)    | 0.302 (0.025)    | 0 (0.000) |     5.08 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            5 |     3924 | 2024-03-01 | BLEED           | L   | 0.154      | -            | -                | -                | -         |    -1.17 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            4 |     3937 | 2024-02-29 | Zero Tenacity   | L   | 0.147      | -            | -                | -                | -         |    -0.58 | BluePho3nix, jocab, MisteM, REZ, Silence        |
|            3 |     3946 | 2024-02-28 | AMKAL           | W   | 0.141      | 0.500        | 0.130 (0.009)    | 0.472 (0.033)    | 0 (0.000) |     4.00 | BluePho3nix, maxster, MisteM, REZ, Silence      |
|            2 |     4172 | 2024-02-18 | ALTERNATE aTTaX | W   | 0.075      | 0.358        | 0.031 (0.001)    | 0.557 (0.015)    | 0 (0.000) |     1.86 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            1 |     4348 | 2024-02-11 | Portugal        | W   | 0.027      | 0.358        | 0.003 (0.000)    | 0.119 (0.001)    | 0 (0.000) |     0.35 | BluePho3nix, jocab, maxster, MisteM, Silence    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,419.10)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-10 |      0.215 | $5,000.00      | $1,075.35       |
| 2024-03-06 |      0.188 | $12,500.00     | $2,343.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
