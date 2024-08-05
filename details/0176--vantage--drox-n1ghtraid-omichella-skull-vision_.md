### Roster Details<br />
Team Name: Vantage<br />
Roster: Drox, N1ghtraid, Omichella, SkulL, vision <br />
Global Rank: [176](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [18]( ../standings_asia.md)<br />
<br />
Final Rank Value:  645.7<br />
<br />
Final Rank Value (645.7) = Starting Rank Value (654.1) + Head To Head Adjustments (-8.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.216[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.124<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 654.1
- 400 + ( ( 0.124 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 654.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |     1869 | 2024-05-22 | Rooster            | L   | 0.698      | -            | -                | -                | -         |    -6.03 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           27 |     1874 | 2024-05-22 | Rooster            | L   | 0.698      | -            | -                | -                | -         |    -6.34 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           26 |     2654 | 2024-04-22 | Mindfreak          | L   | 0.498      | -            | -                | -                | -         |    -6.90 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           25 |     2656 | 2024-04-22 | Mindfreak          | L   | 0.498      | -            | -                | -                | -         |    -7.20 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           24 |     2844 | 2024-04-17 | Arcade             | L   | 0.465      | -            | -                | -                | -         |    -7.71 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           23 |     3008 | 2024-04-10 | Arcade             | W   | 0.418      | 0.333        | 0.002 (0.000)    | 0.134 (0.019)    | 0 (0.000) |     6.35 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           22 |     3012 | 2024-04-10 | Arcade             | W   | 0.418      | 0.333        | 0.002 (0.000)    | 0.134 (0.019)    | 0 (0.000) |     6.59 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           21 |     3236 | 2024-04-03 | KZG                | W   | 0.372      | 0.333        | 0.005 (0.001)    | 0.109 (0.014)    | 0 (0.000) |     6.18 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           20 |     3243 | 2024-04-03 | KZG                | W   | 0.371      | 0.333        | 0.005 (0.001)    | 0.109 (0.014)    | 0 (0.000) |     6.38 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           19 |     3366 | 2024-03-27 | Canon Event        | W   | 0.325      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.11 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           18 |     3371 | 2024-03-27 | Canon Event        | W   | 0.325      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.19 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           17 |     3637 | 2024-03-13 | DXA                | L   | 0.232      | -            | -                | -                | -         |    -3.26 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           16 |     3643 | 2024-03-13 | DXA                | W   | 0.231      | 0.333        | 0.002 (0.000)    | 0.222 (0.017)    | 0 (0.000) |     4.09 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           15 |     3815 | 2024-03-06 | Bad News Kangaroos | L   | 0.185      | -            | -                | -                | -         |    -1.90 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           14 |     3817 | 2024-03-06 | Bad News Kangaroos | L   | 0.185      | -            | -                | -                | -         |    -1.93 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           13 |     3986 | 2024-02-27 | RKON               | W   | 0.131      | 0.333        | -                | 0.030 (0.001)    | 0 (0.000) |     1.28 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     3989 | 2024-02-27 | RKON               | L   | 0.131      | -            | -                | -                | -         |    -2.88 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     4089 | 2024-02-22 | Bad News Kangaroos | L   | 0.098      | -            | -                | -                | -         |    -1.68 | Drox, Omichella, SkulL, viridian, vision   |
|           10 |     4091 | 2024-02-21 | Rooster            | L   | 0.097      | -            | -                | -                | -         |    -1.01 | Drox, Omichella, SkulL, viridian, vision   |
|            9 |     4125 | 2024-02-20 | Arcade             | W   | 0.091      | 0.143        | 0.002 (0.000)    | 0.134 (0.002)    | 0 (0.000) |     1.53 | Drox, Omichella, SkulL, viridian, vision   |
|            8 |     4145 | 2024-02-20 | Mindfreak          | W   | 0.085      | 0.143        | 0.004 (0.000)    | 0.224 (0.003)    | 0 (0.000) |     1.49 | Drox, Omichella, SkulL, viridian, vision   |
|            7 |     4147 | 2024-02-20 | Blitz              | W   | 0.085      | -            | -                | -                | -         |     0.52 | Drox, Omichella, SkulL, viridian, vision   |
|            6 |     4189 | 2024-02-18 | Mindfreak          | L   | 0.071      | -            | -                | -                | -         |    -1.01 | Drox, Omichella, SkulL, viridian, vision   |
|            5 |     4190 | 2024-02-18 | Mindfreak          | L   | 0.071      | -            | -                | -                | -         |    -1.01 | Drox, Omichella, SkulL, viridian, vision   |
|            4 |     4193 | 2024-02-18 | LE-LUX             | W   | 0.071      | -            | -                | -                | -         |     0.44 | Drox, Omichella, SkulL, viridian, vision   |
|            3 |     4251 | 2024-02-15 | sunday school      | L   | 0.057      | -            | -                | -                | -         |    -0.95 | damyo, Omichella, SkulL, viridian, vision  |
|            2 |     4275 | 2024-02-15 | DXA                | W   | 0.051      | 0.143        | 0.002 (0.000)    | 0.222 (0.002)    | -         |     0.90 | damyo, Omichella, SkulL, viridian, vision  |
|            1 |     4277 | 2024-02-14 | KZG                | L   | 0.050      | -            | -                | -                | -         |    -0.67 | damyo, Omichella, SkulL, viridian, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($653.56)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
