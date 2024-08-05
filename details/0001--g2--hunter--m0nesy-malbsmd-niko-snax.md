### Roster Details<br />
Team Name: G2<br />
Roster: huNter-, m0NESY, malbsMd, NiKo, Snax<br />
Global Rank: [1](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [1]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1964.3<br />
<br />
Final Rank Value (1964.3) = Starting Rank Value (2000.0) + Head To Head Adjustments (-35.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.756[<sup>2</sup>](#table1)
- Opponent Network: 0.366[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.780<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 2000.0
- 400 + ( ( 0.780 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 2000.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           40 |       60 | 2024-08-03 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.544 (0.316)    | 1 (1.000) |     3.42 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      151 | 2024-08-01 | FaZe              | W   | 1.000      | 0.581        | 0.631 (0.367)    | 0.394 (0.229)    | 1 (1.000) |     6.22 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      195 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.544 (0.316)    | 1 (1.000) |     3.28 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      505 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -16.15 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           36 |      550 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.498 (0.498)    | 0.317 (0.317)    | 1 (1.000) |     5.80 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           35 |      617 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.452 (0.452)    | 1 (1.000) |    14.62 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           34 |      717 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.710 (0.710)    | 1 (1.000) |     9.14 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           33 |     1129 | 2024-06-13 | Vitality          | L   | 0.846      | -            | -                | -                | -         |   -16.95 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           32 |     1585 | 2024-06-02 | Vitality          | W   | 0.774      | 0.624        | 0.648 (0.313)    | -                | 1 (0.774) |     9.43 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1607 | 2024-06-01 | 9z                | W   | 0.768      | 0.624        | 0.404 (0.194)    | 0.607 (0.291)    | 1 (0.768) |     1.66 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1644 | 2024-05-31 | FaZe              | W   | 0.761      | 0.624        | 0.631 (0.300)    | -                | 1 (0.761) |     5.74 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     1694 | 2024-05-29 | Liquid            | W   | 0.748      | 0.624        | -                | 0.450 (0.210)    | 1 (0.748) |     3.16 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           28 |     1717 | 2024-05-28 | MOUZ              | W   | 0.742      | 0.624        | 1.000 (0.463)    | -                | -         |    10.21 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           27 |     1741 | 2024-05-27 | Vitality          | L   | 0.735      | -            | -                | -                | -         |   -13.76 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           26 |     1752 | 2024-05-27 | Falcons           | W   | 0.733      | -            | -                | -                | -         |     1.23 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           25 |     2291 | 2024-05-09 | MOUZ              | L   | 0.613      | -            | -                | -                | -         |   -11.92 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2317 | 2024-05-08 | 3DMAX             | W   | 0.606      | 0.889        | 0.508 (0.274)    | 1.000 (0.539)    | -         |     2.54 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2335 | 2024-05-07 | BIG               | W   | 0.599      | -            | -                | -                | -         |     0.50 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2512 | 2024-04-28 | M80               | W   | 0.540      | 0.889        | -                | 0.577 (0.277)    | -         |     0.33 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2547 | 2024-04-27 | Falcons           | W   | 0.532      | -            | -                | -                | -         |     0.77 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2570 | 2024-04-26 | M80               | L   | 0.525      | -            | -                | -                | -         |   -16.26 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2599 | 2024-04-25 | The MongolZ       | L   | 0.518      | -            | -                | -                | -         |    -9.46 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2619 | 2024-04-24 | TYLOO             | W   | 0.512      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     2920 | 2024-04-13 | MOUZ              | L   | 0.437      | -            | -                | -                | -         |    -9.15 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     2933 | 2024-04-12 | Virtus.pro        | W   | 0.431      | -            | -                | -                | -         |     2.26 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     3003 | 2024-04-10 | HEROIC            | W   | 0.418      | -            | -                | -                | -         |     1.21 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3063 | 2024-04-09 | Lynn Vision       | W   | 0.412      | -            | -                | -                | -         |     0.08 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3094 | 2024-04-08 | Liquid            | L   | 0.404      | -            | -                | -                | -         |   -11.48 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3103 | 2024-04-07 | 9z                | W   | 0.403      | -            | -                | -                | -         |     1.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3295 | 2024-03-30 | Natus Vincere     | L   | 0.347      | -            | -                | -                | -         |    -5.82 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3302 | 2024-03-29 | MOUZ              | W   | 0.341      | 1.000        | 1.000 (0.341)    | -                | -         |     3.37 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3399 | 2024-03-24 | Virtus.pro        | W   | 0.306      | -            | -                | -                | -         |     1.58 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     3411 | 2024-03-23 | Gaimin Gladiators | W   | 0.300      | -            | -                | -                | -         |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     3429 | 2024-03-22 | Cloud9            | L   | 0.292      | -            | -                | -                | -         |    -9.15 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     3439 | 2024-03-21 | Natus Vincere     | L   | 0.288      | -            | -                | -                | -         |    -4.84 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     3448 | 2024-03-21 | FURIA             | W   | 0.286      | -            | -                | -                | -         |     1.48 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4268 | 2024-02-15 | FaZe              | W   | 0.052      | -            | -                | -                | -         |     0.24 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4298 | 2024-02-14 | Eternal Fire      | W   | 0.047      | -            | -                | -                | -         |     0.23 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4315 | 2024-02-14 | Into the Breach   | W   | 0.045      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4380 | 2024-02-09 | FaZe              | L   | 0.013      | -            | -                | -                | -         |    -0.35 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($342,010.46)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.866 | $10,000.00     | $8,658.33       |
| 2024-06-02 |      0.774 | $100,000.00    | $77,361.11      |
| 2024-05-12 |      0.633 | $32,000.00     | $20,248.89      |
| 2024-04-14 |      0.445 | $20,000.00     | $8,897.69       |
| 2024-03-31 |      0.354 | $80,000.00     | $28,288.89      |
| 2024-02-11 |      0.026 | $40,000.00     | $1,055.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
