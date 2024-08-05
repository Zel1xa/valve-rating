### Roster Details<br />
Team Name: Heimo<br />
Roster: arvid, japE, oopee, Welho, ykis<br />
Global Rank: [183](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [116]( ../standings_europe.md)<br />
<br />
Final Rank Value:  626.2<br />
<br />
Final Rank Value (626.2) = Starting Rank Value (676.9) + Head To Head Adjustments (-50.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 676.9
- 400 + ( ( 0.135 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 676.9


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
|           12 |      136 | 2024-08-01 | JANO         | L   | 1.000      | -            | -                | -                | -         |   -15.85 | arvid, japE, oopee, Welho, ykis    |
|           11 |      517 | 2024-07-21 | INFINITE     | L   | 1.000      | -            | -                | -                | -         |   -17.91 | arvid, japE, oopee, Welho, ykis    |
|           10 |      556 | 2024-07-20 | 777          | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.177 (0.025)    | 0 (0.000) |    16.85 | arvid, japE, oopee, Welho, ykis    |
|            9 |      582 | 2024-07-19 | CPH Wolves   | L   | 1.000      | -            | -                | -                | -         |    -7.59 | arvid, japE, oopee, Welho, ykis    |
|            8 |      989 | 2024-06-24 | lajtbitexe   | L   | 0.919      | -            | -                | -                | -         |   -12.51 | arvid, oopee, Sm1llee, Welho, ykis |
|            7 |      995 | 2024-06-23 | Revenant     | L   | 0.911      | -            | -                | -                | -         |    -8.72 | arvid, oopee, Sm1llee, Welho, ykis |
|            6 |     1601 | 2024-06-02 | HAVU         | L   | 0.771      | -            | -                | -                | -         |   -11.35 | arvid, japE, oopee, Welho, ykis    |
|            5 |     2183 | 2024-05-14 | NOM          | L   | 0.644      | -            | -                | -                | -         |   -13.98 | arvid, japE, oopee, Welho, ykis    |
|            4 |     2201 | 2024-05-13 | DMS          | L   | 0.639      | -            | -                | -                | -         |    -4.95 | arvid, japE, oopee, Welho, ykis    |
|            3 |     2368 | 2024-05-05 | ENCE Academy | W   | 0.586      | 0.306        | 0.003 (0.001)    | 0.107 (0.019)    | 0 (0.000) |    10.30 | arvid, japE, oopee, Welho, ykis    |
|            2 |     2387 | 2024-05-04 | jefet        | W   | 0.579      | 0.306        | 0.001 (0.000)    | 0.021 (0.004)    | 0 (0.000) |     5.37 | arvid, japE, oopee, Welho, ykis    |
|            1 |     2521 | 2024-04-28 | ENCE Academy | W   | 0.539      | 0.306        | 0.004 (0.001)    | 0.080 (0.013)    | 0 (0.000) |     9.61 | arvid, japE, oopee, Welho, ykis    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,885.24)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
