### Roster Details<br />
Team Name: Verdant<br />
Roster: arTisT, Diviiii, Extinct, Girafffe, Vacancy<br />
Global Rank: [104](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  848.6<br />
<br />
Final Rank Value (848.6) = Starting Rank Value (943.8) + Head To Head Adjustments (-95.2)<br />

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
|           34 |      522 | 2024-07-21 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.039 (0.012)    | 1 (1.000) |     9.87 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           33 |      548 | 2024-07-20 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.039 (0.012)    | 1 (1.000) |    10.05 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           32 |      696 | 2024-07-17 | PERA              | L   | 1.000      | -            | -                | -                | -         |    -8.99 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           31 |      863 | 2024-07-12 | Revenant          | L   | 1.000      | -            | -                | -                | -         |   -14.62 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           30 |      944 | 2024-07-08 | Rebels            | L   | 1.000      | -            | -                | -                | -         |    -9.82 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           29 |     1039 | 2024-06-16 | UNiTY             | L   | 0.862      | -            | -                | -                | -         |   -10.14 | arTisT, Diviiii, Ducky, Extinct, Vacancy    |
|           28 |     1050 | 2024-06-15 | Revenant          | L   | 0.858      | -            | -                | -                | -         |   -16.04 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           27 |     1088 | 2024-06-14 | Aurora Young Blud | L   | 0.851      | -            | -                | -                | -         |   -13.58 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           26 |     1127 | 2024-06-13 | Nemiga            | L   | 0.845      | -            | -                | -                | -         |    -5.25 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           25 |     1135 | 2024-06-13 | Revenant          | W   | 0.844      | 0.143        | 0.027 (0.003)    | 0.265 (0.032)    | 0 (0.000) |     9.68 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           24 |     1158 | 2024-06-12 | DMS               | W   | 0.838      | 0.143        | 0.003 (0.000)    | 0.438 (0.052)    | 0 (0.000) |    14.61 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           23 |     1180 | 2024-06-11 | 9INE              | L   | 0.831      | -            | -                | -                | -         |   -23.31 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           22 |     1374 | 2024-06-07 | B8                | L   | 0.804      | -            | -                | -                | -         |    -5.50 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           21 |     1381 | 2024-06-07 | Aurora            | L   | 0.804      | -            | -                | -                | -         |    -0.80 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           20 |     1391 | 2024-06-07 | B8                | W   | 0.803      | 0.143        | 0.164 (0.019)    | 0.934 (0.107)    | 0 (0.000) |    20.11 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           19 |     1428 | 2024-06-06 | Aurora Young Blud | L   | 0.798      | -            | -                | -                | -         |   -13.50 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           18 |     1486 | 2024-06-05 | Enterprise        | W   | 0.792      | 0.372        | 0.039 (0.012)    | 0.616 (0.182)    | 0 (0.000) |    13.37 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           17 |     1537 | 2024-06-04 | K10               | L   | 0.785      | -            | -                | -                | -         |   -18.99 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           16 |     1567 | 2024-06-03 | LEON              | W   | 0.778      | 0.372        | 0.007 (0.002)    | 0.127 (0.037)    | 0 (0.000) |     5.60 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           15 |     1618 | 2024-06-01 | V1dar             | W   | 0.765      | 0.372        | -                | 0.055 (0.016)    | 0 (0.000) |     2.84 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           14 |     1705 | 2024-05-29 | DMS               | L   | 0.745      | -            | -                | -                | -         |   -11.75 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           13 |     1913 | 2024-05-21 | Zero Tenacity     | L   | 0.689      | -            | -                | -                | -         |    -6.12 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           12 |     1951 | 2024-05-20 | Sampi             | W   | 0.682      | 0.435        | 0.027 (0.008)    | 1.000 (0.297)    | 0 (0.000) |    10.35 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           11 |     2012 | 2024-05-18 | Space             | L   | 0.669      | -            | -                | -                | -         |   -13.10 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           10 |     2125 | 2024-05-15 | Sangal            | W   | 0.650      | 0.435        | 0.219 (0.062)    | 0.866 (0.244)    | -         |    15.03 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            9 |     2179 | 2024-05-14 | B8                | L   | 0.644      | -            | -                | -                | -         |    -5.08 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            8 |     2206 | 2024-05-13 | kONO              | L   | 0.636      | -            | -                | -                | -         |   -12.70 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            7 |     2219 | 2024-05-12 | Johnny Speeds     | L   | 0.631      | -            | -                | -                | -         |    -2.53 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            6 |     2230 | 2024-05-12 | Zero Tenacity     | L   | 0.630      | -            | -                | -                | -         |    -6.88 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            5 |     2250 | 2024-05-11 | V1dar             | W   | 0.624      | -            | -                | -                | -         |     1.85 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            4 |     2278 | 2024-05-10 | ECLOT             | L   | 0.616      | -            | -                | -                | -         |    -3.90 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            3 |     3290 | 2024-04-01 | Reason            | W   | 0.356      | 0.301        | 0.002 (0.000)    | -                | 1 (0.356) |     1.07 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            2 |     3363 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.325      | -            | -                | -                | -         |    -0.15 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            1 |     3488 | 2024-03-19 | The Neighbours    | L   | 0.272      | -            | -                | -                | -         |    -6.89 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,721.73)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $2,259.00      | $2,259.00       |
| 2024-06-10 |      0.825 | $750.00        | $618.65         |
| 2024-05-13 |      0.635 | $1,000.00      | $635.28         |
| 2024-04-01 |      0.356 | $3,153.00      | $1,122.60       |
| 2024-03-19 |      0.272 | $317.00        | $86.21          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
