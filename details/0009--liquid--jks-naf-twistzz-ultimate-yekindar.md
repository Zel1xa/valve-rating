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
Final Rank Value:  1672.3<br />
<br />
Final Rank Value (1672.3) = Starting Rank Value (1595.4) + Head To Head Adjustments (76.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.706[<sup>1</sup>](#table2)
- Bounty Collected: 0.622[<sup>2</sup>](#table1)
- Opponent Network: 0.198[<sup>2</sup>](#table1)
- LAN Wins: 0.805[<sup>2</sup>](#table1)

The average of these factors is 0.583<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1595.4
- 400 + ( ( 0.583 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1595.4


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
|           38 |       61 | 2024-08-03 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.365 (0.212)    | 1 (1.000) |    25.60 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           37 |      140 | 2024-08-01 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.365 (0.212)    | 1 (1.000) |    26.86 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           36 |      184 | 2024-07-31 | Virtus.pro       | W   | 1.000      | 0.581        | 0.498 (0.289)    | 0.316 (0.184)    | 1 (1.000) |    19.04 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           35 |     1697 | 2024-05-29 | G2               | L   | 0.746      | -            | -                | -                | -         |    -3.14 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     1722 | 2024-05-28 | Falcons          | W   | 0.739      | 0.624        | 0.221 (0.102)    | -                | 1 (0.739) |     6.28 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     1740 | 2024-05-27 | 9z               | L   | 0.733      | -            | -                | -                | -         |   -16.42 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     1751 | 2024-05-27 | Complexity       | W   | 0.732      | 0.624        | 0.342 (0.156)    | 0.373 (0.170)    | 1 (0.732) |    13.45 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     1825 | 2024-05-23 | Eternal Fire     | L   | 0.703      | -            | -                | -                | -         |    -8.78 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     1869 | 2024-05-22 | Astralis         | W   | 0.696      | 0.769        | 0.389 (0.208)    | 0.413 (0.221)    | -         |    15.31 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     1914 | 2024-05-21 | ENCE             | W   | 0.689      | 0.769        | 0.174 (0.092)    | 0.432 (0.229)    | -         |     5.49 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     1970 | 2024-05-19 | AMKAL            | W   | 0.677      | 0.769        | -                | 0.464 (0.241)    | -         |     2.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     1985 | 2024-05-18 | OG               | W   | 0.672      | 0.769        | 0.137 (0.071)    | -                | -         |     1.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     2275 | 2024-05-10 | Astralis         | L   | 0.617      | -            | -                | -                | -         |    -5.67 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     2319 | 2024-05-08 | FlyQuest         | W   | 0.604      | 0.889        | -                | 0.285 (0.153)    | 1 (0.604) |     1.98 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     2387 | 2024-05-04 | MOUZ             | L   | 0.578      | -            | -                | -                | -         |    -3.41 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     2449 | 2024-05-01 | Monte            | W   | 0.558      | -            | -                | -                | 1 (0.558) |     0.61 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     2472 | 2024-04-30 | FURIA            | W   | 0.551      | 0.889        | 0.284 (0.139)    | 0.480 (0.235)    | 1 (0.551) |    10.44 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     2716 | 2024-04-19 | M80              | L   | 0.480      | -            | -                | -                | -         |   -13.41 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     2766 | 2024-04-18 | M80              | W   | 0.473      | -            | -                | -                | -         |     1.63 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     2769 | 2024-04-18 | Legacy           | W   | 0.472      | -            | -                | -                | -         |     0.58 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     2816 | 2024-04-17 | Akimbo           | W   | 0.466      | -            | -                | -                | -         |     0.14 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     2821 | 2024-04-17 | straykids        | W   | 0.466      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     2934 | 2024-04-12 | FaZe             | L   | 0.429      | -            | -                | -                | -         |    -5.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     3019 | 2024-04-10 | MOUZ             | L   | 0.415      | -            | -                | -                | -         |    -2.57 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     3097 | 2024-04-08 | G2               | W   | 0.402      | 0.624        | 1.000 (0.251)    | 0.489 (0.123)    | 1 (0.402) |    11.42 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     3107 | 2024-04-07 | HEROIC           | W   | 0.401      | -            | -                | -                | 1 (0.401) |     5.82 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     3779 | 2024-03-07 | SAW              | L   | 0.190      | -            | -                | -                | -         |    -5.48 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     3861 | 2024-03-04 | Complexity       | L   | 0.172      | -            | -                | -                | -         |    -2.27 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     3897 | 2024-03-03 | BOSS             | W   | 0.164      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     3910 | 2024-03-02 | FURIA            | L   | 0.158      | -            | -                | -                | -         |    -1.63 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     3925 | 2024-03-01 | BESTIA           | W   | 0.153      | -            | -                | -                | -         |     0.19 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     3996 | 2024-02-26 | Nouns            | W   | 0.127      | -            | -                | -                | -         |     0.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     3998 | 2024-02-26 | BOSS             | W   | 0.126      | -            | -                | -                | -         |     0.05 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     4011 | 2024-02-25 | Wildcard         | W   | 0.120      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     4016 | 2024-02-25 | Nouns            | L   | 0.119      | -            | -                | -                | -         |    -3.68 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     4075 | 2024-02-22 | Party Astronauts | W   | 0.100      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     4077 | 2024-02-22 | MIGHT            | W   | 0.100      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     4083 | 2024-02-22 | ex-CatEvil       | W   | 0.099      | -            | -                | -                | -         |     0.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($123,138.63)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.38) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-06-02 |      0.771 | $6,000.00      | $4,628.33       |
| 2024-05-23 |      0.703 | $100,000.00    | $70,347.22      |
| 2024-05-12 |      0.631 | $32,000.00     | $20,177.78      |
| 2024-04-14 |      0.443 | $10,000.00     | $4,426.62       |
| 2024-03-10 |      0.212 | $5,000.00      | $1,058.68       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
