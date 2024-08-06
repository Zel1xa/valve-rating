### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: BluePho3nix, jocab, MisteM, Silence, xKacpersky<br />
Global Rank: [127](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [87]( ../standings_europe.md)<br />
<br />
Final Rank Value:  790.9<br />
<br />
Final Rank Value (790.9) = Starting Rank Value (753.9) + Head To Head Adjustments (37.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.336[<sup>1</sup>](#table2)
- Bounty Collected: 0.316[<sup>2</sup>](#table1)
- Opponent Network: 0.039[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.173<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 753.9
- 400 + ( ( 0.173 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 753.9


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
|           21 |        7 | 2024-08-05 | Preasy          | W   | 1.000      | 0.435        | 0.008 (0.004)    | 0.221 (0.096)    | 0 (0.000) |    15.46 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           20 |       26 | 2024-08-04 | Alliance        | W   | 1.000      | 0.143        | 0.017 (0.002)    | 0.291 (0.042)    | 0 (0.000) |    19.07 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           19 |       43 | 2024-08-04 | 1WIN            | L   | 1.000      | -            | -                | -                | -         |    -6.56 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           18 |      765 | 2024-07-16 | Johnny Speeds   | L   | 1.000      | -            | -                | -                | -         |    -2.12 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           17 |     2666 | 2024-04-21 | Nexus           | L   | 0.491      | -            | -                | -                | -         |    -5.95 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           16 |     2689 | 2024-04-20 | Passion UA      | L   | 0.485      | -            | -                | -                | -         |    -2.81 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           15 |     2776 | 2024-04-18 | Nexus           | W   | 0.471      | 0.500        | 0.014 (0.003)    | 0.457 (0.108)    | 0 (0.000) |     9.18 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           14 |     3120 | 2024-04-07 | 3DMAX           | L   | 0.397      | -            | -                | -                | -         |    -0.08 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           13 |     3603 | 2024-03-14 | ex-sYnck        | L   | 0.236      | -            | -                | -                | -         |    -6.11 | BluePho3nix, dex, maxster, MisteM, Silence      |
|           12 |     3707 | 2024-03-10 | 500             | W   | 0.210      | 0.358        | 0.001 (0.000)    | 0.093 (0.007)    | 0 (0.000) |     2.84 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           11 |     3736 | 2024-03-09 | AURA            | W   | 0.203      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     1.12 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           10 |     3805 | 2024-03-06 | HEROIC          | L   | 0.184      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            9 |     3851 | 2024-03-05 | fnatic          | L   | 0.177      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            8 |     3853 | 2024-03-05 | Permitta        | L   | 0.177      | -            | -                | -                | -         |    -1.41 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            7 |     3864 | 2024-03-04 | Aurora          | W   | 0.171      | 0.500        | 0.421 (0.036)    | 0.777 (0.066)    | 0 (0.000) |     5.35 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            6 |     3879 | 2024-03-03 | BIG             | W   | 0.165      | 0.500        | 0.154 (0.013)    | 0.297 (0.025)    | 0 (0.000) |     4.97 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            5 |     3935 | 2024-03-01 | BLEED           | L   | 0.151      | -            | -                | -                | -         |    -1.17 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            4 |     3948 | 2024-02-29 | Zero Tenacity   | L   | 0.143      | -            | -                | -                | -         |    -0.58 | BluePho3nix, jocab, MisteM, REZ, Silence        |
|            3 |     3957 | 2024-02-28 | AMKAL           | W   | 0.138      | 0.500        | 0.130 (0.009)    | 0.464 (0.032)    | 0 (0.000) |     3.89 | BluePho3nix, maxster, MisteM, REZ, Silence      |
|            2 |     4183 | 2024-02-18 | ALTERNATE aTTaX | W   | 0.072      | 0.358        | 0.031 (0.001)    | 0.550 (0.014)    | 0 (0.000) |     1.77 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            1 |     4359 | 2024-02-11 | Portugal        | W   | 0.024      | 0.358        | 0.003 (0.000)    | 0.118 (0.001)    | 0 (0.000) |     0.30 | BluePho3nix, jocab, maxster, MisteM, Silence    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,360.76)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-10 |      0.212 | $5,000.00      | $1,058.68       |
| 2024-03-06 |      0.184 | $12,500.00     | $2,302.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
