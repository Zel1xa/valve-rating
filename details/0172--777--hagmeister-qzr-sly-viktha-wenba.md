### Roster Details<br />
Team Name: 777<br />
Roster: Hagmeister, qzr, SLY, Viktha, Wenba<br />
Global Rank: [172](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [110]( ../standings_europe.md)<br />
<br />
Final Rank Value:  664.1<br />
<br />
Final Rank Value (664.1) = Starting Rank Value (706.5) + Head To Head Adjustments (-42.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.354[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.150<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 706.5
- 400 + ( ( 0.150 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 706.5


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
|           19 |        2 | 2024-08-05 | TSM           | L   | 1.000      | -            | -                | -                | -         |    -4.79 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           18 |      548 | 2024-07-20 | Heimo         | L   | 1.000      | -            | -                | -                | -         |   -16.90 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           17 |      562 | 2024-07-19 | INFINITE      | L   | 1.000      | -            | -                | -                | -         |   -20.34 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           16 |      939 | 2024-07-06 | Revenant      | L   | 1.000      | -            | -                | -                | -         |   -11.48 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           15 |     1022 | 2024-06-16 | CPH Wolves    | L   | 0.866      | -            | -                | -                | -         |   -10.45 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           14 |     1056 | 2024-06-15 | The Prodigies | W   | 0.860      | 0.143        | 0.000 (0.000)    | 0.093 (0.011)    | 0 (0.000) |     8.16 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           13 |     1159 | 2024-06-12 | ADEPTS        | W   | 0.840      | 0.143        | 0.002 (0.000)    | 0.027 (0.003)    | 0 (0.000) |    10.90 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           12 |     1173 | 2024-06-11 | The Prodigies | L   | 0.834      | -            | -                | -                | -         |   -18.08 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           11 |     1625 | 2024-06-01 | VP.Prodigy    | L   | 0.766      | -            | -                | -                | -         |    -6.54 | Affava, Hagmeister, qzr, Viktha, Wenba       |
|           10 |     1758 | 2024-05-26 | Metizport X   | W   | 0.728      | 0.322        | 0.005 (0.001)    | 0.025 (0.006)    | 0 (0.000) |     9.03 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            9 |     1983 | 2024-05-18 | DMS           | L   | 0.674      | -            | -                | -                | -         |    -5.39 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            8 |     2032 | 2024-05-17 | Space         | W   | 0.666      | 0.143        | 0.006 (0.001)    | 0.445 (0.042)    | 0 (0.000) |    13.74 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            7 |     2062 | 2024-05-16 | Rounds        | W   | 0.660      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.01 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            6 |     2098 | 2024-05-15 | GUN5          | L   | 0.655      | -            | -                | -                | -         |    -4.74 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            5 |     2241 | 2024-05-11 | Metizport X   | W   | 0.627      | 0.322        | 0.005 (0.001)    | 0.025 (0.005)    | 0 (0.000) |     8.18 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            4 |     2522 | 2024-04-27 | Sashi         | L   | 0.535      | -            | -                | -                | -         |    -1.18 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            3 |     2533 | 2024-04-27 | Preasy        | W   | 0.534      | 0.336        | 0.012 (0.002)    | 0.224 (0.040)    | 0 (0.000) |    10.21 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            2 |     2902 | 2024-04-13 | Norway        | L   | 0.441      | -            | -                | -                | -         |    -7.02 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            1 |     3509 | 2024-03-17 | INFURITY      | W   | 0.262      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.25 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,864.69)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.728 | $3,864.00      | $2,811.06       |
| 2024-04-27 |      0.535 | $2,655.00      | $1,420.43       |
| 2024-04-13 |      0.441 | $1,436.00      | $633.20         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
