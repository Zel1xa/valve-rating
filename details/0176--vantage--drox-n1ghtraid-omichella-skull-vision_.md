### Roster Details<br />
Team Name: Vantage<br />
Roster: Drox, N1ghtraid, Omichella, SkulL, vision <br />
Global Rank: [176](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [18]( ../standings_asia.md)<br />
<br />
Final Rank Value:  644.5<br />
<br />
Final Rank Value (644.5) = Starting Rank Value (654.1) + Head To Head Adjustments (-9.6)<br />

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
|           28 |     1812 | 2024-05-22 | Rooster            | L   | 0.707      | -            | -                | -                | -         |    -6.14 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           27 |     1817 | 2024-05-22 | Rooster            | L   | 0.706      | -            | -                | -                | -         |    -6.46 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           26 |     2597 | 2024-04-22 | Mindfreak          | L   | 0.507      | -            | -                | -                | -         |    -7.16 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           25 |     2599 | 2024-04-22 | Mindfreak          | L   | 0.507      | -            | -                | -                | -         |    -7.48 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           24 |     2787 | 2024-04-17 | Arcade             | L   | 0.473      | -            | -                | -                | -         |    -8.05 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           23 |     2951 | 2024-04-10 | Arcade             | W   | 0.427      | 0.333        | 0.002 (0.000)    | 0.137 (0.019)    | 0 (0.000) |     6.30 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           22 |     2955 | 2024-04-10 | Arcade             | W   | 0.426      | 0.333        | 0.002 (0.000)    | 0.137 (0.019)    | 0 (0.000) |     6.54 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           21 |     3179 | 2024-04-03 | KZG                | W   | 0.380      | 0.333        | 0.005 (0.001)    | 0.112 (0.014)    | 0 (0.000) |     6.31 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           20 |     3186 | 2024-04-03 | KZG                | W   | 0.380      | 0.333        | 0.005 (0.001)    | 0.112 (0.014)    | 0 (0.000) |     6.51 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           19 |     3309 | 2024-03-27 | Canon Event        | W   | 0.334      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.18 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           18 |     3314 | 2024-03-27 | Canon Event        | W   | 0.333      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.26 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           17 |     3580 | 2024-03-13 | DXA                | L   | 0.240      | -            | -                | -                | -         |    -3.48 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           16 |     3586 | 2024-03-13 | DXA                | W   | 0.240      | 0.333        | 0.002 (0.000)    | 0.227 (0.018)    | 0 (0.000) |     4.15 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           15 |     3758 | 2024-03-06 | Bad News Kangaroos | L   | 0.194      | -            | -                | -                | -         |    -2.12 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           14 |     3760 | 2024-03-06 | Bad News Kangaroos | L   | 0.193      | -            | -                | -                | -         |    -2.15 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           13 |     3929 | 2024-02-27 | RKON               | W   | 0.140      | 0.333        | -                | 0.032 (0.001)    | 0 (0.000) |     1.37 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     3932 | 2024-02-27 | RKON               | L   | 0.140      | -            | -                | -                | -         |    -3.06 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     4032 | 2024-02-22 | Bad News Kangaroos | L   | 0.107      | -            | -                | -                | -         |    -1.20 | Drox, Omichella, SkulL, viridian, vision   |
|           10 |     4034 | 2024-02-21 | Rooster            | L   | 0.105      | -            | -                | -                | -         |    -1.11 | Drox, Omichella, SkulL, viridian, vision   |
|            9 |     4068 | 2024-02-20 | Arcade             | W   | 0.099      | 0.143        | 0.002 (0.000)    | 0.137 (0.002)    | 0 (0.000) |     1.63 | Drox, Omichella, SkulL, viridian, vision   |
|            8 |     4088 | 2024-02-20 | Mindfreak          | W   | 0.094      | 0.143        | 0.004 (0.000)    | 0.227 (0.003)    | 0 (0.000) |     1.61 | Drox, Omichella, SkulL, viridian, vision   |
|            7 |     4090 | 2024-02-20 | Blitz              | W   | 0.093      | -            | -                | -                | -         |     0.58 | Drox, Omichella, SkulL, viridian, vision   |
|            6 |     4132 | 2024-02-18 | Mindfreak          | L   | 0.080      | -            | -                | -                | -         |    -1.16 | Drox, Omichella, SkulL, viridian, vision   |
|            5 |     4133 | 2024-02-18 | Mindfreak          | L   | 0.080      | -            | -                | -                | -         |    -1.15 | Drox, Omichella, SkulL, viridian, vision   |
|            4 |     4136 | 2024-02-18 | LE-LUX             | W   | 0.080      | -            | -                | -                | -         |     0.49 | Drox, Omichella, SkulL, viridian, vision   |
|            3 |     4194 | 2024-02-15 | sunday school      | L   | 0.065      | -            | -                | -                | -         |    -1.09 | damyo, Omichella, SkulL, viridian, vision  |
|            2 |     4218 | 2024-02-15 | DXA                | W   | 0.060      | 0.143        | 0.002 (0.000)    | 0.227 (0.002)    | -         |     1.03 | damyo, Omichella, SkulL, viridian, vision  |
|            1 |     4220 | 2024-02-14 | KZG                | L   | 0.059      | -            | -                | -                | -         |    -0.79 | damyo, Omichella, SkulL, viridian, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($660.44)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
