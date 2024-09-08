### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, sliimey, TjP<br />
Global Rank: [123](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  774.3<br />
<br />
Final Rank Value (774.3) = Starting Rank Value (730.0) + Head To Head Adjustments (44.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.317[<sup>1</sup>](#table2)
- Bounty Collected: 0.279[<sup>2</sup>](#table1)
- Opponent Network: 0.055[<sup>2</sup>](#table1)
- LAN Wins: 0.031[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 730.0
- 400 + ( ( 0.170 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 730.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |      289 | 2024-08-29 | TALON              | L   | 1.000      | -            | -                | -                | -         |   -20.52 | asap, chelleos, dangeR, sliimey, TjP |
|           40 |      348 | 2024-08-28 | TALON              | W   | 1.000      | 0.143        | -                | 0.262 (0.037)    | 0 (0.000) |     9.84 | asap, chelleos, dangeR, sliimey, TjP |
|           39 |      401 | 2024-08-27 | The Art of War     | W   | 1.000      | 0.143        | -                | 0.330 (0.047)    | 0 (0.000) |    13.41 | asap, chelleos, dangeR, sliimey, TjP |
|           38 |      412 | 2024-08-26 | Vantage            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.67 | asap, chelleos, dangeR, sliimey, TjP |
|           37 |      590 | 2024-08-22 | The Art of War     | W   | 1.000      | 0.143        | -                | 0.330 (0.047)    | 0 (0.000) |    13.19 | asap, chelleos, dangeR, sliimey, TjP |
|           36 |      602 | 2024-08-21 | Mindfreak          | W   | 1.000      | 0.143        | -                | 0.227 (0.032)    | 0 (0.000) |    15.59 | asap, chelleos, dangeR, sliimey, TjP |
|           35 |      659 | 2024-08-21 | Housebets          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.93 | asap, chelleos, dangeR, sliimey, TjP |
|           34 |      679 | 2024-08-20 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -14.44 | asap, chelleos, dangeR, sliimey, TjP |
|           33 |      891 | 2024-08-13 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.245 (0.082)    | 0 (0.000) |    11.78 | asap, chelleos, dangeR, sliimey, TjP |
|           32 |      898 | 2024-08-13 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -20.07 | asap, chelleos, dangeR, sliimey, TjP |
|           31 |     1084 | 2024-08-07 | Vantage            | W   | 0.986      | 0.333        | 0.002 (0.001)    | 0.150 (0.049)    | 0 (0.000) |    11.57 | asap, chelleos, dangeR, sliimey, TjP |
|           30 |     1090 | 2024-08-07 | Vantage            | L   | 0.986      | -            | -                | -                | -         |   -19.84 | asap, chelleos, dangeR, sliimey, TjP |
|           29 |     1606 | 2024-07-23 | The Art of War     | L   | 0.886      | -            | -                | -                | -         |   -17.09 | asap, chelleos, dangeR, Hatz, TjP    |
|           28 |     1611 | 2024-07-23 | The Art of War     | L   | 0.886      | -            | -                | -                | -         |   -18.38 | asap, chelleos, dangeR, Hatz, TjP    |
|           27 |     1790 | 2024-07-18 | DXA                | W   | 0.853      | 0.333        | -                | 0.221 (0.063)    | 0 (0.000) |     8.79 | asap, chelleos, dangeR, Hatz, TjP    |
|           26 |     1798 | 2024-07-18 | DXA                | L   | 0.852      | -            | -                | -                | -         |   -18.52 | asap, chelleos, dangeR, Hatz, TjP    |
|           25 |     1910 | 2024-07-16 | Mindfreak          | W   | 0.839      | 0.333        | 0.003 (0.001)    | 0.227 (0.063)    | -         |     9.59 | asap, chelleos, dangeR, Hatz, TjP    |
|           24 |     1915 | 2024-07-16 | Mindfreak          | W   | 0.839      | 0.333        | 0.003 (0.001)    | 0.227 (0.063)    | -         |    10.28 | asap, chelleos, dangeR, Hatz, TjP    |
|           23 |     2426 | 2024-06-08 | FlyQuest           | L   | 0.591      | -            | -                | -                | -         |    -3.42 | asap, chelleos, dangeR, nettik, TjP  |
|           22 |     2536 | 2024-06-07 | FlyQuest           | W   | 0.579      | 0.333        | 0.109 (0.021)    | 0.333 (0.064)    | -         |    15.13 | asap, chelleos, dangeR, nettik, TjP  |
|           21 |     2607 | 2024-06-06 | Housebets          | W   | 0.572      | 0.333        | 0.002 (0.000)    | -                | -         |     7.19 | asap, chelleos, dangeR, nettik, TjP  |
|           20 |     3011 | 2024-05-22 | Vantage            | W   | 0.472      | -            | -                | -                | -         |     4.77 | asap, chelleos, dangeR, nettik, TjP  |
|           19 |     3016 | 2024-05-22 | Vantage            | W   | 0.472      | -            | -                | -                | -         |     4.95 | asap, chelleos, dangeR, nettik, TjP  |
|           18 |     3269 | 2024-05-15 | Canon Event        | W   | 0.426      | -            | -                | -                | -         |     2.61 | asap, chelleos, dangeR, nettik, TjP  |
|           17 |     3274 | 2024-05-15 | Canon Event        | W   | 0.426      | -            | -                | -                | -         |     2.67 | asap, chelleos, dangeR, nettik, TjP  |
|           16 |     3462 | 2024-05-08 | KZG                | W   | 0.379      | 0.333        | 0.003 (0.000)    | -                | -         |     4.45 | asap, chelleos, dangeR, nettik, TjP  |
|           15 |     3465 | 2024-05-08 | KZG                | W   | 0.379      | 0.333        | 0.003 (0.000)    | -                | -         |     4.59 | asap, chelleos, dangeR, nettik, TjP  |
|           14 |     3696 | 2024-04-26 | MIBR               | L   | 0.305      | -            | -                | -                | -         |    -0.22 | asap, chelleos, dangeR, nettik, TjP  |
|           13 |     3718 | 2024-04-26 | KZG                | W   | 0.299      | 0.500        | 0.003 (0.000)    | -                | 1 (0.299) |     3.72 | asap, chelleos, dangeR, nettik, TjP  |
|           12 |     3721 | 2024-04-25 | Rebels             | L   | 0.298      | -            | -                | -                | -         |    -2.43 | asap, chelleos, dangeR, nettik, TjP  |
|           11 |     3852 | 2024-04-19 | Bad News Kangaroos | L   | 0.258      | -            | -                | -                | -         |    -4.78 | asap, chelleos, dangeR, nettik, TjP  |
|           10 |     3894 | 2024-04-19 | FlyQuest           | L   | 0.253      | -            | -                | -                | -         |    -1.28 | asap, chelleos, dangeR, nettik, TjP  |
|            9 |     3900 | 2024-04-18 | Bad News Kangaroos | W   | 0.252      | -            | -                | -                | -         |     3.26 | asap, chelleos, dangeR, nettik, TjP  |
|            8 |     3976 | 2024-04-17 | Arcade             | W   | 0.239      | -            | -                | -                | -         |     3.50 | asap, chelleos, dangeR, nettik, TjP  |
|            7 |     3980 | 2024-04-17 | Canon Event        | W   | 0.239      | -            | -                | -                | -         |     1.60 | asap, chelleos, dangeR, nettik, TjP  |
|            6 |     4149 | 2024-04-10 | Bad News Kangaroos | L   | 0.193      | -            | -                | -                | -         |    -3.57 | asap, chelleos, dangeR, nettik, TjP  |
|            5 |     4156 | 2024-04-10 | Bad News Kangaroos | W   | 0.192      | 0.333        | 0.008 (0.001)    | -                | -         |     2.52 | asap, chelleos, dangeR, nettik, TjP  |
|            4 |     4509 | 2024-03-27 | VexX               | W   | 0.099      | -            | -                | -                | -         |     0.67 | asap, chelleos, dangeR, nettik, TjP  |
|            3 |     4514 | 2024-03-27 | VexX               | W   | 0.099      | -            | -                | -                | -         |     0.67 | asap, chelleos, dangeR, nettik, TjP  |
|            2 |     4781 | 2024-03-13 | FlyQuest           | L   | 0.006      | -            | -                | -                | -         |    -0.03 | asap, chelleos, dangeR, nettik, TjP  |
|            1 |     4789 | 2024-03-13 | FlyQuest           | L   | 0.006      | -            | -                | -                | -         |    -0.03 | asap, chelleos, dangeR, nettik, TjP  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,119.58)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.591 | $2,000.00      | $1,182.78       |
| 2024-04-28 |      0.312 | $3,000.00      | $936.81         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
