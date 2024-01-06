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
# Warmup Iteration   1: 4.463 ops/ms
# Warmup Iteration   2: 12.038 ops/ms
# Warmup Iteration   3: 12.405 ops/ms
Iteration   1: 12.529 ops/ms
Iteration   2: 12.676 ops/ms
Iteration   3: 12.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.628 ±(99.9%) 1.555 ops/ms [Average]
  (min, avg, max) = (12.529, 12.628, 12.678), stdev = 0.085
  CI (99.9%): [11.073, 14.183] (assumes normal distribution)


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
# Warmup Iteration   1: 8.470 ops/ms
# Warmup Iteration   2: 13.206 ops/ms
# Warmup Iteration   3: 13.083 ops/ms
Iteration   1: 13.270 ops/ms
Iteration   2: 13.235 ops/ms
Iteration   3: 13.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.206 ±(99.9%) 1.504 ops/ms [Average]
  (min, avg, max) = (13.113, 13.206, 13.270), stdev = 0.082
  CI (99.9%): [11.702, 14.710] (assumes normal distribution)


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
# Warmup Iteration   1: 7.331 ops/ms
# Warmup Iteration   2: 12.297 ops/ms
# Warmup Iteration   3: 12.717 ops/ms
Iteration   1: 12.643 ops/ms
Iteration   2: 12.621 ops/ms
Iteration   3: 12.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.625 ±(99.9%) 0.306 ops/ms [Average]
  (min, avg, max) = (12.611, 12.625, 12.643), stdev = 0.017
  CI (99.9%): [12.319, 12.931] (assumes normal distribution)


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
# Warmup Iteration   1: 6.758 ops/ms
# Warmup Iteration   2: 10.436 ops/ms
# Warmup Iteration   3: 10.649 ops/ms
Iteration   1: 10.588 ops/ms
Iteration   2: 10.572 ops/ms
Iteration   3: 10.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.621 ±(99.9%) 1.311 ops/ms [Average]
  (min, avg, max) = (10.572, 10.621, 10.704), stdev = 0.072
  CI (99.9%): [9.310, 11.932] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.208 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.003 ms/op
Iteration   1: 2.589 ±(99.9%) 0.004 ms/op
Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
Iteration   3: 2.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.546 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (2.523, 2.546, 2.589), stdev = 0.037
  CI (99.9%): [1.868, 3.225] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.939 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.004 ms/op
Iteration   1: 2.441 ±(99.9%) 0.003 ms/op
Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
Iteration   3: 2.442 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.442 ±(99.9%) 0.037 ms/op [Average]
  (min, avg, max) = (2.441, 2.442, 2.445), stdev = 0.002
  CI (99.9%): [2.406, 2.479] (assumes normal distribution)


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
# Warmup Iteration   1: 4.186 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.004 ms/op
Iteration   1: 2.508 ±(99.9%) 0.004 ms/op
Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.502 ±(99.9%) 0.095 ms/op [Average]
  (min, avg, max) = (2.498, 2.502, 2.508), stdev = 0.005
  CI (99.9%): [2.407, 2.597] (assumes normal distribution)


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
# Warmup Iteration   1: 4.792 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
Iteration   1: 2.991 ±(99.9%) 0.006 ms/op
Iteration   2: 2.985 ±(99.9%) 0.005 ms/op
Iteration   3: 3.006 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.994 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (2.985, 2.994, 3.006), stdev = 0.011
  CI (99.9%): [2.796, 3.192] (assumes normal distribution)


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.654 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.006 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  11.460 ms/op
                 createUser·p0.9999: 14.311 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  9.841 ms/op
                 createUser·p0.9999: 12.286 ms/op
                 createUser·p1.00:   13.386 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   4.006 ms/op
                 createUser·p0.999:  8.967 ms/op
                 createUser·p0.9999: 11.026 ms/op
                 createUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382043
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 185942 
    [ 2.500,  3.750) = 192007 
    [ 3.750,  5.000) = 3251 
    [ 5.000,  6.250) = 380 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     14.991 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 3.834 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.012 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.644 ms/op
                 existUser·p0.999:  7.731 ms/op
                 existUser·p0.9999: 14.851 ms/op
                 existUser·p1.00:   15.696 ms/op

Iteration   2: 2.467 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  8.323 ms/op
                 existUser·p0.9999: 15.846 ms/op
                 existUser·p1.00:   16.646 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  8.580 ms/op
                 existUser·p0.9999: 11.438 ms/op
                 existUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389086
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 191523 
    [ 2.500,  3.750) = 193053 
    [ 3.750,  5.000) = 3117 
    [ 5.000,  6.250) = 844 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      8.217 ms/op
     p(99.9900) =     15.222 ms/op
     p(99.9990) =     16.522 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.006 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  9.316 ms/op
                 getUser·p0.9999: 14.184 ms/op
                 getUser·p1.00:   14.811 ms/op

Iteration   2: 2.504 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  9.331 ms/op
                 getUser·p0.9999: 13.550 ms/op
                 getUser·p1.00:   14.926 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  8.387 ms/op
                 getUser·p0.9999: 11.164 ms/op
                 getUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383397
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 188894 
    [ 2.500,  3.750) = 189843 
    [ 3.750,  5.000) = 3566 
    [ 5.000,  6.250) = 586 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.408 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     14.735 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 4.873 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
Iteration   1: 3.053 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 11.379 ms/op
                 listUser·p1.00:   12.403 ms/op

Iteration   2: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.653 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 11.485 ms/op
                 listUser·p1.00:   11.960 ms/op

Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.004 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.361 ms/op
                 listUser·p0.9999: 10.595 ms/op
                 listUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317390
  mean =      3.022 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 90390 
    [ 2.500,  3.750) = 186603 
    [ 3.750,  5.000) = 32749 
    [ 5.000,  6.250) = 6020 
    [ 6.250,  7.500) = 787 
    [ 7.500,  8.750) = 206 
    [ 8.750, 10.000) = 317 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.545 ms/op
     p(99.9900) =     11.387 ms/op
     p(99.9990) =     11.946 ms/op
     p(99.9999) =     12.403 ms/op
    p(100.0000) =     12.403 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.628 ± 1.555  ops/ms
ClientPb.existUser                       thrpt       3  13.206 ± 1.504  ops/ms
ClientPb.getUser                         thrpt       3  12.625 ± 0.306  ops/ms
ClientPb.listUser                        thrpt       3  10.621 ± 1.311  ops/ms
ClientPb.createUser                       avgt       3   2.546 ± 0.678   ms/op
ClientPb.existUser                        avgt       3   2.442 ± 0.037   ms/op
ClientPb.getUser                          avgt       3   2.502 ± 0.095   ms/op
ClientPb.listUser                         avgt       3   2.994 ± 0.198   ms/op
ClientPb.createUser                     sample  382043   2.510 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.860           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.978           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.550           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.041           ms/op
ClientPb.existUser                      sample  389086   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.716           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.217           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.222           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.646           ms/op
ClientPb.getUser                        sample  383397   2.501 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.844           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.408           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.779           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.926           ms/op
ClientPb.listUser                       sample  317390   3.022 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.653           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.545           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.387           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.403           ms/op
