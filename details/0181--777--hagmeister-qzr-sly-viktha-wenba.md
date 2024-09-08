### Roster Details<br />
Team Name: 777<br />
Roster: Hagmeister, qzr, SLY, Viktha, Wenba<br />
Global Rank: [181](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [117]( ../standings_europe.md)<br />
<br />
Final Rank Value:  624.2<br />
<br />
Final Rank Value (624.2) = Starting Rank Value (668.2) + Head To Head Adjustments (-44.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.215[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.138<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 668.2
- 400 + ( ( 0.138 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 668.2


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
|           20 |     1144 | 2024-08-05 | ECSTATIC      | L   | 0.974      | -            | -                | -                | -         |   -12.07 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           19 |     1150 | 2024-08-05 | TSM           | L   | 0.973      | -            | -                | -                | -         |    -3.92 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           18 |     1695 | 2024-07-20 | Heimo         | L   | 0.867      | -            | -                | -                | -         |   -14.57 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           17 |     1709 | 2024-07-19 | INFINITE      | L   | 0.862      | -            | -                | -                | -         |   -17.26 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           16 |     2089 | 2024-07-06 | Revenant      | L   | 0.774      | -            | -                | -                | -         |    -5.65 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           15 |     2172 | 2024-06-16 | CPH Wolves    | L   | 0.640      | -            | -                | -                | -         |    -7.01 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           14 |     2206 | 2024-06-15 | The Prodigies | W   | 0.633      | 0.143        | 0.000 (0.000)    | 0.063 (0.006)    | 0 (0.000) |     6.31 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           13 |     2309 | 2024-06-12 | ADEPTS        | W   | 0.613      | 0.143        | 0.002 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     8.19 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           12 |     2323 | 2024-06-11 | The Prodigies | L   | 0.607      | -            | -                | -                | -         |   -13.04 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           11 |     2775 | 2024-06-01 | VP.Prodigy    | L   | 0.539      | -            | -                | -                | -         |    -4.73 | Affava, Hagmeister, qzr, Viktha, Wenba       |
|           10 |     2908 | 2024-05-26 | Metizport X   | W   | 0.501      | 0.322        | 0.004 (0.001)    | 0.015 (0.002)    | 0 (0.000) |     6.66 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            9 |     3133 | 2024-05-18 | DMS           | L   | 0.447      | -            | -                | -                | -         |    -3.55 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            8 |     3182 | 2024-05-17 | Space         | W   | 0.439      | 0.143        | 0.004 (0.000)    | 0.463 (0.029)    | 0 (0.000) |     9.51 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            7 |     3212 | 2024-05-16 | Rounds        | W   | 0.433      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.41 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            6 |     3248 | 2024-05-15 | GUN5          | L   | 0.428      | -            | -                | -                | -         |    -2.12 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            5 |     3391 | 2024-05-11 | Metizport X   | W   | 0.401      | 0.322        | 0.004 (0.000)    | 0.015 (0.002)    | 0 (0.000) |     5.54 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            4 |     3672 | 2024-04-27 | Sashi         | L   | 0.308      | -            | -                | -                | -         |    -0.87 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            3 |     3683 | 2024-04-27 | Preasy        | W   | 0.307      | 0.336        | 0.007 (0.001)    | 0.162 (0.017)    | 0 (0.000) |     5.56 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            2 |     4052 | 2024-04-13 | Norway        | L   | 0.214      | -            | -                | -                | -         |    -3.56 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            1 |     4659 | 2024-03-17 | INFURITY      | W   | 0.035      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.20 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,061.55)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.501 | $3,864.00      | $1,935.22       |
| 2024-04-27 |      0.308 | $2,655.00      | $818.63         |
| 2024-04-13 |      0.214 | $1,436.00      | $307.71         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
