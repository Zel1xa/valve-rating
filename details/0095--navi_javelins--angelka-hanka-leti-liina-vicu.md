### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Global Rank: [95](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [68]( ../standings_europe.md)<br />
<br />
Final Rank Value:  872.0<br />
<br />
Final Rank Value (872.0) = Starting Rank Value (826.7) + Head To Head Adjustments (45.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.091[<sup>2</sup>](#table1)

The average of these factors is 0.207<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 826.7
- 400 + ( ( 0.207 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 826.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |     1487 | 2024-06-01 | panelinha         | L   | 0.795      | -            | -                | -                | -         |   -12.77 | Angelka, Hanka, LETi, Liina, vicu |
|           21 |     1518 | 2024-05-31 | TSM Shimmer       | W   | 0.790      | 0.524        | 0.021 (0.009)    | 0.200 (0.083)    | 1 (0.790) |     7.42 | Angelka, Hanka, LETi, Liina, vicu |
|           20 |     1526 | 2024-05-31 | Let Her Cook      | L   | 0.788      | -            | -                | -                | -         |   -11.60 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |     1869 | 2024-05-19 | Imperial fe       | W   | 0.707      | 0.281        | 0.130 (0.026)    | 0.270 (0.054)    | 0 (0.000) |    16.22 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     1876 | 2024-05-19 | BIG EQUIPA        | W   | 0.706      | 0.281        | 0.018 (0.004)    | 0.156 (0.031)    | 0 (0.000) |     8.76 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     1904 | 2024-05-18 | Spirit fe         | W   | 0.700      | 0.281        | 0.005 (0.001)    | 0.101 (0.020)    | 0 (0.000) |     4.88 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     2660 | 2024-04-19 | Crescent fe       | W   | 0.508      | 0.331        | 0.005 (0.001)    | 0.079 (0.013)    | 0 (0.000) |     3.80 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     2790 | 2024-04-16 | Imperial fe       | W   | 0.488      | 0.303        | 0.130 (0.019)    | 0.270 (0.040)    | 0 (0.000) |    11.74 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     2813 | 2024-04-15 | NIP Impact        | W   | 0.481      | 0.303        | 0.005 (0.001)    | 0.190 (0.028)    | 0 (0.000) |     5.39 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     2830 | 2024-04-14 | Astralis W        | W   | 0.474      | -            | -                | -                | 0 (0.000) |     3.37 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     2844 | 2024-04-13 | Imperial fe       | L   | 0.467      | -            | -                | -                | -         |    -3.37 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     2860 | 2024-04-12 | Let Her Cook      | W   | 0.460      | 0.303        | 0.061 (0.009)    | 0.147 (0.020)    | 0 (0.000) |     8.69 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     2886 | 2024-04-11 | Spirit fe         | W   | 0.454      | 0.303        | 0.005 (0.001)    | 0.101 (0.014)    | 0 (0.000) |     3.90 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     2986 | 2024-04-09 | NIP Impact        | L   | 0.441      | -            | -                | -                | -         |    -9.02 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     3112 | 2024-04-04 | Spirit fe         | W   | 0.408      | 0.331        | 0.005 (0.001)    | 0.101 (0.014)    | -         |     3.59 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3154 | 2024-04-03 | Let Her Cook      | L   | 0.402      | -            | -                | -                | -         |    -4.64 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3539 | 2024-03-14 | 1WIN Gang         | W   | 0.268      | -            | -                | -                | -         |     2.29 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     3748 | 2024-03-06 | Fearless Cheetahs | W   | 0.215      | -            | -                | -                | -         |     2.07 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     3977 | 2024-02-25 | BIG EQUIPA        | W   | 0.147      | -            | -                | -                | -         |     1.99 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     3982 | 2024-02-25 | ENCE Athena       | W   | 0.146      | -            | -                | -                | -         |     1.22 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     4013 | 2024-02-24 | Crescent fe       | W   | 0.140      | -            | -                | -                | -         |     1.29 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     4410 | 2024-02-04 | EK Violet         | W   | 0.008      | -            | -                | -                | -         |     0.03 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,839.41)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.802 | $7,000.00      | $5,617.50       |
| 2024-05-19 |      0.707 | $2,000.00      | $1,414.63       |
| 2024-04-16 |      0.488 | $3,500.00      | $1,708.19       |
| 2024-02-25 |      0.147 | $630.00        | $92.84          |
| 2024-02-04 |      0.008 | $750.00        | $6.25           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
