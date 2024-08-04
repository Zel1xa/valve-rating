### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: BluePho3nix, jocab, MisteM, Silence, xKacpersky<br />
Global Rank: [140](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [94]( ../standings_europe.md)<br />
<br />
Final Rank Value:  750.7<br />
<br />
Final Rank Value (750.7) = Starting Rank Value (746.8) + Head To Head Adjustments (3.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.337[<sup>1</sup>](#table2)
- Bounty Collected: 0.314[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 746.8
- 400 + ( ( 0.170 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 746.8


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
|           19 |       16 | 2024-08-04 | 1WIN            | L   | 1.000      | -            | -                | -                | -         |    -6.55 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           18 |      737 | 2024-07-16 | Johnny Speeds   | L   | 1.000      | -            | -                | -                | -         |    -2.07 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           17 |     2638 | 2024-04-21 | Nexus           | L   | 0.500      | -            | -                | -                | -         |    -5.95 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           16 |     2661 | 2024-04-20 | Passion UA      | L   | 0.494      | -            | -                | -                | -         |    -2.86 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           15 |     2748 | 2024-04-18 | Nexus           | W   | 0.480      | 0.500        | 0.014 (0.003)    | 0.465 (0.112)    | 0 (0.000) |     9.47 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           14 |     3092 | 2024-04-07 | 3DMAX           | L   | 0.406      | -            | -                | -                | -         |    -0.08 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           13 |     3575 | 2024-03-14 | ex-sYnck        | L   | 0.245      | -            | -                | -                | -         |    -6.30 | BluePho3nix, dex, maxster, MisteM, Silence      |
|           12 |     3679 | 2024-03-10 | 500             | W   | 0.219      | 0.358        | 0.001 (0.000)    | 0.097 (0.008)    | 0 (0.000) |     3.03 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           11 |     3708 | 2024-03-09 | AURA            | W   | 0.212      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     1.23 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           10 |     3777 | 2024-03-06 | HEROIC          | L   | 0.193      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            9 |     3823 | 2024-03-05 | fnatic          | L   | 0.187      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            8 |     3825 | 2024-03-05 | Permitta        | L   | 0.186      | -            | -                | -                | -         |    -1.54 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            7 |     3836 | 2024-03-04 | Aurora          | W   | 0.180      | 0.500        | 0.423 (0.038)    | 0.793 (0.071)    | 0 (0.000) |     5.63 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            6 |     3851 | 2024-03-03 | BIG             | W   | 0.174      | 0.500        | 0.155 (0.013)    | 0.304 (0.026)    | 0 (0.000) |     5.25 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            5 |     3907 | 2024-03-01 | BLEED           | L   | 0.160      | -            | -                | -                | -         |    -1.19 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            4 |     3920 | 2024-02-29 | Zero Tenacity   | L   | 0.152      | -            | -                | -                | -         |    -0.60 | BluePho3nix, jocab, MisteM, REZ, Silence        |
|            3 |     3929 | 2024-02-28 | AMKAL           | W   | 0.147      | 0.500        | 0.130 (0.010)    | 0.475 (0.035)    | 0 (0.000) |     4.17 | BluePho3nix, maxster, MisteM, REZ, Silence      |
|            2 |     4155 | 2024-02-18 | ALTERNATE aTTaX | W   | 0.081      | 0.358        | 0.031 (0.001)    | 0.560 (0.016)    | 0 (0.000) |     2.01 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            1 |     4331 | 2024-02-11 | Portugal        | W   | 0.033      | 0.358        | 0.003 (0.000)    | 0.120 (0.001)    | 0 (0.000) |     0.43 | BluePho3nix, jocab, maxster, MisteM, Silence    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,519.16)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-10 |      0.221 | $5,000.00      | $1,103.94       |
| 2024-03-06 |      0.193 | $12,500.00     | $2,415.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
