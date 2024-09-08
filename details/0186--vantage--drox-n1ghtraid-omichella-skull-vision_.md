### Roster Details<br />
Team Name: Vantage<br />
Roster: Drox, N1ghtraid, Omichella, SkulL, vision <br />
Global Rank: [186](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [22]( ../standings_asia.md)<br />
<br />
Final Rank Value:  616.2<br />
<br />
Final Rank Value (616.2) = Starting Rank Value (622.0) + Head To Head Adjustments (-5.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.263[<sup>1</sup>](#table2)
- Bounty Collected: 0.191[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.115<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 622.0
- 400 + ( ( 0.115 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 622.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     3011 | 2024-05-22 | Rooster     | L   | 0.472      | -            | -                | -                | -         |    -4.77 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     3016 | 2024-05-22 | Rooster     | L   | 0.472      | -            | -                | -                | -         |    -4.95 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     3796 | 2024-04-22 | Mindfreak   | L   | 0.273      | -            | -                | -                | -         |    -3.71 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           10 |     3798 | 2024-04-22 | Mindfreak   | L   | 0.273      | -            | -                | -                | -         |    -3.79 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            9 |     3986 | 2024-04-17 | Arcade      | L   | 0.239      | -            | -                | -                | -         |    -3.05 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            8 |     4150 | 2024-04-10 | Arcade      | W   | 0.193      | 0.333        | 0.002 (0.000)    | 0.245 (0.016)    | 0 (0.000) |     3.65 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            7 |     4154 | 2024-04-10 | Arcade      | W   | 0.192      | 0.333        | 0.002 (0.000)    | 0.245 (0.016)    | 0 (0.000) |     3.71 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            6 |     4378 | 2024-04-03 | KZG         | W   | 0.146      | 0.333        | 0.003 (0.000)    | 0.152 (0.007)    | 0 (0.000) |     2.50 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            5 |     4385 | 2024-04-03 | KZG         | W   | 0.146      | 0.333        | 0.003 (0.000)    | 0.152 (0.007)    | 0 (0.000) |     2.52 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            4 |     4508 | 2024-03-27 | Canon Event | W   | 0.099      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.06 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            3 |     4513 | 2024-03-27 | Canon Event | W   | 0.099      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.07 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            2 |     4779 | 2024-03-13 | DXA         | L   | 0.006      | -            | -                | -                | -         |    -0.09 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            1 |     4785 | 2024-03-13 | DXA         | W   | 0.006      | 0.333        | 0.001 (0.000)    | 0.221 (0.000)    | 0 (0.000) |     0.10 | Drox, N1ghtraid, Omichella, SkulL, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($473.11)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
