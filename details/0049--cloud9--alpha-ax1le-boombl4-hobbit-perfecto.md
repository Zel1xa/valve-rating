### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [49](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1068.8<br />
<br />
Final Rank Value (1068.8) = Starting Rank Value (1032.9) + Head To Head Adjustments (36.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.454[<sup>1</sup>](#table2)
- Bounty Collected: 0.460[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.278[<sup>2</sup>](#table1)

The average of these factors is 0.310<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1032.9
- 400 + ( ( 0.310 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1032.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     2636 | 2024-04-20 | Sashi             | L   | 0.497      | -            | -                | -                | -         |    -6.54 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           18 |     2674 | 2024-04-19 | BetBoom           | W   | 0.492      | 0.143        | 0.252 (0.018)    | 0.543 (0.038)    | -         |    13.49 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           17 |     2684 | 2024-04-19 | Sashi             | L   | 0.491      | -            | -                | -                | -         |    -6.43 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           16 |     2958 | 2024-04-09 | FaZe              | L   | 0.428      | -            | -                | -                | -         |    -0.39 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           15 |     3008 | 2024-04-08 | Wildcard          | W   | 0.422      | 0.624        | 0.006 (0.001)    | -                | 1 (0.422) |     0.72 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           14 |     3038 | 2024-04-08 | FlyQuest          | L   | 0.416      | -            | -                | -                | -         |    -4.90 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           13 |     3261 | 2024-03-28 | Vitality          | L   | 0.345      | -            | -                | -                | -         |    -0.14 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           12 |     3345 | 2024-03-23 | Natus Vincere     | W   | 0.312      | 1.000        | 1.000 (0.312)    | 0.331 (0.103)    | 1 (0.312) |     9.78 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           11 |     3367 | 2024-03-22 | G2                | W   | 0.304      | 1.000        | 1.000 (0.304)    | 0.498 (0.151)    | 1 (0.304) |     9.51 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     3378 | 2024-03-21 | Gaimin Gladiators | W   | 0.299      | 1.000        | 0.038 (0.011)    | 0.353 (0.105)    | 1 (0.299) |     3.97 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     3385 | 2024-03-21 | Spirit            | L   | 0.298      | -            | -                | -                | -         |    -0.08 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     3435 | 2024-03-18 | SAW               | W   | 0.278      | 0.143        | 0.106 (0.004)    | 0.541 (0.021)    | 1 (0.278) |     5.99 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     3452 | 2024-03-17 | Legacy            | W   | 0.273      | 0.143        | 0.122 (0.005)    | 0.642 (0.025)    | 1 (0.273) |     4.17 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     3471 | 2024-03-17 | Gaimin Gladiators | W   | 0.270      | 0.143        | 0.038 (0.001)    | 0.353 (0.014)    | 1 (0.270) |     3.55 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     3679 | 2024-03-08 | SAW               | L   | 0.212      | -            | -                | -                | -         |    -2.13 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     3744 | 2024-03-06 | Rare Atom         | W   | 0.198      | -            | -                | -                | -         |     0.38 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     4076 | 2024-02-20 | Vitality          | W   | 0.097      | 0.143        | 0.649 (0.009)    | 0.383 (0.005)    | 1 (0.097) |     3.03 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4094 | 2024-02-19 | Apeks             | W   | 0.092      | 0.143        | -                | 0.168 (0.002)    | 1 (0.092) |     0.95 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4103 | 2024-02-19 | PERA              | W   | 0.091      | 0.143        | 0.048 (0.001)    | 0.453 (0.006)    | 1 (0.091) |     1.02 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,412.44)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.457 | $5,000.00      | $2,282.75       |
| 2024-03-31 |      0.365 | $45,000.00     | $16,437.50      |
| 2024-03-10 |      0.226 | $7,500.00      | $1,692.19       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
