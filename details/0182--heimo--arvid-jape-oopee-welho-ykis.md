### Roster Details<br />
Team Name: Heimo<br />
Roster: arvid, japE, oopee, Welho, ykis<br />
Global Rank: [182](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [115]( ../standings_europe.md)<br />
<br />
Final Rank Value:  626.9<br />
<br />
Final Rank Value (626.9) = Starting Rank Value (677.5) + Head To Head Adjustments (-50.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 677.5
- 400 + ( ( 0.135 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 677.5


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
|           12 |      147 | 2024-08-01 | JANO         | L   | 1.000      | -            | -                | -                | -         |   -15.83 | arvid, japE, oopee, Welho, ykis    |
|           11 |      528 | 2024-07-21 | INFINITE     | L   | 1.000      | -            | -                | -                | -         |   -17.90 | arvid, japE, oopee, Welho, ykis    |
|           10 |      567 | 2024-07-20 | 777          | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.173 (0.025)    | 0 (0.000) |    16.84 | arvid, japE, oopee, Welho, ykis    |
|            9 |      593 | 2024-07-19 | CPH Wolves   | L   | 1.000      | -            | -                | -                | -         |    -7.59 | arvid, japE, oopee, Welho, ykis    |
|            8 |     1000 | 2024-06-24 | lajtbitexe   | L   | 0.914      | -            | -                | -                | -         |   -12.44 | arvid, oopee, Sm1llee, Welho, ykis |
|            7 |     1006 | 2024-06-23 | Revenant     | L   | 0.906      | -            | -                | -                | -         |    -8.67 | arvid, oopee, Sm1llee, Welho, ykis |
|            6 |     1612 | 2024-06-02 | HAVU         | L   | 0.766      | -            | -                | -                | -         |   -11.30 | arvid, japE, oopee, Welho, ykis    |
|            5 |     2194 | 2024-05-14 | NOM          | L   | 0.639      | -            | -                | -                | -         |   -13.88 | arvid, japE, oopee, Welho, ykis    |
|            4 |     2212 | 2024-05-13 | DMS          | L   | 0.634      | -            | -                | -                | -         |    -4.93 | arvid, japE, oopee, Welho, ykis    |
|            3 |     2379 | 2024-05-05 | ENCE Academy | W   | 0.581      | 0.306        | 0.003 (0.001)    | 0.104 (0.019)    | 0 (0.000) |    10.23 | arvid, japE, oopee, Welho, ykis    |
|            2 |     2398 | 2024-05-04 | jefet        | W   | 0.574      | 0.306        | 0.001 (0.000)    | 0.021 (0.004)    | 0 (0.000) |     5.32 | arvid, japE, oopee, Welho, ykis    |
|            1 |     2532 | 2024-04-28 | ENCE Academy | W   | 0.534      | 0.306        | 0.004 (0.001)    | 0.077 (0.013)    | 0 (0.000) |     9.49 | arvid, japE, oopee, Welho, ykis    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,869.17)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
