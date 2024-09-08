### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, susp, ztr<br />
Global Rank: [122](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [86]( ../standings_europe.md)<br />
<br />
Final Rank Value:  777.9<br />
<br />
Final Rank Value (777.9) = Starting Rank Value (744.7) + Head To Head Adjustments (33.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.349[<sup>1</sup>](#table2)
- Bounty Collected: 0.320[<sup>2</sup>](#table1)
- Opponent Network: 0.043[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.178<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 744.7
- 400 + ( ( 0.178 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 744.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |     3537 | 2024-05-04 | AMKAL             | L   | 0.352      | -            | -                | -                | -         |    -1.56 | adamb, Jackinho, nilo, susp, ztr    |
|           25 |     3553 | 2024-05-03 | Zero Tenacity     | W   | 0.346      | 0.435        | 0.163 (0.025)    | 1.000 (0.150)    | 0 (0.000) |     9.03 | adamb, Jackinho, nilo, susp, ztr    |
|           24 |     3573 | 2024-05-02 | Sangal            | W   | 0.340      | 0.435        | 0.248 (0.037)    | 0.878 (0.130)    | 0 (0.000) |    10.17 | adamb, Jackinho, nilo, susp, ztr    |
|           23 |     3734 | 2024-04-25 | Nexus             | L   | 0.294      | -            | -                | -                | -         |    -4.26 | adamb, Jackinho, nilo, susp, ztr    |
|           22 |     3776 | 2024-04-23 | Alliance          | W   | 0.280      | 0.384        | 0.014 (0.001)    | 0.363 (0.039)    | 0 (0.000) |     5.35 | adamb, Jackinho, nilo, p1ke, susp   |
|           21 |     3886 | 2024-04-19 | FURIA             | L   | 0.254      | -            | -                | -                | -         |    -0.06 | adamb, Jackinho, Plopski, susp, ztr |
|           20 |     3921 | 2024-04-18 | Imperial          | L   | 0.248      | -            | -                | -                | -         |    -1.15 | adamb, Jackinho, Plopski, susp, ztr |
|           19 |     4201 | 2024-04-09 | ex-Guild Eagles   | L   | 0.187      | -            | -                | -                | -         |    -3.21 | adamb, Jackinho, nilo, susp, ztr    |
|           18 |     4216 | 2024-04-08 | Aurora            | L   | 0.182      | -            | -                | -                | -         |    -0.15 | adamb, Jackinho, nilo, susp, ztr    |
|           17 |     4227 | 2024-04-08 | 9 Pandas          | L   | 0.180      | -            | -                | -                | -         |    -1.06 | adamb, Jackinho, nilo, susp, ztr    |
|           16 |     4254 | 2024-04-07 | EYEBALLERS        | W   | 0.174      | 0.330        | 0.003 (0.000)    | 0.298 (0.017)    | 0 (0.000) |     3.11 | adamb, Jackinho, nilo, susp, ztr    |
|           15 |     4263 | 2024-04-07 | Johnny Speeds     | W   | 0.172      | 0.330        | 0.102 (0.006)    | 0.956 (0.055)    | 0 (0.000) |     4.85 | adamb, Jackinho, nilo, susp, ztr    |
|           14 |     4279 | 2024-04-06 | Young Gods        | W   | 0.166      | 0.330        | 0.006 (0.000)    | 0.023 (0.001)    | 0 (0.000) |     2.06 | adamb, Jackinho, nilo, susp, ztr    |
|           13 |     4333 | 2024-04-04 | Ninjas in Pyjamas | L   | 0.153      | -            | -                | -                | -         |    -0.10 | adamb, Jackinho, nilo, susp, ztr    |
|           12 |     4362 | 2024-04-03 | Monte             | W   | 0.148      | 0.143        | 0.076 (0.002)    | 0.289 (0.006)    | 0 (0.000) |     3.47 | adamb, Jackinho, nilo, susp, ztr    |
|           11 |     4371 | 2024-04-03 | FAVBET            | W   | 0.147      | 0.143        | 0.002 (0.000)    | 0.655 (0.014)    | 0 (0.000) |     2.62 | adamb, Jackinho, nilo, susp, ztr    |
|           10 |     4403 | 2024-04-02 | B8                | W   | 0.141      | 0.143        | 0.176 (0.004)    | 1.000 (0.020)    | 0 (0.000) |     3.80 | adamb, Jackinho, nilo, susp, ztr    |
|            9 |     4411 | 2024-04-02 | Aurora            | L   | 0.140      | -            | -                | -                | -         |    -0.10 | adamb, Jackinho, nilo, susp, ztr    |
|            8 |     4425 | 2024-04-01 | PARIVISION        | L   | 0.134      | -            | -                | -                | -         |    -0.55 | adamb, Jackinho, nilo, susp, ztr    |
|            7 |     4493 | 2024-03-27 | Aurora            | L   | 0.102      | -            | -                | -                | -         |    -0.07 | adamb, Jackinho, nilo, susp, ztr    |
|            6 |     4499 | 2024-03-27 | NAVI Junior       | W   | 0.102      | 0.143        | -                | 0.144 (0.002)    | 0 (0.000) |     1.30 | adamb, Jackinho, nilo, susp, ztr    |
|            5 |     4702 | 2024-03-15 | kONO              | L   | 0.021      | -            | -                | -                | -         |    -0.26 | adamb, Jackinho, nilo, susp, ztr    |
|            4 |     4739 | 2024-03-14 | ALTERNATE aTTaX   | L   | 0.013      | -            | -                | -                | -         |    -0.07 | adamb, Jackinho, nilo, susp, ztr    |
|            3 |     4774 | 2024-03-13 | HEROIC            | L   | 0.007      | -            | -                | -                | -         |    -0.01 | adamb, Jackinho, nilo, susp, ztr    |
|            2 |     4797 | 2024-03-12 | B8                | W   | 0.002      | 0.143        | 0.176 (0.000)    | -                | -         |     0.04 | adamb, Jackinho, nilo, susp, ztr    |
|            1 |     4805 | 2024-03-12 | Apeks             | W   | 0.000      | -            | -                | -                | -         |     0.01 | adamb, Jackinho, nilo, susp, ztr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,147.34)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      0.354 | $5,000.00      | $1,770.83       |
| 2024-04-20 |      0.262 | $5,000.00      | $1,310.65       |
| 2024-04-07 |      0.174 | $6,110.00      | $1,065.86       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
