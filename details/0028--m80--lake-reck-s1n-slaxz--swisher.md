### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1270.1<br />
<br />
Final Rank Value (1270.1) = Starting Rank Value (1223.5) + Head To Head Adjustments (46.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.579[<sup>1</sup>](#table2)
- Bounty Collected: 0.494[<sup>2</sup>](#table1)
- Opponent Network: 0.197[<sup>2</sup>](#table1)
- LAN Wins: 0.332[<sup>2</sup>](#table1)

The average of these factors is 0.400<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1223.5
- 400 + ( ( 0.400 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1223.5


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
|           54 |      169 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.05 | Lake, reck, s1n, slaxz-, Swisher        |
|           53 |      175 | 2024-07-31 | Limitless        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.06 | Lake, reck, s1n, slaxz-, Swisher        |
|           52 |      219 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.376 (0.179)    | 0 (0.000) |     2.13 | Lake, reck, s1n, slaxz-, Swisher        |
|           51 |      223 | 2024-07-30 | E-Xolos LAZER    | W   | 1.000      | 0.477        | -                | 0.376 (0.179)    | 0 (0.000) |     2.18 | Lake, reck, s1n, slaxz-, Swisher        |
|           50 |      642 | 2024-07-18 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -1.64 | Lake, reck, s1n, slaxz-, Swisher        |
|           49 |      653 | 2024-07-18 | Complexity       | W   | 1.000      | 1.000        | 0.341 (0.341)    | 0.364 (0.364)    | 1 (1.000) |    27.41 | Lake, reck, s1n, slaxz-, Swisher        |
|           48 |      719 | 2024-07-17 | Vitality         | L   | 1.000      | -            | -                | -                | -         |    -0.97 | Lake, reck, s1n, slaxz-, Swisher        |
|           47 |     1237 | 2024-06-09 | Wildcard         | W   | 0.817      | 0.477        | 0.048 (0.019)    | 0.418 (0.163)    | -         |     4.25 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           46 |     1250 | 2024-06-09 | NRG              | L   | 0.815      | -            | -                | -                | -         |   -22.15 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           45 |     1307 | 2024-06-08 | Legacy           | W   | 0.809      | 0.143        | 0.122 (0.014)    | -                | -         |     5.22 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           44 |     1411 | 2024-06-06 | Wildcard         | W   | 0.797      | 0.477        | 0.048 (0.018)    | 0.418 (0.159)    | -         |     3.76 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           43 |     1427 | 2024-06-06 | Wildcard         | W   | 0.796      | -            | -                | -                | -         |     4.16 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           42 |     1434 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.795      | -            | -                | -                | -         |     1.24 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           41 |     1480 | 2024-06-05 | Nouns            | W   | 0.791      | 0.477        | 0.057 (0.021)    | 0.541 (0.204)    | -         |     4.78 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           40 |     1738 | 2024-05-28 | HEROIC           | L   | 0.735      | -            | -                | -                | -         |    -3.49 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           39 |     1756 | 2024-05-27 | FaZe             | L   | 0.729      | -            | -                | -                | -         |    -1.41 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           38 |     1811 | 2024-05-24 | Nouns            | W   | 0.711      | 0.384        | 0.057 (0.016)    | -                | -         |     4.11 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           37 |     1826 | 2024-05-23 | Wildcard         | W   | 0.703      | 0.384        | 0.048 (0.013)    | -                | -         |     3.41 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           36 |     1851 | 2024-05-22 | Party Astronauts | L   | 0.697      | -            | -                | -                | -         |   -18.59 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           35 |     1855 | 2024-05-22 | Party Astronauts | W   | 0.697      | 0.477        | 0.041 (0.014)    | 0.510 (0.169)    | -         |     3.23 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           34 |     1861 | 2024-05-22 | Mythic           | W   | 0.696      | -            | -                | -                | -         |     1.63 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           33 |     1926 | 2024-05-20 | NRG              | W   | 0.684      | 0.477        | -                | 0.502 (0.164)    | -         |     3.05 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           32 |     1930 | 2024-05-20 | NRG              | W   | 0.684      | 0.477        | -                | 0.502 (0.164)    | -         |     3.14 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           31 |     1941 | 2024-05-20 | E-Xolos LAZER    | W   | 0.682      | -            | -                | -                | -         |     1.49 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           30 |     1964 | 2024-05-19 | BOSS             | W   | 0.677      | -            | -                | -                | -         |     1.52 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           29 |     1965 | 2024-05-19 | BOSS             | W   | 0.676      | -            | -                | -                | -         |     1.55 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           28 |     1990 | 2024-05-18 | Nouns            | L   | 0.670      | -            | -                | -                | -         |   -18.26 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           27 |     2024 | 2024-05-17 | DETONATE         | W   | 0.664      | -            | -                | -                | -         |     0.35 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           26 |     2096 | 2024-05-15 | Take Flyte       | W   | 0.651      | -            | -                | -                | -         |     0.87 | malbsMd, reck, slaxz-, stamina, Swisher |
|           25 |     2103 | 2024-05-15 | Take Flyte       | W   | 0.651      | -            | -                | -                | -         |     0.87 | malbsMd, reck, slaxz-, stamina, Swisher |
|           24 |     2146 | 2024-05-14 | Elevate          | W   | 0.644      | -            | -                | -                | -         |     3.58 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           23 |     2153 | 2024-05-14 | Elevate          | W   | 0.644      | -            | -                | -                | -         |     3.70 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           22 |     2275 | 2024-05-10 | Limitless        | W   | 0.618      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           21 |     2276 | 2024-05-10 | Limitless        | W   | 0.617      | -            | -                | -                | -         |     0.62 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           20 |     2291 | 2024-05-09 | LAG              | W   | 0.611      | -            | -                | -                | -         |     1.69 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           19 |     2296 | 2024-05-09 | LAG              | W   | 0.611      | -            | -                | -                | -         |     1.72 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           18 |     2523 | 2024-04-28 | G2               | L   | 0.535      | -            | -                | -                | -         |    -0.32 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           17 |     2551 | 2024-04-27 | TYLOO            | W   | 0.528      | -            | -                | -                | 1 (0.528) |     1.13 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           16 |     2569 | 2024-04-26 | BetBoom          | L   | 0.522      | -            | -                | -                | -         |    -4.77 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           15 |     2581 | 2024-04-26 | G2               | W   | 0.520      | 0.889        | 1.000 (0.462)    | 0.478 (0.221)    | 1 (0.520) |    16.10 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           14 |     2604 | 2024-04-25 | Sharks           | W   | 0.514      | -            | -                | -                | 1 (0.514) |     1.14 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           13 |     2638 | 2024-04-23 | BetBoom          | L   | 0.502      | -            | -                | -                | -         |    -4.57 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           12 |     2724 | 2024-04-19 | Liquid           | W   | 0.477      | 0.143        | 0.383 (0.026)    | -                | -         |    13.34 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           11 |     2731 | 2024-04-19 | Legacy           | W   | 0.476      | -            | -                | -                | -         |     3.78 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           10 |     2774 | 2024-04-18 | Liquid           | L   | 0.471      | -            | -                | -                | -         |    -1.61 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            9 |     2778 | 2024-04-18 | Elevate          | W   | 0.470      | -            | -                | -                | -         |     3.29 | malbsMd, reck, s1n, slaxz-, Swisher     |
|            8 |     3347 | 2024-03-27 | Phoenix          | W   | 0.324      | -            | -                | -                | -         |     0.64 | malbsMd, reck, s1n, stamina, Swisher    |
|            7 |     3353 | 2024-03-27 | Phoenix          | W   | 0.324      | -            | -                | -                | -         |     0.65 | malbsMd, reck, s1n, stamina, Swisher    |
|            6 |     3614 | 2024-03-13 | Wildcard         | L   | 0.231      | -            | -                | -                | -         |    -6.37 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            5 |     3615 | 2024-03-13 | Wildcard         | W   | 0.231      | -            | -                | -                | -         |     0.91 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            4 |     3871 | 2024-03-04 | Legacy           | L   | 0.169      | -            | -                | -                | -         |    -4.05 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            3 |     3903 | 2024-03-03 | Wildcard         | W   | 0.161      | -            | -                | -                | 1 (0.161) |     0.65 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            2 |     3917 | 2024-03-02 | Imperial         | L   | 0.155      | -            | -                | -                | -         |    -2.23 | dephh, malbsMd, reck, slaxz-, Swisher   |
|            1 |     3938 | 2024-03-01 | ODDIK            | W   | 0.149      | -            | -                | -                | 1 (0.149) |     1.01 | dephh, malbsMd, reck, slaxz-, Swisher   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($60,242.50)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-09 |      0.817 | $25,000.00     | $20,423.61      |
| 2024-06-02 |      0.769 | $4,000.00      | $3,074.44       |
| 2024-05-24 |      0.711 | $20,000.00     | $14,211.11      |
| 2024-05-12 |      0.628 | $12,000.00     | $7,533.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
