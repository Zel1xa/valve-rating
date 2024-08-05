### Roster Details<br />
Team Name: Vantage<br />
Roster: Drox, N1ghtraid, Omichella, SkulL, vision <br />
Global Rank: [177](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [18]( ../standings_asia.md)<br />
<br />
Final Rank Value:  645.5<br />
<br />
Final Rank Value (645.5) = Starting Rank Value (654.0) + Head To Head Adjustments (-8.5)<br />

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
- 400 + ( ( 0.124 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 654.0


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
|           28 |     1848 | 2024-05-22 | Rooster            | L   | 0.702      | -            | -                | -                | -         |    -6.05 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           27 |     1853 | 2024-05-22 | Rooster            | L   | 0.702      | -            | -                | -                | -         |    -6.36 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           26 |     2633 | 2024-04-22 | Mindfreak          | L   | 0.503      | -            | -                | -                | -         |    -6.95 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           25 |     2635 | 2024-04-22 | Mindfreak          | L   | 0.502      | -            | -                | -                | -         |    -7.26 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           24 |     2823 | 2024-04-17 | Arcade             | L   | 0.469      | -            | -                | -                | -         |    -7.79 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           23 |     2987 | 2024-04-10 | Arcade             | W   | 0.422      | 0.333        | 0.002 (0.000)    | 0.136 (0.019)    | 0 (0.000) |     6.42 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           22 |     2991 | 2024-04-10 | Arcade             | W   | 0.422      | 0.333        | 0.002 (0.000)    | 0.136 (0.019)    | 0 (0.000) |     6.66 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           21 |     3215 | 2024-04-03 | KZG                | W   | 0.376      | 0.333        | 0.005 (0.001)    | 0.111 (0.014)    | 0 (0.000) |     6.25 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           20 |     3222 | 2024-04-03 | KZG                | W   | 0.376      | 0.333        | 0.005 (0.001)    | 0.111 (0.014)    | 0 (0.000) |     6.45 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           19 |     3345 | 2024-03-27 | Canon Event        | W   | 0.329      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.15 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           18 |     3350 | 2024-03-27 | Canon Event        | W   | 0.329      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.23 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           17 |     3616 | 2024-03-13 | DXA                | L   | 0.236      | -            | -                | -                | -         |    -3.33 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           16 |     3622 | 2024-03-13 | DXA                | W   | 0.236      | 0.333        | 0.002 (0.000)    | 0.226 (0.018)    | 0 (0.000) |     4.17 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           15 |     3794 | 2024-03-06 | Bad News Kangaroos | L   | 0.189      | -            | -                | -                | -         |    -1.94 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           14 |     3796 | 2024-03-06 | Bad News Kangaroos | L   | 0.189      | -            | -                | -                | -         |    -1.97 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           13 |     3965 | 2024-02-27 | RKON               | W   | 0.136      | 0.333        | -                | 0.031 (0.001)    | 0 (0.000) |     1.33 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     3968 | 2024-02-27 | RKON               | L   | 0.136      | -            | -                | -                | -         |    -2.97 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     4068 | 2024-02-22 | Bad News Kangaroos | L   | 0.102      | -            | -                | -                | -         |    -1.76 | Drox, Omichella, SkulL, viridian, vision   |
|           10 |     4070 | 2024-02-21 | Rooster            | L   | 0.101      | -            | -                | -                | -         |    -1.05 | Drox, Omichella, SkulL, viridian, vision   |
|            9 |     4104 | 2024-02-20 | Arcade             | W   | 0.095      | 0.143        | 0.002 (0.000)    | 0.136 (0.002)    | 0 (0.000) |     1.61 | Drox, Omichella, SkulL, viridian, vision   |
|            8 |     4124 | 2024-02-20 | Mindfreak          | W   | 0.089      | 0.143        | 0.004 (0.000)    | 0.227 (0.003)    | 0 (0.000) |     1.56 | Drox, Omichella, SkulL, viridian, vision   |
|            7 |     4126 | 2024-02-20 | Blitz              | W   | 0.089      | -            | -                | -                | -         |     0.55 | Drox, Omichella, SkulL, viridian, vision   |
|            6 |     4168 | 2024-02-18 | Mindfreak          | L   | 0.076      | -            | -                | -                | -         |    -1.07 | Drox, Omichella, SkulL, viridian, vision   |
|            5 |     4169 | 2024-02-18 | Mindfreak          | L   | 0.076      | -            | -                | -                | -         |    -1.07 | Drox, Omichella, SkulL, viridian, vision   |
|            4 |     4172 | 2024-02-18 | LE-LUX             | W   | 0.076      | -            | -                | -                | -         |     0.47 | Drox, Omichella, SkulL, viridian, vision   |
|            3 |     4230 | 2024-02-15 | sunday school      | L   | 0.061      | -            | -                | -                | -         |    -1.02 | damyo, Omichella, SkulL, viridian, vision  |
|            2 |     4254 | 2024-02-15 | DXA                | W   | 0.056      | 0.143        | 0.002 (0.000)    | 0.226 (0.002)    | -         |     0.98 | damyo, Omichella, SkulL, viridian, vision  |
|            1 |     4256 | 2024-02-14 | KZG                | L   | 0.055      | -            | -                | -                | -         |    -0.73 | damyo, Omichella, SkulL, viridian, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($657.11)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
