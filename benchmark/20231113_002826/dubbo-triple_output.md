# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.397 ops/ms
# Warmup Iteration   2: 11.804 ops/ms
# Warmup Iteration   3: 12.320 ops/ms
Iteration   1: 12.471 ops/ms
Iteration   2: 12.446 ops/ms
Iteration   3: 12.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.512 ±(99.9%) 1.700 ops/ms [Average]
  (min, avg, max) = (12.446, 12.512, 12.618), stdev = 0.093
  CI (99.9%): [10.812, 14.211] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 7.940 ops/ms
# Warmup Iteration   2: 12.810 ops/ms
# Warmup Iteration   3: 12.792 ops/ms
Iteration   1: 12.956 ops/ms
Iteration   2: 12.932 ops/ms
Iteration   3: 12.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.906 ±(99.9%) 1.219 ops/ms [Average]
  (min, avg, max) = (12.830, 12.906, 12.956), stdev = 0.067
  CI (99.9%): [11.687, 14.125] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.788 ops/ms
# Warmup Iteration   2: 12.634 ops/ms
# Warmup Iteration   3: 12.731 ops/ms
Iteration   1: 12.913 ops/ms
Iteration   2: 12.904 ops/ms
Iteration   3: 12.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.822 ±(99.9%) 2.723 ops/ms [Average]
  (min, avg, max) = (12.650, 12.822, 12.913), stdev = 0.149
  CI (99.9%): [10.100, 15.545] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.509 ops/ms
# Warmup Iteration   2: 10.423 ops/ms
# Warmup Iteration   3: 10.550 ops/ms
Iteration   1: 10.561 ops/ms
Iteration   2: 10.519 ops/ms
Iteration   3: 10.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.564 ±(99.9%) 0.853 ops/ms [Average]
  (min, avg, max) = (10.519, 10.564, 10.613), stdev = 0.047
  CI (99.9%): [9.711, 11.417] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.004 ms/op
Iteration   1: 2.556 ±(99.9%) 0.004 ms/op
Iteration   2: 2.538 ±(99.9%) 0.004 ms/op
Iteration   3: 2.573 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.556 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (2.538, 2.556, 2.573), stdev = 0.018
  CI (99.9%): [2.235, 2.876] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.712 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.004 ms/op
Iteration   1: 2.444 ±(99.9%) 0.004 ms/op
Iteration   2: 2.464 ±(99.9%) 0.003 ms/op
Iteration   3: 2.466 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.458 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.444, 2.458, 2.466), stdev = 0.012
  CI (99.9%): [2.237, 2.679] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.882 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.004 ms/op
Iteration   1: 2.498 ±(99.9%) 0.004 ms/op
Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.500 ±(99.9%) 0.048 ms/op [Average]
  (min, avg, max) = (2.498, 2.500, 2.503), stdev = 0.003
  CI (99.9%): [2.453, 2.548] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.585 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.005 ms/op
Iteration   1: 3.023 ±(99.9%) 0.005 ms/op
Iteration   2: 3.020 ±(99.9%) 0.005 ms/op
Iteration   3: 2.985 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.010 ±(99.9%) 0.384 ms/op [Average]
  (min, avg, max) = (2.985, 3.010, 3.023), stdev = 0.021
  CI (99.9%): [2.625, 3.394] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.262 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.508 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   4.096 ms/op
                 createUser·p0.999:  10.941 ms/op
                 createUser·p0.9999: 13.812 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.932 ms/op
                 createUser·p0.999:  9.798 ms/op
                 createUser·p0.9999: 12.538 ms/op
                 createUser·p1.00:   13.058 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   4.035 ms/op
                 createUser·p0.999:  7.930 ms/op
                 createUser·p0.9999: 9.671 ms/op
                 createUser·p1.00:   10.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382044
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 183911 
    [ 2.500,  3.750) = 192948 
    [ 3.750,  5.000) = 3949 
    [ 5.000,  6.250) = 713 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 95 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      4.014 ms/op
     p(99.9000) =      8.159 ms/op
     p(99.9900) =     13.284 ms/op
     p(99.9990) =     13.962 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  6.412 ms/op
                 existUser·p0.9999: 14.142 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   2.617 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  8.857 ms/op
                 existUser·p0.9999: 14.406 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   2.609 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  9.409 ms/op
                 existUser·p0.9999: 15.057 ms/op
                 existUser·p1.00:   15.434 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383645
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 186196 
    [ 2.500,  3.750) = 193136 
    [ 3.750,  5.000) = 2747 
    [ 5.000,  6.250) = 971 
    [ 6.250,  7.500) = 162 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 71 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     14.422 ms/op
     p(99.9990) =     15.319 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.924 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.544 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.378 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   5.186 ms/op
                 getUser·p0.999:  11.905 ms/op
                 getUser·p0.9999: 13.589 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   2: 2.688 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  10.044 ms/op
                 getUser·p0.9999: 14.126 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   3: 2.492 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   2.425 ms/op
                 getUser·p0.90:   3.154 ms/op
                 getUser·p0.95:   3.461 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  9.842 ms/op
                 getUser·p0.9999: 16.540 ms/op
                 getUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 372905
  mean =      2.572 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 188417 
    [ 2.500,  5.000) = 178768 
    [ 5.000,  7.500) = 5057 
    [ 7.500, 10.000) = 280 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.378 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.178 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     10.109 ms/op
     p(99.9900) =     14.359 ms/op
     p(99.9990) =     20.221 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.814 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.009 ms/op
Iteration   1: 3.076 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.779 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.678 ms/op
                 listUser·p0.999:  8.831 ms/op
                 listUser·p0.9999: 10.604 ms/op
                 listUser·p1.00:   11.665 ms/op

Iteration   2: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.617 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  9.874 ms/op
                 listUser·p0.9999: 12.009 ms/op
                 listUser·p1.00:   13.042 ms/op

Iteration   3: 2.956 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.733 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.765 ms/op
                 listUser·p0.9999: 11.780 ms/op
                 listUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318791
  mean =      3.009 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 273 
    [ 1.250,  2.500) = 99060 
    [ 2.500,  3.750) = 175109 
    [ 3.750,  5.000) = 37077 
    [ 5.000,  6.250) = 5640 
    [ 6.250,  7.500) = 868 
    [ 7.500,  8.750) = 295 
    [ 8.750, 10.000) = 242 
    [10.000, 11.250) = 152 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     11.686 ms/op
     p(99.9990) =     12.363 ms/op
     p(99.9999) =     13.042 ms/op
    p(100.0000) =     13.042 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.512 ± 1.700  ops/ms
ClientPb.existUser                       thrpt       3  12.906 ± 1.219  ops/ms
ClientPb.getUser                         thrpt       3  12.822 ± 2.723  ops/ms
ClientPb.listUser                        thrpt       3  10.564 ± 0.853  ops/ms
ClientPb.createUser                       avgt       3   2.556 ± 0.321   ms/op
ClientPb.existUser                        avgt       3   2.458 ± 0.221   ms/op
ClientPb.getUser                          avgt       3   2.500 ± 0.048   ms/op
ClientPb.listUser                         avgt       3   3.010 ± 0.384   ms/op
ClientPb.createUser                     sample  382044   2.511 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.871           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.159           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.284           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.008           ms/op
ClientPb.existUser                      sample  383645   2.500 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.847           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.593           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.733           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.422           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.434           ms/op
ClientPb.getUser                        sample  372905   2.572 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.378           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.604           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.997           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.109           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.359           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.051           ms/op
ClientPb.listUser                       sample  318791   3.009 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.617           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.686           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.042           ms/op
