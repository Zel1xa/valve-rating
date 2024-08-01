### Roster Details<br />
Team Name: GamerLegion<br />
Roster: acoR, isak, Keoz, Snax, volt<br />
Global Rank: [119](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [86]( ../standings_europe.md)<br />
<br />
Final Rank Value:  814.4<br />
<br />
Final Rank Value (814.4) = Starting Rank Value (791.0) + Head To Head Adjustments (23.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.357[<sup>1</sup>](#table2)
- Bounty Collected: 0.270[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.126[<sup>2</sup>](#table1)

The average of these factors is 0.190<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 791.0
- 400 + ( ( 0.190 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 791.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     3418 | 2024-03-20 | Imperial        | L   | 0.307      | -            | -                | -                | -         |    -0.68 | acoR, isak, Keoz, Snax, volt |
|           16 |     3436 | 2024-03-19 | Eternal Fire    | L   | 0.300      | -            | -                | -                | -         |    -0.06 | acoR, isak, Keoz, Snax, volt |
|           15 |     3445 | 2024-03-18 | Legacy          | W   | 0.294      | 0.143        | 0.119 (0.005)    | 0.562 (0.024)    | 1 (0.294) |     7.22 | acoR, isak, Keoz, Snax, volt |
|           14 |     3454 | 2024-03-17 | SAW             | L   | 0.289      | -            | -                | -                | -         |    -0.93 | acoR, isak, Keoz, Snax, volt |
|           13 |     3470 | 2024-03-17 | AMKAL           | W   | 0.288      | 0.143        | 0.132 (0.005)    | 0.482 (0.020)    | 1 (0.288) |     7.89 | acoR, isak, Keoz, Snax, volt |
|           12 |     3696 | 2024-03-08 | BIG             | L   | 0.228      | -            | -                | -                | -         |    -0.59 | acoR, isak, Keoz, Snax, volt |
|           11 |     4012 | 2024-02-24 | 9 Pandas        | L   | 0.141      | -            | -                | -                | -         |    -1.06 | acoR, isak, Keoz, Snax, volt |
|           10 |     4019 | 2024-02-24 | ex-Guild Eagles | W   | 0.140      | 0.143        | 0.007 (0.000)    | 0.225 (0.004)    | 1 (0.140) |     2.38 | acoR, isak, Keoz, Snax, volt |
|            9 |     4028 | 2024-02-23 | fnatic          | W   | 0.134      | 0.143        | 0.292 (0.006)    | 0.529 (0.010)    | 1 (0.134) |     4.07 | acoR, isak, Keoz, Snax, volt |
|            8 |     4048 | 2024-02-22 | HEROIC          | L   | 0.128      | -            | -                | -                | -         |    -0.05 | acoR, isak, Keoz, Snax, volt |
|            7 |     4076 | 2024-02-21 | OG              | W   | 0.121      | 0.143        | 0.143 (0.002)    | 0.132 (0.002)    | 1 (0.121) |     2.88 | acoR, isak, Keoz, Snax, volt |
|            6 |     4107 | 2024-02-20 | ENCE            | L   | 0.113      | -            | -                | -                | -         |    -0.07 | acoR, isak, Keoz, Snax, volt |
|            5 |     4128 | 2024-02-19 | PERA            | W   | 0.108      | 0.143        | 0.048 (0.001)    | 0.452 (0.007)    | 1 (0.108) |     2.33 | acoR, isak, Keoz, Snax, volt |
|            4 |     4137 | 2024-02-19 | Vitality        | L   | 0.106      | -            | -                | -                | -         |    -0.01 | acoR, isak, Keoz, Snax, volt |
|            3 |     4390 | 2024-02-06 | HEROIC          | L   | 0.020      | -            | -                | -                | -         |    -0.01 | acoR, isak, Keoz, Snax, volt |
|            2 |     4396 | 2024-02-05 | MOUZ            | L   | 0.014      | -            | -                | -                | -         |    -0.00 | acoR, isak, Keoz, Snax, volt |
|            1 |     4421 | 2024-02-04 | Monte           | W   | 0.007      | 1.000        | 0.062 (0.000)    | 0.168 (0.001)    | 1 (0.007) |     0.17 | acoR, isak, Keoz, Snax, volt |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,163.13)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-20 |      0.308 | $10,000.00     | $3,081.94       |
| 2024-03-10 |      0.242 | $5,000.00      | $1,210.07       |
| 2024-02-11 |      0.054 | $16,000.00     | $871.11         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
