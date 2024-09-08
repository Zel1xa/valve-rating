### Roster Details<br />
Team Name: Rebels<br />
Roster: casey, Flayy, kisserek, olimp, SZPERO<br />
Global Rank: [68](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Final Rank Value:  941.5<br />
<br />
Final Rank Value (941.5) = Starting Rank Value (921.3) + Head To Head Adjustments (20.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.392[<sup>1</sup>](#table2)
- Bounty Collected: 0.397[<sup>2</sup>](#table1)
- Opponent Network: 0.226[<sup>2</sup>](#table1)
- LAN Wins: 0.062[<sup>2</sup>](#table1)

The average of these factors is 0.269<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 921.3
- 400 + ( ( 0.269 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 921.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           55 |       47 | 2024-09-06 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -12.31 | casey, Flayy, kisserek, olimp, SZPERO   |
|           54 |       81 | 2024-09-05 | Qiang             | W   | 1.000      | 0.500        | 0.029 (0.014)    | -                | 0 (0.000) |     3.66 | casey, Flayy, kisserek, olimp, SZPERO   |
|           53 |      205 | 2024-09-01 | Partizan          | L   | 1.000      | -            | -                | -                | -         |   -24.00 | casey, Flayy, innocent, kisserek, olimp |
|           52 |      387 | 2024-08-27 | FAVBET            | W   | 1.000      | 0.384        | -                | 0.655 (0.252)    | 0 (0.000) |    11.33 | casey, Flayy, innocent, kisserek, olimp |
|           51 |      550 | 2024-08-23 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.61 | casey, Flayy, innocent, kisserek, olimp |
|           50 |      563 | 2024-08-23 | Johnny Speeds     | W   | 1.000      | 0.143        | 0.102 (0.015)    | -                | 0 (0.000) |    21.24 | casey, Flayy, innocent, kisserek, olimp |
|           49 |      591 | 2024-08-22 | OG                | L   | 1.000      | -            | -                | -                | -         |   -10.78 | casey, Flayy, innocent, kisserek, olimp |
|           48 |      624 | 2024-08-21 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -8.61 | casey, Flayy, innocent, kisserek, olimp |
|           47 |      656 | 2024-08-21 | Zero Tenacity     | W   | 1.000      | 0.143        | 0.163 (0.023)    | 1.000 (0.143)    | 0 (0.000) |    19.29 | casey, Flayy, innocent, kisserek, olimp |
|           46 |      693 | 2024-08-20 | Rhyno             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.23 | casey, Flayy, innocent, kisserek, olimp |
|           45 |      825 | 2024-08-15 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -3.25 | casey, Flayy, innocent, kisserek, olimp |
|           44 |      895 | 2024-08-13 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.08 | casey, Flayy, innocent, kisserek, olimp |
|           43 |     1069 | 2024-08-07 | Sangal            | L   | 0.987      | -            | -                | -                | -         |    -2.65 | casey, Flayy, innocent, kisserek, olimp |
|           42 |     1095 | 2024-08-07 | TALON             | L   | 0.985      | -            | -                | -                | -         |   -27.09 | casey, Flayy, innocent, kisserek, olimp |
|           41 |     1140 | 2024-08-05 | SINNERS           | L   | 0.974      | -            | -                | -                | -         |   -13.66 | casey, Flayy, innocent, kisserek, olimp |
|           40 |     1364 | 2024-07-30 | RUSH B            | L   | 0.935      | -            | -                | -                | -         |   -17.42 | casey, Flayy, innocent, kisserek, olimp |
|           39 |     1562 | 2024-07-24 | SAW               | W   | 0.894      | 0.500        | 0.330 (0.148)    | 0.747 (0.334)    | 0 (0.000) |    26.02 | casey, Flayy, innocent, kisserek, olimp |
|           38 |     1573 | 2024-07-24 | 9INE              | L   | 0.892      | -            | -                | -                | -         |   -14.87 | casey, Flayy, innocent, kisserek, olimp |
|           37 |     1616 | 2024-07-23 | Enterprise        | W   | 0.885      | 0.371        | 0.039 (0.013)    | 0.697 (0.229)    | -         |    11.37 | casey, Flayy, innocent, kisserek, olimp |
|           36 |     1633 | 2024-07-22 | Insilio           | W   | 0.879      | 0.371        | -                | 0.654 (0.213)    | -         |    12.86 | casey, Flayy, innocent, kisserek, olimp |
|           35 |     1734 | 2024-07-19 | B8                | L   | 0.859      | -            | -                | -                | -         |    -7.72 | casey, Flayy, innocent, kisserek, olimp |
|           34 |     1799 | 2024-07-18 | Illuminar         | W   | 0.852      | -            | -                | -                | -         |    11.01 | casey, Flayy, innocent, kisserek, olimp |
|           33 |     1860 | 2024-07-17 | 9INE              | W   | 0.846      | 0.500        | 0.020 (0.009)    | 0.707 (0.299)    | -         |    12.06 | casey, Flayy, innocent, kisserek, olimp |
|           32 |     1951 | 2024-07-15 | Apogee            | L   | 0.834      | -            | -                | -                | -         |   -19.34 | casey, Flayy, innocent, kisserek, olimp |
|           31 |     1958 | 2024-07-15 | Sangal            | L   | 0.832      | -            | -                | -                | -         |    -3.25 | casey, Flayy, innocent, kisserek, olimp |
|           30 |     1998 | 2024-07-12 | Enterprise        | W   | 0.813      | 0.371        | 0.039 (0.012)    | 0.697 (0.210)    | -         |    11.47 | casey, Flayy, innocent, kisserek, olimp |
|           29 |     2035 | 2024-07-10 | Belarus           | W   | 0.801      | -            | -                | -                | -         |     1.22 | casey, Flayy, innocent, kisserek, olimp |
|           28 |     2047 | 2024-07-09 | 500               | W   | 0.795      | -            | -                | -                | -         |     2.17 | casey, Flayy, innocent, kisserek, olimp |
|           27 |     2083 | 2024-07-08 | Verdant           | W   | 0.785      | -            | -                | -                | -         |     8.94 | casey, Flayy, innocent, kisserek, olimp |
|           26 |     2272 | 2024-06-13 | Sampi             | L   | 0.621      | -            | -                | -                | -         |   -11.68 | casey, Flayy, innocent, kisserek, olimp |
|           25 |     2295 | 2024-06-12 | Qiang             | L   | 0.615      | -            | -                | -                | -         |   -10.74 | casey, Flayy, innocent, kisserek, olimp |
|           24 |     2339 | 2024-06-10 | Permitta          | W   | 0.601      | 0.379        | -                | 0.968 (0.221)    | -         |     8.99 | casey, Flayy, innocent, kisserek, olimp |
|           23 |     2377 | 2024-06-09 | Rhyno             | L   | 0.595      | -            | -                | -                | -         |   -10.76 | casey, Flayy, kisserek, olimp, SZPERO   |
|           22 |     2502 | 2024-06-07 | BLEED             | W   | 0.581      | 0.500        | 0.101 (0.029)    | 0.541 (0.157)    | -         |    15.05 | casey, Flayy, innocent, kisserek, olimp |
|           21 |     2627 | 2024-06-05 | 9INE              | W   | 0.568      | 0.500        | -                | 0.707 (0.201)    | -         |     8.38 | casey, Flayy, innocent, kisserek, olimp |
|           20 |     2817 | 2024-05-30 | Qiang             | W   | 0.528      | -            | -                | -                | -         |     7.68 | casey, Flayy, innocent, kisserek, olimp |
|           19 |     2854 | 2024-05-29 | UNiTY             | L   | 0.520      | -            | -                | -                | -         |    -9.43 | casey, Flayy, innocent, kisserek, olimp |
|           18 |     2941 | 2024-05-25 | kONO              | W   | 0.492      | -            | -                | -                | -         |     5.88 | casey, Flayy, innocent, kisserek, olimp |
|           17 |     3055 | 2024-05-21 | UNiTY             | L   | 0.465      | -            | -                | -                | -         |    -8.14 | casey, Flayy, innocent, kisserek, olimp |
|           16 |     3078 | 2024-05-20 | The Prodigies     | W   | 0.461      | -            | -                | -                | -         |     1.29 | casey, Flayy, innocent, kisserek, olimp |
|           15 |     3146 | 2024-05-18 | B8                | L   | 0.446      | -            | -                | -                | -         |    -4.19 | casey, Flayy, innocent, kisserek, olimp |
|           14 |     3174 | 2024-05-17 | Gaimin Gladiators | W   | 0.440      | -            | -                | -                | -         |     6.63 | casey, Flayy, innocent, kisserek, olimp |
|           13 |     3669 | 2024-04-27 | Aurora            | L   | 0.312      | -            | -                | -                | -         |    -0.68 | casey, Flayy, innocent, kisserek, olimp |
|           12 |     3719 | 2024-04-26 | MIBR              | W   | 0.299      | 0.500        | 0.156 (0.023)    | -                | 1 (0.299) |     8.82 | casey, Flayy, innocent, kisserek, olimp |
|           11 |     3721 | 2024-04-25 | Rooster           | W   | 0.298      | -            | -                | -                | 1 (0.298) |     2.43 | casey, Flayy, innocent, kisserek, olimp |
|           10 |     3869 | 2024-04-19 | Apogee            | L   | 0.255      | -            | -                | -                | -         |    -5.82 | casey, Flayy, innocent, kisserek, olimp |
|            9 |     4054 | 2024-04-13 | Monte             | L   | 0.214      | -            | -                | -                | -         |    -3.21 | casey, Flayy, innocent, kisserek, olimp |
|            8 |     4188 | 2024-04-09 | B8                | W   | 0.188      | 0.500        | 0.176 (0.017)    | -                | -         |     3.99 | casey, Flayy, innocent, kisserek, olimp |
|            7 |     4330 | 2024-04-04 | ALTERNATE aTTaX   | W   | 0.154      | -            | -                | -                | -         |     3.22 | casey, Flayy, innocent, kisserek, olimp |
|            6 |     4380 | 2024-04-03 | SINNERS           | L   | 0.146      | -            | -                | -                | -         |    -1.03 | casey, Flayy, innocent, kisserek, olimp |
|            5 |     4461 | 2024-03-28 | ex-Sprout         | W   | 0.108      | -            | -                | -                | -         |     0.17 | casey, Flayy, innocent, kisserek, olimp |
|            4 |     4495 | 2024-03-27 | B8                | L   | 0.102      | -            | -                | -                | -         |    -0.99 | casey, Flayy, innocent, kisserek, olimp |
|            3 |     4504 | 2024-03-27 | Sashi             | W   | 0.101      | -            | -                | -                | -         |     2.22 | casey, Flayy, innocent, kisserek, olimp |
|            2 |     4534 | 2024-03-25 | Aurora            | L   | 0.088      | -            | -                | -                | -         |    -0.16 | casey, Flayy, innocent, kisserek, olimp |
|            1 |     4733 | 2024-03-14 | Apogee            | L   | 0.015      | -            | -                | -                | -         |    -0.34 | casey, Flayy, kisserek, olimp, SZPERO   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,579.16)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      0.899 | $3,000.00      | $2,695.83       |
| 2024-06-13 |      0.622 | $1,089.00      | $676.89         |
| 2024-06-09 |      0.594 | $2,000.00      | $1,188.19       |
| 2024-05-18 |      0.448 | $2,000.00      | $895.56         |
| 2024-04-28 |      0.312 | $10,000.00     | $3,122.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
