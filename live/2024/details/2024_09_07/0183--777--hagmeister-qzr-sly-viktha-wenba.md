### Roster Details<br />
Team Name: 777<br />
Roster: Hagmeister, qzr, SLY, Viktha, Wenba<br />
Global Rank: [183](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [118]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  627.4<br />
<br />
Final Rank Value (627.4) = Starting Rank Value (671.5) + Head To Head Adjustments (-44.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.215[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.139<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 671.5
- 400 + ( ( 0.139 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 671.5


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
|           20 |     1112 | 2024-08-05 | ECSTATIC      | L   | 0.982      | -            | -                | -                | -         |   -12.16 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           19 |     1118 | 2024-08-05 | TSM           | L   | 0.981      | -            | -                | -                | -         |    -3.89 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           18 |     1663 | 2024-07-20 | Heimo         | L   | 0.874      | -            | -                | -                | -         |   -14.71 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           17 |     1677 | 2024-07-19 | INFINITE      | L   | 0.869      | -            | -                | -                | -         |   -17.45 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           16 |     2057 | 2024-07-06 | Revenant      | L   | 0.782      | -            | -                | -                | -         |    -5.62 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           15 |     2140 | 2024-06-16 | CPH Wolves    | L   | 0.648      | -            | -                | -                | -         |    -7.11 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           14 |     2174 | 2024-06-15 | The Prodigies | W   | 0.641      | 0.143        | 0.000 (0.000)    | 0.066 (0.006)    | 0 (0.000) |     6.36 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           13 |     2277 | 2024-06-12 | ADEPTS        | W   | 0.621      | 0.143        | 0.002 (0.000)    | 0.018 (0.002)    | 0 (0.000) |     8.27 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           12 |     2291 | 2024-06-11 | The Prodigies | L   | 0.615      | -            | -                | -                | -         |   -13.23 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           11 |     2743 | 2024-06-01 | VP.Prodigy    | L   | 0.547      | -            | -                | -                | -         |    -4.77 | Affava, Hagmeister, qzr, Viktha, Wenba       |
|           10 |     2876 | 2024-05-26 | Metizport X   | W   | 0.509      | 0.322        | 0.004 (0.001)    | 0.016 (0.003)    | 0 (0.000) |     6.73 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            9 |     3101 | 2024-05-18 | DMS           | L   | 0.455      | -            | -                | -                | -         |    -3.56 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            8 |     3150 | 2024-05-17 | Space         | W   | 0.447      | 0.143        | 0.004 (0.000)    | 0.479 (0.031)    | 0 (0.000) |     9.73 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            7 |     3180 | 2024-05-16 | Rounds        | W   | 0.441      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.41 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            6 |     3216 | 2024-05-15 | GUN5          | L   | 0.436      | -            | -                | -                | -         |    -2.11 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            5 |     3359 | 2024-05-11 | Metizport X   | W   | 0.409      | 0.322        | 0.004 (0.001)    | 0.016 (0.002)    | 0 (0.000) |     5.63 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            4 |     3640 | 2024-04-27 | Sashi         | L   | 0.316      | -            | -                | -                | -         |    -0.86 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            3 |     3651 | 2024-04-27 | Preasy        | W   | 0.315      | 0.336        | 0.007 (0.001)    | 0.168 (0.018)    | 0 (0.000) |     5.72 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            2 |     4020 | 2024-04-13 | Norway        | L   | 0.222      | -            | -                | -                | -         |    -3.68 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            1 |     4627 | 2024-03-17 | INFURITY      | W   | 0.043      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.24 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,124.53)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.509 | $3,864.00      | $1,965.81       |
| 2024-04-27 |      0.316 | $2,655.00      | $839.64         |
| 2024-04-13 |      0.222 | $1,436.00      | $319.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
