### Roster Details<br />
Team Name: Entropiq<br />
Roster: c0llins, Marix, mwlky, oxygeN, tiziaN<br />
Global Rank: [194](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [122]( ../standings_europe.md)<br />
<br />
Final Rank Value:  562.9<br />
<br />
Final Rank Value (562.9) = Starting Rank Value (545.7) + Head To Head Adjustments (17.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.269[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.071<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 545.7
- 400 + ( ( 0.071 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 545.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     3566 | 2024-03-15 | MOUZ NXT        | L   | 0.245      | -            | -                | -                | -         |    -0.49 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           13 |     3602 | 2024-03-14 | ex-Preasy       | L   | 0.237      | -            | -                | -                | -         |    -1.61 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           12 |     3692 | 2024-03-11 | ECLOT           | W   | 0.217      | 0.371        | 0.062 (0.005)    | 0.550 (0.044)    | 0 (0.000) |     6.68 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           11 |     3708 | 2024-03-10 | ALTERNATE aTTaX | W   | 0.212      | 0.371        | 0.031 (0.002)    | 0.550 (0.043)    | 0 (0.000) |     6.12 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           10 |     3738 | 2024-03-09 | Alliance        | L   | 0.205      | -            | -                | -                | -         |    -1.01 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            9 |     3754 | 2024-03-08 | Passion UA      | L   | 0.198      | -            | -                | -                | -         |    -0.29 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            8 |     3854 | 2024-03-05 | 500             | L   | 0.178      | -            | -                | -                | -         |    -1.66 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            7 |     3871 | 2024-03-04 | Sashi           | W   | 0.171      | 0.371        | 0.184 (0.012)    | 0.983 (0.062)    | 0 (0.000) |     5.20 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            6 |     4000 | 2024-02-26 | 9INE            | W   | 0.125      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     1.72 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            5 |     4021 | 2024-02-25 | Secret          | W   | 0.118      | 0.358        | 0.000 (0.000)    | 0.057 (0.002)    | 0 (0.000) |     1.82 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            4 |     4071 | 2024-02-23 | Sampi           | L   | 0.104      | -            | -                | -                | -         |    -0.43 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            3 |     4124 | 2024-02-21 | MOUZ NXT        | L   | 0.091      | -            | -                | -                | -         |    -0.17 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            2 |     4205 | 2024-02-17 | The Chosen Few  | W   | 0.067      | 0.358        | 0.001 (0.000)    | 0.040 (0.001)    | 0 (0.000) |     1.40 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            1 |     4354 | 2024-02-11 | ALTERNATE aTTaX | L   | 0.027      | -            | -                | -                | -         |    -0.07 | c0llins, Marix, mwlky, oxygeN, tiziaN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
