### Roster Details<br />
Team Name: Imperial fe<br />
Roster: ANa, Kat, tory, twenty3, zAAz<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1069.7<br />
<br />
Final Rank Value (1069.7) = Starting Rank Value (1045.7) + Head To Head Adjustments (24.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.530[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.038[<sup>2</sup>](#table1)
- LAN Wins: 0.367[<sup>2</sup>](#table1)

The average of these factors is 0.313<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1045.7
- 400 + ( ( 0.313 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1045.7


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
|           25 |     1407 | 2024-06-02 | Let Her Cook  | W   | 0.807      | 0.524        | 0.061 (0.026)    | 0.147 (0.062)    | 1 (0.807) |     8.49 | ANa, Kat, tory, twenty3, zAAz |
|           24 |     1415 | 2024-06-02 | panelinha     | W   | 0.805      | 0.524        | 0.032 (0.014)    | 0.159 (0.067)    | 1 (0.805) |     6.80 | ANa, Kat, tory, twenty3, zAAz |
|           23 |     1469 | 2024-05-31 | BIG EQUIPA    | W   | 0.794      | 0.524        | 0.017 (0.007)    | 0.156 (0.065)    | 1 (0.794) |     4.80 | ANa, Kat, tory, twenty3, zAAz |
|           22 |     1484 | 2024-05-31 | HSG fe        | W   | 0.792      | 0.524        | 0.032 (0.013)    | 0.071 (0.029)    | 1 (0.792) |     5.99 | ANa, Kat, tory, twenty3, zAAz |
|           21 |     1790 | 2024-05-19 | NAVI Javelins | L   | 0.712      | -            | -                | -                | -         |   -16.55 | ANa, Kat, tory, twenty3, zAAz |
|           20 |     1798 | 2024-05-19 | NIP Impact    | W   | 0.711      | 0.281        | 0.005 (0.001)    | 0.191 (0.038)    | 0 (0.000) |     3.15 | ANa, Kat, tory, twenty3, zAAz |
|           19 |     1816 | 2024-05-18 | Crescent fe   | W   | 0.705      | 0.281        | 0.005 (0.001)    | -                | 0 (0.000) |     1.98 | ANa, Kat, tory, twenty3, zAAz |
|           18 |     2198 | 2024-05-05 | Crescent fe   | W   | 0.618      | -            | -                | -                | 0 (0.000) |     1.77 | ANa, Kat, tory, twenty3, zAAz |
|           17 |     2364 | 2024-04-27 | NIP Impact    | W   | 0.565      | 0.252        | -                | 0.191 (0.027)    | 0 (0.000) |     2.51 | ANa, Kat, tory, twenty3, zAAz |
|           16 |     2368 | 2024-04-27 | Spirit fe     | W   | 0.565      | -            | -                | -                | 0 (0.000) |     1.62 | ANa, Kat, tory, twenty3, zAAz |
|           15 |     2560 | 2024-04-19 | ex-GUILD fe   | W   | 0.513      | -            | -                | -                | 0 (0.000) |     1.75 | ANa, Kat, tory, twenty3, zAAz |
|           14 |     2687 | 2024-04-16 | NAVI Javelins | L   | 0.492      | -            | -                | -                | -         |   -12.01 | ANa, Kat, tory, twenty3, zAAz |
|           13 |     2722 | 2024-04-14 | NIP Impact    | W   | 0.479      | 0.303        | 0.005 (0.001)    | 0.191 (0.028)    | -         |     2.15 | ANa, Kat, tory, twenty3, zAAz |
|           12 |     2740 | 2024-04-13 | NAVI Javelins | W   | 0.472      | 0.303        | 0.027 (0.004)    | 0.194 (0.028)    | -         |     3.23 | ANa, Kat, tory, twenty3, zAAz |
|           11 |     2774 | 2024-04-11 | Astralis W    | W   | 0.459      | -            | -                | -                | -         |     1.16 | ANa, Kat, tory, twenty3, zAAz |
|           10 |     2823 | 2024-04-10 | Astralis W    | W   | 0.452      | -            | -                | -                | -         |     1.16 | ANa, Kat, tory, twenty3, zAAz |
|            9 |     2909 | 2024-04-08 | Crescent fe   | W   | 0.438      | -            | -                | -                | -         |     1.43 | ANa, Kat, tory, twenty3, zAAz |
|            8 |     2940 | 2024-04-07 | NIP Impact    | W   | 0.432      | 0.262        | -                | 0.191 (0.022)    | -         |     1.88 | ANa, Kat, tory, twenty3, zAAz |
|            7 |     2944 | 2024-04-07 | BIG EQUIPA    | W   | 0.431      | 0.262        | 0.017 (0.002)    | 0.156 (0.018)    | -         |     2.49 | ANa, Kat, tory, twenty3, zAAz |
|            6 |     2960 | 2024-04-06 | ENCE Athena   | W   | 0.424      | -            | -                | -                | -         |     1.25 | ANa, Kat, tory, twenty3, zAAz |
|            5 |     3181 | 2024-03-27 | ENCE Athena   | W   | 0.359      | -            | -                | -                | -         |     1.09 | ANa, Kat, tory, twenty3, zAAz |
|            4 |     3418 | 2024-03-14 | BIG EQUIPA    | W   | 0.273      | 0.331        | 0.017 (0.002)    | -                | -         |     1.61 | ANa, Kat, tory, twenty3, zAAz |
|            3 |     3594 | 2024-03-07 | NIP Impact    | W   | 0.226      | -            | -                | -                | -         |     0.93 | ANa, Kat, tory, twenty3, zAAz |
|            2 |     3826 | 2024-02-26 | 500           | L   | 0.157      | -            | -                | -                | -         |    -4.30 | ANa, Kat, tory, twenty3, zAAz |
|            1 |     4248 | 2024-02-05 | Sampi         | L   | 0.018      | -            | -                | -                | -         |    -0.40 | ANa, Kat, tory, twenty3, zAAz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($42,955.45)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.807 | $50,000.00     | $40,341.90      |
| 2024-05-19 |      0.712 | $800.00        | $569.32         |
| 2024-05-05 |      0.618 | $750.00        | $463.67         |
| 2024-04-27 |      0.565 | $535.00        | $302.34         |
| 2024-04-16 |      0.492 | $1,500.00      | $738.59         |
| 2024-04-07 |      0.432 | $1,250.00      | $539.62         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
