### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  945.9<br />
<br />
Final Rank Value (945.9) = Starting Rank Value (895.8) + Head To Head Adjustments (50.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.450[<sup>1</sup>](#table2)
- Bounty Collected: 0.385[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.068[<sup>2</sup>](#table1)

The average of these factors is 0.241<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 895.8
- 400 + ( ( 0.241 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 895.8


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
|           30 |     2310 | 2024-05-04 | Monte           | L   | 0.607      | -            | -                | -                | -         |    -7.80 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           29 |     2338 | 2024-05-02 | GamerLegion     | L   | 0.595      | -            | -                | -                | -         |    -5.05 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |     2366 | 2024-05-01 | FURIA           | W   | 0.588      | 0.889        | 0.286 (0.150)    | 0.495 (0.259)    | 1 (0.588) |    18.17 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           27 |     2390 | 2024-04-30 | Monte           | L   | 0.582      | -            | -                | -                | -         |    -7.45 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           26 |     2855 | 2024-04-12 | BIG             | L   | 0.461      | -            | -                | -                | -         |    -2.49 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           25 |     2889 | 2024-04-11 | Aurora          | L   | 0.454      | -            | -                | -                | -         |    -0.30 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           24 |     2921 | 2024-04-10 | TSM             | W   | 0.448      | -            | -                | -                | 0 (0.000) |     2.65 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           23 |     2976 | 2024-04-09 | brazylijski luz | W   | 0.442      | 0.500        | 0.008 (0.002)    | 0.309 (0.068)    | 0 (0.000) |     4.55 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           22 |     3017 | 2024-04-08 | ENCE            | W   | 0.434      | 0.684        | 0.174 (0.052)    | 0.403 (0.120)    | 0 (0.000) |    12.97 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           21 |     3299 | 2024-03-27 | 500             | L   | 0.355      | -            | -                | -                | -         |    -8.34 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     3334 | 2024-03-26 | Apeks           | W   | 0.347      | 0.500        | 0.030 (0.005)    | 0.194 (0.034)    | 0 (0.000) |     5.33 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     3340 | 2024-03-25 | B8              | L   | 0.341      | -            | -                | -                | -         |    -3.09 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     3345 | 2024-03-24 | BetBoom         | W   | 0.333      | 0.143        | 0.257 (0.012)    | 0.551 (0.026)    | 0 (0.000) |     9.89 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     3356 | 2024-03-23 | VP.Prodigy      | W   | 0.327      | 0.143        | -                | 0.405 (0.019)    | 0 (0.000) |     4.49 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     3370 | 2024-03-22 | ex-Preasy       | W   | 0.320      | -            | -                | -                | 0 (0.000) |     3.75 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     3393 | 2024-03-21 | PARIVISION      | L   | 0.314      | -            | -                | -                | -         |    -2.58 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     3417 | 2024-03-20 | NAVI Junior     | W   | 0.307      | -            | -                | -                | 0 (0.000) |     1.05 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     3780 | 2024-03-05 | KOI             | L   | 0.209      | -            | -                | -                | -         |    -3.12 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     3785 | 2024-03-05 | AMKAL           | W   | 0.209      | 0.143        | 0.132 (0.004)    | 0.482 (0.014)    | 0 (0.000) |     5.15 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     3797 | 2024-03-05 | 3DMAX           | W   | 0.208      | 0.143        | 0.505 (0.015)    | 1.000 (0.030)    | -         |     6.46 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     3887 | 2024-03-01 | Aurora          | L   | 0.182      | -            | -                | -                | -         |    -0.07 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     3896 | 2024-02-29 | 9 Pandas        | W   | 0.175      | 0.143        | 0.083 (0.002)    | 0.578 (0.014)    | -         |     3.53 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     3908 | 2024-02-28 | KOI             | W   | 0.168      | -            | -                | -                | -         |     2.92 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     3914 | 2024-02-28 | Aurora          | W   | 0.167      | 0.143        | 0.432 (0.010)    | 0.798 (0.019)    | -         |     5.21 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     3927 | 2024-02-27 | V1dar           | W   | 0.162      | -            | -                | -                | -         |     0.57 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     3935 | 2024-02-27 | ARCRED          | W   | 0.161      | -            | -                | -                | -         |     2.27 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4351 | 2024-02-09 | Sashi           | L   | 0.042      | -            | -                | -                | -         |    -0.24 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4357 | 2024-02-09 | RUBY            | W   | 0.041      | -            | -                | -                | -         |     0.73 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4365 | 2024-02-08 | BetBoom         | W   | 0.035      | 0.143        | 0.257 (0.001)    | -                | -         |     1.06 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4370 | 2024-02-08 | Sashi           | L   | 0.034      | -            | -                | -                | -         |    -0.19 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,612.19)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.848 | $3,000.00      | $2,543.13       |
| 2024-05-12 |      0.661 | $7,000.00      | $4,625.83       |
| 2024-04-14 |      0.474 | $26,250.00     | $12,443.23      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
