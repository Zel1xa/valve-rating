### Roster Details<br />
Team Name: Entropiq<br />
Roster: c0llins, Marix, mwlky, oxygeN, tiziaN<br />
Global Rank: [194](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [122]( ../standings_europe.md)<br />
<br />
Final Rank Value:  563.1<br />
<br />
Final Rank Value (563.1) = Starting Rank Value (545.8) + Head To Head Adjustments (17.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.269[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.071<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 545.8
- 400 + ( ( 0.071 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 545.8


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
|           14 |     3557 | 2024-03-15 | MOUZ NXT        | L   | 0.247      | -            | -                | -                | -         |    -0.50 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           13 |     3593 | 2024-03-14 | ex-Preasy       | L   | 0.239      | -            | -                | -                | -         |    -1.62 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           12 |     3683 | 2024-03-11 | ECLOT           | W   | 0.219      | 0.371        | 0.062 (0.005)    | 0.557 (0.045)    | 0 (0.000) |     6.72 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           11 |     3699 | 2024-03-10 | ALTERNATE aTTaX | W   | 0.213      | 0.371        | 0.031 (0.002)    | 0.557 (0.044)    | 0 (0.000) |     6.16 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           10 |     3729 | 2024-03-09 | Alliance        | L   | 0.206      | -            | -                | -                | -         |    -1.02 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            9 |     3745 | 2024-03-08 | Passion UA      | L   | 0.200      | -            | -                | -                | -         |    -0.30 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            8 |     3845 | 2024-03-05 | 500             | L   | 0.179      | -            | -                | -                | -         |    -1.67 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            7 |     3862 | 2024-03-04 | Sashi           | W   | 0.172      | 0.371        | 0.184 (0.012)    | 0.996 (0.064)    | 0 (0.000) |     5.24 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            6 |     3991 | 2024-02-26 | 9INE            | W   | 0.127      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     1.74 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            5 |     4012 | 2024-02-25 | Secret          | W   | 0.120      | 0.358        | 0.000 (0.000)    | 0.057 (0.002)    | 0 (0.000) |     1.85 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            4 |     4062 | 2024-02-23 | Sampi           | L   | 0.106      | -            | -                | -                | -         |    -0.43 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            3 |     4115 | 2024-02-21 | MOUZ NXT        | L   | 0.092      | -            | -                | -                | -         |    -0.17 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            2 |     4196 | 2024-02-17 | The Chosen Few  | W   | 0.068      | 0.358        | 0.001 (0.000)    | 0.041 (0.001)    | 0 (0.000) |     1.44 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            1 |     4345 | 2024-02-11 | ALTERNATE aTTaX | L   | 0.028      | -            | -                | -                | -         |    -0.07 | c0llins, Marix, mwlky, oxygeN, tiziaN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
