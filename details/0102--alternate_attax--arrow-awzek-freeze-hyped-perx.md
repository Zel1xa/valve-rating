### Roster Details<br />
Team Name: ALTERNATE aTTaX<br />
Roster: ArroW, awzek, FreeZe, hyped, PerX<br />
Global Rank: [102](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  855.1<br />
<br />
Final Rank Value (855.1) = Starting Rank Value (998.9) + Head To Head Adjustments (-143.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.401[<sup>1</sup>](#table2)
- Bounty Collected: 0.375[<sup>2</sup>](#table1)
- Opponent Network: 0.187[<sup>2</sup>](#table1)
- LAN Wins: 0.199[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 998.9
- 400 + ( ( 0.290 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 998.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           77 |      254 | 2024-07-24 | Lilmix            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.36 | ArroW, awzek, FreeZe, hyped, PerX  |
|           76 |      415 | 2024-07-19 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -15.40 | ArroW, awzek, FreeZe, hyped, PerX  |
|           75 |      522 | 2024-07-17 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -12.70 | ArroW, awzek, FreeZe, hyped, PerX  |
|           74 |      549 | 2024-07-17 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.18 | ArroW, awzek, FreeZe, hyped, PerX  |
|           73 |      576 | 2024-07-16 | DMS               | L   | 1.000      | -            | -                | -                | -         |   -12.89 | ArroW, awzek, FreeZe, hyped, PerX  |
|           72 |      641 | 2024-07-15 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -14.43 | ArroW, awzek, FreeZe, hyped, PerX  |
|           71 |      649 | 2024-07-14 | Kosovo            | L   | 1.000      | -            | -                | -                | -         |   -17.61 | ArroW, awzek, FreeZe, hyped, PerX  |
|           70 |      650 | 2024-07-14 | Sampi             | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    15.92 | ArroW, awzek, FreeZe, hyped, PerX  |
|           69 |      653 | 2024-07-14 | Latvia            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.96 | ArroW, awzek, FreeZe, hyped, PerX  |
|           68 |      664 | 2024-07-13 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |    -7.74 | ArroW, awzek, FreeZe, hyped, PerX  |
|           67 |      704 | 2024-07-11 | UNiTY             | L   | 1.000      | -            | -                | -                | -         |   -12.63 | ArroW, awzek, FreeZe, hyped, PerX  |
|           66 |      761 | 2024-07-08 | Austria           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.92 | ArroW, awzek, FreeZe, hyped, PerX  |
|           65 |      879 | 2024-06-15 | Sissi State Punks | W   | 0.892      | -            | -                | -                | 1 (0.892) |     7.55 | ArroW, awzek, FreeZe, hyped, PerX  |
|           64 |      985 | 2024-06-12 | Versager trupp    | W   | 0.872      | -            | -                | -                | 0 (0.000) |     1.76 | ArroW, awzek, FreeZe, hyped, PerX  |
|           63 |     1155 | 2024-06-08 | Kosovo            | L   | 0.844      | -            | -                | -                | -         |   -15.63 | ArroW, awzek, FreeZe, hyped, PerX  |
|           62 |     1192 | 2024-06-07 | Kubix             | W   | 0.839      | -            | -                | -                | 1 (0.839) |     1.58 | ArroW, awzek, FreeZe, hyped, PerX  |
|           61 |     1634 | 2024-05-24 | Endpoint          | L   | 0.744      | -            | -                | -                | -         |   -11.24 | ArroW, awzek, FreeZe, hyped, PerX  |
|           60 |     1651 | 2024-05-23 | Entropiq          | W   | 0.737      | -            | -                | -                | 0 (0.000) |     1.31 | ArroW, awzek, FreeZe, hyped, PerX  |
|           59 |     1681 | 2024-05-22 | VP.Prodigy        | L   | 0.733      | -            | -                | -                | -         |   -12.23 | ArroW, awzek, FreeZe, hyped, PerX  |
|           58 |     1760 | 2024-05-20 | Nexus             | L   | 0.719      | -            | -                | -                | -         |   -15.33 | ArroW, awzek, FreeZe, hyped, PerX  |
|           57 |     1799 | 2024-05-19 | Passion UA        | L   | 0.710      | -            | -                | -                | -         |    -8.57 | ArroW, awzek, FreeZe, hyped, PerX  |
|           56 |     1832 | 2024-05-18 | Sashi             | L   | 0.704      | -            | -                | -                | -         |    -3.92 | ArroW, awzek, FreeZe, hyped, PerX  |
|           55 |     1851 | 2024-05-17 | EYEBALLERS        | L   | 0.699      | -            | -                | -                | -         |   -12.88 | ArroW, awzek, FreeZe, hyped, PerX  |
|           54 |     1890 | 2024-05-16 | 9 Pandas          | L   | 0.692      | -            | -                | -                | -         |    -9.04 | ArroW, awzek, FreeZe, hyped, PerX  |
|           53 |     1904 | 2024-05-16 | SINNERS           | L   | 0.690      | -            | -                | -                | -         |    -9.46 | ArroW, awzek, FreeZe, hyped, PerX  |
|           52 |     1994 | 2024-05-14 | PERA              | L   | 0.679      | -            | -                | -                | -         |   -12.31 | ArroW, awzek, FreeZe, hyped, PerX  |
|           51 |     2006 | 2024-05-14 | Endpoint          | W   | 0.677      | 0.435        | -                | 0.523 (0.154)    | 0 (0.000) |     9.62 | ArroW, awzek, FreeZe, hyped, PerX  |
|           50 |     2177 | 2024-05-06 | Sashi             | L   | 0.625      | -            | -                | -                | -         |    -4.22 | ArroW, awzek, FreeZe, hyped, PerX  |
|           49 |     2261 | 2024-05-02 | MOUZ NXT          | L   | 0.598      | -            | -                | -                | -         |    -7.70 | ArroW, awzek, FreeZe, hyped, PerX  |
|           48 |     2281 | 2024-05-01 | Sampi             | W   | 0.591      | 0.396        | 0.028 (0.007)    | 1.000 (0.234)    | -         |     7.92 | ArroW, awzek, FreeZe, hyped, PerX  |
|           47 |     2290 | 2024-05-01 | Sangal            | W   | 0.590      | 0.500        | 0.219 (0.065)    | 0.824 (0.243)    | -         |    13.14 | ArroW, awzek, FreeZe, hyped, PerX  |
|           46 |     2299 | 2024-04-30 | Endpoint          | L   | 0.585      | -            | -                | -                | -         |   -10.76 | ArroW, awzek, FreeZe, hyped, PerX  |
|           45 |     2311 | 2024-04-30 | Sampi             | W   | 0.584      | 0.396        | 0.028 (0.006)    | 1.000 (0.231)    | -         |     8.04 | ArroW, awzek, FreeZe, hyped, PerX  |
|           44 |     2340 | 2024-04-28 | Passion UA        | W   | 0.572      | 0.500        | 0.171 (0.049)    | 1.000 (0.286)    | -         |    10.49 | ArroW, awzek, FreeZe, hyped, PerX  |
|           43 |     2400 | 2024-04-26 | Gaimin Gladiators | W   | 0.557      | 0.500        | 0.040 (0.011)    | 0.363 (0.101)    | -         |    10.99 | ArroW, awzek, FreeZe, hyped, skyye |
|           42 |     2468 | 2024-04-23 | Enterprise        | W   | 0.537      | 0.384        | 0.040 (0.008)    | 0.622 (0.128)    | -         |     7.85 | ArroW, FreeZe, hyped, PerX, skyye  |
|           41 |     2470 | 2024-04-23 | Permitta          | L   | 0.536      | -            | -                | -                | -         |    -8.14 | ArroW, FreeZe, hyped, PerX, skyye  |
|           40 |     2481 | 2024-04-22 | ENCE Academy      | W   | 0.531      | -            | -                | -                | -         |     4.23 | ArroW, FreeZe, hyped, PerX, skyye  |
|           39 |     2492 | 2024-04-21 | MOUZ NXT          | L   | 0.525      | -            | -                | -                | -         |    -6.05 | ArroW, awzek, FreeZe, hyped, skyye |
|           38 |     2503 | 2024-04-21 | Sampi             | L   | 0.523      | -            | -                | -                | -         |    -9.04 | ArroW, awzek, FreeZe, hyped, skyye |
|           37 |     2510 | 2024-04-20 | Space             | L   | 0.519      | -            | -                | -                | -         |   -11.28 | ArroW, awzek, FreeZe, hyped, skyye |
|           36 |     2533 | 2024-04-20 | Enterprise        | W   | 0.517      | 0.500        | 0.040 (0.010)    | 0.622 (0.161)    | -         |     7.21 | ArroW, awzek, FreeZe, hyped, skyye |
|           35 |     2568 | 2024-04-19 | Passion UA        | W   | 0.512      | 0.371        | 0.171 (0.032)    | 1.000 (0.190)    | -         |    10.04 | ArroW, awzek, FreeZe, hyped, skyye |
|           34 |     2576 | 2024-04-19 | Zero Tenacity     | L   | 0.511      | -            | -                | -                | -         |    -5.92 | ArroW, awzek, FreeZe, hyped, skyye |
|           33 |     2626 | 2024-04-18 | HAVU              | L   | 0.504      | -            | -                | -                | -         |   -12.99 | ArroW, awzek, FreeZe, hyped, skyye |
|           32 |     2634 | 2024-04-18 | BLEED             | L   | 0.504      | -            | -                | -                | -         |    -6.94 | ArroW, awzek, FreeZe, hyped, skyye |
|           31 |     2695 | 2024-04-16 | Aurora Young Blud | W   | 0.491      | -            | -                | -                | -         |     4.44 | ArroW, awzek, FreeZe, hyped, skyye |
|           30 |     2708 | 2024-04-15 | Zero Tenacity     | L   | 0.486      | -            | -                | -                | -         |    -6.05 | ArroW, awzek, FreeZe, hyped, skyye |
|           29 |     2744 | 2024-04-13 | Alliance          | W   | 0.471      | -            | -                | -                | -         |     5.10 | ArroW, awzek, FreeZe, hyped, skyye |
|           28 |     2888 | 2024-04-09 | ECLOT             | W   | 0.444      | 0.371        | 0.064 (0.011)    | -                | -         |     9.34 | ArroW, awzek, FreeZe, hyped, skyye |
|           27 |     2921 | 2024-04-08 | SINNERS           | L   | 0.437      | -            | -                | -                | -         |    -5.28 | ArroW, awzek, FreeZe, hyped, skyye |
|           26 |     3014 | 2024-04-04 | Rebels            | L   | 0.412      | -            | -                | -                | -         |    -6.08 | ArroW, awzek, FreeZe, hyped, skyye |
|           25 |     3102 | 2024-04-02 | AMKAL             | L   | 0.397      | -            | -                | -                | -         |    -3.69 | ArroW, awzek, FreeZe, hyped, skyye |
|           24 |     3180 | 2024-03-27 | FAVBET            | L   | 0.360      | -            | -                | -                | -         |    -8.80 | ArroW, awzek, FreeZe, hyped, skyye |
|           23 |     3187 | 2024-03-27 | ex-Guild Eagles   | W   | 0.359      | -            | -                | -                | -         |     3.23 | ArroW, awzek, FreeZe, hyped, skyye |
|           22 |     3219 | 2024-03-25 | ex-Sprout         | W   | 0.346      | -            | -                | -                | -         |     0.76 | ArroW, awzek, FreeZe, hyped, skyye |
|           21 |     3234 | 2024-03-23 | Aurora            | L   | 0.333      | -            | -                | -                | -         |    -0.21 | ArroW, awzek, FreeZe, hyped, skyye |
|           20 |     3423 | 2024-03-14 | Metizport         | W   | 0.271      | -            | -                | -                | -         |     3.70 | ArroW, awzek, FreeZe, hyped, skyye |
|           19 |     3452 | 2024-03-13 | SINNERS           | L   | 0.266      | -            | -                | -                | -         |    -3.66 | ArroW, awzek, FreeZe, hyped, skyye |
|           18 |     3533 | 2024-03-10 | Entropiq          | L   | 0.245      | -            | -                | -                | -         |    -7.08 | ArroW, awzek, FreeZe, hyped, skyye |
|           17 |     3538 | 2024-03-10 | MOUZ NXT          | L   | 0.244      | -            | -                | -                | -         |    -3.26 | ArroW, awzek, FreeZe, hyped, skyye |
|           16 |     3581 | 2024-03-08 | Sashi             | W   | 0.230      | 0.371        | 0.185 (0.016)    | -                | -         |     5.13 | ArroW, awzek, FreeZe, hyped, skyye |
|           15 |     3621 | 2024-03-06 | brazylijski luz   | W   | 0.220      | -            | -                | -                | -         |     1.75 | ArroW, awzek, FreeZe, hyped, skyye |
|           14 |     3680 | 2024-03-05 | Sashi             | W   | 0.210      | -            | -                | -                | -         |     4.78 | ArroW, awzek, FreeZe, hyped, skyye |
|           13 |     3692 | 2024-03-04 | Passion UA        | L   | 0.204      | -            | -                | -                | -         |    -2.30 | ArroW, awzek, FreeZe, hyped, skyye |
|           12 |     3738 | 2024-03-02 | 500               | L   | 0.192      | -            | -                | -                | -         |    -4.99 | ArroW, awzek, FreeZe, hyped, skyye |
|           11 |     3760 | 2024-03-01 | fnatic            | L   | 0.185      | -            | -                | -                | -         |    -0.22 | ArroW, awzek, FreeZe, hyped, skyye |
|           10 |     3786 | 2024-02-28 | BetBoom           | L   | 0.171      | -            | -                | -                | -         |    -0.40 | ArroW, awzek, FreeZe, hyped, skyye |
|            9 |     3803 | 2024-02-27 | RUBY              | L   | 0.166      | -            | -                | -                | -         |    -3.02 | ArroW, awzek, FreeZe, hyped, skyye |
|            8 |     3827 | 2024-02-26 | Endpoint          | W   | 0.157      | -            | -                | -                | -         |     1.82 | ArroW, awzek, FreeZe, hyped, skyye |
|            7 |     3843 | 2024-02-25 | Alliance          | L   | 0.152      | -            | -                | -                | -         |    -3.32 | ArroW, awzek, FreeZe, hyped, skyye |
|            6 |     4006 | 2024-02-18 | Young Ninjas      | L   | 0.106      | -            | -                | -                | -         |    -2.65 | ArroW, awzek, FreeZe, PANIX, PerX  |
|            5 |     4179 | 2024-02-11 | Entropiq          | W   | 0.059      | -            | -                | -                | -         |     0.14 | ArroW, awzek, FreeZe, PANIX, PerX  |
|            4 |     4239 | 2024-02-06 | 500               | W   | 0.025      | -            | -                | -                | -         |     0.13 | awzek, FreeZe, Goody, PANIX, PerX  |
|            3 |     4263 | 2024-02-04 | brazylijski luz   | W   | 0.012      | -            | -                | -                | -         |     0.10 | awzek, FreeZe, Goody, PANIX, PerX  |
|            2 |     4276 | 2024-02-04 | Sangal            | L   | 0.010      | -            | -                | -                | -         |    -0.10 | awzek, FreeZe, PANIX, PerX, S3NSEY |
|            1 |     4304 | 2024-02-03 | TSM               | L   | 0.004      | -            | -                | -                | -         |    -0.12 | awzek, FreeZe, Goody, PANIX, PerX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,608.89)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-15 |      0.892 | $810.00        | $722.73         |
| 2024-06-09 |      0.852 | $1,000.00      | $852.05         |
| 2024-06-08 |      0.846 | $1,087.00      | $919.58         |
| 2024-05-03 |      0.605 | $12,500.00     | $7,564.64       |
| 2024-04-25 |      0.550 | $1,000.00      | $549.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
