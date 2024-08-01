### Roster Details<br />
Team Name: HEROIC<br />
Roster: kyxsan, NertZ, sAw, sjuush, TeSeS<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1566.0<br />
<br />
Final Rank Value (1566.0) = Starting Rank Value (1576.3) + Head To Head Adjustments (-10.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.595[<sup>1</sup>](#table2)
- Bounty Collected: 0.554[<sup>2</sup>](#table1)
- Opponent Network: 0.271[<sup>2</sup>](#table1)
- LAN Wins: 0.867[<sup>2</sup>](#table1)

The average of these factors is 0.572<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1576.3
- 400 + ( ( 0.572 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1576.3


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
|           46 |      107 | 2024-07-30 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -3.67 | kyxsan, NertZ, sAw, sjuush, TeSeS      |
|           45 |      131 | 2024-07-29 | Complexity        | W   | 1.000      | 0.581        | 0.318 (0.185)    | 0.366 (0.213)    | 1 (1.000) |    15.51 | kyxsan, NertZ, sAw, sjuush, TeSeS      |
|           44 |     1317 | 2024-06-06 | ENCE              | W   | 0.826      | 0.715        | 0.173 (0.102)    | 0.403 (0.238)    | 1 (0.826) |     5.86 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           43 |     1336 | 2024-06-06 | Sashi             | W   | 0.825      | 0.715        | 0.186 (0.110)    | 0.970 (0.572)    | 1 (0.825) |     3.36 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           42 |     1348 | 2024-06-06 | The MongolZ       | L   | 0.824      | -            | -                | -                | -         |    -3.13 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           41 |     1378 | 2024-06-05 | Ninjas in Pyjamas | L   | 0.820      | -            | -                | -                | -         |   -16.72 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           40 |     1400 | 2024-06-05 | Astralis          | L   | 0.817      | -            | -                | -                | -         |    -8.08 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           39 |     1533 | 2024-05-31 | Vitality          | L   | 0.787      | -            | -                | -                | -         |    -4.48 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           38 |     1579 | 2024-05-29 | BIG               | W   | 0.775      | -            | -                | -                | 1 (0.775) |     3.59 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           37 |     1591 | 2024-05-29 | Natus Vincere     | W   | 0.773      | 0.624        | 1.000 (0.483)    | 0.331 (0.160)    | 1 (0.773) |    21.68 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           36 |     1611 | 2024-05-28 | M80               | W   | 0.766      | 0.624        | 0.190 (0.091)    | 0.641 (0.307)    | 1 (0.766) |     3.99 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           35 |     1626 | 2024-05-27 | Virtus.pro        | L   | 0.761      | -            | -                | -                | -         |    -8.17 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           34 |     1905 | 2024-05-18 | MOUZ              | L   | 0.699      | -            | -                | -                | -         |    -2.68 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           33 |     1940 | 2024-05-17 | MIBR              | W   | 0.693      | 0.769        | 0.201 (0.107)    | 0.637 (0.339)    | 1 (0.693) |     7.83 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           32 |     1979 | 2024-05-16 | Spirit            | L   | 0.686      | -            | -                | -                | -         |    -2.55 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           31 |     2035 | 2024-05-15 | MIBR              | W   | 0.679      | 0.769        | 0.201 (0.105)    | 0.637 (0.332)    | 1 (0.679) |     7.64 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           30 |     2309 | 2024-05-04 | Ninjas in Pyjamas | L   | 0.606      | -            | -                | -                | -         |   -11.51 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           29 |     2322 | 2024-05-03 | BIG               | L   | 0.600      | -            | -                | -                | -         |   -16.50 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           28 |     2333 | 2024-05-03 | FlyQuest          | W   | 0.598      | 0.889        | -                | 0.322 (0.171)    | 1 (0.598) |     2.03 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           27 |     2353 | 2024-05-02 | Complexity        | L   | 0.592      | -            | -                | -                | -         |    -7.91 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           26 |     2401 | 2024-04-30 | Ninjas in Pyjamas | W   | 0.579      | 0.889        | 0.207 (0.107)    | 0.447 (0.230)    | 1 (0.579) |     7.20 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           25 |     2940 | 2024-04-10 | G2                | L   | 0.445      | -            | -                | -                | -         |    -1.35 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           24 |     2999 | 2024-04-09 | FURIA             | W   | 0.438      | 0.624        | 0.286 (0.078)    | -                | -         |     9.39 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           23 |     3030 | 2024-04-08 | 9z                | W   | 0.431      | 0.624        | -                | 0.553 (0.149)    | -         |     1.29 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           22 |     3041 | 2024-04-07 | Liquid            | L   | 0.430      | -            | -                | -                | -         |    -7.82 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           21 |     3359 | 2024-03-23 | paiN              | L   | 0.327      | -            | -                | -                | -         |    -7.80 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           20 |     3380 | 2024-03-22 | Virtus.pro        | L   | 0.318      | -            | -                | -                | -         |    -3.27 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           19 |     3393 | 2024-03-21 | Complexity        | L   | 0.313      | -            | -                | -                | -         |    -4.27 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           18 |     3400 | 2024-03-21 | FaZe              | W   | 0.312      | 1.000        | 0.637 (0.199)    | -                | -         |     6.69 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           17 |     3450 | 2024-03-18 | Eternal Fire      | W   | 0.292      | -            | -                | -                | -         |     6.41 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           16 |     3469 | 2024-03-17 | Imperial          | W   | 0.287      | -            | -                | -                | -         |     1.49 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           15 |     3478 | 2024-03-17 | Lynn Vision       | W   | 0.286      | -            | -                | -                | -         |     0.34 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           14 |     3586 | 2024-03-13 | Metizport         | W   | 0.259      | -            | -                | -                | -         |     0.22 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           13 |     3611 | 2024-03-12 | Virtus.pro        | L   | 0.253      | -            | -                | -                | -         |    -2.47 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           12 |     3630 | 2024-03-11 | ENCE              | W   | 0.247      | -            | -                | -                | -         |     2.94 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           11 |     3639 | 2024-03-11 | ex-Preasy         | W   | 0.246      | -            | -                | -                | -         |     0.11 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           10 |     3682 | 2024-03-09 | OG                | L   | 0.232      | -            | -                | -                | -         |    -7.04 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            9 |     3758 | 2024-03-06 | Young Ninjas      | W   | 0.213      | -            | -                | -                | -         |     0.07 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            8 |     4054 | 2024-02-22 | GamerLegion       | W   | 0.126      | -            | -                | -                | -         |     0.05 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            7 |     4076 | 2024-02-21 | Spirit            | L   | 0.120      | -            | -                | -                | -         |    -0.51 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            6 |     4111 | 2024-02-20 | Astralis          | W   | 0.112      | -            | -                | -                | -         |     2.29 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            5 |     4127 | 2024-02-19 | Vitality          | L   | 0.107      | -            | -                | -                | -         |    -0.62 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            4 |     4135 | 2024-02-19 | ex-Preasy         | W   | 0.106      | -            | -                | -                | -         |     0.04 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            3 |     4389 | 2024-02-06 | G2                | L   | 0.020      | -            | -                | -                | -         |    -0.05 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            2 |     4396 | 2024-02-06 | GamerLegion       | W   | 0.018      | -            | -                | -                | -         |     0.01 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            1 |     4404 | 2024-02-05 | Vitality          | W   | 0.012      | -            | -                | -                | -         |     0.30 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($68,141.63)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.846 | $8,000.00      | $6,766.67       |
| 2024-06-02 |      0.800 | $10,000.00     | $8,000.00       |
| 2024-05-19 |      0.705 | $50,000.00     | $35,263.89      |
| 2024-05-12 |      0.659 | $7,000.00      | $4,614.17       |
| 2024-04-14 |      0.471 | $6,000.00      | $2,827.64       |
| 2024-03-31 |      0.380 | $20,000.00     | $7,600.00       |
| 2024-03-10 |      0.240 | $7,500.00      | $1,802.60       |
| 2024-02-11 |      0.053 | $24,000.00     | $1,266.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
