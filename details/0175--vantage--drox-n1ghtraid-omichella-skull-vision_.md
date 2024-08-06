### Roster Details<br />
Team Name: Vantage<br />
Roster: Drox, N1ghtraid, Omichella, SkulL, vision <br />
Global Rank: [175](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [17]( ../standings_asia.md)<br />
<br />
Final Rank Value:  645.1<br />
<br />
Final Rank Value (645.1) = Starting Rank Value (654.5) + Head To Head Adjustments (-9.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.216[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.124<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 654.5
- 400 + ( ( 0.124 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 654.5


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
|           28 |     1878 | 2024-05-22 | Rooster            | L   | 0.692      | -            | -                | -                | -         |    -6.08 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           27 |     1883 | 2024-05-22 | Rooster            | L   | 0.692      | -            | -                | -                | -         |    -6.39 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           26 |     2663 | 2024-04-22 | Mindfreak          | L   | 0.493      | -            | -                | -                | -         |    -6.97 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           25 |     2665 | 2024-04-22 | Mindfreak          | L   | 0.492      | -            | -                | -                | -         |    -7.28 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           24 |     2853 | 2024-04-17 | Arcade             | L   | 0.459      | -            | -                | -                | -         |    -7.80 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           23 |     3017 | 2024-04-10 | Arcade             | W   | 0.412      | 0.333        | 0.002 (0.000)    | 0.130 (0.018)    | 0 (0.000) |     6.09 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           22 |     3021 | 2024-04-10 | Arcade             | W   | 0.412      | 0.333        | 0.002 (0.000)    | 0.130 (0.018)    | 0 (0.000) |     6.32 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           21 |     3245 | 2024-04-03 | KZG                | W   | 0.366      | 0.333        | 0.005 (0.001)    | 0.106 (0.013)    | 0 (0.000) |     6.08 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           20 |     3252 | 2024-04-03 | KZG                | W   | 0.365      | 0.333        | 0.005 (0.001)    | 0.106 (0.013)    | 0 (0.000) |     6.28 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           19 |     3375 | 2024-03-27 | Canon Event        | W   | 0.319      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.06 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           18 |     3380 | 2024-03-27 | Canon Event        | W   | 0.319      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.13 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           17 |     3646 | 2024-03-13 | DXA                | L   | 0.226      | -            | -                | -                | -         |    -3.27 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           16 |     3652 | 2024-03-13 | DXA                | W   | 0.226      | 0.333        | 0.002 (0.000)    | 0.217 (0.016)    | 0 (0.000) |     3.91 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           15 |     3824 | 2024-03-06 | Bad News Kangaroos | L   | 0.179      | -            | -                | -                | -         |    -1.98 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           14 |     3826 | 2024-03-06 | Bad News Kangaroos | L   | 0.179      | -            | -                | -                | -         |    -2.01 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           13 |     3995 | 2024-02-27 | RKON               | W   | 0.126      | 0.333        | -                | 0.029 (0.001)    | 0 (0.000) |     1.22 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     3998 | 2024-02-27 | RKON               | L   | 0.125      | -            | -                | -                | -         |    -2.76 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     4098 | 2024-02-22 | Bad News Kangaroos | L   | 0.092      | -            | -                | -                | -         |    -1.04 | Drox, Omichella, SkulL, viridian, vision   |
|           10 |     4100 | 2024-02-21 | Rooster            | L   | 0.091      | -            | -                | -                | -         |    -0.96 | Drox, Omichella, SkulL, viridian, vision   |
|            9 |     4134 | 2024-02-20 | Arcade             | W   | 0.085      | 0.143        | 0.002 (0.000)    | 0.130 (0.002)    | 0 (0.000) |     1.39 | Drox, Omichella, SkulL, viridian, vision   |
|            8 |     4154 | 2024-02-20 | Mindfreak          | W   | 0.079      | 0.143        | 0.004 (0.000)    | 0.218 (0.002)    | 0 (0.000) |     1.36 | Drox, Omichella, SkulL, viridian, vision   |
|            7 |     4156 | 2024-02-20 | Blitz              | W   | 0.079      | -            | -                | -                | -         |     0.49 | Drox, Omichella, SkulL, viridian, vision   |
|            6 |     4198 | 2024-02-18 | Mindfreak          | L   | 0.066      | -            | -                | -                | -         |    -0.95 | Drox, Omichella, SkulL, viridian, vision   |
|            5 |     4199 | 2024-02-18 | Mindfreak          | L   | 0.066      | -            | -                | -                | -         |    -0.95 | Drox, Omichella, SkulL, viridian, vision   |
|            4 |     4202 | 2024-02-18 | LE-LUX             | W   | 0.066      | -            | -                | -                | -         |     0.40 | Drox, Omichella, SkulL, viridian, vision   |
|            3 |     4260 | 2024-02-15 | sunday school      | L   | 0.051      | -            | -                | -                | -         |    -0.86 | damyo, Omichella, SkulL, viridian, vision  |
|            2 |     4284 | 2024-02-15 | DXA                | W   | 0.046      | 0.143        | 0.002 (0.000)    | 0.217 (0.001)    | -         |     0.79 | damyo, Omichella, SkulL, viridian, vision  |
|            1 |     4286 | 2024-02-14 | KZG                | L   | 0.044      | -            | -                | -                | -         |    -0.60 | damyo, Omichella, SkulL, viridian, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($649.04)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
