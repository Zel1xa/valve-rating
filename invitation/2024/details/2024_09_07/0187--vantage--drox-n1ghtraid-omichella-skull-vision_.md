### Roster Details<br />
Team Name: Vantage<br />
Roster: Drox, N1ghtraid, Omichella, SkulL, vision <br />
Global Rank: [187](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Asia]( ../../standings_asia_2024_09_07.md)<br />
Regional Rank: [22]( ../../standings_asia_2024_09_07.md)<br />
<br />
Final Rank Value:  619.4<br />
<br />
Final Rank Value (619.4) = Starting Rank Value (624.9) + Head To Head Adjustments (-5.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.263[<sup>1</sup>](#table2)
- Bounty Collected: 0.192[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.115<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 624.9
- 400 + ( ( 0.115 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 624.9


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
|           13 |     2979 | 2024-05-22 | Rooster     | L   | 0.480      | -            | -                | -                | -         |    -4.86 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     2984 | 2024-05-22 | Rooster     | L   | 0.480      | -            | -                | -                | -         |    -5.04 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     3764 | 2024-04-22 | Mindfreak   | L   | 0.281      | -            | -                | -                | -         |    -3.81 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           10 |     3766 | 2024-04-22 | Mindfreak   | L   | 0.280      | -            | -                | -                | -         |    -3.90 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            9 |     3954 | 2024-04-17 | Arcade      | L   | 0.247      | -            | -                | -                | -         |    -3.15 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            8 |     4118 | 2024-04-10 | Arcade      | W   | 0.200      | 0.333        | 0.002 (0.000)    | 0.252 (0.017)    | 0 (0.000) |     3.81 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            7 |     4122 | 2024-04-10 | Arcade      | W   | 0.200      | 0.333        | 0.002 (0.000)    | 0.252 (0.017)    | 0 (0.000) |     3.87 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            6 |     4346 | 2024-04-03 | KZG         | W   | 0.154      | 0.333        | 0.003 (0.000)    | 0.157 (0.008)    | 0 (0.000) |     2.64 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            5 |     4353 | 2024-04-03 | KZG         | W   | 0.153      | 0.333        | 0.003 (0.000)    | 0.157 (0.008)    | 0 (0.000) |     2.66 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            4 |     4476 | 2024-03-27 | Canon Event | W   | 0.107      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.14 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            3 |     4481 | 2024-03-27 | Canon Event | W   | 0.107      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.15 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            2 |     4747 | 2024-03-13 | DXA         | L   | 0.014      | -            | -                | -                | -         |    -0.20 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|            1 |     4753 | 2024-03-13 | DXA         | W   | 0.014      | 0.333        | 0.001 (0.000)    | 0.230 (0.001)    | 0 (0.000) |     0.23 | Drox, N1ghtraid, Omichella, SkulL, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($479.44)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
