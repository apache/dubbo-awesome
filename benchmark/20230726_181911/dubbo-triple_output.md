# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.479 ops/ms
# Warmup Iteration   2: 3.373 ops/ms
# Warmup Iteration   3: 6.181 ops/ms
Iteration   1: 7.519 ops/ms
Iteration   2: 8.420 ops/ms
Iteration   3: 8.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.990 ±(99.9%) 8.251 ops/ms [Average]
  (min, avg, max) = (7.519, 7.990, 8.420), stdev = 0.452
  CI (99.9%): [≈ 0, 16.241] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 2.066 ops/ms
# Warmup Iteration   2: 7.022 ops/ms
# Warmup Iteration   3: 8.540 ops/ms
Iteration   1: 9.007 ops/ms
Iteration   2: 8.530 ops/ms
Iteration   3: 8.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.784 ±(99.9%) 4.379 ops/ms [Average]
  (min, avg, max) = (8.530, 8.784, 9.007), stdev = 0.240
  CI (99.9%): [4.405, 13.163] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.291 ops/ms
# Warmup Iteration   2: 6.258 ops/ms
# Warmup Iteration   3: 7.729 ops/ms
Iteration   1: 8.487 ops/ms
Iteration   2: 7.920 ops/ms
Iteration   3: 8.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.177 ±(99.9%) 5.243 ops/ms [Average]
  (min, avg, max) = (7.920, 8.177, 8.487), stdev = 0.287
  CI (99.9%): [2.934, 13.421] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.500 ops/ms
# Warmup Iteration   2: 5.499 ops/ms
# Warmup Iteration   3: 7.045 ops/ms
Iteration   1: 7.124 ops/ms
Iteration   2: 7.396 ops/ms
Iteration   3: 7.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.237 ±(99.9%) 2.589 ops/ms [Average]
  (min, avg, max) = (7.124, 7.237, 7.396), stdev = 0.142
  CI (99.9%): [4.648, 9.826] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 13.130 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.795 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.023 ms/op
Iteration   1: 3.980 ±(99.9%) 0.012 ms/op
Iteration   2: 4.091 ±(99.9%) 0.008 ms/op
Iteration   3: 3.645 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.905 ±(99.9%) 4.237 ms/op [Average]
  (min, avg, max) = (3.645, 3.905, 4.091), stdev = 0.232
  CI (99.9%): [≈ 0, 8.143] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.640 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.718 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.804 ±(99.9%) 0.013 ms/op
Iteration   1: 3.565 ±(99.9%) 0.016 ms/op
Iteration   2: 3.549 ±(99.9%) 0.008 ms/op
Iteration   3: 3.526 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.547 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (3.526, 3.547, 3.565), stdev = 0.020
  CI (99.9%): [3.188, 3.906] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 12.631 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.856 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.008 ms/op
Iteration   1: 3.968 ±(99.9%) 0.009 ms/op
Iteration   2: 3.682 ±(99.9%) 0.015 ms/op
Iteration   3: 3.921 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.857 ±(99.9%) 2.799 ms/op [Average]
  (min, avg, max) = (3.682, 3.857, 3.968), stdev = 0.153
  CI (99.9%): [1.058, 6.656] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 14.016 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 6.555 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.662 ±(99.9%) 0.008 ms/op
Iteration   1: 4.569 ±(99.9%) 0.008 ms/op
Iteration   2: 4.339 ±(99.9%) 0.030 ms/op
Iteration   3: 4.554 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.487 ±(99.9%) 2.351 ms/op [Average]
  (min, avg, max) = (4.339, 4.487, 4.569), stdev = 0.129
  CI (99.9%): [2.136, 6.839] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 12.574 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 5.944 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.425 ±(99.9%) 0.019 ms/op
Iteration   1: 3.846 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.964 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   7.356 ms/op
                 createUser·p0.999:  10.680 ms/op
                 createUser·p0.9999: 24.041 ms/op
                 createUser·p1.00:   24.674 ms/op

Iteration   2: 3.835 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.864 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   7.561 ms/op
                 createUser·p0.999:  19.398 ms/op
                 createUser·p0.9999: 22.500 ms/op
                 createUser·p1.00:   23.265 ms/op

Iteration   3: 3.692 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  12.751 ms/op
                 createUser·p0.9999: 20.928 ms/op
                 createUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 253283
  mean =      3.790 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 804 
    [ 2.500,  5.000) = 241890 
    [ 5.000,  7.500) = 8755 
    [ 7.500, 10.000) = 1264 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     16.761 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     24.052 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 11.607 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.010 ms/op
Iteration   1: 3.780 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.722 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   5.046 ms/op
                 existUser·p0.99:   7.167 ms/op
                 existUser·p0.999:  12.632 ms/op
                 existUser·p0.9999: 22.824 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   2: 3.530 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.694 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   6.873 ms/op
                 existUser·p0.999:  15.356 ms/op
                 existUser·p0.9999: 21.344 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   3: 3.623 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.929 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   6.873 ms/op
                 existUser·p0.999:  11.289 ms/op
                 existUser·p0.9999: 23.462 ms/op
                 existUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 263414
  mean =      3.641 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 375 
    [ 2.500,  5.000) = 252808 
    [ 5.000,  7.500) = 8578 
    [ 7.500, 10.000) = 1239 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     13.061 ms/op
     p(99.9900) =     22.926 ms/op
     p(99.9990) =     24.070 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 12.912 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.145 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.307 ±(99.9%) 0.018 ms/op
Iteration   1: 3.745 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.767 ms/op
                 getUser·p0.50:   3.602 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.845 ms/op
                 getUser·p0.999:  9.987 ms/op
                 getUser·p0.9999: 19.905 ms/op
                 getUser·p1.00:   21.135 ms/op

Iteration   2: 3.842 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   7.381 ms/op
                 getUser·p0.999:  10.322 ms/op
                 getUser·p0.9999: 19.104 ms/op
                 getUser·p1.00:   20.218 ms/op

Iteration   3: 3.959 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.933 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.784 ms/op
                 getUser·p0.95:   5.652 ms/op
                 getUser·p0.99:   7.758 ms/op
                 getUser·p0.999:  19.890 ms/op
                 getUser·p0.9999: 22.706 ms/op
                 getUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 249452
  mean =      3.847 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 323 
    [ 2.500,  5.000) = 234242 
    [ 5.000,  7.500) = 12671 
    [ 7.500, 10.000) = 1702 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     14.219 ms/op
     p(99.9900) =     21.070 ms/op
     p(99.9990) =     23.217 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.871 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 5.555 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.837 ±(99.9%) 0.017 ms/op
Iteration   1: 4.644 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.692 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   2: 4.619 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   6.439 ms/op
                 listUser·p0.99:   8.667 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 19.595 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   3: 4.777 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.825 ms/op
                 listUser·p0.95:   7.021 ms/op
                 listUser·p0.99:   9.421 ms/op
                 listUser·p0.999:  14.780 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205088
  mean =      4.679 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 170850 
    [ 5.000,  7.500) = 28430 
    [ 7.500, 10.000) = 4638 
    [10.000, 12.500) = 560 
    [12.500, 15.000) = 225 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.352 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      6.660 ms/op
     p(99.0000) =      8.880 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     20.993 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.990 ± 8.251  ops/ms
ClientPb.existUser                       thrpt       3   8.784 ± 4.379  ops/ms
ClientPb.getUser                         thrpt       3   8.177 ± 5.243  ops/ms
ClientPb.listUser                        thrpt       3   7.237 ± 2.589  ops/ms
ClientPb.createUser                       avgt       3   3.905 ± 4.237   ms/op
ClientPb.existUser                        avgt       3   3.547 ± 0.359   ms/op
ClientPb.getUser                          avgt       3   3.857 ± 2.799   ms/op
ClientPb.listUser                         avgt       3   4.487 ± 2.351   ms/op
ClientPb.createUser                     sample  253283   3.790 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.509           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.342           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.833           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.004           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.761           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.069           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.674           ms/op
ClientPb.existUser                      sample  263414   3.641 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.694           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.588           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.906           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.061           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.926           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.707           ms/op
ClientPb.getUser                        sample  249452   3.847 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.458           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.650           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.267           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.219           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.070           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.527           ms/op
ClientPb.listUser                       sample  205088   4.679 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.352           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.660           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.880           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.876           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.857           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.070           ms/op
