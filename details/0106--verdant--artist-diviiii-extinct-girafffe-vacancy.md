### Roster Details<br />
Team Name: Verdant<br />
Roster: arTisT, Diviiii, Extinct, Girafffe, Vacancy<br />
Global Rank: [106](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [78]( ../standings_europe.md)<br />
<br />
Final Rank Value:  843.9<br />
<br />
Final Rank Value (843.9) = Starting Rank Value (942.9) + Head To Head Adjustments (-98.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.353[<sup>1</sup>](#table2)
- Bounty Collected: 0.338[<sup>2</sup>](#table1)
- Opponent Network: 0.101[<sup>2</sup>](#table1)
- LAN Wins: 0.270[<sup>2</sup>](#table1)

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
|           34 |      459 | 2024-07-21 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.039 (0.012)    | 1 (1.000) |     9.96 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           33 |      485 | 2024-07-20 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.039 (0.012)    | 1 (1.000) |    10.15 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           32 |      633 | 2024-07-17 | PERA              | L   | 1.000      | -            | -                | -                | -         |    -8.79 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           31 |      799 | 2024-07-12 | Revenant          | L   | 1.000      | -            | -                | -                | -         |   -14.53 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           30 |      880 | 2024-07-08 | Rebels            | L   | 1.000      | -            | -                | -                | -         |    -9.63 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           29 |      975 | 2024-06-16 | UNiTY             | L   | 0.876      | -            | -                | -                | -         |   -10.33 | arTisT, Diviiii, Ducky, Extinct, Vacancy    |
|           28 |      986 | 2024-06-15 | Revenant          | L   | 0.872      | -            | -                | -                | -         |   -16.23 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           27 |     1024 | 2024-06-14 | Aurora Young Blud | L   | 0.865      | -            | -                | -                | -         |   -15.01 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           26 |     1063 | 2024-06-13 | Nemiga            | L   | 0.859      | -            | -                | -                | -         |    -5.57 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           25 |     1071 | 2024-06-13 | Revenant          | W   | 0.858      | 0.143        | 0.027 (0.003)    | 0.266 (0.033)    | 0 (0.000) |     9.83 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           24 |     1094 | 2024-06-12 | DMS               | W   | 0.852      | 0.143        | 0.003 (0.000)    | 0.446 (0.054)    | 0 (0.000) |    14.83 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           23 |     1116 | 2024-06-11 | 9INE              | L   | 0.845      | -            | -                | -                | -         |   -23.65 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           22 |     1310 | 2024-06-07 | B8                | L   | 0.818      | -            | -                | -                | -         |    -5.54 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           21 |     1317 | 2024-06-07 | Aurora            | L   | 0.818      | -            | -                | -                | -         |    -0.84 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           20 |     1327 | 2024-06-07 | B8                | W   | 0.817      | 0.143        | 0.165 (0.019)    | 0.913 (0.107)    | 0 (0.000) |    20.50 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           19 |     1364 | 2024-06-06 | Aurora Young Blud | L   | 0.812      | -            | -                | -                | -         |   -15.13 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           18 |     1422 | 2024-06-05 | Enterprise        | W   | 0.805      | 0.372        | 0.039 (0.012)    | 0.624 (0.187)    | 0 (0.000) |    13.51 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           17 |     1473 | 2024-06-04 | K10               | L   | 0.799      | -            | -                | -                | -         |   -19.29 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           16 |     1503 | 2024-06-03 | LEON              | W   | 0.792      | 0.372        | 0.007 (0.002)    | 0.130 (0.038)    | 0 (0.000) |     5.69 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           15 |     1554 | 2024-06-01 | V1dar             | W   | 0.779      | 0.372        | -                | 0.057 (0.016)    | 0 (0.000) |     2.93 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           14 |     1641 | 2024-05-29 | DMS               | L   | 0.759      | -            | -                | -                | -         |   -12.00 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           13 |     1849 | 2024-05-21 | Zero Tenacity     | L   | 0.703      | -            | -                | -                | -         |    -6.16 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           12 |     1887 | 2024-05-20 | Sampi             | W   | 0.696      | 0.435        | 0.027 (0.008)    | 1.000 (0.303)    | 0 (0.000) |    10.60 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           11 |     1948 | 2024-05-18 | Space             | L   | 0.682      | -            | -                | -                | -         |   -13.22 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           10 |     2061 | 2024-05-15 | Sangal            | W   | 0.663      | 0.435        | 0.219 (0.063)    | 0.862 (0.248)    | -         |    15.22 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            9 |     2115 | 2024-05-14 | B8                | L   | 0.657      | -            | -                | -                | -         |    -5.15 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            8 |     2142 | 2024-05-13 | kONO              | L   | 0.650      | -            | -                | -                | -         |   -12.90 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            7 |     2155 | 2024-05-12 | Johnny Speeds     | L   | 0.645      | -            | -                | -                | -         |    -2.69 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            6 |     2166 | 2024-05-12 | Zero Tenacity     | L   | 0.643      | -            | -                | -                | -         |    -7.13 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            5 |     2186 | 2024-05-11 | V1dar             | W   | 0.638      | -            | -                | -                | -         |     1.91 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            4 |     2214 | 2024-05-10 | ECLOT             | L   | 0.630      | -            | -                | -                | -         |    -4.04 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            3 |     3225 | 2024-04-01 | Reason            | W   | 0.370      | 0.301        | 0.002 (0.000)    | -                | 1 (0.370) |     1.12 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            2 |     3298 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.339      | -            | -                | -                | -         |    -0.16 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            1 |     3423 | 2024-03-19 | The Neighbours    | L   | 0.286      | -            | -                | -                | -         |    -7.21 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,794.23)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $2,259.00      | $2,259.00       |
| 2024-06-10 |      0.839 | $750.00        | $629.06         |
| 2024-05-13 |      0.649 | $1,000.00      | $649.17         |
| 2024-04-01 |      0.370 | $3,153.00      | $1,166.39       |
| 2024-03-19 |      0.286 | $317.00        | $90.61          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
