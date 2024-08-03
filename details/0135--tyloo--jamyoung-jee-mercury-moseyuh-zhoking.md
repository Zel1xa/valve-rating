### Roster Details<br />
Team Name: TYLOO<br />
Roster: JamYoung, Jee, Mercury, Moseyuh, zhokiNg<br />
Global Rank: [135](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [10]( ../standings_asia.md)<br />
<br />
Final Rank Value:  759.1<br />
<br />
Final Rank Value (759.1) = Starting Rank Value (705.2) + Head To Head Adjustments (53.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.345[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.2
- 400 + ( ( 0.149 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 705.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |       73 | 2024-08-01 | CatEvil           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.243 (0.035)    | 0 (0.000) |    10.89 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            9 |      754 | 2024-07-13 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -14.93 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            8 |      756 | 2024-07-13 | CatEvil           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.243 (0.035)    | 0 (0.000) |     9.85 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            7 |      766 | 2024-07-12 | Chinggis Warriors | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.159 (0.023)    | 0 (0.000) |    16.38 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            6 |      770 | 2024-07-12 | Alter Ego         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.081 (0.012)    | 0 (0.000) |     6.75 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            5 |     1209 | 2024-06-08 | Lynn Vision       | L   | 0.825      | -            | -                | -                | -         |    -5.20 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|            4 |     1262 | 2024-06-07 | GR                | W   | 0.819      | 0.416        | 0.008 (0.003)    | 0.078 (0.027)    | 0 (0.000) |    10.89 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|            3 |     1329 | 2024-06-06 | The QUBE          | W   | 0.812      | 0.416        | 0.005 (0.002)    | 0.065 (0.022)    | 0 (0.000) |    11.38 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|            2 |     1386 | 2024-06-05 | Lynn Vision       | L   | 0.805      | -            | -                | -                | -         |    -4.45 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|            1 |     1427 | 2024-06-04 | LYG               | W   | 0.799      | 0.416        | 0.003 (0.001)    | 0.035 (0.012)    | 0 (0.000) |    12.36 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,157.18)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
