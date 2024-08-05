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
Final Rank Value (645.5) = Starting Rank Value (653.9) + Head To Head Adjustments (-8.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.216[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.124<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 653.9
- 400 + ( ( 0.124 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 653.9


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
|           28 |     1861 | 2024-05-22 | Rooster            | L   | 0.699      | -            | -                | -                | -         |    -6.04 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           27 |     1866 | 2024-05-22 | Rooster            | L   | 0.699      | -            | -                | -                | -         |    -6.35 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           26 |     2646 | 2024-04-22 | Mindfreak          | L   | 0.499      | -            | -                | -                | -         |    -6.91 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           25 |     2648 | 2024-04-22 | Mindfreak          | L   | 0.499      | -            | -                | -                | -         |    -7.22 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           24 |     2836 | 2024-04-17 | Arcade             | L   | 0.466      | -            | -                | -                | -         |    -7.73 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           23 |     3000 | 2024-04-10 | Arcade             | W   | 0.419      | 0.333        | 0.002 (0.000)    | 0.136 (0.019)    | 0 (0.000) |     6.37 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           22 |     3004 | 2024-04-10 | Arcade             | W   | 0.419      | 0.333        | 0.002 (0.000)    | 0.136 (0.019)    | 0 (0.000) |     6.61 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           21 |     3228 | 2024-04-03 | KZG                | W   | 0.373      | 0.333        | 0.005 (0.001)    | 0.111 (0.014)    | 0 (0.000) |     6.20 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           20 |     3235 | 2024-04-03 | KZG                | W   | 0.372      | 0.333        | 0.005 (0.001)    | 0.111 (0.014)    | 0 (0.000) |     6.40 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           19 |     3358 | 2024-03-27 | Canon Event        | W   | 0.326      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.12 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           18 |     3363 | 2024-03-27 | Canon Event        | W   | 0.326      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.20 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           17 |     3629 | 2024-03-13 | DXA                | L   | 0.233      | -            | -                | -                | -         |    -3.28 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           16 |     3635 | 2024-03-13 | DXA                | W   | 0.233      | 0.333        | 0.002 (0.000)    | 0.225 (0.017)    | 0 (0.000) |     4.12 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           15 |     3807 | 2024-03-06 | Bad News Kangaroos | L   | 0.186      | -            | -                | -                | -         |    -1.91 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           14 |     3809 | 2024-03-06 | Bad News Kangaroos | L   | 0.186      | -            | -                | -                | -         |    -1.94 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           13 |     3978 | 2024-02-27 | RKON               | W   | 0.133      | 0.333        | -                | 0.031 (0.001)    | 0 (0.000) |     1.29 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     3981 | 2024-02-27 | RKON               | L   | 0.132      | -            | -                | -                | -         |    -2.90 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     4081 | 2024-02-22 | Bad News Kangaroos | L   | 0.099      | -            | -                | -                | -         |    -1.70 | Drox, Omichella, SkulL, viridian, vision   |
|           10 |     4083 | 2024-02-21 | Rooster            | L   | 0.098      | -            | -                | -                | -         |    -1.02 | Drox, Omichella, SkulL, viridian, vision   |
|            9 |     4117 | 2024-02-20 | Arcade             | W   | 0.092      | 0.143        | 0.002 (0.000)    | 0.136 (0.002)    | 0 (0.000) |     1.55 | Drox, Omichella, SkulL, viridian, vision   |
|            8 |     4137 | 2024-02-20 | Mindfreak          | W   | 0.086      | 0.143        | 0.004 (0.000)    | 0.226 (0.003)    | 0 (0.000) |     1.51 | Drox, Omichella, SkulL, viridian, vision   |
|            7 |     4139 | 2024-02-20 | Blitz              | W   | 0.086      | -            | -                | -                | -         |     0.53 | Drox, Omichella, SkulL, viridian, vision   |
|            6 |     4181 | 2024-02-18 | Mindfreak          | L   | 0.073      | -            | -                | -                | -         |    -1.03 | Drox, Omichella, SkulL, viridian, vision   |
|            5 |     4182 | 2024-02-18 | Mindfreak          | L   | 0.073      | -            | -                | -                | -         |    -1.02 | Drox, Omichella, SkulL, viridian, vision   |
|            4 |     4185 | 2024-02-18 | LE-LUX             | W   | 0.072      | -            | -                | -                | -         |     0.44 | Drox, Omichella, SkulL, viridian, vision   |
|            3 |     4243 | 2024-02-15 | sunday school      | L   | 0.058      | -            | -                | -                | -         |    -0.97 | damyo, Omichella, SkulL, viridian, vision  |
|            2 |     4267 | 2024-02-15 | DXA                | W   | 0.052      | 0.143        | 0.002 (0.000)    | 0.225 (0.002)    | -         |     0.92 | damyo, Omichella, SkulL, viridian, vision  |
|            1 |     4269 | 2024-02-14 | KZG                | L   | 0.051      | -            | -                | -                | -         |    -0.69 | damyo, Omichella, SkulL, viridian, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($654.44)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
