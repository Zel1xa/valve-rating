### Roster Details<br />
Team Name: Astralis Talent<br />
Roster: ANSG1, kiR, kroK, sSen, suma<br />
Global Rank: [153](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [100]( ../standings_europe.md)<br />
<br />
Final Rank Value:  709.7<br />
<br />
Final Rank Value (709.7) = Starting Rank Value (786.4) + Head To Head Adjustments (-76.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.327[<sup>1</sup>](#table2)
- Bounty Collected: 0.215[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.204[<sup>2</sup>](#table1)

The average of these factors is 0.188<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 786.4
- 400 + ( ( 0.188 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 786.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |      133 | 2024-08-02 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |    -6.66 | ANSG1, kiR, kroK, sSen, suma       |
|           22 |      327 | 2024-07-28 | GUN5              | L   | 1.000      | -            | -                | -                | -         |    -9.77 | ANSG1, kiR, kroK, sSen, suma       |
|           21 |      380 | 2024-07-26 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -3.18 | ANSG1, kiR, kroK, sSen, suma       |
|           20 |      433 | 2024-07-24 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |    -6.70 | ANSG1, kiR, kroK, sSen, suma       |
|           19 |      505 | 2024-07-22 | GenOne            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.077 (0.011)    | 0 (0.000) |     7.70 | ANSG1, kiR, kroK, sSen, suma       |
|           18 |      660 | 2024-07-18 | GL Academy        | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.095 (0.014)    | 0 (0.000) |    16.29 | ANSG1, kiR, kroK, sSen, suma       |
|           17 |      708 | 2024-07-17 | 9INE              | L   | 1.000      | -            | -                | -                | -         |    -7.55 | ANSG1, kiR, kroK, sSen, suma       |
|           16 |     1124 | 2024-06-14 | Revenant          | L   | 0.846      | -            | -                | -                | -         |   -10.53 | alexsomfan, ANSG1, kiR, sSen, suma |
|           15 |     1142 | 2024-06-13 | Aurora Young Blud | L   | 0.841      | -            | -                | -                | -         |    -7.20 | alexsomfan, ANSG1, kiR, sSen, suma |
|           14 |     1182 | 2024-06-12 | Sashi             | L   | 0.834      | -            | -                | -                | -         |    -1.82 | ANSG1, kiR, kroK, sSen, suma       |
|           13 |     1199 | 2024-06-11 | Sampi             | L   | 0.827      | -            | -                | -                | -         |    -8.09 | ANSG1, kiR, kroK, sSen, suma       |
|           12 |     1355 | 2024-06-08 | M1X KS            | L   | 0.805      | -            | -                | -                | -         |    -9.23 | ANSG1, kiR, kroK, sSen, suma       |
|           11 |     1394 | 2024-06-07 | Nexus             | L   | 0.800      | -            | -                | -                | -         |   -12.66 | ANSG1, kiR, kroK, sSen, suma       |
|           10 |     1409 | 2024-06-07 | 618 KS            | W   | 0.799      | 0.337        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.799) |     2.83 | ANSG1, kiR, kroK, sSen, suma       |
|            9 |     1458 | 2024-06-06 | Gaimin Gladiators | L   | 0.794      | -            | -                | -                | -         |    -5.79 | ANSG1, kiR, kroK, sSen, suma       |
|            8 |     2688 | 2024-04-21 | MASONIC           | L   | 0.486      | -            | -                | -                | -         |    -7.75 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            7 |     2694 | 2024-04-21 | Preasy            | W   | 0.485      | 0.318        | 0.008 (0.001)    | 0.216 (0.033)    | 1 (0.485) |     7.82 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            6 |     2707 | 2024-04-20 | Kronjyllands      | W   | 0.481      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.481) |     1.69 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            5 |     2910 | 2024-04-15 | ECLOT             | L   | 0.445      | -            | -                | -                | -         |    -1.26 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            4 |     3087 | 2024-04-09 | Alliance          | L   | 0.405      | -            | -                | -                | -         |    -5.07 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            3 |     3410 | 2024-03-25 | Sashi             | L   | 0.308      | -            | -                | -                | -         |    -6.21 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            2 |     3413 | 2024-03-25 | XI                | W   | 0.307      | 0.342        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.78 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            1 |     3754 | 2024-03-09 | NOM               | L   | 0.199      | -            | -                | -                | -         |    -5.23 | ANSG1, JBOEN, kiR, kroK, tOPZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,788.94)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.841 | $545.00        | $458.46         |
| 2024-06-12 |      0.834 | $360.00        | $300.29         |
| 2024-06-08 |      0.808 | $1,087.00      | $877.93         |
| 2024-04-21 |      0.486 | $1,426.00      | $693.16         |
| 2024-03-25 |      0.308 | $1,490.00      | $459.11         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
