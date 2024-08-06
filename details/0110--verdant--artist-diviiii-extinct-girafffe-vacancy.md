### Roster Details<br />
Team Name: Verdant<br />
Roster: arTisT, Diviiii, Extinct, Girafffe, Vacancy<br />
Global Rank: [110](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [78]( ../standings_europe.md)<br />
<br />
Final Rank Value:  840.5<br />
<br />
Final Rank Value (840.5) = Starting Rank Value (945.1) + Head To Head Adjustments (-104.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.353[<sup>1</sup>](#table2)
- Bounty Collected: 0.337[<sup>2</sup>](#table1)
- Opponent Network: 0.098[<sup>2</sup>](#table1)
- LAN Wins: 0.272[<sup>2</sup>](#table1)

The average of these factors is 0.265<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 945.1
- 400 + ( ( 0.265 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 945.1


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
|           35 |        8 | 2024-08-06 | Enterprise        | L   | 1.000      | -            | -                | -                | -         |   -11.17 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           34 |      539 | 2024-07-21 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.038 (0.011)    | 1 (1.000) |     9.79 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           33 |      565 | 2024-07-20 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.038 (0.011)    | 1 (1.000) |     9.97 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           32 |      713 | 2024-07-17 | PERA              | L   | 1.000      | -            | -                | -                | -         |    -9.11 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           31 |      880 | 2024-07-12 | Revenant          | L   | 1.000      | -            | -                | -                | -         |   -14.73 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           30 |      961 | 2024-07-08 | Rebels            | L   | 1.000      | -            | -                | -                | -         |    -9.89 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           29 |     1056 | 2024-06-16 | UNiTY             | L   | 0.858      | -            | -                | -                | -         |   -10.21 | arTisT, Diviiii, Ducky, Extinct, Vacancy    |
|           28 |     1067 | 2024-06-15 | Revenant          | L   | 0.854      | -            | -                | -                | -         |   -16.08 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           27 |     1105 | 2024-06-14 | Aurora Young Blud | L   | 0.848      | -            | -                | -                | -         |   -12.59 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           26 |     1144 | 2024-06-13 | Nemiga            | L   | 0.841      | -            | -                | -                | -         |    -5.27 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           25 |     1152 | 2024-06-13 | Revenant          | W   | 0.840      | 0.143        | 0.027 (0.003)    | 0.259 (0.031)    | 0 (0.000) |     9.56 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           24 |     1175 | 2024-06-12 | DMS               | W   | 0.834      | 0.143        | 0.003 (0.000)    | 0.428 (0.051)    | 0 (0.000) |    14.47 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           23 |     1197 | 2024-06-11 | 9INE              | L   | 0.827      | -            | -                | -                | -         |   -23.18 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           22 |     1391 | 2024-06-07 | B8                | L   | 0.800      | -            | -                | -                | -         |    -5.49 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           21 |     1398 | 2024-06-07 | Aurora            | L   | 0.800      | -            | -                | -                | -         |    -0.79 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           20 |     1408 | 2024-06-07 | B8                | W   | 0.799      | 0.143        | 0.170 (0.019)    | 0.912 (0.104)    | 0 (0.000) |    19.98 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           19 |     1445 | 2024-06-06 | Aurora Young Blud | L   | 0.794      | -            | -                | -                | -         |   -12.35 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           18 |     1503 | 2024-06-05 | Enterprise        | W   | 0.788      | 0.372        | 0.039 (0.012)    | 0.641 (0.188)    | 0 (0.000) |    13.31 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           17 |     1554 | 2024-06-04 | K10               | L   | 0.781      | -            | -                | -                | -         |   -18.93 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           16 |     1584 | 2024-06-03 | LEON              | W   | 0.774      | 0.372        | 0.007 (0.002)    | 0.124 (0.036)    | 0 (0.000) |     5.57 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           15 |     1635 | 2024-06-01 | V1dar             | W   | 0.761      | 0.372        | -                | 0.054 (0.015)    | 0 (0.000) |     2.80 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           14 |     1722 | 2024-05-29 | DMS               | L   | 0.741      | -            | -                | -                | -         |   -11.74 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           13 |     1930 | 2024-05-21 | Zero Tenacity     | L   | 0.685      | -            | -                | -                | -         |    -6.00 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           12 |     1968 | 2024-05-20 | Sampi             | W   | 0.679      | 0.435        | 0.027 (0.008)    | 1.000 (0.295)    | 0 (0.000) |    10.28 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           11 |     2029 | 2024-05-18 | Space             | L   | 0.665      | -            | -                | -                | -         |   -12.93 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           10 |     2142 | 2024-05-15 | Sangal            | W   | 0.646      | 0.435        | 0.219 (0.061)    | 0.846 (0.237)    | -         |    15.04 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            9 |     2196 | 2024-05-14 | B8                | L   | 0.640      | -            | -                | -                | -         |    -5.04 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            8 |     2223 | 2024-05-13 | kONO              | L   | 0.632      | -            | -                | -                | -         |   -12.54 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            7 |     2236 | 2024-05-12 | Johnny Speeds     | L   | 0.627      | -            | -                | -                | -         |    -2.49 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            6 |     2247 | 2024-05-12 | Zero Tenacity     | L   | 0.626      | -            | -                | -                | -         |    -6.83 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            5 |     2267 | 2024-05-11 | V1dar             | W   | 0.621      | -            | -                | -                | -         |     1.82 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            4 |     2295 | 2024-05-10 | ECLOT             | L   | 0.612      | -            | -                | -                | -         |    -3.87 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            3 |     3307 | 2024-04-01 | Reason            | W   | 0.352      | 0.301        | 0.002 (0.000)    | -                | 1 (0.352) |     1.06 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            2 |     3380 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.321      | -            | -                | -                | -         |    -0.15 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            1 |     3505 | 2024-03-19 | The Neighbours    | L   | 0.268      | -            | -                | -                | -         |    -6.81 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,701.43)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $2,259.00      | $2,259.00       |
| 2024-06-10 |      0.821 | $750.00        | $615.73         |
| 2024-05-13 |      0.631 | $1,000.00      | $631.39         |
| 2024-04-01 |      0.352 | $3,153.00      | $1,110.34       |
| 2024-03-19 |      0.268 | $317.00        | $84.97          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />