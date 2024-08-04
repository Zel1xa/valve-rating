### Roster Details<br />
Team Name: Vantage<br />
Roster: Drox, N1ghtraid, Omichella, SkulL, vision <br />
Global Rank: [178](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [18]( ../standings_asia.md)<br />
<br />
Final Rank Value:  645.5<br />
<br />
Final Rank Value (645.5) = Starting Rank Value (654.0) + Head To Head Adjustments (-8.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
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
|           28 |     1843 | 2024-05-22 | Rooster            | L   | 0.705      | -            | -                | -                | -         |    -6.07 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           27 |     1848 | 2024-05-22 | Rooster            | L   | 0.705      | -            | -                | -                | -         |    -6.38 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           26 |     2628 | 2024-04-22 | Mindfreak          | L   | 0.505      | -            | -                | -                | -         |    -6.99 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           25 |     2630 | 2024-04-22 | Mindfreak          | L   | 0.505      | -            | -                | -                | -         |    -7.30 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           24 |     2818 | 2024-04-17 | Arcade             | L   | 0.472      | -            | -                | -                | -         |    -7.83 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           23 |     2982 | 2024-04-10 | Arcade             | W   | 0.425      | 0.333        | 0.002 (0.000)    | 0.137 (0.019)    | 0 (0.000) |     6.46 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           22 |     2986 | 2024-04-10 | Arcade             | W   | 0.425      | 0.333        | 0.002 (0.000)    | 0.137 (0.019)    | 0 (0.000) |     6.70 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           21 |     3210 | 2024-04-03 | KZG                | W   | 0.379      | 0.333        | 0.005 (0.001)    | 0.112 (0.014)    | 0 (0.000) |     6.29 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           20 |     3217 | 2024-04-03 | KZG                | W   | 0.378      | 0.333        | 0.005 (0.001)    | 0.112 (0.014)    | 0 (0.000) |     6.50 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           19 |     3340 | 2024-03-27 | Canon Event        | W   | 0.332      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.17 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           18 |     3345 | 2024-03-27 | Canon Event        | W   | 0.332      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.25 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           17 |     3611 | 2024-03-13 | DXA                | L   | 0.239      | -            | -                | -                | -         |    -3.36 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           16 |     3617 | 2024-03-13 | DXA                | W   | 0.239      | 0.333        | 0.002 (0.000)    | 0.226 (0.018)    | 0 (0.000) |     4.22 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           15 |     3789 | 2024-03-06 | Bad News Kangaroos | L   | 0.192      | -            | -                | -                | -         |    -1.97 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           14 |     3791 | 2024-03-06 | Bad News Kangaroos | L   | 0.192      | -            | -                | -                | -         |    -1.99 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           13 |     3960 | 2024-02-27 | RKON               | W   | 0.139      | 0.333        | -                | 0.032 (0.001)    | 0 (0.000) |     1.36 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     3963 | 2024-02-27 | RKON               | L   | 0.138      | -            | -                | -                | -         |    -3.03 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     4063 | 2024-02-22 | Bad News Kangaroos | L   | 0.105      | -            | -                | -                | -         |    -1.81 | Drox, Omichella, SkulL, viridian, vision   |
|           10 |     4065 | 2024-02-21 | Rooster            | L   | 0.104      | -            | -                | -                | -         |    -1.08 | Drox, Omichella, SkulL, viridian, vision   |
|            9 |     4099 | 2024-02-20 | Arcade             | W   | 0.098      | 0.143        | 0.002 (0.000)    | 0.137 (0.002)    | 0 (0.000) |     1.65 | Drox, Omichella, SkulL, viridian, vision   |
|            8 |     4119 | 2024-02-20 | Mindfreak          | W   | 0.092      | 0.143        | 0.004 (0.000)    | 0.227 (0.003)    | 0 (0.000) |     1.61 | Drox, Omichella, SkulL, viridian, vision   |
|            7 |     4121 | 2024-02-20 | Blitz              | W   | 0.092      | -            | -                | -                | -         |     0.57 | Drox, Omichella, SkulL, viridian, vision   |
|            6 |     4163 | 2024-02-18 | Mindfreak          | L   | 0.079      | -            | -                | -                | -         |    -1.11 | Drox, Omichella, SkulL, viridian, vision   |
|            5 |     4164 | 2024-02-18 | Mindfreak          | L   | 0.079      | -            | -                | -                | -         |    -1.10 | Drox, Omichella, SkulL, viridian, vision   |
|            4 |     4167 | 2024-02-18 | LE-LUX             | W   | 0.078      | -            | -                | -                | -         |     0.48 | Drox, Omichella, SkulL, viridian, vision   |
|            3 |     4225 | 2024-02-15 | sunday school      | L   | 0.064      | -            | -                | -                | -         |    -1.07 | damyo, Omichella, SkulL, viridian, vision  |
|            2 |     4249 | 2024-02-15 | DXA                | W   | 0.058      | 0.143        | 0.002 (0.000)    | 0.226 (0.002)    | -         |     1.03 | damyo, Omichella, SkulL, viridian, vision  |
|            1 |     4251 | 2024-02-14 | KZG                | L   | 0.057      | -            | -                | -                | -         |    -0.77 | damyo, Omichella, SkulL, viridian, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($659.26)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
