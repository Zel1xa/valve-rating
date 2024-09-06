### Roster Details<br />
Team Name: 777<br />
Roster: Hagmeister, qzr, SLY, Viktha, Wenba<br />
Global Rank: [183](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [118]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  627.4<br />
<br />
Final Rank Value (627.4) = Starting Rank Value (671.6) + Head To Head Adjustments (-44.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.215[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.139<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 671.6
- 400 + ( ( 0.139 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 671.6


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
|           20 |     1107 | 2024-08-05 | ECSTATIC      | L   | 0.986      | -            | -                | -                | -         |   -12.22 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           19 |     1113 | 2024-08-05 | TSM           | L   | 0.985      | -            | -                | -                | -         |    -3.92 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           18 |     1658 | 2024-07-20 | Heimo         | L   | 0.878      | -            | -                | -                | -         |   -14.78 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           17 |     1672 | 2024-07-19 | INFINITE      | L   | 0.873      | -            | -                | -                | -         |   -17.52 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           16 |     2052 | 2024-07-06 | Revenant      | L   | 0.786      | -            | -                | -                | -         |    -5.67 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           15 |     2135 | 2024-06-16 | CPH Wolves    | L   | 0.652      | -            | -                | -                | -         |    -7.17 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           14 |     2169 | 2024-06-15 | The Prodigies | W   | 0.645      | 0.143        | 0.000 (0.000)    | 0.066 (0.006)    | 0 (0.000) |     6.40 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           13 |     2272 | 2024-06-12 | ADEPTS        | W   | 0.625      | 0.143        | 0.002 (0.000)    | 0.018 (0.002)    | 0 (0.000) |     8.32 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           12 |     2286 | 2024-06-11 | The Prodigies | L   | 0.619      | -            | -                | -                | -         |   -13.32 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           11 |     2738 | 2024-06-01 | VP.Prodigy    | L   | 0.551      | -            | -                | -                | -         |    -4.79 | Affava, Hagmeister, qzr, Viktha, Wenba       |
|           10 |     2871 | 2024-05-26 | Metizport X   | W   | 0.513      | 0.322        | 0.004 (0.001)    | 0.016 (0.003)    | 0 (0.000) |     6.78 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            9 |     3096 | 2024-05-18 | DMS           | L   | 0.459      | -            | -                | -                | -         |    -3.58 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            8 |     3145 | 2024-05-17 | Space         | W   | 0.451      | 0.143        | 0.004 (0.000)    | 0.479 (0.031)    | 0 (0.000) |     9.82 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            7 |     3175 | 2024-05-16 | Rounds        | W   | 0.445      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.43 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            6 |     3211 | 2024-05-15 | GUN5          | L   | 0.440      | -            | -                | -                | -         |    -2.13 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            5 |     3354 | 2024-05-11 | Metizport X   | W   | 0.413      | 0.322        | 0.004 (0.001)    | 0.016 (0.002)    | 0 (0.000) |     5.68 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            4 |     3635 | 2024-04-27 | Sashi         | L   | 0.320      | -            | -                | -                | -         |    -0.87 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            3 |     3646 | 2024-04-27 | Preasy        | W   | 0.319      | 0.336        | 0.007 (0.001)    | 0.169 (0.018)    | 0 (0.000) |     5.80 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            2 |     4015 | 2024-04-13 | Norway        | L   | 0.226      | -            | -                | -                | -         |    -3.75 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            1 |     4622 | 2024-03-17 | INFURITY      | W   | 0.047      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.27 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,156.39)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.513 | $3,864.00      | $1,981.28       |
| 2024-04-27 |      0.320 | $2,655.00      | $850.28         |
| 2024-04-13 |      0.226 | $1,436.00      | $324.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
