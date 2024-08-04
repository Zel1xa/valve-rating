### Roster Details<br />
Team Name: Imperial fe<br />
Roster: ANa, Kat, tory, twenty3, zAAz<br />
Global Rank: [50](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1066.9<br />
<br />
Final Rank Value (1066.9) = Starting Rank Value (1034.7) + Head To Head Adjustments (32.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.529[<sup>1</sup>](#table2)
- Bounty Collected: 0.316[<sup>2</sup>](#table1)
- Opponent Network: 0.043[<sup>2</sup>](#table1)
- LAN Wins: 0.355[<sup>2</sup>](#table1)

The average of these factors is 0.310<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1034.7
- 400 + ( ( 0.310 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1034.7


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
|           26 |       15 | 2024-08-03 | NIP Impact    | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.229 (0.062)    | 0 (0.000) |     4.14 | ANa, Kat, tory, twenty3, zAAz |
|           25 |       36 | 2024-08-02 | Astralis W    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.03 | ANa, Kat, tory, twenty3, zAAz |
|           24 |     1524 | 2024-06-02 | Let Her Cook  | W   | 0.783      | 0.524        | 0.060 (0.025)    | 0.144 (0.059)    | 1 (0.783) |     8.27 | ANa, Kat, tory, twenty3, zAAz |
|           23 |     1532 | 2024-06-02 | panelinha     | W   | 0.781      | 0.524        | 0.032 (0.013)    | 0.154 (0.063)    | 1 (0.781) |     6.61 | ANa, Kat, tory, twenty3, zAAz |
|           22 |     1586 | 2024-05-31 | BIG EQUIPA    | W   | 0.770      | 0.524        | 0.017 (0.007)    | 0.151 (0.061)    | 1 (0.770) |     4.70 | ANa, Kat, tory, twenty3, zAAz |
|           21 |     1601 | 2024-05-31 | HSG fe        | W   | 0.768      | 0.524        | 0.031 (0.013)    | 0.070 (0.028)    | 1 (0.768) |     5.84 | ANa, Kat, tory, twenty3, zAAz |
|           20 |     1907 | 2024-05-19 | NAVI Javelins | L   | 0.688      | -            | -                | -                | -         |   -15.96 | ANa, Kat, tory, twenty3, zAAz |
|           19 |     1915 | 2024-05-19 | NIP Impact    | W   | 0.687      | 0.281        | 0.005 (0.001)    | 0.229 (0.044)    | 0 (0.000) |     3.14 | ANa, Kat, tory, twenty3, zAAz |
|           18 |     1933 | 2024-05-18 | Crescent fe   | W   | 0.682      | 0.281        | 0.005 (0.001)    | -                | 0 (0.000) |     1.99 | ANa, Kat, tory, twenty3, zAAz |
|           17 |     2315 | 2024-05-05 | Crescent fe   | W   | 0.594      | -            | -                | -                | 0 (0.000) |     1.77 | ANa, Kat, tory, twenty3, zAAz |
|           16 |     2481 | 2024-04-27 | NIP Impact    | W   | 0.541      | 0.252        | -                | 0.229 (0.031)    | 0 (0.000) |     2.48 | ANa, Kat, tory, twenty3, zAAz |
|           15 |     2485 | 2024-04-27 | Spirit fe     | W   | 0.541      | -            | -                | -                | -         |     1.66 | ANa, Kat, tory, twenty3, zAAz |
|           14 |     2677 | 2024-04-19 | Astralis W    | W   | 0.489      | -            | -                | -                | -         |     1.72 | ANa, Kat, tory, twenty3, zAAz |
|           13 |     2804 | 2024-04-16 | NAVI Javelins | L   | 0.469      | -            | -                | -                | -         |   -11.39 | ANa, Kat, tory, twenty3, zAAz |
|           12 |     2839 | 2024-04-14 | NIP Impact    | W   | 0.455      | 0.303        | -                | 0.229 (0.032)    | -         |     2.11 | ANa, Kat, tory, twenty3, zAAz |
|           11 |     2857 | 2024-04-13 | NAVI Javelins | W   | 0.448      | 0.303        | 0.026 (0.004)    | 0.189 (0.026)    | -         |     3.13 | ANa, Kat, tory, twenty3, zAAz |
|           10 |     2891 | 2024-04-11 | Astralis W    | W   | 0.435      | -            | -                | -                | -         |     1.14 | ANa, Kat, tory, twenty3, zAAz |
|            9 |     2940 | 2024-04-10 | Astralis W    | W   | 0.428      | -            | -                | -                | -         |     1.14 | ANa, Kat, tory, twenty3, zAAz |
|            8 |     3026 | 2024-04-08 | Crescent fe   | W   | 0.414      | -            | -                | -                | -         |     1.40 | ANa, Kat, tory, twenty3, zAAz |
|            7 |     3057 | 2024-04-07 | NIP Impact    | W   | 0.408      | 0.262        | -                | 0.229 (0.024)    | -         |     1.84 | ANa, Kat, tory, twenty3, zAAz |
|            6 |     3061 | 2024-04-07 | BIG EQUIPA    | W   | 0.407      | 0.262        | 0.017 (0.002)    | -                | -         |     2.39 | ANa, Kat, tory, twenty3, zAAz |
|            5 |     3077 | 2024-04-06 | ENCE Athena   | W   | 0.400      | -            | -                | -                | -         |     1.22 | ANa, Kat, tory, twenty3, zAAz |
|            4 |     3298 | 2024-03-27 | ENCE Athena   | W   | 0.336      | -            | -                | -                | -         |     1.05 | ANa, Kat, tory, twenty3, zAAz |
|            3 |     3535 | 2024-03-14 | BIG EQUIPA    | W   | 0.249      | 0.331        | 0.017 (0.001)    | -                | -         |     1.49 | ANa, Kat, tory, twenty3, zAAz |
|            2 |     3711 | 2024-03-07 | NIP Impact    | W   | 0.202      | -            | -                | -                | -         |     0.86 | ANa, Kat, tory, twenty3, zAAz |
|            1 |     3943 | 2024-02-26 | 500           | L   | 0.134      | -            | -                | -                | -         |    -3.64 | ANa, Kat, tory, twenty3, zAAz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,651.34)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.783 | $50,000.00     | $39,152.78      |
| 2024-05-19 |      0.688 | $800.00        | $550.30         |
| 2024-05-05 |      0.594 | $750.00        | $445.83         |
| 2024-04-27 |      0.541 | $535.00        | $289.62         |
| 2024-04-16 |      0.469 | $1,500.00      | $702.92         |
| 2024-04-07 |      0.408 | $1,250.00      | $509.90         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
