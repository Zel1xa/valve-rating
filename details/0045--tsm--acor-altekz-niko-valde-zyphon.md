### Roster Details<br />
Team Name: TSM<br />
Roster: acoR, Altekz, niko, valde, Zyphon<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1047.5<br />
<br />
Final Rank Value (1047.5) = Starting Rank Value (1008.7) + Head To Head Adjustments (38.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.465[<sup>2</sup>](#table1)
- Opponent Network: 0.346[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.314<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1008.7
- 400 + ( ( 0.314 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1008.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           48 |      129 | 2024-09-04 | Young Ninjas     | L   | 1.000      | -            | -                | -                | -         |   -21.55 | acoR, Altekz, niko, valde, Zyphon |
|           47 |      155 | 2024-09-03 | B8               | W   | 1.000      | 0.384        | 0.176 (0.067)    | 1.000 (0.384)    | 0 (0.000) |    18.32 | acoR, Altekz, niko, valde, Zyphon |
|           46 |      187 | 2024-09-02 | Into the Breach  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.90 | acoR, Altekz, niko, valde, Zyphon |
|           45 |      280 | 2024-08-29 | MOUZ NXT         | L   | 1.000      | -            | -                | -                | -         |   -17.80 | acoR, Altekz, niko, valde, Zyphon |
|           44 |      376 | 2024-08-27 | Monte Gen        | L   | 1.000      | -            | -                | -                | -         |   -22.91 | acoR, Altekz, niko, valde, Zyphon |
|           43 |      385 | 2024-08-27 | Sampi            | W   | 1.000      | 0.384        | -                | 1.000 (0.384)    | 0 (0.000) |     9.53 | acoR, Altekz, niko, valde, Zyphon |
|           42 |      463 | 2024-08-26 | ECSTATIC         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.66 | acoR, Altekz, niko, valde, Zyphon |
|           41 |      547 | 2024-08-23 | KOI              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.34 | acoR, Altekz, niko, valde, Zyphon |
|           40 |      567 | 2024-08-23 | BC.Game          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.80 | acoR, Altekz, niko, valde, Zyphon |
|           39 |      580 | 2024-08-22 | 1WIN             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.46 | acoR, Altekz, niko, valde, Zyphon |
|           38 |      631 | 2024-08-21 | GamerLegion      | L   | 1.000      | -            | -                | -                | -         |   -13.86 | acoR, Altekz, niko, valde, Zyphon |
|           37 |      666 | 2024-08-21 | BLEED            | L   | 1.000      | -            | -                | -                | -         |   -13.67 | acoR, Altekz, niko, valde, Zyphon |
|           36 |      697 | 2024-08-20 | Metizport        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.09 | acoR, Altekz, niko, valde, Zyphon |
|           35 |      847 | 2024-08-14 | ALTERNATE aTTaX  | W   | 1.000      | 0.384        | 0.102 (0.039)    | 0.837 (0.322)    | 0 (0.000) |     7.69 | acoR, Altekz, niko, valde, Zyphon |
|           34 |      922 | 2024-08-12 | Aurora           | W   | 1.000      | 0.500        | 0.290 (0.145)    | 0.603 (0.301)    | 0 (0.000) |    25.57 | acoR, Altekz, niko, valde, Zyphon |
|           33 |      937 | 2024-08-12 | Johnny Speeds    | W   | 1.000      | 0.333        | 0.102 (0.034)    | 0.956 (0.319)    | -         |    22.58 | acoR, Altekz, niko, valde, Zyphon |
|           32 |      955 | 2024-08-11 | kONO             | L   | 1.000      | -            | -                | -                | -         |   -21.78 | acoR, Altekz, niko, valde, Zyphon |
|           31 |      962 | 2024-08-11 | Enterprise       | W   | 1.000      | -            | -                | -                | -         |    10.65 | acoR, Altekz, niko, valde, Zyphon |
|           30 |      964 | 2024-08-11 | Illuminar        | W   | 1.000      | -            | -                | -                | -         |     9.22 | acoR, Altekz, niko, valde, Zyphon |
|           29 |      986 | 2024-08-10 | Into the Breach  | W   | 1.000      | -            | -                | -                | -         |    10.11 | acoR, Altekz, niko, valde, Zyphon |
|           28 |     1010 | 2024-08-09 | Revenant         | L   | 0.999      | -            | -                | -                | -         |   -19.30 | acoR, Altekz, niko, valde, Zyphon |
|           27 |     1015 | 2024-08-09 | Permitta         | W   | 0.999      | 0.333        | -                | 0.968 (0.322)    | -         |    11.87 | acoR, Altekz, niko, valde, Zyphon |
|           26 |     1030 | 2024-08-08 | Johnny Speeds    | L   | 0.993      | -            | -                | -                | -         |    -8.55 | acoR, Altekz, niko, valde, Zyphon |
|           25 |     1073 | 2024-08-07 | Metizport        | L   | 0.987      | -            | -                | -                | -         |   -19.74 | acoR, Altekz, niko, valde, Zyphon |
|           24 |     1094 | 2024-08-07 | Enterprise       | W   | 0.985      | -            | -                | -                | -         |    10.69 | acoR, Altekz, niko, valde, Zyphon |
|           23 |     1116 | 2024-08-06 | Betera           | W   | 0.981      | -            | -                | -                | -         |     3.46 | acoR, Altekz, niko, valde, Zyphon |
|           22 |     1135 | 2024-08-06 | ECSTATIC         | W   | 0.979      | -            | -                | -                | -         |     5.62 | acoR, Altekz, niko, valde, Zyphon |
|           21 |     1146 | 2024-08-05 | Sashi            | W   | 0.973      | -            | -                | -                | -         |    19.80 | acoR, Altekz, niko, valde, Zyphon |
|           20 |     1150 | 2024-08-05 | 777              | W   | 0.973      | -            | -                | -                | -         |     3.92 | acoR, Altekz, niko, valde, Zyphon |
|           19 |     1166 | 2024-08-04 | 1WIN             | L   | 0.967      | -            | -                | -                | -         |   -16.23 | acoR, Altekz, niko, valde, Zyphon |
|           18 |     1173 | 2024-08-04 | TALON            | W   | 0.967      | -            | -                | -                | -         |     2.42 | acoR, Altekz, niko, valde, Zyphon |
|           17 |     1229 | 2024-08-02 | PARIVISION       | L   | 0.955      | -            | -                | -                | -         |   -10.98 | acoR, Altekz, niko, valde, Zyphon |
|           16 |     1362 | 2024-07-30 | 9 Pandas         | W   | 0.935      | 0.500        | -                | 0.732 (0.342)    | -         |    17.39 | acoR, Altekz, niko, valde, Zyphon |
|           15 |     1419 | 2024-07-29 | GUN5             | L   | 0.926      | -            | -                | -                | -         |   -18.63 | acoR, Altekz, niko, valde, Zyphon |
|           14 |     1448 | 2024-07-28 | 1WIN             | L   | 0.920      | -            | -                | -                | -         |   -17.33 | acoR, Altekz, niko, valde, Zyphon |
|           13 |     1619 | 2024-07-22 | CPH Wolves       | L   | 0.882      | -            | -                | -                | -         |   -21.04 | acoR, Altekz, niko, valde, Zyphon |
|           12 |     1662 | 2024-07-21 | Preasy           | W   | 0.872      | -            | -                | -                | -         |     4.31 | acoR, Altekz, niko, valde, Zyphon |
|           11 |     1768 | 2024-07-18 | Nexus            | L   | 0.854      | -            | -                | -                | -         |   -23.12 | acoR, Altekz, niko, valde, Zyphon |
|           10 |     1792 | 2024-07-18 | LEON             | W   | 0.852      | -            | -                | -                | -         |     2.33 | acoR, Altekz, niko, valde, Zyphon |
|            9 |     1838 | 2024-07-17 | GUN5             | W   | 0.848      | 0.500        | 0.091 (0.039)    | 0.959 (0.407)    | -         |     9.84 | acoR, Altekz, niko, valde, Zyphon |
|            8 |     1859 | 2024-07-17 | Into the Breach  | L   | 0.846      | -            | -                | -                | -         |   -20.69 | acoR, Altekz, niko, valde, Zyphon |
|            7 |     1907 | 2024-07-16 | 500              | W   | 0.839      | -            | -                | -                | -         |     1.14 | acoR, Altekz, niko, valde, Zyphon |
|            6 |     1942 | 2024-07-15 | 3DMAX            | W   | 0.835      | 0.500        | 0.509 (0.212)    | 0.951 (0.397)    | -         |    24.06 | acoR, Altekz, niko, valde, Zyphon |
|            5 |     1987 | 2024-07-13 | Sashi            | W   | 0.820      | 0.358        | 0.151 (0.044)    | -                | -         |    15.66 | acoR, Altekz, niko, valde, Zyphon |
|            4 |     2000 | 2024-07-12 | Johnny Speeds    | W   | 0.813      | 0.358        | 0.102 (0.030)    | -                | -         |    16.95 | acoR, Altekz, niko, valde, Zyphon |
|            3 |     2059 | 2024-07-09 | Passion UA       | W   | 0.793      | 0.358        | 0.164 (0.046)    | 1.000 (0.284)    | -         |    13.48 | acoR, Altekz, niko, valde, Zyphon |
|            2 |     2078 | 2024-07-08 | FLuffy Gangsters | L   | 0.787      | -            | -                | -                | -         |   -22.14 | acoR, Altekz, niko, valde, Zyphon |
|            1 |     2081 | 2024-07-08 | Passion UA       | W   | 0.786      | 0.358        | 0.164 (0.046)    | -                | -         |    13.21 | acoR, Altekz, niko, valde, Zyphon |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,548.48)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-08-12 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-13 |      0.820 | $12,864.00     | $10,548.48      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
