### Roster Details<br />
Team Name: Verdant<br />
Roster: arTisT, Diviiii, Extinct, Girafffe, Vacancy<br />
Global Rank: [100](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  852.8<br />
<br />
Final Rank Value (852.8) = Starting Rank Value (943.9) + Head To Head Adjustments (-91.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.353[<sup>1</sup>](#table2)
- Bounty Collected: 0.338[<sup>2</sup>](#table1)
- Opponent Network: 0.102[<sup>2</sup>](#table1)
- LAN Wins: 0.270[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 943.9
- 400 + ( ( 0.266 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 943.9


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
|           33 |      436 | 2024-07-21 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.040 (0.012)    | 1 (1.000) |     9.65 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           32 |      462 | 2024-07-20 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.040 (0.012)    | 1 (1.000) |     9.81 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           31 |      610 | 2024-07-17 | PERA              | L   | 1.000      | -            | -                | -                | -         |    -9.12 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           30 |      771 | 2024-07-12 | Revenant          | L   | 1.000      | -            | -                | -                | -         |   -15.26 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           29 |      850 | 2024-07-08 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -10.10 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           28 |      945 | 2024-06-15 | Revenant          | L   | 0.874      | -            | -                | -                | -         |   -16.33 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           27 |      976 | 2024-06-14 | Aurora Young Blud | L   | 0.867      | -            | -                | -                | -         |   -15.00 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           26 |     1013 | 2024-06-13 | Nemiga            | L   | 0.860      | -            | -                | -                | -         |    -5.58 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           25 |     1021 | 2024-06-13 | Revenant          | W   | 0.859      | 0.143        | 0.027 (0.003)    | 0.275 (0.034)    | 0 (0.000) |     9.77 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           24 |     1043 | 2024-06-12 | DMS               | W   | 0.853      | 0.143        | 0.003 (0.000)    | 0.462 (0.056)    | 0 (0.000) |    15.06 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           23 |     1064 | 2024-06-11 | 9INE              | L   | 0.847      | -            | -                | -                | -         |   -23.71 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           22 |     1250 | 2024-06-07 | B8                | L   | 0.820      | -            | -                | -                | -         |    -5.60 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           21 |     1257 | 2024-06-07 | Aurora            | L   | 0.819      | -            | -                | -                | -         |    -0.83 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           20 |     1267 | 2024-06-07 | B8                | W   | 0.819      | 0.143        | 0.166 (0.019)    | 0.945 (0.110)    | 0 (0.000) |    20.50 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           19 |     1305 | 2024-06-06 | Aurora Young Blud | L   | 0.814      | -            | -                | -                | -         |   -15.13 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           18 |     1363 | 2024-06-05 | Enterprise        | W   | 0.807      | 0.372        | 0.039 (0.012)    | 0.646 (0.194)    | 0 (0.000) |    13.57 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           17 |     1413 | 2024-06-04 | K10               | L   | 0.800      | -            | -                | -                | -         |   -19.33 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           16 |     1443 | 2024-06-03 | LEON              | W   | 0.794      | 0.372        | 0.007 (0.002)    | 0.135 (0.040)    | 0 (0.000) |     5.71 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           15 |     1492 | 2024-06-01 | V1dar             | W   | 0.780      | 0.372        | -                | 0.059 (0.017)    | 0 (0.000) |     2.94 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           14 |     1578 | 2024-05-29 | DMS               | L   | 0.760      | -            | -                | -                | -         |   -12.05 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           13 |     1785 | 2024-05-21 | Zero Tenacity     | L   | 0.705      | -            | -                | -                | -         |    -6.24 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           12 |     1823 | 2024-05-20 | Sampi             | W   | 0.698      | 0.435        | 0.028 (0.008)    | 1.000 (0.303)    | 0 (0.000) |    10.66 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           11 |     1883 | 2024-05-18 | Space             | L   | 0.684      | -            | -                | -                | -         |   -13.19 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           10 |     1996 | 2024-05-15 | Sangal            | W   | 0.665      | 0.435        | 0.219 (0.063)    | 0.823 (0.238)    | -         |    15.21 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            9 |     2050 | 2024-05-14 | B8                | L   | 0.659      | -            | -                | -                | -         |    -5.23 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            8 |     2077 | 2024-05-13 | kONO              | L   | 0.652      | -            | -                | -                | -         |   -12.95 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            7 |     2090 | 2024-05-12 | Johnny Speeds     | L   | 0.647      | -            | -                | -                | -         |    -2.68 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            6 |     2101 | 2024-05-12 | Zero Tenacity     | L   | 0.645      | -            | -                | -                | -         |    -7.23 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            5 |     2121 | 2024-05-11 | V1dar             | W   | 0.640      | -            | -                | -                | -         |     1.91 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            4 |     2149 | 2024-05-10 | ECLOT             | L   | 0.632      | -            | -                | -                | -         |    -4.03 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            3 |     3159 | 2024-04-01 | Reason            | W   | 0.372      | 0.301        | 0.002 (0.000)    | -                | 1 (0.372) |     1.13 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            2 |     3231 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.340      | -            | -                | -                | -         |    -0.23 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            1 |     3352 | 2024-03-19 | The Neighbours    | L   | 0.287      | -            | -                | -                | -         |    -7.26 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,803.17)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $2,259.00      | $2,259.00       |
| 2024-06-10 |      0.840 | $750.00        | $630.35         |
| 2024-05-13 |      0.651 | $1,000.00      | $650.88         |
| 2024-04-01 |      0.372 | $3,153.00      | $1,171.79       |
| 2024-03-19 |      0.288 | $317.00        | $91.15          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
