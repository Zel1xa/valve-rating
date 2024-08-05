### Roster Details<br />
Team Name: HEROIC<br />
Roster: kyxsan, NertZ, sAw, sjuush, TeSeS<br />
Global Rank: [12](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1589.5<br />
<br />
Final Rank Value (1589.5) = Starting Rank Value (1593.9) + Head To Head Adjustments (-4.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.613[<sup>1</sup>](#table2)
- Bounty Collected: 0.562[<sup>2</sup>](#table1)
- Opponent Network: 0.272[<sup>2</sup>](#table1)
- LAN Wins: 0.870[<sup>2</sup>](#table1)

The average of these factors is 0.579<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1593.9
- 400 + ( ( 0.579 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1593.9


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
|           47 |       72 | 2024-07-30 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -3.93 | kyxsan, NertZ, sAw, sjuush, TeSeS      |
|           46 |       97 | 2024-07-29 | Complexity        | W   | 1.000      | 0.581        | 0.348 (0.202)    | 0.367 (0.213)    | 1 (1.000) |    15.22 | kyxsan, NertZ, sAw, sjuush, TeSeS      |
|           45 |     1263 | 2024-06-06 | ENCE              | W   | 0.832      | 0.715        | 0.173 (0.103)    | 0.404 (0.240)    | 1 (0.832) |     5.81 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           44 |     1281 | 2024-06-06 | Sashi             | W   | 0.831      | 0.715        | 0.185 (0.110)    | 0.973 (0.578)    | 1 (0.831) |     3.11 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           43 |     1293 | 2024-06-06 | The MongolZ       | L   | 0.830      | -            | -                | -                | -         |    -3.46 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           42 |     1321 | 2024-06-05 | Ninjas in Pyjamas | L   | 0.826      | -            | -                | -                | -         |   -14.76 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           41 |     1343 | 2024-06-05 | Astralis          | L   | 0.823      | -            | -                | -                | -         |    -8.40 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           40 |     1475 | 2024-05-31 | Vitality          | L   | 0.793      | -            | -                | -                | -         |    -4.62 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           39 |     1521 | 2024-05-29 | BIG               | W   | 0.781      | -            | -                | -                | 1 (0.781) |     3.48 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           38 |     1533 | 2024-05-29 | Natus Vincere     | W   | 0.779      | 0.624        | 1.000 (0.486)    | 0.331 (0.161)    | 1 (0.779) |    21.60 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           37 |     1553 | 2024-05-28 | M80               | W   | 0.772      | 0.624        | 0.189 (0.091)    | 0.551 (0.266)    | 1 (0.772) |     3.54 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           36 |     1568 | 2024-05-27 | Virtus.pro        | L   | 0.767      | -            | -                | -                | -         |    -8.30 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           35 |     1820 | 2024-05-18 | MOUZ              | L   | 0.705      | -            | -                | -                | -         |    -2.92 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           34 |     1854 | 2024-05-17 | MIBR              | W   | 0.699      | 0.769        | 0.200 (0.107)    | 0.637 (0.342)    | 1 (0.699) |     7.76 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           33 |     1893 | 2024-05-16 | Spirit            | L   | 0.692      | -            | -                | -                | -         |    -2.78 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           32 |     1945 | 2024-05-15 | MIBR              | W   | 0.685      | 0.769        | 0.200 (0.105)    | 0.637 (0.335)    | 1 (0.685) |     7.57 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           31 |     2212 | 2024-05-04 | Ninjas in Pyjamas | L   | 0.612      | -            | -                | -                | -         |    -9.81 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           30 |     2225 | 2024-05-03 | BIG               | L   | 0.606      | -            | -                | -                | -         |   -16.76 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           29 |     2236 | 2024-05-03 | FlyQuest          | W   | 0.604      | 0.889        | -                | 0.298 (0.160)    | 1 (0.604) |     1.89 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           28 |     2255 | 2024-05-02 | Complexity        | L   | 0.598      | -            | -                | -                | -         |    -8.19 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           27 |     2301 | 2024-04-30 | Ninjas in Pyjamas | W   | 0.585      | 0.889        | 0.256 (0.133)    | 0.477 (0.248)    | 1 (0.585) |     9.09 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           26 |     2829 | 2024-04-10 | G2                | L   | 0.451      | -            | -                | -                | -         |    -1.52 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           25 |     2887 | 2024-04-09 | FURIA             | W   | 0.444      | -            | -                | -                | -         |     9.27 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           24 |     2919 | 2024-04-08 | 9z                | W   | 0.437      | 0.624        | 0.408 (0.111)    | 0.625 (0.170)    | -         |     6.61 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           23 |     2930 | 2024-04-07 | Liquid            | L   | 0.436      | -            | -                | -                | -         |    -9.09 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           22 |     3235 | 2024-03-23 | paiN              | L   | 0.333      | -            | -                | -                | -         |    -7.38 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           21 |     3256 | 2024-03-22 | Virtus.pro        | L   | 0.324      | -            | -                | -                | -         |    -3.31 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           20 |     3269 | 2024-03-21 | Complexity        | L   | 0.319      | -            | -                | -                | -         |    -4.37 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           19 |     3276 | 2024-03-21 | FaZe              | W   | 0.318      | 1.000        | 0.663 (0.211)    | -                | -         |     6.72 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           18 |     3326 | 2024-03-18 | Eternal Fire      | W   | 0.298      | -            | -                | -                | -         |     6.44 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           17 |     3345 | 2024-03-17 | Imperial          | W   | 0.293      | -            | -                | -                | -         |     1.50 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           16 |     3354 | 2024-03-17 | Lynn Vision       | W   | 0.292      | -            | -                | -                | -         |     0.33 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           15 |     3458 | 2024-03-13 | Metizport         | W   | 0.265      | -            | -                | -                | -         |     0.21 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           14 |     3482 | 2024-03-12 | Virtus.pro        | L   | 0.259      | -            | -                | -                | -         |    -2.52 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           13 |     3501 | 2024-03-11 | ENCE              | W   | 0.253      | -            | -                | -                | -         |     2.93 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           12 |     3510 | 2024-03-11 | ex-Preasy         | W   | 0.252      | -            | -                | -                | -         |     0.10 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           11 |     3552 | 2024-03-09 | OG                | L   | 0.238      | -            | -                | -                | -         |    -7.22 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           10 |     3628 | 2024-03-06 | Young Ninjas      | W   | 0.219      | -            | -                | -                | -         |     0.07 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            9 |     3910 | 2024-02-22 | GamerLegion       | W   | 0.132      | -            | -                | -                | -         |     0.05 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            8 |     3931 | 2024-02-21 | Spirit            | L   | 0.126      | -            | -                | -                | -         |    -0.56 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            7 |     3966 | 2024-02-20 | Astralis          | W   | 0.118      | -            | -                | -                | -         |     2.42 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            6 |     3982 | 2024-02-19 | Vitality          | L   | 0.113      | -            | -                | -                | -         |    -0.65 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            5 |     3990 | 2024-02-19 | ex-Preasy         | W   | 0.112      | -            | -                | -                | -         |     0.04 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            4 |     4234 | 2024-02-06 | G2                | L   | 0.026      | -            | -                | -                | -         |    -0.08 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            3 |     4241 | 2024-02-06 | GamerLegion       | W   | 0.024      | -            | -                | -                | -         |     0.01 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            2 |     4249 | 2024-02-05 | Vitality          | W   | 0.018      | -            | -                | -                | -         |     0.46 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            1 |     4301 | 2024-02-03 | G2                | L   | 0.004      | -            | -                | -                | -         |    -0.01 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($77,437.25)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.23) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-09 |      0.852 | $8,000.00      | $6,814.70       |
| 2024-06-02 |      0.806 | $10,000.00     | $8,060.05       |
| 2024-05-19 |      0.711 | $50,000.00     | $35,564.12      |
| 2024-05-12 |      0.665 | $7,000.00      | $4,656.20       |
| 2024-04-14 |      0.477 | $6,000.00      | $2,863.67       |
| 2024-03-31 |      0.386 | $20,000.00     | $7,720.09       |
| 2024-03-10 |      0.246 | $7,500.00      | $1,847.64       |
| 2024-02-11 |      0.059 | $24,000.00     | $1,410.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
