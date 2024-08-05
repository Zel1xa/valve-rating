### Roster Details<br />
Team Name: Verdant<br />
Roster: arTisT, Diviiii, Extinct, Girafffe, Vacancy<br />
Global Rank: [105](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
<br />
Final Rank Value:  846.8<br />
<br />
Final Rank Value (846.8) = Starting Rank Value (943.6) + Head To Head Adjustments (-96.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.353[<sup>1</sup>](#table2)
- Bounty Collected: 0.337[<sup>2</sup>](#table1)
- Opponent Network: 0.100[<sup>2</sup>](#table1)
- LAN Wins: 0.271[<sup>2</sup>](#table1)

The average of these factors is 0.265<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 943.6
- 400 + ( ( 0.265 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 943.6


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
|           34 |      511 | 2024-07-21 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.040 (0.012)    | 1 (1.000) |     9.90 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           33 |      537 | 2024-07-20 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.040 (0.012)    | 1 (1.000) |    10.09 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           32 |      685 | 2024-07-17 | PERA              | L   | 1.000      | -            | -                | -                | -         |    -8.92 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           31 |      852 | 2024-07-12 | Revenant          | L   | 1.000      | -            | -                | -                | -         |   -14.59 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           30 |      933 | 2024-07-08 | Rebels            | L   | 1.000      | -            | -                | -                | -         |    -9.74 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           29 |     1028 | 2024-06-16 | UNiTY             | L   | 0.865      | -            | -                | -                | -         |   -10.15 | arTisT, Diviiii, Ducky, Extinct, Vacancy    |
|           28 |     1039 | 2024-06-15 | Revenant          | L   | 0.861      | -            | -                | -                | -         |   -16.08 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           27 |     1077 | 2024-06-14 | Aurora Young Blud | L   | 0.855      | -            | -                | -                | -         |   -14.29 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           26 |     1116 | 2024-06-13 | Nemiga            | L   | 0.848      | -            | -                | -                | -         |    -5.24 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           25 |     1124 | 2024-06-13 | Revenant          | W   | 0.847      | 0.143        | 0.027 (0.003)    | 0.267 (0.032)    | 0 (0.000) |     9.71 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           24 |     1147 | 2024-06-12 | DMS               | W   | 0.841      | 0.143        | 0.003 (0.000)    | 0.444 (0.053)    | 0 (0.000) |    14.68 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           23 |     1169 | 2024-06-11 | 9INE              | L   | 0.834      | -            | -                | -                | -         |   -23.39 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           22 |     1363 | 2024-06-07 | B8                | L   | 0.808      | -            | -                | -                | -         |    -5.49 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           21 |     1370 | 2024-06-07 | Aurora            | L   | 0.807      | -            | -                | -                | -         |    -0.81 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           20 |     1380 | 2024-06-07 | B8                | W   | 0.806      | 0.143        | 0.165 (0.019)    | 0.947 (0.109)    | 0 (0.000) |    20.21 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           19 |     1417 | 2024-06-06 | Aurora Young Blud | L   | 0.801      | -            | -                | -                | -         |   -14.30 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           18 |     1475 | 2024-06-05 | Enterprise        | W   | 0.795      | 0.372        | 0.039 (0.012)    | 0.624 (0.185)    | 0 (0.000) |    13.30 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           17 |     1526 | 2024-06-04 | K10               | L   | 0.788      | -            | -                | -                | -         |   -19.07 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           16 |     1556 | 2024-06-03 | LEON              | W   | 0.782      | 0.372        | 0.007 (0.002)    | 0.129 (0.038)    | 0 (0.000) |     5.61 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           15 |     1607 | 2024-06-01 | V1dar             | W   | 0.768      | 0.372        | -                | 0.056 (0.016)    | 0 (0.000) |     2.86 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           14 |     1694 | 2024-05-29 | DMS               | L   | 0.748      | -            | -                | -                | -         |   -11.78 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           13 |     1902 | 2024-05-21 | Zero Tenacity     | L   | 0.693      | -            | -                | -                | -         |    -6.12 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           12 |     1940 | 2024-05-20 | Sampi             | W   | 0.686      | 0.435        | 0.027 (0.008)    | 1.000 (0.298)    | 0 (0.000) |    10.40 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           11 |     2001 | 2024-05-18 | Space             | L   | 0.672      | -            | -                | -                | -         |   -13.14 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           10 |     2114 | 2024-05-15 | Sangal            | W   | 0.653      | 0.435        | 0.219 (0.062)    | 0.877 (0.249)    | -         |    15.08 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            9 |     2168 | 2024-05-14 | B8                | L   | 0.647      | -            | -                | -                | -         |    -5.10 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            8 |     2195 | 2024-05-13 | kONO              | L   | 0.639      | -            | -                | -                | -         |   -12.76 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            7 |     2208 | 2024-05-12 | Johnny Speeds     | L   | 0.635      | -            | -                | -                | -         |    -2.54 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            6 |     2219 | 2024-05-12 | Zero Tenacity     | L   | 0.633      | -            | -                | -                | -         |    -6.95 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            5 |     2239 | 2024-05-11 | V1dar             | W   | 0.628      | -            | -                | -                | -         |     1.86 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            4 |     2267 | 2024-05-10 | ECLOT             | L   | 0.619      | -            | -                | -                | -         |    -3.94 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            3 |     3279 | 2024-04-01 | Reason            | W   | 0.359      | 0.301        | 0.002 (0.000)    | -                | 1 (0.359) |     1.09 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            2 |     3352 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.328      | -            | -                | -                | -         |    -0.15 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            1 |     3477 | 2024-03-19 | The Neighbours    | L   | 0.275      | -            | -                | -                | -         |    -6.97 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,739.13)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $2,259.00      | $2,259.00       |
| 2024-06-10 |      0.828 | $750.00        | $621.15         |
| 2024-05-13 |      0.639 | $1,000.00      | $638.61         |
| 2024-04-01 |      0.359 | $3,153.00      | $1,133.11       |
| 2024-03-19 |      0.275 | $317.00        | $87.26          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
