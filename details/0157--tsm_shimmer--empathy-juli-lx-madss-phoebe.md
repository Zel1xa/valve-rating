### Roster Details<br />
Team Name: TSM Shimmer<br />
Roster: empathy, Juli, Lx, madss, phoebe<br />
Global Rank: [157](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [44]( ../standings_americas.md)<br />
<br />
Final Rank Value:  693.0<br />
<br />
Final Rank Value (693.0) = Starting Rank Value (712.3) + Head To Head Adjustments (-19.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 712.3
- 400 + ( ( 0.153 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 712.3


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
|           23 |      260 | 2024-07-28 | Nouns fe         | W   | 1.000      | 0.250        | 0.003 (0.001)    | 0.035 (0.009)    | 0 (0.000) |    12.61 | empathy, Juli, Lx, madss, phoebe   |
|           22 |      988 | 2024-06-16 | Lotus fe         | W   | 0.875      | 0.250        | 0.005 (0.001)    | 0.038 (0.008)    | 0 (0.000) |    12.24 | abby, empathy, Juli, Lx, madss     |
|           21 |     1213 | 2024-06-09 | Perseverance     | L   | 0.827      | -            | -                | -                | -         |   -18.22 | abby, empathy, Florence, Lx, madss |
|           20 |     1315 | 2024-06-07 | Zomblers         | L   | 0.816      | -            | -                | -                | -         |   -18.89 | abby, empathy, Florence, Lx, madss |
|           19 |     1463 | 2024-06-05 | Asian Kings      | W   | 0.800      | -            | -                | -                | 0 (0.000) |     3.77 | abby, empathy, Florence, Lx, madss |
|           18 |     1506 | 2024-06-04 | Nouns            | L   | 0.795      | -            | -                | -                | -         |    -4.50 | abby, empathy, Florence, Lx, madss |
|           17 |     1508 | 2024-06-04 | Homyno           | L   | 0.794      | -            | -                | -                | -         |   -12.73 | abby, empathy, Florence, Lx, madss |
|           16 |     1615 | 2024-05-31 | NAVI Javelins    | L   | 0.769      | -            | -                | -                | -         |    -7.58 | abby, empathy, Lx, madss, phoebe   |
|           15 |     1621 | 2024-05-31 | panelinha        | L   | 0.768      | -            | -                | -                | -         |    -7.78 | abby, empathy, Lx, madss, phoebe   |
|           14 |     1735 | 2024-05-26 | FlyQuest RED     | L   | 0.734      | -            | -                | -                | -         |   -10.61 | abby, empathy, Lx, madss, phoebe   |
|           13 |     1736 | 2024-05-26 | Karma            | W   | 0.734      | 0.303        | 0.004 (0.001)    | 0.072 (0.016)    | 0 (0.000) |     9.35 | abby, empathy, Lx, madss, phoebe   |
|           12 |     2334 | 2024-05-05 | Lotus fe         | W   | 0.595      | 0.250        | 0.005 (0.001)    | 0.038 (0.006)    | 0 (0.000) |     7.35 | abby, empathy, Lx, madss, phoebe   |
|           11 |     2690 | 2024-04-19 | Limitless Angels | W   | 0.489      | 0.322        | 0.003 (0.000)    | 0.048 (0.008)    | 0 (0.000) |     6.04 | abby, empathy, Lx, madss, phoebe   |
|           10 |     2868 | 2024-04-14 | FlyQuest RED     | L   | 0.455      | -            | -                | -                | -         |    -6.75 | abby, empathy, Lx, madss, phoebe   |
|            9 |     2915 | 2024-04-11 | COVEN            | W   | 0.435      | 0.322        | 0.002 (0.000)    | -                | 0 (0.000) |     3.26 | abby, empathy, Lx, madss, phoebe   |
|            8 |     3082 | 2024-04-07 | Limitless Angels | W   | 0.408      | 0.250        | 0.003 (0.000)    | 0.048 (0.005)    | 0 (0.000) |     5.06 | abby, empathy, Lx, madss, phoebe   |
|            7 |     3180 | 2024-04-03 | WG Bandits       | W   | 0.382      | 0.322        | 0.002 (0.000)    | 0.021 (0.003)    | 0 (0.000) |     4.30 | abby, empathy, Lx, madss, phoebe   |
|            6 |     3313 | 2024-03-27 | cleanup crew fe  | W   | 0.336      | 0.322        | -                | 0.021 (0.002)    | 0 (0.000) |     4.11 | abby, empathy, Lx, madss, phoebe   |
|            5 |     3408 | 2024-03-21 | Karma            | W   | 0.296      | 0.322        | 0.004 (0.000)    | 0.072 (0.007)    | -         |     3.94 | abby, empathy, Lx, madss, phoebe   |
|            4 |     3552 | 2024-03-14 | Nouns fe         | W   | 0.249      | 0.322        | 0.003 (0.000)    | 0.035 (0.003)    | -         |     3.29 | abby, empathy, Lx, madss, phoebe   |
|            3 |     3762 | 2024-03-06 | FlyQuest RED     | L   | 0.196      | -            | -                | -                | -         |    -2.92 | abby, empathy, Lx, madss, phoebe   |
|            2 |     3846 | 2024-03-03 | FlyQuest RED     | L   | 0.175      | -            | -                | -                | -         |    -2.65 | abby, empathy, Lx, madss, phoebe   |
|            1 |     3986 | 2024-02-25 | FlyQuest RED     | L   | 0.128      | -            | -                | -                | -         |    -1.97 | abby, empathy, Lx, madss, phoebe   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,575.34)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $750.00        | $750.00         |
| 2024-06-16 |      0.875 | $750.00        | $656.41         |
| 2024-06-02 |      0.781 | $4,000.00      | $3,125.09       |
| 2024-05-26 |      0.734 | $1,500.00      | $1,101.42       |
| 2024-05-05 |      0.595 | $750.00        | $446.41         |
| 2024-04-14 |      0.455 | $250.00        | $113.72         |
| 2024-04-07 |      0.408 | $750.00        | $306.37         |
| 2024-03-03 |      0.175 | $250.00        | $43.80          |
| 2024-02-25 |      0.128 | $250.00        | $32.12          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
