### Roster Details<br />
Team Name: GamerLegion<br />
Roster: acoR, isak, Keoz, Snax, volt<br />
Global Rank: [128](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [88]( ../standings_europe.md)<br />
<br />
Final Rank Value:  787.2<br />
<br />
Final Rank Value (787.2) = Starting Rank Value (767.4) + Head To Head Adjustments (19.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.265[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.102[<sup>2</sup>](#table1)

The average of these factors is 0.179<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 767.4
- 400 + ( ( 0.179 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 767.4


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
|           14 |     3488 | 2024-03-20 | Imperial        | L   | 0.274      | -            | -                | -                | -         |    -0.59 | acoR, isak, Keoz, Snax, volt |
|           13 |     3506 | 2024-03-19 | Eternal Fire    | L   | 0.267      | -            | -                | -                | -         |    -0.05 | acoR, isak, Keoz, Snax, volt |
|           12 |     3515 | 2024-03-18 | Legacy          | W   | 0.260      | 0.143        | 0.122 (0.005)    | 0.620 (0.023)    | 1 (0.260) |     6.49 | acoR, isak, Keoz, Snax, volt |
|           11 |     3524 | 2024-03-17 | SAW             | L   | 0.256      | -            | -                | -                | -         |    -0.80 | acoR, isak, Keoz, Snax, volt |
|           10 |     3540 | 2024-03-17 | AMKAL           | W   | 0.254      | 0.143        | 0.130 (0.005)    | 0.453 (0.016)    | 1 (0.254) |     7.07 | acoR, isak, Keoz, Snax, volt |
|            9 |     3760 | 2024-03-08 | BIG             | L   | 0.194      | -            | -                | -                | -         |    -0.30 | acoR, isak, Keoz, Snax, volt |
|            8 |     4065 | 2024-02-24 | 9 Pandas        | L   | 0.107      | -            | -                | -                | -         |    -0.75 | acoR, isak, Keoz, Snax, volt |
|            7 |     4072 | 2024-02-24 | ex-Guild Eagles | W   | 0.106      | 0.143        | 0.007 (0.000)    | 0.207 (0.003)    | 1 (0.106) |     1.87 | acoR, isak, Keoz, Snax, volt |
|            6 |     4080 | 2024-02-23 | fnatic          | W   | 0.101      | 0.143        | 0.371 (0.005)    | 0.680 (0.010)    | 1 (0.101) |     3.14 | acoR, isak, Keoz, Snax, volt |
|            5 |     4098 | 2024-02-22 | HEROIC          | L   | 0.094      | -            | -                | -                | -         |    -0.04 | acoR, isak, Keoz, Snax, volt |
|            4 |     4124 | 2024-02-21 | OG              | W   | 0.087      | 0.143        | 0.137 (0.002)    | 0.120 (0.001)    | 1 (0.087) |     2.13 | acoR, isak, Keoz, Snax, volt |
|            3 |     4156 | 2024-02-20 | ENCE            | L   | 0.080      | -            | -                | -                | -         |    -0.05 | acoR, isak, Keoz, Snax, volt |
|            2 |     4177 | 2024-02-19 | PERA            | W   | 0.074      | 0.143        | 0.048 (0.001)    | 0.435 (0.005)    | 1 (0.074) |     1.67 | acoR, isak, Keoz, Snax, volt |
|            1 |     4186 | 2024-02-19 | Vitality        | L   | 0.073      | -            | -                | -                | -         |    -0.01 | acoR, isak, Keoz, Snax, volt |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,790.63)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-20 |      0.275 | $10,000.00     | $2,747.69       |
| 2024-03-10 |      0.209 | $5,000.00      | $1,042.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
