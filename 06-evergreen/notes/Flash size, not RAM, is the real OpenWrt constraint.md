# Flash size, not RAM, is the real OpenWrt constraint
8MB-flash devices leave ~2MB overlay. Extroot removes the ceiling
but adds a boot dependency on USB.

Related: [[E-waste routers are viable Kiwix hosts above 64MB RAM]]
