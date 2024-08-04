### Roster Details<br />
Team Name: GamerLegion<br />
Roster: acoR, isak, Keoz, Snax, volt<br />
Global Rank: [124](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [86]( ../standings_europe.md)<br />
<br />
Final Rank Value:  793.7<br />
<br />
Final Rank Value (793.7) = Starting Rank Value (772.2) + Head To Head Adjustments (21.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.268[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.110[<sup>2</sup>](#table1)

The average of these factors is 0.182<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 772.2
- 400 + ( ( 0.182 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 772.2


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
|           14 |     3425 | 2024-03-20 | Imperial        | L   | 0.287      | -            | -                | -                | -         |    -0.61 | acoR, isak, Keoz, Snax, volt |
|           13 |     3443 | 2024-03-19 | Eternal Fire    | L   | 0.280      | -            | -                | -                | -         |    -0.06 | acoR, isak, Keoz, Snax, volt |
|           12 |     3452 | 2024-03-18 | Legacy          | W   | 0.273      | 0.143        | 0.122 (0.005)    | 0.643 (0.025)    | 1 (0.273) |     6.80 | acoR, isak, Keoz, Snax, volt |
|           11 |     3461 | 2024-03-17 | SAW             | L   | 0.269      | -            | -                | -                | -         |    -0.84 | acoR, isak, Keoz, Snax, volt |
|           10 |     3477 | 2024-03-17 | AMKAL           | W   | 0.267      | 0.143        | 0.130 (0.005)    | 0.475 (0.018)    | 1 (0.267) |     7.42 | acoR, isak, Keoz, Snax, volt |
|            9 |     3697 | 2024-03-08 | BIG             | L   | 0.208      | -            | -                | -                | -         |    -0.33 | acoR, isak, Keoz, Snax, volt |
|            8 |     4002 | 2024-02-24 | 9 Pandas        | L   | 0.120      | -            | -                | -                | -         |    -0.85 | acoR, isak, Keoz, Snax, volt |
|            7 |     4009 | 2024-02-24 | ex-Guild Eagles | W   | 0.120      | 0.143        | 0.007 (0.000)    | 0.219 (0.004)    | 1 (0.120) |     2.08 | acoR, isak, Keoz, Snax, volt |
|            6 |     4017 | 2024-02-23 | fnatic          | W   | 0.114      | 0.143        | 0.371 (0.006)    | 0.708 (0.012)    | 1 (0.114) |     3.55 | acoR, isak, Keoz, Snax, volt |
|            5 |     4035 | 2024-02-22 | HEROIC          | L   | 0.108      | -            | -                | -                | -         |    -0.04 | acoR, isak, Keoz, Snax, volt |
|            4 |     4061 | 2024-02-21 | OG              | W   | 0.100      | 0.143        | 0.139 (0.002)    | 0.128 (0.002)    | 1 (0.100) |     2.45 | acoR, isak, Keoz, Snax, volt |
|            3 |     4093 | 2024-02-20 | ENCE            | L   | 0.093      | -            | -                | -                | -         |    -0.06 | acoR, isak, Keoz, Snax, volt |
|            2 |     4114 | 2024-02-19 | PERA            | W   | 0.088      | 0.143        | 0.048 (0.001)    | 0.453 (0.006)    | 1 (0.088) |     1.95 | acoR, isak, Keoz, Snax, volt |
|            1 |     4123 | 2024-02-19 | Vitality        | L   | 0.086      | -            | -                | -                | -         |    -0.01 | acoR, isak, Keoz, Snax, volt |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,989.58)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-20 |      0.288 | $10,000.00     | $2,880.32       |
| 2024-03-10 |      0.222 | $5,000.00      | $1,109.26       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
