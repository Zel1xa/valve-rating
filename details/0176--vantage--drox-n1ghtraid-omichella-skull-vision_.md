### Roster Details<br />
Team Name: Vantage<br />
Roster: Drox, N1ghtraid, Omichella, SkulL, vision <br />
Global Rank: [176](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [18]( ../standings_asia.md)<br />
<br />
Final Rank Value:  645.5<br />
<br />
Final Rank Value (645.5) = Starting Rank Value (654.1) + Head To Head Adjustments (-8.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.124<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 654.1
- 400 + ( ( 0.124 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 654.1


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
|           28 |     1820 | 2024-05-22 | Rooster            | L   | 0.706      | -            | -                | -                | -         |    -6.07 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           27 |     1825 | 2024-05-22 | Rooster            | L   | 0.706      | -            | -                | -                | -         |    -6.38 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           26 |     2605 | 2024-04-22 | Mindfreak          | L   | 0.506      | -            | -                | -                | -         |    -7.00 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           25 |     2607 | 2024-04-22 | Mindfreak          | L   | 0.506      | -            | -                | -                | -         |    -7.31 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           24 |     2795 | 2024-04-17 | Arcade             | L   | 0.473      | -            | -                | -                | -         |    -7.84 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           23 |     2959 | 2024-04-10 | Arcade             | W   | 0.426      | 0.333        | 0.002 (0.000)    | 0.137 (0.019)    | 0 (0.000) |     6.47 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           22 |     2963 | 2024-04-10 | Arcade             | W   | 0.426      | 0.333        | 0.002 (0.000)    | 0.137 (0.019)    | 0 (0.000) |     6.71 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           21 |     3187 | 2024-04-03 | KZG                | W   | 0.380      | 0.333        | 0.005 (0.001)    | 0.112 (0.014)    | 0 (0.000) |     6.30 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           20 |     3194 | 2024-04-03 | KZG                | W   | 0.379      | 0.333        | 0.005 (0.001)    | 0.112 (0.014)    | 0 (0.000) |     6.51 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           19 |     3317 | 2024-03-27 | Canon Event        | W   | 0.333      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.18 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           18 |     3322 | 2024-03-27 | Canon Event        | W   | 0.333      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.26 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           17 |     3588 | 2024-03-13 | DXA                | L   | 0.240      | -            | -                | -                | -         |    -3.38 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           16 |     3594 | 2024-03-13 | DXA                | W   | 0.239      | 0.333        | 0.002 (0.000)    | 0.226 (0.018)    | 0 (0.000) |     4.24 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           15 |     3766 | 2024-03-06 | Bad News Kangaroos | L   | 0.193      | -            | -                | -                | -         |    -1.97 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           14 |     3768 | 2024-03-06 | Bad News Kangaroos | L   | 0.193      | -            | -                | -                | -         |    -2.00 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           13 |     3937 | 2024-02-27 | RKON               | W   | 0.139      | 0.333        | -                | 0.032 (0.001)    | 0 (0.000) |     1.36 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     3940 | 2024-02-27 | RKON               | L   | 0.139      | -            | -                | -                | -         |    -3.05 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     4040 | 2024-02-22 | Bad News Kangaroos | L   | 0.106      | -            | -                | -                | -         |    -1.82 | Drox, Omichella, SkulL, viridian, vision   |
|           10 |     4042 | 2024-02-21 | Rooster            | L   | 0.105      | -            | -                | -                | -         |    -1.09 | Drox, Omichella, SkulL, viridian, vision   |
|            9 |     4076 | 2024-02-20 | Arcade             | W   | 0.098      | 0.143        | 0.002 (0.000)    | 0.137 (0.002)    | 0 (0.000) |     1.67 | Drox, Omichella, SkulL, viridian, vision   |
|            8 |     4096 | 2024-02-20 | Mindfreak          | W   | 0.093      | 0.143        | 0.004 (0.000)    | 0.227 (0.003)    | 0 (0.000) |     1.63 | Drox, Omichella, SkulL, viridian, vision   |
|            7 |     4098 | 2024-02-20 | Blitz              | W   | 0.093      | -            | -                | -                | -         |     0.57 | Drox, Omichella, SkulL, viridian, vision   |
|            6 |     4140 | 2024-02-18 | Mindfreak          | L   | 0.079      | -            | -                | -                | -         |    -1.12 | Drox, Omichella, SkulL, viridian, vision   |
|            5 |     4141 | 2024-02-18 | Mindfreak          | L   | 0.079      | -            | -                | -                | -         |    -1.12 | Drox, Omichella, SkulL, viridian, vision   |
|            4 |     4144 | 2024-02-18 | LE-LUX             | W   | 0.079      | -            | -                | -                | -         |     0.49 | Drox, Omichella, SkulL, viridian, vision   |
|            3 |     4202 | 2024-02-15 | sunday school      | L   | 0.065      | -            | -                | -                | -         |    -1.08 | damyo, Omichella, SkulL, viridian, vision  |
|            2 |     4226 | 2024-02-15 | DXA                | W   | 0.059      | 0.143        | 0.002 (0.000)    | 0.226 (0.002)    | -         |     1.04 | damyo, Omichella, SkulL, viridian, vision  |
|            1 |     4228 | 2024-02-14 | KZG                | L   | 0.058      | -            | -                | -                | -         |    -0.78 | damyo, Omichella, SkulL, viridian, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($659.87)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
