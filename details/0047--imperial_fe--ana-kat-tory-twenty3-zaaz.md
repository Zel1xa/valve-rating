### Roster Details<br />
Team Name: Imperial fe<br />
Roster: ANa, Kat, tory, twenty3, zAAz<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1068.3<br />
<br />
Final Rank Value (1068.3) = Starting Rank Value (1043.8) + Head To Head Adjustments (24.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.531[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.038[<sup>2</sup>](#table1)
- LAN Wins: 0.366[<sup>2</sup>](#table1)

The average of these factors is 0.313<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1043.8
- 400 + ( ( 0.313 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1043.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |     1462 | 2024-06-02 | Let Her Cook  | W   | 0.801      | 0.524        | 0.061 (0.026)    | 0.146 (0.061)    | 1 (0.801) |     8.17 | ANa, Kat, tory, twenty3, zAAz |
|           24 |     1473 | 2024-06-02 | panelinha     | W   | 0.799      | 0.524        | 0.033 (0.014)    | 0.158 (0.066)    | 1 (0.799) |     6.76 | ANa, Kat, tory, twenty3, zAAz |
|           23 |     1525 | 2024-05-31 | BIG EQUIPA    | W   | 0.788      | 0.524        | 0.018 (0.007)    | 0.155 (0.064)    | 1 (0.788) |     4.76 | ANa, Kat, tory, twenty3, zAAz |
|           22 |     1540 | 2024-05-31 | HSG fe        | W   | 0.786      | 0.524        | 0.032 (0.013)    | 0.070 (0.029)    | 1 (0.786) |     5.94 | ANa, Kat, tory, twenty3, zAAz |
|           21 |     1873 | 2024-05-19 | NAVI Javelins | L   | 0.706      | -            | -                | -                | -         |   -16.18 | ANa, Kat, tory, twenty3, zAAz |
|           20 |     1881 | 2024-05-19 | NIP Impact    | W   | 0.705      | 0.281        | 0.005 (0.001)    | 0.190 (0.038)    | 0 (0.000) |     3.13 | ANa, Kat, tory, twenty3, zAAz |
|           19 |     1899 | 2024-05-18 | Crescent fe   | W   | 0.700      | 0.281        | 0.005 (0.001)    | -                | 0 (0.000) |     1.99 | ANa, Kat, tory, twenty3, zAAz |
|           18 |     2293 | 2024-05-05 | Crescent fe   | W   | 0.613      | -            | -                | -                | 0 (0.000) |     1.78 | ANa, Kat, tory, twenty3, zAAz |
|           17 |     2462 | 2024-04-27 | NIP Impact    | W   | 0.559      | 0.252        | -                | 0.190 (0.027)    | 0 (0.000) |     2.49 | ANa, Kat, tory, twenty3, zAAz |
|           16 |     2467 | 2024-04-27 | Spirit fe     | W   | 0.559      | -            | -                | -                | 0 (0.000) |     1.61 | ANa, Kat, tory, twenty3, zAAz |
|           15 |     2665 | 2024-04-19 | ex-GUILD fe   | W   | 0.507      | -            | -                | -                | 0 (0.000) |     1.74 | ANa, Kat, tory, twenty3, zAAz |
|           14 |     2794 | 2024-04-16 | NAVI Javelins | L   | 0.487      | -            | -                | -                | -         |   -11.71 | ANa, Kat, tory, twenty3, zAAz |
|           13 |     2830 | 2024-04-14 | NIP Impact    | W   | 0.473      | 0.303        | 0.005 (0.001)    | 0.190 (0.027)    | -         |     2.13 | ANa, Kat, tory, twenty3, zAAz |
|           12 |     2848 | 2024-04-13 | NAVI Javelins | W   | 0.466      | 0.303        | 0.027 (0.004)    | 0.210 (0.030)    | -         |     3.37 | ANa, Kat, tory, twenty3, zAAz |
|           11 |     2883 | 2024-04-11 | Astralis W    | W   | 0.453      | -            | -                | -                | -         |     1.15 | ANa, Kat, tory, twenty3, zAAz |
|           10 |     2932 | 2024-04-10 | Astralis W    | W   | 0.447      | -            | -                | -                | -         |     1.15 | ANa, Kat, tory, twenty3, zAAz |
|            9 |     3018 | 2024-04-08 | Crescent fe   | W   | 0.432      | -            | -                | -                | -         |     1.43 | ANa, Kat, tory, twenty3, zAAz |
|            8 |     3049 | 2024-04-07 | NIP Impact    | W   | 0.426      | 0.262        | -                | 0.190 (0.021)    | -         |     1.86 | ANa, Kat, tory, twenty3, zAAz |
|            7 |     3053 | 2024-04-07 | BIG EQUIPA    | W   | 0.425      | 0.262        | 0.018 (0.002)    | 0.155 (0.017)    | -         |     2.46 | ANa, Kat, tory, twenty3, zAAz |
|            6 |     3069 | 2024-04-06 | ENCE Athena   | W   | 0.419      | -            | -                | -                | -         |     1.24 | ANa, Kat, tory, twenty3, zAAz |
|            5 |     3299 | 2024-03-27 | ENCE Athena   | W   | 0.354      | -            | -                | -                | -         |     1.08 | ANa, Kat, tory, twenty3, zAAz |
|            4 |     3542 | 2024-03-14 | BIG EQUIPA    | W   | 0.267      | 0.331        | 0.018 (0.002)    | -                | -         |     1.58 | ANa, Kat, tory, twenty3, zAAz |
|            3 |     3722 | 2024-03-07 | NIP Impact    | W   | 0.220      | -            | -                | -                | -         |     0.91 | ANa, Kat, tory, twenty3, zAAz |
|            2 |     3962 | 2024-02-26 | 500           | L   | 0.152      | -            | -                | -                | -         |    -4.07 | ANa, Kat, tory, twenty3, zAAz |
|            1 |     4401 | 2024-02-05 | Sampi         | L   | 0.013      | -            | -                | -                | -         |    -0.28 | ANa, Kat, tory, twenty3, zAAz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($42,641.41)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.801 | $50,000.00     | $40,055.56      |
| 2024-05-19 |      0.706 | $800.00        | $564.74         |
| 2024-05-05 |      0.613 | $750.00        | $459.38         |
| 2024-04-27 |      0.559 | $535.00        | $299.28         |
| 2024-04-16 |      0.487 | $1,500.00      | $730.00         |
| 2024-04-07 |      0.426 | $1,250.00      | $532.47         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
