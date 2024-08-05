### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [9](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [8]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1685.8<br />
<br />
Final Rank Value (1685.8) = Starting Rank Value (1707.2) + Head To Head Adjustments (-21.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.712[<sup>1</sup>](#table2)
- Bounty Collected: 0.631[<sup>2</sup>](#table1)
- Opponent Network: 0.330[<sup>2</sup>](#table1)
- LAN Wins: 0.862[<sup>2</sup>](#table1)

The average of these factors is 0.634<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1707.2
- 400 + ( ( 0.634 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1707.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |       58 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.14 | br0, device, jabbi, Staehr, stavn    |
|           30 |       86 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     6.78 | br0, device, jabbi, Staehr, stavn    |
|           29 |      909 | 2024-06-14 | Virtus.pro        | L   | 0.886      | -            | -                | -                | -         |   -14.32 | br0, device, jabbi, Staehr, stavn    |
|           28 |      968 | 2024-06-13 | SAW               | W   | 0.877      | 0.729        | -                | 0.545 (0.349)    | 1 (0.877) |     1.40 | br0, device, jabbi, Staehr, stavn    |
|           27 |      991 | 2024-06-12 | Natus Vincere     | L   | 0.871      | -            | -                | -                | -         |    -6.08 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1152 | 2024-06-08 | The MongolZ       | L   | 0.845      | -            | -                | -                | -         |    -7.00 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1207 | 2024-06-07 | BetBoom           | W   | 0.838      | 0.715        | 0.256 (0.154)    | 0.554 (0.332)    | 1 (0.838) |     4.69 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1254 | 2024-06-06 | The MongolZ       | W   | 0.832      | 0.715        | 1.000 (0.595)    | 0.719 (0.428)    | 1 (0.832) |    19.95 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1274 | 2024-06-06 | ENCE              | W   | 0.831      | 0.715        | -                | 0.404 (0.240)    | 1 (0.831) |     3.52 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1284 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.830      | -            | -                | -                | -         |   -18.20 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1330 | 2024-06-05 | Sashi             | L   | 0.825      | -            | -                | -                | -         |   -24.58 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1343 | 2024-06-05 | HEROIC            | W   | 0.823      | 0.715        | -                | 0.382 (0.225)    | 1 (0.823) |     8.40 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1692 | 2024-05-22 | Liquid            | L   | 0.731      | -            | -                | -                | -         |   -17.90 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1733 | 2024-05-21 | Aurora            | W   | 0.724      | 0.769        | 0.429 (0.239)    | 0.800 (0.445)    | -         |     6.14 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1763 | 2024-05-20 | BetBoom           | W   | 0.719      | 0.769        | 0.256 (0.142)    | 0.554 (0.306)    | -         |     2.93 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1783 | 2024-05-19 | BIG               | W   | 0.713      | -            | -                | -                | -         |     1.45 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2079 | 2024-05-11 | Vitality          | L   | 0.658      | -            | -                | -                | -         |    -6.43 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2098 | 2024-05-10 | Liquid            | W   | 0.652      | 0.889        | 0.387 (0.224)    | 0.430 (0.249)    | 1 (0.652) |     4.23 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2365 | 2024-04-27 | 3DMAX             | W   | 0.565      | 0.889        | 0.499 (0.251)    | 1.000 (0.502)    | 1 (0.565) |     6.63 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2436 | 2024-04-24 | FaZe              | W   | 0.546      | 0.889        | 0.663 (0.322)    | -                | 1 (0.546) |     9.45 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2456 | 2024-04-23 | Eternal Fire      | W   | 0.539      | 0.889        | 0.752 (0.360)    | 0.462 (0.221)    | 1 (0.539) |     8.83 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2743 | 2024-04-13 | FaZe              | L   | 0.471      | -            | -                | -                | -         |    -6.85 | br0, device, jabbi, Staehr, stavn    |
|            9 |     2843 | 2024-04-10 | Virtus.pro        | W   | 0.450      | 0.624        | 0.494 (0.139)    | -                | -         |     7.47 | br0, device, jabbi, Staehr, stavn    |
|            8 |     2891 | 2024-04-09 | FaZe              | W   | 0.444      | 0.624        | 0.663 (0.183)    | -                | -         |     7.76 | br0, device, jabbi, Staehr, stavn    |
|            7 |     2923 | 2024-04-08 | Steel Helmet      | W   | 0.437      | -            | -                | -                | -         |     0.02 | br0, device, jabbi, Staehr, stavn    |
|            6 |     3894 | 2024-02-23 | 9 Pandas          | L   | 0.137      | -            | -                | -                | -         |    -4.24 | blameF, device, jabbi, Staehr, stavn |
|            5 |     3913 | 2024-02-22 | ENCE              | L   | 0.131      | -            | -                | -                | -         |    -3.16 | blameF, device, jabbi, Staehr, stavn |
|            4 |     3940 | 2024-02-21 | Monte             | W   | 0.124      | -            | -                | -                | -         |     0.08 | blameF, device, jabbi, Staehr, stavn |
|            3 |     3966 | 2024-02-20 | HEROIC            | L   | 0.118      | -            | -                | -                | -         |    -2.42 | blameF, device, jabbi, Staehr, stavn |
|            2 |     3981 | 2024-02-19 | Spirit            | L   | 0.113      | -            | -                | -                | -         |    -0.83 | blameF, device, jabbi, Staehr, stavn |
|            1 |     3991 | 2024-02-19 | Nexus             | W   | 0.111      | -            | -                | -                | -         |     0.03 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($130,698.66)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.39) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-16 |      0.898 | $20,000.00     | $17,964.54      |
| 2024-06-09 |      0.852 | $28,000.00     | $23,851.46      |
| 2024-05-23 |      0.738 | $50,000.00     | $36,904.40      |
| 2024-05-12 |      0.665 | $45,000.00     | $29,932.71      |
| 2024-04-14 |      0.477 | $20,000.00     | $9,545.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
