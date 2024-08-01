### Roster Details<br />
Team Name: Astralis Talent<br />
Roster: ANSG1, kiR, kroK, sSen, suma<br />
Global Rank: [150](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [99]( ../standings_europe.md)<br />
<br />
Final Rank Value:  720.1<br />
<br />
Final Rank Value (720.1) = Starting Rank Value (801.5) + Head To Head Adjustments (-81.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.328[<sup>1</sup>](#table2)
- Bounty Collected: 0.228[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.215[<sup>2</sup>](#table1)

The average of these factors is 0.195<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 801.5
- 400 + ( ( 0.195 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 801.5


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
|           24 |      163 | 2024-07-28 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -10.00 | ANSG1, kiR, kroK, sSen, suma       |
|           23 |      216 | 2024-07-26 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -3.42 | ANSG1, kiR, kroK, sSen, suma       |
|           22 |      269 | 2024-07-24 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |    -7.68 | ANSG1, kiR, kroK, sSen, suma       |
|           21 |      342 | 2024-07-22 | GenOne            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.077 (0.011)    | 0 (0.000) |     7.54 | ANSG1, kiR, kroK, sSen, suma       |
|           20 |      364 | 2024-07-21 | K10               | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.133 (0.019)    | 0 (0.000) |    14.85 | ANSG1, kiR, kroK, sSen, suma       |
|           19 |      505 | 2024-07-18 | GL Academy        | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.102 (0.015)    | 0 (0.000) |    16.92 | ANSG1, kiR, kroK, sSen, suma       |
|           18 |      553 | 2024-07-17 | 9INE              | L   | 1.000      | -            | -                | -                | -         |    -6.37 | ANSG1, kiR, kroK, sSen, suma       |
|           17 |      966 | 2024-06-14 | Revenant          | L   | 0.880      | -            | -                | -                | -         |   -10.60 | alexsomfan, ANSG1, kiR, sSen, suma |
|           16 |      984 | 2024-06-13 | Aurora Young Blud | L   | 0.875      | -            | -                | -                | -         |    -7.92 | alexsomfan, ANSG1, kiR, sSen, suma |
|           15 |     1024 | 2024-06-12 | Sashi             | L   | 0.868      | -            | -                | -                | -         |    -1.81 | ANSG1, kiR, kroK, sSen, suma       |
|           14 |     1042 | 2024-06-11 | Sampi             | L   | 0.861      | -            | -                | -                | -         |    -8.53 | ANSG1, kiR, kroK, sSen, suma       |
|           13 |     1202 | 2024-06-08 | M1X KS            | L   | 0.839      | -            | -                | -                | -         |    -9.00 | ANSG1, kiR, kroK, sSen, suma       |
|           12 |     1205 | 2024-06-08 | GhoulsW           | L   | 0.839      | -            | -                | -                | -         |   -20.79 | ANSG1, kiR, kroK, sSen, suma       |
|           11 |     1247 | 2024-06-07 | Nexus             | L   | 0.834      | -            | -                | -                | -         |   -13.69 | ANSG1, kiR, kroK, sSen, suma       |
|           10 |     1262 | 2024-06-07 | 618 KS            | W   | 0.833      | 0.337        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.833) |     2.79 | ANSG1, kiR, kroK, sSen, suma       |
|            9 |     1313 | 2024-06-06 | Gaimin Gladiators | L   | 0.828      | -            | -                | -                | -         |    -5.96 | ANSG1, kiR, kroK, sSen, suma       |
|            8 |     2593 | 2024-04-21 | MASONIC           | L   | 0.520      | -            | -                | -                | -         |    -8.34 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            7 |     2599 | 2024-04-21 | Preasy            | W   | 0.519      | 0.318        | 0.012 (0.002)    | 0.222 (0.037)    | 1 (0.519) |     8.35 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            6 |     2614 | 2024-04-20 | Kronjyllands      | W   | 0.515      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.515) |     1.70 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            5 |     2821 | 2024-04-15 | ECLOT             | L   | 0.479      | -            | -                | -                | -         |    -2.37 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            4 |     2999 | 2024-04-09 | Alliance          | L   | 0.439      | -            | -                | -                | -         |    -5.67 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            3 |     3335 | 2024-03-25 | Sashi             | L   | 0.342      | -            | -                | -                | -         |    -7.02 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            2 |     3338 | 2024-03-25 | XI                | W   | 0.341      | 0.342        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.86 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            1 |     3685 | 2024-03-09 | NOM               | L   | 0.233      | -            | -                | -                | -         |    -6.20 | ANSG1, JBOEN, kiR, kroK, tOPZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,955.73)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.875 | $545.00        | $476.98         |
| 2024-06-12 |      0.868 | $360.00        | $312.53         |
| 2024-06-08 |      0.842 | $1,087.00      | $914.87         |
| 2024-04-21 |      0.520 | $1,426.00      | $741.62         |
| 2024-03-25 |      0.342 | $1,490.00      | $509.74         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
