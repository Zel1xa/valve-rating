### Roster Details<br />
Team Name: CYBERSHOKE<br />
Roster: FenomeN, levantino, lov1kus, notineki, sstiNiX<br />
Global Rank: [78](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
<br />
Final Rank Value:  938.1<br />
<br />
Final Rank Value (938.1) = Starting Rank Value (899.5) + Head To Head Adjustments (38.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.229[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.242<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 899.5
- 400 + ( ( 0.242 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 899.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |       64 | 2024-07-30 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -17.13 | FenomeN, levantino, lov1kus, notineki, sstiNiX |
|           25 |       85 | 2024-07-29 | 1WIN             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 0.630 (0.274)    | 0 (0.000) |    17.28 | FenomeN, levantino, lov1kus, notineki, sstiNiX |
|           24 |       90 | 2024-07-29 | MOUZ NXT         | L   | 1.000      | -            | -                | -                | -         |    -8.62 | FenomeN, levantino, lov1kus, notineki, sstiNiX |
|           23 |      101 | 2024-07-29 | Sampi            | W   | 1.000      | 0.426        | 0.028 (0.012)    | 1.000 (0.426)    | 0 (0.000) |    14.56 | FenomeN, levantino, lov1kus, notineki, sstiNiX |
|           22 |      152 | 2024-07-27 | EYEBALLERS       | W   | 1.000      | 0.435        | 0.006 (0.002)    | 0.513 (0.223)    | 0 (0.000) |    11.25 | FenomeN, levantino, lov1kus, notineki, sstiNiX |
|           21 |      218 | 2024-07-25 | GUN5             | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.516 (0.224)    | 0 (0.000) |    15.02 | FenomeN, levantino, lov1kus, notineki, sstiNiX |
|           20 |      409 | 2024-07-19 | fnatic           | L   | 1.000      | -            | -                | -                | -         |    -1.48 | FenomeN, levantino, lov1kus, notineki, sstiNiX |
|           19 |      483 | 2024-07-18 | EYEBALLERS       | W   | 1.000      | 0.500        | 0.006 (0.003)    | 0.513 (0.257)    | 0 (0.000) |    13.54 | FenomeN, levantino, lov1kus, notineki, sstiNiX |
|           18 |      586 | 2024-07-16 | fnatic           | L   | 1.000      | -            | -                | -                | -         |    -1.21 | FenomeN, levantino, lov1kus, notineki, sstiNiX |
|           17 |      844 | 2024-06-16 | Revenant         | W   | 0.899      | 0.143        | 0.027 (0.003)    | 0.262 (0.034)    | 0 (0.000) |    11.37 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |
|           16 |      967 | 2024-06-13 | ARCRED           | L   | 0.877      | -            | -                | -                | -         |   -12.85 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |
|           15 |      988 | 2024-06-12 | LEON             | W   | 0.872      | -            | -                | -                | 0 (0.000) |     7.03 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |
|           14 |     1012 | 2024-06-11 | Preasy           | W   | 0.864      | 0.143        | 0.012 (0.001)    | 0.222 (0.027)    | 0 (0.000) |     9.90 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |
|           13 |     1030 | 2024-06-10 | Rhyno            | L   | 0.859      | -            | -                | -                | -         |    -8.93 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |
|           12 |     1072 | 2024-06-09 | EYEBALLERS       | W   | 0.852      | 0.500        | 0.006 (0.002)    | 0.513 (0.219)    | 0 (0.000) |    14.87 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |
|           11 |     1164 | 2024-06-08 | Sampi            | W   | 0.844      | 0.500        | 0.028 (0.012)    | 1.000 (0.422)    | 0 (0.000) |    15.06 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |
|           10 |     1221 | 2024-06-07 | Illuminar        | L   | 0.837      | -            | -                | -                | -         |   -14.41 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |
|            9 |     1286 | 2024-06-06 | DMS              | W   | 0.830      | 0.500        | -                | 0.447 (0.186)    | -         |    16.59 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |
|            8 |     1320 | 2024-06-05 | GUN5             | L   | 0.826      | -            | -                | -                | -         |    -8.78 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |
|            7 |     1363 | 2024-06-04 | Zero Tenacity    | L   | 0.819      | -            | -                | -                | -         |    -4.67 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |
|            6 |     1370 | 2024-06-04 | Nemiga           | L   | 0.819      | -            | -                | -                | -         |    -5.21 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |
|            5 |     1397 | 2024-06-03 | Grannys Knockers | L   | 0.812      | -            | -                | -                | -         |   -15.66 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |
|            4 |     1443 | 2024-06-01 | K10              | W   | 0.799      | -            | -                | -                | -         |     6.25 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |
|            3 |     1488 | 2024-05-31 | HOTU             | W   | 0.791      | 0.372        | 0.007 (0.002)    | -                | -         |     5.96 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |
|            2 |     1549 | 2024-05-28 | VP.Prodigy       | L   | 0.773      | -            | -                | -                | -         |   -10.86 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |
|            1 |     2080 | 2024-05-11 | DMS              | L   | 0.658      | -            | -                | -                | -         |   -10.27 | FenomeN, kelieN, lov1kus, notineki, sstiNiX    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,058.82)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.898 | $2,500.00      | $2,244.18       |
| 2024-06-11 |      0.865 | $12,500.00     | $10,814.64      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
