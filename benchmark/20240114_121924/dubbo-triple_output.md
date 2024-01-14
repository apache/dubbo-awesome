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
# Warmup Iteration   1: 4.823 ops/ms
# Warmup Iteration   2: 11.990 ops/ms
# Warmup Iteration   3: 12.390 ops/ms
Iteration   1: 12.584 ops/ms
Iteration   2: 12.721 ops/ms
Iteration   3: 12.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.686 ±(99.9%) 1.646 ops/ms [Average]
  (min, avg, max) = (12.584, 12.686, 12.754), stdev = 0.090
  CI (99.9%): [11.040, 14.333] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 7.857 ops/ms
# Warmup Iteration   2: 12.903 ops/ms
# Warmup Iteration   3: 13.032 ops/ms
Iteration   1: 13.137 ops/ms
Iteration   2: 13.281 ops/ms
Iteration   3: 13.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.188 ±(99.9%) 1.477 ops/ms [Average]
  (min, avg, max) = (13.137, 13.188, 13.281), stdev = 0.081
  CI (99.9%): [11.712, 14.665] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.533 ops/ms
# Warmup Iteration   2: 12.589 ops/ms
# Warmup Iteration   3: 12.839 ops/ms
Iteration   1: 12.828 ops/ms
Iteration   2: 12.821 ops/ms
Iteration   3: 12.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.690 ±(99.9%) 4.255 ops/ms [Average]
  (min, avg, max) = (12.421, 12.690, 12.828), stdev = 0.233
  CI (99.9%): [8.435, 16.945] (assumes normal distribution)


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
# Warmup Iteration   1: 6.531 ops/ms
# Warmup Iteration   2: 10.433 ops/ms
# Warmup Iteration   3: 10.548 ops/ms
Iteration   1: 10.698 ops/ms
Iteration   2: 10.597 ops/ms
Iteration   3: 10.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.570 ±(99.9%) 2.617 ops/ms [Average]
  (min, avg, max) = (10.415, 10.570, 10.698), stdev = 0.143
  CI (99.9%): [7.953, 13.187] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.044 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.003 ms/op
Iteration   1: 2.542 ±(99.9%) 0.004 ms/op
Iteration   2: 2.523 ±(99.9%) 0.004 ms/op
Iteration   3: 2.540 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.535 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (2.523, 2.535, 2.542), stdev = 0.010
  CI (99.9%): [2.351, 2.719] (assumes normal distribution)


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
# Warmup Iteration   1: 3.623 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.450 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.408 ±(99.9%) 0.003 ms/op
Iteration   1: 2.424 ±(99.9%) 0.003 ms/op
Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
Iteration   3: 2.435 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.436 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (2.424, 2.436, 2.448), stdev = 0.012
  CI (99.9%): [2.216, 2.656] (assumes normal distribution)


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.004 ms/op
Iteration   1: 2.505 ±(99.9%) 0.004 ms/op
Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
Iteration   3: 2.534 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.525 ±(99.9%) 0.318 ms/op [Average]
  (min, avg, max) = (2.505, 2.525, 2.536), stdev = 0.017
  CI (99.9%): [2.207, 2.843] (assumes normal distribution)


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.005 ms/op
Iteration   1: 3.020 ±(99.9%) 0.005 ms/op
Iteration   2: 3.001 ±(99.9%) 0.005 ms/op
Iteration   3: 3.000 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.007 ±(99.9%) 0.203 ms/op [Average]
  (min, avg, max) = (3.000, 3.007, 3.020), stdev = 0.011
  CI (99.9%): [2.804, 3.210] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.060 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.006 ms/op
Iteration   1: 2.527 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.770 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  12.976 ms/op
                 createUser·p0.9999: 14.631 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  10.042 ms/op
                 createUser·p0.9999: 12.730 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  8.716 ms/op
                 createUser·p0.9999: 10.403 ms/op
                 createUser·p1.00:   14.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380759
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 181413 
    [ 2.500,  3.750) = 195454 
    [ 3.750,  5.000) = 3040 
    [ 5.000,  6.250) = 354 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      8.720 ms/op
     p(99.9900) =     14.156 ms/op
     p(99.9990) =     14.798 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.746 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.566 ms/op
                 existUser·p0.999:  6.045 ms/op
                 existUser·p0.9999: 14.336 ms/op
                 existUser·p1.00:   15.172 ms/op

Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.034 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  6.542 ms/op
                 existUser·p0.9999: 12.862 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.826 ms/op
                 existUser·p0.999:  8.111 ms/op
                 existUser·p0.9999: 11.638 ms/op
                 existUser·p1.00:   15.270 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388730
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 192631 
    [ 2.500,  3.750) = 192639 
    [ 3.750,  5.000) = 2665 
    [ 5.000,  6.250) = 294 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      8.021 ms/op
     p(99.9900) =     13.718 ms/op
     p(99.9990) =     14.966 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.767 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  11.788 ms/op
                 getUser·p0.9999: 13.858 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  9.186 ms/op
                 getUser·p0.9999: 14.128 ms/op
                 getUser·p1.00:   15.073 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  6.158 ms/op
                 getUser·p0.9999: 12.797 ms/op
                 getUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383476
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 189521 
    [ 2.500,  3.750) = 189800 
    [ 3.750,  5.000) = 3276 
    [ 5.000,  6.250) = 424 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      7.897 ms/op
     p(99.9900) =     13.812 ms/op
     p(99.9990) =     14.672 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.686 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.009 ms/op
Iteration   1: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.506 ms/op
                 listUser·p0.9999: 12.321 ms/op
                 listUser·p1.00:   12.960 ms/op

Iteration   2: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.847 ms/op
                 listUser·p0.9999: 10.607 ms/op
                 listUser·p1.00:   10.977 ms/op

Iteration   3: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.732 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  8.696 ms/op
                 listUser·p0.9999: 10.556 ms/op
                 listUser·p1.00:   10.912 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318997
  mean =      3.007 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 94192 
    [ 2.500,  3.750) = 186540 
    [ 3.750,  5.000) = 31004 
    [ 5.000,  6.250) = 5771 
    [ 6.250,  7.500) = 683 
    [ 7.500,  8.750) = 339 
    [ 8.750, 10.000) = 180 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     11.813 ms/op
     p(99.9990) =     12.921 ms/op
     p(99.9999) =     12.960 ms/op
    p(100.0000) =     12.960 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.686 ± 1.646  ops/ms
ClientPb.existUser                       thrpt       3  13.188 ± 1.477  ops/ms
ClientPb.getUser                         thrpt       3  12.690 ± 4.255  ops/ms
ClientPb.listUser                        thrpt       3  10.570 ± 2.617  ops/ms
ClientPb.createUser                       avgt       3   2.535 ± 0.184   ms/op
ClientPb.existUser                        avgt       3   2.436 ± 0.220   ms/op
ClientPb.getUser                          avgt       3   2.525 ± 0.318   ms/op
ClientPb.listUser                         avgt       3   3.007 ± 0.203   ms/op
ClientPb.createUser                     sample  380759   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.748           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.720           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.156           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.893           ms/op
ClientPb.existUser                      sample  388730   2.467 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.945           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.021           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.718           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.270           ms/op
ClientPb.getUser                        sample  383476   2.501 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.798           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.897           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.812           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.073           ms/op
ClientPb.listUser                       sample  318997   3.007 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.732           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.929           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.813           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.960           ms/op
