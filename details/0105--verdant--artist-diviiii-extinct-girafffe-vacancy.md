### Roster Details<br />
Team Name: Verdant<br />
Roster: arTisT, Diviiii, Extinct, Girafffe, Vacancy<br />
Global Rank: [105](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
<br />
Final Rank Value:  848.9<br />
<br />
Final Rank Value (848.9) = Starting Rank Value (943.9) + Head To Head Adjustments (-95.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.353[<sup>1</sup>](#table2)
- Bounty Collected: 0.337[<sup>2</sup>](#table1)
- Opponent Network: 0.099[<sup>2</sup>](#table1)
- LAN Wins: 0.272[<sup>2</sup>](#table1)

The average of these factors is 0.265<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 943.9
- 400 + ( ( 0.265 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 943.9


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
|           34 |      526 | 2024-07-21 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.039 (0.012)    | 1 (1.000) |     9.87 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           33 |      552 | 2024-07-20 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.039 (0.012)    | 1 (1.000) |    10.05 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           32 |      700 | 2024-07-17 | PERA              | L   | 1.000      | -            | -                | -                | -         |    -9.01 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           31 |      867 | 2024-07-12 | Revenant          | L   | 1.000      | -            | -                | -                | -         |   -14.63 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           30 |      948 | 2024-07-08 | Rebels            | L   | 1.000      | -            | -                | -                | -         |    -9.81 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           29 |     1043 | 2024-06-16 | UNiTY             | L   | 0.859      | -            | -                | -                | -         |   -10.13 | arTisT, Diviiii, Ducky, Extinct, Vacancy    |
|           28 |     1054 | 2024-06-15 | Revenant          | L   | 0.856      | -            | -                | -                | -         |   -16.00 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           27 |     1092 | 2024-06-14 | Aurora Young Blud | L   | 0.849      | -            | -                | -                | -         |   -13.55 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           26 |     1131 | 2024-06-13 | Nemiga            | L   | 0.842      | -            | -                | -                | -         |    -5.25 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           25 |     1139 | 2024-06-13 | Revenant          | W   | 0.841      | 0.143        | 0.027 (0.003)    | 0.265 (0.032)    | 0 (0.000) |     9.65 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           24 |     1162 | 2024-06-12 | DMS               | W   | 0.835      | 0.143        | 0.003 (0.000)    | 0.437 (0.052)    | 0 (0.000) |    14.56 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           23 |     1184 | 2024-06-11 | 9INE              | L   | 0.829      | -            | -                | -                | -         |   -23.24 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           22 |     1378 | 2024-06-07 | B8                | L   | 0.802      | -            | -                | -                | -         |    -5.49 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           21 |     1385 | 2024-06-07 | Aurora            | L   | 0.801      | -            | -                | -                | -         |    -0.79 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           20 |     1395 | 2024-06-07 | B8                | W   | 0.801      | 0.143        | 0.164 (0.019)    | 0.933 (0.107)    | 0 (0.000) |    20.03 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           19 |     1432 | 2024-06-06 | Aurora Young Blud | L   | 0.795      | -            | -                | -                | -         |   -13.47 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           18 |     1490 | 2024-06-05 | Enterprise        | W   | 0.789      | 0.372        | 0.039 (0.012)    | 0.616 (0.181)    | 0 (0.000) |    13.34 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           17 |     1541 | 2024-06-04 | K10               | L   | 0.782      | -            | -                | -                | -         |   -18.94 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           16 |     1571 | 2024-06-03 | LEON              | W   | 0.776      | 0.372        | 0.007 (0.002)    | 0.127 (0.037)    | 0 (0.000) |     5.58 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           15 |     1622 | 2024-06-01 | V1dar             | W   | 0.762      | 0.372        | -                | 0.055 (0.016)    | 0 (0.000) |     2.82 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           14 |     1709 | 2024-05-29 | DMS               | L   | 0.742      | -            | -                | -                | -         |   -11.72 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           13 |     1917 | 2024-05-21 | Zero Tenacity     | L   | 0.687      | -            | -                | -                | -         |    -6.10 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           12 |     1955 | 2024-05-20 | Sampi             | W   | 0.680      | 0.435        | 0.027 (0.008)    | 1.000 (0.296)    | 0 (0.000) |    10.32 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           11 |     2016 | 2024-05-18 | Space             | L   | 0.666      | -            | -                | -                | -         |   -13.04 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           10 |     2129 | 2024-05-15 | Sangal            | W   | 0.647      | 0.435        | 0.219 (0.062)    | 0.865 (0.243)    | -         |    14.98 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            9 |     2183 | 2024-05-14 | B8                | L   | 0.641      | -            | -                | -                | -         |    -5.07 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            8 |     2210 | 2024-05-13 | kONO              | L   | 0.633      | -            | -                | -                | -         |   -12.56 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            7 |     2223 | 2024-05-12 | Johnny Speeds     | L   | 0.629      | -            | -                | -                | -         |    -2.52 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            6 |     2234 | 2024-05-12 | Zero Tenacity     | L   | 0.627      | -            | -                | -                | -         |    -6.85 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            5 |     2254 | 2024-05-11 | V1dar             | W   | 0.622      | -            | -                | -                | -         |     1.84 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            4 |     2282 | 2024-05-10 | ECLOT             | L   | 0.614      | -            | -                | -                | -         |    -3.89 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            3 |     3294 | 2024-04-01 | Reason            | W   | 0.354      | 0.301        | 0.002 (0.000)    | -                | 1 (0.354) |     1.07 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            2 |     3367 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.322      | -            | -                | -                | -         |    -0.15 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            1 |     3492 | 2024-03-19 | The Neighbours    | L   | 0.269      | -            | -                | -                | -         |    -6.84 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,708.68)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $2,259.00      | $2,259.00       |
| 2024-06-10 |      0.822 | $750.00        | $616.77         |
| 2024-05-13 |      0.633 | $1,000.00      | $632.78         |
| 2024-04-01 |      0.354 | $3,153.00      | $1,114.72       |
| 2024-03-19 |      0.269 | $317.00        | $85.41          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
