### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: BluePho3nix, jocab, MisteM, Silence, xKacpersky<br />
Global Rank: [137](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [92]( ../standings_europe.md)<br />
<br />
Final Rank Value:  757.7<br />
<br />
Final Rank Value (757.7) = Starting Rank Value (747.3) + Head To Head Adjustments (10.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.338[<sup>1</sup>](#table2)
- Bounty Collected: 0.314[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 747.3
- 400 + ( ( 0.170 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 747.3


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
|           18 |      705 | 2024-07-16 | Johnny Speeds   | L   | 1.000      | -            | -                | -                | -         |    -2.14 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           17 |     2606 | 2024-04-21 | Nexus           | L   | 0.502      | -            | -                | -                | -         |    -6.00 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           16 |     2629 | 2024-04-20 | Passion UA      | L   | 0.496      | -            | -                | -                | -         |    -2.93 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           15 |     2716 | 2024-04-18 | Nexus           | W   | 0.482      | 0.500        | 0.014 (0.003)    | 0.465 (0.112)    | 0 (0.000) |     9.47 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           14 |     3060 | 2024-04-07 | 3DMAX           | L   | 0.407      | -            | -                | -                | -         |    -0.09 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           13 |     3543 | 2024-03-14 | ex-sYnck        | L   | 0.247      | -            | -                | -                | -         |    -6.35 | BluePho3nix, dex, maxster, MisteM, Silence      |
|           12 |     3647 | 2024-03-10 | 500             | W   | 0.221      | 0.358        | 0.001 (0.000)    | 0.098 (0.008)    | 0 (0.000) |     3.05 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           11 |     3676 | 2024-03-09 | AURA            | W   | 0.214      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     1.24 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           10 |     3745 | 2024-03-06 | HEROIC          | L   | 0.195      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            9 |     3791 | 2024-03-05 | fnatic          | L   | 0.188      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            8 |     3793 | 2024-03-05 | Permitta        | L   | 0.188      | -            | -                | -                | -         |    -1.57 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            7 |     3804 | 2024-03-04 | Aurora          | W   | 0.182      | 0.500        | 0.424 (0.038)    | 0.793 (0.072)    | 0 (0.000) |     5.69 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            6 |     3819 | 2024-03-03 | BIG             | W   | 0.176      | 0.500        | 0.155 (0.014)    | 0.304 (0.027)    | 0 (0.000) |     5.30 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            5 |     3875 | 2024-03-01 | BLEED           | L   | 0.162      | -            | -                | -                | -         |    -1.21 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            4 |     3888 | 2024-02-29 | Zero Tenacity   | L   | 0.154      | -            | -                | -                | -         |    -0.61 | BluePho3nix, jocab, MisteM, REZ, Silence        |
|            3 |     3897 | 2024-02-28 | AMKAL           | W   | 0.148      | 0.500        | 0.130 (0.010)    | 0.476 (0.035)    | 0 (0.000) |     4.22 | BluePho3nix, maxster, MisteM, REZ, Silence      |
|            2 |     4123 | 2024-02-18 | ALTERNATE aTTaX | W   | 0.082      | 0.358        | 0.031 (0.001)    | 0.560 (0.017)    | 0 (0.000) |     2.06 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            1 |     4299 | 2024-02-11 | Portugal        | W   | 0.035      | 0.358        | 0.003 (0.000)    | 0.120 (0.002)    | 0 (0.000) |     0.46 | BluePho3nix, jocab, maxster, MisteM, Silence    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,550.35)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-10 |      0.223 | $5,000.00      | $1,112.85       |
| 2024-03-06 |      0.195 | $12,500.00     | $2,437.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
