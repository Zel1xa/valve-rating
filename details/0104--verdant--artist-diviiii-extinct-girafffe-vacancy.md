### Roster Details<br />
Team Name: Verdant<br />
Roster: arTisT, Diviiii, Extinct, Girafffe, Vacancy<br />
Global Rank: [104](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [77]( ../standings_europe.md)<br />
<br />
Final Rank Value:  846.1<br />
<br />
Final Rank Value (846.1) = Starting Rank Value (943.2) + Head To Head Adjustments (-97.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.353[<sup>1</sup>](#table2)
- Bounty Collected: 0.338[<sup>2</sup>](#table1)
- Opponent Network: 0.101[<sup>2</sup>](#table1)
- LAN Wins: 0.271[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 943.2
- 400 + ( ( 0.266 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 943.2


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
|           34 |      494 | 2024-07-21 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.039 (0.012)    | 1 (1.000) |     9.90 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           33 |      520 | 2024-07-20 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.039 (0.012)    | 1 (1.000) |    10.09 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           32 |      668 | 2024-07-17 | PERA              | L   | 1.000      | -            | -                | -                | -         |    -8.80 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           31 |      835 | 2024-07-12 | Revenant          | L   | 1.000      | -            | -                | -                | -         |   -14.58 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           30 |      916 | 2024-07-08 | Rebels            | L   | 1.000      | -            | -                | -                | -         |    -9.69 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           29 |     1011 | 2024-06-16 | UNiTY             | L   | 0.871      | -            | -                | -                | -         |   -10.18 | arTisT, Diviiii, Ducky, Extinct, Vacancy    |
|           28 |     1022 | 2024-06-15 | Revenant          | L   | 0.867      | -            | -                | -                | -         |   -16.19 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           27 |     1060 | 2024-06-14 | Aurora Young Blud | L   | 0.860      | -            | -                | -                | -         |   -14.39 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           26 |     1099 | 2024-06-13 | Nemiga            | L   | 0.854      | -            | -                | -                | -         |    -5.25 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           25 |     1107 | 2024-06-13 | Revenant          | W   | 0.853      | 0.143        | 0.027 (0.003)    | 0.267 (0.033)    | 0 (0.000) |     9.77 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           24 |     1130 | 2024-06-12 | DMS               | W   | 0.847      | 0.143        | 0.003 (0.000)    | 0.446 (0.054)    | 0 (0.000) |    14.72 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           23 |     1152 | 2024-06-11 | 9INE              | L   | 0.840      | -            | -                | -                | -         |   -23.54 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           22 |     1346 | 2024-06-07 | B8                | L   | 0.813      | -            | -                | -                | -         |    -5.51 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           21 |     1353 | 2024-06-07 | Aurora            | L   | 0.813      | -            | -                | -                | -         |    -0.82 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           20 |     1363 | 2024-06-07 | B8                | W   | 0.812      | 0.143        | 0.165 (0.019)    | 0.951 (0.110)    | 0 (0.000) |    20.38 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           19 |     1400 | 2024-06-06 | Aurora Young Blud | L   | 0.807      | -            | -                | -                | -         |   -14.42 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           18 |     1458 | 2024-06-05 | Enterprise        | W   | 0.801      | 0.372        | 0.039 (0.012)    | 0.625 (0.186)    | 0 (0.000) |    13.44 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           17 |     1509 | 2024-06-04 | K10               | L   | 0.794      | -            | -                | -                | -         |   -19.19 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           16 |     1539 | 2024-06-03 | LEON              | W   | 0.787      | 0.372        | 0.007 (0.002)    | 0.130 (0.038)    | 0 (0.000) |     5.66 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           15 |     1590 | 2024-06-01 | V1dar             | W   | 0.774      | 0.372        | -                | 0.056 (0.016)    | 0 (0.000) |     2.90 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           14 |     1677 | 2024-05-29 | DMS               | L   | 0.754      | -            | -                | -                | -         |   -11.94 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           13 |     1885 | 2024-05-21 | Zero Tenacity     | L   | 0.698      | -            | -                | -                | -         |    -6.17 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           12 |     1923 | 2024-05-20 | Sampi             | W   | 0.692      | 0.435        | 0.027 (0.008)    | 1.000 (0.301)    | 0 (0.000) |    10.52 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           11 |     1984 | 2024-05-18 | Space             | L   | 0.678      | -            | -                | -                | -         |   -13.23 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           10 |     2097 | 2024-05-15 | Sangal            | W   | 0.659      | 0.435        | 0.219 (0.063)    | 0.861 (0.247)    | -         |    15.21 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            9 |     2151 | 2024-05-14 | B8                | L   | 0.653      | -            | -                | -                | -         |    -5.12 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            8 |     2178 | 2024-05-13 | kONO              | L   | 0.645      | -            | -                | -                | -         |   -12.84 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            7 |     2191 | 2024-05-12 | Johnny Speeds     | L   | 0.640      | -            | -                | -                | -         |    -2.58 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            6 |     2202 | 2024-05-12 | Zero Tenacity     | L   | 0.639      | -            | -                | -                | -         |    -7.02 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            5 |     2222 | 2024-05-11 | V1dar             | W   | 0.633      | -            | -                | -                | -         |     1.89 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            4 |     2250 | 2024-05-10 | ECLOT             | L   | 0.625      | -            | -                | -                | -         |    -3.96 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            3 |     3262 | 2024-04-01 | Reason            | W   | 0.365      | 0.301        | 0.002 (0.000)    | -                | 1 (0.365) |     1.11 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            2 |     3335 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.334      | -            | -                | -                | -         |    -0.15 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            1 |     3460 | 2024-03-19 | The Neighbours    | L   | 0.281      | -            | -                | -                | -         |    -7.11 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,768.98)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $2,259.00      | $2,259.00       |
| 2024-06-10 |      0.834 | $750.00        | $625.43         |
| 2024-05-13 |      0.644 | $1,000.00      | $644.33         |
| 2024-04-01 |      0.365 | $3,153.00      | $1,151.14       |
| 2024-03-19 |      0.281 | $317.00        | $89.08          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
