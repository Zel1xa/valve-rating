### Roster Details<br />
Team Name: 1WIN<br />
Roster: buster, HObbit, lattykk, neaLaN, Ryujin<br />
Global Rank: [67](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  965.6<br />
<br />
Final Rank Value (965.6) = Starting Rank Value (892.4) + Head To Head Adjustments (73.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.397[<sup>2</sup>](#table1)
- Opponent Network: 0.169[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.239<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 892.4
- 400 + ( ( 0.239 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 892.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |       20 | 2024-07-31 | Into the Breach | W   | 1.000      | 0.435        | -                | 0.192 (0.083)    | 0 (0.000) |     6.58 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           40 |       63 | 2024-07-30 | ECLOT           | L   | 1.000      | -            | -                | -                | -         |   -13.52 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           39 |       85 | 2024-07-29 | CYBERSHOKE      | L   | 1.000      | -            | -                | -                | -         |   -17.28 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           38 |       96 | 2024-07-29 | NOM             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.11 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           37 |      135 | 2024-07-28 | TSM             | W   | 1.000      | 0.143        | 0.039 (0.006)    | -                | 0 (0.000) |    16.39 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           36 |      148 | 2024-07-27 | CPH Wolves      | W   | 1.000      | 0.435        | -                | 0.359 (0.156)    | 0 (0.000) |    11.35 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           35 |      245 | 2024-07-24 | BC.Game         | W   | 1.000      | 0.435        | -                | 0.153 (0.067)    | 0 (0.000) |     5.99 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           34 |     1140 | 2024-06-08 | Monte           | L   | 0.846      | -            | -                | -                | -         |   -11.02 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           33 |     1141 | 2024-06-08 | Quixal          | W   | 0.845      | -            | -                | -                | 0 (0.000) |     1.08 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           32 |     1151 | 2024-06-08 | AMKAL           | L   | 0.845      | -            | -                | -                | -         |    -5.77 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           31 |     1272 | 2024-06-06 | FAVBET          | L   | 0.831      | -            | -                | -                | -         |   -18.99 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           30 |     1450 | 2024-06-01 | Insilio         | L   | 0.799      | -            | -                | -                | -         |   -14.28 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           29 |     1508 | 2024-05-30 | V1dar           | W   | 0.785      | -            | -                | -                | 0 (0.000) |     1.85 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           28 |     1595 | 2024-05-26 | 9 Pandas        | L   | 0.758      | -            | -                | -                | -         |   -10.28 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           27 |     1620 | 2024-05-25 | FURIA           | W   | 0.751      | 0.435        | 0.284 (0.093)    | 0.495 (0.162)    | 0 (0.000) |    22.97 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           26 |     1644 | 2024-05-23 | ECSTATIC        | W   | 0.739      | -            | -                | -                | 0 (0.000) |     0.83 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           25 |     1818 | 2024-05-18 | SINNERS         | W   | 0.705      | 0.435        | 0.038 (0.012)    | 0.721 (0.221)    | 0 (0.000) |    12.30 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           24 |     1898 | 2024-05-16 | Zero Tenacity   | W   | 0.691      | 0.435        | 0.138 (0.041)    | 1.000 (0.300)    | -         |    14.25 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           23 |     2020 | 2024-05-13 | Permitta        | W   | 0.672      | 0.435        | 0.024 (0.007)    | 0.799 (0.234)    | -         |     9.08 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           22 |     2122 | 2024-05-09 | Sashi           | L   | 0.644      | -            | -                | -                | -         |    -3.72 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           21 |     2148 | 2024-05-08 | Nemiga          | W   | 0.637      | 0.396        | 0.322 (0.081)    | 0.698 (0.176)    | -         |    15.92 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           20 |     2158 | 2024-05-07 | BLEED           | W   | 0.632      | 0.396        | 0.095 (0.024)    | 0.409 (0.103)    | -         |    13.94 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           19 |     2206 | 2024-05-05 | ex-Guild Eagles | W   | 0.617      | -            | -                | -                | -         |     7.90 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           18 |     2250 | 2024-05-02 | Soda            | W   | 0.599      | -            | -                | -                | -         |     0.99 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           17 |     2258 | 2024-05-02 | 500             | W   | 0.598      | -            | -                | -                | -         |     5.06 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           16 |     2321 | 2024-04-29 | ECLOT           | L   | 0.579      | -            | -                | -                | -         |    -4.67 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           15 |     2323 | 2024-04-29 | SINNERS         | L   | 0.578      | -            | -                | -                | -         |    -6.85 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           14 |     2339 | 2024-04-28 | Sangal          | L   | 0.572      | -            | -                | -                | -         |    -4.67 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           13 |     2371 | 2024-04-27 | Nemiga          | L   | 0.564      | -            | -                | -                | -         |    -3.68 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           12 |     2420 | 2024-04-25 | Permitta        | W   | 0.552      | 0.435        | 0.024 (0.006)    | 0.799 (0.192)    | -         |     9.47 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           11 |     2459 | 2024-04-23 | HAVU            | W   | 0.538      | -            | -                | -                | -         |     3.93 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           10 |     2498 | 2024-04-21 | Nemiga          | L   | 0.524      | -            | -                | -                | -         |    -3.44 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            9 |     2518 | 2024-04-20 | Portugal        | W   | 0.519      | -            | -                | -                | -         |     3.71 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            8 |     2690 | 2024-04-16 | ENCE Academy    | W   | 0.492      | -            | -                | -                | -         |     4.50 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            7 |     2718 | 2024-04-15 | Lazer Cats      | W   | 0.483      | -            | -                | -                | -         |     1.65 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            6 |     2882 | 2024-04-09 | Aurora          | L   | 0.445      | -            | -                | -                | -         |    -0.20 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            5 |     2903 | 2024-04-08 | 9 Pandas        | W   | 0.439      | 0.143        | 0.082 (0.005)    | -                | -         |     9.03 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            4 |     2915 | 2024-04-08 | Aurora          | W   | 0.438      | 0.143        | 0.429 (0.027)    | -                | -         |    13.63 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            3 |     3507 | 2024-03-11 | Insilio         | L   | 0.252      | -            | -                | -                | -         |    -3.90 | buster, lattykk, neaLaN, oz1k, Ryujin   |
|            2 |     3529 | 2024-03-10 | VP.Prodigy      | W   | 0.245      | -            | -                | -                | -         |     3.67 | buster, lattykk, neaLaN, oz1k, Ryujin   |
|            1 |     3657 | 2024-03-05 | ARCRED          | L   | 0.213      | -            | -                | -                | -         |    -3.68 | buster, lattykk, neaLaN, oz1k, Ryujin   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,948.62)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.759 | $5,000.00      | $3,793.91       |
| 2024-05-09 |      0.644 | $8,000.00      | $5,154.70       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
