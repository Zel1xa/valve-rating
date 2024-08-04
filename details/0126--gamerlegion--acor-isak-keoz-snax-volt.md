### Roster Details<br />
Team Name: GamerLegion<br />
Roster: acoR, isak, Keoz, Snax, volt<br />
Global Rank: [126](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [87]( ../standings_europe.md)<br />
<br />
Final Rank Value:  793.1<br />
<br />
Final Rank Value (793.1) = Starting Rank Value (771.8) + Head To Head Adjustments (21.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.268[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.109[<sup>2</sup>](#table1)

The average of these factors is 0.182<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 771.8
- 400 + ( ( 0.182 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 771.8


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
|           14 |     3449 | 2024-03-20 | Imperial        | L   | 0.286      | -            | -                | -                | -         |    -0.61 | acoR, isak, Keoz, Snax, volt |
|           13 |     3467 | 2024-03-19 | Eternal Fire    | L   | 0.279      | -            | -                | -                | -         |    -0.06 | acoR, isak, Keoz, Snax, volt |
|           12 |     3476 | 2024-03-18 | Legacy          | W   | 0.272      | 0.143        | 0.122 (0.005)    | 0.643 (0.025)    | 1 (0.272) |     6.79 | acoR, isak, Keoz, Snax, volt |
|           11 |     3485 | 2024-03-17 | SAW             | L   | 0.268      | -            | -                | -                | -         |    -0.84 | acoR, isak, Keoz, Snax, volt |
|           10 |     3501 | 2024-03-17 | AMKAL           | W   | 0.266      | 0.143        | 0.130 (0.005)    | 0.475 (0.018)    | 1 (0.266) |     7.39 | acoR, isak, Keoz, Snax, volt |
|            9 |     3721 | 2024-03-08 | BIG             | L   | 0.207      | -            | -                | -                | -         |    -0.33 | acoR, isak, Keoz, Snax, volt |
|            8 |     4026 | 2024-02-24 | 9 Pandas        | L   | 0.119      | -            | -                | -                | -         |    -0.84 | acoR, isak, Keoz, Snax, volt |
|            7 |     4033 | 2024-02-24 | ex-Guild Eagles | W   | 0.118      | 0.143        | 0.007 (0.000)    | 0.219 (0.004)    | 1 (0.118) |     2.06 | acoR, isak, Keoz, Snax, volt |
|            6 |     4041 | 2024-02-23 | fnatic          | W   | 0.113      | 0.143        | 0.371 (0.006)    | 0.708 (0.011)    | 1 (0.113) |     3.52 | acoR, isak, Keoz, Snax, volt |
|            5 |     4059 | 2024-02-22 | HEROIC          | L   | 0.107      | -            | -                | -                | -         |    -0.04 | acoR, isak, Keoz, Snax, volt |
|            4 |     4085 | 2024-02-21 | OG              | W   | 0.099      | 0.143        | 0.139 (0.002)    | 0.127 (0.002)    | 1 (0.099) |     2.43 | acoR, isak, Keoz, Snax, volt |
|            3 |     4117 | 2024-02-20 | ENCE            | L   | 0.092      | -            | -                | -                | -         |    -0.06 | acoR, isak, Keoz, Snax, volt |
|            2 |     4138 | 2024-02-19 | PERA            | W   | 0.087      | 0.143        | 0.048 (0.001)    | 0.453 (0.006)    | 1 (0.087) |     1.93 | acoR, isak, Keoz, Snax, volt |
|            1 |     4147 | 2024-02-19 | Vitality        | L   | 0.085      | -            | -                | -                | -         |    -0.01 | acoR, isak, Keoz, Snax, volt |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,973.61)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-20 |      0.287 | $10,000.00     | $2,869.68       |
| 2024-03-10 |      0.221 | $5,000.00      | $1,103.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
