### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: BluePho3nix, jocab, MisteM, Silence, xKacpersky<br />
Global Rank: [127](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [87]( ../standings_europe.md)<br />
<br />
Final Rank Value:  790.5<br />
<br />
Final Rank Value (790.5) = Starting Rank Value (753.3) + Head To Head Adjustments (37.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.335[<sup>1</sup>](#table2)
- Bounty Collected: 0.315[<sup>2</sup>](#table1)
- Opponent Network: 0.038[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.172<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 753.3
- 400 + ( ( 0.172 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 753.3


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
|           21 |       24 | 2024-08-05 | Preasy          | W   | 1.000      | 0.435        | 0.008 (0.004)    | 0.216 (0.094)    | 0 (0.000) |    15.55 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           20 |       43 | 2024-08-04 | Alliance        | W   | 1.000      | 0.143        | 0.017 (0.002)    | 0.283 (0.040)    | 0 (0.000) |    19.15 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           19 |       60 | 2024-08-04 | 1WIN            | L   | 1.000      | -            | -                | -                | -         |    -6.48 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           18 |      782 | 2024-07-16 | Johnny Speeds   | L   | 1.000      | -            | -                | -                | -         |    -2.08 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           17 |     2683 | 2024-04-21 | Nexus           | L   | 0.487      | -            | -                | -                | -         |    -5.82 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           16 |     2706 | 2024-04-20 | Passion UA      | L   | 0.481      | -            | -                | -                | -         |    -2.75 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           15 |     2793 | 2024-04-18 | Nexus           | W   | 0.468      | 0.500        | 0.014 (0.003)    | 0.447 (0.104)    | 0 (0.000) |     9.18 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           14 |     3137 | 2024-04-07 | 3DMAX           | L   | 0.393      | -            | -                | -                | -         |    -0.08 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           13 |     3620 | 2024-03-14 | ex-sYnck        | L   | 0.232      | -            | -                | -                | -         |    -6.00 | BluePho3nix, dex, maxster, MisteM, Silence      |
|           12 |     3724 | 2024-03-10 | 500             | W   | 0.207      | 0.358        | 0.001 (0.000)    | 0.090 (0.007)    | 0 (0.000) |     2.79 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           11 |     3753 | 2024-03-09 | AURA            | W   | 0.199      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     1.09 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           10 |     3822 | 2024-03-06 | HEROIC          | L   | 0.181      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            9 |     3868 | 2024-03-05 | fnatic          | L   | 0.174      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            8 |     3870 | 2024-03-05 | Permitta        | L   | 0.173      | -            | -                | -                | -         |    -1.26 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            7 |     3881 | 2024-03-04 | Aurora          | W   | 0.167      | 0.500        | 0.420 (0.035)    | 0.758 (0.063)    | 0 (0.000) |     5.23 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            6 |     3896 | 2024-03-03 | BIG             | W   | 0.161      | 0.500        | 0.154 (0.012)    | 0.290 (0.023)    | 0 (0.000) |     4.85 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            5 |     3952 | 2024-03-01 | BLEED           | L   | 0.147      | -            | -                | -                | -         |    -1.13 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            4 |     3965 | 2024-02-29 | Zero Tenacity   | L   | 0.139      | -            | -                | -                | -         |    -0.56 | BluePho3nix, jocab, MisteM, REZ, Silence        |
|            3 |     3974 | 2024-02-28 | AMKAL           | W   | 0.134      | 0.500        | 0.130 (0.009)    | 0.452 (0.030)    | 0 (0.000) |     3.79 | BluePho3nix, maxster, MisteM, REZ, Silence      |
|            2 |     4200 | 2024-02-18 | ALTERNATE aTTaX | W   | 0.068      | 0.358        | 0.031 (0.001)    | 0.537 (0.013)    | 0 (0.000) |     1.68 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            1 |     4376 | 2024-02-11 | Portugal        | W   | 0.020      | 0.358        | 0.003 (0.000)    | 0.115 (0.001)    | 0 (0.000) |     0.26 | BluePho3nix, jocab, maxster, MisteM, Silence    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,292.71)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-10 |      0.208 | $5,000.00      | $1,039.24       |
| 2024-03-06 |      0.180 | $12,500.00     | $2,253.47       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
