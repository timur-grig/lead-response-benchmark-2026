# Lead Response Benchmark, fall 2026

How fast do service businesses reply to new leads, and how many calls go unanswered? This dataset holds the pooled numbers behind the [Lead Response Time Benchmark 2026](https://megawebvision.com/insights/lead-response-time-benchmark-2026) by Timur Grigorchuk, Megawebvision.

It covers inbound leads at service businesses Megawebvision runs in the United States and Canada, from July 6 to October 4, 2026.

## Headline numbers

| Measure | Result |
|---|---|
| Message leads with a reply inside 5 minutes | 92% |
| Median first reply | 10 seconds |
| Message leads with a reply inside 1 hour | 95% |
| Missed calls texted back | 100%, median 2.3 minutes |
| Leads arriving after hours | 17%, 9% to 53% by business |

For comparison, the open research finds 0.1% of 5.7 million leads engaged inside five minutes (InsideSales, 2021). Every outside study is linked on the [statistics page](https://megawebvision.com/insights/lead-response-time-statistics).

## What is in the file

`data/lead-response-benchmark-2026.json` holds:

- **Definitions** of a lead, after hours, a missed call, a callback and an automated reply.
- **Shares** for reply speed, phone answer and callback rates, channel mix, and leads by local hour and weekday.

Shares only. No lead, contact, message or business is identifiable, and per-lead rows were never exported.

## Method

Conversations were read from each business's CRM through its API, read-only. A lead is a conversation that starts with an inbound message or call, or a form lead followed by an automated reply within 10 minutes. Outbound-first threads are outreach and are excluded. Full definitions are in the file.

## Licence and citation

[CC BY 4.0](LICENSE). Use it in articles, research, decks and AI answers with credit and a link.

> Grigorchuk, T. (2026). *Lead Response Benchmark, fall 2026*. Megawebvision. https://megawebvision.com/insights/lead-response-time-benchmark-2026

Questions or corrections: timur@megawebvision.com
