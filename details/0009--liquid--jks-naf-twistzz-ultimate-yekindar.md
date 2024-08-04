### Roster Details<br />
Team Name: Liquid<br />
Roster: jks, NAF, Twistzz, ultimate, YEKINDAR<br />
Global Rank: [9](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [8]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [1]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1670.5<br />
<br />
Final Rank Value (1670.5) = Starting Rank Value (1593.1) + Head To Head Adjustments (77.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.707[<sup>1</sup>](#table2)
- Bounty Collected: 0.622[<sup>2</sup>](#table1)
- Opponent Network: 0.198[<sup>2</sup>](#table1)
- LAN Wins: 0.807[<sup>2</sup>](#table1)

The average of these factors is 0.584<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1593.1
- 400 + ( ( 0.584 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1593.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |       11 | 2024-08-03 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.331 (0.192)    | 1 (1.000) |    25.61 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           37 |       90 | 2024-08-01 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.331 (0.192)    | 1 (1.000) |    26.87 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           36 |      132 | 2024-07-31 | Virtus.pro       | W   | 1.000      | 0.581        | 0.497 (0.289)    | 0.323 (0.188)    | 1 (1.000) |    19.16 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           35 |     1645 | 2024-05-29 | G2               | L   | 0.756      | -            | -                | -                | -         |    -3.18 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     1670 | 2024-05-28 | Falcons          | W   | 0.750      | 0.624        | 0.224 (0.105)    | -                | 1 (0.750) |     6.50 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     1688 | 2024-05-27 | 9z               | L   | 0.743      | -            | -                | -                | -         |   -16.56 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     1699 | 2024-05-27 | Complexity       | W   | 0.742      | 0.624        | 0.310 (0.144)    | 0.380 (0.176)    | 1 (0.742) |    13.49 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     1773 | 2024-05-23 | Eternal Fire     | L   | 0.714      | -            | -                | -                | -         |    -8.80 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     1817 | 2024-05-22 | Astralis         | W   | 0.706      | 0.769        | 0.391 (0.212)    | 0.421 (0.228)    | -         |    15.63 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     1862 | 2024-05-21 | ENCE             | W   | 0.699      | 0.769        | 0.169 (0.091)    | 0.400 (0.215)    | -         |     5.41 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     1918 | 2024-05-19 | AMKAL            | W   | 0.687      | 0.769        | -                | 0.475 (0.251)    | -         |     2.15 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     1933 | 2024-05-18 | OG               | W   | 0.682      | 0.769        | 0.139 (0.073)    | -                | -         |     1.04 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     2223 | 2024-05-10 | Astralis         | L   | 0.627      | -            | -                | -                | -         |    -5.65 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     2267 | 2024-05-08 | FlyQuest         | W   | 0.614      | 0.889        | -                | 0.294 (0.160)    | 1 (0.614) |     2.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     2335 | 2024-05-04 | MOUZ             | L   | 0.588      | -            | -                | -                | -         |    -3.41 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     2397 | 2024-05-01 | Monte            | W   | 0.568      | -            | -                | -                | 1 (0.568) |     0.64 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     2420 | 2024-04-30 | FURIA            | W   | 0.561      | 0.889        | 0.284 (0.142)    | 0.490 (0.245)    | 1 (0.561) |    10.62 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     2664 | 2024-04-19 | M80              | L   | 0.490      | -            | -                | -                | -         |   -13.64 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     2714 | 2024-04-18 | M80              | W   | 0.484      | -            | -                | -                | -         |     1.71 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     2717 | 2024-04-18 | Legacy           | W   | 0.482      | -            | -                | -                | -         |     0.60 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     2764 | 2024-04-17 | Akimbo           | W   | 0.476      | -            | -                | -                | -         |     0.15 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     2769 | 2024-04-17 | straykids        | W   | 0.476      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     2882 | 2024-04-12 | FaZe             | L   | 0.439      | -            | -                | -                | -         |    -4.99 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     2967 | 2024-04-10 | MOUZ             | L   | 0.426      | -            | -                | -                | -         |    -2.59 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     3045 | 2024-04-08 | G2               | W   | 0.412      | 0.624        | 1.000 (0.257)    | 0.498 (0.128)    | 1 (0.412) |    11.72 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     3055 | 2024-04-07 | HEROIC           | W   | 0.411      | -            | -                | -                | 1 (0.411) |     6.05 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     3727 | 2024-03-07 | SAW              | L   | 0.201      | -            | -                | -                | -         |    -5.76 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     3809 | 2024-03-04 | Complexity       | L   | 0.182      | -            | -                | -                | -         |    -2.44 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     3845 | 2024-03-03 | BOSS             | W   | 0.174      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     3858 | 2024-03-02 | FURIA            | L   | 0.168      | -            | -                | -                | -         |    -1.73 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     3873 | 2024-03-01 | BESTIA           | W   | 0.163      | -            | -                | -                | -         |     0.21 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     3944 | 2024-02-26 | Nouns            | W   | 0.137      | -            | -                | -                | -         |     0.10 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     3946 | 2024-02-26 | BOSS             | W   | 0.136      | -            | -                | -                | -         |     0.05 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     3959 | 2024-02-25 | Wildcard         | W   | 0.131      | -            | -                | -                | -         |     0.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     3964 | 2024-02-25 | Nouns            | L   | 0.129      | -            | -                | -                | -         |    -3.99 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     4023 | 2024-02-22 | Party Astronauts | W   | 0.110      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     4025 | 2024-02-22 | MIGHT            | W   | 0.110      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     4031 | 2024-02-22 | ex-CatEvil       | W   | 0.110      | -            | -                | -                | -         |     0.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($124,686.34)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.38) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-06-02 |      0.782 | $6,000.00      | $4,689.03       |
| 2024-05-23 |      0.714 | $100,000.00    | $71,358.80      |
| 2024-05-12 |      0.641 | $32,000.00     | $20,501.48      |
| 2024-04-14 |      0.453 | $10,000.00     | $4,527.78       |
| 2024-03-10 |      0.222 | $5,000.00      | $1,109.26       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
