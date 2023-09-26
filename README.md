
# GraphQL Frameworks Benchmark

A comparative analysis of several popular GraphQL frameworks:

- **Tailcall** - [GitHub](https://github.com/tailcallhq/tailcall)
- **gqlgen** - [GitHub](https://github.com/99designs/gqlgen)
- **Apollo Server** - [Official Docs](https://www.apollographql.com/docs/apollo-server/)
- **Netflix DGS** - [Official Docs](https://netflix.github.io/dgs/)
---
## Setting up the Benchmark

Kickstart your benchmarking environment with just one click:

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/tailcallhq/graphql-benchmarks)

---

## Execution

Once the post-creation setup in Codespaces is complete, initiate the benchmark tests using:

```bash
./run_benchmarks.sh
```

## Benchmark Results
<!-- PERFORMANCE_RESULTS_START -->
| Server | Requests/sec | Latency (ms) |
|--------|--------------:|--------------:|
| tailcall | `2,890.68` | `34.69` |
| gqlgen | `935.00` | `115.73` |
| apollo | `793.37` | `128.22` |
| netflixdgs | `597.39` | `191.85` |

<!-- PERFORMANCE_RESULTS_END -->

## Throughput (Higher is better)
![Throughput Histogram](assets/req_sec_histogram.png)

## Latency (Lower is better)
![Latency Histogram](assets/latency_histogram.png)
