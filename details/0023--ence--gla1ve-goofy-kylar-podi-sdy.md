### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1335.6<br />
<br />
Final Rank Value (1335.6) = Starting Rank Value (1477.9) + Head To Head Adjustments (-142.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.269[<sup>2</sup>](#table1)
- LAN Wins: 0.802[<sup>2</sup>](#table1)

The average of these factors is 0.525<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1477.9
- 400 + ( ( 0.525 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1477.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |       16 | 2024-08-05 | PARIVISION         | L   | 1.000      | -            | -                | -                | -         |   -25.60 | gla1ve, Goofy, Kylar, podi, sdy    |
|           45 |       29 | 2024-08-04 | 9INE               | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.534 (0.232)    | -         |     2.66 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      331 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.35 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      358 | 2024-07-26 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      398 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.564 (0.367)    | 1 (1.000) |     5.54 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      408 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -12.21 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      425 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.88 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |      438 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.550 (0.358)    | 1 (1.000) |    12.81 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |     1038 | 2024-06-16 | Falcons            | L   | 0.860      | -            | -                | -                | -         |   -11.35 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |     1102 | 2024-06-14 | Complexity         | W   | 0.848      | 0.500        | 0.341 (0.145)    | 0.372 (0.158)    | 1 (0.848) |    21.13 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1111 | 2024-06-14 | MIBR               | W   | 0.847      | 0.500        | 0.208 (0.088)    | 0.647 (0.274)    | 1 (0.847) |    15.32 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1444 | 2024-06-06 | HEROIC             | L   | 0.795      | -            | -                | -                | -         |    -6.00 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1455 | 2024-06-06 | Astralis           | L   | 0.794      | -            | -                | -                | -         |    -3.06 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1491 | 2024-06-05 | Sashi              | W   | 0.789      | 0.715        | 0.184 (0.104)    | 0.980 (0.553)    | 1 (0.789) |     7.81 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1504 | 2024-06-05 | The MongolZ        | L   | 0.788      | -            | -                | -                | -         |    -1.07 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1513 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.787      | -            | -                | -                | -         |    -6.01 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1620 | 2024-06-01 | DMS                | L   | 0.762      | -            | -                | -                | -         |   -21.73 | gla1ve, Goofy, Kylar, podi, sdy    |
|           29 |     1629 | 2024-06-01 | KOI                | W   | 0.762      | -            | -                | -                | -         |     3.23 | gla1ve, Goofy, Kylar, podi, sdy    |
|           28 |     1639 | 2024-06-01 | DMS                | L   | 0.761      | -            | -                | -                | -         |   -22.05 | gla1ve, Goofy, Kylar, podi, sdy    |
|           27 |     1918 | 2024-05-21 | Liquid             | L   | 0.687      | -            | -                | -                | -         |    -5.51 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     2004 | 2024-05-18 | fnatic             | W   | 0.668      | 0.769        | 0.371 (0.190)    | 0.695 (0.357)    | -         |    12.87 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     2027 | 2024-05-17 | Gaimin Gladiators  | W   | 0.663      | 0.769        | 0.037 (0.019)    | 0.339 (0.173)    | -         |     2.08 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2038 | 2024-05-17 | fnatic             | L   | 0.661      | -            | -                | -                | -         |    -7.57 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2396 | 2024-05-04 | FURIA              | L   | 0.575      | -            | -                | -                | -         |    -3.76 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2410 | 2024-05-03 | GamerLegion        | L   | 0.568      | -            | -                | -                | -         |   -14.70 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2430 | 2024-05-02 | Monte              | W   | 0.562      | 0.889        | 0.057 (0.028)    | -                | 1 (0.562) |     1.59 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2458 | 2024-05-01 | Bad News Kangaroos | W   | 0.555      | 0.889        | 0.016 (0.008)    | 0.222 (0.109)    | 1 (0.555) |     0.55 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2489 | 2024-04-30 | GamerLegion        | L   | 0.547      | -            | -                | -                | -         |   -14.59 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     2750 | 2024-04-19 | AMKAL              | L   | 0.474      | -            | -                | -                | -         |   -12.58 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     2837 | 2024-04-17 | Enterprise         | W   | 0.461      | 0.384        | -                | 0.616 (0.109)    | -         |     0.77 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     3008 | 2024-04-10 | OG                 | L   | 0.414      | -            | -                | -                | -         |   -12.04 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3093 | 2024-04-08 | FORZE              | L   | 0.401      | -            | -                | -                | -         |   -12.04 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3201 | 2024-04-04 | Aurora Young Blud  | W   | 0.374      | -            | -                | -                | -         |     0.41 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3495 | 2024-03-19 | FURIA              | L   | 0.269      | -            | -                | -                | -         |    -1.70 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3511 | 2024-03-18 | paiN               | L   | 0.261      | -            | -                | -                | -         |    -4.83 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3518 | 2024-03-17 | KOI                | W   | 0.256      | -            | -                | -                | 1 (0.256) |     0.83 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3538 | 2024-03-17 | Imperial           | L   | 0.254      | -            | -                | -                | -         |    -6.14 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     3669 | 2024-03-12 | B8                 | L   | 0.221      | -            | -                | -                | -         |    -6.26 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     3682 | 2024-03-11 | HEROIC             | L   | 0.216      | -            | -                | -                | -         |    -2.69 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     3692 | 2024-03-11 | Metizport          | W   | 0.215      | -            | -                | -                | -         |     0.27 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     4094 | 2024-02-22 | Astralis           | W   | 0.094      | -            | -                | -                | 1 (0.094) |     2.36 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4116 | 2024-02-21 | Vitality           | L   | 0.088      | -            | -                | -                | -         |    -0.31 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4149 | 2024-02-20 | GamerLegion        | W   | 0.081      | -            | -                | -                | -         |     0.05 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4169 | 2024-02-19 | ex-Guild Eagles    | W   | 0.075      | -            | -                | -                | -         |     0.06 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4177 | 2024-02-19 | Spirit             | L   | 0.074      | -            | -                | -                | -         |    -0.20 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4382 | 2024-02-09 | Falcons            | L   | 0.009      | -            | -                | -                | -         |    -0.17 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,527.01)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-05 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.861 | $10,000.00     | $8,611.11       |
| 2024-06-09 |      0.815 | $8,000.00      | $6,517.78       |
| 2024-05-23 |      0.701 | $12,500.00     | $8,762.15       |
| 2024-05-12 |      0.628 | $7,000.00      | $4,396.39       |
| 2024-04-14 |      0.441 | $15,000.00     | $6,618.75       |
| 2024-03-20 |      0.275 | $10,000.00     | $2,754.17       |
| 2024-02-11 |      0.022 | $40,000.00     | $866.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
