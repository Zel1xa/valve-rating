### Roster Details<br />
Team Name: RKON<br />
Roster: alecc, Crunchy, doom, Jynx, TRIPLUS<br />
Global Rank: [200](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [22]( ../standings_asia.md)<br />
<br />
Final Rank Value:  514.7<br />
<br />
Final Rank Value (514.7) = Starting Rank Value (502.3) + Head To Head Adjustments (12.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.196[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.050<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 502.3
- 400 + ( ( 0.050 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 502.3


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
|           10 |     3339 | 2024-03-27 | DXA         | W   | 0.332      | 0.333        | 0.002 (0.000)    | 0.226 (0.025)    | 0 (0.000) |     7.73 | alecc, Crunchy, doom, Jynx, TRIPLUS    |
|            9 |     3344 | 2024-03-27 | DXA         | L   | 0.332      | -            | -                | -                | -         |    -2.75 | alecc, Crunchy, doom, Jynx, TRIPLUS    |
|            8 |     3612 | 2024-03-13 | KZG         | W   | 0.239      | 0.333        | 0.005 (0.000)    | 0.112 (0.009)    | 0 (0.000) |     5.60 | alecc, Crunchy, Jynx, Poccket, TRIPLUS |
|            7 |     3619 | 2024-03-13 | KZG         | L   | 0.239      | -            | -                | -                | -         |    -1.94 | alecc, Crunchy, Jynx, Poccket, TRIPLUS |
|            6 |     3960 | 2024-02-27 | Vantage     | L   | 0.139      | -            | -                | -                | -         |    -1.36 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS  |
|            5 |     3963 | 2024-02-27 | Vantage     | W   | 0.138      | 0.333        | 0.002 (0.000)    | 0.070 (0.003)    | 0 (0.000) |     3.03 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS  |
|            4 |     4091 | 2024-02-21 | Canon Event | W   | 0.099      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.60 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS  |
|            3 |     4094 | 2024-02-21 | Canon Event | W   | 0.099      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.61 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS  |
|            2 |     4124 | 2024-02-20 | Mindfreak   | L   | 0.091      | -            | -                | -                | -         |    -0.74 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS  |
|            1 |     4317 | 2024-02-13 | KZG         | L   | 0.045      | -            | -                | -                | -         |    -0.34 | alecc, Bumb1e, Jynx, PixeL, TRIPLUS    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
