### Roster Details<br />
Team Name: 777<br />
Roster: Hagmeister, qzr, SLY, Viktha, Wenba<br />
Global Rank: [173](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [110]( ../standings_europe.md)<br />
<br />
Final Rank Value:  658.4<br />
<br />
Final Rank Value (658.4) = Starting Rank Value (701.0) + Head To Head Adjustments (-42.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.351[<sup>1</sup>](#table2)
- Bounty Collected: 0.227[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.0
- 400 + ( ( 0.147 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 701.0


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
|           17 |      473 | 2024-07-20 | Heimo         | L   | 1.000      | -            | -                | -                | -         |   -16.40 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           16 |      487 | 2024-07-19 | INFINITE      | L   | 1.000      | -            | -                | -                | -         |   -19.91 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           15 |      856 | 2024-07-06 | Revenant      | L   | 1.000      | -            | -                | -                | -         |   -11.43 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           14 |      932 | 2024-06-16 | CPH Wolves    | L   | 0.879      | -            | -                | -                | -         |   -10.19 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           13 |      960 | 2024-06-15 | The Prodigies | W   | 0.872      | 0.143        | 0.000 (0.000)    | 0.097 (0.012)    | 0 (0.000) |     8.66 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           12 |     1054 | 2024-06-12 | ADEPTS        | W   | 0.852      | 0.143        | 0.002 (0.000)    | 0.028 (0.003)    | 0 (0.000) |    11.51 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           11 |     1066 | 2024-06-11 | The Prodigies | L   | 0.846      | -            | -                | -                | -         |   -17.91 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           10 |     1509 | 2024-06-01 | VP.Prodigy    | L   | 0.778      | -            | -                | -                | -         |    -6.27 | Affava, Hagmeister, qzr, Viktha, Wenba       |
|            9 |     1865 | 2024-05-18 | DMS           | L   | 0.686      | -            | -                | -                | -         |    -5.48 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            8 |     1914 | 2024-05-17 | Space         | W   | 0.678      | 0.143        | 0.006 (0.001)    | 0.420 (0.041)    | 0 (0.000) |    14.28 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            7 |     1944 | 2024-05-16 | Rounds        | W   | 0.672      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.13 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            6 |     1980 | 2024-05-15 | GUN5          | L   | 0.667      | -            | -                | -                | -         |    -4.64 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            5 |     2123 | 2024-05-11 | Metizport X   | W   | 0.640      | 0.322        | 0.005 (0.001)    | 0.026 (0.005)    | 0 (0.000) |     8.37 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            4 |     2403 | 2024-04-27 | Sashi         | L   | 0.547      | -            | -                | -                | -         |    -1.14 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            3 |     2414 | 2024-04-27 | Preasy        | W   | 0.546      | 0.336        | 0.012 (0.002)    | 0.231 (0.042)    | 0 (0.000) |    10.58 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            2 |     2782 | 2024-04-13 | Norway        | L   | 0.453      | -            | -                | -                | -         |    -7.09 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            1 |     3384 | 2024-03-17 | INFURITY      | W   | 0.274      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.35 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,597.35)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      0.645 | $3,864.00      | $2,493.53       |
| 2024-04-27 |      0.547 | $2,655.00      | $1,453.00       |
| 2024-04-13 |      0.453 | $1,436.00      | $650.82         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
