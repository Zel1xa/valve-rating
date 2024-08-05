### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: BluePho3nix, jocab, MisteM, Silence, xKacpersky<br />
Global Rank: [127](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [87]( ../standings_europe.md)<br />
<br />
Final Rank Value:  791.5<br />
<br />
Final Rank Value (791.5) = Starting Rank Value (754.4) + Head To Head Adjustments (37.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.336[<sup>1</sup>](#table2)
- Bounty Collected: 0.316[<sup>2</sup>](#table1)
- Opponent Network: 0.039[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.173<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 754.4
- 400 + ( ( 0.173 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 754.4


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
|           21 |        5 | 2024-08-05 | Preasy          | W   | 1.000      | 0.435        | 0.008 (0.004)    | 0.221 (0.096)    | 0 (0.000) |    15.44 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           20 |       24 | 2024-08-04 | Alliance        | W   | 1.000      | 0.143        | 0.017 (0.002)    | 0.292 (0.042)    | 0 (0.000) |    19.05 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           19 |       41 | 2024-08-04 | 1WIN            | L   | 1.000      | -            | -                | -                | -         |    -6.57 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           18 |      763 | 2024-07-16 | Johnny Speeds   | L   | 1.000      | -            | -                | -                | -         |    -2.13 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           17 |     2664 | 2024-04-21 | Nexus           | L   | 0.493      | -            | -                | -                | -         |    -5.98 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           16 |     2687 | 2024-04-20 | Passion UA      | L   | 0.487      | -            | -                | -                | -         |    -2.83 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           15 |     2774 | 2024-04-18 | Nexus           | W   | 0.473      | 0.500        | 0.014 (0.003)    | 0.458 (0.108)    | 0 (0.000) |     9.20 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           14 |     3118 | 2024-04-07 | 3DMAX           | L   | 0.398      | -            | -                | -                | -         |    -0.08 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           13 |     3601 | 2024-03-14 | ex-sYnck        | L   | 0.238      | -            | -                | -                | -         |    -6.16 | BluePho3nix, dex, maxster, MisteM, Silence      |
|           12 |     3705 | 2024-03-10 | 500             | W   | 0.212      | 0.358        | 0.001 (0.000)    | 0.094 (0.007)    | 0 (0.000) |     2.86 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           11 |     3734 | 2024-03-09 | AURA            | W   | 0.205      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     1.14 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           10 |     3803 | 2024-03-06 | HEROIC          | L   | 0.186      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            9 |     3849 | 2024-03-05 | fnatic          | L   | 0.179      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            8 |     3851 | 2024-03-05 | Permitta        | L   | 0.178      | -            | -                | -                | -         |    -1.43 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            7 |     3862 | 2024-03-04 | Aurora          | W   | 0.173      | 0.500        | 0.422 (0.036)    | 0.778 (0.067)    | 0 (0.000) |     5.41 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            6 |     3877 | 2024-03-03 | BIG             | W   | 0.167      | 0.500        | 0.154 (0.013)    | 0.298 (0.025)    | 0 (0.000) |     5.02 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            5 |     3933 | 2024-03-01 | BLEED           | L   | 0.153      | -            | -                | -                | -         |    -1.18 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            4 |     3946 | 2024-02-29 | Zero Tenacity   | L   | 0.145      | -            | -                | -                | -         |    -0.58 | BluePho3nix, jocab, MisteM, REZ, Silence        |
|            3 |     3955 | 2024-02-28 | AMKAL           | W   | 0.139      | 0.500        | 0.130 (0.009)    | 0.465 (0.032)    | 0 (0.000) |     3.94 | BluePho3nix, maxster, MisteM, REZ, Silence      |
|            2 |     4181 | 2024-02-18 | ALTERNATE aTTaX | W   | 0.073      | 0.358        | 0.031 (0.001)    | 0.550 (0.014)    | 0 (0.000) |     1.81 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            1 |     4357 | 2024-02-11 | Portugal        | W   | 0.026      | 0.358        | 0.003 (0.000)    | 0.118 (0.001)    | 0 (0.000) |     0.33 | BluePho3nix, jocab, maxster, MisteM, Silence    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,392.36)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-10 |      0.214 | $5,000.00      | $1,067.71       |
| 2024-03-06 |      0.186 | $12,500.00     | $2,324.65       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
