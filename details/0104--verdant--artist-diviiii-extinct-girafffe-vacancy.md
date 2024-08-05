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
- Opponent Network: 0.100[<sup>2</sup>](#table1)
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
|           34 |      498 | 2024-07-21 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.040 (0.012)    | 1 (1.000) |     9.91 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           33 |      524 | 2024-07-20 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.040 (0.012)    | 1 (1.000) |    10.10 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           32 |      672 | 2024-07-17 | PERA              | L   | 1.000      | -            | -                | -                | -         |    -8.90 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           31 |      839 | 2024-07-12 | Revenant          | L   | 1.000      | -            | -                | -                | -         |   -14.58 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           30 |      920 | 2024-07-08 | Rebels            | L   | 1.000      | -            | -                | -                | -         |    -9.71 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           29 |     1015 | 2024-06-16 | UNiTY             | L   | 0.869      | -            | -                | -                | -         |   -10.17 | arTisT, Diviiii, Ducky, Extinct, Vacancy    |
|           28 |     1026 | 2024-06-15 | Revenant          | L   | 0.865      | -            | -                | -                | -         |   -16.14 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           27 |     1064 | 2024-06-14 | Aurora Young Blud | L   | 0.858      | -            | -                | -                | -         |   -14.36 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           26 |     1103 | 2024-06-13 | Nemiga            | L   | 0.851      | -            | -                | -                | -         |    -5.25 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           25 |     1111 | 2024-06-13 | Revenant          | W   | 0.851      | 0.143        | 0.027 (0.003)    | 0.268 (0.033)    | 0 (0.000) |     9.74 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           24 |     1134 | 2024-06-12 | DMS               | W   | 0.844      | 0.143        | 0.003 (0.000)    | 0.446 (0.054)    | 0 (0.000) |    14.68 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           23 |     1156 | 2024-06-11 | 9INE              | L   | 0.838      | -            | -                | -                | -         |   -23.47 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           22 |     1350 | 2024-06-07 | B8                | L   | 0.811      | -            | -                | -                | -         |    -5.50 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           21 |     1357 | 2024-06-07 | Aurora            | L   | 0.810      | -            | -                | -                | -         |    -0.82 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           20 |     1367 | 2024-06-07 | B8                | W   | 0.810      | 0.143        | 0.165 (0.019)    | 0.951 (0.110)    | 0 (0.000) |    20.31 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           19 |     1404 | 2024-06-06 | Aurora Young Blud | L   | 0.805      | -            | -                | -                | -         |   -14.38 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           18 |     1462 | 2024-06-05 | Enterprise        | W   | 0.798      | 0.372        | 0.039 (0.012)    | 0.625 (0.186)    | 0 (0.000) |    13.38 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           17 |     1513 | 2024-06-04 | K10               | L   | 0.791      | -            | -                | -                | -         |   -19.14 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           16 |     1543 | 2024-06-03 | LEON              | W   | 0.785      | 0.372        | 0.007 (0.002)    | 0.130 (0.038)    | 0 (0.000) |     5.64 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           15 |     1594 | 2024-06-01 | V1dar             | W   | 0.771      | 0.372        | -                | 0.056 (0.016)    | 0 (0.000) |     2.88 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           14 |     1681 | 2024-05-29 | DMS               | L   | 0.752      | -            | -                | -                | -         |   -11.91 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           13 |     1889 | 2024-05-21 | Zero Tenacity     | L   | 0.696      | -            | -                | -                | -         |    -6.16 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           12 |     1927 | 2024-05-20 | Sampi             | W   | 0.689      | 0.435        | 0.027 (0.008)    | 1.000 (0.300)    | 0 (0.000) |    10.47 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           11 |     1988 | 2024-05-18 | Space             | L   | 0.675      | -            | -                | -                | -         |   -13.19 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           10 |     2101 | 2024-05-15 | Sangal            | W   | 0.656      | 0.435        | 0.219 (0.062)    | 0.861 (0.246)    | -         |    15.15 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            9 |     2155 | 2024-05-14 | B8                | L   | 0.650      | -            | -                | -                | -         |    -5.11 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            8 |     2182 | 2024-05-13 | kONO              | L   | 0.643      | -            | -                | -                | -         |   -12.80 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            7 |     2195 | 2024-05-12 | Johnny Speeds     | L   | 0.638      | -            | -                | -                | -         |    -2.57 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            6 |     2206 | 2024-05-12 | Zero Tenacity     | L   | 0.636      | -            | -                | -                | -         |    -7.00 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            5 |     2226 | 2024-05-11 | V1dar             | W   | 0.631      | -            | -                | -                | -         |     1.88 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            4 |     2254 | 2024-05-10 | ECLOT             | L   | 0.623      | -            | -                | -                | -         |    -3.96 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            3 |     3266 | 2024-04-01 | Reason            | W   | 0.363      | 0.301        | 0.002 (0.000)    | -                | 1 (0.363) |     1.10 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            2 |     3339 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.331      | -            | -                | -                | -         |    -0.15 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            1 |     3464 | 2024-03-19 | The Neighbours    | L   | 0.278      | -            | -                | -                | -         |    -7.05 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,756.53)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $2,259.00      | $2,259.00       |
| 2024-06-10 |      0.832 | $750.00        | $623.65         |
| 2024-05-13 |      0.642 | $1,000.00      | $641.94         |
| 2024-04-01 |      0.363 | $3,153.00      | $1,143.62       |
| 2024-03-19 |      0.279 | $317.00        | $88.32          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
