### Roster Details<br />
Team Name: Verdant<br />
Roster: arTisT, Diviiii, Extinct, Girafffe, Vacancy<br />
Global Rank: [98](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [71]( ../standings_europe.md)<br />
<br />
Final Rank Value:  864.3<br />
<br />
Final Rank Value (864.3) = Starting Rank Value (956.2) + Head To Head Adjustments (-91.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.354[<sup>1</sup>](#table2)
- Bounty Collected: 0.344[<sup>2</sup>](#table1)
- Opponent Network: 0.109[<sup>2</sup>](#table1)
- LAN Wins: 0.275[<sup>2</sup>](#table1)

The average of these factors is 0.270<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 956.2
- 400 + ( ( 0.270 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 956.2


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
|           35 |      380 | 2024-07-21 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.039 (0.011)    | 1 (1.000) |     9.32 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           34 |      407 | 2024-07-20 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | -                | 1 (1.000) |     9.46 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           33 |      561 | 2024-07-17 | PERA              | L   | 1.000      | -            | -                | -                | -         |    -9.65 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           32 |      682 | 2024-07-15 | Revenant          | W   | 1.000      | 0.333        | 0.027 (0.009)    | 0.263 (0.088)    | 0 (0.000) |    16.75 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           31 |      736 | 2024-07-12 | Revenant          | L   | 1.000      | -            | -                | -                | -         |   -14.65 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           30 |      817 | 2024-07-08 | Rebels            | L   | 1.000      | -            | -                | -                | -         |    -9.60 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           29 |      910 | 2024-06-16 | UNiTY             | L   | 0.891      | -            | -                | -                | -         |   -10.89 | arTisT, Diviiii, Ducky, Extinct, Vacancy    |
|           28 |      919 | 2024-06-15 | Revenant          | L   | 0.887      | -            | -                | -                | -         |   -16.68 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           27 |      951 | 2024-06-14 | Aurora Young Blud | L   | 0.880      | -            | -                | -                | -         |   -13.94 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           26 |      989 | 2024-06-13 | Nemiga            | L   | 0.874      | -            | -                | -                | -         |    -5.84 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           25 |      997 | 2024-06-13 | Revenant          | W   | 0.873      | 0.143        | 0.027 (0.003)    | 0.263 (0.033)    | 0 (0.000) |     9.85 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           24 |     1020 | 2024-06-12 | DMS               | W   | 0.867      | 0.143        | 0.003 (0.000)    | 0.447 (0.055)    | 0 (0.000) |    14.77 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           23 |     1043 | 2024-06-11 | 9INE              | L   | 0.860      | -            | -                | -                | -         |   -24.05 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           22 |     1247 | 2024-06-07 | B8                | L   | 0.833      | -            | -                | -                | -         |    -6.08 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           21 |     1254 | 2024-06-07 | Aurora            | L   | 0.833      | -            | -                | -                | -         |    -0.87 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           20 |     1264 | 2024-06-07 | B8                | W   | 0.832      | 0.143        | 0.168 (0.020)    | 0.878 (0.104)    | 0 (0.000) |    20.42 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           19 |     1303 | 2024-06-06 | Aurora Young Blud | L   | 0.827      | -            | -                | -                | -         |   -14.72 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           18 |     1363 | 2024-06-05 | Enterprise        | W   | 0.820      | 0.372        | 0.040 (0.012)    | 0.622 (0.190)    | 0 (0.000) |    13.48 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           17 |     1415 | 2024-06-04 | K10               | L   | 0.814      | -            | -                | -                | -         |   -19.75 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           16 |     1445 | 2024-06-03 | LEON              | W   | 0.807      | 0.372        | 0.007 (0.002)    | 0.131 (0.039)    | 0 (0.000) |     5.71 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           15 |     1496 | 2024-06-01 | V1dar             | W   | 0.794      | 0.372        | -                | 0.058 (0.017)    | 0 (0.000) |     2.93 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           14 |     1584 | 2024-05-29 | DMS               | L   | 0.774      | -            | -                | -                | -         |   -12.40 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           13 |     1809 | 2024-05-21 | Zero Tenacity     | L   | 0.718      | -            | -                | -                | -         |    -7.24 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           12 |     1852 | 2024-05-20 | Sampi             | W   | 0.711      | 0.435        | 0.028 (0.009)    | 1.000 (0.309)    | -         |    10.35 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           11 |     1919 | 2024-05-18 | Space             | L   | 0.698      | -            | -                | -                | -         |   -13.67 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           10 |     2036 | 2024-05-15 | Sangal            | W   | 0.678      | 0.435        | 0.221 (0.065)    | 0.823 (0.243)    | -         |    15.20 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            9 |     2092 | 2024-05-14 | B8                | L   | 0.672      | -            | -                | -                | -         |    -5.58 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            8 |     2122 | 2024-05-13 | kONO              | L   | 0.665      | -            | -                | -                | -         |   -12.95 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            7 |     2135 | 2024-05-12 | Johnny Speeds     | L   | 0.660      | -            | -                | -                | -         |    -2.76 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            6 |     2146 | 2024-05-12 | Zero Tenacity     | L   | 0.658      | -            | -                | -                | -         |    -7.67 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            5 |     2166 | 2024-05-11 | V1dar             | W   | 0.653      | -            | -                | -                | -         |     1.88 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            4 |     2194 | 2024-05-10 | ECLOT             | L   | 0.645      | -            | -                | -                | -         |    -6.13 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            3 |     3230 | 2024-04-01 | Reason            | W   | 0.385      | -            | -                | -                | 1 (0.385) |     1.10 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            2 |     3304 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.354      | -            | -                | -                | -         |    -0.36 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            1 |     3433 | 2024-03-19 | The Neighbours    | L   | 0.301      | -            | -                | -                | -         |    -7.64 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,872.53)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $2,259.00      | $2,259.00       |
| 2024-06-10 |      0.854 | $750.00        | $640.31         |
| 2024-05-13 |      0.664 | $1,000.00      | $664.17         |
| 2024-04-01 |      0.385 | $3,153.00      | $1,213.69       |
| 2024-03-19 |      0.301 | $317.00        | $95.36          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
