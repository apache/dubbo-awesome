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
# Warmup Iteration   1: 5.304 ops/ms
# Warmup Iteration   2: 12.405 ops/ms
# Warmup Iteration   3: 12.512 ops/ms
Iteration   1: 12.601 ops/ms
Iteration   2: 12.740 ops/ms
Iteration   3: 12.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.753 ±(99.9%) 2.881 ops/ms [Average]
  (min, avg, max) = (12.601, 12.753, 12.917), stdev = 0.158
  CI (99.9%): [9.871, 15.634] (assumes normal distribution)


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
# Warmup Iteration   1: 8.214 ops/ms
# Warmup Iteration   2: 12.982 ops/ms
# Warmup Iteration   3: 13.036 ops/ms
Iteration   1: 13.110 ops/ms
Iteration   2: 13.163 ops/ms
Iteration   3: 13.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.102 ±(99.9%) 1.192 ops/ms [Average]
  (min, avg, max) = (13.033, 13.102, 13.163), stdev = 0.065
  CI (99.9%): [11.910, 14.294] (assumes normal distribution)


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
# Warmup Iteration   1: 8.116 ops/ms
# Warmup Iteration   2: 12.794 ops/ms
# Warmup Iteration   3: 13.051 ops/ms
Iteration   1: 13.025 ops/ms
Iteration   2: 12.878 ops/ms
Iteration   3: 13.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.990 ±(99.9%) 1.811 ops/ms [Average]
  (min, avg, max) = (12.878, 12.990, 13.067), stdev = 0.099
  CI (99.9%): [11.179, 14.801] (assumes normal distribution)


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
# Warmup Iteration   1: 6.721 ops/ms
# Warmup Iteration   2: 10.545 ops/ms
# Warmup Iteration   3: 10.630 ops/ms
Iteration   1: 10.741 ops/ms
Iteration   2: 10.607 ops/ms
Iteration   3: 10.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.658 ±(99.9%) 1.323 ops/ms [Average]
  (min, avg, max) = (10.607, 10.658, 10.741), stdev = 0.073
  CI (99.9%): [9.335, 11.981] (assumes normal distribution)


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
# Warmup Iteration   1: 3.975 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.003 ms/op
Iteration   1: 2.532 ±(99.9%) 0.004 ms/op
Iteration   2: 2.499 ±(99.9%) 0.004 ms/op
Iteration   3: 2.475 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.502 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (2.475, 2.502, 2.532), stdev = 0.029
  CI (99.9%): [1.975, 3.029] (assumes normal distribution)


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
# Warmup Iteration   1: 3.663 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
Iteration   1: 2.437 ±(99.9%) 0.004 ms/op
Iteration   2: 2.427 ±(99.9%) 0.004 ms/op
Iteration   3: 2.430 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.431 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (2.427, 2.431, 2.437), stdev = 0.005
  CI (99.9%): [2.332, 2.531] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.950 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.003 ms/op
Iteration   1: 2.467 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.489 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.487 ±(99.9%) 0.353 ms/op [Average]
  (min, avg, max) = (2.467, 2.487, 2.506), stdev = 0.019
  CI (99.9%): [2.135, 2.840] (assumes normal distribution)


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
# Warmup Iteration   1: 4.650 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.004 ms/op
Iteration   1: 2.976 ±(99.9%) 0.005 ms/op
Iteration   2: 2.997 ±(99.9%) 0.007 ms/op
Iteration   3: 2.976 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.983 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.976, 2.983, 2.997), stdev = 0.012
  CI (99.9%): [2.764, 3.201] (assumes normal distribution)


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
# Warmup Iteration   1: 4.065 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.648 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
Iteration   1: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.588 ms/op
                 createUser·p0.999:  11.352 ms/op
                 createUser·p0.9999: 16.044 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  9.267 ms/op
                 createUser·p0.9999: 12.571 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  8.260 ms/op
                 createUser·p0.9999: 11.196 ms/op
                 createUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383164
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 185522 
    [ 2.500,  3.750) = 193983 
    [ 3.750,  5.000) = 2709 
    [ 5.000,  6.250) = 400 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      8.319 ms/op
     p(99.9900) =     14.342 ms/op
     p(99.9990) =     17.094 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 3.632 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
Iteration   1: 2.415 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  5.854 ms/op
                 existUser·p0.9999: 13.578 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.912 ms/op
                 existUser·p0.999:  7.247 ms/op
                 existUser·p0.9999: 13.835 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   3: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  6.542 ms/op
                 existUser·p0.9999: 11.287 ms/op
                 existUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394896
  mean =      2.429 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 200672 
    [ 2.500,  3.750) = 190687 
    [ 3.750,  5.000) = 2765 
    [ 5.000,  6.250) = 295 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      6.565 ms/op
     p(99.9900) =     13.492 ms/op
     p(99.9990) =     14.158 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 3.843 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.006 ms/op
Iteration   1: 2.530 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  11.878 ms/op
                 getUser·p0.9999: 14.555 ms/op
                 getUser·p1.00:   15.188 ms/op

Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.096 ms/op
                 getUser·p0.999:  9.812 ms/op
                 getUser·p0.9999: 13.114 ms/op
                 getUser·p1.00:   13.402 ms/op

Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  8.552 ms/op
                 getUser·p0.9999: 10.936 ms/op
                 getUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378742
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 185658 
    [ 2.500,  3.750) = 187254 
    [ 3.750,  5.000) = 4481 
    [ 5.000,  6.250) = 831 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =      8.573 ms/op
     p(99.9900) =     13.681 ms/op
     p(99.9990) =     14.854 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 4.727 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.009 ms/op
Iteration   1: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.780 ms/op
                 listUser·p0.999:  8.915 ms/op
                 listUser·p0.9999: 9.978 ms/op
                 listUser·p1.00:   10.682 ms/op

Iteration   2: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.769 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.011 ms/op
                 listUser·p0.9999: 11.484 ms/op
                 listUser·p1.00:   11.846 ms/op

Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.731 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  10.207 ms/op
                 listUser·p0.9999: 11.762 ms/op
                 listUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318768
  mean =      3.009 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 93878 
    [ 2.500,  3.750) = 186251 
    [ 3.750,  5.000) = 30967 
    [ 5.000,  6.250) = 5989 
    [ 6.250,  7.500) = 873 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 276 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.212 ms/op
     p(99.9900) =     11.452 ms/op
     p(99.9990) =     12.125 ms/op
     p(99.9999) =     12.370 ms/op
    p(100.0000) =     12.370 ms/op


# Run complete. Total time: 00:12:56

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.753 ± 2.881  ops/ms
ClientPb.existUser                       thrpt       3  13.102 ± 1.192  ops/ms
ClientPb.getUser                         thrpt       3  12.990 ± 1.811  ops/ms
ClientPb.listUser                        thrpt       3  10.658 ± 1.323  ops/ms
ClientPb.createUser                       avgt       3   2.502 ± 0.527   ms/op
ClientPb.existUser                        avgt       3   2.431 ± 0.100   ms/op
ClientPb.getUser                          avgt       3   2.487 ± 0.353   ms/op
ClientPb.listUser                         avgt       3   2.983 ± 0.219   ms/op
ClientPb.createUser                     sample  383164   2.503 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.890           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.319           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.342           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.302           ms/op
ClientPb.existUser                      sample  394896   2.429 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.754           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.565           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.492           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.565           ms/op
ClientPb.getUser                        sample  378742   2.533 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.818           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.573           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.681           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.188           ms/op
ClientPb.listUser                       sample  318768   3.009 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.731           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.212           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.452           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.370           ms/op
