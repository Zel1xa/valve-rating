### Roster Details<br />
Team Name: Verdant<br />
Roster: arTisT, Diviiii, Extinct, Girafffe, Vacancy<br />
Global Rank: [100](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
<br />
Final Rank Value:  864.7<br />
<br />
Final Rank Value (864.7) = Starting Rank Value (956.9) + Head To Head Adjustments (-92.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.354[<sup>1</sup>](#table2)
- Bounty Collected: 0.344[<sup>2</sup>](#table1)
- Opponent Network: 0.109[<sup>2</sup>](#table1)
- LAN Wins: 0.275[<sup>2</sup>](#table1)

The average of these factors is 0.270<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 956.9
- 400 + ( ( 0.270 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 956.9


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
|           35 |      376 | 2024-07-21 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | 0.039 (0.011)    | 1 (1.000) |     9.31 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           34 |      403 | 2024-07-20 | Invictum          | W   | 1.000      | 0.296        | 0.003 (0.001)    | -                | 1 (1.000) |     9.45 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           33 |      557 | 2024-07-17 | PERA              | L   | 1.000      | -            | -                | -                | -         |    -9.66 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           32 |      678 | 2024-07-15 | Revenant          | W   | 1.000      | 0.333        | 0.027 (0.009)    | 0.263 (0.088)    | 0 (0.000) |    16.75 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           31 |      732 | 2024-07-12 | Revenant          | L   | 1.000      | -            | -                | -                | -         |   -14.65 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           30 |      813 | 2024-07-08 | Rebels            | L   | 1.000      | -            | -                | -                | -         |    -9.59 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           29 |      906 | 2024-06-16 | UNiTY             | L   | 0.892      | -            | -                | -                | -         |   -10.89 | arTisT, Diviiii, Ducky, Extinct, Vacancy    |
|           28 |      915 | 2024-06-15 | Revenant          | L   | 0.888      | -            | -                | -                | -         |   -16.71 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           27 |      947 | 2024-06-14 | Aurora Young Blud | L   | 0.882      | -            | -                | -                | -         |   -13.98 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           26 |      985 | 2024-06-13 | Nemiga            | L   | 0.875      | -            | -                | -                | -         |    -5.83 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           25 |      993 | 2024-06-13 | Revenant          | W   | 0.874      | 0.143        | 0.027 (0.003)    | 0.263 (0.033)    | 0 (0.000) |     9.86 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           24 |     1016 | 2024-06-12 | DMS               | W   | 0.868      | 0.143        | 0.003 (0.000)    | 0.447 (0.055)    | 0 (0.000) |    14.80 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           23 |     1039 | 2024-06-11 | 9INE              | L   | 0.861      | -            | -                | -                | -         |   -24.10 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           22 |     1243 | 2024-06-07 | B8                | L   | 0.835      | -            | -                | -                | -         |    -6.08 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           21 |     1250 | 2024-06-07 | Aurora            | L   | 0.834      | -            | -                | -                | -         |    -0.87 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           20 |     1260 | 2024-06-07 | B8                | W   | 0.833      | 0.143        | 0.168 (0.020)    | 0.878 (0.105)    | 0 (0.000) |    20.46 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           19 |     1299 | 2024-06-06 | Aurora Young Blud | L   | 0.828      | -            | -                | -                | -         |   -14.77 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           18 |     1359 | 2024-06-05 | Enterprise        | W   | 0.822      | 0.372        | 0.040 (0.012)    | 0.622 (0.190)    | 0 (0.000) |    13.52 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           17 |     1411 | 2024-06-04 | K10               | L   | 0.815      | -            | -                | -                | -         |   -19.79 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           16 |     1441 | 2024-06-03 | LEON              | W   | 0.808      | 0.372        | 0.007 (0.002)    | 0.131 (0.039)    | 0 (0.000) |     5.72 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           15 |     1492 | 2024-06-01 | V1dar             | W   | 0.795      | 0.372        | -                | 0.058 (0.017)    | 0 (0.000) |     2.93 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           14 |     1580 | 2024-05-29 | DMS               | L   | 0.775      | -            | -                | -                | -         |   -12.41 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           13 |     1805 | 2024-05-21 | Zero Tenacity     | L   | 0.719      | -            | -                | -                | -         |    -7.25 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           12 |     1848 | 2024-05-20 | Sampi             | W   | 0.713      | 0.435        | 0.028 (0.009)    | 1.000 (0.310)    | -         |    10.38 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           11 |     1915 | 2024-05-18 | Space             | L   | 0.699      | -            | -                | -                | -         |   -13.69 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           10 |     2032 | 2024-05-15 | Sangal            | W   | 0.680      | 0.435        | 0.221 (0.065)    | 0.823 (0.243)    | -         |    15.24 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            9 |     2088 | 2024-05-14 | B8                | L   | 0.674      | -            | -                | -                | -         |    -5.58 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            8 |     2118 | 2024-05-13 | kONO              | L   | 0.666      | -            | -                | -                | -         |   -12.97 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            7 |     2131 | 2024-05-12 | Johnny Speeds     | L   | 0.662      | -            | -                | -                | -         |    -2.76 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            6 |     2142 | 2024-05-12 | Zero Tenacity     | L   | 0.660      | -            | -                | -                | -         |    -7.68 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            5 |     2162 | 2024-05-11 | V1dar             | W   | 0.655      | -            | -                | -                | -         |     1.88 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            4 |     2190 | 2024-05-10 | ECLOT             | L   | 0.646      | -            | -                | -                | -         |    -6.12 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|            3 |     3226 | 2024-04-01 | Reason            | W   | 0.386      | -            | -                | -                | 1 (0.386) |     1.11 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            2 |     3300 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.355      | -            | -                | -                | -         |    -0.49 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            1 |     3429 | 2024-03-19 | The Neighbours    | L   | 0.302      | -            | -                | -                | -         |    -7.68 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,879.78)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $2,259.00      | $2,259.00       |
| 2024-06-10 |      0.855 | $750.00        | $641.35         |
| 2024-05-13 |      0.666 | $1,000.00      | $665.56         |
| 2024-04-01 |      0.386 | $3,153.00      | $1,218.07       |
| 2024-03-19 |      0.302 | $317.00        | $95.80          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
