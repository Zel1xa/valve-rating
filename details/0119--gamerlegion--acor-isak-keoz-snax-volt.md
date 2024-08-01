### Roster Details<br />
Team Name: GamerLegion<br />
Roster: acoR, isak, Keoz, Snax, volt<br />
Global Rank: [119](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [86]( ../standings_europe.md)<br />
<br />
Final Rank Value:  812.9<br />
<br />
Final Rank Value (812.9) = Starting Rank Value (789.6) + Head To Head Adjustments (23.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.356[<sup>1</sup>](#table2)
- Bounty Collected: 0.270[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.125[<sup>2</sup>](#table1)

The average of these factors is 0.189<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 789.6
- 400 + ( ( 0.189 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 789.6


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
|           17 |     3422 | 2024-03-20 | Imperial        | L   | 0.306      | -            | -                | -                | -         |    -0.68 | acoR, isak, Keoz, Snax, volt |
|           16 |     3440 | 2024-03-19 | Eternal Fire    | L   | 0.299      | -            | -                | -                | -         |    -0.06 | acoR, isak, Keoz, Snax, volt |
|           15 |     3449 | 2024-03-18 | Legacy          | W   | 0.292      | 0.143        | 0.119 (0.005)    | 0.562 (0.023)    | 1 (0.292) |     7.19 | acoR, isak, Keoz, Snax, volt |
|           14 |     3458 | 2024-03-17 | SAW             | L   | 0.288      | -            | -                | -                | -         |    -0.93 | acoR, isak, Keoz, Snax, volt |
|           13 |     3474 | 2024-03-17 | AMKAL           | W   | 0.286      | 0.143        | 0.132 (0.005)    | 0.482 (0.020)    | 1 (0.286) |     7.86 | acoR, isak, Keoz, Snax, volt |
|           12 |     3700 | 2024-03-08 | BIG             | L   | 0.226      | -            | -                | -                | -         |    -0.59 | acoR, isak, Keoz, Snax, volt |
|           11 |     4016 | 2024-02-24 | 9 Pandas        | L   | 0.139      | -            | -                | -                | -         |    -1.04 | acoR, isak, Keoz, Snax, volt |
|           10 |     4023 | 2024-02-24 | ex-Guild Eagles | W   | 0.138      | 0.143        | 0.007 (0.000)    | 0.224 (0.004)    | 1 (0.138) |     2.35 | acoR, isak, Keoz, Snax, volt |
|            9 |     4032 | 2024-02-23 | fnatic          | W   | 0.133      | 0.143        | 0.292 (0.006)    | 0.529 (0.010)    | 1 (0.133) |     4.03 | acoR, isak, Keoz, Snax, volt |
|            8 |     4052 | 2024-02-22 | HEROIC          | L   | 0.126      | -            | -                | -                | -         |    -0.05 | acoR, isak, Keoz, Snax, volt |
|            7 |     4080 | 2024-02-21 | OG              | W   | 0.119      | 0.143        | 0.143 (0.002)    | 0.132 (0.002)    | 1 (0.119) |     2.85 | acoR, isak, Keoz, Snax, volt |
|            6 |     4111 | 2024-02-20 | ENCE            | L   | 0.112      | -            | -                | -                | -         |    -0.07 | acoR, isak, Keoz, Snax, volt |
|            5 |     4132 | 2024-02-19 | PERA            | W   | 0.107      | 0.143        | 0.048 (0.001)    | 0.452 (0.007)    | 1 (0.107) |     2.30 | acoR, isak, Keoz, Snax, volt |
|            4 |     4141 | 2024-02-19 | Vitality        | L   | 0.105      | -            | -                | -                | -         |    -0.01 | acoR, isak, Keoz, Snax, volt |
|            3 |     4394 | 2024-02-06 | HEROIC          | L   | 0.019      | -            | -                | -                | -         |    -0.01 | acoR, isak, Keoz, Snax, volt |
|            2 |     4400 | 2024-02-05 | MOUZ            | L   | 0.013      | -            | -                | -                | -         |    -0.00 | acoR, isak, Keoz, Snax, volt |
|            1 |     4425 | 2024-02-04 | Monte           | W   | 0.005      | 1.000        | 0.062 (0.000)    | 0.168 (0.001)    | 1 (0.005) |     0.13 | acoR, isak, Keoz, Snax, volt |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,120.07)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-20 |      0.307 | $10,000.00     | $3,068.06       |
| 2024-03-10 |      0.241 | $5,000.00      | $1,203.13       |
| 2024-02-11 |      0.053 | $16,000.00     | $848.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
