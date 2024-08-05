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
Final Rank Value:  1673.0<br />
<br />
Final Rank Value (1673.0) = Starting Rank Value (1596.3) + Head To Head Adjustments (76.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.706[<sup>1</sup>](#table2)
- Bounty Collected: 0.623[<sup>2</sup>](#table1)
- Opponent Network: 0.203[<sup>2</sup>](#table1)
- LAN Wins: 0.807[<sup>2</sup>](#table1)

The average of these factors is 0.585<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1596.3
- 400 + ( ( 0.585 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1596.3


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
|           38 |       37 | 2024-08-03 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.371 (0.215)    | 1 (1.000) |    25.59 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           37 |      116 | 2024-08-01 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.371 (0.215)    | 1 (1.000) |    26.85 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           36 |      160 | 2024-07-31 | Virtus.pro       | W   | 1.000      | 0.581        | 0.497 (0.289)    | 0.323 (0.187)    | 1 (1.000) |    19.08 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           35 |     1673 | 2024-05-29 | G2               | L   | 0.753      | -            | -                | -                | -         |    -3.20 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     1698 | 2024-05-28 | Falcons          | W   | 0.746      | 0.624        | 0.223 (0.104)    | -                | 1 (0.746) |     6.38 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     1716 | 2024-05-27 | 9z               | L   | 0.740      | -            | -                | -                | -         |   -16.56 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     1727 | 2024-05-27 | Complexity       | W   | 0.738      | 0.624        | 0.342 (0.158)    | 0.380 (0.175)    | 1 (0.738) |    13.61 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     1801 | 2024-05-23 | Eternal Fire     | L   | 0.710      | -            | -                | -                | -         |    -8.86 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     1845 | 2024-05-22 | Astralis         | W   | 0.703      | 0.769        | 0.390 (0.211)    | 0.421 (0.227)    | -         |    15.49 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     1890 | 2024-05-21 | ENCE             | W   | 0.696      | 0.769        | 0.168 (0.090)    | 0.439 (0.235)    | -         |     5.45 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     1946 | 2024-05-19 | AMKAL            | W   | 0.683      | 0.769        | -                | 0.474 (0.249)    | -         |     2.10 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     1961 | 2024-05-18 | OG               | W   | 0.679      | 0.769        | 0.138 (0.072)    | -                | -         |     1.02 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     2251 | 2024-05-10 | Astralis         | L   | 0.624      | -            | -                | -                | -         |    -5.69 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     2295 | 2024-05-08 | FlyQuest         | W   | 0.610      | 0.889        | -                | 0.293 (0.159)    | 1 (0.610) |     2.04 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     2363 | 2024-05-04 | MOUZ             | L   | 0.585      | -            | -                | -                | -         |    -3.45 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     2425 | 2024-05-01 | Monte            | W   | 0.565      | -            | -                | -                | 1 (0.565) |     0.62 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     2448 | 2024-04-30 | FURIA            | W   | 0.558      | 0.889        | 0.284 (0.141)    | 0.490 (0.243)    | 1 (0.558) |    10.51 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     2692 | 2024-04-19 | M80              | L   | 0.487      | -            | -                | -                | -         |   -13.59 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     2742 | 2024-04-18 | M80              | W   | 0.480      | -            | -                | -                | -         |     1.66 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     2745 | 2024-04-18 | Legacy           | W   | 0.479      | -            | -                | -                | -         |     0.59 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     2792 | 2024-04-17 | Akimbo           | W   | 0.473      | -            | -                | -                | -         |     0.14 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     2797 | 2024-04-17 | straykids        | W   | 0.473      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     2910 | 2024-04-12 | FaZe             | L   | 0.436      | -            | -                | -                | -         |    -5.02 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     2995 | 2024-04-10 | MOUZ             | L   | 0.422      | -            | -                | -                | -         |    -2.62 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     3073 | 2024-04-08 | G2               | W   | 0.409      | 0.624        | 1.000 (0.255)    | 0.498 (0.127)    | 1 (0.409) |    11.60 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     3083 | 2024-04-07 | HEROIC           | W   | 0.408      | -            | -                | -                | 1 (0.408) |     5.95 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     3755 | 2024-03-07 | SAW              | L   | 0.197      | -            | -                | -                | -         |    -5.67 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     3837 | 2024-03-04 | Complexity       | L   | 0.179      | -            | -                | -                | -         |    -2.35 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     3873 | 2024-03-03 | BOSS             | W   | 0.171      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     3886 | 2024-03-02 | FURIA            | L   | 0.164      | -            | -                | -                | -         |    -1.71 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     3901 | 2024-03-01 | BESTIA           | W   | 0.159      | -            | -                | -                | -         |     0.20 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     3972 | 2024-02-26 | Nouns            | W   | 0.134      | -            | -                | -                | -         |     0.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     3974 | 2024-02-26 | BOSS             | W   | 0.133      | -            | -                | -                | -         |     0.05 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     3987 | 2024-02-25 | Wildcard         | W   | 0.127      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     3992 | 2024-02-25 | Nouns            | L   | 0.126      | -            | -                | -                | -         |    -3.89 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     4051 | 2024-02-22 | Party Astronauts | W   | 0.107      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     4053 | 2024-02-22 | MIGHT            | W   | 0.106      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     4059 | 2024-02-22 | ex-CatEvil       | W   | 0.106      | -            | -                | -                | -         |     0.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($124,158.63)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.38) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-06-02 |      0.778 | $6,000.00      | $4,668.33       |
| 2024-05-23 |      0.710 | $100,000.00    | $71,013.89      |
| 2024-05-12 |      0.637 | $32,000.00     | $20,391.11      |
| 2024-04-14 |      0.449 | $10,000.00     | $4,493.29       |
| 2024-03-10 |      0.218 | $5,000.00      | $1,092.01       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
