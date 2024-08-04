### Roster Details<br />
Team Name: 777<br />
Roster: Hagmeister, qzr, SLY, Viktha, Wenba<br />
Global Rank: [168](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [107]( ../standings_europe.md)<br />
<br />
Final Rank Value:  668.6<br />
<br />
Final Rank Value (668.6) = Starting Rank Value (706.2) + Head To Head Adjustments (-37.6)<br />

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
- 400 + ( ( 0.150 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 706.2


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
|           18 |      499 | 2024-07-20 | Heimo         | L   | 1.000      | -            | -                | -                | -         |   -16.91 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           17 |      513 | 2024-07-19 | INFINITE      | L   | 1.000      | -            | -                | -                | -         |   -20.34 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           16 |      890 | 2024-07-06 | Revenant      | L   | 1.000      | -            | -                | -                | -         |   -11.55 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           15 |      973 | 2024-06-16 | CPH Wolves    | L   | 0.874      | -            | -                | -                | -         |   -10.59 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           14 |     1007 | 2024-06-15 | The Prodigies | W   | 0.867      | 0.143        | 0.000 (0.000)    | 0.094 (0.012)    | 0 (0.000) |     8.24 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           13 |     1110 | 2024-06-12 | ADEPTS        | W   | 0.847      | 0.143        | 0.002 (0.000)    | 0.027 (0.003)    | 0 (0.000) |    10.99 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           12 |     1124 | 2024-06-11 | The Prodigies | L   | 0.841      | -            | -                | -                | -         |   -18.22 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           11 |     1576 | 2024-06-01 | VP.Prodigy    | L   | 0.774      | -            | -                | -                | -         |    -6.63 | Affava, Hagmeister, qzr, Viktha, Wenba       |
|           10 |     1709 | 2024-05-26 | Metizport X   | W   | 0.735      | 0.322        | 0.005 (0.001)    | 0.025 (0.006)    | 0 (0.000) |     9.12 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            9 |     1934 | 2024-05-18 | DMS           | L   | 0.681      | -            | -                | -                | -         |    -5.54 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            8 |     1983 | 2024-05-17 | Space         | W   | 0.673      | 0.143        | 0.006 (0.001)    | 0.406 (0.039)    | 0 (0.000) |    13.96 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            7 |     2013 | 2024-05-16 | Rounds        | W   | 0.667      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.04 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            6 |     2049 | 2024-05-15 | GUN5          | L   | 0.662      | -            | -                | -                | -         |    -4.79 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            5 |     2192 | 2024-05-11 | Metizport X   | W   | 0.635      | 0.322        | 0.005 (0.001)    | 0.025 (0.005)    | 0 (0.000) |     8.28 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            4 |     2473 | 2024-04-27 | Sashi         | L   | 0.542      | -            | -                | -                | -         |    -1.21 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            3 |     2484 | 2024-04-27 | Preasy        | W   | 0.541      | 0.336        | 0.012 (0.002)    | 0.224 (0.041)    | 0 (0.000) |    10.34 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            2 |     2853 | 2024-04-13 | Norway        | L   | 0.448      | -            | -                | -                | -         |    -7.13 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            1 |     3460 | 2024-03-17 | INFURITY      | W   | 0.269      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.29 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,924.35)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.735 | $3,864.00      | $2,840.04       |
| 2024-04-27 |      0.542 | $2,655.00      | $1,440.34       |
| 2024-04-13 |      0.448 | $1,436.00      | $643.97         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
