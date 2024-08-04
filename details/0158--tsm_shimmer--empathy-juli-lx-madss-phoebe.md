### Roster Details<br />
Team Name: TSM Shimmer<br />
Roster: empathy, Juli, Lx, madss, phoebe<br />
Global Rank: [158](../standings_global.md)<br />
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
|           23 |      259 | 2024-07-28 | Nouns fe         | W   | 1.000      | 0.250        | 0.003 (0.001)    | 0.035 (0.009)    | 0 (0.000) |    12.61 | empathy, Juli, Lx, madss, phoebe   |
|           22 |      987 | 2024-06-16 | Lotus fe         | W   | 0.876      | 0.250        | 0.005 (0.001)    | 0.038 (0.008)    | 0 (0.000) |    12.25 | abby, empathy, Juli, Lx, madss     |
|           21 |     1212 | 2024-06-09 | Perseverance     | L   | 0.827      | -            | -                | -                | -         |   -18.22 | abby, empathy, Florence, Lx, madss |
|           20 |     1314 | 2024-06-07 | Zomblers         | L   | 0.817      | -            | -                | -                | -         |   -18.90 | abby, empathy, Florence, Lx, madss |
|           19 |     1462 | 2024-06-05 | Asian Kings      | W   | 0.801      | -            | -                | -                | 0 (0.000) |     3.77 | abby, empathy, Florence, Lx, madss |
|           18 |     1505 | 2024-06-04 | Nouns            | L   | 0.795      | -            | -                | -                | -         |    -4.50 | abby, empathy, Florence, Lx, madss |
|           17 |     1507 | 2024-06-04 | Homyno           | L   | 0.794      | -            | -                | -                | -         |   -12.73 | abby, empathy, Florence, Lx, madss |
|           16 |     1614 | 2024-05-31 | NAVI Javelins    | L   | 0.769      | -            | -                | -                | -         |    -7.58 | abby, empathy, Lx, madss, phoebe   |
|           15 |     1620 | 2024-05-31 | panelinha        | L   | 0.768      | -            | -                | -                | -         |    -7.79 | abby, empathy, Lx, madss, phoebe   |
|           14 |     1734 | 2024-05-26 | FlyQuest RED     | L   | 0.735      | -            | -                | -                | -         |   -10.62 | abby, empathy, Lx, madss, phoebe   |
|           13 |     1735 | 2024-05-26 | Karma            | W   | 0.734      | 0.303        | 0.004 (0.001)    | 0.072 (0.016)    | 0 (0.000) |     9.35 | abby, empathy, Lx, madss, phoebe   |
|           12 |     2333 | 2024-05-05 | Lotus fe         | W   | 0.596      | 0.250        | 0.005 (0.001)    | 0.038 (0.006)    | 0 (0.000) |     7.35 | abby, empathy, Lx, madss, phoebe   |
|           11 |     2689 | 2024-04-19 | Limitless Angels | W   | 0.489      | 0.322        | 0.003 (0.000)    | 0.048 (0.008)    | 0 (0.000) |     6.05 | abby, empathy, Lx, madss, phoebe   |
|           10 |     2867 | 2024-04-14 | FlyQuest RED     | L   | 0.455      | -            | -                | -                | -         |    -6.75 | abby, empathy, Lx, madss, phoebe   |
|            9 |     2914 | 2024-04-11 | COVEN            | W   | 0.436      | 0.322        | 0.002 (0.000)    | -                | 0 (0.000) |     3.26 | abby, empathy, Lx, madss, phoebe   |
|            8 |     3081 | 2024-04-07 | Limitless Angels | W   | 0.409      | 0.250        | 0.003 (0.000)    | 0.048 (0.005)    | 0 (0.000) |     5.06 | abby, empathy, Lx, madss, phoebe   |
|            7 |     3179 | 2024-04-03 | WG Bandits       | W   | 0.382      | 0.322        | 0.002 (0.000)    | 0.021 (0.003)    | 0 (0.000) |     4.30 | abby, empathy, Lx, madss, phoebe   |
|            6 |     3312 | 2024-03-27 | cleanup crew fe  | W   | 0.336      | 0.322        | -                | 0.021 (0.002)    | 0 (0.000) |     4.11 | abby, empathy, Lx, madss, phoebe   |
|            5 |     3407 | 2024-03-21 | Karma            | W   | 0.296      | 0.322        | 0.004 (0.000)    | 0.072 (0.007)    | -         |     3.94 | abby, empathy, Lx, madss, phoebe   |
|            4 |     3551 | 2024-03-14 | Nouns fe         | W   | 0.249      | 0.322        | 0.003 (0.000)    | 0.035 (0.003)    | -         |     3.29 | abby, empathy, Lx, madss, phoebe   |
|            3 |     3761 | 2024-03-06 | FlyQuest RED     | L   | 0.196      | -            | -                | -                | -         |    -2.93 | abby, empathy, Lx, madss, phoebe   |
|            2 |     3845 | 2024-03-03 | FlyQuest RED     | L   | 0.175      | -            | -                | -                | -         |    -2.66 | abby, empathy, Lx, madss, phoebe   |
|            1 |     3985 | 2024-02-25 | FlyQuest RED     | L   | 0.129      | -            | -                | -                | -         |    -1.98 | abby, empathy, Lx, madss, phoebe   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,577.90)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $750.00        | $750.00         |
| 2024-06-16 |      0.876 | $750.00        | $656.63         |
| 2024-06-02 |      0.782 | $4,000.00      | $3,126.30       |
| 2024-05-26 |      0.735 | $1,500.00      | $1,101.88       |
| 2024-05-05 |      0.596 | $750.00        | $446.63         |
| 2024-04-14 |      0.455 | $250.00        | $113.80         |
| 2024-04-07 |      0.409 | $750.00        | $306.60         |
| 2024-03-03 |      0.175 | $250.00        | $43.87          |
| 2024-02-25 |      0.129 | $250.00        | $32.20          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
