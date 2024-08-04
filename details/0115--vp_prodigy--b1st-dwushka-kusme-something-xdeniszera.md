### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: b1st, dwushka, KusMe, Something, xdENiSZERA<br />
Global Rank: [115](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [83]( ../standings_europe.md)<br />
<br />
Final Rank Value:  833.9<br />
<br />
Final Rank Value (833.9) = Starting Rank Value (869.7) + Head To Head Adjustments (-35.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.386[<sup>1</sup>](#table2)
- Bounty Collected: 0.378[<sup>2</sup>](#table1)
- Opponent Network: 0.155[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.230<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 869.7
- 400 + ( ( 0.230 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 869.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |      547 | 2024-07-19 | WOPA              | L   | 1.000      | -            | -                | -                | -         |   -26.59 | b1st, dwushka, KusMe, Something, xdENiSZERA  |
|           33 |      665 | 2024-07-17 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -14.60 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |      752 | 2024-07-15 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -15.21 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |     1018 | 2024-06-15 | ARCRED            | L   | 0.866      | -            | -                | -                | -         |   -12.00 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |     1085 | 2024-06-13 | HOTU              | W   | 0.854      | 0.450        | 0.007 (0.003)    | -                | 0 (0.000) |     5.72 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     1094 | 2024-06-13 | 3DMAX             | L   | 0.853      | -            | -                | -                | -         |    -1.34 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     1231 | 2024-06-09 | Illuminar         | L   | 0.826      | -            | -                | -                | -         |   -13.78 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     1286 | 2024-06-08 | EYEBALLERS        | L   | 0.820      | -            | -                | -                | -         |   -13.07 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     1384 | 2024-06-06 | Space             | L   | 0.808      | -            | -                | -                | -         |   -14.38 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     1506 | 2024-06-04 | SINNERS           | W   | 0.793      | 0.435        | 0.037 (0.013)    | 0.757 (0.261)    | 0 (0.000) |    15.59 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     1553 | 2024-06-02 | GUN5              | L   | 0.779      | -            | -                | -                | -         |   -11.14 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     1574 | 2024-06-01 | 3DMAX             | W   | 0.774      | 0.435        | 0.506 (0.170)    | 1.000 (0.336)    | 0 (0.000) |    23.65 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     1584 | 2024-06-01 | 777               | W   | 0.773      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |     6.62 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     1601 | 2024-05-31 | LEON              | L   | 0.768      | -            | -                | -                | -         |   -18.93 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     1617 | 2024-05-31 | Alliance          | W   | 0.766      | 0.435        | 0.017 (0.006)    | 0.300 (0.100)    | 0 (0.000) |     9.96 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     1628 | 2024-05-30 | Insilio           | L   | 0.762      | -            | -                | -                | -         |   -11.71 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     1674 | 2024-05-28 | CYBERSHOKE        | W   | 0.749      | 0.372        | 0.039 (0.011)    | 0.351 (0.098)    | 0 (0.000) |    10.59 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     1704 | 2024-05-27 | Permitta          | W   | 0.741      | 0.435        | 0.024 (0.008)    | 0.876 (0.282)    | 0 (0.000) |    11.93 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     1755 | 2024-05-24 | DMS               | W   | 0.721      | 0.435        | -                | 0.446 (0.140)    | 0 (0.000) |    12.18 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     1806 | 2024-05-22 | ALTERNATE aTTaX   | W   | 0.708      | 0.435        | 0.031 (0.010)    | 0.560 (0.172)    | 0 (0.000) |    11.90 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     1895 | 2024-05-20 | SINNERS           | L   | 0.693      | -            | -                | -                | -         |    -6.45 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     1952 | 2024-05-18 | CPH Wolves        | W   | 0.680      | 0.143        | -                | 0.364 (0.035)    | 0 (0.000) |     8.10 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     2117 | 2024-05-14 | LEON              | W   | 0.655      | -            | -                | -                | -         |     5.48 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     2148 | 2024-05-13 | WOPA              | W   | 0.648      | -            | -                | -                | -         |     4.06 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     2317 | 2024-05-05 | Nemiga            | L   | 0.594      | -            | -                | -                | -         |    -2.96 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     2449 | 2024-04-29 | Nexus             | W   | 0.553      | 0.396        | 0.014 (0.003)    | 0.465 (0.102)    | -         |     8.16 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     2467 | 2024-04-28 | brazylijski luz   | L   | 0.547      | -            | -                | -                | -         |    -9.36 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     2470 | 2024-04-28 | LEON              | W   | 0.547      | 0.396        | 0.007 (0.001)    | 0.130 (0.028)    | -         |     4.76 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     3363 | 2024-03-23 | FORZE             | L   | 0.307      | -            | -                | -                | -         |    -4.28 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     3382 | 2024-03-22 | ex-Guild Eagles   | W   | 0.300      | -            | -                | -                | -         |     4.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     3427 | 2024-03-20 | TSM               | W   | 0.286      | -            | -                | -                | -         |     2.33 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     3654 | 2024-03-10 | 1WIN              | L   | 0.221      | -            | -                | -                | -         |    -3.05 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     3722 | 2024-03-07 | Permitta          | L   | 0.202      | -            | -                | -                | -         |    -2.43 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     3792 | 2024-03-05 | FORZE YNG         | W   | 0.188      | -            | -                | -                | -         |     0.40 | dwushka, KusMe, shady, Something, xdENiSZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,269.21)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.873 | $5,000.00      | $4,365.86       |
| 2024-06-02 |      0.781 | $5,000.00      | $3,903.36       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
