### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: BluePho3nix, jocab, MisteM, Silence, xKacpersky<br />
Global Rank: [136](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [92]( ../standings_europe.md)<br />
<br />
Final Rank Value:  758.7<br />
<br />
Final Rank Value (758.7) = Starting Rank Value (748.0) + Head To Head Adjustments (10.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.338[<sup>1</sup>](#table2)
- Bounty Collected: 0.315[<sup>2</sup>](#table1)
- Opponent Network: 0.028[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 748.0
- 400 + ( ( 0.170 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 748.0


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
|           18 |      702 | 2024-07-16 | Johnny Speeds   | L   | 1.000      | -            | -                | -                | -         |    -2.15 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           17 |     2601 | 2024-04-21 | Nexus           | L   | 0.505      | -            | -                | -                | -         |    -6.05 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           16 |     2624 | 2024-04-20 | Passion UA      | L   | 0.499      | -            | -                | -                | -         |    -2.97 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           15 |     2711 | 2024-04-18 | Nexus           | W   | 0.485      | 0.500        | 0.014 (0.003)    | 0.465 (0.113)    | 0 (0.000) |     9.52 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           14 |     3055 | 2024-04-07 | 3DMAX           | L   | 0.411      | -            | -                | -                | -         |    -0.09 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           13 |     3538 | 2024-03-14 | ex-sYnck        | L   | 0.250      | -            | -                | -                | -         |    -6.44 | BluePho3nix, dex, maxster, MisteM, Silence      |
|           12 |     3641 | 2024-03-10 | 500             | W   | 0.224      | 0.358        | 0.001 (0.000)    | 0.099 (0.008)    | 0 (0.000) |     3.08 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           11 |     3670 | 2024-03-09 | AURA            | W   | 0.217      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     1.26 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           10 |     3739 | 2024-03-06 | HEROIC          | L   | 0.198      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            9 |     3785 | 2024-03-05 | fnatic          | L   | 0.191      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            8 |     3787 | 2024-03-05 | Permitta        | L   | 0.191      | -            | -                | -                | -         |    -1.60 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            7 |     3798 | 2024-03-04 | Aurora          | W   | 0.185      | 0.500        | 0.424 (0.039)    | 0.794 (0.073)    | 0 (0.000) |     5.78 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            6 |     3813 | 2024-03-03 | BIG             | W   | 0.179      | 0.500        | 0.155 (0.014)    | 0.305 (0.027)    | 0 (0.000) |     5.40 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            5 |     3869 | 2024-03-01 | BLEED           | L   | 0.165      | -            | -                | -                | -         |    -1.24 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            4 |     3882 | 2024-02-29 | Zero Tenacity   | L   | 0.157      | -            | -                | -                | -         |    -0.63 | BluePho3nix, jocab, MisteM, REZ, Silence        |
|            3 |     3891 | 2024-02-28 | AMKAL           | W   | 0.151      | 0.500        | 0.130 (0.010)    | 0.477 (0.036)    | 0 (0.000) |     4.30 | BluePho3nix, maxster, MisteM, REZ, Silence      |
|            2 |     4117 | 2024-02-18 | ALTERNATE aTTaX | W   | 0.085      | 0.358        | 0.032 (0.001)    | 0.561 (0.017)    | 0 (0.000) |     2.13 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            1 |     4292 | 2024-02-11 | Portugal        | W   | 0.038      | 0.358        | 0.003 (0.000)    | 0.121 (0.002)    | 0 (0.000) |     0.49 | BluePho3nix, jocab, maxster, MisteM, Silence    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,603.82)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-10 |      0.226 | $5,000.00      | $1,128.13       |
| 2024-03-06 |      0.198 | $12,500.00     | $2,475.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
