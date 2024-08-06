### Roster Details<br />
Team Name: Vantage<br />
Roster: Drox, N1ghtraid, Omichella, SkulL, vision <br />
Global Rank: [175](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [18]( ../standings_asia.md)<br />
<br />
Final Rank Value:  645.7<br />
<br />
Final Rank Value (645.7) = Starting Rank Value (654.0) + Head To Head Adjustments (-8.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.216[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.124<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 654.0
- 400 + ( ( 0.124 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 654.0


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
|           28 |     1876 | 2024-05-22 | Rooster            | L   | 0.693      | -            | -                | -                | -         |    -6.01 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           27 |     1881 | 2024-05-22 | Rooster            | L   | 0.693      | -            | -                | -                | -         |    -6.32 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           26 |     2661 | 2024-04-22 | Mindfreak          | L   | 0.494      | -            | -                | -                | -         |    -6.84 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           25 |     2663 | 2024-04-22 | Mindfreak          | L   | 0.493      | -            | -                | -                | -         |    -7.14 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           24 |     2851 | 2024-04-17 | Arcade             | L   | 0.460      | -            | -                | -                | -         |    -7.63 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           23 |     3015 | 2024-04-10 | Arcade             | W   | 0.413      | 0.333        | 0.002 (0.000)    | 0.133 (0.018)    | 0 (0.000) |     6.28 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           22 |     3019 | 2024-04-10 | Arcade             | W   | 0.413      | 0.333        | 0.002 (0.000)    | 0.133 (0.018)    | 0 (0.000) |     6.51 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           21 |     3243 | 2024-04-03 | KZG                | W   | 0.367      | 0.333        | 0.005 (0.001)    | 0.109 (0.013)    | 0 (0.000) |     6.11 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           20 |     3250 | 2024-04-03 | KZG                | W   | 0.366      | 0.333        | 0.005 (0.001)    | 0.109 (0.013)    | 0 (0.000) |     6.30 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           19 |     3373 | 2024-03-27 | Canon Event        | W   | 0.320      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.07 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           18 |     3378 | 2024-03-27 | Canon Event        | W   | 0.320      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.14 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           17 |     3644 | 2024-03-13 | DXA                | L   | 0.227      | -            | -                | -                | -         |    -3.20 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           16 |     3650 | 2024-03-13 | DXA                | W   | 0.227      | 0.333        | 0.002 (0.000)    | 0.222 (0.017)    | 0 (0.000) |     4.01 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           15 |     3822 | 2024-03-06 | Bad News Kangaroos | L   | 0.180      | -            | -                | -                | -         |    -1.86 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           14 |     3824 | 2024-03-06 | Bad News Kangaroos | L   | 0.180      | -            | -                | -                | -         |    -1.89 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           13 |     3993 | 2024-02-27 | RKON               | W   | 0.127      | 0.333        | -                | 0.030 (0.001)    | 0 (0.000) |     1.24 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     3996 | 2024-02-27 | RKON               | L   | 0.126      | -            | -                | -                | -         |    -2.77 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     4096 | 2024-02-22 | Bad News Kangaroos | L   | 0.093      | -            | -                | -                | -         |    -1.60 | Drox, Omichella, SkulL, viridian, vision   |
|           10 |     4098 | 2024-02-21 | Rooster            | L   | 0.092      | -            | -                | -                | -         |    -0.96 | Drox, Omichella, SkulL, viridian, vision   |
|            9 |     4132 | 2024-02-20 | Arcade             | W   | 0.086      | 0.143        | 0.002 (0.000)    | 0.133 (0.002)    | 0 (0.000) |     1.45 | Drox, Omichella, SkulL, viridian, vision   |
|            8 |     4152 | 2024-02-20 | Mindfreak          | W   | 0.080      | 0.143        | 0.004 (0.000)    | 0.223 (0.003)    | 0 (0.000) |     1.40 | Drox, Omichella, SkulL, viridian, vision   |
|            7 |     4154 | 2024-02-20 | Blitz              | W   | 0.080      | -            | -                | -                | -         |     0.49 | Drox, Omichella, SkulL, viridian, vision   |
|            6 |     4196 | 2024-02-18 | Mindfreak          | L   | 0.067      | -            | -                | -                | -         |    -0.94 | Drox, Omichella, SkulL, viridian, vision   |
|            5 |     4197 | 2024-02-18 | Mindfreak          | L   | 0.067      | -            | -                | -                | -         |    -0.94 | Drox, Omichella, SkulL, viridian, vision   |
|            4 |     4200 | 2024-02-18 | LE-LUX             | W   | 0.066      | -            | -                | -                | -         |     0.41 | Drox, Omichella, SkulL, viridian, vision   |
|            3 |     4258 | 2024-02-15 | sunday school      | L   | 0.052      | -            | -                | -                | -         |    -0.87 | damyo, Omichella, SkulL, viridian, vision  |
|            2 |     4282 | 2024-02-15 | DXA                | W   | 0.047      | 0.143        | 0.002 (0.000)    | 0.222 (0.001)    | -         |     0.82 | damyo, Omichella, SkulL, viridian, vision  |
|            1 |     4284 | 2024-02-14 | KZG                | L   | 0.045      | -            | -                | -                | -         |    -0.61 | damyo, Omichella, SkulL, viridian, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($649.78)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
