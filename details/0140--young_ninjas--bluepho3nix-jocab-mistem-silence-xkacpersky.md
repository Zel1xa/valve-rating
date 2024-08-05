### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: BluePho3nix, jocab, MisteM, Silence, xKacpersky<br />
Global Rank: [140](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [94]( ../standings_europe.md)<br />
<br />
Final Rank Value:  750.0<br />
<br />
Final Rank Value (750.0) = Starting Rank Value (746.2) + Head To Head Adjustments (3.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.337[<sup>1</sup>](#table2)
- Bounty Collected: 0.313[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.169<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 746.2
- 400 + ( ( 0.169 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 746.2


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
|           19 |       20 | 2024-08-04 | 1WIN            | L   | 1.000      | -            | -                | -                | -         |    -6.53 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           18 |      741 | 2024-07-16 | Johnny Speeds   | L   | 1.000      | -            | -                | -                | -         |    -2.06 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           17 |     2642 | 2024-04-21 | Nexus           | L   | 0.498      | -            | -                | -                | -         |    -5.92 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           16 |     2665 | 2024-04-20 | Passion UA      | L   | 0.491      | -            | -                | -                | -         |    -2.83 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           15 |     2752 | 2024-04-18 | Nexus           | W   | 0.478      | 0.500        | 0.014 (0.003)    | 0.465 (0.111)    | 0 (0.000) |     9.43 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           14 |     3096 | 2024-04-07 | 3DMAX           | L   | 0.403      | -            | -                | -                | -         |    -0.08 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           13 |     3579 | 2024-03-14 | ex-sYnck        | L   | 0.242      | -            | -                | -                | -         |    -6.24 | BluePho3nix, dex, maxster, MisteM, Silence      |
|           12 |     3683 | 2024-03-10 | 500             | W   | 0.217      | 0.358        | 0.001 (0.000)    | 0.097 (0.008)    | 0 (0.000) |     3.00 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           11 |     3712 | 2024-03-09 | AURA            | W   | 0.210      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     1.22 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           10 |     3781 | 2024-03-06 | HEROIC          | L   | 0.191      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            9 |     3827 | 2024-03-05 | fnatic          | L   | 0.184      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            8 |     3829 | 2024-03-05 | Permitta        | L   | 0.183      | -            | -                | -                | -         |    -1.52 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            7 |     3840 | 2024-03-04 | Aurora          | W   | 0.177      | 0.500        | 0.423 (0.038)    | 0.792 (0.070)    | 0 (0.000) |     5.56 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            6 |     3855 | 2024-03-03 | BIG             | W   | 0.172      | 0.500        | 0.155 (0.013)    | 0.303 (0.026)    | 0 (0.000) |     5.18 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            5 |     3911 | 2024-03-01 | BLEED           | L   | 0.158      | -            | -                | -                | -         |    -1.18 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            4 |     3924 | 2024-02-29 | Zero Tenacity   | L   | 0.150      | -            | -                | -                | -         |    -0.59 | BluePho3nix, jocab, MisteM, REZ, Silence        |
|            3 |     3933 | 2024-02-28 | AMKAL           | W   | 0.144      | 0.500        | 0.130 (0.009)    | 0.474 (0.034)    | 0 (0.000) |     4.10 | BluePho3nix, maxster, MisteM, REZ, Silence      |
|            2 |     4159 | 2024-02-18 | ALTERNATE aTTaX | W   | 0.078      | 0.358        | 0.031 (0.001)    | 0.560 (0.016)    | 0 (0.000) |     1.95 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            1 |     4335 | 2024-02-11 | Portugal        | W   | 0.031      | 0.358        | 0.003 (0.000)    | 0.120 (0.001)    | 0 (0.000) |     0.40 | BluePho3nix, jocab, maxster, MisteM, Silence    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,477.43)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-10 |      0.218 | $5,000.00      | $1,092.01       |
| 2024-03-06 |      0.191 | $12,500.00     | $2,385.42       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
