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
# Warmup Iteration   1: 4.987 ops/ms
# Warmup Iteration   2: 12.048 ops/ms
# Warmup Iteration   3: 12.252 ops/ms
Iteration   1: 12.548 ops/ms
Iteration   2: 12.584 ops/ms
Iteration   3: 12.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.582 ±(99.9%) 0.596 ops/ms [Average]
  (min, avg, max) = (12.548, 12.582, 12.613), stdev = 0.033
  CI (99.9%): [11.985, 13.178] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.462 ops/ms
# Warmup Iteration   2: 13.026 ops/ms
# Warmup Iteration   3: 13.144 ops/ms
Iteration   1: 13.099 ops/ms
Iteration   2: 13.152 ops/ms
Iteration   3: 13.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.109 ±(99.9%) 0.707 ops/ms [Average]
  (min, avg, max) = (13.077, 13.109, 13.152), stdev = 0.039
  CI (99.9%): [12.403, 13.816] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.628 ops/ms
# Warmup Iteration   2: 12.477 ops/ms
# Warmup Iteration   3: 12.819 ops/ms
Iteration   1: 12.981 ops/ms
Iteration   2: 12.850 ops/ms
Iteration   3: 12.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.914 ±(99.9%) 1.195 ops/ms [Average]
  (min, avg, max) = (12.850, 12.914, 12.981), stdev = 0.065
  CI (99.9%): [11.719, 14.108] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.877 ops/ms
# Warmup Iteration   2: 10.548 ops/ms
# Warmup Iteration   3: 10.708 ops/ms
Iteration   1: 10.665 ops/ms
Iteration   2: 10.584 ops/ms
Iteration   3: 10.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.675 ±(99.9%) 1.749 ops/ms [Average]
  (min, avg, max) = (10.584, 10.675, 10.775), stdev = 0.096
  CI (99.9%): [8.925, 12.424] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.967 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.004 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
Iteration   3: 2.528 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.514 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (2.506, 2.514, 2.528), stdev = 0.012
  CI (99.9%): [2.298, 2.731] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.779 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.004 ms/op
Iteration   1: 2.447 ±(99.9%) 0.004 ms/op
Iteration   2: 2.431 ±(99.9%) 0.004 ms/op
Iteration   3: 2.421 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.433 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (2.421, 2.433, 2.447), stdev = 0.013
  CI (99.9%): [2.189, 2.677] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.768 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.004 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.477 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (2.468, 2.477, 2.493), stdev = 0.013
  CI (99.9%): [2.233, 2.721] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.834 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.005 ms/op
Iteration   1: 3.003 ±(99.9%) 0.005 ms/op
Iteration   2: 2.998 ±(99.9%) 0.005 ms/op
Iteration   3: 2.999 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.000 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (2.998, 3.000, 3.003), stdev = 0.003
  CI (99.9%): [2.944, 3.056] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.021 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.677 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.006 ms/op
Iteration   1: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.621 ms/op
                 createUser·p0.999:  11.880 ms/op
                 createUser·p0.9999: 14.189 ms/op
                 createUser·p1.00:   14.451 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.622 ms/op
                 createUser·p0.999:  8.738 ms/op
                 createUser·p0.9999: 12.143 ms/op
                 createUser·p1.00:   12.993 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  9.307 ms/op
                 createUser·p0.9999: 10.847 ms/op
                 createUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380140
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 184749 
    [ 2.500,  3.750) = 192010 
    [ 3.750,  5.000) = 2517 
    [ 5.000,  6.250) = 353 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.470 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 3.680 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  5.803 ms/op
                 existUser·p0.9999: 13.976 ms/op
                 existUser·p1.00:   15.155 ms/op

Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  6.775 ms/op
                 existUser·p0.9999: 14.538 ms/op
                 existUser·p1.00:   15.041 ms/op

Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.887 ms/op
                 existUser·p0.999:  7.938 ms/op
                 existUser·p0.9999: 11.862 ms/op
                 existUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391550
  mean =      2.450 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 194291 
    [ 2.500,  3.750) = 193687 
    [ 3.750,  5.000) = 2692 
    [ 5.000,  6.250) = 365 
    [ 6.250,  7.500) = 96 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      6.918 ms/op
     p(99.9900) =     13.929 ms/op
     p(99.9990) =     14.981 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 4.191 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.836 ms/op
                 getUser·p0.999:  11.751 ms/op
                 getUser·p0.9999: 13.931 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.703 ms/op
                 getUser·p0.999:  8.520 ms/op
                 getUser·p0.9999: 12.225 ms/op
                 getUser·p1.00:   13.156 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.645 ms/op
                 getUser·p0.999:  7.667 ms/op
                 getUser·p0.9999: 11.477 ms/op
                 getUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383659
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 190210 
    [ 2.500,  3.750) = 189695 
    [ 3.750,  5.000) = 3014 
    [ 5.000,  6.250) = 278 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      8.250 ms/op
     p(99.9900) =     13.331 ms/op
     p(99.9990) =     14.093 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 4.744 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.009 ms/op
Iteration   1: 3.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.748 ms/op
                 listUser·p0.9999: 11.190 ms/op
                 listUser·p1.00:   13.976 ms/op

Iteration   2: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.321 ms/op
                 listUser·p0.9999: 12.331 ms/op
                 listUser·p1.00:   12.960 ms/op

Iteration   3: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.787 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  10.584 ms/op
                 listUser·p0.9999: 14.239 ms/op
                 listUser·p1.00:   14.959 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316728
  mean =      3.028 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 87399 
    [ 2.500,  3.750) = 189070 
    [ 3.750,  5.000) = 33276 
    [ 5.000,  6.250) = 5667 
    [ 6.250,  7.500) = 504 
    [ 7.500,  8.750) = 192 
    [ 8.750, 10.000) = 212 
    [10.000, 11.250) = 172 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.769 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     14.808 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.582 ± 0.596  ops/ms
ClientPb.existUser                       thrpt       3  13.109 ± 0.707  ops/ms
ClientPb.getUser                         thrpt       3  12.914 ± 1.195  ops/ms
ClientPb.listUser                        thrpt       3  10.675 ± 1.749  ops/ms
ClientPb.createUser                       avgt       3   2.514 ± 0.217   ms/op
ClientPb.existUser                        avgt       3   2.433 ± 0.244   ms/op
ClientPb.getUser                          avgt       3   2.477 ± 0.244   ms/op
ClientPb.listUser                         avgt       3   3.000 ± 0.056   ms/op
ClientPb.createUser                     sample  380140   2.523 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.810           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.674           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.028           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.435           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.975           ms/op
ClientPb.existUser                      sample  391550   2.450 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.758           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.918           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.929           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.155           ms/op
ClientPb.getUser                        sample  383659   2.500 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.878           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.250           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.331           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.320           ms/op
ClientPb.listUser                       sample  316728   3.028 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.787           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.769           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.238           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.959           ms/op
