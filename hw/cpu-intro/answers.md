# OSTEP Ch.4 Homework Answers

## Q1
- Prediction / 预测:
```text
Time  PID: 0  PID: 1  CPU  I/Os
1     RUN:cpu READY    1
2     RUN:cpu READY    1
3     RUN:cpu READY    1
4     RUN:cpu READY    1
5     RUN:cpu READY    1
6     READY   RUN:cpu  1
7     READY   RUN:cpu  1
8     READY   RUN:cpu  1
9     READY   RUN:cpu  1
10    READY   RUN:cpu  1
Total Time: 10
CPU Busy: 10 (100.00%)

Reasoning / 理由: Both processes (PID 0 and PID 1) have 5 CPU-only instructions (5:100). Since there is no I/O, the CPU executes them sequentially without any idle time. PID 0 runs for 5 ticks, then PID 1 runs for 5 ticks, taking a total of 10 ticks with 100% CPU utilization.

Verified result / 验证结果: (Will be filled in the 2nd commit)

Analysis / 分析: (Will be filled in the 2nd commit)
