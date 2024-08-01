### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1289.3<br />
<br />
Final Rank Value (1289.3) = Starting Rank Value (1244.9) + Head To Head Adjustments (44.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.581[<sup>1</sup>](#table2)
- Bounty Collected: 0.496[<sup>2</sup>](#table1)
- Opponent Network: 0.214[<sup>2</sup>](#table1)
- LAN Wins: 0.350[<sup>2</sup>](#table1)

The average of these factors is 0.410<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1244.9
- 400 + ( ( 0.410 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1244.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           60 |       12 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.06 | Lake, reck, s1n, slaxz-, Swisher        |
|           59 |       18 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.07 | Lake, reck, s1n, slaxz-, Swisher        |
|           58 |       62 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.386 (0.184)    | 0 (0.000) |     1.93 | Lake, reck, s1n, slaxz-, Swisher        |
|           57 |       66 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.386 (0.184)    | 0 (0.000) |     1.97 | Lake, reck, s1n, slaxz-, Swisher        |
|           56 |      495 | 2024-07-18 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -1.91 | Lake, reck, s1n, slaxz-, Swisher        |
|           55 |      506 | 2024-07-18 | Complexity       | W   | 1.000      | 1.000        | 0.318 (0.318)    | 0.366 (0.366)    | 1 (1.000) |    26.71 | Lake, reck, s1n, slaxz-, Swisher        |
|           54 |      572 | 2024-07-17 | Vitality         | L   | 1.000      | -            | -                | -                | -         |    -1.10 | Lake, reck, s1n, slaxz-, Swisher        |
|           53 |     1089 | 2024-06-09 | Wildcard         | W   | 0.850      | 0.477        | 0.055 (0.022)    | 0.501 (0.203)    | -         |     4.71 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           52 |     1102 | 2024-06-09 | NRG              | L   | 0.848      | -            | -                | -                | -         |   -23.11 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           51 |     1161 | 2024-06-08 | Legacy           | W   | 0.842      | 0.143        | 0.119 (0.014)    | -                | -         |     5.51 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           50 |     1273 | 2024-06-06 | Wildcard         | W   | 0.830      | 0.477        | 0.055 (0.022)    | 0.501 (0.198)    | -         |     4.23 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           49 |     1290 | 2024-06-06 | Wildcard         | W   | 0.829      | -            | -                | -                | -         |     4.73 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           48 |     1297 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.828      | -            | -                | -                | -         |     1.16 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           47 |     1344 | 2024-06-05 | Nouns            | W   | 0.824      | 0.477        | 0.058 (0.023)    | 0.557 (0.219)    | -         |     4.72 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           46 |     1605 | 2024-05-28 | HEROIC           | L   | 0.768      | -            | -                | -                | -         |    -4.03 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           45 |     1623 | 2024-05-27 | FaZe             | L   | 0.762      | -            | -                | -                | -         |    -1.39 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           44 |     1680 | 2024-05-24 | Nouns            | W   | 0.744      | 0.384        | 0.058 (0.017)    | -                | -         |     4.04 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           43 |     1695 | 2024-05-23 | Wildcard         | W   | 0.736      | 0.384        | 0.055 (0.016)    | -                | -         |     3.93 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           42 |     1720 | 2024-05-22 | Party Astronauts | L   | 0.730      | -            | -                | -                | -         |   -19.58 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           41 |     1724 | 2024-05-22 | Party Astronauts | W   | 0.730      | 0.477        | 0.042 (0.015)    | 0.532 (0.185)    | -         |     3.26 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           40 |     1730 | 2024-05-22 | Mythic           | W   | 0.729      | -            | -                | -                | -         |     1.61 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           39 |     1773 | 2024-05-21 | MIGHT            | W   | 0.724      | -            | -                | -                | -         |     0.35 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           38 |     1776 | 2024-05-21 | MIGHT            | W   | 0.724      | -            | -                | -                | -         |     0.35 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           37 |     1811 | 2024-05-20 | NRG              | W   | 0.717      | 0.477        | -                | 0.519 (0.178)    | -         |     3.16 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           36 |     1815 | 2024-05-20 | NRG              | W   | 0.717      | 0.477        | -                | 0.519 (0.177)    | -         |     3.26 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           35 |     1827 | 2024-05-20 | E-Xolos LAZER    | W   | 0.716      | -            | -                | -                | -         |     1.42 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           34 |     1853 | 2024-05-19 | BOSS             | W   | 0.710      | -            | -                | -                | -         |     1.51 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           33 |     1856 | 2024-05-19 | BOSS             | W   | 0.709      | -            | -                | -                | -         |     1.54 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           32 |     1858 | 2024-05-19 | FLUFFY AIMERS    | W   | 0.709      | -            | -                | -                | -         |     1.04 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           31 |     1859 | 2024-05-19 | FLUFFY AIMERS    | W   | 0.709      | -            | -                | -                | -         |     1.06 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           30 |     1884 | 2024-05-18 | Nouns            | L   | 0.703      | -            | -                | -                | -         |   -19.36 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           29 |     1919 | 2024-05-17 | Detonate         | W   | 0.697      | -            | -                | -                | -         |     0.33 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           28 |     1991 | 2024-05-15 | Take Flyte       | W   | 0.684      | -            | -                | -                | -         |     0.83 | malbsMd, reck, slaxz-, stamina, Swisher |
|           27 |     1998 | 2024-05-15 | Take Flyte       | W   | 0.684      | -            | -                | -                | -         |     0.84 | malbsMd, reck, slaxz-, stamina, Swisher |
|           26 |     2047 | 2024-05-14 | Elevate          | W   | 0.677      | -            | -                | -                | -         |     3.61 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           25 |     2054 | 2024-05-14 | Elevate          | W   | 0.677      | -            | -                | -                | -         |     3.74 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           24 |     2179 | 2024-05-10 | Limitless        | W   | 0.651      | -            | -                | -                | -         |     0.60 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           23 |     2180 | 2024-05-10 | Limitless        | W   | 0.650      | -            | -                | -                | -         |     0.60 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           22 |     2195 | 2024-05-09 | LAG              | W   | 0.644      | -            | -                | -                | -         |     1.81 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           21 |     2200 | 2024-05-09 | LAG              | W   | 0.644      | -            | -                | -                | -         |     1.84 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           20 |     2223 | 2024-05-08 | Carpe Diem       | W   | 0.637      | -            | -                | -                | -         |     0.70 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           19 |     2224 | 2024-05-08 | Carpe Diem       | W   | 0.637      | -            | -                | -                | -         |     0.70 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           18 |     2432 | 2024-04-28 | G2               | L   | 0.568      | -            | -                | -                | -         |    -0.39 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           17 |     2460 | 2024-04-27 | TYLOO            | W   | 0.561      | -            | -                | -                | 1 (0.561) |     1.10 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           16 |     2479 | 2024-04-26 | BetBoom          | L   | 0.555      | -            | -                | -                | -         |    -5.19 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           15 |     2491 | 2024-04-26 | G2               | W   | 0.553      | 0.889        | 1.000 (0.492)    | 0.500 (0.246)    | 1 (0.553) |    17.09 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           14 |     2513 | 2024-04-25 | Sharks           | W   | 0.547      | -            | -                | -                | 1 (0.547) |     1.23 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           13 |     2548 | 2024-04-23 | BetBoom          | L   | 0.535      | -            | -                | -                | -         |    -4.99 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           12 |     2639 | 2024-04-19 | Liquid           | W   | 0.510      | 0.143        | 0.322 (0.023)    | -                | -         |    12.43 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           11 |     2646 | 2024-04-19 | Legacy           | W   | 0.509      | -            | -                | -                | -         |     3.98 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           10 |     2690 | 2024-04-18 | Liquid           | L   | 0.504      | -            | -                | -                | -         |    -3.52 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            9 |     2694 | 2024-04-18 | Elevate          | W   | 0.503      | -            | -                | -                | -         |     3.36 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            8 |     3275 | 2024-03-27 | Perseverance     | W   | 0.357      | -            | -                | -                | -         |     0.66 | malbsMd, reck, s1n, stamina, Swisher    |
|            7 |     3281 | 2024-03-27 | Perseverance     | W   | 0.357      | -            | -                | -                | -         |     0.66 | malbsMd, reck, s1n, stamina, Swisher    |
|            6 |     3551 | 2024-03-13 | Wildcard         | L   | 0.264      | -            | -                | -                | -         |    -7.17 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            5 |     3552 | 2024-03-13 | Wildcard         | W   | 0.264      | -            | -                | -                | -         |     1.16 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            4 |     3815 | 2024-03-04 | Legacy           | L   | 0.202      | -            | -                | -                | -         |    -4.89 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            3 |     3848 | 2024-03-03 | Wildcard         | W   | 0.194      | -            | -                | -                | 1 (0.194) |     0.86 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            2 |     3861 | 2024-03-02 | Imperial         | L   | 0.188      | -            | -                | -                | -         |    -2.70 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            1 |     3883 | 2024-03-01 | ODDIK            | W   | 0.182      | -            | -                | -                | 1 (0.182) |     1.23 | dephh, malbsMd, reck, slaxz-, Swisher   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($62,258.89)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-09 |      0.850 | $25,000.00     | $21,250.00      |
| 2024-06-02 |      0.802 | $4,000.00      | $3,206.67       |
| 2024-05-24 |      0.744 | $20,000.00     | $14,872.22      |
| 2024-05-12 |      0.661 | $12,000.00     | $7,930.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
