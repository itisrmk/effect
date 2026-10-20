---
"effect": patch
---

`Duration.toHrTime` keeps the nanosecond component in `0` through `999_999_999` for negative durations, carrying the sign on the seconds component.
