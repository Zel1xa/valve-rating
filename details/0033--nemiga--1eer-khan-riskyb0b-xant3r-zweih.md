### Roster Details<br />
Team Name: Nemiga<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1154.1<br />
<br />
Final Rank Value (1154.1) = Starting Rank Value (1170.2) + Head To Head Adjustments (-16.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.666[<sup>1</sup>](#table2)
- Bounty Collected: 0.460[<sup>2</sup>](#table1)
- Opponent Network: 0.329[<sup>2</sup>](#table1)
- LAN Wins: 0.047[<sup>2</sup>](#table1)

The average of these factors is 0.376<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1170.2
- 400 + ( ( 0.376 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1170.2


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
|           57 |       33 | 2024-08-04 | Aurora            | W   | 1.000      | 0.500        | 0.422 (0.211)    | 0.778 (0.389)    | 0 (0.000) |    26.36 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           56 |       66 | 2024-08-03 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -23.97 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           55 |      109 | 2024-08-02 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.94 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           54 |      113 | 2024-08-02 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.03 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           53 |      180 | 2024-07-31 | Space             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.62 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           52 |      240 | 2024-07-30 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.43 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           51 |      591 | 2024-07-19 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -21.00 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           50 |      625 | 2024-07-18 | PERA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.25 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           49 |      691 | 2024-07-17 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -9.40 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           48 |      753 | 2024-07-16 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.26 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           47 |      798 | 2024-07-15 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.086)    | 1.000 (0.500)    | 0 (0.000) |     9.46 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           46 |     1053 | 2024-06-15 | Zero Tenacity     | W   | 0.860      | -            | -                | -                | 0 (0.000) |    10.49 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           45 |     1091 | 2024-06-14 | System5           | W   | 0.853      | -            | -                | -                | 0 (0.000) |     1.65 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           44 |     1125 | 2024-06-13 | Verdant           | W   | 0.847      | -            | -                | -                | 0 (0.000) |     5.25 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           43 |     1158 | 2024-06-12 | FAVBET            | L   | 0.840      | -            | -                | -                | -         |   -22.96 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           42 |     1173 | 2024-06-11 | Permitta          | W   | 0.833      | -            | -                | -                | -         |     5.54 | 1eeR, khaN, riskyb0b, roman, Xant3r  |
|           41 |     1183 | 2024-06-11 | Rhyno             | W   | 0.832      | -            | -                | -                | -         |     7.43 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           40 |     1213 | 2024-06-10 | BLEED             | W   | 0.825      | 0.500        | 0.126 (0.052)    | -                | -         |    19.85 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           39 |     1280 | 2024-06-09 | Zero Tenacity     | W   | 0.817      | 0.500        | 0.143 (0.058)    | 1.000 (0.409)    | -         |    10.95 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           38 |     1441 | 2024-06-06 | Sampi             | W   | 0.799      | 0.500        | -                | 1.000 (0.400)    | -         |     6.19 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           37 |     1545 | 2024-06-04 | CYBERSHOKE        | W   | 0.786      | -            | -                | -                | -         |     4.83 | 1eeR, khaN, riskyb0b, Xant3r, zweih  |
|           36 |     1593 | 2024-06-02 | Grannys Knockers  | L   | 0.772      | -            | -                | -                | -         |   -21.44 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           35 |     1685 | 2024-05-30 | DMS               | L   | 0.752      | -            | -                | -                | -         |   -18.59 | 1eeR, boX, khaN, riskyb0b, Xant3r    |
|           34 |     2277 | 2024-05-10 | RUBY              | L   | 0.617      | -            | -                | -                | -         |   -15.35 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           33 |     2323 | 2024-05-08 | 1WIN              | L   | 0.604      | -            | -                | -                | -         |   -14.68 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           32 |     2341 | 2024-05-07 | SINNERS           | W   | 0.598      | -            | -                | -                | -         |     6.61 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           31 |     2367 | 2024-05-05 | VP.Prodigy        | W   | 0.586      | -            | -                | -                | -         |     2.73 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           30 |     2403 | 2024-05-03 | MOUZ NXT          | W   | 0.572      | 0.500        | 0.139 (0.040)    | 0.987 (0.282)    | -         |     5.76 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           29 |     2428 | 2024-05-02 | Passion UA        | W   | 0.566      | 0.500        | 0.173 (0.049)    | 1.000 (0.283)    | -         |     5.71 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           28 |     2446 | 2024-05-01 | B8                | W   | 0.560      | 0.500        | 0.165 (0.046)    | 0.935 (0.262)    | -         |     5.83 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           27 |     2492 | 2024-04-29 | MOUZ NXT          | W   | 0.547      | 0.500        | 0.139 (0.038)    | 0.987 (0.270)    | -         |     5.86 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           26 |     2524 | 2024-04-28 | Grannys Knockers  | L   | 0.538      | -            | -                | -                | -         |   -15.39 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           25 |     2546 | 2024-04-27 | 1WIN              | W   | 0.532      | -            | -                | -                | -         |     3.90 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           24 |     2572 | 2024-04-26 | Sangal            | L   | 0.525      | -            | -                | -                | -         |    -9.48 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           23 |     2613 | 2024-04-24 | BLEED             | W   | 0.512      | -            | -                | -                | -         |     5.48 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           22 |     2637 | 2024-04-23 | Zero Tenacity     | W   | 0.505      | 0.500        | 0.143 (0.036)    | 1.000 (0.252)    | -         |     5.93 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           21 |     2658 | 2024-04-22 | MOUZ NXT          | W   | 0.497      | 0.500        | -                | 0.987 (0.245)    | -         |     5.34 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           20 |     2673 | 2024-04-21 | 1WIN              | W   | 0.491      | -            | -                | -                | -         |     3.65 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           19 |     2706 | 2024-04-20 | Gaimin Gladiators | L   | 0.484      | -            | -                | -                | -         |   -10.70 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           18 |     2741 | 2024-04-19 | Sangal            | W   | 0.479      | 0.500        | 0.219 (0.052)    | -                | -         |     7.05 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           17 |     2791 | 2024-04-18 | Secret            | W   | 0.472      | -            | -                | -                | -         |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           16 |     2828 | 2024-04-17 | Alliance          | W   | 0.466      | -            | -                | -                | -         |     2.22 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           15 |     3020 | 2024-04-09 | FlyQuest          | L   | 0.416      | -            | -                | -                | -         |    -6.60 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           14 |     3068 | 2024-04-09 | Steel Helmet      | W   | 0.411      | -            | -                | -                | 1 (0.411) |     0.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           13 |     3097 | 2024-04-08 | FaZe              | L   | 0.404      | -            | -                | -                | -         |    -0.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           12 |     3290 | 2024-04-01 | Zero Tenacity     | W   | 0.357      | -            | -                | -                | -         |     4.64 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           11 |     3422 | 2024-03-22 | Sashi             | L   | 0.293      | -            | -                | -                | -         |    -5.02 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|           10 |     3659 | 2024-03-12 | Nexus             | L   | 0.227      | -            | -                | -                | -         |    -6.18 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            9 |     3688 | 2024-03-11 | Sashi             | W   | 0.219      | -            | -                | -                | -         |     3.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            8 |     3703 | 2024-03-10 | Endpoint          | W   | 0.213      | -            | -                | -                | -         |     1.15 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            7 |     3775 | 2024-03-07 | Zero Tenacity     | W   | 0.193      | -            | -                | -                | -         |     2.48 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            6 |     3837 | 2024-03-05 | KOI               | L   | 0.180      | -            | -                | -                | -         |    -3.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            5 |     3844 | 2024-03-05 | GUN5              | W   | 0.180      | -            | -                | -                | -         |     0.07 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            4 |     4361 | 2024-02-10 | Sashi             | W   | 0.020      | -            | -                | -                | -         |     0.31 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            3 |     4377 | 2024-02-09 | AMKAL             | W   | 0.013      | -            | -                | -                | -         |     0.20 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            2 |     4392 | 2024-02-08 | Sashi             | W   | 0.007      | -            | -                | -                | -         |     0.10 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |
|            1 |     4398 | 2024-02-08 | BetBoom           | W   | 0.006      | -            | -                | -                | -         |     0.14 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($101,554.32)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.832 | $50,000.00     | $41,618.06      |
| 2024-05-09 |      0.612 | $4,000.00      | $2,446.11       |
| 2024-05-03 |      0.572 | $50,000.00     | $28,618.06      |
| 2024-04-24 |      0.512 | $50,000.00     | $25,618.06      |
| 2024-04-14 |      0.444 | $5,000.00      | $2,222.34       |
| 2024-03-25 |      0.313 | $3,300.00      | $1,031.71       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
