### Roster Details<br />
Team Name: TSM Shimmer<br />
Roster: empathy, Juli, Lx, madss, phoebe<br />
Global Rank: [157](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [44]( ../standings_americas.md)<br />
<br />
Final Rank Value:  693.2<br />
<br />
Final Rank Value (693.2) = Starting Rank Value (712.3) + Head To Head Adjustments (-19.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 712.3
- 400 + ( ( 0.153 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 712.3


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
|           23 |      277 | 2024-07-28 | Nouns fe         | W   | 1.000      | 0.250        | 0.003 (0.001)    | 0.034 (0.009)    | 0 (0.000) |    12.61 | empathy, Juli, Lx, madss, phoebe   |
|           22 |     1005 | 2024-06-16 | Lotus fe         | W   | 0.869      | 0.250        | 0.005 (0.001)    | 0.038 (0.008)    | 0 (0.000) |    12.17 | abby, empathy, Juli, Lx, madss     |
|           21 |     1230 | 2024-06-09 | Perseverance     | L   | 0.821      | -            | -                | -                | -         |   -18.10 | abby, empathy, Florence, Lx, madss |
|           20 |     1332 | 2024-06-07 | Zomblers         | L   | 0.811      | -            | -                | -                | -         |   -18.76 | abby, empathy, Florence, Lx, madss |
|           19 |     1480 | 2024-06-05 | Asian Kings      | W   | 0.795      | -            | -                | -                | 0 (0.000) |     3.75 | abby, empathy, Florence, Lx, madss |
|           18 |     1523 | 2024-06-04 | Nouns            | L   | 0.789      | -            | -                | -                | -         |    -4.49 | abby, empathy, Florence, Lx, madss |
|           17 |     1525 | 2024-06-04 | Homyno           | L   | 0.788      | -            | -                | -                | -         |   -12.64 | abby, empathy, Florence, Lx, madss |
|           16 |     1632 | 2024-05-31 | NAVI Javelins    | L   | 0.763      | -            | -                | -                | -         |    -7.55 | abby, empathy, Lx, madss, phoebe   |
|           15 |     1638 | 2024-05-31 | panelinha        | L   | 0.762      | -            | -                | -                | -         |    -7.74 | abby, empathy, Lx, madss, phoebe   |
|           14 |     1752 | 2024-05-26 | FlyQuest RED     | L   | 0.729      | -            | -                | -                | -         |   -10.55 | abby, empathy, Lx, madss, phoebe   |
|           13 |     1753 | 2024-05-26 | Karma            | W   | 0.728      | 0.303        | 0.004 (0.001)    | 0.071 (0.016)    | 0 (0.000) |     9.28 | abby, empathy, Lx, madss, phoebe   |
|           12 |     2351 | 2024-05-05 | Lotus fe         | W   | 0.589      | 0.250        | 0.005 (0.001)    | 0.038 (0.006)    | 0 (0.000) |     7.29 | abby, empathy, Lx, madss, phoebe   |
|           11 |     2707 | 2024-04-19 | Limitless Angels | W   | 0.483      | 0.322        | 0.003 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     5.97 | abby, empathy, Lx, madss, phoebe   |
|           10 |     2885 | 2024-04-14 | FlyQuest RED     | L   | 0.449      | -            | -                | -                | -         |    -6.68 | abby, empathy, Lx, madss, phoebe   |
|            9 |     2932 | 2024-04-11 | COVEN            | W   | 0.430      | 0.322        | 0.001 (0.000)    | -                | 0 (0.000) |     3.22 | abby, empathy, Lx, madss, phoebe   |
|            8 |     3099 | 2024-04-07 | Limitless Angels | W   | 0.403      | 0.250        | 0.003 (0.000)    | 0.047 (0.005)    | 0 (0.000) |     4.99 | abby, empathy, Lx, madss, phoebe   |
|            7 |     3197 | 2024-04-03 | WG Bandits       | W   | 0.376      | 0.322        | 0.002 (0.000)    | 0.021 (0.003)    | 0 (0.000) |     4.24 | abby, empathy, Lx, madss, phoebe   |
|            6 |     3330 | 2024-03-27 | cleanup crew fe  | W   | 0.330      | 0.322        | -                | 0.021 (0.002)    | 0 (0.000) |     4.03 | abby, empathy, Lx, madss, phoebe   |
|            5 |     3425 | 2024-03-21 | Karma            | W   | 0.290      | 0.322        | 0.004 (0.000)    | 0.071 (0.007)    | -         |     3.86 | abby, empathy, Lx, madss, phoebe   |
|            4 |     3569 | 2024-03-14 | Nouns fe         | W   | 0.243      | 0.322        | 0.003 (0.000)    | 0.034 (0.003)    | -         |     3.21 | abby, empathy, Lx, madss, phoebe   |
|            3 |     3779 | 2024-03-06 | FlyQuest RED     | L   | 0.190      | -            | -                | -                | -         |    -2.84 | abby, empathy, Lx, madss, phoebe   |
|            2 |     3863 | 2024-03-03 | FlyQuest RED     | L   | 0.169      | -            | -                | -                | -         |    -2.57 | abby, empathy, Lx, madss, phoebe   |
|            1 |     4003 | 2024-02-25 | FlyQuest RED     | L   | 0.123      | -            | -                | -                | -         |    -1.89 | abby, empathy, Lx, madss, phoebe   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,526.74)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $750.00        | $750.00         |
| 2024-06-16 |      0.869 | $750.00        | $652.12         |
| 2024-06-02 |      0.776 | $4,000.00      | $3,102.22       |
| 2024-05-26 |      0.729 | $1,500.00      | $1,092.85       |
| 2024-05-05 |      0.589 | $750.00        | $442.12         |
| 2024-04-14 |      0.449 | $250.00        | $112.29         |
| 2024-04-07 |      0.403 | $750.00        | $302.08         |
| 2024-03-03 |      0.169 | $250.00        | $42.37          |
| 2024-02-25 |      0.123 | $250.00        | $30.69          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
