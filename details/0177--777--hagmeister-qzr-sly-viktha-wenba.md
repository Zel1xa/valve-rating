### Roster Details<br />
Team Name: 777<br />
Roster: Hagmeister, qzr, SLY, Viktha, Wenba<br />
Global Rank: [177](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [112]( ../standings_europe.md)<br />
<br />
Final Rank Value:  643.4<br />
<br />
Final Rank Value (643.4) = Starting Rank Value (705.2) + Head To Head Adjustments (-61.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.354[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.2
- 400 + ( ( 0.149 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 705.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |        8 | 2024-08-05 | ECSTATIC      | L   | 1.000      | -            | -                | -                | -         |   -19.93 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           19 |       13 | 2024-08-05 | TSM           | L   | 1.000      | -            | -                | -                | -         |    -4.74 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           18 |      559 | 2024-07-20 | Heimo         | L   | 1.000      | -            | -                | -                | -         |   -16.85 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           17 |      573 | 2024-07-19 | INFINITE      | L   | 1.000      | -            | -                | -                | -         |   -20.29 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           16 |      950 | 2024-07-06 | Revenant      | L   | 0.997      | -            | -                | -                | -         |   -11.36 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           15 |     1033 | 2024-06-16 | CPH Wolves    | L   | 0.863      | -            | -                | -                | -         |   -10.37 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           14 |     1067 | 2024-06-15 | The Prodigies | W   | 0.856      | 0.143        | 0.000 (0.000)    | 0.092 (0.011)    | 0 (0.000) |     8.16 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           13 |     1170 | 2024-06-12 | ADEPTS        | W   | 0.836      | 0.143        | 0.002 (0.000)    | 0.026 (0.003)    | 0 (0.000) |    10.91 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           12 |     1184 | 2024-06-11 | The Prodigies | L   | 0.831      | -            | -                | -                | -         |   -17.98 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           11 |     1636 | 2024-06-01 | VP.Prodigy    | L   | 0.763      | -            | -                | -                | -         |    -6.46 | Affava, Hagmeister, qzr, Viktha, Wenba       |
|           10 |     1769 | 2024-05-26 | Metizport X   | W   | 0.724      | 0.322        | 0.005 (0.001)    | 0.025 (0.006)    | 0 (0.000) |     9.04 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            9 |     1994 | 2024-05-18 | DMS           | L   | 0.671      | -            | -                | -                | -         |    -5.34 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            8 |     2043 | 2024-05-17 | Space         | W   | 0.662      | 0.143        | 0.006 (0.001)    | 0.439 (0.042)    | 0 (0.000) |    13.70 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            7 |     2073 | 2024-05-16 | Rounds        | W   | 0.656      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.01 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            6 |     2109 | 2024-05-15 | GUN5          | L   | 0.651      | -            | -                | -                | -         |    -4.67 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            5 |     2252 | 2024-05-11 | Metizport X   | W   | 0.624      | 0.322        | 0.005 (0.001)    | 0.025 (0.005)    | 0 (0.000) |     8.19 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            4 |     2533 | 2024-04-27 | Sashi         | L   | 0.532      | -            | -                | -                | -         |    -1.16 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            3 |     2544 | 2024-04-27 | Preasy        | W   | 0.530      | 0.336        | 0.008 (0.001)    | 0.221 (0.039)    | 0 (0.000) |    10.00 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            2 |     2913 | 2024-04-13 | Norway        | L   | 0.438      | -            | -                | -                | -         |    -6.94 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            1 |     3520 | 2024-03-17 | INFURITY      | W   | 0.258      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.25 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,838.17)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.724 | $3,864.00      | $2,798.18       |
| 2024-04-27 |      0.532 | $2,655.00      | $1,411.57       |
| 2024-04-13 |      0.438 | $1,436.00      | $628.42         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
