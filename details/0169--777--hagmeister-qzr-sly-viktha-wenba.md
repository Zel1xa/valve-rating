### Roster Details<br />
Team Name: 777<br />
Roster: Hagmeister, qzr, SLY, Viktha, Wenba<br />
Global Rank: [169](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [108]( ../standings_europe.md)<br />
<br />
Final Rank Value:  668.7<br />
<br />
Final Rank Value (668.7) = Starting Rank Value (706.2) + Head To Head Adjustments (-37.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.355[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.150<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 706.2
- 400 + ( ( 0.150 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 706.2


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
|           18 |      531 | 2024-07-20 | Heimo         | L   | 1.000      | -            | -                | -                | -         |   -16.91 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           17 |      545 | 2024-07-19 | INFINITE      | L   | 1.000      | -            | -                | -                | -         |   -20.34 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           16 |      922 | 2024-07-06 | Revenant      | L   | 1.000      | -            | -                | -                | -         |   -11.51 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           15 |     1005 | 2024-06-16 | CPH Wolves    | L   | 0.872      | -            | -                | -                | -         |   -10.55 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           14 |     1039 | 2024-06-15 | The Prodigies | W   | 0.865      | 0.143        | 0.000 (0.000)    | 0.094 (0.012)    | 0 (0.000) |     8.22 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           13 |     1142 | 2024-06-12 | ADEPTS        | W   | 0.845      | 0.143        | 0.002 (0.000)    | 0.027 (0.003)    | 0 (0.000) |    10.97 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           12 |     1156 | 2024-06-11 | The Prodigies | L   | 0.840      | -            | -                | -                | -         |   -18.19 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           11 |     1608 | 2024-06-01 | VP.Prodigy    | L   | 0.772      | -            | -                | -                | -         |    -6.57 | Affava, Hagmeister, qzr, Viktha, Wenba       |
|           10 |     1741 | 2024-05-26 | Metizport X   | W   | 0.733      | 0.322        | 0.005 (0.001)    | 0.025 (0.006)    | 0 (0.000) |     9.10 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            9 |     1966 | 2024-05-18 | DMS           | L   | 0.680      | -            | -                | -                | -         |    -5.51 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            8 |     2015 | 2024-05-17 | Space         | W   | 0.671      | 0.143        | 0.006 (0.001)    | 0.406 (0.039)    | 0 (0.000) |    13.87 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            7 |     2045 | 2024-05-16 | Rounds        | W   | 0.666      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.04 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            6 |     2081 | 2024-05-15 | GUN5          | L   | 0.660      | -            | -                | -                | -         |    -4.76 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            5 |     2224 | 2024-05-11 | Metizport X   | W   | 0.633      | 0.322        | 0.005 (0.001)    | 0.025 (0.005)    | 0 (0.000) |     8.25 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            4 |     2505 | 2024-04-27 | Sashi         | L   | 0.541      | -            | -                | -                | -         |    -1.19 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            3 |     2516 | 2024-04-27 | Preasy        | W   | 0.539      | 0.336        | 0.012 (0.002)    | 0.224 (0.041)    | 0 (0.000) |    10.31 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            2 |     2885 | 2024-04-13 | Norway        | L   | 0.447      | -            | -                | -                | -         |    -7.10 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            1 |     3492 | 2024-03-17 | INFURITY      | W   | 0.267      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.28 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,910.17)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.733 | $3,864.00      | $2,833.15       |
| 2024-04-27 |      0.541 | $2,655.00      | $1,435.61       |
| 2024-04-13 |      0.447 | $1,436.00      | $641.41         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />