### Roster Details<br />
Team Name: HEROIC<br />
Roster: degster, kyxsan, NertZ, sjuush, TeSeS<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1376.0<br />
<br />
Final Rank Value (1376.0) = Starting Rank Value (1395.0) + Head To Head Adjustments (-19.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.593[<sup>1</sup>](#table2)
- Bounty Collected: 0.517[<sup>2</sup>](#table1)
- Opponent Network: 0.212[<sup>2</sup>](#table1)
- LAN Wins: 0.734[<sup>2</sup>](#table1)

The average of these factors is 0.514<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1395.0
- 400 + ( ( 0.514 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1395.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           50 |       17 | 2024-09-07 | Ninjas in Pyjamas | W   | 1.000      | 0.889        | 0.232 (0.207)    | 0.428 (0.380)    | 1 (1.000) |    13.96 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           49 |       73 | 2024-09-05 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -15.48 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           48 |      115 | 2024-09-04 | Lynn Vision       | W   | 1.000      | 0.889        | 0.073 (0.065)    | -                | 1 (1.000) |     2.20 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           47 |      152 | 2024-09-03 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |   -18.09 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           46 |      276 | 2024-08-29 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -4.54 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           45 |      317 | 2024-08-28 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -8.21 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           44 |      325 | 2024-08-28 | Falcons           | W   | 1.000      | -            | -                | -                | -         |    20.20 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           43 |      371 | 2024-08-27 | fnatic            | W   | 1.000      | -            | -                | -                | -         |    12.68 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           42 |      383 | 2024-08-27 | 3DMAX             | W   | 1.000      | 0.143        | 0.509 (0.073)    | 0.951 (0.136)    | -         |    17.45 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           41 |      444 | 2024-08-26 | B8                | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | -         |     6.97 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           40 |      460 | 2024-08-26 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -25.99 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           39 |      620 | 2024-08-21 | OG                | L   | 1.000      | -            | -                | -                | -         |   -27.79 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           38 |     1004 | 2024-08-09 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -8.95 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           37 |     1026 | 2024-08-08 | 3DMAX             | W   | 0.994      | 0.143        | 0.509 (0.072)    | -                | 1 (0.994) |    18.52 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           36 |     1077 | 2024-08-07 | MIBR              | L   | 0.986      | -            | -                | -                | -         |   -19.82 | kyxsan, NertZ, sjuush, TeSeS, Woro2k   |
|           35 |     1249 | 2024-08-02 | Complexity        | L   | 0.953      | -            | -                | -                | -         |   -12.99 | kyxsan, NertZ, sAw, sjuush, TeSeS      |
|           34 |     1384 | 2024-07-30 | Spirit            | L   | 0.932      | -            | -                | -                | -         |    -1.42 | kyxsan, NertZ, sAw, sjuush, TeSeS      |
|           33 |     1409 | 2024-07-29 | Complexity        | W   | 0.926      | 0.581        | 0.337 (0.181)    | 0.367 (0.197)    | 1 (0.926) |    16.65 | kyxsan, NertZ, sAw, sjuush, TeSeS      |
|           32 |     2579 | 2024-06-06 | ENCE              | W   | 0.574      | 0.715        | 0.130 (0.054)    | 0.330 (0.135)    | 1 (0.574) |     4.10 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           31 |     2597 | 2024-06-06 | Sashi             | W   | 0.573      | 0.715        | 0.151 (0.062)    | 0.926 (0.379)    | 1 (0.573) |     2.99 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           30 |     2609 | 2024-06-06 | The MongolZ       | L   | 0.572      | -            | -                | -                | -         |    -1.22 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           29 |     2637 | 2024-06-05 | Ninjas in Pyjamas | L   | 0.568      | -            | -                | -                | -         |    -9.51 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           28 |     2659 | 2024-06-05 | Astralis          | L   | 0.565      | -            | -                | -                | -         |    -5.85 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           27 |     2791 | 2024-05-31 | Vitality          | L   | 0.535      | -            | -                | -                | -         |    -1.04 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           26 |     2837 | 2024-05-29 | BIG               | W   | 0.523      | -            | -                | -                | 1 (0.523) |     3.93 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           25 |     2849 | 2024-05-29 | Natus Vincere     | W   | 0.521      | 0.624        | 1.000 (0.325)    | 0.473 (0.154)    | 1 (0.521) |    15.75 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           24 |     2869 | 2024-05-28 | M80               | W   | 0.514      | 0.624        | 0.169 (0.054)    | 0.521 (0.167)    | 1 (0.514) |     2.78 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           23 |     2884 | 2024-05-27 | Virtus.pro        | L   | 0.509      | -            | -                | -                | -         |    -5.45 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           22 |     3136 | 2024-05-18 | MOUZ              | L   | 0.447      | -            | -                | -                | -         |    -0.93 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           21 |     3170 | 2024-05-17 | MIBR              | W   | 0.441      | 0.769        | -                | 0.644 (0.218)    | 1 (0.441) |     7.05 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           20 |     3209 | 2024-05-16 | Spirit            | L   | 0.434      | -            | -                | -                | -         |    -0.58 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           19 |     3261 | 2024-05-15 | MIBR              | W   | 0.427      | 0.769        | -                | 0.644 (0.211)    | -         |     6.96 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           18 |     3528 | 2024-05-04 | Ninjas in Pyjamas | L   | 0.354      | -            | -                | -                | -         |    -5.42 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           17 |     3541 | 2024-05-03 | BIG               | L   | 0.348      | -            | -                | -                | -         |    -8.40 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           16 |     3552 | 2024-05-03 | FlyQuest          | W   | 0.346      | -            | -                | -                | -         |     1.24 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           15 |     3571 | 2024-05-02 | Complexity        | L   | 0.340      | -            | -                | -                | -         |    -3.77 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           14 |     3617 | 2024-04-30 | Ninjas in Pyjamas | W   | 0.327      | 0.889        | 0.232 (0.068)    | -                | -         |     5.38 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           13 |     4145 | 2024-04-10 | G2                | L   | 0.193      | -            | -                | -                | -         |    -0.24 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           12 |     4203 | 2024-04-09 | FURIA             | W   | 0.186      | -            | -                | -                | -         |     4.62 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           11 |     4235 | 2024-04-08 | 9z                | W   | 0.179      | -            | -                | -                | -         |     3.51 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           10 |     4246 | 2024-04-07 | Liquid            | L   | 0.178      | -            | -                | -                | -         |    -1.56 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            9 |     4551 | 2024-03-23 | paiN              | L   | 0.075      | -            | -                | -                | -         |    -0.38 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            8 |     4572 | 2024-03-22 | Virtus.pro        | L   | 0.066      | -            | -                | -                | -         |    -0.71 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            7 |     4585 | 2024-03-21 | Complexity        | L   | 0.062      | -            | -                | -                | -         |    -0.66 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            6 |     4592 | 2024-03-21 | FaZe              | W   | 0.060      | -            | -                | -                | -         |     1.67 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            5 |     4642 | 2024-03-18 | Eternal Fire      | W   | 0.040      | -            | -                | -                | -         |     1.19 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            4 |     4661 | 2024-03-17 | Imperial          | W   | 0.035      | -            | -                | -                | -         |     0.14 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            3 |     4670 | 2024-03-17 | Lynn Vision       | W   | 0.034      | -            | -                | -                | -         |     0.07 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            2 |     4774 | 2024-03-13 | Metizport         | W   | 0.007      | -            | -                | -                | -         |     0.01 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            1 |     4798 | 2024-03-12 | Virtus.pro        | L   | 0.002      | -            | -                | -                | -         |    -0.02 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($62,346.38)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-01 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-08-25 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-08-09 |      1.000 | $4,500.00      | $4,500.00       |
| 2024-08-04 |      0.967 | $8,500.00      | $8,220.41       |
| 2024-06-09 |      0.594 | $8,000.00      | $4,751.11       |
| 2024-06-02 |      0.548 | $10,000.00     | $5,480.56       |
| 2024-05-19 |      0.453 | $50,000.00     | $22,666.67      |
| 2024-05-12 |      0.407 | $7,000.00      | $2,850.56       |
| 2024-04-14 |      0.219 | $6,000.00      | $1,315.97       |
| 2024-03-31 |      0.128 | $20,000.00     | $2,561.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
