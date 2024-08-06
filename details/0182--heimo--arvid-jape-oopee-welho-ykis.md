### Roster Details<br />
Team Name: Heimo<br />
Roster: arvid, japE, oopee, Welho, ykis<br />
Global Rank: [182](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [115]( ../standings_europe.md)<br />
<br />
Final Rank Value:  626.4<br />
<br />
Final Rank Value (626.4) = Starting Rank Value (677.0) + Head To Head Adjustments (-50.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 677.0
- 400 + ( ( 0.135 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 677.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |      143 | 2024-08-01 | JANO         | L   | 1.000      | -            | -                | -                | -         |   -15.83 | arvid, japE, oopee, Welho, ykis    |
|           11 |      524 | 2024-07-21 | INFINITE     | L   | 1.000      | -            | -                | -                | -         |   -17.89 | arvid, japE, oopee, Welho, ykis    |
|           10 |      563 | 2024-07-20 | 777          | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.177 (0.025)    | 0 (0.000) |    16.85 | arvid, japE, oopee, Welho, ykis    |
|            9 |      589 | 2024-07-19 | CPH Wolves   | L   | 1.000      | -            | -                | -                | -         |    -7.58 | arvid, japE, oopee, Welho, ykis    |
|            8 |      996 | 2024-06-24 | lajtbitexe   | L   | 0.914      | -            | -                | -                | -         |   -12.44 | arvid, oopee, Sm1llee, Welho, ykis |
|            7 |     1002 | 2024-06-23 | Revenant     | L   | 0.906      | -            | -                | -                | -         |    -8.67 | arvid, oopee, Sm1llee, Welho, ykis |
|            6 |     1608 | 2024-06-02 | HAVU         | L   | 0.767      | -            | -                | -                | -         |   -11.29 | arvid, japE, oopee, Welho, ykis    |
|            5 |     2190 | 2024-05-14 | NOM          | L   | 0.640      | -            | -                | -                | -         |   -13.88 | arvid, japE, oopee, Welho, ykis    |
|            4 |     2208 | 2024-05-13 | DMS          | L   | 0.634      | -            | -                | -                | -         |    -4.92 | arvid, japE, oopee, Welho, ykis    |
|            3 |     2375 | 2024-05-05 | ENCE Academy | W   | 0.582      | 0.306        | 0.003 (0.001)    | 0.107 (0.019)    | 0 (0.000) |    10.23 | arvid, japE, oopee, Welho, ykis    |
|            2 |     2394 | 2024-05-04 | jefet        | W   | 0.575      | 0.306        | 0.001 (0.000)    | 0.021 (0.004)    | 0 (0.000) |     5.33 | arvid, japE, oopee, Welho, ykis    |
|            1 |     2528 | 2024-04-28 | ENCE Academy | W   | 0.534      | 0.306        | 0.004 (0.001)    | 0.079 (0.013)    | 0 (0.000) |     9.50 | arvid, japE, oopee, Welho, ykis    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,870.06)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
