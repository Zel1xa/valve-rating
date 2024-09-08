### Roster Details<br />
Team Name: Gaimin Gladiators<br />
Roster: kraghen, nicoodoz, Nodios, Queenix, roeJ<br />
Global Rank: [71](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  929.1<br />
<br />
Final Rank Value (929.1) = Starting Rank Value (893.5) + Head To Head Adjustments (35.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.364[<sup>1</sup>](#table2)
- Bounty Collected: 0.373[<sup>2</sup>](#table1)
- Opponent Network: 0.262[<sup>2</sup>](#table1)
- LAN Wins: 0.020[<sup>2</sup>](#table1)

The average of these factors is 0.255<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 893.5
- 400 + ( ( 0.255 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 893.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           57 |       13 | 2024-09-07 | Spirit Academy    | L   | 1.000      | -            | -                | -                | -         |   -19.78 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           56 |       39 | 2024-09-06 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -13.83 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           55 |       88 | 2024-09-05 | BetBoom           | L   | 1.000      | -            | -                | -                | -         |    -4.40 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           54 |       99 | 2024-09-05 | Revenant          | W   | 1.000      | 0.435        | 0.042 (0.018)    | 0.666 (0.289)    | 0 (0.000) |    13.48 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           53 |      124 | 2024-09-04 | Rhyno             | W   | 1.000      | 0.384        | -                | 0.247 (0.095)    | 0 (0.000) |     5.13 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           52 |      163 | 2024-09-03 | SINNERS           | W   | 1.000      | 0.384        | 0.081 (0.031)    | 1.000 (0.384)    | 0 (0.000) |    23.42 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           51 |      189 | 2024-09-02 | Alliance          | W   | 1.000      | 0.435        | -                | 0.363 (0.158)    | 0 (0.000) |    13.29 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           50 |      215 | 2024-08-31 | SINNERS           | W   | 1.000      | 0.435        | 0.081 (0.035)    | 1.000 (0.435)    | 0 (0.000) |    25.12 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           49 |      269 | 2024-08-29 | Sampi             | W   | 1.000      | 0.435        | 0.032 (0.014)    | 1.000 (0.435)    | 0 (0.000) |    18.05 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           48 |      398 | 2024-08-27 | PARIVISION        | W   | 1.000      | 0.384        | 0.046 (0.018)    | 0.730 (0.281)    | -         |    25.24 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           47 |      455 | 2024-08-26 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.711 (0.309)    | -         |    19.78 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           46 |      483 | 2024-08-26 | DASH              | L   | 1.000      | -            | -                | -                | -         |   -22.78 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           45 |      650 | 2024-08-21 | FAVBET            | L   | 1.000      | -            | -                | -                | -         |   -16.27 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           44 |      721 | 2024-08-19 | KOI               | L   | 1.000      | -            | -                | -                | -         |   -13.21 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           43 |      814 | 2024-08-15 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -2.53 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           42 |      822 | 2024-08-15 | Betera            | W   | 1.000      | -            | -                | -                | -         |     6.54 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           41 |      883 | 2024-08-13 | Meteor            | W   | 1.000      | -            | -                | -                | -         |     9.61 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           40 |     1176 | 2024-08-04 | TYLOO             | L   | 0.967      | -            | -                | -                | -         |   -12.48 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           39 |     1481 | 2024-07-26 | Passion UA        | L   | 0.908      | -            | -                | -                | -         |    -6.78 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           38 |     2234 | 2024-06-14 | GUN5              | L   | 0.628      | -            | -                | -                | -         |    -6.90 | kraghen, Nodios, Patti, Queenix, salazar |
|           37 |     2360 | 2024-06-10 | Enterprise        | L   | 0.599      | -            | -                | -                | -         |   -10.04 | kraghen, Nodios, Patti, Queenix, salazar |
|           36 |     2416 | 2024-06-09 | 5W                | L   | 0.593      | -            | -                | -                | -         |    -9.68 | kraghen, Nodios, Patti, Queenix, salazar |
|           35 |     2460 | 2024-06-08 | EYEBALLERS        | W   | 0.587      | -            | -                | -                | -         |     7.83 | kraghen, Nodios, Patti, Queenix, salazar |
|           34 |     2516 | 2024-06-07 | 3DMAX             | L   | 0.581      | -            | -                | -                | -         |    -0.35 | kraghen, Nodios, Patti, Queenix, salazar |
|           33 |     2581 | 2024-06-06 | Astralis Talent   | W   | 0.574      | -            | -                | -                | -         |     4.46 | kraghen, Nodios, Patti, Queenix, salazar |
|           32 |     2833 | 2024-05-30 | Lynn Vision       | L   | 0.525      | -            | -                | -                | -         |    -8.28 | kraghen, Nodios, Patti, Queenix, salazar |
|           31 |     2876 | 2024-05-28 | The MongolZ       | L   | 0.513      | -            | -                | -                | -         |    -0.07 | kraghen, Nodios, Patti, Queenix, salazar |
|           30 |     3162 | 2024-05-17 | ENCE              | L   | 0.442      | -            | -                | -                | -         |    -2.18 | kraghen, Nodios, Patti, Queenix, salazar |
|           29 |     3168 | 2024-05-17 | GamerLegion       | L   | 0.441      | -            | -                | -                | -         |    -3.98 | kraghen, Nodios, Patti, Queenix, salazar |
|           28 |     3174 | 2024-05-17 | Rebels            | L   | 0.440      | -            | -                | -                | -         |    -6.63 | kraghen, Nodios, Patti, Queenix, salazar |
|           27 |     3260 | 2024-05-15 | BLEED             | W   | 0.427      | 0.384        | 0.101 (0.017)    | -                | -         |    11.50 | kraghen, Nodios, Patti, Queenix, salazar |
|           26 |     3485 | 2024-05-07 | Grannys Knockers  | L   | 0.372      | -            | -                | -                | -         |    -8.73 | kraghen, Nodios, Patti, Queenix, salazar |
|           25 |     3496 | 2024-05-06 | 500               | W   | 0.367      | -            | -                | -                | -         |     1.17 | kraghen, Nodios, Patti, Queenix, salazar |
|           24 |     3507 | 2024-05-05 | Sashi             | W   | 0.361      | -            | -                | -                | -         |     8.58 | kraghen, Nodios, Patti, Queenix, salazar |
|           23 |     3516 | 2024-05-05 | Kronjyllands      | W   | 0.360      | -            | -                | -                | -         |     0.63 | kraghen, Nodios, Patti, Queenix, salazar |
|           22 |     3547 | 2024-05-03 | AMKAL             | L   | 0.347      | -            | -                | -                | -         |    -2.76 | kraghen, Nodios, Patti, Queenix, salazar |
|           21 |     3568 | 2024-05-02 | HAVU              | W   | 0.341      | -            | -                | -                | -         |     1.47 | kraghen, Nodios, Patti, Queenix, salazar |
|           20 |     3580 | 2024-05-02 | SINNERS           | W   | 0.339      | 0.435        | 0.081 (0.012)    | 1.000 (0.148)    | -         |     8.11 | kraghen, Nodios, Patti, Queenix, salazar |
|           19 |     3613 | 2024-04-30 | AMKAL             | L   | 0.328      | -            | -                | -                | -         |    -2.57 | kraghen, Nodios, Patti, Queenix, salazar |
|           18 |     3642 | 2024-04-29 | kONO              | L   | 0.320      | -            | -                | -                | -         |    -6.16 | kraghen, Nodios, Patti, Queenix, salazar |
|           17 |     3668 | 2024-04-28 | 9 Pandas          | L   | 0.312      | -            | -                | -                | -         |    -3.62 | kraghen, Nodios, Patti, Queenix, salazar |
|           16 |     3716 | 2024-04-26 | ALTERNATE aTTaX   | L   | 0.299      | -            | -                | -                | -         |    -3.41 | kraghen, Nodios, Patti, Queenix, salazar |
|           15 |     3777 | 2024-04-23 | Sashi             | L   | 0.280      | -            | -                | -                | -         |    -2.54 | kraghen, Nodios, Patti, Queenix, salazar |
|           14 |     3792 | 2024-04-22 | BLEED             | L   | 0.273      | -            | -                | -                | -         |    -4.78 | kraghen, Nodios, Patti, Queenix, salazar |
|           13 |     3810 | 2024-04-21 | AMKAL             | W   | 0.267      | 0.384        | 0.123 (0.013)    | -                | -         |     6.18 | kraghen, Nodios, Patti, Queenix, salazar |
|           12 |     3847 | 2024-04-20 | Nemiga            | W   | 0.259      | 0.384        | 0.303 (0.030)    | -                | -         |     6.60 | kraghen, Nodios, Patti, Queenix, salazar |
|           11 |     3989 | 2024-04-17 | SINNERS           | W   | 0.239      | 0.384        | -                | 1.000 (0.092)    | -         |     6.04 | kraghen, Nodios, Patti, Queenix, salazar |
|           10 |     4010 | 2024-04-16 | Permitta          | W   | 0.233      | -            | -                | -                | -         |     4.19 | kraghen, Nodios, Patti, Queenix, salazar |
|            9 |     4338 | 2024-04-04 | JANO              | W   | 0.152      | -            | -                | -                | -         |     0.95 | kraghen, Nodios, Patti, Queenix, salazar |
|            8 |     4553 | 2024-03-23 | G2                | L   | 0.074      | -            | -                | -                | -         |    -0.01 | kraghen, Nodios, Patti, Queenix, salazar |
|            7 |     4562 | 2024-03-22 | FURIA             | W   | 0.068      | 1.000        | 0.319 (0.022)    | -                | 1 (0.068) |     2.11 | kraghen, Nodios, Patti, Queenix, salazar |
|            6 |     4582 | 2024-03-21 | Cloud9            | L   | 0.062      | -            | -                | -                | -         |    -1.26 | kraghen, Nodios, Patti, Queenix, salazar |
|            5 |     4597 | 2024-03-21 | MOUZ              | L   | 0.060      | -            | -                | -                | -         |    -0.01 | kraghen, Nodios, Patti, Queenix, salazar |
|            4 |     4629 | 2024-03-19 | Imperial          | W   | 0.048      | -            | -                | -                | 1 (0.048) |     1.06 | kraghen, Nodios, Patti, Queenix, salazar |
|            3 |     4644 | 2024-03-18 | Lynn Vision       | W   | 0.040      | -            | -                | -                | 1 (0.040) |     0.65 | kraghen, Nodios, Patti, Queenix, salazar |
|            2 |     4663 | 2024-03-17 | The MongolZ       | W   | 0.035      | -            | -                | -                | 1 (0.035) |     1.09 | kraghen, Nodios, Patti, Queenix, salazar |
|            1 |     4675 | 2024-03-17 | Cloud9            | L   | 0.033      | -            | -                | -                | -         |    -0.67 | kraghen, Nodios, Patti, Queenix, salazar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,424.03)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.448 | $1,000.00      | $447.78         |
| 2024-05-04 |      0.354 | $2,000.00      | $708.33         |
| 2024-05-02 |      0.341 | $1,000.00      | $340.83         |
| 2024-04-22 |      0.273 | $5,000.00      | $1,365.97       |
| 2024-03-31 |      0.128 | $20,000.00     | $2,561.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
