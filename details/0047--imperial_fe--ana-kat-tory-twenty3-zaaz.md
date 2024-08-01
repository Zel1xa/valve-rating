### Roster Details<br />
Team Name: Imperial fe<br />
Roster: ANa, Kat, tory, twenty3, zAAz<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1069.2<br />
<br />
Final Rank Value (1069.2) = Starting Rank Value (1044.8) + Head To Head Adjustments (24.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.531[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.038[<sup>2</sup>](#table1)
- LAN Wins: 0.367[<sup>2</sup>](#table1)

The average of these factors is 0.313<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1044.8
- 400 + ( ( 0.313 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1044.8


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
|           25 |     1458 | 2024-06-02 | Let Her Cook  | W   | 0.802      | 0.524        | 0.061 (0.026)    | 0.147 (0.062)    | 1 (0.802) |     8.17 | ANa, Kat, tory, twenty3, zAAz |
|           24 |     1469 | 2024-06-02 | panelinha     | W   | 0.801      | 0.524        | 0.033 (0.014)    | 0.158 (0.066)    | 1 (0.801) |     6.77 | ANa, Kat, tory, twenty3, zAAz |
|           23 |     1521 | 2024-05-31 | BIG EQUIPA    | W   | 0.789      | 0.524        | 0.018 (0.007)    | 0.156 (0.064)    | 1 (0.789) |     4.77 | ANa, Kat, tory, twenty3, zAAz |
|           22 |     1536 | 2024-05-31 | HSG fe        | W   | 0.787      | 0.524        | 0.032 (0.013)    | 0.071 (0.029)    | 1 (0.787) |     5.94 | ANa, Kat, tory, twenty3, zAAz |
|           21 |     1869 | 2024-05-19 | NAVI Javelins | L   | 0.707      | -            | -                | -                | -         |   -16.22 | ANa, Kat, tory, twenty3, zAAz |
|           20 |     1877 | 2024-05-19 | NIP Impact    | W   | 0.706      | 0.281        | 0.005 (0.001)    | 0.190 (0.038)    | 0 (0.000) |     3.13 | ANa, Kat, tory, twenty3, zAAz |
|           19 |     1895 | 2024-05-18 | Crescent fe   | W   | 0.701      | 0.281        | 0.005 (0.001)    | -                | 0 (0.000) |     1.99 | ANa, Kat, tory, twenty3, zAAz |
|           18 |     2289 | 2024-05-05 | Crescent fe   | W   | 0.614      | -            | -                | -                | 0 (0.000) |     1.78 | ANa, Kat, tory, twenty3, zAAz |
|           17 |     2458 | 2024-04-27 | NIP Impact    | W   | 0.561      | 0.252        | -                | 0.190 (0.027)    | 0 (0.000) |     2.49 | ANa, Kat, tory, twenty3, zAAz |
|           16 |     2463 | 2024-04-27 | Spirit fe     | W   | 0.560      | -            | -                | -                | 0 (0.000) |     1.61 | ANa, Kat, tory, twenty3, zAAz |
|           15 |     2661 | 2024-04-19 | ex-GUILD fe   | W   | 0.508      | -            | -                | -                | 0 (0.000) |     1.74 | ANa, Kat, tory, twenty3, zAAz |
|           14 |     2790 | 2024-04-16 | NAVI Javelins | L   | 0.488      | -            | -                | -                | -         |   -11.74 | ANa, Kat, tory, twenty3, zAAz |
|           13 |     2826 | 2024-04-14 | NIP Impact    | W   | 0.475      | 0.303        | 0.005 (0.001)    | 0.190 (0.027)    | -         |     2.13 | ANa, Kat, tory, twenty3, zAAz |
|           12 |     2844 | 2024-04-13 | NAVI Javelins | W   | 0.467      | 0.303        | 0.027 (0.004)    | 0.211 (0.030)    | -         |     3.37 | ANa, Kat, tory, twenty3, zAAz |
|           11 |     2879 | 2024-04-11 | Astralis W    | W   | 0.455      | -            | -                | -                | -         |     1.15 | ANa, Kat, tory, twenty3, zAAz |
|           10 |     2928 | 2024-04-10 | Astralis W    | W   | 0.448      | -            | -                | -                | -         |     1.15 | ANa, Kat, tory, twenty3, zAAz |
|            9 |     3014 | 2024-04-08 | Crescent fe   | W   | 0.434      | -            | -                | -                | -         |     1.43 | ANa, Kat, tory, twenty3, zAAz |
|            8 |     3045 | 2024-04-07 | NIP Impact    | W   | 0.427      | 0.262        | -                | 0.190 (0.021)    | -         |     1.86 | ANa, Kat, tory, twenty3, zAAz |
|            7 |     3049 | 2024-04-07 | BIG EQUIPA    | W   | 0.427      | 0.262        | 0.018 (0.002)    | 0.156 (0.017)    | -         |     2.47 | ANa, Kat, tory, twenty3, zAAz |
|            6 |     3065 | 2024-04-06 | ENCE Athena   | W   | 0.420      | -            | -                | -                | -         |     1.24 | ANa, Kat, tory, twenty3, zAAz |
|            5 |     3295 | 2024-03-27 | ENCE Athena   | W   | 0.355      | -            | -                | -                | -         |     1.08 | ANa, Kat, tory, twenty3, zAAz |
|            4 |     3538 | 2024-03-14 | BIG EQUIPA    | W   | 0.268      | 0.331        | 0.018 (0.002)    | -                | -         |     1.59 | ANa, Kat, tory, twenty3, zAAz |
|            3 |     3718 | 2024-03-07 | NIP Impact    | W   | 0.222      | -            | -                | -                | -         |     0.91 | ANa, Kat, tory, twenty3, zAAz |
|            2 |     3958 | 2024-02-26 | 500           | L   | 0.153      | -            | -                | -                | -         |    -4.11 | ANa, Kat, tory, twenty3, zAAz |
|            1 |     4397 | 2024-02-05 | Sampi         | L   | 0.014      | -            | -                | -                | -         |    -0.31 | ANa, Kat, tory, twenty3, zAAz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($42,717.57)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.802 | $50,000.00     | $40,125.00      |
| 2024-05-19 |      0.707 | $800.00        | $565.85         |
| 2024-05-05 |      0.614 | $750.00        | $460.42         |
| 2024-04-27 |      0.561 | $535.00        | $300.02         |
| 2024-04-16 |      0.488 | $1,500.00      | $732.08         |
| 2024-04-07 |      0.427 | $1,250.00      | $534.20         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
