### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [122](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  810.7<br />
<br />
Final Rank Value (810.7) = Starting Rank Value (778.4) + Head To Head Adjustments (32.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.048[<sup>2</sup>](#table1)
- LAN Wins: 0.060[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.4
- 400 + ( ( 0.184 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 778.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |      470 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.35 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      474 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.67 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      654 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.222 (0.074)    | 0 (0.000) |     8.69 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      659 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.34 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |      772 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.223 (0.074)    | 0 (0.000) |     9.72 | asap, chelleos, dangeR, Hatz, TjP   |
|           32 |      774 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.223 (0.074)    | 0 (0.000) |    10.50 | asap, chelleos, dangeR, Hatz, TjP   |
|           31 |     1287 | 2024-06-08 | FlyQuest           | L   | 0.815      | -            | -                | -                | -         |    -3.65 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1397 | 2024-06-07 | FlyQuest           | W   | 0.802      | 0.333        | 0.104 (0.028)    | 0.285 (0.076)    | 0 (0.000) |    22.03 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1468 | 2024-06-06 | Bad News Kangaroos | W   | 0.795      | 0.333        | 0.016 (0.004)    | 0.222 (0.059)    | 0 (0.000) |    12.00 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     1872 | 2024-05-22 | Vantage            | W   | 0.696      | 0.333        | -                | 0.067 (0.015)    | 0 (0.000) |     6.02 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     1877 | 2024-05-22 | Vantage            | W   | 0.696      | -            | -                | -                | 0 (0.000) |     6.33 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     2130 | 2024-05-15 | Canon Event        | W   | 0.649      | -            | -                | -                | 0 (0.000) |     2.78 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     2135 | 2024-05-15 | Canon Event        | W   | 0.649      | -            | -                | -                | 0 (0.000) |     2.85 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2323 | 2024-05-08 | KZG                | W   | 0.603      | 0.333        | 0.005 (0.001)    | 0.109 (0.022)    | -         |     5.91 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2326 | 2024-05-08 | KZG                | W   | 0.602      | 0.333        | 0.005 (0.001)    | 0.109 (0.022)    | -         |     6.19 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2557 | 2024-04-26 | MIBR               | L   | 0.528      | -            | -                | -                | -         |    -0.46 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2579 | 2024-04-26 | KZG                | W   | 0.522      | 0.500        | 0.005 (0.001)    | 0.109 (0.028)    | 1 (0.522) |     5.60 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2582 | 2024-04-25 | Rebels             | L   | 0.521      | -            | -                | -                | -         |    -4.21 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2713 | 2024-04-19 | Bad News Kangaroos | L   | 0.482      | -            | -                | -                | -         |    -7.78 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2755 | 2024-04-19 | FlyQuest           | L   | 0.476      | -            | -                | -                | -         |    -1.73 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2761 | 2024-04-18 | Bad News Kangaroos | W   | 0.475      | 0.143        | 0.016 (0.001)    | -                | -         |     7.29 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2837 | 2024-04-17 | Arcade             | W   | 0.463      | -            | -                | -                | -         |     4.74 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2841 | 2024-04-17 | Canon Event        | W   | 0.463      | -            | -                | -                | -         |     2.25 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     3010 | 2024-04-10 | Bad News Kangaroos | L   | 0.416      | -            | -                | -                | -         |    -6.72 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     3017 | 2024-04-10 | Bad News Kangaroos | W   | 0.416      | 0.333        | 0.016 (0.002)    | 0.222 (0.031)    | -         |     6.51 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3370 | 2024-03-27 | Arcade             | W   | 0.323      | -            | -                | -                | -         |     3.52 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3375 | 2024-03-27 | Arcade             | W   | 0.323      | -            | -                | -                | -         |     3.60 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3642 | 2024-03-13 | FlyQuest           | L   | 0.229      | -            | -                | -                | -         |    -0.81 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3650 | 2024-03-13 | FlyQuest           | L   | 0.229      | -            | -                | -                | -         |    -0.82 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3817 | 2024-03-06 | Mindfreak          | W   | 0.183      | -            | -                | -                | -         |     1.97 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3823 | 2024-03-06 | Mindfreak          | W   | 0.182      | -            | -                | -                | -         |     1.99 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     4072 | 2024-02-23 | FlyQuest           | L   | 0.102      | -            | -                | -                | -         |    -0.36 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     4074 | 2024-02-22 | Bad News Kangaroos | W   | 0.101      | -            | -                | -                | -         |     0.93 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     4091 | 2024-02-22 | FlyQuest           | L   | 0.096      | -            | -                | -                | -         |    -0.34 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     4094 | 2024-02-21 | Vantage            | W   | 0.095      | -            | -                | -                | -         |     0.99 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     4121 | 2024-02-21 | DXA                | W   | 0.089      | -            | -                | -                | -         |     1.08 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     4125 | 2024-02-21 | DXA                | W   | 0.089      | -            | -                | -                | -         |     1.08 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,236.25)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.815 | $2,000.00      | $1,629.44       |
| 2024-04-28 |      0.536 | $3,000.00      | $1,606.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
