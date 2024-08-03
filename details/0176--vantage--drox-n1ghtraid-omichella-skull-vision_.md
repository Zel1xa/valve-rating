### Roster Details<br />
Team Name: Vantage<br />
Roster: Drox, N1ghtraid, Omichella, SkulL, vision <br />
Global Rank: [176](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [18]( ../standings_asia.md)<br />
<br />
Final Rank Value:  645.3<br />
<br />
Final Rank Value (645.3) = Starting Rank Value (654.8) + Head To Head Adjustments (-9.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.125<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 654.8
- 400 + ( ( 0.125 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 654.8


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
|           27 |     1744 | 2024-05-22 | Rooster            | L   | 0.711      | -            | -                | -                | -         |    -6.20 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           26 |     1749 | 2024-05-22 | Rooster            | L   | 0.711      | -            | -                | -                | -         |    -6.52 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           25 |     2526 | 2024-04-22 | Mindfreak          | L   | 0.512      | -            | -                | -                | -         |    -7.30 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           24 |     2528 | 2024-04-22 | Mindfreak          | L   | 0.511      | -            | -                | -                | -         |    -7.63 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           23 |     2716 | 2024-04-17 | Arcade             | L   | 0.478      | -            | -                | -                | -         |    -8.05 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           22 |     2880 | 2024-04-10 | Arcade             | W   | 0.431      | 0.333        | 0.002 (0.000)    | 0.142 (0.020)    | 0 (0.000) |     6.44 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           21 |     2884 | 2024-04-10 | Arcade             | W   | 0.431      | 0.333        | 0.002 (0.000)    | 0.142 (0.020)    | 0 (0.000) |     6.69 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           20 |     3108 | 2024-04-03 | KZG                | W   | 0.385      | 0.333        | 0.005 (0.001)    | 0.116 (0.015)    | 0 (0.000) |     6.00 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           19 |     3115 | 2024-04-03 | KZG                | W   | 0.384      | 0.333        | 0.005 (0.001)    | 0.116 (0.015)    | 0 (0.000) |     6.20 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           18 |     3236 | 2024-03-27 | Canon Event        | W   | 0.338      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.21 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           17 |     3241 | 2024-03-27 | Canon Event        | W   | 0.338      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.29 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           16 |     3502 | 2024-03-13 | DXA                | L   | 0.245      | -            | -                | -                | -         |    -3.56 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           15 |     3508 | 2024-03-13 | DXA                | W   | 0.245      | 0.333        | 0.002 (0.000)    | 0.235 (0.019)    | 0 (0.000) |     4.23 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           14 |     3679 | 2024-03-06 | Bad News Kangaroos | L   | 0.198      | -            | -                | -                | -         |    -2.17 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           13 |     3681 | 2024-03-06 | Bad News Kangaroos | L   | 0.198      | -            | -                | -                | -         |    -2.20 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     3850 | 2024-02-27 | RKON               | W   | 0.145      | 0.333        | -                | 0.034 (0.002)    | 0 (0.000) |     1.41 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     3852 | 2024-02-27 | RKON               | L   | 0.144      | -            | -                | -                | -         |    -3.17 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           10 |     3953 | 2024-02-22 | Bad News Kangaroos | L   | 0.111      | -            | -                | -                | -         |    -1.25 | Drox, Omichella, SkulL, viridian, vision   |
|            9 |     3955 | 2024-02-21 | Rooster            | L   | 0.110      | -            | -                | -                | -         |    -1.17 | Drox, Omichella, SkulL, viridian, vision   |
|            8 |     3989 | 2024-02-20 | Arcade             | W   | 0.104      | 0.143        | 0.002 (0.000)    | 0.142 (0.002)    | 0 (0.000) |     1.71 | Drox, Omichella, SkulL, viridian, vision   |
|            7 |     4009 | 2024-02-20 | Mindfreak          | W   | 0.098      | 0.143        | 0.004 (0.000)    | 0.214 (0.003)    | 0 (0.000) |     1.67 | Drox, Omichella, SkulL, viridian, vision   |
|            6 |     4011 | 2024-02-20 | Blitz              | W   | 0.098      | -            | -                | -                | -         |     0.60 | Drox, Omichella, SkulL, viridian, vision   |
|            5 |     4053 | 2024-02-18 | Mindfreak          | L   | 0.085      | -            | -                | -                | -         |    -1.24 | Drox, Omichella, SkulL, viridian, vision   |
|            4 |     4056 | 2024-02-18 | LE-LUX             | W   | 0.085      | -            | -                | -                | -         |     0.52 | Drox, Omichella, SkulL, viridian, vision   |
|            3 |     4114 | 2024-02-15 | sunday school      | L   | 0.070      | -            | -                | -                | -         |    -1.17 | damyo, Omichella, SkulL, viridian, vision  |
|            2 |     4138 | 2024-02-15 | DXA                | W   | 0.065      | 0.143        | 0.002 (0.000)    | 0.235 (0.002)    | -         |     1.12 | damyo, Omichella, SkulL, viridian, vision  |
|            1 |     4140 | 2024-02-14 | KZG                | L   | 0.064      | -            | -                | -                | -         |    -0.90 | damyo, Omichella, SkulL, viridian, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($664.26)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
