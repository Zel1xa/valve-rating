### Roster Details<br />
Team Name: Verdant<br />
Roster: arTisT, Diviiii, Extinct, Girafffe, Vacancy<br />
Global Rank: [106](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [78]( ../standings_europe.md)<br />
<br />
Final Rank Value:  844.1<br />
<br />
Final Rank Value (844.1) = Starting Rank Value (942.9) + Head To Head Adjustments (-98.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.353[<sup>1</sup>](#table2)
- Bounty Collected: 0.338[<sup>2</sup>](#table1)
- Opponent Network: 0.101[<sup>2</sup>](#table1)
- LAN Wins: 0.271[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 942.9
- 400 + ( ( 0.266 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 942.9


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
|           34 |      462 | 2024-07-21 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.039 (0.012)    | 1 (1.000) |     9.97 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           33 |      488 | 2024-07-20 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.039 (0.012)    | 1 (1.000) |    10.16 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           32 |      636 | 2024-07-17 | PERA              | L   | 1.000      | -            | -                | -                | -         |    -8.80 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           31 |      803 | 2024-07-12 | Revenant          | L   | 1.000      | -            | -                | -                | -         |   -14.53 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           30 |      884 | 2024-07-08 | Rebels            | L   | 1.000      | -            | -                | -                | -         |    -9.66 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           29 |      979 | 2024-06-16 | UNiTY             | L   | 0.873      | -            | -                | -                | -         |   -10.31 | arTisT, Diviiii, Ducky, Extinct, Vacancy    |
|           28 |      990 | 2024-06-15 | Revenant          | L   | 0.869      | -            | -                | -                | -         |   -16.17 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           27 |     1028 | 2024-06-14 | Aurora Young Blud | L   | 0.862      | -            | -                | -                | -         |   -14.97 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           26 |     1067 | 2024-06-13 | Nemiga            | L   | 0.856      | -            | -                | -                | -         |    -5.56 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           25 |     1075 | 2024-06-13 | Revenant          | W   | 0.855      | 0.143        | 0.027 (0.003)    | 0.267 (0.033)    | 0 (0.000) |     9.80 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           24 |     1098 | 2024-06-12 | DMS               | W   | 0.849      | 0.143        | 0.003 (0.000)    | 0.446 (0.054)    | 0 (0.000) |    14.76 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           23 |     1120 | 2024-06-11 | 9INE              | L   | 0.842      | -            | -                | -                | -         |   -23.57 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           22 |     1314 | 2024-06-07 | B8                | L   | 0.815      | -            | -                | -                | -         |    -5.54 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           21 |     1321 | 2024-06-07 | Aurora            | L   | 0.815      | -            | -                | -                | -         |    -0.84 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           20 |     1331 | 2024-06-07 | B8                | W   | 0.814      | 0.143        | 0.165 (0.019)    | 0.912 (0.106)    | 0 (0.000) |    20.41 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           19 |     1368 | 2024-06-06 | Aurora Young Blud | L   | 0.809      | -            | -                | -                | -         |   -15.08 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           18 |     1426 | 2024-06-05 | Enterprise        | W   | 0.802      | 0.372        | 0.039 (0.012)    | 0.625 (0.187)    | 0 (0.000) |    13.45 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           17 |     1477 | 2024-06-04 | K10               | L   | 0.796      | -            | -                | -                | -         |   -19.22 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           16 |     1507 | 2024-06-03 | LEON              | W   | 0.789      | 0.372        | 0.007 (0.002)    | 0.130 (0.038)    | 0 (0.000) |     5.67 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           15 |     1558 | 2024-06-01 | V1dar             | W   | 0.776      | 0.372        | -                | 0.057 (0.016)    | 0 (0.000) |     2.91 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           14 |     1645 | 2024-05-29 | DMS               | L   | 0.756      | -            | -                | -                | -         |   -11.97 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           13 |     1853 | 2024-05-21 | Zero Tenacity     | L   | 0.700      | -            | -                | -                | -         |    -6.14 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           12 |     1891 | 2024-05-20 | Sampi             | W   | 0.693      | 0.435        | 0.027 (0.008)    | 1.000 (0.301)    | 0 (0.000) |    10.53 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           11 |     1952 | 2024-05-18 | Space             | L   | 0.679      | -            | -                | -                | -         |   -13.18 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           10 |     2065 | 2024-05-15 | Sangal            | W   | 0.660      | 0.435        | 0.219 (0.063)    | 0.862 (0.247)    | -         |    15.16 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            9 |     2119 | 2024-05-14 | B8                | L   | 0.654      | -            | -                | -                | -         |    -5.15 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            8 |     2146 | 2024-05-13 | kONO              | L   | 0.647      | -            | -                | -                | -         |   -12.85 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            7 |     2159 | 2024-05-12 | Johnny Speeds     | L   | 0.642      | -            | -                | -                | -         |    -2.68 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            6 |     2170 | 2024-05-12 | Zero Tenacity     | L   | 0.640      | -            | -                | -                | -         |    -7.10 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            5 |     2190 | 2024-05-11 | V1dar             | W   | 0.635      | -            | -                | -                | -         |     1.90 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            4 |     2218 | 2024-05-10 | ECLOT             | L   | 0.627      | -            | -                | -                | -         |    -4.03 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            3 |     3230 | 2024-04-01 | Reason            | W   | 0.367      | 0.301        | 0.002 (0.000)    | -                | 1 (0.367) |     1.11 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            2 |     3303 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.336      | -            | -                | -                | -         |    -0.16 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            1 |     3428 | 2024-03-19 | The Neighbours    | L   | 0.283      | -            | -                | -                | -         |    -7.14 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,778.28)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $2,259.00      | $2,259.00       |
| 2024-06-10 |      0.836 | $750.00        | $626.77         |
| 2024-05-13 |      0.646 | $1,000.00      | $646.11         |
| 2024-04-01 |      0.367 | $3,153.00      | $1,156.76       |
| 2024-03-19 |      0.283 | $317.00        | $89.64          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
