### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: BluePho3nix, jocab, MisteM, Silence, xKacpersky<br />
Global Rank: [134](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [92]( ../standings_europe.md)<br />
<br />
Final Rank Value:  759.7<br />
<br />
Final Rank Value (759.7) = Starting Rank Value (748.9) + Head To Head Adjustments (10.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.339[<sup>1</sup>](#table2)
- Bounty Collected: 0.316[<sup>2</sup>](#table1)
- Opponent Network: 0.028[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.171<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 748.9
- 400 + ( ( 0.171 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 748.9


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
|           18 |      675 | 2024-07-16 | Johnny Speeds   | L   | 1.000      | -            | -                | -                | -         |    -2.17 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           17 |     2535 | 2024-04-21 | Nexus           | L   | 0.507      | -            | -                | -                | -         |    -6.03 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           16 |     2558 | 2024-04-20 | Passion UA      | L   | 0.500      | -            | -                | -                | -         |    -2.98 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           15 |     2645 | 2024-04-18 | Nexus           | W   | 0.487      | 0.500        | 0.014 (0.003)    | 0.441 (0.107)    | 0 (0.000) |     9.60 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           14 |     2989 | 2024-04-07 | 3DMAX           | L   | 0.412      | -            | -                | -                | -         |    -0.09 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           13 |     3466 | 2024-03-14 | ex-sYnck        | L   | 0.251      | -            | -                | -                | -         |    -6.49 | BluePho3nix, dex, maxster, MisteM, Silence      |
|           12 |     3568 | 2024-03-10 | 500             | W   | 0.226      | 0.358        | 0.001 (0.000)    | 0.103 (0.008)    | 0 (0.000) |     3.11 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           11 |     3597 | 2024-03-09 | AURA            | W   | 0.219      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     1.27 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           10 |     3666 | 2024-03-06 | HEROIC          | L   | 0.200      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            9 |     3712 | 2024-03-05 | fnatic          | L   | 0.193      | -            | -                | -                | -         |    -0.22 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            8 |     3714 | 2024-03-05 | Permitta        | L   | 0.192      | -            | -                | -                | -         |    -1.62 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            7 |     3725 | 2024-03-04 | Aurora          | W   | 0.186      | 0.500        | 0.425 (0.040)    | 0.809 (0.075)    | 0 (0.000) |     5.84 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            6 |     3740 | 2024-03-03 | BIG             | W   | 0.181      | 0.500        | 0.156 (0.014)    | 0.316 (0.028)    | 0 (0.000) |     5.45 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            5 |     3796 | 2024-03-01 | BLEED           | L   | 0.166      | -            | -                | -                | -         |    -1.24 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            4 |     3809 | 2024-02-29 | Zero Tenacity   | L   | 0.159      | -            | -                | -                | -         |    -0.64 | BluePho3nix, jocab, MisteM, REZ, Silence        |
|            3 |     3818 | 2024-02-28 | AMKAL           | W   | 0.153      | 0.500        | 0.130 (0.010)    | 0.494 (0.038)    | 0 (0.000) |     4.36 | BluePho3nix, maxster, MisteM, REZ, Silence      |
|            2 |     4044 | 2024-02-18 | ALTERNATE aTTaX | W   | 0.087      | 0.358        | 0.032 (0.001)    | 0.580 (0.018)    | 0 (0.000) |     2.18 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            1 |     4219 | 2024-02-11 | Portugal        | W   | 0.040      | 0.358        | 0.003 (0.000)    | 0.125 (0.002)    | 0 (0.000) |     0.52 | BluePho3nix, jocab, maxster, MisteM, Silence    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,633.80)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-10 |      0.227 | $5,000.00      | $1,136.69       |
| 2024-03-06 |      0.200 | $12,500.00     | $2,497.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
