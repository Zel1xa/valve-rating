### Roster Details<br />
Team Name: Vantage<br />
Roster: Drox, N1ghtraid, Omichella, SkulL, vision <br />
Global Rank: [176](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [18]( ../standings_asia.md)<br />
<br />
Final Rank Value:  645.4<br />
<br />
Final Rank Value (645.4) = Starting Rank Value (654.2) + Head To Head Adjustments (-8.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.124<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 654.2
- 400 + ( ( 0.124 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 654.2


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
|           27 |     1808 | 2024-05-22 | Rooster            | L   | 0.710      | -            | -                | -                | -         |    -6.18 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           26 |     1813 | 2024-05-22 | Rooster            | L   | 0.709      | -            | -                | -                | -         |    -6.50 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           25 |     2592 | 2024-04-22 | Mindfreak          | L   | 0.510      | -            | -                | -                | -         |    -7.24 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           24 |     2594 | 2024-04-22 | Mindfreak          | L   | 0.510      | -            | -                | -                | -         |    -7.57 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           23 |     2782 | 2024-04-17 | Arcade             | L   | 0.476      | -            | -                | -                | -         |    -8.12 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           22 |     2946 | 2024-04-10 | Arcade             | W   | 0.430      | 0.333        | 0.002 (0.000)    | 0.137 (0.020)    | 0 (0.000) |     6.33 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           21 |     2950 | 2024-04-10 | Arcade             | W   | 0.429      | 0.333        | 0.002 (0.000)    | 0.137 (0.020)    | 0 (0.000) |     6.57 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           20 |     3174 | 2024-04-03 | KZG                | W   | 0.383      | 0.333        | 0.005 (0.001)    | 0.112 (0.014)    | 0 (0.000) |     6.33 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           19 |     3181 | 2024-04-03 | KZG                | W   | 0.383      | 0.333        | 0.005 (0.001)    | 0.112 (0.014)    | 0 (0.000) |     6.55 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           18 |     3304 | 2024-03-27 | Canon Event        | W   | 0.337      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.19 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           17 |     3309 | 2024-03-27 | Canon Event        | W   | 0.336      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.27 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           16 |     3574 | 2024-03-13 | DXA                | L   | 0.243      | -            | -                | -                | -         |    -3.54 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           15 |     3580 | 2024-03-13 | DXA                | W   | 0.243      | 0.333        | 0.002 (0.000)    | 0.227 (0.018)    | 0 (0.000) |     4.20 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           14 |     3752 | 2024-03-06 | Bad News Kangaroos | L   | 0.197      | -            | -                | -                | -         |    -2.16 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           13 |     3754 | 2024-03-06 | Bad News Kangaroos | L   | 0.196      | -            | -                | -                | -         |    -2.19 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     3923 | 2024-02-27 | RKON               | W   | 0.143      | 0.333        | -                | 0.032 (0.002)    | 0 (0.000) |     1.39 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     3926 | 2024-02-27 | RKON               | L   | 0.143      | -            | -                | -                | -         |    -3.14 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           10 |     4026 | 2024-02-22 | Bad News Kangaroos | L   | 0.110      | -            | -                | -                | -         |    -1.23 | Drox, Omichella, SkulL, viridian, vision   |
|            9 |     4028 | 2024-02-21 | Rooster            | L   | 0.108      | -            | -                | -                | -         |    -1.15 | Drox, Omichella, SkulL, viridian, vision   |
|            8 |     4062 | 2024-02-20 | Arcade             | W   | 0.102      | 0.143        | 0.002 (0.000)    | 0.137 (0.002)    | 0 (0.000) |     1.68 | Drox, Omichella, SkulL, viridian, vision   |
|            7 |     4082 | 2024-02-20 | Mindfreak          | W   | 0.097      | 0.143        | 0.004 (0.000)    | 0.227 (0.003)    | 0 (0.000) |     1.65 | Drox, Omichella, SkulL, viridian, vision   |
|            6 |     4084 | 2024-02-20 | Blitz              | W   | 0.096      | -            | -                | -                | -         |     0.59 | Drox, Omichella, SkulL, viridian, vision   |
|            5 |     4126 | 2024-02-18 | Mindfreak          | L   | 0.083      | -            | -                | -                | -         |    -1.21 | Drox, Omichella, SkulL, viridian, vision   |
|            4 |     4129 | 2024-02-18 | LE-LUX             | W   | 0.083      | -            | -                | -                | -         |     0.51 | Drox, Omichella, SkulL, viridian, vision   |
|            3 |     4187 | 2024-02-15 | sunday school      | L   | 0.068      | -            | -                | -                | -         |    -1.14 | damyo, Omichella, SkulL, viridian, vision  |
|            2 |     4211 | 2024-02-15 | DXA                | W   | 0.063      | 0.143        | 0.002 (0.000)    | 0.227 (0.002)    | -         |     1.09 | damyo, Omichella, SkulL, viridian, vision  |
|            1 |     4213 | 2024-02-14 | KZG                | L   | 0.062      | -            | -                | -                | -         |    -0.83 | damyo, Omichella, SkulL, viridian, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($662.89)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
