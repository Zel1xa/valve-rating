### Roster Details<br />
Team Name: Verdant<br />
Roster: arTisT, Diviiii, Extinct, Girafffe, Vacancy<br />
Global Rank: [104](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  848.5<br />
<br />
Final Rank Value (848.5) = Starting Rank Value (943.8) + Head To Head Adjustments (-95.3)<br />

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
|           34 |      520 | 2024-07-21 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.039 (0.012)    | 1 (1.000) |     9.86 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           33 |      546 | 2024-07-20 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.039 (0.012)    | 1 (1.000) |    10.04 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           32 |      694 | 2024-07-17 | PERA              | L   | 1.000      | -            | -                | -                | -         |    -8.98 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           31 |      861 | 2024-07-12 | Revenant          | L   | 1.000      | -            | -                | -                | -         |   -14.62 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           30 |      942 | 2024-07-08 | Rebels            | L   | 1.000      | -            | -                | -                | -         |    -9.81 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           29 |     1037 | 2024-06-16 | UNiTY             | L   | 0.864      | -            | -                | -                | -         |   -10.15 | arTisT, Diviiii, Ducky, Extinct, Vacancy    |
|           28 |     1048 | 2024-06-15 | Revenant          | L   | 0.860      | -            | -                | -                | -         |   -16.08 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           27 |     1086 | 2024-06-14 | Aurora Young Blud | L   | 0.853      | -            | -                | -                | -         |   -13.61 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           26 |     1125 | 2024-06-13 | Nemiga            | L   | 0.847      | -            | -                | -                | -         |    -5.25 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           25 |     1133 | 2024-06-13 | Revenant          | W   | 0.846      | 0.143        | 0.027 (0.003)    | 0.264 (0.032)    | 0 (0.000) |     9.70 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           24 |     1156 | 2024-06-12 | DMS               | W   | 0.840      | 0.143        | 0.003 (0.000)    | 0.438 (0.053)    | 0 (0.000) |    14.65 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           23 |     1178 | 2024-06-11 | 9INE              | L   | 0.833      | -            | -                | -                | -         |   -23.36 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           22 |     1372 | 2024-06-07 | B8                | L   | 0.806      | -            | -                | -                | -         |    -5.50 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           21 |     1379 | 2024-06-07 | Aurora            | L   | 0.805      | -            | -                | -                | -         |    -0.80 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           20 |     1389 | 2024-06-07 | B8                | W   | 0.805      | 0.143        | 0.165 (0.019)    | 0.935 (0.108)    | 0 (0.000) |    20.16 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           19 |     1426 | 2024-06-06 | Aurora Young Blud | L   | 0.800      | -            | -                | -                | -         |   -13.53 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           18 |     1484 | 2024-06-05 | Enterprise        | W   | 0.793      | 0.372        | 0.039 (0.012)    | 0.616 (0.182)    | 0 (0.000) |    13.41 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           17 |     1535 | 2024-06-04 | K10               | L   | 0.787      | -            | -                | -                | -         |   -19.03 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           16 |     1565 | 2024-06-03 | LEON              | W   | 0.780      | 0.372        | 0.007 (0.002)    | 0.127 (0.037)    | 0 (0.000) |     5.61 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           15 |     1616 | 2024-06-01 | V1dar             | W   | 0.767      | 0.372        | -                | 0.055 (0.016)    | 0 (0.000) |     2.85 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           14 |     1703 | 2024-05-29 | DMS               | L   | 0.747      | -            | -                | -                | -         |   -11.77 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           13 |     1911 | 2024-05-21 | Zero Tenacity     | L   | 0.691      | -            | -                | -                | -         |    -6.13 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           12 |     1949 | 2024-05-20 | Sampi             | W   | 0.684      | 0.435        | 0.027 (0.008)    | 1.000 (0.297)    | 0 (0.000) |    10.39 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           11 |     2010 | 2024-05-18 | Space             | L   | 0.670      | -            | -                | -                | -         |   -13.12 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           10 |     2123 | 2024-05-15 | Sangal            | W   | 0.651      | 0.435        | 0.219 (0.062)    | 0.866 (0.245)    | -         |    15.07 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            9 |     2177 | 2024-05-14 | B8                | L   | 0.645      | -            | -                | -                | -         |    -5.08 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            8 |     2204 | 2024-05-13 | kONO              | L   | 0.638      | -            | -                | -                | -         |   -12.73 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            7 |     2217 | 2024-05-12 | Johnny Speeds     | L   | 0.633      | -            | -                | -                | -         |    -2.54 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            6 |     2228 | 2024-05-12 | Zero Tenacity     | L   | 0.631      | -            | -                | -                | -         |    -6.90 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            5 |     2248 | 2024-05-11 | V1dar             | W   | 0.626      | -            | -                | -                | -         |     1.85 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            4 |     2276 | 2024-05-10 | ECLOT             | L   | 0.618      | -            | -                | -                | -         |    -3.91 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            3 |     3288 | 2024-04-01 | Reason            | W   | 0.358      | 0.301        | 0.002 (0.000)    | -                | 1 (0.358) |     1.08 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            2 |     3361 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.327      | -            | -                | -                | -         |    -0.15 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            1 |     3486 | 2024-03-19 | The Neighbours    | L   | 0.274      | -            | -                | -                | -         |    -6.94 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,731.15)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $2,259.00      | $2,259.00       |
| 2024-06-10 |      0.827 | $750.00        | $620.00         |
| 2024-05-13 |      0.637 | $1,000.00      | $637.08         |
| 2024-04-01 |      0.358 | $3,153.00      | $1,128.29       |
| 2024-03-19 |      0.274 | $317.00        | $86.78          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
