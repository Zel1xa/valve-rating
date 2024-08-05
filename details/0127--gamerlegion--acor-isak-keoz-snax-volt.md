### Roster Details<br />
Team Name: GamerLegion<br />
Roster: acoR, isak, Keoz, Snax, volt<br />
Global Rank: [127](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [87]( ../standings_europe.md)<br />
<br />
Final Rank Value:  789.9<br />
<br />
Final Rank Value (789.9) = Starting Rank Value (769.3) + Head To Head Adjustments (20.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.266[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.106[<sup>2</sup>](#table1)

The average of these factors is 0.180<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 769.3
- 400 + ( ( 0.180 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 769.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     3466 | 2024-03-20 | Imperial        | L   | 0.280      | -            | -                | -                | -         |    -0.59 | acoR, isak, Keoz, Snax, volt |
|           13 |     3484 | 2024-03-19 | Eternal Fire    | L   | 0.273      | -            | -                | -                | -         |    -0.05 | acoR, isak, Keoz, Snax, volt |
|           12 |     3493 | 2024-03-18 | Legacy          | W   | 0.267      | 0.143        | 0.122 (0.005)    | 0.642 (0.024)    | 1 (0.267) |     6.65 | acoR, isak, Keoz, Snax, volt |
|           11 |     3502 | 2024-03-17 | SAW             | L   | 0.262      | -            | -                | -                | -         |    -0.82 | acoR, isak, Keoz, Snax, volt |
|           10 |     3518 | 2024-03-17 | AMKAL           | W   | 0.261      | 0.143        | 0.130 (0.005)    | 0.472 (0.018)    | 1 (0.261) |     7.24 | acoR, isak, Keoz, Snax, volt |
|            9 |     3738 | 2024-03-08 | BIG             | L   | 0.201      | -            | -                | -                | -         |    -0.32 | acoR, isak, Keoz, Snax, volt |
|            8 |     4043 | 2024-02-24 | 9 Pandas        | L   | 0.114      | -            | -                | -                | -         |    -0.80 | acoR, isak, Keoz, Snax, volt |
|            7 |     4050 | 2024-02-24 | ex-Guild Eagles | W   | 0.113      | 0.143        | 0.007 (0.000)    | 0.217 (0.003)    | 1 (0.113) |     1.97 | acoR, isak, Keoz, Snax, volt |
|            6 |     4058 | 2024-02-23 | fnatic          | W   | 0.107      | 0.143        | 0.371 (0.006)    | 0.706 (0.011)    | 1 (0.107) |     3.34 | acoR, isak, Keoz, Snax, volt |
|            5 |     4076 | 2024-02-22 | HEROIC          | L   | 0.101      | -            | -                | -                | -         |    -0.04 | acoR, isak, Keoz, Snax, volt |
|            4 |     4102 | 2024-02-21 | OG              | W   | 0.094      | 0.143        | 0.138 (0.002)    | 0.126 (0.002)    | 1 (0.094) |     2.29 | acoR, isak, Keoz, Snax, volt |
|            3 |     4134 | 2024-02-20 | ENCE            | L   | 0.086      | -            | -                | -                | -         |    -0.05 | acoR, isak, Keoz, Snax, volt |
|            2 |     4155 | 2024-02-19 | PERA            | W   | 0.081      | 0.143        | 0.048 (0.001)    | 0.451 (0.005)    | 1 (0.081) |     1.81 | acoR, isak, Keoz, Snax, volt |
|            1 |     4164 | 2024-02-19 | Vitality        | L   | 0.079      | -            | -                | -                | -         |    -0.01 | acoR, isak, Keoz, Snax, volt |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,887.85)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-20 |      0.281 | $10,000.00     | $2,812.50       |
| 2024-03-10 |      0.215 | $5,000.00      | $1,075.35       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
