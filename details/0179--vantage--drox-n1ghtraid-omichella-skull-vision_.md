### Roster Details<br />
Team Name: Vantage<br />
Roster: Drox, N1ghtraid, Omichella, SkulL, vision <br />
Global Rank: [179](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [17]( ../standings_asia.md)<br />
<br />
Final Rank Value:  647.3<br />
<br />
Final Rank Value (647.3) = Starting Rank Value (657.6) + Head To Head Adjustments (-10.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.219[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.125<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 657.6
- 400 + ( ( 0.125 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 657.6


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
|           29 |     1759 | 2024-05-22 | Rooster            | L   | 0.726      | -            | -                | -                | -         |    -6.09 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           28 |     1764 | 2024-05-22 | Rooster            | L   | 0.726      | -            | -                | -                | -         |    -6.41 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           27 |     2043 | 2024-05-15 | FlyQuest           | L   | 0.679      | -            | -                | -                | -         |    -0.87 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           26 |     2044 | 2024-05-15 | FlyQuest           | L   | 0.679      | -            | -                | -                | -         |    -0.88 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           25 |     2577 | 2024-04-22 | Mindfreak          | L   | 0.526      | -            | -                | -                | -         |    -7.45 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           24 |     2579 | 2024-04-22 | Mindfreak          | L   | 0.526      | -            | -                | -                | -         |    -7.80 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           23 |     2773 | 2024-04-17 | Arcade             | L   | 0.493      | -            | -                | -                | -         |    -8.40 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           22 |     2939 | 2024-04-10 | Arcade             | W   | 0.446      | 0.333        | 0.003 (0.000)    | 0.138 (0.021)    | 0 (0.000) |     6.56 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           21 |     2943 | 2024-04-10 | Arcade             | W   | 0.446      | 0.333        | 0.003 (0.000)    | 0.138 (0.021)    | 0 (0.000) |     6.83 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           20 |     3173 | 2024-04-03 | KZG                | W   | 0.400      | 0.333        | 0.006 (0.001)    | 0.113 (0.015)    | 0 (0.000) |     6.60 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           19 |     3180 | 2024-04-03 | KZG                | W   | 0.399      | 0.333        | 0.006 (0.001)    | 0.113 (0.015)    | 0 (0.000) |     6.83 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           18 |     3306 | 2024-03-27 | Canon Event        | W   | 0.353      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.31 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           17 |     3311 | 2024-03-27 | Canon Event        | W   | 0.353      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.40 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           16 |     3585 | 2024-03-13 | DXA                | L   | 0.260      | -            | -                | -                | -         |    -3.77 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           15 |     3591 | 2024-03-13 | DXA                | W   | 0.259      | 0.333        | 0.002 (0.000)    | 0.228 (0.020)    | 0 (0.000) |     4.49 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           14 |     3765 | 2024-03-06 | Bad News Kangaroos | L   | 0.213      | -            | -                | -                | -         |    -2.29 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           13 |     3767 | 2024-03-06 | Bad News Kangaroos | L   | 0.213      | -            | -                | -                | -         |    -2.33 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           12 |     3943 | 2024-02-27 | RKON               | W   | 0.159      | 0.333        | -                | 0.034 (0.002)    | 0 (0.000) |     1.55 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           11 |     3945 | 2024-02-27 | RKON               | L   | 0.159      | -            | -                | -                | -         |    -3.50 | Drox, N1ghtraid, Omichella, SkulL, vision  |
|           10 |     4053 | 2024-02-22 | Bad News Kangaroos | L   | 0.126      | -            | -                | -                | -         |    -1.39 | Drox, Omichella, SkulL, viridian, vision   |
|            9 |     4055 | 2024-02-21 | Rooster            | L   | 0.125      | -            | -                | -                | -         |    -1.31 | Drox, Omichella, SkulL, viridian, vision   |
|            8 |     4090 | 2024-02-20 | Arcade             | W   | 0.119      | 0.143        | 0.003 (0.000)    | 0.138 (0.002)    | 0 (0.000) |     1.95 | Drox, Omichella, SkulL, viridian, vision   |
|            7 |     4110 | 2024-02-20 | Mindfreak          | W   | 0.113      | 0.143        | 0.004 (0.000)    | 0.227 (0.004)    | 0 (0.000) |     1.93 | Drox, Omichella, SkulL, viridian, vision   |
|            6 |     4112 | 2024-02-20 | Blitz              | W   | 0.113      | -            | -                | -                | -         |     0.69 | Drox, Omichella, SkulL, viridian, vision   |
|            5 |     4154 | 2024-02-18 | Mindfreak          | L   | 0.100      | -            | -                | -                | -         |    -1.44 | Drox, Omichella, SkulL, viridian, vision   |
|            4 |     4157 | 2024-02-18 | LE-LUX             | W   | 0.099      | -            | -                | -                | -         |     0.60 | Drox, Omichella, SkulL, viridian, vision   |
|            3 |     4216 | 2024-02-15 | sunday school      | L   | 0.085      | -            | -                | -                | -         |    -1.42 | damyo, Omichella, SkulL, viridian, vision  |
|            2 |     4240 | 2024-02-15 | DXA                | W   | 0.079      | 0.143        | 0.002 (0.000)    | 0.228 (0.003)    | -         |     1.37 | damyo, Omichella, SkulL, viridian, vision  |
|            1 |     4242 | 2024-02-14 | KZG                | L   | 0.078      | -            | -                | -                | -         |    -1.04 | damyo, Omichella, SkulL, viridian, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($676.00)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
