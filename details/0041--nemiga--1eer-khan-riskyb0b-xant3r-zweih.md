### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [41](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1113.2<br />
<br />
Final Rank Value (1113.2) = Starting Rank Value (1152.5) + Head To Head Adjustments (-39.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.668[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.320[<sup>2</sup>](#table1)
- LAN Wins: 0.048[<sup>2</sup>](#table1)

The average of these factors is 0.368<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1152.5
- 400 + ( ( 0.368 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1152.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           56 |        5 | 2024-08-03 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -24.10 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           55 |       42 | 2024-08-02 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -8.52 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           54 |       46 | 2024-08-02 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -12.98 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |       97 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.10 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      156 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.46 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      507 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -21.20 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      541 | 2024-07-18 | PERA              | W   | 1.000      | 0.500        | -                | 0.468 (0.234)    | 0 (0.000) |     8.70 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      607 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -9.09 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      666 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.80 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      711 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.172 (0.086)    | 1.000 (0.500)    | 0 (0.000) |     9.64 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           46 |      950 | 2024-06-15 | Zero Tenacity     | W   | 0.873      | -            | -                | -                | 0 (0.000) |    10.25 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           45 |      981 | 2024-06-14 | System5           | W   | 0.867      | -            | -                | -                | 0 (0.000) |     1.79 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1013 | 2024-06-13 | Verdant           | W   | 0.860      | -            | -                | -                | 0 (0.000) |     5.58 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1045 | 2024-06-12 | FAVBET            | L   | 0.853      | -            | -                | -                | -         |   -23.15 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1059 | 2024-06-11 | Permitta          | W   | 0.847      | -            | -                | -                | 0 (0.000) |     5.52 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           41 |     1067 | 2024-06-11 | Rhyno             | W   | 0.846      | -            | -                | -                | -         |     8.01 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           40 |     1097 | 2024-06-10 | BLEED             | W   | 0.839      | 0.500        | 0.126 (0.053)    | -                | -         |    20.47 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1163 | 2024-06-09 | Zero Tenacity     | W   | 0.831      | 0.500        | 0.137 (0.057)    | 1.000 (0.416)    | -         |    11.30 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1319 | 2024-06-06 | Sampi             | W   | 0.813      | 0.500        | -                | 1.000 (0.406)    | -         |     6.57 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1422 | 2024-06-04 | CYBERSHOKE        | W   | 0.799      | -            | -                | -                | -         |     5.26 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           36 |     1469 | 2024-06-02 | Grannys Knockers  | L   | 0.786      | -            | -                | -                | -         |   -21.60 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           35 |     1560 | 2024-05-30 | DMS               | L   | 0.766      | -            | -                | -                | -         |   -18.64 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           34 |     2150 | 2024-05-10 | RUBY              | L   | 0.631      | -            | -                | -                | -         |   -15.29 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           33 |     2195 | 2024-05-08 | 1WIN              | L   | 0.618      | -            | -                | -                | -         |   -15.25 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2213 | 2024-05-07 | SINNERS           | W   | 0.612      | -            | -                | -                | -         |     6.10 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2239 | 2024-05-05 | VP.Prodigy        | W   | 0.600      | -            | -                | -                | -         |     2.99 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2275 | 2024-05-03 | MOUZ NXT          | W   | 0.586      | 0.500        | 0.139 (0.041)    | 1.000 (0.293)    | -         |     6.06 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2300 | 2024-05-02 | Passion UA        | W   | 0.579      | 0.500        | 0.172 (0.050)    | 1.000 (0.290)    | -         |     5.86 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2318 | 2024-05-01 | B8                | W   | 0.574      | 0.500        | 0.166 (0.047)    | 0.945 (0.271)    | -         |     6.29 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2364 | 2024-04-29 | MOUZ NXT          | W   | 0.560      | 0.500        | 0.139 (0.039)    | 1.000 (0.280)    | -         |     6.17 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2396 | 2024-04-28 | Grannys Knockers  | L   | 0.551      | -            | -                | -                | -         |   -15.65 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2418 | 2024-04-27 | 1WIN              | W   | 0.545      | -            | -                | -                | -         |     3.74 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2442 | 2024-04-26 | Sangal            | L   | 0.539      | -            | -                | -                | -         |    -9.57 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2484 | 2024-04-24 | BLEED             | W   | 0.526      | -            | -                | -                | -         |     5.99 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2508 | 2024-04-23 | Zero Tenacity     | W   | 0.519      | 0.500        | 0.137 (0.036)    | 1.000 (0.259)    | -         |     6.32 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2529 | 2024-04-22 | MOUZ NXT          | W   | 0.511      | 0.500        | 0.139 (0.036)    | 1.000 (0.256)    | -         |     5.64 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2544 | 2024-04-21 | 1WIN              | W   | 0.505      | -            | -                | -                | -         |     3.50 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2577 | 2024-04-20 | Gaimin Gladiators | L   | 0.498      | -            | -                | -                | -         |   -10.56 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2612 | 2024-04-19 | Sangal            | W   | 0.493      | 0.500        | 0.219 (0.054)    | -                | -         |     7.42 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2662 | 2024-04-18 | Secret            | W   | 0.486      | -            | -                | -                | -         |     0.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2699 | 2024-04-17 | Alliance          | W   | 0.479      | -            | -                | -                | -         |     2.49 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     2891 | 2024-04-09 | FlyQuest          | L   | 0.430      | -            | -                | -                | -         |    -6.40 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     2939 | 2024-04-09 | Steel Helmet      | W   | 0.424      | -            | -                | -                | 1 (0.424) |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     2968 | 2024-04-08 | FaZe              | L   | 0.418      | -            | -                | -                | -         |    -0.55 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3161 | 2024-04-01 | Zero Tenacity     | W   | 0.371      | -            | -                | -                | -         |     5.02 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3288 | 2024-03-22 | Sashi             | L   | 0.307      | -            | -                | -                | -         |    -5.04 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3522 | 2024-03-12 | Nexus             | L   | 0.240      | -            | -                | -                | -         |    -6.46 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3551 | 2024-03-11 | Sashi             | W   | 0.233      | -            | -                | -                | -         |     3.45 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3566 | 2024-03-10 | Endpoint          | W   | 0.226      | -            | -                | -                | -         |     1.34 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3638 | 2024-03-07 | Zero Tenacity     | W   | 0.206      | -            | -                | -                | -         |     2.78 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3700 | 2024-03-05 | KOI               | L   | 0.194      | -            | -                | -                | -         |    -4.75 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3707 | 2024-03-05 | GUN5              | W   | 0.193      | -            | -                | -                | -         |     0.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     4223 | 2024-02-10 | Sashi             | W   | 0.034      | -            | -                | -                | -         |     0.55 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4238 | 2024-02-09 | AMKAL             | W   | 0.027      | -            | -                | -                | -         |     0.42 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4254 | 2024-02-08 | Sashi             | W   | 0.020      | -            | -                | -                | -         |     0.33 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4260 | 2024-02-08 | BetBoom           | W   | 0.019      | -            | -                | -                | -         |     0.50 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($103,793.46)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.846 | $50,000.00     | $42,307.87      |
| 2024-05-09 |      0.625 | $4,000.00      | $2,501.30       |
| 2024-05-03 |      0.586 | $50,000.00     | $29,307.87      |
| 2024-04-24 |      0.526 | $50,000.00     | $26,307.87      |
| 2024-04-14 |      0.458 | $5,000.00      | $2,291.32       |
| 2024-03-25 |      0.326 | $3,300.00      | $1,077.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
