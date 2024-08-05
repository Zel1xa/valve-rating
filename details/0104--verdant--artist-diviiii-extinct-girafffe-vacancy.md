### Roster Details<br />
Team Name: Verdant<br />
Roster: arTisT, Diviiii, Extinct, Girafffe, Vacancy<br />
Global Rank: [104](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  848.3<br />
<br />
Final Rank Value (848.3) = Starting Rank Value (943.8) + Head To Head Adjustments (-95.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.353[<sup>1</sup>](#table2)
- Bounty Collected: 0.337[<sup>2</sup>](#table1)
- Opponent Network: 0.099[<sup>2</sup>](#table1)
- LAN Wins: 0.271[<sup>2</sup>](#table1)

The average of these factors is 0.265<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 943.8
- 400 + ( ( 0.265 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 943.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |      519 | 2024-07-21 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.039 (0.012)    | 1 (1.000) |     9.86 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           33 |      545 | 2024-07-20 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.039 (0.012)    | 1 (1.000) |    10.05 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           32 |      693 | 2024-07-17 | PERA              | L   | 1.000      | -            | -                | -                | -         |    -8.98 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           31 |      860 | 2024-07-12 | Revenant          | L   | 1.000      | -            | -                | -                | -         |   -14.62 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           30 |      941 | 2024-07-08 | Rebels            | L   | 1.000      | -            | -                | -                | -         |    -9.82 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           29 |     1036 | 2024-06-16 | UNiTY             | L   | 0.864      | -            | -                | -                | -         |   -10.15 | arTisT, Diviiii, Ducky, Extinct, Vacancy    |
|           28 |     1047 | 2024-06-15 | Revenant          | L   | 0.860      | -            | -                | -                | -         |   -16.08 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           27 |     1085 | 2024-06-14 | Aurora Young Blud | L   | 0.854      | -            | -                | -                | -         |   -13.61 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           26 |     1124 | 2024-06-13 | Nemiga            | L   | 0.847      | -            | -                | -                | -         |    -5.25 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           25 |     1132 | 2024-06-13 | Revenant          | W   | 0.846      | 0.143        | 0.027 (0.003)    | 0.264 (0.032)    | 0 (0.000) |     9.71 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           24 |     1155 | 2024-06-12 | DMS               | W   | 0.840      | 0.143        | 0.003 (0.000)    | 0.438 (0.053)    | 0 (0.000) |    14.66 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           23 |     1177 | 2024-06-11 | 9INE              | L   | 0.833      | -            | -                | -                | -         |   -23.37 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           22 |     1371 | 2024-06-07 | B8                | L   | 0.807      | -            | -                | -                | -         |    -5.50 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           21 |     1378 | 2024-06-07 | Aurora            | L   | 0.806      | -            | -                | -                | -         |    -0.80 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           20 |     1388 | 2024-06-07 | B8                | W   | 0.805      | 0.143        | 0.165 (0.019)    | 0.935 (0.108)    | 0 (0.000) |    20.17 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           19 |     1425 | 2024-06-06 | Aurora Young Blud | L   | 0.800      | -            | -                | -                | -         |   -13.53 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           18 |     1483 | 2024-06-05 | Enterprise        | W   | 0.794      | 0.372        | 0.039 (0.012)    | 0.616 (0.182)    | 0 (0.000) |    13.38 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           17 |     1534 | 2024-06-04 | K10               | L   | 0.787      | -            | -                | -                | -         |   -19.04 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           16 |     1564 | 2024-06-03 | LEON              | W   | 0.780      | 0.372        | 0.007 (0.002)    | 0.127 (0.037)    | 0 (0.000) |     5.62 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           15 |     1615 | 2024-06-01 | V1dar             | W   | 0.767      | 0.372        | -                | 0.055 (0.016)    | 0 (0.000) |     2.85 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           14 |     1702 | 2024-05-29 | DMS               | L   | 0.747      | -            | -                | -                | -         |   -11.78 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           13 |     1910 | 2024-05-21 | Zero Tenacity     | L   | 0.691      | -            | -                | -                | -         |    -6.13 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           12 |     1948 | 2024-05-20 | Sampi             | W   | 0.685      | 0.435        | 0.027 (0.008)    | 1.000 (0.298)    | 0 (0.000) |    10.37 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           11 |     2009 | 2024-05-18 | Space             | L   | 0.671      | -            | -                | -                | -         |   -13.15 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           10 |     2122 | 2024-05-15 | Sangal            | W   | 0.652      | 0.435        | 0.219 (0.062)    | 0.866 (0.245)    | -         |    15.07 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            9 |     2176 | 2024-05-14 | B8                | L   | 0.646      | -            | -                | -                | -         |    -5.09 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            8 |     2203 | 2024-05-13 | kONO              | L   | 0.638      | -            | -                | -                | -         |   -12.73 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            7 |     2216 | 2024-05-12 | Johnny Speeds     | L   | 0.634      | -            | -                | -                | -         |    -2.54 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            6 |     2227 | 2024-05-12 | Zero Tenacity     | L   | 0.632      | -            | -                | -                | -         |    -6.90 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            5 |     2247 | 2024-05-11 | V1dar             | W   | 0.627      | -            | -                | -                | -         |     1.86 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            4 |     2275 | 2024-05-10 | ECLOT             | L   | 0.618      | -            | -                | -                | -         |    -3.92 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            3 |     3287 | 2024-04-01 | Reason            | W   | 0.358      | 0.301        | 0.002 (0.000)    | -                | 1 (0.358) |     1.08 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            2 |     3360 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.327      | -            | -                | -                | -         |    -0.15 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            1 |     3485 | 2024-03-19 | The Neighbours    | L   | 0.274      | -            | -                | -                | -         |    -6.95 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,733.33)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $2,259.00      | $2,259.00       |
| 2024-06-10 |      0.827 | $750.00        | $620.31         |
| 2024-05-13 |      0.637 | $1,000.00      | $637.50         |
| 2024-04-01 |      0.358 | $3,153.00      | $1,129.61       |
| 2024-03-19 |      0.274 | $317.00        | $86.91          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
