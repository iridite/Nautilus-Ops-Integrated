# Repository Coverage

[Full report](https://htmlpreview.github.io/?https://github.com/iridite/Nautilus-Ops-Integrated/blob/python-coverage-comment-action-data/htmlcov/index.html)

| Name                                                      |    Stmts |     Miss |      Cover |   Missing |
|---------------------------------------------------------- | -------: | -------: | ---------: | --------: |
| backtest/\_\_init\_\_.py                                  |        0 |        0 |    100.00% |           |
| backtest/engine\_high.py                                  |      732 |      577 |     21.17% |85-103, 110-125, 130-138, 155-187, 205-210, 233-250, 283-326, 352-357, 372-379, 397-404, 420-444, 464-469, 484-485, 499-504, 519-530, 558-565, 577-601, 625-651, 662-665, 676-684, 697-947, 952, 963-995, 1006-1011, 1016-1024, 1046-1050, 1055-1058, 1073-1079, 1084-1085, 1090-1098, 1103-1108, 1113-1120, 1125-1135, 1162-1199, 1227-1258, 1274-1345, 1350-1352, 1357-1370, 1375, 1394-1397, 1414-1455, 1465, 1470-1471, 1476-1478, 1486-1497, 1513-1520, 1531-1580, 1616-1631, 1667, 1683, 1698-1710, 1715-1726, 1731-1737, 1757-1774, 1779-1780, 1791-1800, 1810-1827, 1868-1901, 1924-1937, 1954-1979, 2003-2042 |
| backtest/engine\_low.py                                   |      444 |      369 |     16.89% |78, 85, 98-159, 163, 174-175, 180-182, 189-203, 214-258, 265-302, 326-343, 348-355, 360-372, 377-380, 385-389, 405-409, 414-416, 421-425, 430-432, 437-455, 469-495, 510-554, 559-565, 570-580, 585-601, 606-622, 638-680, 685-718, 723-805, 810-855, 862-914, 921-957, 962-969, 987-1026 |
| backtest/funding\_data\_client.py                         |        8 |        8 |      0.00% |      5-31 |
| backtest/tui\_manager.py                                  |      140 |       83 |     40.71% |56-74, 78-82, 86, 90, 94-110, 119-130, 134-147, 151-155, 159-163, 167-188, 192-193, 197-209, 213-226, 230-231, 236-240, 244-245, 249-250 |
| cli/\_\_init\_\_.py                                       |        2 |        0 |    100.00% |           |
| cli/commands.py                                           |      125 |       62 |     50.40% |30, 36, 53-54, 68-69, 74, 105-106, 114, 121-124, 129-132, 137-225 |
| config/constants.py                                       |       62 |        0 |    100.00% |           |
| core/\_\_init\_\_.py                                      |        5 |        0 |    100.00% |           |
| core/adapter.py                                           |      347 |      206 |     40.63% |115, 119, 128-132, 148-152, 234, 251, 262-285, 298, 311-320, 334-335, 345-346, 348, 351-353, 367-371, 381-383, 387-397, 401-415, 419-427, 433-449, 453-459, 463-480, 501-503, 515-528, 550-558, 564-565, 569-574, 583-586, 600-610, 614-632, 636-652, 658-743, 747-765, 769-772 |
| core/config\_validator.py                                 |      110 |      110 |      0.00% |    10-213 |
| core/exceptions.py                                        |      128 |       17 |     86.72% |125-126, 199, 264, 307, 361, 391-394, 427, 475-480 |
| core/loader.py                                            |      137 |       61 |     55.47% |56-57, 87-88, 114-115, 168, 176, 181-186, 248-263, 269-276, 280-290, 294-300, 306-313, 322-335, 341, 356-368 |
| core/schemas.py                                           |      436 |       84 |     80.73% |99-100, 120, 178, 222-224, 228-239, 243-244, 248-251, 255-256, 260-262, 281-286, 357-358, 362-367, 371-376, 380-383, 387-390, 447-449, 601-604, 610-612, 672, 706, 715, 787, 790, 801-803, 810, 821, 854-856, 860-864, 868-872 |
| langgraph/\_\_init\_\_.py                                 |        0 |        0 |    100.00% |           |
| langgraph/application/\_\_init\_\_.py                     |        0 |        0 |    100.00% |           |
| langgraph/application/interfaces/\_\_init\_\_.py          |        0 |        0 |    100.00% |           |
| langgraph/application/interfaces/llm\_service.py          |        2 |        2 |      0.00% |       3-6 |
| langgraph/application/interfaces/strategy\_repository.py  |        3 |        3 |      0.00% |       3-7 |
| langgraph/application/use\_cases/\_\_init\_\_.py          |        0 |        0 |    100.00% |           |
| langgraph/application/use\_cases/generate\_strategy.py    |       21 |       21 |      0.00% |      3-63 |
| langgraph/domain/\_\_init\_\_.py                          |        0 |        0 |    100.00% |           |
| langgraph/domain/models/\_\_init\_\_.py                   |        0 |        0 |    100.00% |           |
| langgraph/domain/models/optimization.py                   |       55 |       55 |      0.00% |     6-151 |
| langgraph/domain/models/strategy.py                       |       58 |       58 |      0.00% |     7-143 |
| langgraph/infrastructure/\_\_init\_\_.py                  |        0 |        0 |    100.00% |           |
| langgraph/infrastructure/agents/\_\_init\_\_.py           |        6 |        6 |      0.00% |       3-9 |
| langgraph/infrastructure/agents/base.py                   |       20 |       20 |      0.00% |      3-77 |
| langgraph/infrastructure/agents/coordinator.py            |       49 |       49 |      0.00% |     3-134 |
| langgraph/infrastructure/agents/optimizer.py              |       60 |       60 |      0.00% |     3-157 |
| langgraph/infrastructure/agents/researcher.py             |       43 |       43 |      0.00% |     3-107 |
| langgraph/infrastructure/agents/validator.py              |       57 |       57 |      0.00% |     3-148 |
| langgraph/infrastructure/backtest/engine.py               |      105 |      105 |      0.00% |     3-321 |
| langgraph/infrastructure/cache/\_\_init\_\_.py            |        2 |        2 |      0.00% |       3-5 |
| langgraph/infrastructure/cache/llm\_cache.py              |       68 |       68 |      0.00% |     3-186 |
| langgraph/infrastructure/code\_gen/\_\_init\_\_.py        |        0 |        0 |    100.00% |           |
| langgraph/infrastructure/code\_gen/strategy\_generator.py |       88 |       88 |      0.00% |     3-169 |
| langgraph/infrastructure/database/\_\_init\_\_.py         |        0 |        0 |    100.00% |           |
| langgraph/infrastructure/database/models.py               |       43 |       43 |      0.00% |      3-68 |
| langgraph/infrastructure/database/repositories.py         |       94 |       94 |      0.00% |     3-283 |
| langgraph/infrastructure/graph/\_\_init\_\_.py            |       12 |       12 |      0.00% |      3-26 |
| langgraph/infrastructure/graph/\_config.py                |       11 |       11 |      0.00% |      3-34 |
| langgraph/infrastructure/graph/\_error\_handling.py       |       54 |       54 |      0.00% |     6-113 |
| langgraph/infrastructure/graph/\_import\_utils.py         |       17 |       17 |      0.00% |      3-39 |
| langgraph/infrastructure/graph/checkpoint.py              |       88 |       88 |      0.00% |     3-246 |
| langgraph/infrastructure/graph/optimize\_graph.py         |      128 |      128 |      0.00% |     3-328 |
| langgraph/infrastructure/graph/research\_graph.py         |       91 |       91 |      0.00% |     3-248 |
| langgraph/infrastructure/graph/state.py                   |       11 |       11 |      0.00% |      3-30 |
| langgraph/infrastructure/llm/\_\_init\_\_.py              |        0 |        0 |    100.00% |           |
| langgraph/infrastructure/llm/claude\_client.py            |       57 |       57 |      0.00% |     3-193 |
| langgraph/infrastructure/llm/prompt\_templates.py         |       47 |       47 |      0.00% |     3-264 |
| langgraph/infrastructure/observability/\_\_init\_\_.py    |        3 |        3 |      0.00% |      7-18 |
| langgraph/infrastructure/observability/metrics.py         |      121 |      121 |      0.00% |    10-279 |
| langgraph/infrastructure/observability/tracing.py         |       55 |       55 |      0.00% |     7-183 |
| langgraph/shared/\_\_init\_\_.py                          |        0 |        0 |    100.00% |           |
| langgraph/shared/config.py                                |       36 |       36 |      0.00% |     3-107 |
| langgraph/shared/exceptions.py                            |       18 |       18 |      0.00% |      3-92 |
| langgraph/shared/logging.py                               |       38 |       38 |      0.00% |     3-124 |
| live/\_\_init\_\_.py                                      |        0 |        0 |    100.00% |           |
| live/circuit\_breaker.py                                  |       55 |       55 |      0.00% |    10-228 |
| live/funding\_rate\_monitor.py                            |       71 |       71 |      0.00% |     7-245 |
| strategy/\_\_init\_\_.py                                  |        2 |        0 |    100.00% |           |
| strategy/common/\_\_init\_\_.py                           |        0 |        0 |    100.00% |           |
| strategy/common/arbitrage/\_\_init\_\_.py                 |        4 |        0 |    100.00% |           |
| strategy/common/arbitrage/basis\_calculator.py            |       17 |        0 |    100.00% |           |
| strategy/common/arbitrage/delta\_manager.py               |       20 |        0 |    100.00% |           |
| strategy/common/arbitrage/position\_tracker.py            |       59 |        2 |     96.61% |   95, 120 |
| strategy/common/indicators/\_\_init\_\_.py                |        5 |        0 |    100.00% |           |
| strategy/common/indicators/dual\_thrust.py                |       35 |        0 |    100.00% |           |
| strategy/common/indicators/keltner\_channel.py            |       62 |        3 |     95.16% |113, 130, 156 |
| strategy/common/indicators/market\_regime.py              |       50 |       15 |     70.00% |91, 102-110, 119, 128-135 |
| strategy/common/indicators/relative\_strength.py          |       65 |       16 |     75.38% |62, 76, 88, 90, 97, 116, 122, 129, 133, 152, 157, 162, 178-179, 191-192 |
| strategy/common/signals/\_\_init\_\_.py                   |        3 |        0 |    100.00% |           |
| strategy/common/signals/dual\_thrust\_signals.py          |       19 |        0 |    100.00% |           |
| strategy/common/signals/entry\_exit\_signals.py           |      101 |       47 |     53.47% |56, 76, 95-98, 117-124, 155-162, 232, 255, 275-279, 294-307, 323-328, 345-349, 353-354, 394, 396, 409, 421 |
| strategy/common/universe/\_\_init\_\_.py                  |        2 |        0 |    100.00% |           |
| strategy/common/universe/dynamic\_universe.py             |       59 |       16 |     72.88% |33-40, 84, 94-95, 124, 129, 148, 156, 160, 164 |
| strategy/core/base.py                                     |      311 |      245 |     21.22% |93-100, 108-120, 130-133, 137-176, 183-192, 200-209, 213-216, 220-225, 229, 233, 262-276, 280-296, 300-303, 309-322, 326-330, 333-347, 353-359, 363-368, 372-377, 381-384, 404-424, 430-449, 463-466, 474-498, 509, 519-536, 540-545, 553-571, 575, 579, 586-600, 604-609, 637-661 |
| strategy/core/dependency\_checker.py                      |       77 |        4 |     94.81% |18-19, 36-37 |
| strategy/dual\_thrust.py                                  |       66 |       43 |     34.85% |50-62, 65-71, 75-105, 116-121, 125-134, 138-147, 157-168 |
| strategy/funding\_arbitrage.py                            |      274 |      274 |      0.00% |    13-683 |
| strategy/spot\_futures\_arbitrage.py                      |      233 |      186 |     20.17% |88-107, 111-154, 159-179, 183-214, 221-240, 247-271, 278-336, 345-389, 397-407, 411-429, 435-450, 455-483, 490-491, 495-521, 530-557 |
| utils/\_\_init\_\_.py                                     |       12 |        0 |    100.00% |           |
| utils/custom\_data.py                                     |       46 |        0 |    100.00% |           |
| utils/data\_file\_checker.py                              |       38 |        5 |     86.84% |     50-55 |
| utils/data\_management/\_\_init\_\_.py                    |        7 |        0 |    100.00% |           |
| utils/data\_management/data\_cache.py                     |       68 |       27 |     60.29% |45-49, 64-66, 74-80, 91-103, 112-117 |
| utils/data\_management/data\_fetcher.py                   |      115 |       94 |     18.26% |34-46, 75, 103-177, 202-251, 263, 274-291, 298-299, 319-329 |
| utils/data\_management/data\_limits.py                    |       41 |        0 |    100.00% |           |
| utils/data\_management/data\_loader.py                    |      373 |      254 |     31.90% |137-143, 148, 158-159, 164-179, 186-201, 225-230, 237-250, 263-274, 285-287, 329-359, 364-417, 438-443, 450-460, 465-469, 481-490, 503-512, 540-561, 589-616, 634-643, 661-685, 704-705, 731-735, 757, 783-793, 832, 849-850, 864-867, 872-892, 897-911, 918, 925-928, 933-938, 946-956, 994-1029, 1070-1083 |
| utils/data\_management/data\_manager.py                   |      210 |       72 |     65.71% |36-65, 117, 120, 134, 158, 164, 175, 205, 227, 334, 353-361, 381-393, 419, 424, 432-436, 460, 484, 491, 496-502, 507-509, 525-556 |
| utils/data\_management/data\_retrieval.py                 |      428 |      108 |     74.77% |107, 136-137, 141-147, 156-162, 181-187, 233-277, 320, 322, 326-329, 333, 365, 382, 391, 427-429, 453, 464, 468, 485, 517-522, 525, 550, 556, 580, 588-593, 596, 619, 630, 634, 651, 683-688, 691, 710-716, 719-720, 730-734, 743, 777-783, 811, 847, 879-880, 948-950 |
| utils/data\_management/data\_validator.py                 |      258 |       63 |     75.58% |57, 74, 112, 126, 143, 197, 208, 219, 234, 298, 314, 335, 364, 368, 429, 455-459, 471, 480, 493, 511, 515-516, 523, 533-592 |
| utils/exceptions.py                                       |        2 |        0 |    100.00% |           |
| utils/filename\_parser.py                                 |       25 |        0 |    100.00% |           |
| utils/instrument\_helpers.py                              |      120 |        5 |     95.83% |94, 100, 112, 145, 263 |
| utils/instrument\_loader.py                               |       50 |       37 |     26.00% |14-15, 20-21, 26-42, 47-54, 59-69, 82-97 |
| utils/logging\_config.py                                  |       24 |       24 |      0.00% |      8-52 |
| utils/network.py                                          |       23 |        3 |     86.96% |     92-94 |
| utils/oi\_funding\_adapter.py                             |      174 |       57 |     67.24% |67-71, 178-182, 199, 313-330, 356-363, 391-418, 423-430, 445-451, 468-472, 497-530 |
| utils/path\_helpers.py                                    |       13 |        0 |    100.00% |           |
| utils/performance/\_\_init\_\_.py                         |        4 |        0 |    100.00% |           |
| utils/performance/analyzer.py                             |       80 |       19 |     76.25% |66, 100, 115-116, 145, 174, 189, 219-238, 274, 277, 280, 286, 295-296 |
| utils/performance/metrics.py                              |      114 |       15 |     86.84% |49, 64, 68, 74, 141, 162, 191, 244, 250, 265, 271, 285-288, 300 |
| utils/performance/report.py                               |       87 |       34 |     60.92% |117, 246-250, 266-288, 312, 369-434 |
| utils/symbol\_parser.py                                   |      173 |       40 |     76.88% |57, 68, 140-150, 173, 185, 191, 202, 211, 316, 327, 370, 397-398, 435, 475, 500-545, 564-587 |
| utils/time\_helpers.py                                    |       42 |        1 |     97.62% |       131 |
| utils/universe.py                                         |       85 |       10 |     88.24% |137-139, 171-174, 179-180, 190-192 |
| **TOTAL**                                                 | **8439** | **4983** | **40.95%** |           |


## Setup coverage badge

Below are examples of the badges you can use in your main branch `README` file.

### Direct image

[![Coverage badge](https://raw.githubusercontent.com/iridite/Nautilus-Ops-Integrated/python-coverage-comment-action-data/badge.svg)](https://htmlpreview.github.io/?https://github.com/iridite/Nautilus-Ops-Integrated/blob/python-coverage-comment-action-data/htmlcov/index.html)

This is the one to use if your repository is private or if you don't want to customize anything.

### [Shields.io](https://shields.io) Json Endpoint

[![Coverage badge](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/iridite/Nautilus-Ops-Integrated/python-coverage-comment-action-data/endpoint.json)](https://htmlpreview.github.io/?https://github.com/iridite/Nautilus-Ops-Integrated/blob/python-coverage-comment-action-data/htmlcov/index.html)

Using this one will allow you to [customize](https://shields.io/endpoint) the look of your badge.
It won't work with private repositories. It won't be refreshed more than once per five minutes.

### [Shields.io](https://shields.io) Dynamic Badge

[![Coverage badge](https://img.shields.io/badge/dynamic/json?color=brightgreen&label=coverage&query=%24.message&url=https%3A%2F%2Fraw.githubusercontent.com%2Firidite%2FNautilus-Ops-Integrated%2Fpython-coverage-comment-action-data%2Fendpoint.json)](https://htmlpreview.github.io/?https://github.com/iridite/Nautilus-Ops-Integrated/blob/python-coverage-comment-action-data/htmlcov/index.html)

This one will always be the same color. It won't work for private repos. I'm not even sure why we included it.

## What is that?

This branch is part of the
[python-coverage-comment-action](https://github.com/marketplace/actions/python-coverage-comment)
GitHub Action. All the files in this branch are automatically generated and may be
overwritten at any moment.