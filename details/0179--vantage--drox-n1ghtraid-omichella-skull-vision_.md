### Roster Details<br />
Team Name: Vantage<br />
Roster: Drox, N1ghtraid, Omichella, SkulL, vision <br />
Global Rank: [179](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [17]( ../standings_asia.md)<br />
<br />
Final Rank Value:  646.9<br />
<br />
Final Rank Value (646.9) = Starting Rank Value (657.2) + Head To Head Adjustments (-10.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.219[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.125<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 657.2
- 400 + ( ( 0.125 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 657.2


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
|           29 |     1763 | 2024-05-22 | Rooster            | L   | 0.725      | -            | -                | -                | -         |    -6.09 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           28 |     1768 | 2024-05-22 | Rooster            | L   | 0.724      | -            | -                | -                | -         |    -6.41 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           27 |     2047 | 2024-05-15 | FlyQuest           | L   | 0.678      | -            | -                | -                | -         |    -0.86 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           26 |     2048 | 2024-05-15 | FlyQuest           | L   | 0.678      | -            | -                | -                | -         |    -0.87 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           25 |     2581 | 2024-04-22 | Mindfreak          | L   | 0.525      | -            | -                | -                | -         |    -7.43 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           24 |     2583 | 2024-04-22 | Mindfreak          | L   | 0.525      | -            | -                | -                | -         |    -7.79 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           23 |     2777 | 2024-04-17 | Arcade             | L   | 0.491      | -            | -                | -                | -         |    -8.38 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           22 |     2943 | 2024-04-10 | Arcade             | W   | 0.445      | 0.333        | 0.003 (0.000)    | 0.138 (0.021)    | 0 (0.000) |     6.54 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           21 |     2947 | 2024-04-10 | Arcade             | W   | 0.444      | 0.333        | 0.003 (0.000)    | 0.138 (0.020)    | 0 (0.000) |     6.80 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           20 |     3177 | 2024-04-03 | KZG                | W   | 0.398      | 0.333        | 0.006 (0.001)    | 0.113 (0.015)    | 0 (0.000) |     6.57 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           19 |     3184 | 2024-04-03 | KZG                | W   | 0.398      | 0.333        | 0.006 (0.001)    | 0.113 (0.015)    | 0 (0.000) |     6.80 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           18 |     3310 | 2024-03-27 | Canon Event        | W   | 0.352      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.30 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           17 |     3315 | 2024-03-27 | Canon Event        | W   | 0.351      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.39 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           16 |     3589 | 2024-03-13 | DXA                | L   | 0.258      | -            | -                | -                | -         |    -3.75 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           15 |     3595 | 2024-03-13 | DXA                | W   | 0.258      | 0.333        | 0.002 (0.000)    | 0.228 (0.020)    | 0 (0.000) |     4.46 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           14 |     3769 | 2024-03-06 | Bad News Kangaroos | L   | 0.212      | -            | -                | -                | -         |    -2.28 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           13 |     3771 | 2024-03-06 | Bad News Kangaroos | L   | 0.211      | -            | -                | -                | -         |    -2.31 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     3947 | 2024-02-27 | RKON               | W   | 0.158      | 0.333        | -                | 0.034 (0.002)    | 0 (0.000) |     1.54 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     3949 | 2024-02-27 | RKON               | L   | 0.158      | -            | -                | -                | -         |    -3.47 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           10 |     4057 | 2024-02-22 | Bad News Kangaroos | L   | 0.125      | -            | -                | -                | -         |    -1.38 | Drox, Omichella, SkulL, viridian, vision   |
|            9 |     4059 | 2024-02-21 | Rooster            | L   | 0.123      | -            | -                | -                | -         |    -1.29 | Drox, Omichella, SkulL, viridian, vision   |
|            8 |     4094 | 2024-02-20 | Arcade             | W   | 0.117      | 0.143        | 0.003 (0.000)    | 0.138 (0.002)    | 0 (0.000) |     1.93 | Drox, Omichella, SkulL, viridian, vision   |
|            7 |     4114 | 2024-02-20 | Mindfreak          | W   | 0.112      | 0.143        | 0.004 (0.000)    | 0.227 (0.004)    | 0 (0.000) |     1.91 | Drox, Omichella, SkulL, viridian, vision   |
|            6 |     4116 | 2024-02-20 | Blitz              | W   | 0.111      | -            | -                | -                | -         |     0.68 | Drox, Omichella, SkulL, viridian, vision   |
|            5 |     4158 | 2024-02-18 | Mindfreak          | L   | 0.098      | -            | -                | -                | -         |    -1.42 | Drox, Omichella, SkulL, viridian, vision   |
|            4 |     4161 | 2024-02-18 | LE-LUX             | W   | 0.098      | -            | -                | -                | -         |     0.59 | Drox, Omichella, SkulL, viridian, vision   |
|            3 |     4220 | 2024-02-15 | sunday school      | L   | 0.083      | -            | -                | -                | -         |    -1.39 | damyo, Omichella, SkulL, viridian, vision  |
|            2 |     4244 | 2024-02-15 | DXA                | W   | 0.078      | 0.143        | 0.002 (0.000)    | 0.228 (0.003)    | -         |     1.35 | damyo, Omichella, SkulL, viridian, vision  |
|            1 |     4246 | 2024-02-14 | KZG                | L   | 0.077      | -            | -                | -                | -         |    -1.02 | damyo, Omichella, SkulL, viridian, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($674.89)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
