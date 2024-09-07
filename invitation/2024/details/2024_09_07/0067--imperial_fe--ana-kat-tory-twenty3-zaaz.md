### Roster Details<br />
Team Name: Imperial fe<br />
Roster: ANa, Kat, tory, twenty3, zAAz<br />
Global Rank: [67](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [49]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  958.9<br />
<br />
Final Rank Value (958.9) = Starting Rank Value (913.2) + Head To Head Adjustments (45.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.495[<sup>1</sup>](#table2)
- Bounty Collected: 0.294[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.229[<sup>2</sup>](#table1)

The average of these factors is 0.262<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 913.2
- 400 + ( ( 0.262 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 913.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |       82 | 2024-09-04 | dream catchers fe | W   | 1.000      | 0.328        | 0.016 (0.005)    | 0.180 (0.059)    | 0 (0.000) |     7.58 | ANa, Kat, tory, twenty3, zAAz |
|           24 |     1177 | 2024-08-03 | NIP Impact        | W   | 0.968      | 0.273        | 0.004 (0.001)    | 0.215 (0.057)    | 0 (0.000) |     5.72 | ANa, Kat, tory, twenty3, zAAz |
|           23 |     1198 | 2024-08-02 | Astralis W        | W   | 0.963      | -            | -                | -                | 0 (0.000) |     4.30 | ANa, Kat, tory, twenty3, zAAz |
|           22 |     2691 | 2024-06-02 | Let Her Cook      | W   | 0.557      | 0.524        | 0.045 (0.013)    | 0.084 (0.024)    | 1 (0.557) |     6.79 | ANa, Kat, tory, twenty3, zAAz |
|           21 |     2699 | 2024-06-02 | Fluxo Demons      | W   | 0.555      | 0.524        | 0.027 (0.008)    | 0.178 (0.052)    | 1 (0.555) |     5.48 | ANa, Kat, tory, twenty3, zAAz |
|           20 |     2753 | 2024-05-31 | BIG EQUIPA        | W   | 0.544      | 0.524        | 0.013 (0.004)    | 0.111 (0.032)    | 1 (0.544) |     4.23 | ANa, Kat, tory, twenty3, zAAz |
|           19 |     2768 | 2024-05-31 | HSG fe            | W   | 0.542      | 0.524        | 0.024 (0.007)    | 0.081 (0.023)    | 1 (0.542) |     5.04 | ANa, Kat, tory, twenty3, zAAz |
|           18 |     3074 | 2024-05-19 | NAVI Javelins     | L   | 0.462      | -            | -                | -                | -         |   -10.10 | ANa, Kat, tory, twenty3, zAAz |
|           17 |     3082 | 2024-05-19 | NIP Impact        | W   | 0.461      | 0.281        | 0.004 (0.000)    | 0.215 (0.028)    | 0 (0.000) |     2.97 | ANa, Kat, tory, twenty3, zAAz |
|           16 |     3100 | 2024-05-18 | Crescent fe       | W   | 0.455      | 0.281        | 0.003 (0.000)    | -                | 0 (0.000) |     2.24 | ANa, Kat, tory, twenty3, zAAz |
|           15 |     3482 | 2024-05-05 | Crescent fe       | W   | 0.368      | -            | -                | -                | 0 (0.000) |     1.85 | ANa, Kat, tory, twenty3, zAAz |
|           14 |     3648 | 2024-04-27 | NIP Impact        | W   | 0.315      | 0.252        | -                | 0.215 (0.017)    | -         |     2.06 | ANa, Kat, tory, twenty3, zAAz |
|           13 |     3652 | 2024-04-27 | Spirit fe         | W   | 0.315      | -            | -                | -                | -         |     1.65 | ANa, Kat, tory, twenty3, zAAz |
|           12 |     3844 | 2024-04-19 | Astralis W        | W   | 0.263      | -            | -                | -                | -         |     1.37 | ANa, Kat, tory, twenty3, zAAz |
|           11 |     3971 | 2024-04-16 | NAVI Javelins     | L   | 0.242      | -            | -                | -                | -         |    -5.44 | ANa, Kat, tory, twenty3, zAAz |
|           10 |     4006 | 2024-04-14 | NIP Impact        | W   | 0.229      | 0.303        | -                | 0.215 (0.015)    | -         |     1.52 | ANa, Kat, tory, twenty3, zAAz |
|            9 |     4024 | 2024-04-13 | NAVI Javelins     | W   | 0.222      | 0.303        | 0.018 (0.001)    | -                | -         |     2.00 | ANa, Kat, tory, twenty3, zAAz |
|            8 |     4058 | 2024-04-11 | Astralis W        | W   | 0.209      | -            | -                | -                | -         |     0.63 | ANa, Kat, tory, twenty3, zAAz |
|            7 |     4107 | 2024-04-10 | Astralis W        | W   | 0.202      | -            | -                | -                | -         |     0.61 | ANa, Kat, tory, twenty3, zAAz |
|            6 |     4193 | 2024-04-08 | Crescent fe       | W   | 0.188      | -            | -                | -                | -         |     1.02 | ANa, Kat, tory, twenty3, zAAz |
|            5 |     4224 | 2024-04-07 | NIP Impact        | W   | 0.182      | 0.262        | -                | 0.215 (0.010)    | -         |     1.22 | ANa, Kat, tory, twenty3, zAAz |
|            4 |     4228 | 2024-04-07 | BIG EQUIPA        | W   | 0.181      | 0.262        | 0.013 (0.001)    | -                | -         |     1.42 | ANa, Kat, tory, twenty3, zAAz |
|            3 |     4244 | 2024-04-06 | ENCE Athena       | W   | 0.174      | -            | -                | -                | -         |     0.85 | ANa, Kat, tory, twenty3, zAAz |
|            2 |     4465 | 2024-03-27 | ENCE Athena       | W   | 0.109      | -            | -                | -                | -         |     0.54 | ANa, Kat, tory, twenty3, zAAz |
|            1 |     4702 | 2024-03-14 | BIG EQUIPA        | W   | 0.023      | -            | -                | -                | -         |     0.18 | ANa, Kat, tory, twenty3, zAAz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29,244.92)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.557 | $50,000.00     | $27,840.28      |
| 2024-05-19 |      0.462 | $800.00        | $369.30         |
| 2024-05-05 |      0.368 | $750.00        | $276.15         |
| 2024-04-27 |      0.315 | $535.00        | $168.57         |
| 2024-04-16 |      0.242 | $1,500.00      | $363.54         |
| 2024-04-07 |      0.182 | $1,250.00      | $227.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
