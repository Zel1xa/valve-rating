### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: BluePho3nix, jocab, MisteM, Silence, xKacpersky<br />
Global Rank: [140](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [94]( ../standings_europe.md)<br />
<br />
Final Rank Value:  750.8<br />
<br />
Final Rank Value (750.8) = Starting Rank Value (746.9) + Head To Head Adjustments (3.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.337[<sup>1</sup>](#table2)
- Bounty Collected: 0.314[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 746.9
- 400 + ( ( 0.170 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 746.9


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
|           19 |       15 | 2024-08-04 | 1WIN            | L   | 1.000      | -            | -                | -                | -         |    -6.55 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           18 |      736 | 2024-07-16 | Johnny Speeds   | L   | 1.000      | -            | -                | -                | -         |    -2.07 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           17 |     2637 | 2024-04-21 | Nexus           | L   | 0.501      | -            | -                | -                | -         |    -5.96 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           16 |     2660 | 2024-04-20 | Passion UA      | L   | 0.494      | -            | -                | -                | -         |    -2.87 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           15 |     2747 | 2024-04-18 | Nexus           | W   | 0.481      | 0.500        | 0.014 (0.003)    | 0.465 (0.112)    | 0 (0.000) |     9.46 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           14 |     3091 | 2024-04-07 | 3DMAX           | L   | 0.406      | -            | -                | -                | -         |    -0.08 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           13 |     3574 | 2024-03-14 | ex-sYnck        | L   | 0.245      | -            | -                | -                | -         |    -6.31 | BluePho3nix, dex, maxster, MisteM, Silence      |
|           12 |     3678 | 2024-03-10 | 500             | W   | 0.220      | 0.358        | 0.001 (0.000)    | 0.098 (0.008)    | 0 (0.000) |     3.03 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           11 |     3707 | 2024-03-09 | AURA            | W   | 0.213      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     1.23 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           10 |     3776 | 2024-03-06 | HEROIC          | L   | 0.194      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            9 |     3822 | 2024-03-05 | fnatic          | L   | 0.187      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            8 |     3824 | 2024-03-05 | Permitta        | L   | 0.186      | -            | -                | -                | -         |    -1.55 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            7 |     3835 | 2024-03-04 | Aurora          | W   | 0.180      | 0.500        | 0.423 (0.038)    | 0.793 (0.071)    | 0 (0.000) |     5.64 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            6 |     3850 | 2024-03-03 | BIG             | W   | 0.174      | 0.500        | 0.155 (0.014)    | 0.304 (0.026)    | 0 (0.000) |     5.26 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            5 |     3906 | 2024-03-01 | BLEED           | L   | 0.160      | -            | -                | -                | -         |    -1.20 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            4 |     3919 | 2024-02-29 | Zero Tenacity   | L   | 0.153      | -            | -                | -                | -         |    -0.61 | BluePho3nix, jocab, MisteM, REZ, Silence        |
|            3 |     3928 | 2024-02-28 | AMKAL           | W   | 0.147      | 0.500        | 0.130 (0.010)    | 0.475 (0.035)    | 0 (0.000) |     4.18 | BluePho3nix, maxster, MisteM, REZ, Silence      |
|            2 |     4154 | 2024-02-18 | ALTERNATE aTTaX | W   | 0.081      | 0.358        | 0.031 (0.001)    | 0.560 (0.016)    | 0 (0.000) |     2.02 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            1 |     4330 | 2024-02-11 | Portugal        | W   | 0.033      | 0.358        | 0.003 (0.000)    | 0.120 (0.001)    | 0 (0.000) |     0.44 | BluePho3nix, jocab, maxster, MisteM, Silence    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,524.42)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-10 |      0.221 | $5,000.00      | $1,105.44       |
| 2024-03-06 |      0.194 | $12,500.00     | $2,418.98       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
