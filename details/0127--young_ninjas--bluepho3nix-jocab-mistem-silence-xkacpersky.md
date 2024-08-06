### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: BluePho3nix, jocab, MisteM, Silence, xKacpersky<br />
Global Rank: [127](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [87]( ../standings_europe.md)<br />
<br />
Final Rank Value:  790.4<br />
<br />
Final Rank Value (790.4) = Starting Rank Value (753.3) + Head To Head Adjustments (37.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.335[<sup>1</sup>](#table2)
- Bounty Collected: 0.315[<sup>2</sup>](#table1)
- Opponent Network: 0.039[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.172<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 753.3
- 400 + ( ( 0.172 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 753.3


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
|           21 |       11 | 2024-08-05 | Preasy          | W   | 1.000      | 0.435        | 0.008 (0.004)    | 0.221 (0.096)    | 0 (0.000) |    15.49 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           20 |       30 | 2024-08-04 | Alliance        | W   | 1.000      | 0.143        | 0.017 (0.002)    | 0.289 (0.041)    | 0 (0.000) |    19.12 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           19 |       47 | 2024-08-04 | 1WIN            | L   | 1.000      | -            | -                | -                | -         |    -6.50 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           18 |      769 | 2024-07-16 | Johnny Speeds   | L   | 1.000      | -            | -                | -                | -         |    -2.11 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           17 |     2670 | 2024-04-21 | Nexus           | L   | 0.489      | -            | -                | -                | -         |    -5.87 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           16 |     2693 | 2024-04-20 | Passion UA      | L   | 0.482      | -            | -                | -                | -         |    -2.77 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           15 |     2780 | 2024-04-18 | Nexus           | W   | 0.469      | 0.500        | 0.014 (0.003)    | 0.457 (0.107)    | 0 (0.000) |     9.19 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           14 |     3124 | 2024-04-07 | 3DMAX           | L   | 0.394      | -            | -                | -                | -         |    -0.08 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           13 |     3607 | 2024-03-14 | ex-sYnck        | L   | 0.233      | -            | -                | -                | -         |    -6.04 | BluePho3nix, dex, maxster, MisteM, Silence      |
|           12 |     3711 | 2024-03-10 | 500             | W   | 0.208      | 0.358        | 0.001 (0.000)    | 0.093 (0.007)    | 0 (0.000) |     2.81 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           11 |     3740 | 2024-03-09 | AURA            | W   | 0.201      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     1.11 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           10 |     3809 | 2024-03-06 | HEROIC          | L   | 0.182      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            9 |     3855 | 2024-03-05 | fnatic          | L   | 0.175      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            8 |     3857 | 2024-03-05 | Permitta        | L   | 0.174      | -            | -                | -                | -         |    -1.39 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            7 |     3868 | 2024-03-04 | Aurora          | W   | 0.168      | 0.500        | 0.421 (0.035)    | 0.776 (0.065)    | 0 (0.000) |     5.27 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            6 |     3883 | 2024-03-03 | BIG             | W   | 0.163      | 0.500        | 0.154 (0.013)    | 0.297 (0.024)    | 0 (0.000) |     4.89 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            5 |     3939 | 2024-03-01 | BLEED           | L   | 0.148      | -            | -                | -                | -         |    -1.14 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            4 |     3952 | 2024-02-29 | Zero Tenacity   | L   | 0.141      | -            | -                | -                | -         |    -0.56 | BluePho3nix, jocab, MisteM, REZ, Silence        |
|            3 |     3961 | 2024-02-28 | AMKAL           | W   | 0.135      | 0.500        | 0.130 (0.009)    | 0.463 (0.031)    | 0 (0.000) |     3.83 | BluePho3nix, maxster, MisteM, REZ, Silence      |
|            2 |     4187 | 2024-02-18 | ALTERNATE aTTaX | W   | 0.069      | 0.358        | 0.031 (0.001)    | 0.549 (0.014)    | 0 (0.000) |     1.71 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            1 |     4363 | 2024-02-11 | Portugal        | W   | 0.022      | 0.358        | 0.003 (0.000)    | 0.117 (0.001)    | 0 (0.000) |     0.27 | BluePho3nix, jocab, maxster, MisteM, Silence    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,317.01)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-10 |      0.209 | $5,000.00      | $1,046.18       |
| 2024-03-06 |      0.182 | $12,500.00     | $2,270.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
