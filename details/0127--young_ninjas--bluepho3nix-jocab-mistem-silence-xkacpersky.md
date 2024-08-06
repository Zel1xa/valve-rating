### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: BluePho3nix, jocab, MisteM, Silence, xKacpersky<br />
Global Rank: [127](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [87]( ../standings_europe.md)<br />
<br />
Final Rank Value:  790.6<br />
<br />
Final Rank Value (790.6) = Starting Rank Value (753.5) + Head To Head Adjustments (37.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.335[<sup>1</sup>](#table2)
- Bounty Collected: 0.315[<sup>2</sup>](#table1)
- Opponent Network: 0.038[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.172<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 753.5
- 400 + ( ( 0.172 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 753.5


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
|           21 |       15 | 2024-08-05 | Preasy          | W   | 1.000      | 0.435        | 0.008 (0.004)    | 0.216 (0.094)    | 0 (0.000) |    15.49 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           20 |       34 | 2024-08-04 | Alliance        | W   | 1.000      | 0.143        | 0.017 (0.002)    | 0.283 (0.040)    | 0 (0.000) |    19.13 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           19 |       51 | 2024-08-04 | 1WIN            | L   | 1.000      | -            | -                | -                | -         |    -6.52 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           18 |      773 | 2024-07-16 | Johnny Speeds   | L   | 1.000      | -            | -                | -                | -         |    -2.11 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           17 |     2674 | 2024-04-21 | Nexus           | L   | 0.489      | -            | -                | -                | -         |    -5.87 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           16 |     2697 | 2024-04-20 | Passion UA      | L   | 0.482      | -            | -                | -                | -         |    -2.77 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           15 |     2784 | 2024-04-18 | Nexus           | W   | 0.469      | 0.500        | 0.014 (0.003)    | 0.447 (0.105)    | 0 (0.000) |     9.17 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           14 |     3128 | 2024-04-07 | 3DMAX           | L   | 0.394      | -            | -                | -                | -         |    -0.08 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           13 |     3611 | 2024-03-14 | ex-sYnck        | L   | 0.233      | -            | -                | -                | -         |    -6.03 | BluePho3nix, dex, maxster, MisteM, Silence      |
|           12 |     3715 | 2024-03-10 | 500             | W   | 0.208      | 0.358        | 0.001 (0.000)    | 0.090 (0.007)    | 0 (0.000) |     2.81 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           11 |     3744 | 2024-03-09 | AURA            | W   | 0.201      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     1.10 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           10 |     3813 | 2024-03-06 | HEROIC          | L   | 0.182      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            9 |     3859 | 2024-03-05 | fnatic          | L   | 0.175      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            8 |     3861 | 2024-03-05 | Permitta        | L   | 0.174      | -            | -                | -                | -         |    -1.39 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            7 |     3872 | 2024-03-04 | Aurora          | W   | 0.168      | 0.500        | 0.421 (0.035)    | 0.759 (0.064)    | 0 (0.000) |     5.26 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            6 |     3887 | 2024-03-03 | BIG             | W   | 0.162      | 0.500        | 0.154 (0.012)    | 0.290 (0.024)    | 0 (0.000) |     4.88 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            5 |     3943 | 2024-03-01 | BLEED           | L   | 0.148      | -            | -                | -                | -         |    -1.14 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            4 |     3956 | 2024-02-29 | Zero Tenacity   | L   | 0.141      | -            | -                | -                | -         |    -0.56 | BluePho3nix, jocab, MisteM, REZ, Silence        |
|            3 |     3965 | 2024-02-28 | AMKAL           | W   | 0.135      | 0.500        | 0.130 (0.009)    | 0.453 (0.031)    | 0 (0.000) |     3.82 | BluePho3nix, maxster, MisteM, REZ, Silence      |
|            2 |     4191 | 2024-02-18 | ALTERNATE aTTaX | W   | 0.069      | 0.358        | 0.031 (0.001)    | 0.537 (0.013)    | 0 (0.000) |     1.70 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            1 |     4367 | 2024-02-11 | Portugal        | W   | 0.021      | 0.358        | 0.003 (0.000)    | 0.115 (0.001)    | 0 (0.000) |     0.27 | BluePho3nix, jocab, maxster, MisteM, Silence    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,312.15)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-10 |      0.209 | $5,000.00      | $1,044.79       |
| 2024-03-06 |      0.181 | $12,500.00     | $2,267.36       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
