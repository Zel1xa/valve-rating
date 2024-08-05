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
|           28 |     1870 | 2024-05-22 | Rooster            | L   | 0.698      | -            | -                | -                | -         |    -6.03 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           27 |     1875 | 2024-05-22 | Rooster            | L   | 0.697      | -            | -                | -                | -         |    -6.34 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           26 |     2655 | 2024-04-22 | Mindfreak          | L   | 0.498      | -            | -                | -                | -         |    -6.89 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           25 |     2657 | 2024-04-22 | Mindfreak          | L   | 0.498      | -            | -                | -                | -         |    -7.20 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           24 |     2845 | 2024-04-17 | Arcade             | L   | 0.464      | -            | -                | -                | -         |    -7.70 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           23 |     3009 | 2024-04-10 | Arcade             | W   | 0.418      | 0.333        | 0.002 (0.000)    | 0.134 (0.019)    | 0 (0.000) |     6.34 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           22 |     3013 | 2024-04-10 | Arcade             | W   | 0.417      | 0.333        | 0.002 (0.000)    | 0.134 (0.019)    | 0 (0.000) |     6.58 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           21 |     3237 | 2024-04-03 | KZG                | W   | 0.371      | 0.333        | 0.005 (0.001)    | 0.109 (0.014)    | 0 (0.000) |     6.17 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           20 |     3244 | 2024-04-03 | KZG                | W   | 0.371      | 0.333        | 0.005 (0.001)    | 0.109 (0.013)    | 0 (0.000) |     6.37 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           19 |     3367 | 2024-03-27 | Canon Event        | W   | 0.325      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.11 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           18 |     3372 | 2024-03-27 | Canon Event        | W   | 0.324      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.18 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           17 |     3638 | 2024-03-13 | DXA                | L   | 0.231      | -            | -                | -                | -         |    -3.26 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           16 |     3644 | 2024-03-13 | DXA                | W   | 0.231      | 0.333        | 0.002 (0.000)    | 0.222 (0.017)    | 0 (0.000) |     4.09 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           15 |     3816 | 2024-03-06 | Bad News Kangaroos | L   | 0.185      | -            | -                | -                | -         |    -1.90 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           14 |     3818 | 2024-03-06 | Bad News Kangaroos | L   | 0.184      | -            | -                | -                | -         |    -1.93 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           13 |     3987 | 2024-02-27 | RKON               | W   | 0.131      | 0.333        | -                | 0.030 (0.001)    | 0 (0.000) |     1.28 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     3990 | 2024-02-27 | RKON               | L   | 0.131      | -            | -                | -                | -         |    -2.87 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     4090 | 2024-02-22 | Bad News Kangaroos | L   | 0.098      | -            | -                | -                | -         |    -1.68 | Drox, Omichella, SkulL, viridian, vision   |
|           10 |     4092 | 2024-02-21 | Rooster            | L   | 0.096      | -            | -                | -                | -         |    -1.01 | Drox, Omichella, SkulL, viridian, vision   |
|            9 |     4126 | 2024-02-20 | Arcade             | W   | 0.090      | 0.143        | 0.002 (0.000)    | 0.134 (0.002)    | 0 (0.000) |     1.52 | Drox, Omichella, SkulL, viridian, vision   |
|            8 |     4146 | 2024-02-20 | Mindfreak          | W   | 0.084      | 0.143        | 0.004 (0.000)    | 0.224 (0.003)    | 0 (0.000) |     1.48 | Drox, Omichella, SkulL, viridian, vision   |
|            7 |     4148 | 2024-02-20 | Blitz              | W   | 0.084      | -            | -                | -                | -         |     0.52 | Drox, Omichella, SkulL, viridian, vision   |
|            6 |     4190 | 2024-02-18 | Mindfreak          | L   | 0.071      | -            | -                | -                | -         |    -1.01 | Drox, Omichella, SkulL, viridian, vision   |
|            5 |     4191 | 2024-02-18 | Mindfreak          | L   | 0.071      | -            | -                | -                | -         |    -1.00 | Drox, Omichella, SkulL, viridian, vision   |
|            4 |     4194 | 2024-02-18 | LE-LUX             | W   | 0.071      | -            | -                | -                | -         |     0.43 | Drox, Omichella, SkulL, viridian, vision   |
|            3 |     4252 | 2024-02-15 | sunday school      | L   | 0.056      | -            | -                | -                | -         |    -0.94 | damyo, Omichella, SkulL, viridian, vision  |
|            2 |     4276 | 2024-02-15 | DXA                | W   | 0.051      | 0.143        | 0.002 (0.000)    | 0.222 (0.002)    | -         |     0.90 | damyo, Omichella, SkulL, viridian, vision  |
|            1 |     4278 | 2024-02-14 | KZG                | L   | 0.050      | -            | -                | -                | -         |    -0.67 | damyo, Omichella, SkulL, viridian, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($653.22)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
