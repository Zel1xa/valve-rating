### Roster Details<br />
Team Name: Heimo<br />
Roster: arvid, japE, oopee, Welho, ykis<br />
Global Rank: [183](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [116]( ../standings_europe.md)<br />
<br />
Final Rank Value:  627.1<br />
<br />
Final Rank Value (627.1) = Starting Rank Value (677.5) + Head To Head Adjustments (-50.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
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
|           12 |      161 | 2024-08-01 | JANO         | L   | 1.000      | -            | -                | -                | -         |   -15.83 | arvid, japE, oopee, Welho, ykis    |
|           11 |      542 | 2024-07-21 | INFINITE     | L   | 1.000      | -            | -                | -                | -         |   -17.81 | arvid, japE, oopee, Welho, ykis    |
|           10 |      581 | 2024-07-20 | 777          | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.173 (0.025)    | 0 (0.000) |    16.85 | arvid, japE, oopee, Welho, ykis    |
|            9 |      607 | 2024-07-19 | CPH Wolves   | L   | 1.000      | -            | -                | -                | -         |    -7.58 | arvid, japE, oopee, Welho, ykis    |
|            8 |     1014 | 2024-06-24 | lajtbitexe   | L   | 0.913      | -            | -                | -                | -         |   -12.42 | arvid, oopee, Sm1llee, Welho, ykis |
|            7 |     1020 | 2024-06-23 | Revenant     | L   | 0.904      | -            | -                | -                | -         |    -8.64 | arvid, oopee, Sm1llee, Welho, ykis |
|            6 |     1626 | 2024-06-02 | HAVU         | L   | 0.765      | -            | -                | -                | -         |   -11.26 | arvid, japE, oopee, Welho, ykis    |
|            5 |     2208 | 2024-05-14 | NOM          | L   | 0.638      | -            | -                | -                | -         |   -13.85 | arvid, japE, oopee, Welho, ykis    |
|            4 |     2226 | 2024-05-13 | DMS          | L   | 0.632      | -            | -                | -                | -         |    -4.88 | arvid, japE, oopee, Welho, ykis    |
|            3 |     2393 | 2024-05-05 | ENCE Academy | W   | 0.580      | 0.306        | 0.003 (0.001)    | 0.104 (0.019)    | 0 (0.000) |    10.20 | arvid, japE, oopee, Welho, ykis    |
|            2 |     2412 | 2024-05-04 | jefet        | W   | 0.573      | 0.306        | 0.001 (0.000)    | 0.020 (0.004)    | 0 (0.000) |     5.31 | arvid, japE, oopee, Welho, ykis    |
|            1 |     2546 | 2024-04-28 | ENCE Academy | W   | 0.532      | 0.306        | 0.004 (0.001)    | 0.077 (0.013)    | 0 (0.000) |     9.46 | arvid, japE, oopee, Welho, ykis    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,864.25)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
