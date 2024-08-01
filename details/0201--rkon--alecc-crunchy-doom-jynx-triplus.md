### Roster Details<br />
Team Name: RKON<br />
Roster: alecc, Crunchy, doom, Jynx, TRIPLUS<br />
Global Rank: [201](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [22]( ../standings_asia.md)<br />
<br />
Final Rank Value:  513.5<br />
<br />
Final Rank Value (513.5) = Starting Rank Value (504.2) + Head To Head Adjustments (9.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.198[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.051<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 504.2
- 400 + ( ( 0.051 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 504.2


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
|           12 |     3184 | 2024-04-03 | Rooster     | L   | 0.399      | -            | -                | -                | -         |    -2.12 | alecc, Crunchy, doom, Jynx, TRIPLUS    |
|           11 |     3185 | 2024-04-03 | Rooster     | L   | 0.399      | -            | -                | -                | -         |    -2.17 | alecc, Crunchy, doom, Jynx, TRIPLUS    |
|           10 |     3305 | 2024-03-27 | DXA         | W   | 0.353      | 0.333        | 0.002 (0.000)    | 0.228 (0.027)    | 0 (0.000) |     8.13 | alecc, Crunchy, doom, Jynx, TRIPLUS    |
|            9 |     3310 | 2024-03-27 | DXA         | L   | 0.353      | -            | -                | -                | -         |    -3.02 | alecc, Crunchy, doom, Jynx, TRIPLUS    |
|            8 |     3586 | 2024-03-13 | KZG         | W   | 0.260      | 0.333        | 0.006 (0.000)    | 0.113 (0.010)    | 0 (0.000) |     6.09 | alecc, Crunchy, Jynx, Poccket, TRIPLUS |
|            7 |     3593 | 2024-03-13 | KZG         | L   | 0.259      | -            | -                | -                | -         |    -2.10 | alecc, Crunchy, Jynx, Poccket, TRIPLUS |
|            6 |     3943 | 2024-02-27 | Vantage     | L   | 0.159      | -            | -                | -                | -         |    -1.55 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS  |
|            5 |     3945 | 2024-02-27 | Vantage     | W   | 0.159      | 0.333        | 0.002 (0.000)    | 0.075 (0.004)    | 0 (0.000) |     3.50 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS  |
|            4 |     4082 | 2024-02-21 | Canon Event | W   | 0.120      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.94 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS  |
|            3 |     4085 | 2024-02-21 | Canon Event | W   | 0.119      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.95 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS  |
|            2 |     4115 | 2024-02-20 | Mindfreak   | L   | 0.112      | -            | -                | -                | -         |    -0.94 | alecc, Bumb1e, Crunchy, Jynx, TRIPLUS  |
|            1 |     4316 | 2024-02-13 | KZG         | L   | 0.066      | -            | -                | -                | -         |    -0.49 | alecc, Bumb1e, Jynx, PixeL, TRIPLUS    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
