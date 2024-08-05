### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [71](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
<br />
Final Rank Value:  949.4<br />
<br />
Final Rank Value (949.4) = Starting Rank Value (896.3) + Head To Head Adjustments (53.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.450[<sup>1</sup>](#table2)
- Bounty Collected: 0.385[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.068[<sup>2</sup>](#table1)

The average of these factors is 0.241<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 896.3
- 400 + ( ( 0.241 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 896.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |     2219 | 2024-05-04 | Monte           | L   | 0.611      | -            | -                | -                | -         |    -7.86 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           29 |     2247 | 2024-05-02 | GamerLegion     | L   | 0.599      | -            | -                | -                | -         |    -5.02 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |     2273 | 2024-05-01 | FURIA           | W   | 0.593      | 0.889        | 0.284 (0.149)    | 0.495 (0.261)    | 1 (0.593) |    18.32 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           27 |     2296 | 2024-04-30 | Monte           | L   | 0.586      | -            | -                | -                | -         |    -7.51 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           26 |     2751 | 2024-04-12 | BIG             | L   | 0.465      | -            | -                | -                | -         |    -2.39 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           25 |     2784 | 2024-04-11 | Aurora          | L   | 0.458      | -            | -                | -                | -         |    -0.29 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           24 |     2816 | 2024-04-10 | TSM             | W   | 0.453      | -            | -                | -                | 0 (0.000) |     2.66 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           23 |     2871 | 2024-04-09 | brazylijski luz | W   | 0.446      | 0.500        | 0.008 (0.002)    | 0.264 (0.059)    | 0 (0.000) |     4.37 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           22 |     2912 | 2024-04-08 | ENCE            | W   | 0.438      | 0.684        | 0.173 (0.052)    | 0.404 (0.121)    | 0 (0.000) |    13.13 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           21 |     3185 | 2024-03-27 | 500             | L   | 0.359      | -            | -                | -                | -         |    -8.73 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     3216 | 2024-03-26 | Apeks           | W   | 0.351      | 0.500        | 0.030 (0.005)    | 0.176 (0.031)    | 0 (0.000) |     5.43 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     3222 | 2024-03-25 | B8              | L   | 0.345      | -            | -                | -                | -         |    -3.16 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     3227 | 2024-03-24 | BetBoom         | W   | 0.337      | 0.143        | 0.256 (0.012)    | 0.554 (0.027)    | 0 (0.000) |    10.04 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     3238 | 2024-03-23 | VP.Prodigy      | W   | 0.332      | 0.143        | -                | 0.406 (0.019)    | 0 (0.000) |     4.47 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     3252 | 2024-03-22 | ex-Preasy       | W   | 0.325      | -            | -                | -                | 0 (0.000) |     3.82 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     3275 | 2024-03-21 | PARIVISION      | L   | 0.319      | -            | -                | -                | -         |    -2.70 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     3299 | 2024-03-20 | NAVI Junior     | W   | 0.312      | -            | -                | -                | 0 (0.000) |     1.04 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     3656 | 2024-03-05 | KOI             | L   | 0.213      | -            | -                | -                | -         |    -1.80 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     3661 | 2024-03-05 | AMKAL           | W   | 0.213      | 0.143        | 0.131 (0.004)    | 0.484 (0.015)    | 0 (0.000) |     5.28 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     3668 | 2024-03-05 | 3DMAX           | W   | 0.212      | 0.143        | 0.499 (0.015)    | 1.000 (0.030)    | -         |     6.60 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     3757 | 2024-03-01 | Aurora          | L   | 0.186      | -            | -                | -                | -         |    -0.08 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     3766 | 2024-02-29 | 9 Pandas        | W   | 0.179      | 0.143        | 0.082 (0.002)    | 0.579 (0.015)    | -         |     3.64 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     3778 | 2024-02-28 | KOI             | W   | 0.173      | 0.143        | 0.059 (0.001)    | -                | -         |     4.12 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     3783 | 2024-02-28 | Aurora          | W   | 0.172      | 0.143        | 0.429 (0.011)    | 0.800 (0.020)    | -         |     5.34 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     3796 | 2024-02-27 | V1dar           | W   | 0.166      | -            | -                | -                | -         |     0.58 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     3804 | 2024-02-27 | ARCRED          | W   | 0.166      | -            | -                | -                | -         |     2.33 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4203 | 2024-02-09 | Sashi           | L   | 0.046      | -            | -                | -                | -         |    -0.26 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4208 | 2024-02-09 | RUBY            | W   | 0.045      | -            | -                | -                | -         |     0.79 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4216 | 2024-02-08 | BetBoom         | W   | 0.039      | -            | -                | -                | -         |     1.19 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4221 | 2024-02-08 | Sashi           | L   | 0.038      | -            | -                | -                | -         |    -0.21 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,769.44)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.852 | $3,000.00      | $2,556.14       |
| 2024-05-12 |      0.665 | $7,000.00      | $4,656.20       |
| 2024-04-14 |      0.478 | $26,250.00     | $12,557.10      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
