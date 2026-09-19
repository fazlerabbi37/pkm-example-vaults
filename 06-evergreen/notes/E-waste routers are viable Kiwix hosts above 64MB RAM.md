# E-waste routers are viable Kiwix hosts above 64MB RAM
(rev 3 — softened from "128MB" after TL-WR841 test on 2026-08-21)

kiwix-serve streams content from disk, so RAM bounds only the index.
64MB handled a 12GB mini ZIM in testing.

Related: [[Flash size, not RAM, is the real OpenWrt constraint]]
