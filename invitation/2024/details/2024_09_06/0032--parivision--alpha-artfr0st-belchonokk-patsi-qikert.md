### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [32](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [24]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  1121.2<br />
<br />
Final Rank Value (1121.2) = Starting Rank Value (1094.7) + Head To Head Adjustments (26.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.427[<sup>1</sup>](#table2)
- Bounty Collected: 0.481[<sup>2</sup>](#table1)
- Opponent Network: 0.324[<sup>2</sup>](#table1)
- LAN Wins: 0.189[<sup>2</sup>](#table1)

The average of these factors is 0.355<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1094.7
- 400 + ( ( 0.355 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 1094.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           70 |       91 | 2024-09-04 | Monte             | W   | 1.000      | 0.384        | -                | 0.714 (0.274)    | 0 (0.000) |    12.94 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           69 |      249 | 2024-08-29 | AMKAL             | W   | 1.000      | 0.384        | 0.123 (0.047)    | -                | 0 (0.000) |    11.86 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           68 |      361 | 2024-08-27 | Gaimin Gladiators | L   | 1.000      | -            | -                | -                | -         |   -25.16 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           67 |      462 | 2024-08-25 | Monte Gen         | L   | 1.000      | -            | -                | -                | -         |   -25.78 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           66 |      522 | 2024-08-23 | GamerLegion       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.51 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           65 |      557 | 2024-08-22 | B8                | W   | 1.000      | 0.143        | 0.176 (0.025)    | -                | 0 (0.000) |    15.58 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           64 |      590 | 2024-08-21 | SINNERS           | L   | 1.000      | -            | -                | -                | -         |   -16.36 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           63 |      611 | 2024-08-21 | Enterprise        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.09 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           62 |      652 | 2024-08-20 | 9 Pandas          | W   | 1.000      | 0.500        | 0.059 (0.030)    | 0.756 (0.378)    | 0 (0.000) |    15.79 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           61 |      683 | 2024-08-19 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -4.38 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           60 |      778 | 2024-08-15 | OG                | L   | 1.000      | -            | -                | -                | -         |   -21.87 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           59 |      783 | 2024-08-15 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.95 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           58 |      796 | 2024-08-15 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.45 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           57 |      834 | 2024-08-13 | RUSH B            | W   | 1.000      | -            | -                | -                | -         |     8.51 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           56 |      880 | 2024-08-12 | Monte             | W   | 1.000      | 0.500        | -                | 0.714 (0.357)    | -         |    11.41 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           55 |      966 | 2024-08-09 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -4.22 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           54 |     1045 | 2024-08-07 | SINNERS           | W   | 0.998      | -            | -                | -                | -         |    11.80 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           53 |     1076 | 2024-08-06 | Sangal            | L   | 0.993      | -            | -                | -                | -         |    -6.80 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |     1090 | 2024-08-06 | Aurora Young Blud | W   | 0.991      | 0.435        | -                | 0.692 (0.298)    | -         |    11.43 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |     1110 | 2024-08-05 | ENCE              | W   | 0.985      | 0.435        | 0.131 (0.056)    | -                | -         |    21.68 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |     1127 | 2024-08-04 | Betera            | L   | 0.980      | -            | -                | -                | -         |   -28.59 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |     1166 | 2024-08-03 | GUN5              | L   | 0.973      | -            | -                | -                | -         |   -23.65 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |     1181 | 2024-08-03 | CYBERSHOKE        | W   | 0.971      | 0.435        | -                | 0.720 (0.304)    | -         |     8.47 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |     1192 | 2024-08-02 | TSM               | W   | 0.967      | 0.500        | 0.057 (0.028)    | 0.922 (0.446)    | -         |    11.06 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |     1233 | 2024-08-01 | 9 Pandas          | W   | 0.960      | 0.500        | 0.059 (0.028)    | 0.756 (0.363)    | -         |    13.31 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |     1348 | 2024-07-30 | Permitta          | W   | 0.944      | -            | -                | -                | -         |     8.54 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |     1448 | 2024-07-26 | BLEED             | L   | 0.919      | -            | -                | -                | -         |    -9.38 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1461 | 2024-07-26 | True Rippers      | W   | 0.918      | -            | -                | -                | 1 (0.918) |     2.73 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1493 | 2024-07-25 | ENCE              | L   | 0.912      | -            | -                | -                | -         |    -8.82 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1531 | 2024-07-24 | The MongolZ       | W   | 0.905      | 0.650        | 0.865 (0.509)    | 0.642 (0.378)    | 1 (0.905) |    27.66 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1538 | 2024-07-24 | Aurora            | L   | 0.904      | -            | -                | -                | -         |    -4.68 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     2213 | 2024-06-14 | Permitta          | L   | 0.638      | -            | -                | -                | -         |   -14.43 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     2314 | 2024-06-10 | RUSH B            | W   | 0.612      | -            | -                | -                | -         |     5.42 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     2320 | 2024-06-10 | 3DMAX             | L   | 0.612      | -            | -                | -                | -         |    -1.72 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     2326 | 2024-06-10 | SINNERS           | L   | 0.611      | -            | -                | -                | -         |   -10.16 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     2357 | 2024-06-09 | Aurora            | L   | 0.606      | -            | -                | -                | -         |    -3.94 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     2363 | 2024-06-09 | 9 Pandas          | W   | 0.605      | -            | -                | -                | -         |     9.31 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     2374 | 2024-06-09 | Monte             | W   | 0.605      | -            | -                | -                | -         |     6.89 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           32 |     2376 | 2024-06-09 | SAW               | L   | 0.605      | -            | -                | -                | -         |    -2.03 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           31 |     2596 | 2024-06-05 | Aurora            | L   | 0.580      | -            | -                | -                | -         |    -2.92 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           30 |     2643 | 2024-06-04 | Monte             | W   | 0.573      | -            | -                | -                | -         |     6.85 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           29 |     3048 | 2024-05-20 | Sangal            | L   | 0.472      | -            | -                | -                | -         |    -4.51 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     3127 | 2024-05-17 | Zero Tenacity     | W   | 0.453      | 0.500        | 0.138 (0.031)    | 1.000 (0.227)    | -         |     6.53 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     3158 | 2024-05-16 | Aurora            | L   | 0.447      | -            | -                | -                | -         |    -2.11 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     3174 | 2024-05-16 | Eternal Fire      | L   | 0.445      | -            | -                | -                | -         |    -0.18 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     3213 | 2024-05-15 | B8                | W   | 0.440      | 0.500        | 0.176 (0.039)    | 1.000 (0.220)    | -         |     6.91 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     3398 | 2024-05-09 | Endpoint          | L   | 0.399      | -            | -                | -                | -         |    -7.06 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     3555 | 2024-05-01 | Passion UA        | L   | 0.346      | -            | -                | -                | -         |    -6.55 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     3571 | 2024-05-01 | fnatic            | L   | 0.344      | -            | -                | -                | -         |    -2.16 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     3597 | 2024-04-29 | 3DMAX             | L   | 0.333      | -            | -                | -                | -         |    -0.41 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     3606 | 2024-04-29 | Zero Tenacity     | W   | 0.332      | -            | -                | -                | -         |     4.60 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     3642 | 2024-04-27 | Sangal            | W   | 0.319      | 0.500        | 0.248 (0.040)    | -                | -         |     7.36 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     3672 | 2024-04-26 | SINNERS           | W   | 0.312      | -            | -                | -                | -         |     5.80 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     3701 | 2024-04-25 | ex-Guild Eagles   | W   | 0.306      | -            | -                | -                | -         |     1.50 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     3720 | 2024-04-24 | MOUZ NXT          | W   | 0.299      | -            | -                | -                | -         |     3.72 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     3772 | 2024-04-21 | Nexus             | W   | 0.279      | -            | -                | -                | -         |     1.76 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           14 |     3775 | 2024-04-21 | B8                | L   | 0.278      | -            | -                | -                | -         |    -4.73 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           13 |     3831 | 2024-04-19 | Zero Tenacity     | L   | 0.267      | -            | -                | -                | -         |    -4.62 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           12 |     3930 | 2024-04-17 | HAVU              | W   | 0.253      | -            | -                | -                | -         |     0.44 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           11 |     3933 | 2024-04-17 | Permitta          | L   | 0.252      | -            | -                | -                | -         |    -5.30 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           10 |     4057 | 2024-04-11 | 500               | L   | 0.213      | -            | -                | -                | -         |    -6.13 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|            9 |     4092 | 2024-04-10 | Aurora            | L   | 0.207      | -            | -                | -                | -         |    -0.84 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     4152 | 2024-04-09 | RUSH B            | L   | 0.200      | -            | -                | -                | -         |    -4.95 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     4321 | 2024-04-03 | MOUZ NXT          | L   | 0.160      | -            | -                | -                | -         |    -3.27 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     4333 | 2024-04-03 | Space             | W   | 0.159      | -            | -                | -                | -         |     0.87 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     4369 | 2024-04-02 | AMKAL             | L   | 0.153      | -            | -                | -                | -         |    -2.34 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     4376 | 2024-04-02 | Insilio           | L   | 0.152      | -            | -                | -                | -         |    -3.63 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     4388 | 2024-04-01 | Metizport         | W   | 0.146      | -            | -                | -                | -         |     0.58 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     4554 | 2024-03-21 | FORZE             | W   | 0.072      | -            | -                | -                | -         |     0.36 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     4736 | 2024-03-13 | 3DMAX             | W   | 0.019      | -            | -                | -                | -         |     0.58 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($14,044.43)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      0.993 | $10,000.00     | $9,928.94       |
| 2024-06-09 |      0.606 | $6,500.00      | $3,939.12       |
| 2024-05-02 |      0.353 | $500.00        | $176.38         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
