### Roster Details<br />
Team Name: TSM Shimmer<br />
Roster: empathy, Juli, Lx, madss, phoebe<br />
Global Rank: [160](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [43]( ../standings_americas.md)<br />
<br />
Final Rank Value:  671.8<br />
<br />
Final Rank Value (671.8) = Starting Rank Value (683.6) + Head To Head Adjustments (-11.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.363[<sup>1</sup>](#table2)
- Bounty Collected: 0.219[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 683.6
- 400 + ( ( 0.146 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 683.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |      108 | 2024-09-04 | FlyQuest RED     | L   | 1.000      | -            | -                | -                | -         |   -13.54 | empathy, Juli, Lx, madss, phoebe   |
|           22 |      252 | 2024-08-29 | Lotus fe         | W   | 1.000      | 0.333        | 0.001 (0.000)    | -                | 0 (0.000) |     8.47 | empathy, Juli, Lx, madss, phoebe   |
|           21 |      737 | 2024-08-18 | Nouns fe         | W   | 1.000      | 0.250        | 0.003 (0.001)    | 0.046 (0.011)    | 0 (0.000) |    11.96 | empathy, Juli, Lx, madss, phoebe   |
|           20 |     1424 | 2024-07-28 | Nouns fe         | W   | 0.923      | 0.250        | 0.003 (0.001)    | 0.046 (0.011)    | 0 (0.000) |    12.01 | empathy, Juli, Lx, madss, phoebe   |
|           19 |     2155 | 2024-06-16 | Lotus fe         | W   | 0.643      | 0.250        | 0.001 (0.000)    | -                | 0 (0.000) |     6.41 | abby, empathy, Juli, Lx, madss     |
|           18 |     2380 | 2024-06-09 | Perseverance     | L   | 0.595      | -            | -                | -                | -         |   -12.91 | abby, empathy, Florence, Lx, madss |
|           17 |     2482 | 2024-06-07 | Zomblers         | L   | 0.584      | -            | -                | -                | -         |   -13.17 | abby, empathy, Florence, Lx, madss |
|           16 |     2630 | 2024-06-05 | Asian Kings      | W   | 0.568      | -            | -                | -                | 0 (0.000) |     3.15 | abby, empathy, Florence, Lx, madss |
|           15 |     2673 | 2024-06-04 | Nouns            | L   | 0.562      | -            | -                | -                | -         |    -3.53 | abby, empathy, Florence, Lx, madss |
|           14 |     2675 | 2024-06-04 | Homyno           | L   | 0.562      | -            | -                | -                | -         |    -9.32 | abby, empathy, Florence, Lx, madss |
|           13 |     2782 | 2024-05-31 | NAVI Javelins    | L   | 0.537      | -            | -                | -                | -         |    -6.35 | abby, empathy, Lx, madss, phoebe   |
|           12 |     2788 | 2024-05-31 | Fluxo Demons     | L   | 0.535      | -            | -                | -                | -         |    -6.42 | abby, empathy, Lx, madss, phoebe   |
|           11 |     2902 | 2024-05-26 | FlyQuest RED     | L   | 0.502      | -            | -                | -                | -         |    -7.52 | abby, empathy, Lx, madss, phoebe   |
|           10 |     2903 | 2024-05-26 | Blue Otter Karma | W   | 0.502      | 0.303        | 0.002 (0.000)    | 0.064 (0.010)    | 0 (0.000) |     6.46 | abby, empathy, Lx, madss, phoebe   |
|            9 |     3501 | 2024-05-05 | Lotus fe         | W   | 0.363      | 0.250        | 0.003 (0.000)    | 0.028 (0.003)    | 0 (0.000) |     4.72 | abby, empathy, Lx, madss, phoebe   |
|            8 |     3857 | 2024-04-19 | Limitless Angels | W   | 0.256      | 0.322        | 0.001 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     3.18 | abby, empathy, Lx, madss, phoebe   |
|            7 |     4035 | 2024-04-14 | FlyQuest RED     | L   | 0.223      | -            | -                | -                | -         |    -3.38 | abby, empathy, Lx, madss, phoebe   |
|            6 |     4082 | 2024-04-11 | COVEN            | W   | 0.203      | 0.322        | 0.001 (0.000)    | -                | 0 (0.000) |     1.75 | abby, empathy, Lx, madss, phoebe   |
|            5 |     4249 | 2024-04-07 | Limitless Angels | W   | 0.176      | 0.250        | 0.001 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     2.18 | abby, empathy, Lx, madss, phoebe   |
|            4 |     4347 | 2024-04-03 | WG Bandits       | W   | 0.150      | 0.322        | -                | 0.010 (0.000)    | -         |     1.78 | abby, empathy, Lx, madss, phoebe   |
|            3 |     4480 | 2024-03-27 | cleanup crew fe  | W   | 0.103      | 0.322        | -                | 0.003 (0.000)    | -         |     1.23 | abby, empathy, Lx, madss, phoebe   |
|            2 |     4575 | 2024-03-21 | Blue Otter Karma | W   | 0.063      | 0.322        | 0.002 (0.000)    | 0.064 (0.001)    | -         |     0.83 | abby, empathy, Lx, madss, phoebe   |
|            1 |     4719 | 2024-03-14 | Nouns fe         | W   | 0.017      | 0.322        | -                | 0.046 (0.000)    | -         |     0.21 | abby, empathy, Lx, madss, phoebe   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,332.43)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-18 |      1.000 | $750.00        | $750.00         |
| 2024-07-28 |      0.923 | $750.00        | $692.08         |
| 2024-06-16 |      0.643 | $750.00        | $482.12         |
| 2024-06-02 |      0.549 | $4,000.00      | $2,195.56       |
| 2024-05-26 |      0.502 | $1,500.00      | $752.85         |
| 2024-05-05 |      0.363 | $750.00        | $272.12         |
| 2024-04-14 |      0.223 | $250.00        | $55.63          |
| 2024-04-07 |      0.176 | $750.00        | $132.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
