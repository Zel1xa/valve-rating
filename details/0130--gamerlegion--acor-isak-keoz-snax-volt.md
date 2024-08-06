### Roster Details<br />
Team Name: GamerLegion<br />
Roster: acoR, isak, Keoz, Snax, volt<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [90]( ../standings_europe.md)<br />
<br />
Final Rank Value:  786.9<br />
<br />
Final Rank Value (786.9) = Starting Rank Value (767.0) + Head To Head Adjustments (19.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.265[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.102[<sup>2</sup>](#table1)

The average of these factors is 0.179<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 767.0
- 400 + ( ( 0.179 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 767.0


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
|           14 |     3481 | 2024-03-20 | Imperial        | L   | 0.274      | -            | -                | -                | -         |    -0.58 | acoR, isak, Keoz, Snax, volt |
|           13 |     3499 | 2024-03-19 | Eternal Fire    | L   | 0.267      | -            | -                | -                | -         |    -0.05 | acoR, isak, Keoz, Snax, volt |
|           12 |     3508 | 2024-03-18 | Legacy          | W   | 0.261      | 0.143        | 0.122 (0.005)    | 0.634 (0.024)    | 1 (0.261) |     6.51 | acoR, isak, Keoz, Snax, volt |
|           11 |     3517 | 2024-03-17 | SAW             | L   | 0.257      | -            | -                | -                | -         |    -0.80 | acoR, isak, Keoz, Snax, volt |
|           10 |     3533 | 2024-03-17 | AMKAL           | W   | 0.255      | 0.143        | 0.130 (0.005)    | 0.463 (0.017)    | 1 (0.255) |     7.09 | acoR, isak, Keoz, Snax, volt |
|            9 |     3753 | 2024-03-08 | BIG             | L   | 0.195      | -            | -                | -                | -         |    -0.30 | acoR, isak, Keoz, Snax, volt |
|            8 |     4058 | 2024-02-24 | 9 Pandas        | L   | 0.108      | -            | -                | -                | -         |    -0.75 | acoR, isak, Keoz, Snax, volt |
|            7 |     4065 | 2024-02-24 | ex-Guild Eagles | W   | 0.107      | 0.143        | 0.007 (0.000)    | 0.212 (0.003)    | 1 (0.107) |     1.87 | acoR, isak, Keoz, Snax, volt |
|            6 |     4073 | 2024-02-23 | fnatic          | W   | 0.101      | 0.143        | 0.371 (0.005)    | 0.695 (0.010)    | 1 (0.101) |     3.16 | acoR, isak, Keoz, Snax, volt |
|            5 |     4091 | 2024-02-22 | HEROIC          | L   | 0.095      | -            | -                | -                | -         |    -0.04 | acoR, isak, Keoz, Snax, volt |
|            4 |     4117 | 2024-02-21 | OG              | W   | 0.088      | 0.143        | 0.137 (0.002)    | 0.123 (0.002)    | 1 (0.088) |     2.15 | acoR, isak, Keoz, Snax, volt |
|            3 |     4149 | 2024-02-20 | ENCE            | L   | 0.081      | -            | -                | -                | -         |    -0.05 | acoR, isak, Keoz, Snax, volt |
|            2 |     4170 | 2024-02-19 | PERA            | W   | 0.075      | 0.143        | 0.048 (0.001)    | 0.445 (0.005)    | 1 (0.075) |     1.69 | acoR, isak, Keoz, Snax, volt |
|            1 |     4179 | 2024-02-19 | Vitality        | L   | 0.074      | -            | -                | -                | -         |    -0.01 | acoR, isak, Keoz, Snax, volt |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,800.35)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-20 |      0.275 | $10,000.00     | $2,754.17       |
| 2024-03-10 |      0.209 | $5,000.00      | $1,046.18       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
