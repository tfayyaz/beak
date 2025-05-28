# beak

--

Beak is a newsletter and open-source agent to help you learn about B2B SaaS Metrics

## Beak Agent

When you ask a business question beak first suggests some visuals that will help you understand your the data for question and will then build the required materialized table to make your future questions run faster.

It's built on DuckDB and follows the same principals that development should be fast and simple.

How it works:

```sh
beak -q "how many users do I have"

beak reframe q: "You should focus on improving MAU/WAU" accept [y/n]: y

beak viz search .../

3 viz found select [1, 2, 3]
1: Y Combintor

2: Menlo Ventures

3: Theory Ventures

user: 3

beak searching tables .../
found 1 table with suitable data to create visual
beak creating table .../
beak creating visual .../
```


