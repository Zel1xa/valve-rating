### Roster Details<br />
Team Name: TSM Shimmer<br />
Roster: empathy, Juli, Lx, madss, phoebe<br />
Global Rank: [156](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [42]( ../standings_americas.md)<br />
<br />
Final Rank Value:  693.2<br />
<br />
Final Rank Value (693.2) = Starting Rank Value (712.9) + Head To Head Adjustments (-19.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.372[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 712.9
- 400 + ( ( 0.153 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 712.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |      201 | 2024-07-28 | Nouns fe         | W   | 1.000      | 0.250        | 0.003 (0.001)    | 0.036 (0.009)    | 0 (0.000) |    12.61 | empathy, Juli, Lx, madss, phoebe   |
|           22 |      917 | 2024-06-16 | Lotus fe         | W   | 0.882      | 0.250        | 0.005 (0.001)    | 0.039 (0.009)    | 0 (0.000) |    12.33 | abby, empathy, Juli, Lx, madss     |
|           21 |     1122 | 2024-06-09 | Perseverance     | L   | 0.834      | -            | -                | -                | -         |   -18.36 | abby, empathy, Florence, Lx, madss |
|           20 |     1219 | 2024-06-07 | Zomblers         | L   | 0.823      | -            | -                | -                | -         |   -19.04 | abby, empathy, Florence, Lx, madss |
|           19 |     1367 | 2024-06-05 | Asian Kings      | W   | 0.807      | -            | -                | -                | 0 (0.000) |     3.79 | abby, empathy, Florence, Lx, madss |
|           18 |     1410 | 2024-06-04 | Nouns            | L   | 0.801      | -            | -                | -                | -         |    -4.76 | abby, empathy, Florence, Lx, madss |
|           17 |     1412 | 2024-06-04 | Homyno           | L   | 0.800      | -            | -                | -                | -         |   -12.82 | abby, empathy, Florence, Lx, madss |
|           16 |     1516 | 2024-05-31 | NAVI Javelins    | L   | 0.775      | -            | -                | -                | -         |    -7.61 | abby, empathy, Lx, madss, phoebe   |
|           15 |     1522 | 2024-05-31 | panelinha        | L   | 0.774      | -            | -                | -                | -         |    -7.82 | abby, empathy, Lx, madss, phoebe   |
|           14 |     1636 | 2024-05-26 | FlyQuest RED     | L   | 0.741      | -            | -                | -                | -         |   -10.68 | abby, empathy, Lx, madss, phoebe   |
|           13 |     1637 | 2024-05-26 | Karma            | W   | 0.741      | 0.303        | 0.004 (0.001)    | 0.076 (0.017)    | 0 (0.000) |     9.43 | abby, empathy, Lx, madss, phoebe   |
|           12 |     2232 | 2024-05-05 | Lotus fe         | W   | 0.602      | 0.250        | 0.005 (0.001)    | 0.039 (0.006)    | 0 (0.000) |     7.42 | abby, empathy, Lx, madss, phoebe   |
|           11 |     2587 | 2024-04-19 | Limitless Angels | W   | 0.495      | 0.322        | 0.003 (0.000)    | 0.051 (0.008)    | 0 (0.000) |     6.12 | abby, empathy, Lx, madss, phoebe   |
|           10 |     2765 | 2024-04-14 | FlyQuest RED     | L   | 0.461      | -            | -                | -                | -         |    -6.83 | abby, empathy, Lx, madss, phoebe   |
|            9 |     2812 | 2024-04-11 | COVEN            | W   | 0.442      | 0.322        | 0.002 (0.000)    | -                | 0 (0.000) |     3.29 | abby, empathy, Lx, madss, phoebe   |
|            8 |     2979 | 2024-04-07 | Limitless Angels | W   | 0.415      | 0.250        | 0.003 (0.000)    | 0.051 (0.005)    | 0 (0.000) |     5.14 | abby, empathy, Lx, madss, phoebe   |
|            7 |     3077 | 2024-04-03 | WG Bandits       | W   | 0.389      | 0.322        | 0.002 (0.000)    | 0.022 (0.003)    | 0 (0.000) |     4.36 | abby, empathy, Lx, madss, phoebe   |
|            6 |     3210 | 2024-03-27 | cleanup crew fe  | W   | 0.342      | 0.322        | -                | 0.022 (0.002)    | 0 (0.000) |     4.18 | abby, empathy, Lx, madss, phoebe   |
|            5 |     3300 | 2024-03-21 | Karma            | W   | 0.302      | 0.322        | 0.004 (0.000)    | 0.076 (0.007)    | -         |     4.02 | abby, empathy, Lx, madss, phoebe   |
|            4 |     3443 | 2024-03-14 | Nouns fe         | W   | 0.255      | 0.322        | 0.003 (0.000)    | 0.036 (0.003)    | -         |     3.38 | abby, empathy, Lx, madss, phoebe   |
|            3 |     3651 | 2024-03-06 | FlyQuest RED     | L   | 0.202      | -            | -                | -                | -         |    -3.01 | abby, empathy, Lx, madss, phoebe   |
|            2 |     3735 | 2024-03-03 | FlyQuest RED     | L   | 0.182      | -            | -                | -                | -         |    -2.75 | abby, empathy, Lx, madss, phoebe   |
|            1 |     3875 | 2024-02-25 | FlyQuest RED     | L   | 0.135      | -            | -                | -                | -         |    -2.07 | abby, empathy, Lx, madss, phoebe   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,631.02)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $750.00        | $750.00         |
| 2024-06-16 |      0.882 | $750.00        | $661.32         |
| 2024-06-02 |      0.788 | $4,000.00      | $3,151.30       |
| 2024-05-26 |      0.741 | $1,500.00      | $1,111.25       |
| 2024-05-05 |      0.602 | $750.00        | $451.32         |
| 2024-04-14 |      0.461 | $250.00        | $115.36         |
| 2024-04-07 |      0.415 | $750.00        | $311.28         |
| 2024-03-03 |      0.182 | $250.00        | $45.43          |
| 2024-02-25 |      0.135 | $250.00        | $33.76          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
