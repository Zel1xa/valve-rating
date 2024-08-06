### Roster Details<br />
Team Name: RKON<br />
Roster: alecc, Crunchy, doom, Jynx, TRIPLUS<br />
Global Rank: [200](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [22]( ../standings_asia.md)<br />
<br />
Final Rank Value:  514.0<br />
<br />
Final Rank Value (514.0) = Starting Rank Value (502.1) + Head To Head Adjustments (11.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.196[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.050<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 502.1
- 400 + ( ( 0.050 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 502.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     3368 | 2024-03-27 | DXA         | W   | 0.323      | 0.333        | 0.002 (0.000)    | 0.222 (0.024)    | 0 (0.000) |     7.52 | alecc, Crunchy, doom, Jynx, TRIPLUS    |
|            9 |     3373 | 2024-03-27 | DXA         | L   | 0.323      | -            | -                | -                | -         |    -2.67 | alecc, Crunchy, doom, Jynx, TRIPLUS    |
|            8 |     3641 | 2024-03-13 | KZG         | W   | 0.229      | 0.333        | 0.005 (0.000)    | 0.109 (0.008)    | 0 (0.000) |     5.38 | alecc, Crunchy, Jynx, Poccket, TRIPLUS |
|            7 |     3648 | 2024-03-13 | KZG         | L   | 0.229      | -            | -                | -                | -         |    -1.86 | alecc, Crunchy, Jynx, Poccket, TRIPLUS |
|            6 |     3989 | 2024-02-27 | Vantage     | L   | 0.129      | -            | -                | -                | -         |    -1.26 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS  |
|            5 |     3992 | 2024-02-27 | Vantage     | W   | 0.129      | 0.333        | 0.002 (0.000)    | 0.067 (0.003)    | 0 (0.000) |     2.83 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS  |
|            4 |     4120 | 2024-02-21 | Canon Event | W   | 0.089      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.46 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS  |
|            3 |     4123 | 2024-02-21 | Canon Event | W   | 0.089      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.46 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS  |
|            2 |     4153 | 2024-02-20 | Mindfreak   | L   | 0.082      | -            | -                | -                | -         |    -0.66 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS  |
|            1 |     4346 | 2024-02-13 | KZG         | L   | 0.036      | -            | -                | -                | -         |    -0.27 | alecc, Bumb1e, Jynx, PixeL, TRIPLUS    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
