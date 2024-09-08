### Roster Details<br />
Team Name: Apogee<br />
Roster: POLO, Prism, Qlocuu, swiz, virtuoso<br />
Global Rank: [116](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [83]( ../standings_europe.md)<br />
<br />
Final Rank Value:  785.3<br />
<br />
Final Rank Value (785.3) = Starting Rank Value (742.7) + Head To Head Adjustments (42.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.302[<sup>2</sup>](#table1)
- Opponent Network: 0.097[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.177<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 742.7
- 400 + ( ( 0.177 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 742.7


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
|           26 |       37 | 2024-09-06 | GUN5              | L   | 1.000      | -            | -                | -                | -         |    -6.30 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           25 |       70 | 2024-09-05 | Space             | W   | 1.000      | 0.500        | 0.004 (0.002)    | 0.463 (0.232)    | 0 (0.000) |    14.20 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           24 |     1119 | 2024-08-06 | SINNERS           | L   | 0.981      | -            | -                | -                | -         |    -6.80 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           23 |     1329 | 2024-07-31 | SAW               | L   | 0.941      | -            | -                | -                | -         |    -0.98 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           22 |     1601 | 2024-07-23 | Sangal            | L   | 0.887      | -            | -                | -                | -         |    -1.57 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           21 |     1837 | 2024-07-17 | RUSH B            | W   | 0.848      | 0.500        | 0.026 (0.011)    | 0.304 (0.129)    | 0 (0.000) |    17.50 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           20 |     1951 | 2024-07-15 | Rebels            | W   | 0.834      | 0.500        | 0.028 (0.012)    | 0.656 (0.273)    | 0 (0.000) |    19.34 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           19 |     2685 | 2024-06-04 | The Prodigies     | L   | 0.561      | -            | -                | -                | -         |   -13.81 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           18 |     2717 | 2024-06-03 | Johnny Speeds     | L   | 0.554      | -            | -                | -                | -         |    -2.04 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           17 |     2741 | 2024-06-02 | Partizan          | L   | 0.546      | -            | -                | -                | -         |    -8.62 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           16 |     2832 | 2024-05-30 | Enterprise        | W   | 0.525      | 0.371        | 0.039 (0.008)    | 0.697 (0.136)    | 0 (0.000) |    10.91 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           15 |     2851 | 2024-05-29 | SINNERS           | L   | 0.521      | -            | -                | -                | -         |    -2.24 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           14 |     2900 | 2024-05-27 | Entropiq          | W   | 0.505      | -            | -                | -                | 0 (0.000) |     1.81 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           13 |     2959 | 2024-05-23 | GL Academy        | W   | 0.481      | 0.379        | 0.002 (0.000)    | 0.052 (0.009)    | 0 (0.000) |     6.01 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           12 |     2970 | 2024-05-23 | Zero Tenacity     | L   | 0.479      | -            | -                | -                | -         |    -2.20 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           11 |     3500 | 2024-05-06 | Grannys Knockers  | L   | 0.365      | -            | -                | -                | -         |    -6.57 | POLO, Prism, Qlocuu, swiz, virtuoso |
|           10 |     3658 | 2024-04-28 | VP.Prodigy        | W   | 0.314      | 0.396        | 0.020 (0.002)    | 0.245 (0.030)    | 0 (0.000) |     5.75 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            9 |     3666 | 2024-04-28 | Nexus             | W   | 0.313      | 0.396        | 0.010 (0.001)    | 0.432 (0.054)    | 0 (0.000) |     5.46 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            8 |     3835 | 2024-04-20 | Sangal            | L   | 0.261      | -            | -                | -                | -         |    -0.36 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            7 |     3869 | 2024-04-19 | Rebels            | W   | 0.255      | 0.500        | 0.028 (0.004)    | 0.656 (0.084)    | 0 (0.000) |     5.82 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            6 |     3917 | 2024-04-18 | BetBoom           | L   | 0.248      | -            | -                | -                | -         |    -0.50 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            5 |     3925 | 2024-04-18 | Ninjas in Pyjamas | W   | 0.247      | 0.143        | 0.232 (0.008)    | 0.428 (0.015)    | 0 (0.000) |     7.63 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            4 |     4131 | 2024-04-10 | Betera            | W   | 0.195      | 0.500        | 0.004 (0.000)    | -                | -         |     2.36 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            3 |     4187 | 2024-04-09 | FORZE             | L   | 0.188      | -            | -                | -                | -         |    -2.51 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            2 |     4462 | 2024-03-28 | Aurora            | L   | 0.108      | -            | -                | -                | -         |    -0.08 | POLO, Prism, Qlocuu, swiz, virtuoso |
|            1 |     4733 | 2024-03-14 | Rebels            | W   | 0.015      | 0.500        | -                | 0.656 (0.005)    | -         |     0.34 | POLO, Prism, Qlocuu, swiz, virtuoso |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,782.29)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
