### Roster Details<br />
Team Name: 777<br />
Roster: Hagmeister, qzr, SLY, Viktha, Wenba<br />
Global Rank: [178](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [113]( ../standings_europe.md)<br />
<br />
Final Rank Value:  643.3<br />
<br />
Final Rank Value (643.3) = Starting Rank Value (705.2) + Head To Head Adjustments (-61.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.354[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.2
- 400 + ( ( 0.149 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 705.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |        5 | 2024-08-05 | ECSTATIC      | L   | 1.000      | -            | -                | -                | -         |   -19.93 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           19 |       10 | 2024-08-05 | TSM           | L   | 1.000      | -            | -                | -                | -         |    -4.75 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           18 |      556 | 2024-07-20 | Heimo         | L   | 1.000      | -            | -                | -                | -         |   -16.85 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           17 |      570 | 2024-07-19 | INFINITE      | L   | 1.000      | -            | -                | -                | -         |   -20.30 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           16 |      947 | 2024-07-06 | Revenant      | L   | 0.999      | -            | -                | -                | -         |   -11.39 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           15 |     1030 | 2024-06-16 | CPH Wolves    | L   | 0.865      | -            | -                | -                | -         |   -10.40 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           14 |     1064 | 2024-06-15 | The Prodigies | W   | 0.859      | 0.143        | 0.000 (0.000)    | 0.092 (0.011)    | 0 (0.000) |     8.18 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           13 |     1167 | 2024-06-12 | ADEPTS        | W   | 0.839      | 0.143        | 0.002 (0.000)    | 0.026 (0.003)    | 0 (0.000) |    10.94 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           12 |     1181 | 2024-06-11 | The Prodigies | L   | 0.833      | -            | -                | -                | -         |   -18.02 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           11 |     1633 | 2024-06-01 | VP.Prodigy    | L   | 0.765      | -            | -                | -                | -         |    -6.49 | Affava, Hagmeister, qzr, Viktha, Wenba       |
|           10 |     1766 | 2024-05-26 | Metizport X   | W   | 0.726      | 0.322        | 0.005 (0.001)    | 0.025 (0.006)    | 0 (0.000) |     9.06 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            9 |     1991 | 2024-05-18 | DMS           | L   | 0.673      | -            | -                | -                | -         |    -5.36 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            8 |     2040 | 2024-05-17 | Space         | W   | 0.664      | 0.143        | 0.006 (0.001)    | 0.439 (0.042)    | 0 (0.000) |    13.74 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            7 |     2070 | 2024-05-16 | Rounds        | W   | 0.659      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.02 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            6 |     2106 | 2024-05-15 | GUN5          | L   | 0.654      | -            | -                | -                | -         |    -4.68 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            5 |     2249 | 2024-05-11 | Metizport X   | W   | 0.626      | 0.322        | 0.005 (0.001)    | 0.025 (0.005)    | 0 (0.000) |     8.21 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            4 |     2530 | 2024-04-27 | Sashi         | L   | 0.534      | -            | -                | -                | -         |    -1.17 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            3 |     2541 | 2024-04-27 | Preasy        | W   | 0.532      | 0.336        | 0.008 (0.001)    | 0.221 (0.040)    | 0 (0.000) |    10.04 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            2 |     2910 | 2024-04-13 | Norway        | L   | 0.440      | -            | -                | -                | -         |    -6.97 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            1 |     3517 | 2024-03-17 | INFURITY      | W   | 0.261      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.26 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,855.85)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.726 | $3,864.00      | $2,806.77       |
| 2024-04-27 |      0.534 | $2,655.00      | $1,417.48       |
| 2024-04-13 |      0.440 | $1,436.00      | $631.61         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
