# mermaid-sample
mermaid sample

## Flowchart
```mermaid
flowchart LR
    test
```

```mermaid
graph TD
    Get-->wild
    wild-->and
    and-->chart
```

## Gantt Chart

```mermaid
gantt
  Get   :  done,    t1, 2022-02-17, 3d
  wild. :  active,  t2, after t1,   3d
  and   :           t3, after t2,   1d
  chart :                           3d
```


# Reference
- https://mermaid-js.github.io/mermaid/
- https://dev.classmethod.jp/articles/mermaid-markdown-is-supported-in-notion/
- https://github.com/amane-uehara/how-to-use-mermaid
- https://zenn.dev/yasuhiroki/articles/dd0feae790ba41
