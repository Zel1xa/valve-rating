### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: BluePho3nix, jocab, MisteM, Silence, xKacpersky<br />
Global Rank: [135](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [92]( ../standings_europe.md)<br />
<br />
Final Rank Value:  766.7<br />
<br />
Final Rank Value (766.7) = Starting Rank Value (755.0) + Head To Head Adjustments (11.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.318[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.173<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 755.0
- 400 + ( ( 0.173 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 755.0


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
|           18 |      634 | 2024-07-16 | Johnny Speeds   | L   | 1.000      | -            | -                | -                | -         |    -2.16 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           17 |     2593 | 2024-04-21 | Nexus           | L   | 0.520      | -            | -                | -                | -         |    -6.28 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           16 |     2618 | 2024-04-20 | Passion UA      | L   | 0.513      | -            | -                | -                | -         |    -3.09 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           15 |     2707 | 2024-04-18 | Nexus           | W   | 0.500      | 0.500        | 0.014 (0.003)    | 0.504 (0.126)    | 0 (0.000) |     9.76 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           14 |     3054 | 2024-04-07 | 3DMAX           | L   | 0.425      | -            | -                | -                | -         |    -0.09 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           13 |     3554 | 2024-03-14 | ex-sYnck        | L   | 0.264      | -            | -                | -                | -         |    -6.86 | BluePho3nix, dex, maxster, MisteM, Silence      |
|           12 |     3659 | 2024-03-10 | 500             | W   | 0.239      | 0.358        | 0.001 (0.000)    | 0.126 (0.011)    | 0 (0.000) |     3.49 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           11 |     3689 | 2024-03-09 | AURA            | W   | 0.232      | 0.143        | 0.000 (0.000)    | 0.011 (0.000)    | 0 (0.000) |     1.32 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           10 |     3758 | 2024-03-06 | HEROIC          | L   | 0.213      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            9 |     3809 | 2024-03-05 | fnatic          | L   | 0.206      | -            | -                | -                | -         |    -0.23 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            8 |     3811 | 2024-03-05 | Permitta        | L   | 0.205      | -            | -                | -                | -         |    -1.86 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            7 |     3822 | 2024-03-04 | Aurora          | W   | 0.199      | 0.500        | 0.431 (0.043)    | 0.798 (0.080)    | 0 (0.000) |     6.25 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            6 |     3837 | 2024-03-03 | BIG             | W   | 0.194      | 0.500        | 0.132 (0.013)    | 0.299 (0.029)    | 0 (0.000) |     5.70 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            5 |     3894 | 2024-03-01 | BLEED           | L   | 0.179      | -            | -                | -                | -         |    -1.36 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            4 |     3907 | 2024-02-29 | Zero Tenacity   | L   | 0.172      | -            | -                | -                | -         |    -0.72 | BluePho3nix, jocab, MisteM, REZ, Silence        |
|            3 |     3917 | 2024-02-28 | AMKAL           | W   | 0.166      | 0.500        | 0.132 (0.011)    | 0.482 (0.040)    | 0 (0.000) |     4.71 | BluePho3nix, maxster, MisteM, REZ, Silence      |
|            2 |     4151 | 2024-02-18 | ALTERNATE aTTaX | W   | 0.100      | 0.358        | 0.032 (0.001)    | 0.563 (0.020)    | 0 (0.000) |     2.51 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            1 |     4336 | 2024-02-11 | Portugal        | W   | 0.053      | 0.358        | 0.003 (0.000)    | 0.122 (0.002)    | 0 (0.000) |     0.69 | BluePho3nix, jocab, maxster, MisteM, Silence    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,861.46)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-10 |      0.240 | $5,000.00      | $1,201.74       |
| 2024-03-06 |      0.213 | $12,500.00     | $2,659.72       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
