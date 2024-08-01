### Roster Details<br />
Team Name: 777<br />
Roster: Hagmeister, qzr, SLY, Viktha, Wenba<br />
Global Rank: [168](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [107]( ../standings_europe.md)<br />
<br />
Final Rank Value:  672.2<br />
<br />
Final Rank Value (672.2) = Starting Rank Value (709.4) + Head To Head Adjustments (-37.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.356[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.150<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 709.4
- 400 + ( ( 0.150 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 709.4


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
|           18 |      420 | 2024-07-20 | Heimo         | L   | 1.000      | -            | -                | -                | -         |   -16.89 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           17 |      435 | 2024-07-19 | INFINITE      | L   | 1.000      | -            | -                | -                | -         |   -20.43 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           16 |      826 | 2024-07-06 | Revenant      | L   | 1.000      | -            | -                | -                | -         |   -11.60 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           15 |      906 | 2024-06-16 | CPH Wolves    | L   | 0.892      | -            | -                | -                | -         |   -10.81 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           14 |      937 | 2024-06-15 | The Prodigies | W   | 0.885      | 0.143        | 0.000 (0.000)    | 0.094 (0.012)    | 0 (0.000) |     8.41 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           13 |     1034 | 2024-06-12 | ADEPTS        | W   | 0.865      | 0.143        | 0.002 (0.000)    | 0.027 (0.003)    | 0 (0.000) |    11.20 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           12 |     1049 | 2024-06-11 | The Prodigies | L   | 0.859      | -            | -                | -                | -         |   -18.58 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           11 |     1517 | 2024-06-01 | VP.Prodigy    | L   | 0.791      | -            | -                | -                | -         |    -6.75 | Affava, Hagmeister, qzr, Viktha, Wenba       |
|           10 |     1652 | 2024-05-26 | Metizport X   | W   | 0.753      | 0.322        | 0.005 (0.001)    | 0.025 (0.006)    | 0 (0.000) |     9.28 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            9 |     1902 | 2024-05-18 | DMS           | L   | 0.699      | -            | -                | -                | -         |    -5.72 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            8 |     1952 | 2024-05-17 | Space         | W   | 0.691      | 0.143        | 0.006 (0.001)    | 0.406 (0.040)    | 0 (0.000) |    14.34 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            7 |     1982 | 2024-05-16 | Rounds        | W   | 0.685      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.07 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            6 |     2018 | 2024-05-15 | GUN5          | L   | 0.680      | -            | -                | -                | -         |    -4.67 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            5 |     2170 | 2024-05-11 | Metizport X   | W   | 0.653      | 0.322        | 0.005 (0.001)    | 0.025 (0.005)    | 0 (0.000) |     8.47 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            4 |     2456 | 2024-04-27 | Sashi         | L   | 0.560      | -            | -                | -                | -         |    -1.22 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            3 |     2467 | 2024-04-27 | Preasy        | W   | 0.559      | 0.336        | 0.012 (0.002)    | 0.222 (0.042)    | 0 (0.000) |    10.69 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            2 |     2846 | 2024-04-13 | Norway        | L   | 0.466      | -            | -                | -                | -         |    -7.38 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            1 |     3467 | 2024-03-17 | INFURITY      | W   | 0.287      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.35 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,065.77)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.753 | $3,864.00      | $2,908.73       |
| 2024-04-27 |      0.560 | $2,655.00      | $1,487.54       |
| 2024-04-13 |      0.466 | $1,436.00      | $669.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
