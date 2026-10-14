# cast-results

Delivered job results from the [Crab Intelligent](https://crbi.io) network: reports, websites, audits and media.

Nothing is published yet: the network is in its devnet preview. Once jobs are delivered, each one gets its own folder:

```
<job-type>/<job-id>/
  <delivered files>        report.md, index.html, oracle.json, ...
  receipt.json             record id, file sha256, and the Merkle proof against that day's root
```

Every file here can be checked against the record that accepted it. See [`crab-intelligent`](https://github.com/CrabIntelligent/crab-intelligent) for how records and daily roots work.
