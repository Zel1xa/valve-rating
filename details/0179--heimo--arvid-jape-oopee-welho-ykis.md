### Roster Details<br />
Team Name: Heimo<br />
Roster: arvid, japE, oopee, Welho, ykis<br />
Global Rank: [179](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [114]( ../standings_europe.md)<br />
<br />
Final Rank Value:  642.2<br />
<br />
Final Rank Value (642.2) = Starting Rank Value (678.4) + Head To Head Adjustments (-36.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.310[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.136<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 678.4
- 400 + ( ( 0.136 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 678.4


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
|           11 |      434 | 2024-07-21 | INFINITE     | L   | 1.000      | -            | -                | -                | -         |   -17.94 | arvid, japE, oopee, Welho, ykis    |
|           10 |      473 | 2024-07-20 | 777          | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.184 (0.026)    | 0 (0.000) |    16.40 | arvid, japE, oopee, Welho, ykis    |
|            9 |      499 | 2024-07-19 | CPH Wolves   | L   | 1.000      | -            | -                | -                | -         |    -7.64 | arvid, japE, oopee, Welho, ykis    |
|            8 |      896 | 2024-06-24 | lajtbitexe   | L   | 0.933      | -            | -                | -                | -         |   -12.75 | arvid, oopee, Sm1llee, Welho, ykis |
|            7 |      901 | 2024-06-23 | Revenant     | L   | 0.924      | -            | -                | -                | -         |    -9.02 | arvid, oopee, Sm1llee, Welho, ykis |
|            6 |     1478 | 2024-06-02 | HAVU         | L   | 0.785      | -            | -                | -                | -         |   -11.55 | arvid, japE, oopee, Welho, ykis    |
|            5 |     2057 | 2024-05-14 | NOM          | L   | 0.658      | -            | -                | -                | -         |   -14.39 | arvid, japE, oopee, Welho, ykis    |
|            4 |     2075 | 2024-05-13 | DMS          | L   | 0.652      | -            | -                | -                | -         |    -5.09 | arvid, japE, oopee, Welho, ykis    |
|            3 |     2241 | 2024-05-05 | ENCE Academy | W   | 0.600      | 0.306        | 0.004 (0.001)    | 0.158 (0.029)    | 0 (0.000) |    10.22 | arvid, japE, oopee, Welho, ykis    |
|            2 |     2260 | 2024-05-04 | jefet        | W   | 0.593      | 0.306        | 0.001 (0.000)    | 0.022 (0.004)    | 0 (0.000) |     5.45 | arvid, japE, oopee, Welho, ykis    |
|            1 |     2394 | 2024-04-28 | ENCE Academy | W   | 0.552      | 0.306        | 0.004 (0.001)    | 0.158 (0.027)    | 0 (0.000) |    10.06 | arvid, japE, oopee, Welho, ykis    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,928.26)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
