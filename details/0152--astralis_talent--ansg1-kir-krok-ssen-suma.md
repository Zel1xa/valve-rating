### Roster Details<br />
Team Name: Astralis Talent<br />
Roster: ANSG1, kiR, kroK, sSen, suma<br />
Global Rank: [152](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [100]( ../standings_europe.md)<br />
<br />
Final Rank Value:  709.5<br />
<br />
Final Rank Value (709.5) = Starting Rank Value (785.6) + Head To Head Adjustments (-76.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.319[<sup>1</sup>](#table2)
- Bounty Collected: 0.220[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.208[<sup>2</sup>](#table1)

The average of these factors is 0.188<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 785.6
- 400 + ( ( 0.188 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 785.6


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
|           22 |       47 | 2024-08-02 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |    -6.97 | ANSG1, kiR, kroK, sSen, suma       |
|           21 |      225 | 2024-07-28 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -10.28 | ANSG1, kiR, kroK, sSen, suma       |
|           20 |      278 | 2024-07-26 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -3.61 | ANSG1, kiR, kroK, sSen, suma       |
|           19 |      331 | 2024-07-24 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |    -8.28 | ANSG1, kiR, kroK, sSen, suma       |
|           18 |      403 | 2024-07-22 | GenOne            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.081 (0.012)    | 0 (0.000) |     7.60 | ANSG1, kiR, kroK, sSen, suma       |
|           17 |      558 | 2024-07-18 | GL Academy        | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.104 (0.015)    | 0 (0.000) |    16.18 | ANSG1, kiR, kroK, sSen, suma       |
|           16 |      606 | 2024-07-17 | 9INE              | L   | 1.000      | -            | -                | -                | -         |    -7.74 | ANSG1, kiR, kroK, sSen, suma       |
|           15 |      994 | 2024-06-14 | Revenant          | L   | 0.865      | -            | -                | -                | -         |   -11.09 | alexsomfan, ANSG1, kiR, sSen, suma |
|           14 |     1012 | 2024-06-13 | Aurora Young Blud | L   | 0.860      | -            | -                | -                | -         |    -9.63 | alexsomfan, ANSG1, kiR, sSen, suma |
|           13 |     1050 | 2024-06-12 | Sashi             | L   | 0.853      | -            | -                | -                | -         |    -1.94 | ANSG1, kiR, kroK, sSen, suma       |
|           12 |     1215 | 2024-06-08 | M1X KS            | L   | 0.825      | -            | -                | -                | -         |    -9.43 | ANSG1, kiR, kroK, sSen, suma       |
|           11 |     1254 | 2024-06-07 | Nexus             | L   | 0.819      | -            | -                | -                | -         |   -13.08 | ANSG1, kiR, kroK, sSen, suma       |
|           10 |     1269 | 2024-06-07 | 618 KS            | W   | 0.818      | 0.337        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.818) |     2.92 | ANSG1, kiR, kroK, sSen, suma       |
|            9 |     1318 | 2024-06-06 | Gaimin Gladiators | L   | 0.813      | -            | -                | -                | -         |    -5.82 | ANSG1, kiR, kroK, sSen, suma       |
|            8 |     2541 | 2024-04-21 | MASONIC           | L   | 0.505      | -            | -                | -                | -         |    -8.01 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            7 |     2547 | 2024-04-21 | Preasy            | W   | 0.504      | 0.318        | 0.012 (0.002)    | 0.231 (0.037)    | 1 (0.504) |     8.36 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            6 |     2560 | 2024-04-20 | Kronjyllands      | W   | 0.500      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.500) |     1.77 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            5 |     2763 | 2024-04-15 | ECLOT             | L   | 0.464      | -            | -                | -                | -         |    -1.32 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            4 |     2940 | 2024-04-09 | Alliance          | L   | 0.424      | -            | -                | -                | -         |    -5.25 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            3 |     3260 | 2024-03-25 | Sashi             | L   | 0.327      | -            | -                | -                | -         |    -6.58 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            2 |     3263 | 2024-03-25 | XI                | W   | 0.327      | 0.342        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.90 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            1 |     3599 | 2024-03-09 | NOM               | L   | 0.219      | -            | -                | -                | -         |    -5.74 | ANSG1, JBOEN, kiR, kroK, tOPZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,414.72)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-12 |      0.853 | $360.00        | $307.24         |
| 2024-06-08 |      0.827 | $1,087.00      | $898.91         |
| 2024-04-21 |      0.505 | $1,426.00      | $720.69         |
| 2024-03-25 |      0.327 | $1,490.00      | $487.87         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
