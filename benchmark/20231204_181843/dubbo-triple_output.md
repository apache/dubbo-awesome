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
# Warmup Iteration   1: 4.966 ops/ms
# Warmup Iteration   2: 12.039 ops/ms
# Warmup Iteration   3: 12.277 ops/ms
Iteration   1: 12.524 ops/ms
Iteration   2: 12.714 ops/ms
Iteration   3: 12.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.605 ±(99.9%) 1.779 ops/ms [Average]
  (min, avg, max) = (12.524, 12.605, 12.714), stdev = 0.098
  CI (99.9%): [10.826, 14.385] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.375 ops/ms
# Warmup Iteration   2: 13.068 ops/ms
# Warmup Iteration   3: 13.012 ops/ms
Iteration   1: 13.031 ops/ms
Iteration   2: 13.015 ops/ms
Iteration   3: 13.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.046 ±(99.9%) 0.743 ops/ms [Average]
  (min, avg, max) = (13.015, 13.046, 13.092), stdev = 0.041
  CI (99.9%): [12.303, 13.789] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.664 ops/ms
# Warmup Iteration   2: 12.404 ops/ms
# Warmup Iteration   3: 12.709 ops/ms
Iteration   1: 12.746 ops/ms
Iteration   2: 12.798 ops/ms
Iteration   3: 12.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.756 ±(99.9%) 0.683 ops/ms [Average]
  (min, avg, max) = (12.725, 12.756, 12.798), stdev = 0.037
  CI (99.9%): [12.074, 13.439] (assumes normal distribution)


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
# Warmup Iteration   1: 6.373 ops/ms
# Warmup Iteration   2: 10.468 ops/ms
# Warmup Iteration   3: 10.499 ops/ms
Iteration   1: 10.694 ops/ms
Iteration   2: 10.594 ops/ms
Iteration   3: 10.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.674 ±(99.9%) 1.315 ops/ms [Average]
  (min, avg, max) = (10.594, 10.674, 10.733), stdev = 0.072
  CI (99.9%): [9.359, 11.989] (assumes normal distribution)


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
# Warmup Iteration   1: 4.137 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.568 ±(99.9%) 0.004 ms/op
Iteration   1: 2.569 ±(99.9%) 0.004 ms/op
Iteration   2: 2.533 ±(99.9%) 0.004 ms/op
Iteration   3: 2.559 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.554 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (2.533, 2.554, 2.569), stdev = 0.019
  CI (99.9%): [2.214, 2.894] (assumes normal distribution)


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
# Warmup Iteration   1: 3.664 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.484 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (2.470, 2.484, 2.493), stdev = 0.012
  CI (99.9%): [2.262, 2.706] (assumes normal distribution)


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
# Warmup Iteration   1: 4.212 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.666 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.593 ±(99.9%) 0.004 ms/op
Iteration   1: 2.593 ±(99.9%) 0.005 ms/op
Iteration   2: 2.570 ±(99.9%) 0.004 ms/op
Iteration   3: 2.578 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.580 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.570, 2.580, 2.593), stdev = 0.012
  CI (99.9%): [2.370, 2.791] (assumes normal distribution)


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
# Warmup Iteration   1: 4.948 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
Iteration   1: 3.087 ±(99.9%) 0.005 ms/op
Iteration   2: 3.039 ±(99.9%) 0.007 ms/op
Iteration   3: 3.081 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.069 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.039, 3.069, 3.087), stdev = 0.026
  CI (99.9%): [2.597, 3.541] (assumes normal distribution)


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
# Warmup Iteration   1: 4.255 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.006 ms/op
Iteration   1: 2.547 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.960 ms/op
                 createUser·p0.999:  11.056 ms/op
                 createUser·p0.9999: 13.295 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  9.977 ms/op
                 createUser·p0.9999: 15.457 ms/op
                 createUser·p1.00:   16.597 ms/op

Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  9.159 ms/op
                 createUser·p0.9999: 11.994 ms/op
                 createUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376478
  mean =      2.547 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 178816 
    [ 2.500,  3.750) = 191638 
    [ 3.750,  5.000) = 4857 
    [ 5.000,  6.250) = 672 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 142 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      4.067 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     16.457 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.558 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.121 ms/op
                 existUser·p0.95:   3.232 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  12.435 ms/op
                 existUser·p0.9999: 18.104 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.707 ms/op
                 existUser·p0.50:   2.626 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   4.026 ms/op
                 existUser·p0.999:  6.183 ms/op
                 existUser·p0.9999: 12.780 ms/op
                 existUser·p1.00:   13.730 ms/op

Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.017 ms/op
                 existUser·p0.50:   2.621 ms/op
                 existUser·p0.90:   3.109 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   3.903 ms/op
                 existUser·p0.999:  9.044 ms/op
                 existUser·p0.9999: 14.164 ms/op
                 existUser·p1.00:   14.828 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 376435
  mean =      2.548 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 181394 
    [ 2.500,  3.750) = 190952 
    [ 3.750,  5.000) = 3148 
    [ 5.000,  6.250) = 477 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      7.074 ms/op
     p(99.9900) =     14.659 ms/op
     p(99.9990) =     18.751 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 3.948 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.558 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  10.948 ms/op
                 getUser·p0.9999: 13.927 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   2: 2.567 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   4.084 ms/op
                 getUser·p0.999:  9.105 ms/op
                 getUser·p0.9999: 12.943 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 2.585 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.142 ms/op
                 getUser·p0.95:   3.310 ms/op
                 getUser·p0.99:   5.079 ms/op
                 getUser·p0.999:  8.722 ms/op
                 getUser·p0.9999: 11.381 ms/op
                 getUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 373165
  mean =      2.570 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 179070 
    [ 2.500,  3.750) = 186478 
    [ 3.750,  5.000) = 5196 
    [ 5.000,  6.250) = 1819 
    [ 6.250,  7.500) = 141 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.289 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      8.812 ms/op
     p(99.9900) =     13.413 ms/op
     p(99.9990) =     14.108 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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
# Warmup Iteration   1: 4.576 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
Iteration   1: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.077 ms/op
                 listUser·p0.9999: 10.764 ms/op
                 listUser·p1.00:   11.158 ms/op

Iteration   2: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.975 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 10.755 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  10.207 ms/op
                 listUser·p0.9999: 12.411 ms/op
                 listUser·p1.00:   13.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318569
  mean =      3.011 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 136 
    [ 1.250,  2.500) = 92494 
    [ 2.500,  3.750) = 186727 
    [ 3.750,  5.000) = 31845 
    [ 5.000,  6.250) = 6026 
    [ 6.250,  7.500) = 633 
    [ 7.500,  8.750) = 248 
    [ 8.750, 10.000) = 236 
    [10.000, 11.250) = 170 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     12.009 ms/op
     p(99.9990) =     13.134 ms/op
     p(99.9999) =     13.386 ms/op
    p(100.0000) =     13.386 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.605 ± 1.779  ops/ms
ClientPb.existUser                       thrpt       3  13.046 ± 0.743  ops/ms
ClientPb.getUser                         thrpt       3  12.756 ± 0.683  ops/ms
ClientPb.listUser                        thrpt       3  10.674 ± 1.315  ops/ms
ClientPb.createUser                       avgt       3   2.554 ± 0.340   ms/op
ClientPb.existUser                        avgt       3   2.484 ± 0.222   ms/op
ClientPb.getUser                          avgt       3   2.580 ± 0.211   ms/op
ClientPb.listUser                         avgt       3   3.069 ± 0.472   ms/op
ClientPb.createUser                     sample  376478   2.547 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.915           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.067           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.290           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.418           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.597           ms/op
ClientPb.existUser                      sample  376435   2.548 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.707           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.617           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.074           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.659           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.333           ms/op
ClientPb.getUser                        sample  373165   2.570 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.696           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.589           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.289           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.812           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.413           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.451           ms/op
ClientPb.listUser                       sample  318569   3.011 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.885           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.009           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.386           ms/op
