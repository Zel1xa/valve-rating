### Roster Details<br />
Team Name: Gaimin Gladiators<br />
Roster: kraghen, nicoodoz, Nodios, Queenix, roeJ<br />
Global Rank: [69](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
<br />
Final Rank Value:  957.4<br />
<br />
Final Rank Value (957.4) = Starting Rank Value (983.8) + Head To Head Adjustments (-26.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.399[<sup>2</sup>](#table1)
- Opponent Network: 0.135[<sup>2</sup>](#table1)
- LAN Wins: 0.182[<sup>2</sup>](#table1)

The average of these factors is 0.283<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 983.8
- 400 + ( ( 0.283 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 983.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           55 |      168 | 2024-07-26 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -9.46 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           54 |      918 | 2024-06-14 | GUN5             | L   | 0.886      | -            | -                | -                | -         |   -13.50 | kraghen, Nodios, Patti, Queenix, salazar |
|           53 |     1044 | 2024-06-10 | Enterprise       | L   | 0.857      | -            | -                | -                | -         |   -16.52 | kraghen, Nodios, Patti, Queenix, salazar |
|           52 |     1100 | 2024-06-09 | 5W               | L   | 0.850      | -            | -                | -                | -         |   -14.95 | kraghen, Nodios, Patti, Queenix, salazar |
|           51 |     1144 | 2024-06-08 | EYEBALLERS       | W   | 0.845      | 0.450        | -                | 0.513 (0.195)    | 0 (0.000) |    10.28 | kraghen, Nodios, Patti, Queenix, salazar |
|           50 |     1200 | 2024-06-07 | 3DMAX            | L   | 0.839      | -            | -                | -                | -         |    -1.58 | kraghen, Nodios, Patti, Queenix, salazar |
|           49 |     1265 | 2024-06-06 | Astralis Talent  | W   | 0.832      | 0.450        | -                | 0.162 (0.061)    | 0 (0.000) |     5.87 | kraghen, Nodios, Patti, Queenix, salazar |
|           48 |     1517 | 2024-05-30 | Lynn Vision      | L   | 0.783      | -            | -                | -                | -         |   -12.88 | kraghen, Nodios, Patti, Queenix, salazar |
|           47 |     1560 | 2024-05-28 | The MongolZ      | L   | 0.770      | -            | -                | -                | -         |    -0.17 | kraghen, Nodios, Patti, Queenix, salazar |
|           46 |     1846 | 2024-05-17 | ENCE             | L   | 0.700      | -            | -                | -                | -         |    -2.35 | kraghen, Nodios, Patti, Queenix, salazar |
|           45 |     1852 | 2024-05-17 | GamerLegion      | L   | 0.699      | -            | -                | -                | -         |    -6.75 | kraghen, Nodios, Patti, Queenix, salazar |
|           44 |     1858 | 2024-05-17 | Rebels           | L   | 0.698      | -            | -                | -                | -         |   -11.31 | kraghen, Nodios, Patti, Queenix, salazar |
|           43 |     1944 | 2024-05-15 | BLEED            | W   | 0.685      | 0.384        | 0.127 (0.033)    | 0.512 (0.135)    | 0 (0.000) |    19.50 | kraghen, Nodios, Patti, Queenix, salazar |
|           42 |     2169 | 2024-05-07 | Grannys Knockers | L   | 0.630      | -            | -                | -                | -         |   -15.68 | kraghen, Nodios, Patti, Queenix, salazar |
|           41 |     2180 | 2024-05-06 | 500              | W   | 0.625      | -            | -                | -                | -         |     0.60 | kraghen, Nodios, Patti, Queenix, salazar |
|           40 |     2191 | 2024-05-05 | Sashi            | W   | 0.619      | 0.143        | 0.185 (0.016)    | 0.973 (0.086)    | -         |    14.76 | kraghen, Nodios, Patti, Queenix, salazar |
|           39 |     2200 | 2024-05-05 | Kronjyllands     | W   | 0.618      | -            | -                | -                | -         |     0.61 | kraghen, Nodios, Patti, Queenix, salazar |
|           38 |     2231 | 2024-05-03 | AMKAL            | L   | 0.605      | -            | -                | -                | -         |    -5.78 | kraghen, Nodios, Patti, Queenix, salazar |
|           37 |     2252 | 2024-05-02 | HAVU             | W   | 0.599      | -            | -                | -                | -         |     2.98 | kraghen, Nodios, Patti, Queenix, salazar |
|           36 |     2264 | 2024-05-02 | SINNERS          | W   | 0.597      | 0.435        | 0.038 (0.010)    | 0.721 (0.187)    | -         |     9.34 | kraghen, Nodios, Patti, Queenix, salazar |
|           35 |     2297 | 2024-04-30 | AMKAL            | L   | 0.586      | -            | -                | -                | -         |    -5.71 | kraghen, Nodios, Patti, Queenix, salazar |
|           34 |     2326 | 2024-04-29 | kONO             | L   | 0.578      | -            | -                | -                | -         |   -13.77 | kraghen, Nodios, Patti, Queenix, salazar |
|           33 |     2352 | 2024-04-28 | 9 Pandas         | L   | 0.570      | -            | -                | -                | -         |   -10.48 | kraghen, Nodios, Patti, Queenix, salazar |
|           32 |     2400 | 2024-04-26 | ALTERNATE aTTaX  | L   | 0.557      | -            | -                | -                | -         |   -10.99 | kraghen, Nodios, Patti, Queenix, salazar |
|           31 |     2461 | 2024-04-23 | Sashi            | L   | 0.538      | -            | -                | -                | -         |    -5.71 | kraghen, Nodios, Patti, Queenix, salazar |
|           30 |     2476 | 2024-04-22 | BLEED            | L   | 0.531      | -            | -                | -                | -         |    -8.39 | kraghen, Nodios, Patti, Queenix, salazar |
|           29 |     2494 | 2024-04-21 | AMKAL            | W   | 0.525      | 0.384        | 0.131 (0.026)    | 0.484 (0.098)    | -         |    10.51 | kraghen, Nodios, Patti, Queenix, salazar |
|           28 |     2531 | 2024-04-20 | Nemiga           | W   | 0.517      | 0.384        | 0.322 (0.064)    | 0.698 (0.139)    | -         |    10.88 | kraghen, Nodios, Patti, Queenix, salazar |
|           27 |     2673 | 2024-04-17 | SINNERS          | W   | 0.497      | 0.384        | 0.038 (0.007)    | 0.721 (0.138)    | -         |     8.85 | kraghen, Nodios, Patti, Queenix, salazar |
|           26 |     2694 | 2024-04-16 | Permitta         | W   | 0.491      | 0.384        | -                | 0.799 (0.151)    | -         |     6.22 | kraghen, Nodios, Patti, Queenix, salazar |
|           25 |     3022 | 2024-04-04 | JANO             | W   | 0.410      | -            | -                | -                | -         |     1.65 | kraghen, Nodios, Patti, Queenix, salazar |
|           24 |     3237 | 2024-03-23 | G2               | L   | 0.332      | -            | -                | -                | -         |    -0.05 | kraghen, Nodios, Patti, Queenix, salazar |
|           23 |     3246 | 2024-03-22 | FURIA            | W   | 0.326      | 1.000        | 0.284 (0.093)    | 0.495 (0.162)    | 1 (0.326) |    10.08 | kraghen, Nodios, Patti, Queenix, salazar |
|           22 |     3266 | 2024-03-21 | Cloud9           | L   | 0.320      | -            | -                | -                | -         |    -4.15 | kraghen, Nodios, Patti, Queenix, salazar |
|           21 |     3281 | 2024-03-21 | MOUZ             | L   | 0.318      | -            | -                | -                | -         |    -0.08 | kraghen, Nodios, Patti, Queenix, salazar |
|           20 |     3313 | 2024-03-19 | Imperial         | W   | 0.306      | 0.143        | 0.243 (0.011)    | -                | 1 (0.306) |     8.03 | kraghen, Nodios, Patti, Queenix, salazar |
|           19 |     3328 | 2024-03-18 | Lynn Vision      | W   | 0.298      | -            | -                | -                | 1 (0.298) |     4.74 | kraghen, Nodios, Patti, Queenix, salazar |
|           18 |     3347 | 2024-03-17 | The MongolZ      | W   | 0.293      | 0.143        | 1.000 (0.042)    | -                | 1 (0.293) |     9.18 | kraghen, Nodios, Patti, Queenix, salazar |
|           17 |     3359 | 2024-03-17 | Cloud9           | L   | 0.291      | -            | -                | -                | -         |    -3.73 | kraghen, Nodios, Patti, Queenix, salazar |
|           16 |     3695 | 2024-03-04 | BetBoom          | L   | 0.204      | -            | -                | -                | -         |    -0.51 | kraghen, Nodios, Patti, Queenix, salazar |
|           15 |     3701 | 2024-03-03 | ex-Preasy        | L   | 0.200      | -            | -                | -                | -         |    -4.72 | kraghen, Nodios, Patti, Queenix, salazar |
|           14 |     3708 | 2024-03-03 | fnatic           | W   | 0.199      | 0.143        | 0.371 (0.011)    | -                | -         |     6.04 | kraghen, Nodios, Patti, Queenix, salazar |
|           13 |     3717 | 2024-03-03 | SINNERS          | W   | 0.199      | -            | -                | -                | -         |     3.54 | kraghen, Nodios, Patti, Queenix, salazar |
|           12 |     3724 | 2024-03-03 | Monte            | W   | 0.197      | -            | -                | -                | -         |     3.35 | kraghen, Nodios, Patti, Queenix, salazar |
|           11 |     3740 | 2024-03-02 | PARIVISION       | W   | 0.191      | -            | -                | -                | -         |     3.88 | kraghen, Nodios, Patti, Queenix, salazar |
|           10 |     3764 | 2024-02-29 | 3DMAX            | L   | 0.180      | -            | -                | -                | -         |    -0.11 | kraghen, Nodios, Patti, Queenix, salazar |
|            9 |     3911 | 2024-02-22 | ex-Guild Eagles  | W   | 0.131      | -            | -                | -                | 1 (0.131) |     1.22 | kraghen, Nodios, Patti, Queenix, salazar |
|            8 |     3939 | 2024-02-21 | Apeks            | L   | 0.124      | -            | -                | -                | -         |    -2.28 | kraghen, Nodios, Patti, Queenix, salazar |
|            7 |     3969 | 2024-02-20 | OG               | W   | 0.117      | -            | -                | -                | 1 (0.117) |     2.00 | kraghen, Nodios, Patti, Queenix, salazar |
|            6 |     3984 | 2024-02-19 | MOUZ             | L   | 0.113      | -            | -                | -                | -         |    -0.02 | kraghen, Nodios, Patti, Queenix, salazar |
|            5 |     3994 | 2024-02-19 | Monte            | W   | 0.111      | -            | -                | -                | 1 (0.111) |     1.92 | kraghen, Nodios, Patti, Queenix, salazar |
|            4 |     4213 | 2024-02-09 | ex-Preasy        | L   | 0.044      | -            | -                | -                | -         |    -1.02 | kraghen, Nodios, Patti, Queenix, salazar |
|            3 |     4231 | 2024-02-07 | TSM              | W   | 0.031      | -            | -                | -                | -         |     0.15 | kraghen, Nodios, Patti, Queenix, salazar |
|            2 |     4253 | 2024-02-05 | ex-Preasy        | W   | 0.017      | -            | -                | -                | -         |     0.13 | kraghen, Nodios, Patti, Queenix, salazar |
|            1 |     4288 | 2024-02-03 | Sashi            | L   | 0.006      | -            | -                | -                | -         |    -0.05 | kraghen, Nodios, Patti, Queenix, salazar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,122.07)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.706 | $1,000.00      | $705.73         |
| 2024-05-04 |      0.612 | $2,000.00      | $1,224.23       |
| 2024-05-02 |      0.599 | $1,000.00      | $598.78         |
| 2024-04-22 |      0.531 | $5,000.00      | $2,655.72       |
| 2024-03-31 |      0.386 | $20,000.00     | $7,720.09       |
| 2024-02-09 |      0.044 | $5,000.00      | $217.52         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
