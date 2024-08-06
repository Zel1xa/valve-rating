### Roster Details<br />
Team Name: Cloud9<br />
Roster: alpha, Ax1Le, Boombl4, HObbit, Perfecto<br />
Global Rank: [51](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [38]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1064.1<br />
<br />
Final Rank Value (1064.1) = Starting Rank Value (1027.8) + Head To Head Adjustments (36.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.451[<sup>1</sup>](#table2)
- Bounty Collected: 0.455[<sup>2</sup>](#table1)
- Opponent Network: 0.054[<sup>2</sup>](#table1)
- LAN Wins: 0.261[<sup>2</sup>](#table1)

The average of these factors is 0.305<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1027.8
- 400 + ( ( 0.305 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1027.8


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
|           19 |     2722 | 2024-04-20 | Sashi             | L   | 0.479      | -            | -                | -                | -         |    -6.11 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           18 |     2760 | 2024-04-19 | BetBoom           | W   | 0.474      | 0.143        | 0.248 (0.017)    | 0.513 (0.035)    | -         |    13.00 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           17 |     2770 | 2024-04-19 | Sashi             | L   | 0.473      | -            | -                | -                | -         |    -5.99 | alpha, Ax1Le, Boombl4, HObbit, Perfecto      |
|           16 |     3044 | 2024-04-09 | FaZe              | L   | 0.410      | -            | -                | -                | -         |    -0.38 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           15 |     3094 | 2024-04-08 | Wildcard          | W   | 0.404      | 0.624        | 0.048 (0.012)    | 0.418 (0.105)    | 1 (0.404) |     3.50 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           14 |     3124 | 2024-04-08 | FlyQuest          | L   | 0.398      | -            | -                | -                | -         |    -4.68 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           13 |     3347 | 2024-03-28 | Vitality          | L   | 0.327      | -            | -                | -                | -         |    -0.12 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           12 |     3431 | 2024-03-23 | Natus Vincere     | W   | 0.294      | 1.000        | 1.000 (0.294)    | 0.357 (0.105)    | 1 (0.294) |     9.21 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           11 |     3453 | 2024-03-22 | G2                | W   | 0.286      | 1.000        | 1.000 (0.286)    | 0.478 (0.136)    | 1 (0.286) |     8.95 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|           10 |     3464 | 2024-03-21 | Gaimin Gladiators | W   | 0.281      | 1.000        | 0.037 (0.010)    | 0.331 (0.093)    | 1 (0.281) |     3.71 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            9 |     3471 | 2024-03-21 | Spirit            | L   | 0.280      | -            | -                | -                | -         |    -0.07 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            8 |     3521 | 2024-03-18 | SAW               | W   | 0.260      | 0.143        | 0.104 (0.004)    | 0.516 (0.019)    | 1 (0.260) |     5.59 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            7 |     3538 | 2024-03-17 | Legacy            | W   | 0.255      | 0.143        | 0.122 (0.004)    | 0.621 (0.023)    | 1 (0.255) |     3.90 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            6 |     3557 | 2024-03-17 | Gaimin Gladiators | W   | 0.252      | 0.143        | 0.037 (0.001)    | 0.331 (0.012)    | 1 (0.252) |     3.29 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            5 |     3766 | 2024-03-08 | SAW               | L   | 0.194      | -            | -                | -                | -         |    -1.95 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            4 |     3831 | 2024-03-06 | Rare Atom         | W   | 0.180      | -            | -                | -                | -         |     0.35 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            3 |     4163 | 2024-02-20 | Vitality          | W   | 0.079      | 0.143        | 0.647 (0.007)    | 0.367 (0.004)    | 1 (0.079) |     2.47 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            2 |     4181 | 2024-02-19 | Apeks             | W   | 0.074      | -            | -                | -                | 1 (0.074) |     0.76 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |
|            1 |     4190 | 2024-02-19 | PERA              | W   | 0.073      | 0.143        | 0.047 (0.000)    | 0.435 (0.005)    | 1 (0.073) |     0.84 | Ax1Le, Boombl4, electroNic, HObbit, Perfecto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,374.25)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      0.438 | $5,000.00      | $2,192.48       |
| 2024-03-31 |      0.347 | $45,000.00     | $15,625.00      |
| 2024-03-10 |      0.208 | $7,500.00      | $1,556.77       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
