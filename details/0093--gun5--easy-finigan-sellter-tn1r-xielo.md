### Roster Details<br />
Team Name: GUN5<br />
Roster: easy, FinigaN, SELLTER, tN1R, xiELO<br />
Global Rank: [93](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  866.8<br />
<br />
Final Rank Value (866.8) = Starting Rank Value (931.4) + Head To Head Adjustments (-64.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.468[<sup>1</sup>](#table2)
- Bounty Collected: 0.379[<sup>2</sup>](#table1)
- Opponent Network: 0.192[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.260<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 931.4
- 400 + ( ( 0.260 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 931.4


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
|           38 |        3 | 2024-08-03 | PARIVISION        | W   | 1.000      | 0.500        | 0.018 (0.009)    | 0.553 (0.276)    | 0 (0.000) |    25.37 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           37 |        9 | 2024-08-03 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -7.20 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           36 |       58 | 2024-08-01 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -20.51 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           35 |       71 | 2024-08-01 | NOM               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.53 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           34 |      120 | 2024-07-31 | K27               | L   | 1.000      | -            | -                | -                | -         |   -26.70 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           33 |      160 | 2024-07-30 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.540 (0.235)    | 0 (0.000) |    13.72 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           32 |      197 | 2024-07-29 | TSM               | W   | 1.000      | 0.143        | 0.039 (0.006)    | -                | 0 (0.000) |    20.48 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           31 |      225 | 2024-07-28 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.28 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           30 |      230 | 2024-07-28 | NOM               | L   | 1.000      | -            | -                | -                | -         |   -25.99 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           29 |      273 | 2024-07-26 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -21.70 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           28 |      309 | 2024-07-25 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -15.56 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           27 |      380 | 2024-07-23 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -23.53 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           26 |      433 | 2024-07-21 | Endpoint          | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.540 (0.235)    | 0 (0.000) |    12.56 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           25 |      474 | 2024-07-20 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -17.07 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           24 |      615 | 2024-07-17 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -11.71 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           23 |      637 | 2024-07-17 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.85 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           22 |      672 | 2024-07-16 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -25.15 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           21 |      726 | 2024-07-15 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -22.28 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           20 |      946 | 2024-06-15 | 3DMAX             | L   | 0.874      | -            | -                | -                | -         |    -2.11 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |      983 | 2024-06-14 | Gaimin Gladiators | W   | 0.867      | 0.435        | 0.038 (0.014)    | 0.366 (0.138)    | 0 (0.000) |    12.70 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |      998 | 2024-06-14 | Spirit Academy    | L   | 0.865      | -            | -                | -                | -         |   -22.02 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |     1098 | 2024-06-10 | EYEBALLERS        | W   | 0.839      | 0.435        | -                | 0.528 (0.192)    | 0 (0.000) |     9.68 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |     1246 | 2024-06-07 | HAVU              | W   | 0.820      | -            | -                | -                | 0 (0.000) |     4.74 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |     1373 | 2024-06-05 | CYBERSHOKE        | W   | 0.807      | 0.435        | 0.039 (0.014)    | 0.327 (0.115)    | -         |     8.56 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |     1456 | 2024-06-03 | Permitta          | L   | 0.792      | -            | -                | -                | -         |   -15.44 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |     1467 | 2024-06-02 | FURIA             | W   | 0.786      | 0.435        | 0.284 (0.097)    | 0.508 (0.174)    | -         |    23.93 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |     1479 | 2024-06-02 | VP.Prodigy        | W   | 0.784      | 0.435        | 0.026 (0.009)    | 0.416 (0.142)    | -         |    11.15 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |     1488 | 2024-06-01 | SINNERS           | W   | 0.781      | 0.435        | 0.037 (0.013)    | 0.784 (0.266)    | -         |    15.64 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1532 | 2024-05-31 | GamerLegion       | W   | 0.773      | 0.435        | 0.174 (0.058)    | -                | -         |    19.24 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1611 | 2024-05-28 | Permitta          | L   | 0.751      | -            | -                | -                | -         |   -12.59 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1650 | 2024-05-26 | DMS               | W   | 0.738      | 0.435        | -                | 0.462 (0.148)    | -         |    10.85 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1676 | 2024-05-24 | SINNERS           | L   | 0.727      | -            | -                | -                | -         |    -8.38 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1691 | 2024-05-23 | Sampi             | L   | 0.720      | -            | -                | -                | -         |   -12.40 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     1861 | 2024-05-18 | NOM               | W   | 0.687      | -            | -                | -                | -         |     2.34 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     1933 | 2024-05-16 | Space             | W   | 0.674      | -            | -                | -                | -         |     7.98 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     1980 | 2024-05-15 | 777               | W   | 0.667      | -            | -                | -                | -         |     4.64 | easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     3089 | 2024-04-03 | 3DMAX             | L   | 0.387      | -            | -                | -                | -         |    -0.22 | easy, kelieN, SELLTER, spirit, tN1R  |
|            1 |     3194 | 2024-03-28 | Space             | W   | 0.346      | -            | -                | -                | -         |     3.76 | easy, r3salt, SELLTER, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,750.74)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.880 | $2,000.00      | $1,759.54       |
| 2024-06-16 |      0.879 | $2,500.00      | $2,196.64       |
| 2024-06-09 |      0.833 | $3,000.00      | $2,499.10       |
| 2024-06-02 |      0.786 | $22,000.00     | $17,295.46      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
