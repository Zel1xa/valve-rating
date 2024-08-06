### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Goofy, Kylar, podi, sdy<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1336.1<br />
<br />
Final Rank Value (1336.1) = Starting Rank Value (1478.7) + Head To Head Adjustments (-142.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.266[<sup>2</sup>](#table1)
- LAN Wins: 0.802[<sup>2</sup>](#table1)

The average of these factors is 0.524<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1478.7
- 400 + ( ( 0.524 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1478.7


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
|           46 |       20 | 2024-08-05 | PARIVISION         | L   | 1.000      | -            | -                | -                | -         |   -25.60 | gla1ve, Goofy, Kylar, podi, sdy    |
|           45 |       33 | 2024-08-04 | 9INE               | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.523 (0.227)    | -         |     2.65 | gla1ve, Goofy, Kylar, podi, sdy    |
|           44 |      335 | 2024-07-27 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -15.37 | gla1ve, Goofy, Kylar, podi, sdy    |
|           43 |      362 | 2024-07-26 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           42 |      402 | 2024-07-25 | PARIVISION         | W   | 1.000      | 0.650        | 0.017 (0.011)    | 0.590 (0.384)    | 1 (1.000) |     5.55 | gla1ve, Goofy, Kylar, podi, sdy    |
|           41 |      412 | 2024-07-25 | Aurora             | L   | 1.000      | -            | -                | -                | -         |   -12.17 | gla1ve, Goofy, Kylar, podi, sdy    |
|           40 |      429 | 2024-07-24 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -3.90 | gla1ve, Goofy, Kylar, podi, sdy    |
|           39 |      442 | 2024-07-24 | BLEED              | W   | 1.000      | 0.650        | 0.126 (0.082)    | 0.538 (0.350)    | 1 (1.000) |    12.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           38 |     1042 | 2024-06-16 | Falcons            | L   | 0.860      | -            | -                | -                | -         |   -11.35 | gla1ve, Goofy, Kylar, podi, sdy    |
|           37 |     1106 | 2024-06-14 | Complexity         | W   | 0.848      | 0.500        | 0.341 (0.145)    | 0.364 (0.154)    | 1 (0.848) |    21.11 | gla1ve, Goofy, Kylar, podi, sdy    |
|           36 |     1115 | 2024-06-14 | MIBR               | W   | 0.847      | 0.500        | 0.208 (0.088)    | 0.633 (0.268)    | 1 (0.847) |    15.26 | gla1ve, Goofy, Kylar, podi, sdy    |
|           35 |     1448 | 2024-06-06 | HEROIC             | L   | 0.795      | -            | -                | -                | -         |    -6.02 | gla1ve, Goofy, Kylar, podi, sdy    |
|           34 |     1459 | 2024-06-06 | Astralis           | L   | 0.794      | -            | -                | -                | -         |    -3.06 | gla1ve, Goofy, Kylar, podi, sdy    |
|           33 |     1495 | 2024-06-05 | Sashi              | W   | 0.789      | 0.715        | 0.184 (0.104)    | 0.958 (0.541)    | 1 (0.789) |     7.79 | gla1ve, Goofy, Kylar, podi, sdy    |
|           32 |     1508 | 2024-06-05 | The MongolZ        | L   | 0.788      | -            | -                | -                | -         |    -1.08 | gla1ve, Goofy, Kylar, podi, sdy    |
|           31 |     1517 | 2024-06-05 | Ninjas in Pyjamas  | L   | 0.787      | -            | -                | -                | -         |    -6.04 | gla1ve, Goofy, Kylar, podi, sdy    |
|           30 |     1624 | 2024-06-01 | DMS                | L   | 0.762      | -            | -                | -                | -         |   -21.74 | gla1ve, Goofy, Kylar, podi, sdy    |
|           29 |     1633 | 2024-06-01 | KOI                | W   | 0.761      | -            | -                | -                | -         |     3.21 | gla1ve, Goofy, Kylar, podi, sdy    |
|           28 |     1643 | 2024-06-01 | DMS                | L   | 0.760      | -            | -                | -                | -         |   -22.05 | gla1ve, Goofy, Kylar, podi, sdy    |
|           27 |     1922 | 2024-05-21 | Liquid             | L   | 0.686      | -            | -                | -                | -         |    -5.51 | dycha, gla1ve, Goofy, hades, Kylar |
|           26 |     2008 | 2024-05-18 | fnatic             | W   | 0.667      | 0.769        | 0.371 (0.190)    | 0.680 (0.349)    | -         |    12.83 | dycha, gla1ve, Goofy, hades, Kylar |
|           25 |     2031 | 2024-05-17 | Gaimin Gladiators  | W   | 0.663      | 0.769        | 0.037 (0.019)    | 0.331 (0.169)    | -         |     2.07 | dycha, gla1ve, Goofy, hades, Kylar |
|           24 |     2042 | 2024-05-17 | fnatic             | L   | 0.661      | -            | -                | -                | -         |    -7.60 | dycha, gla1ve, Goofy, hades, Kylar |
|           23 |     2400 | 2024-05-04 | FURIA              | L   | 0.574      | -            | -                | -                | -         |    -3.79 | dycha, gla1ve, Goofy, hades, Kylar |
|           22 |     2414 | 2024-05-03 | GamerLegion        | L   | 0.568      | -            | -                | -                | -         |   -14.72 | dycha, gla1ve, Goofy, hades, Kylar |
|           21 |     2434 | 2024-05-02 | Monte              | W   | 0.562      | 0.889        | 0.057 (0.028)    | -                | 1 (0.562) |     1.59 | dycha, gla1ve, Goofy, hades, Kylar |
|           20 |     2462 | 2024-05-01 | Bad News Kangaroos | W   | 0.554      | 0.889        | 0.016 (0.008)    | 0.217 (0.107)    | 1 (0.554) |     0.54 | dycha, gla1ve, Goofy, hades, Kylar |
|           19 |     2493 | 2024-04-30 | GamerLegion        | L   | 0.547      | -            | -                | -                | -         |   -14.60 | dycha, gla1ve, Goofy, hades, Kylar |
|           18 |     2754 | 2024-04-19 | AMKAL              | L   | 0.474      | -            | -                | -                | -         |   -12.59 | dycha, gla1ve, Goofy, hades, Kylar |
|           17 |     2841 | 2024-04-17 | Enterprise         | W   | 0.460      | 0.384        | -                | 0.641 (0.113)    | -         |     0.76 | dycha, gla1ve, Goofy, hades, Kylar |
|           16 |     3012 | 2024-04-10 | OG                 | L   | 0.414      | -            | -                | -                | -         |   -12.03 | dycha, gla1ve, Goofy, hades, Kylar |
|           15 |     3097 | 2024-04-08 | FORZE              | L   | 0.401      | -            | -                | -                | -         |   -12.04 | dycha, gla1ve, Goofy, hades, Kylar |
|           14 |     3205 | 2024-04-04 | Aurora Young Blud  | W   | 0.374      | -            | -                | -                | -         |     0.41 | dycha, gla1ve, Goofy, hades, Kylar |
|           13 |     3499 | 2024-03-19 | FURIA              | L   | 0.268      | -            | -                | -                | -         |    -1.71 | dycha, gla1ve, Goofy, hades, Kylar |
|           12 |     3515 | 2024-03-18 | paiN               | L   | 0.260      | -            | -                | -                | -         |    -4.85 | dycha, gla1ve, Goofy, hades, Kylar |
|           11 |     3522 | 2024-03-17 | KOI                | W   | 0.256      | -            | -                | -                | 1 (0.256) |     0.82 | dycha, gla1ve, Goofy, hades, Kylar |
|           10 |     3542 | 2024-03-17 | Imperial           | L   | 0.254      | -            | -                | -                | -         |    -6.15 | dycha, gla1ve, Goofy, hades, Kylar |
|            9 |     3673 | 2024-03-12 | B8                 | L   | 0.221      | -            | -                | -                | -         |    -6.25 | dycha, gla1ve, Goofy, hades, Kylar |
|            8 |     3686 | 2024-03-11 | HEROIC             | L   | 0.215      | -            | -                | -                | -         |    -2.70 | dycha, gla1ve, Goofy, hades, Kylar |
|            7 |     3696 | 2024-03-11 | Metizport          | W   | 0.214      | -            | -                | -                | -         |     0.27 | dycha, gla1ve, Goofy, hades, Kylar |
|            6 |     4098 | 2024-02-22 | Astralis           | W   | 0.093      | -            | -                | -                | 1 (0.093) |     2.35 | dycha, gla1ve, Goofy, hades, Kylar |
|            5 |     4120 | 2024-02-21 | Vitality           | L   | 0.088      | -            | -                | -                | -         |    -0.31 | dycha, gla1ve, Goofy, hades, Kylar |
|            4 |     4153 | 2024-02-20 | GamerLegion        | W   | 0.080      | -            | -                | -                | -         |     0.05 | dycha, gla1ve, Goofy, hades, Kylar |
|            3 |     4173 | 2024-02-19 | ex-Guild Eagles    | W   | 0.075      | -            | -                | -                | -         |     0.06 | dycha, gla1ve, Goofy, hades, Kylar |
|            2 |     4181 | 2024-02-19 | Spirit             | L   | 0.074      | -            | -                | -                | -         |    -0.20 | dycha, gla1ve, Goofy, hades, Kylar |
|            1 |     4386 | 2024-02-09 | Falcons            | L   | 0.009      | -            | -                | -                | -         |    -0.16 | dycha, gla1ve, Goofy, hades, Kylar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,498.54)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-16 |      0.861 | $10,000.00     | $8,608.33       |
| 2024-06-09 |      0.814 | $8,000.00      | $6,515.56       |
| 2024-05-23 |      0.701 | $12,500.00     | $8,758.68       |
| 2024-05-12 |      0.628 | $7,000.00      | $4,394.44       |
| 2024-04-14 |      0.441 | $15,000.00     | $6,614.58       |
| 2024-03-20 |      0.275 | $10,000.00     | $2,751.39       |
| 2024-02-11 |      0.021 | $40,000.00     | $855.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
