### Roster Details<br />
Team Name: ENCE Academy<br />
Roster: 2high, millert, myltsi, Schwarz, teme<br />
Global Rank: [163](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [105]( ../standings_europe.md)<br />
<br />
Final Rank Value:  659.4<br />
<br />
Final Rank Value (659.4) = Starting Rank Value (682.6) + Head To Head Adjustments (-23.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.269[<sup>1</sup>](#table2)
- Bounty Collected: 0.207[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.099[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 682.6
- 400 + ( ( 0.146 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 682.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      600 | 2024-08-22 | Verdant    | L   | 1.000      | -            | -                | -                | -         |    -9.84 | 2high, millert, myltsi, Schwarz, teme |
|            9 |      676 | 2024-08-21 | Revenant   | L   | 1.000      | -            | -                | -                | -         |    -6.12 | 2high, millert, myltsi, Schwarz, teme |
|            8 |     1213 | 2024-08-03 | JANO       | L   | 0.960      | -            | -                | -                | -         |   -17.80 | 2high, millert, myltsi, Schwarz, teme |
|            7 |     1235 | 2024-08-02 | HAVU       | W   | 0.954      | 0.143        | 0.000 (0.000)    | 0.134 (0.018)    | 1 (0.954) |    10.30 | 2high, millert, myltsi, Schwarz, teme |
|            6 |     3499 | 2024-05-06 | Permitta   | L   | 0.366      | -            | -                | -                | -         |    -2.48 | 2high, HENU, myltsi, podi, teme       |
|            5 |     3510 | 2024-05-05 | Heimo      | L   | 0.361      | -            | -                | -                | -         |    -6.25 | 2high, HENU, myltsi, podi, teme       |
|            4 |     3519 | 2024-05-05 | jefet      | W   | 0.360      | 0.306        | 0.001 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     3.10 | 2high, HENU, myltsi, podi, teme       |
|            3 |     3534 | 2024-05-04 | TMVG       | W   | 0.353      | 0.306        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.82 | 2high, HENU, myltsi, podi, teme       |
|            2 |     3554 | 2024-05-03 | Nexus      | W   | 0.346      | 0.435        | 0.010 (0.001)    | 0.432 (0.065)    | 0 (0.000) |     7.03 | 2high, HENU, myltsi, podi, teme       |
|            1 |     3586 | 2024-05-01 | Enterprise | L   | 0.335      | -            | -                | -                | -         |    -2.94 | 2high, HENU, myltsi, podi, teme       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($580.22)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
