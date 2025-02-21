| Name                 | Term. Cond.         |   Path Length |   Nodes Gen. |   Nodes Tested |   Nodes Discarded | Distinct States                 |   Time Taken |
|----------------------|---------------------|---------------|--------------|----------------|-------------------|---------------------------------|--------------|
| BF                   | NODE_LIMIT_EXCEEDED |               |       100001 |          22287 |                 0 | not recorded (loop_check=False) |     4.31617  |
| BF_LC                | GOAL_STATE_FOUND    |            15 |        18459 |           4698 |             12738 | 5721                            |     0.518506 |
| BF_LC_HEU1           | GOAL_STATE_FOUND    |            15 |        28068 |           7874 |             19164 | 8904                            |     0.861906 |
| BF_LC_COS1           | GOAL_STATE_FOUND    |            15 |        18459 |           4698 |             12738 | 5721                            |     0.486333 |
| BF_LC_HEU1+COS1      | GOAL_STATE_FOUND    |            15 |        23580 |           6136 |             16292 | 7288                            |     0.672402 |
| BF_LC_HEU1+COS1_RAND | GOAL_STATE_FOUND    |            15 |        23610 |           6143 |             16316 | 7294                            |     0.746205 |
| BF_LC_HEU2           | GOAL_STATE_FOUND    |            15 |        28068 |           7874 |             19164 | 8904                            |     0.840849 |
| BF_LC_HEU2+COS1      | GOAL_STATE_FOUND    |            15 |        23580 |           6136 |             16292 | 7288                            |     0.677458 |
| BF_LC_HEU2+COS1_RAND | GOAL_STATE_FOUND    |            15 |        23563 |           6132 |             16279 | 7284                            |     0.752811 |

| DF                   | NODE_LIMIT_EXCEEDED |               |       100001 |          18184 |                 0 | not recorded (loop_check=False) |    66.683    |
| DF_LC                | GOAL_STATE_FOUND    |           649 |         2792 |            658 |              1011 | 1781                            |     0.141257 |
| DF_LC_HEU1           | GOAL_STATE_FOUND    |           649 |         2792 |            658 |              1011 | 1781                            |     0.11648  |
| DF_LC_COS1           | GOAL_STATE_FOUND    |            15 |        18092 |           4599 |             12463 | 5629                            |    67.583    |
| DF_LC_HEU1+COS1      | GOAL_STATE_FOUND    |            15 |        18092 |           4599 |             12463 | 5629                            |     0.487376 |
| DF_LC_HEU1+COS1_RAND | GOAL_STATE_FOUND    |            15 |        18108 |           4604 |             12467 | 5641                            |     0.492602 |
| DF_LC_HEU2           | GOAL_STATE_FOUND    |           113 |        31142 |           8618 |             21441 | 9701                            |     1.05253  |
| DF_LC_HEU2+COS1      | GOAL_STATE_FOUND    |            15 |        24276 |           6347 |             16581 | 7695                            |     0.672521 |
| DF_LC_HEU2+COS1_RAND | GOAL_STATE_FOUND    |            15 |        24446 |           6385 |             16752 | 7694                            |     0.750701 |