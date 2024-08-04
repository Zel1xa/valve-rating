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
|           28 |     1844 | 2024-05-22 | Rooster            | L   | 0.705      | -            | -                | -                | -         |    -6.06 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           27 |     1849 | 2024-05-22 | Rooster            | L   | 0.705      | -            | -                | -                | -         |    -6.38 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           26 |     2629 | 2024-04-22 | Mindfreak          | L   | 0.505      | -            | -                | -                | -         |    -6.98 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           25 |     2631 | 2024-04-22 | Mindfreak          | L   | 0.505      | -            | -                | -                | -         |    -7.29 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           24 |     2819 | 2024-04-17 | Arcade             | L   | 0.472      | -            | -                | -                | -         |    -7.83 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           23 |     2983 | 2024-04-10 | Arcade             | W   | 0.425      | 0.333        | 0.002 (0.000)    | 0.137 (0.019)    | 0 (0.000) |     6.45 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           22 |     2987 | 2024-04-10 | Arcade             | W   | 0.425      | 0.333        | 0.002 (0.000)    | 0.137 (0.019)    | 0 (0.000) |     6.70 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           21 |     3211 | 2024-04-03 | KZG                | W   | 0.378      | 0.333        | 0.005 (0.001)    | 0.111 (0.014)    | 0 (0.000) |     6.29 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           20 |     3218 | 2024-04-03 | KZG                | W   | 0.378      | 0.333        | 0.005 (0.001)    | 0.111 (0.014)    | 0 (0.000) |     6.49 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           19 |     3341 | 2024-03-27 | Canon Event        | W   | 0.332      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.17 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           18 |     3346 | 2024-03-27 | Canon Event        | W   | 0.332      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.25 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           17 |     3612 | 2024-03-13 | DXA                | L   | 0.239      | -            | -                | -                | -         |    -3.36 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           16 |     3618 | 2024-03-13 | DXA                | W   | 0.238      | 0.333        | 0.002 (0.000)    | 0.226 (0.018)    | 0 (0.000) |     4.22 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           15 |     3790 | 2024-03-06 | Bad News Kangaroos | L   | 0.192      | -            | -                | -                | -         |    -1.96 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           14 |     3792 | 2024-03-06 | Bad News Kangaroos | L   | 0.192      | -            | -                | -                | -         |    -1.99 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           13 |     3961 | 2024-02-27 | RKON               | W   | 0.138      | 0.333        | -                | 0.032 (0.001)    | 0 (0.000) |     1.35 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     3964 | 2024-02-27 | RKON               | L   | 0.138      | -            | -                | -                | -         |    -3.02 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     4064 | 2024-02-22 | Bad News Kangaroos | L   | 0.105      | -            | -                | -                | -         |    -1.80 | Drox, Omichella, SkulL, viridian, vision   |
|           10 |     4066 | 2024-02-21 | Rooster            | L   | 0.104      | -            | -                | -                | -         |    -1.08 | Drox, Omichella, SkulL, viridian, vision   |
|            9 |     4100 | 2024-02-20 | Arcade             | W   | 0.097      | 0.143        | 0.002 (0.000)    | 0.137 (0.002)    | 0 (0.000) |     1.65 | Drox, Omichella, SkulL, viridian, vision   |
|            8 |     4120 | 2024-02-20 | Mindfreak          | W   | 0.092      | 0.143        | 0.004 (0.000)    | 0.227 (0.003)    | 0 (0.000) |     1.61 | Drox, Omichella, SkulL, viridian, vision   |
|            7 |     4122 | 2024-02-20 | Blitz              | W   | 0.092      | -            | -                | -                | -         |     0.57 | Drox, Omichella, SkulL, viridian, vision   |
|            6 |     4164 | 2024-02-18 | Mindfreak          | L   | 0.078      | -            | -                | -                | -         |    -1.11 | Drox, Omichella, SkulL, viridian, vision   |
|            5 |     4165 | 2024-02-18 | Mindfreak          | L   | 0.078      | -            | -                | -                | -         |    -1.10 | Drox, Omichella, SkulL, viridian, vision   |
|            4 |     4168 | 2024-02-18 | LE-LUX             | W   | 0.078      | -            | -                | -                | -         |     0.48 | Drox, Omichella, SkulL, viridian, vision   |
|            3 |     4226 | 2024-02-15 | sunday school      | L   | 0.064      | -            | -                | -                | -         |    -1.06 | damyo, Omichella, SkulL, viridian, vision  |
|            2 |     4250 | 2024-02-15 | DXA                | W   | 0.058      | 0.143        | 0.002 (0.000)    | 0.226 (0.002)    | -         |     1.02 | damyo, Omichella, SkulL, viridian, vision  |
|            1 |     4252 | 2024-02-14 | KZG                | L   | 0.057      | -            | -                | -                | -         |    -0.77 | damyo, Omichella, SkulL, viridian, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($659.02)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
