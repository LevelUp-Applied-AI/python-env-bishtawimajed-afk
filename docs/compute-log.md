SYSTEM INFORMATION
==================================================
OS:         Windows 10
Version:    10.0.19045
Machine:    AMD64
Processor:  Intel64 Family 6 Model 140 Stepping 1, GenuineIntel
Python:     3.13.12 (tags/v3.13.12:1cbe481, Feb  3 2026, 18:22:25) [MSC v.1944 64 bit (AMD64)]

Benchmark 1 — sum(range(5,000,000))
  Result:  12,499,997,500,000
  Time:    0.0630 seconds

Benchmark 2 — list comprehension (n=1,000,000)
  First 5: [0, 1, 4, 9, 16]
  Time:    0.0620 seconds

Benchmark 3 — string join (n=100,000)
  Length:  588,889 characters
  Time:    0.0116 seconds

==================================================
SUMMARY
==================================================
  sum benchmark:    0.0630s
  list benchmark:   0.0620s
  string benchmark: 0.0116s

Total Ram is : 8
