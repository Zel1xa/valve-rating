### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Global Rank: [94](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  871.2<br />
<br />
Final Rank Value (871.2) = Starting Rank Value (826.1) + Head To Head Adjustments (45.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.091[<sup>2</sup>](#table1)

The average of these factors is 0.207<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 826.1
- 400 + ( ( 0.207 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 826.1


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
|           22 |     1493 | 2024-06-01 | panelinha         | L   | 0.794      | -            | -                | -                | -         |   -12.74 | Angelka, Hanka, LETi, Liina, vicu |
|           21 |     1524 | 2024-05-31 | TSM Shimmer       | W   | 0.788      | 0.524        | 0.021 (0.009)    | 0.200 (0.083)    | 1 (0.788) |     7.42 | Angelka, Hanka, LETi, Liina, vicu |
|           20 |     1532 | 2024-05-31 | Let Her Cook      | L   | 0.787      | -            | -                | -                | -         |   -11.57 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |     1875 | 2024-05-19 | Imperial fe       | W   | 0.706      | 0.281        | 0.130 (0.026)    | 0.269 (0.053)    | 0 (0.000) |    16.18 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     1882 | 2024-05-19 | BIG EQUIPA        | W   | 0.705      | 0.281        | 0.018 (0.003)    | 0.155 (0.031)    | 0 (0.000) |     8.74 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     1910 | 2024-05-18 | Spirit fe         | W   | 0.699      | 0.281        | 0.005 (0.001)    | 0.101 (0.020)    | 0 (0.000) |     4.88 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     2666 | 2024-04-19 | Crescent fe       | W   | 0.507      | 0.331        | 0.005 (0.001)    | 0.079 (0.013)    | 0 (0.000) |     3.79 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     2796 | 2024-04-16 | Imperial fe       | W   | 0.486      | 0.303        | 0.130 (0.019)    | 0.269 (0.040)    | 0 (0.000) |    11.70 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     2819 | 2024-04-15 | NIP Impact        | W   | 0.480      | 0.303        | 0.005 (0.001)    | 0.190 (0.028)    | 0 (0.000) |     5.38 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     2836 | 2024-04-14 | Astralis W        | W   | 0.472      | -            | -                | -                | 0 (0.000) |     3.37 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     2850 | 2024-04-13 | Imperial fe       | L   | 0.466      | -            | -                | -                | -         |    -3.36 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     2866 | 2024-04-12 | Let Her Cook      | W   | 0.459      | 0.303        | 0.061 (0.009)    | 0.146 (0.020)    | 0 (0.000) |     8.66 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     2892 | 2024-04-11 | Spirit fe         | W   | 0.452      | 0.303        | 0.005 (0.001)    | 0.101 (0.014)    | 0 (0.000) |     3.89 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     2992 | 2024-04-09 | NIP Impact        | L   | 0.439      | -            | -                | -                | -         |    -8.98 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     3118 | 2024-04-04 | Spirit fe         | W   | 0.407      | 0.331        | 0.005 (0.001)    | 0.101 (0.014)    | -         |     3.58 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3160 | 2024-04-03 | Let Her Cook      | L   | 0.400      | -            | -                | -                | -         |    -4.63 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3545 | 2024-03-14 | 1WIN Gang         | W   | 0.267      | -            | -                | -                | -         |     2.28 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     3754 | 2024-03-06 | Fearless Cheetahs | W   | 0.213      | -            | -                | -                | -         |     2.06 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     3983 | 2024-02-25 | BIG EQUIPA        | W   | 0.146      | -            | -                | -                | -         |     1.96 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     3988 | 2024-02-25 | ENCE Athena       | W   | 0.145      | -            | -                | -                | -         |     1.20 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     4019 | 2024-02-24 | Crescent fe       | W   | 0.139      | -            | -                | -                | -         |     1.28 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     4416 | 2024-02-04 | EK Violet         | W   | 0.007      | -            | -                | -                | -         |     0.03 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,816.28)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.801 | $7,000.00      | $5,605.83       |
| 2024-05-19 |      0.706 | $2,000.00      | $1,411.30       |
| 2024-04-16 |      0.486 | $3,500.00      | $1,702.36       |
| 2024-02-25 |      0.146 | $630.00        | $91.79          |
| 2024-02-04 |      0.007 | $750.00        | $5.00           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
