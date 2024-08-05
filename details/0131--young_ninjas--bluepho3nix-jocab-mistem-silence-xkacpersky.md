### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: BluePho3nix, jocab, MisteM, Silence, xKacpersky<br />
Global Rank: [131](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [91]( ../standings_europe.md)<br />
<br />
Final Rank Value:  769.3<br />
<br />
Final Rank Value (769.3) = Starting Rank Value (757.4) + Head To Head Adjustments (11.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.321[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.173<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 757.4
- 400 + ( ( 0.173 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 757.4


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
|           19 |      588 | 2024-07-16 | Johnny Speeds   | L   | 1.000      | -            | -                | -                | -         |    -2.19 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           18 |     2489 | 2024-04-21 | Nexus           | L   | 0.526      | -            | -                | -                | -         |    -6.42 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           17 |     2512 | 2024-04-20 | Passion UA      | L   | 0.519      | -            | -                | -                | -         |    -3.27 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           16 |     2599 | 2024-04-18 | Nexus           | W   | 0.506      | 0.500        | 0.014 (0.003)    | 0.465 (0.118)    | 0 (0.000) |     9.81 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           15 |     2943 | 2024-04-07 | 3DMAX           | L   | 0.431      | -            | -                | -                | -         |    -0.09 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           14 |     3426 | 2024-03-14 | ex-sYnck        | L   | 0.270      | -            | -                | -                | -         |    -7.03 | BluePho3nix, dex, maxster, MisteM, Silence      |
|           13 |     3530 | 2024-03-10 | 500             | W   | 0.245      | 0.358        | 0.001 (0.000)    | 0.106 (0.009)    | 0 (0.000) |     3.33 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           12 |     3559 | 2024-03-09 | AURA            | W   | 0.238      | 0.143        | 0.000 (0.000)    | 0.011 (0.000)    | 0 (0.000) |     1.35 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           11 |     3628 | 2024-03-06 | HEROIC          | L   | 0.219      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           10 |     3674 | 2024-03-05 | fnatic          | L   | 0.212      | -            | -                | -                | -         |    -0.08 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            9 |     3676 | 2024-03-05 | Permitta        | L   | 0.211      | -            | -                | -                | -         |    -1.97 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            8 |     3687 | 2024-03-04 | Aurora          | W   | 0.205      | 0.500        | 0.429 (0.044)    | 0.800 (0.082)    | 0 (0.000) |     6.43 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            7 |     3702 | 2024-03-03 | BIG             | W   | 0.200      | 0.500        | 0.157 (0.016)    | 0.300 (0.030)    | 0 (0.000) |     5.90 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            6 |     3758 | 2024-03-01 | BLEED           | L   | 0.185      | -            | -                | -                | -         |    -1.39 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            5 |     3771 | 2024-02-29 | Zero Tenacity   | L   | 0.178      | -            | -                | -                | -         |    -0.73 | BluePho3nix, jocab, MisteM, REZ, Silence        |
|            4 |     3780 | 2024-02-28 | AMKAL           | W   | 0.172      | 0.500        | 0.131 (0.011)    | 0.484 (0.042)    | 0 (0.000) |     4.89 | BluePho3nix, maxster, MisteM, REZ, Silence      |
|            3 |     4006 | 2024-02-18 | ALTERNATE aTTaX | W   | 0.106      | 0.358        | 0.032 (0.001)    | 0.564 (0.021)    | 0 (0.000) |     2.65 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            2 |     4182 | 2024-02-11 | Portugal        | W   | 0.059      | 0.358        | 0.003 (0.000)    | 0.122 (0.003)    | 0 (0.000) |     0.76 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            1 |     4291 | 2024-02-03 | ex-Anonymo      | W   | 0.006      | 0.358        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.02 | BluePho3nix, jocab, maxster, MisteM, Silence    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,966.54)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-10 |      0.246 | $5,000.00      | $1,231.76       |
| 2024-03-06 |      0.219 | $12,500.00     | $2,734.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
