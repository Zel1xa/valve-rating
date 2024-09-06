### Roster Details<br />
Team Name: Apogee<br />
Roster: POLO, Prism, Qlocuu, swiz, virtuoso<br />
Global Rank: [114](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [83]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  798.3<br />
<br />
Final Rank Value (798.3) = Starting Rank Value (748.9) + Head To Head Adjustments (49.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.310[<sup>1</sup>](#table2)
- Bounty Collected: 0.302[<sup>2</sup>](#table1)
- Opponent Network: 0.102[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.178<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 748.9
- 400 + ( ( 0.178 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 748.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |       33 | 2024-09-05 | Space             | W   | 1.000      | 0.500        | 0.004 (0.002)    | 0.479 (0.239)    | 0 (0.000) |    14.11 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           25 |     1082 | 2024-08-06 | SINNERS           | L   | 0.992      | -            | -                | -                | -         |    -6.97 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           24 |     1292 | 2024-07-31 | SAW               | L   | 0.952      | -            | -                | -                | -         |    -0.99 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           23 |     1564 | 2024-07-23 | Sangal            | L   | 0.899      | -            | -                | -                | -         |    -1.85 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           22 |     1800 | 2024-07-17 | RUSH B            | W   | 0.860      | 0.500        | 0.025 (0.011)    | 0.316 (0.136)    | 0 (0.000) |    17.77 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           21 |     1914 | 2024-07-15 | Rebels            | W   | 0.846      | 0.500        | 0.028 (0.012)    | 0.677 (0.286)    | 0 (0.000) |    19.67 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           20 |     2648 | 2024-06-04 | The Prodigies     | L   | 0.572      | -            | -                | -                | -         |   -14.18 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           19 |     2680 | 2024-06-03 | Johnny Speeds     | L   | 0.566      | -            | -                | -                | -         |    -2.02 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           18 |     2704 | 2024-06-02 | Partizan          | L   | 0.558      | -            | -                | -                | -         |    -9.04 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           17 |     2795 | 2024-05-30 | Enterprise        | W   | 0.537      | 0.371        | 0.039 (0.008)    | 0.720 (0.143)    | 0 (0.000) |    11.17 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           16 |     2814 | 2024-05-29 | SINNERS           | L   | 0.533      | -            | -                | -                | -         |    -2.32 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           15 |     2863 | 2024-05-27 | Entropiq          | W   | 0.517      | -            | -                | -                | 0 (0.000) |     1.79 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           14 |     2922 | 2024-05-23 | GL Academy        | W   | 0.493      | 0.379        | 0.003 (0.000)    | 0.055 (0.010)    | 0 (0.000) |     6.13 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           13 |     2933 | 2024-05-23 | Zero Tenacity     | L   | 0.491      | -            | -                | -                | -         |    -2.41 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           12 |     3463 | 2024-05-06 | Grannys Knockers  | L   | 0.377      | -            | -                | -                | -         |    -6.83 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           11 |     3621 | 2024-04-28 | VP.Prodigy        | W   | 0.326      | 0.396        | 0.020 (0.003)    | 0.257 (0.033)    | 0 (0.000) |     5.95 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           10 |     3629 | 2024-04-28 | Nexus             | W   | 0.324      | 0.396        | 0.010 (0.001)    | 0.448 (0.058)    | 0 (0.000) |     5.68 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            9 |     3798 | 2024-04-20 | Sangal            | L   | 0.273      | -            | -                | -                | -         |    -0.48 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            8 |     3832 | 2024-04-19 | Rebels            | W   | 0.267      | 0.500        | 0.028 (0.004)    | 0.677 (0.090)    | 0 (0.000) |     6.12 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            7 |     3880 | 2024-04-18 | BetBoom           | L   | 0.260      | -            | -                | -                | -         |    -0.49 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            6 |     3888 | 2024-04-18 | Ninjas in Pyjamas | W   | 0.259      | 0.143        | 0.210 (0.008)    | 0.445 (0.016)    | 0 (0.000) |     8.00 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            5 |     4094 | 2024-04-10 | Betera            | W   | 0.207      | 0.500        | 0.004 (0.000)    | -                | -         |     2.49 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            4 |     4150 | 2024-04-09 | FORZE             | L   | 0.200      | -            | -                | -                | -         |    -2.66 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            3 |     4425 | 2024-03-28 | Aurora            | L   | 0.120      | -            | -                | -                | -         |    -0.08 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            2 |     4696 | 2024-03-14 | Rebels            | W   | 0.027      | 0.500        | -                | 0.677 (0.009)    | -         |     0.62 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            1 |     4784 | 2024-03-11 | SINNERS           | W   | 0.006      | -            | -                | -                | -         |     0.18 | POLO, Prism, Qlocuu, swiz, virtuoso |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,818.06)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
