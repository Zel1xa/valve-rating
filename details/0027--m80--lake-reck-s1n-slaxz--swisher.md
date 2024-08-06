### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1269.8<br />
<br />
Final Rank Value (1269.8) = Starting Rank Value (1223.2) + Head To Head Adjustments (46.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.579[<sup>1</sup>](#table2)
- Bounty Collected: 0.494[<sup>2</sup>](#table1)
- Opponent Network: 0.196[<sup>2</sup>](#table1)
- LAN Wins: 0.331[<sup>2</sup>](#table1)

The average of these factors is 0.400<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1223.2
- 400 + ( ( 0.400 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1223.2


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
|           54 |      180 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.05 | Lake, reck, s1n, slaxz-, Swisher        |
|           53 |      186 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.07 | Lake, reck, s1n, slaxz-, Swisher        |
|           52 |      230 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.376 (0.179)    | 0 (0.000) |     2.14 | Lake, reck, s1n, slaxz-, Swisher        |
|           51 |      234 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.376 (0.179)    | 0 (0.000) |     2.19 | Lake, reck, s1n, slaxz-, Swisher        |
|           50 |      653 | 2024-07-18 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -1.64 | Lake, reck, s1n, slaxz-, Swisher        |
|           49 |      664 | 2024-07-18 | Complexity       | W   | 1.000      | 1.000        | 0.341 (0.341)    | 0.364 (0.364)    | 1 (1.000) |    27.41 | Lake, reck, s1n, slaxz-, Swisher        |
|           48 |      730 | 2024-07-17 | Vitality         | L   | 1.000      | -            | -                | -                | -         |    -0.97 | Lake, reck, s1n, slaxz-, Swisher        |
|           47 |     1248 | 2024-06-09 | Wildcard         | W   | 0.816      | 0.477        | 0.048 (0.019)    | 0.418 (0.162)    | -         |     4.24 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           46 |     1261 | 2024-06-09 | NRG              | L   | 0.814      | -            | -                | -                | -         |   -22.11 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           45 |     1318 | 2024-06-08 | Legacy           | W   | 0.808      | 0.143        | 0.122 (0.014)    | -                | -         |     5.21 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           44 |     1422 | 2024-06-06 | Wildcard         | W   | 0.796      | 0.477        | 0.048 (0.018)    | 0.418 (0.159)    | -         |     3.75 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           43 |     1438 | 2024-06-06 | Wildcard         | W   | 0.794      | -            | -                | -                | -         |     4.16 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           42 |     1445 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.794      | -            | -                | -                | -         |     1.24 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           41 |     1491 | 2024-06-05 | Nouns            | W   | 0.789      | 0.477        | 0.057 (0.021)    | 0.541 (0.204)    | -         |     4.78 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           40 |     1749 | 2024-05-28 | HEROIC           | L   | 0.734      | -            | -                | -                | -         |    -3.49 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           39 |     1767 | 2024-05-27 | FaZe             | L   | 0.728      | -            | -                | -                | -         |    -1.41 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           38 |     1822 | 2024-05-24 | Nouns            | W   | 0.709      | 0.384        | 0.057 (0.016)    | -                | -         |     4.10 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           37 |     1837 | 2024-05-23 | Wildcard         | W   | 0.702      | 0.384        | 0.048 (0.013)    | -                | -         |     3.40 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           36 |     1862 | 2024-05-22 | Party Astronauts | L   | 0.696      | -            | -                | -                | -         |   -18.55 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           35 |     1866 | 2024-05-22 | Party Astronauts | W   | 0.695      | 0.477        | 0.041 (0.014)    | 0.510 (0.169)    | -         |     3.23 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           34 |     1872 | 2024-05-22 | Mythic           | W   | 0.694      | -            | -                | -                | -         |     1.63 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           33 |     1937 | 2024-05-20 | NRG              | W   | 0.683      | 0.477        | -                | 0.502 (0.163)    | -         |     3.05 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           32 |     1941 | 2024-05-20 | NRG              | W   | 0.682      | 0.477        | -                | 0.502 (0.163)    | -         |     3.14 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           31 |     1952 | 2024-05-20 | E-Xolos LAZER    | W   | 0.681      | -            | -                | -                | -         |     1.49 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           30 |     1975 | 2024-05-19 | BOSS             | W   | 0.675      | -            | -                | -                | -         |     1.52 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           29 |     1976 | 2024-05-19 | BOSS             | W   | 0.675      | -            | -                | -                | -         |     1.54 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           28 |     2001 | 2024-05-18 | Nouns            | L   | 0.668      | -            | -                | -                | -         |   -18.22 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           27 |     2035 | 2024-05-17 | DETONATE         | W   | 0.662      | -            | -                | -                | -         |     0.35 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           26 |     2107 | 2024-05-15 | Take Flyte       | W   | 0.649      | -            | -                | -                | -         |     0.87 | malbsMd, reck, slaxz-, stamina, Swisher |
|           25 |     2114 | 2024-05-15 | Take Flyte       | W   | 0.649      | -            | -                | -                | -         |     0.87 | malbsMd, reck, slaxz-, stamina, Swisher |
|           24 |     2157 | 2024-05-14 | Elevate          | W   | 0.643      | -            | -                | -                | -         |     3.57 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           23 |     2164 | 2024-05-14 | Elevate          | W   | 0.642      | -            | -                | -                | -         |     3.69 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           22 |     2286 | 2024-05-10 | Limitless        | W   | 0.616      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           21 |     2287 | 2024-05-10 | Limitless        | W   | 0.616      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           20 |     2302 | 2024-05-09 | LAG              | W   | 0.609      | -            | -                | -                | -         |     1.69 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           19 |     2307 | 2024-05-09 | LAG              | W   | 0.609      | -            | -                | -                | -         |     1.72 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           18 |     2534 | 2024-04-28 | G2               | L   | 0.534      | -            | -                | -                | -         |    -0.32 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           17 |     2562 | 2024-04-27 | TYLOO            | W   | 0.526      | -            | -                | -                | 1 (0.526) |     1.13 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           16 |     2580 | 2024-04-26 | BetBoom          | L   | 0.521      | -            | -                | -                | -         |    -4.76 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           15 |     2592 | 2024-04-26 | G2               | W   | 0.519      | 0.889        | 1.000 (0.461)    | 0.478 (0.220)    | 1 (0.519) |    16.06 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           14 |     2615 | 2024-04-25 | Sharks           | W   | 0.513      | -            | -                | -                | 1 (0.513) |     1.14 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           13 |     2649 | 2024-04-23 | BetBoom          | L   | 0.500      | -            | -                | -                | -         |    -4.56 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           12 |     2735 | 2024-04-19 | Liquid           | W   | 0.476      | 0.143        | 0.383 (0.026)    | -                | -         |    13.30 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           11 |     2742 | 2024-04-19 | Legacy           | W   | 0.475      | -            | -                | -                | -         |     3.77 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           10 |     2785 | 2024-04-18 | Liquid           | L   | 0.469      | -            | -                | -                | -         |    -1.60 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            9 |     2789 | 2024-04-18 | Elevate          | W   | 0.468      | -            | -                | -                | -         |     3.29 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            8 |     3358 | 2024-03-27 | Phoenix          | W   | 0.322      | -            | -                | -                | -         |     0.64 | malbsMd, reck, s1n, stamina, Swisher    |
|            7 |     3364 | 2024-03-27 | Phoenix          | W   | 0.322      | -            | -                | -                | -         |     0.64 | malbsMd, reck, s1n, stamina, Swisher    |
|            6 |     3625 | 2024-03-13 | Wildcard         | L   | 0.230      | -            | -                | -                | -         |    -6.33 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            5 |     3626 | 2024-03-13 | Wildcard         | W   | 0.229      | -            | -                | -                | -         |     0.91 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            4 |     3882 | 2024-03-04 | Legacy           | L   | 0.167      | -            | -                | -                | -         |    -4.02 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            3 |     3914 | 2024-03-03 | Wildcard         | W   | 0.160      | -            | -                | -                | 1 (0.160) |     0.64 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            2 |     3928 | 2024-03-02 | Imperial         | L   | 0.154      | -            | -                | -                | -         |    -2.21 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            1 |     3949 | 2024-03-01 | ODDIK            | W   | 0.148      | -            | -                | -                | 1 (0.148) |     1.01 | dephh, malbsMd, reck, slaxz-, Swisher   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($60,157.78)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-09 |      0.816 | $25,000.00     | $20,388.89      |
| 2024-06-02 |      0.767 | $4,000.00      | $3,068.89       |
| 2024-05-24 |      0.709 | $20,000.00     | $14,183.33      |
| 2024-05-12 |      0.626 | $12,000.00     | $7,516.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
