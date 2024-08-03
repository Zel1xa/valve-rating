### Roster Details<br />
Team Name: FORZE<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Global Rank: [76](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [55]( ../standings_europe.md)<br />
<br />
Final Rank Value:  935.5<br />
<br />
Final Rank Value (935.5) = Starting Rank Value (887.8) + Head To Head Adjustments (47.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.448[<sup>1</sup>](#table2)
- Bounty Collected: 0.382[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.238<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 887.8
- 400 + ( ( 0.238 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 887.8


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
|           30 |     2266 | 2024-05-04 | Monte           | L   | 0.592      | -            | -                | -                | -         |    -7.66 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           29 |     2294 | 2024-05-02 | GamerLegion     | L   | 0.580      | -            | -                | -                | -         |    -4.86 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |     2320 | 2024-05-01 | FURIA           | W   | 0.574      | 0.889        | 0.284 (0.145)    | 0.508 (0.259)    | 1 (0.574) |    17.72 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           27 |     2343 | 2024-04-30 | Monte           | L   | 0.567      | -            | -                | -                | -         |    -7.32 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           26 |     2797 | 2024-04-12 | BIG             | L   | 0.446      | -            | -                | -                | -         |    -1.58 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           25 |     2830 | 2024-04-11 | Aurora          | L   | 0.439      | -            | -                | -                | -         |    -0.28 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           24 |     2862 | 2024-04-10 | TSM             | W   | 0.434      | 0.500        | 0.005 (0.001)    | -                | 0 (0.000) |     2.63 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           23 |     2917 | 2024-04-09 | brazylijski luz | W   | 0.427      | 0.500        | 0.008 (0.002)    | 0.271 (0.058)    | 0 (0.000) |     4.36 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           22 |     2958 | 2024-04-08 | ENCE            | W   | 0.419      | 0.684        | 0.170 (0.049)    | 0.415 (0.119)    | 0 (0.000) |    12.53 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           21 |     3230 | 2024-03-27 | 500             | L   | 0.340      | -            | -                | -                | -         |    -8.18 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     3259 | 2024-03-26 | Apeks           | W   | 0.332      | 0.500        | 0.027 (0.005)    | 0.174 (0.029)    | 0 (0.000) |     5.04 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     3265 | 2024-03-25 | B8              | L   | 0.326      | -            | -                | -                | -         |    -2.93 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     3270 | 2024-03-24 | BetBoom         | W   | 0.318      | 0.143        | 0.252 (0.011)    | 0.563 (0.026)    | 0 (0.000) |     9.45 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     3280 | 2024-03-23 | VP.Prodigy      | W   | 0.313      | 0.143        | -                | 0.416 (0.019)    | 0 (0.000) |     4.36 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     3293 | 2024-03-22 | ex-Preasy       | W   | 0.306      | -            | -                | -                | 0 (0.000) |     3.56 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     3316 | 2024-03-21 | PARIVISION      | L   | 0.299      | -            | -                | -                | -         |    -2.31 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     3340 | 2024-03-20 | NAVI Junior     | W   | 0.293      | -            | -                | -                | 0 (0.000) |     1.04 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     3694 | 2024-03-05 | KOI             | L   | 0.194      | -            | -                | -                | -         |    -2.88 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     3699 | 2024-03-05 | AMKAL           | W   | 0.194      | 0.143        | 0.130 (0.004)    | 0.494 (0.014)    | 0 (0.000) |     4.84 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     3706 | 2024-03-05 | 3DMAX           | W   | 0.193      | 0.143        | 0.504 (0.014)    | 1.000 (0.028)    | -         |     6.01 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     3795 | 2024-03-01 | Aurora          | L   | 0.167      | -            | -                | -                | -         |    -0.07 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     3804 | 2024-02-29 | 9 Pandas        | W   | 0.160      | 0.143        | 0.082 (0.002)    | 0.715 (0.016)    | -         |     3.25 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     3816 | 2024-02-28 | KOI             | W   | 0.154      | -            | -                | -                | -         |     2.68 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     3821 | 2024-02-28 | Aurora          | W   | 0.153      | 0.143        | 0.425 (0.009)    | 0.809 (0.018)    | -         |     4.75 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     3834 | 2024-02-27 | V1dar           | W   | 0.147      | -            | -                | -                | -         |     0.53 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     3842 | 2024-02-27 | ARCRED          | W   | 0.147      | -            | -                | -                | -         |     2.18 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     4239 | 2024-02-09 | Sashi           | L   | 0.027      | -            | -                | -                | -         |    -0.15 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     4245 | 2024-02-09 | RUBY            | W   | 0.026      | -            | -                | -                | -         |     0.46 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     4253 | 2024-02-08 | BetBoom         | W   | 0.020      | -            | -                | -                | -         |     0.61 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     4258 | 2024-02-08 | Sashi           | L   | 0.019      | -            | -                | -                | -         |    -0.11 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,080.19)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.833 | $3,000.00      | $2,499.10       |
| 2024-05-12 |      0.646 | $7,000.00      | $4,523.10       |
| 2024-04-14 |      0.459 | $26,250.00     | $12,057.99      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
