### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1090.9<br />
<br />
Final Rank Value (1090.9) = Starting Rank Value (1054.1) + Head To Head Adjustments (36.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.460[<sup>1</sup>](#table2)
- Bounty Collected: 0.464[<sup>2</sup>](#table1)
- Opponent Network: 0.050[<sup>2</sup>](#table1)
- LAN Wins: 0.299[<sup>2</sup>](#table1)

The average of these factors is 0.318<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1054.1
- 400 + ( ( 0.318 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1054.1


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
|           21 |     2628 | 2024-04-20 | Sashi             | L   | 0.512      | -            | -                | -                | -         |    -7.09 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           20 |     2667 | 2024-04-19 | BetBoom           | W   | 0.507      | 0.143        | 0.257 (0.019)    | 0.551 (0.040)    | -         |    13.73 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           19 |     2677 | 2024-04-19 | Sashi             | L   | 0.506      | -            | -                | -                | -         |    -7.00 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           18 |     2955 | 2024-04-09 | FaZe              | L   | 0.443      | -            | -                | -                | -         |    -0.40 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           17 |     3005 | 2024-04-08 | Wildcard          | W   | 0.437      | 0.624        | 0.006 (0.002)    | -                | 1 (0.437) |     0.99 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           16 |     3035 | 2024-04-08 | FlyQuest          | L   | 0.431      | -            | -                | -                | -         |    -5.19 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           15 |     3266 | 2024-03-28 | Vitality          | L   | 0.360      | -            | -                | -                | -         |    -0.17 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           14 |     3355 | 2024-03-23 | Natus Vincere     | W   | 0.327      | 1.000        | 1.000 (0.327)    | 0.331 (0.108)    | 1 (0.327) |    10.24 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           13 |     3377 | 2024-03-22 | G2                | W   | 0.319      | 1.000        | 1.000 (0.319)    | 0.500 (0.159)    | 1 (0.319) |     9.98 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           12 |     3388 | 2024-03-21 | Gaimin Gladiators | W   | 0.314      | 1.000        | 0.040 (0.012)    | 0.360 (0.113)    | 1 (0.314) |     4.10 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           11 |     3395 | 2024-03-21 | Spirit            | L   | 0.313      | -            | -                | -                | -         |    -0.09 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     3445 | 2024-03-18 | SAW               | W   | 0.293      | 0.143        | 0.108 (0.005)    | 0.544 (0.023)    | 1 (0.293) |     6.22 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     3462 | 2024-03-17 | Legacy            | W   | 0.288      | 0.143        | 0.119 (0.005)    | 0.562 (0.023)    | 1 (0.288) |     4.24 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     3481 | 2024-03-17 | Gaimin Gladiators | W   | 0.285      | 0.143        | 0.040 (0.002)    | 0.360 (0.015)    | 1 (0.285) |     3.68 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     3696 | 2024-03-08 | SAW               | L   | 0.227      | -            | -                | -                | -         |    -2.33 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     3761 | 2024-03-06 | Rare Atom         | W   | 0.213      | -            | -                | -                | -         |     0.36 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     4108 | 2024-02-20 | Vitality          | W   | 0.112      | 0.143        | 0.590 (0.009)    | 0.384 (0.006)    | 1 (0.112) |     3.50 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     4126 | 2024-02-19 | Apeks             | W   | 0.107      | 0.143        | -                | 0.193 (0.003)    | 1 (0.107) |     1.07 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     4135 | 2024-02-19 | PERA              | W   | 0.106      | 0.143        | 0.048 (0.001)    | 0.452 (0.007)    | 1 (0.106) |     1.11 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4403 | 2024-02-05 | Monte             | L   | 0.012      | -            | -                | -                | -         |    -0.22 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4424 | 2024-02-04 | MOUZ              | L   | 0.005      | -            | -                | -                | -         |    -0.00 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($21,805.50)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.472 | $5,000.00      | $2,357.75       |
| 2024-03-31 |      0.380 | $45,000.00     | $17,112.50      |
| 2024-03-10 |      0.241 | $7,500.00      | $1,804.69       |
| 2024-02-11 |      0.053 | $10,000.00     | $530.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
