# ConcordeVPN — releases

Download mirror for [ConcordeVPN](https://github.com/bigmillz), the
bring-your-own-server VPN client for macOS in the Concorde family.
This repo carries only the published builds; the source lives in a
separate repository.

Every `.dmg` ships with a `.dmg.sha256`. Verify before installing:

```
shasum -a 256 -c ConcordeVPN-<version>.dmg.sha256
```

**macOS first launch** — the builds are not notarized. Open
System Settings › Privacy & Security, scroll to the message naming the
app, and click "Open Anyway". Once per version.

ConcordeVPN is bring-your-own-server: you run your own exit node (the
one-command installer is included with the app). It is not a hosted
subscription.

*Fly Concorde, Fly.*
