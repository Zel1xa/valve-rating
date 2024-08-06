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
|           28 |     1872 | 2024-05-22 | Rooster            | L   | 0.696      | -            | -                | -                | -         |    -6.02 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           27 |     1877 | 2024-05-22 | Rooster            | L   | 0.696      | -            | -                | -                | -         |    -6.33 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           26 |     2657 | 2024-04-22 | Mindfreak          | L   | 0.496      | -            | -                | -                | -         |    -6.87 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           25 |     2659 | 2024-04-22 | Mindfreak          | L   | 0.496      | -            | -                | -                | -         |    -7.17 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           24 |     2847 | 2024-04-17 | Arcade             | L   | 0.463      | -            | -                | -                | -         |    -7.67 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           23 |     3011 | 2024-04-10 | Arcade             | W   | 0.416      | 0.333        | 0.002 (0.000)    | 0.134 (0.019)    | 0 (0.000) |     6.32 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           22 |     3015 | 2024-04-10 | Arcade             | W   | 0.416      | 0.333        | 0.002 (0.000)    | 0.134 (0.019)    | 0 (0.000) |     6.55 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           21 |     3239 | 2024-04-03 | KZG                | W   | 0.369      | 0.333        | 0.005 (0.001)    | 0.109 (0.013)    | 0 (0.000) |     6.14 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           20 |     3246 | 2024-04-03 | KZG                | W   | 0.369      | 0.333        | 0.005 (0.001)    | 0.109 (0.013)    | 0 (0.000) |     6.34 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           19 |     3369 | 2024-03-27 | Canon Event        | W   | 0.323      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.09 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           18 |     3374 | 2024-03-27 | Canon Event        | W   | 0.323      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.17 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           17 |     3640 | 2024-03-13 | DXA                | L   | 0.229      | -            | -                | -                | -         |    -3.23 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           16 |     3646 | 2024-03-13 | DXA                | W   | 0.229      | 0.333        | 0.002 (0.000)    | 0.222 (0.017)    | 0 (0.000) |     4.05 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           15 |     3818 | 2024-03-06 | Bad News Kangaroos | L   | 0.183      | -            | -                | -                | -         |    -1.89 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           14 |     3820 | 2024-03-06 | Bad News Kangaroos | L   | 0.182      | -            | -                | -                | -         |    -1.91 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           13 |     3989 | 2024-02-27 | RKON               | W   | 0.129      | 0.333        | -                | 0.030 (0.001)    | 0 (0.000) |     1.26 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     3992 | 2024-02-27 | RKON               | L   | 0.129      | -            | -                | -                | -         |    -2.83 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     4092 | 2024-02-22 | Bad News Kangaroos | L   | 0.096      | -            | -                | -                | -         |    -1.65 | Drox, Omichella, SkulL, viridian, vision   |
|           10 |     4094 | 2024-02-21 | Rooster            | L   | 0.095      | -            | -                | -                | -         |    -0.99 | Drox, Omichella, SkulL, viridian, vision   |
|            9 |     4128 | 2024-02-20 | Arcade             | W   | 0.088      | 0.143        | 0.002 (0.000)    | 0.134 (0.002)    | 0 (0.000) |     1.49 | Drox, Omichella, SkulL, viridian, vision   |
|            8 |     4148 | 2024-02-20 | Mindfreak          | W   | 0.083      | 0.143        | 0.004 (0.000)    | 0.223 (0.003)    | 0 (0.000) |     1.45 | Drox, Omichella, SkulL, viridian, vision   |
|            7 |     4150 | 2024-02-20 | Blitz              | W   | 0.083      | -            | -                | -                | -         |     0.51 | Drox, Omichella, SkulL, viridian, vision   |
|            6 |     4192 | 2024-02-18 | Mindfreak          | L   | 0.069      | -            | -                | -                | -         |    -0.98 | Drox, Omichella, SkulL, viridian, vision   |
|            5 |     4193 | 2024-02-18 | Mindfreak          | L   | 0.069      | -            | -                | -                | -         |    -0.97 | Drox, Omichella, SkulL, viridian, vision   |
|            4 |     4196 | 2024-02-18 | LE-LUX             | W   | 0.069      | -            | -                | -                | -         |     0.42 | Drox, Omichella, SkulL, viridian, vision   |
|            3 |     4254 | 2024-02-15 | sunday school      | L   | 0.055      | -            | -                | -                | -         |    -0.91 | damyo, Omichella, SkulL, viridian, vision  |
|            2 |     4278 | 2024-02-15 | DXA                | W   | 0.049      | 0.143        | 0.002 (0.000)    | 0.222 (0.002)    | -         |     0.86 | damyo, Omichella, SkulL, viridian, vision  |
|            1 |     4280 | 2024-02-14 | KZG                | L   | 0.048      | -            | -                | -                | -         |    -0.65 | damyo, Omichella, SkulL, viridian, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($651.78)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
