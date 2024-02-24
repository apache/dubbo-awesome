# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.267 ops/ms
# Warmup Iteration   2: 12.139 ops/ms
# Warmup Iteration   3: 12.639 ops/ms
Iteration   1: 12.854 ops/ms
Iteration   2: 12.955 ops/ms
Iteration   3: 12.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.894 ±(99.9%) 0.986 ops/ms [Average]
  (min, avg, max) = (12.854, 12.894, 12.955), stdev = 0.054
  CI (99.9%): [11.908, 13.880] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.234 ops/ms
# Warmup Iteration   2: 13.108 ops/ms
# Warmup Iteration   3: 12.910 ops/ms
Iteration   1: 13.023 ops/ms
Iteration   2: 13.038 ops/ms
Iteration   3: 12.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.006 ±(99.9%) 0.781 ops/ms [Average]
  (min, avg, max) = (12.957, 13.006, 13.038), stdev = 0.043
  CI (99.9%): [12.224, 13.787] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.084 ops/ms
# Warmup Iteration   2: 12.846 ops/ms
# Warmup Iteration   3: 12.822 ops/ms
Iteration   1: 12.897 ops/ms
Iteration   2: 12.979 ops/ms
Iteration   3: 12.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.894 ±(99.9%) 1.580 ops/ms [Average]
  (min, avg, max) = (12.806, 12.894, 12.979), stdev = 0.087
  CI (99.9%): [11.315, 14.474] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.342 ops/ms
# Warmup Iteration   2: 10.613 ops/ms
# Warmup Iteration   3: 10.647 ops/ms
Iteration   1: 10.794 ops/ms
Iteration   2: 10.681 ops/ms
Iteration   3: 10.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.732 ±(99.9%) 1.051 ops/ms [Average]
  (min, avg, max) = (10.681, 10.732, 10.794), stdev = 0.058
  CI (99.9%): [9.680, 11.783] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.895 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.003 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.488 ±(99.9%) 0.003 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.495 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (2.488, 2.495, 2.504), stdev = 0.009
  CI (99.9%): [2.337, 2.653] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.678 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.004 ms/op
Iteration   1: 2.425 ±(99.9%) 0.004 ms/op
Iteration   2: 2.451 ±(99.9%) 0.004 ms/op
Iteration   3: 2.437 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.438 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (2.425, 2.438, 2.451), stdev = 0.013
  CI (99.9%): [2.193, 2.683] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.057 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
Iteration   3: 2.481 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.479 ±(99.9%) 0.032 ms/op [Average]
  (min, avg, max) = (2.478, 2.479, 2.481), stdev = 0.002
  CI (99.9%): [2.447, 2.512] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.599 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.994 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.005 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
Iteration   2: 2.956 ±(99.9%) 0.006 ms/op
Iteration   3: 2.971 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.971 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (2.956, 2.971, 2.987), stdev = 0.016
  CI (99.9%): [2.687, 3.256] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
Iteration   1: 2.455 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  6.583 ms/op
                 createUser·p0.9999: 13.992 ms/op
                 createUser·p1.00:   14.975 ms/op

Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   2.503 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.728 ms/op
                 createUser·p0.999:  7.801 ms/op
                 createUser·p0.9999: 11.463 ms/op
                 createUser·p1.00:   12.272 ms/op

Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  8.102 ms/op
                 createUser·p0.9999: 11.156 ms/op
                 createUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391505
  mean =      2.450 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 193696 
    [ 2.500,  3.750) = 194095 
    [ 3.750,  5.000) = 2772 
    [ 5.000,  6.250) = 397 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 120 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      8.086 ms/op
     p(99.9900) =     13.271 ms/op
     p(99.9990) =     14.829 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.625 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
Iteration   1: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  6.286 ms/op
                 existUser·p0.9999: 15.005 ms/op
                 existUser·p1.00:   16.040 ms/op

Iteration   2: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  7.810 ms/op
                 existUser·p0.9999: 12.710 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  5.816 ms/op
                 existUser·p0.9999: 12.071 ms/op
                 existUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393720
  mean =      2.435 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 196684 
    [ 2.500,  3.750) = 194590 
    [ 3.750,  5.000) = 1714 
    [ 5.000,  6.250) = 285 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.449 ms/op
     p(99.9000) =      6.460 ms/op
     p(99.9900) =     13.412 ms/op
     p(99.9990) =     15.861 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.023 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.539 ms/op
                 getUser·p0.999:  7.223 ms/op
                 getUser·p0.9999: 13.500 ms/op
                 getUser·p1.00:   13.648 ms/op

Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.877 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  6.781 ms/op
                 getUser·p0.9999: 11.731 ms/op
                 getUser·p1.00:   12.698 ms/op

Iteration   3: 2.494 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.794 ms/op
                 getUser·p0.999:  8.894 ms/op
                 getUser·p0.9999: 21.234 ms/op
                 getUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384783
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 193102 
    [ 2.500,  5.000) = 190839 
    [ 5.000,  7.500) = 476 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      6.996 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     22.156 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.671 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.008 ms/op
Iteration   1: 2.946 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.897 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  8.270 ms/op
                 listUser·p0.9999: 13.258 ms/op
                 listUser·p1.00:   14.565 ms/op

Iteration   2: 2.954 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.714 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  8.864 ms/op
                 listUser·p0.9999: 11.079 ms/op
                 listUser·p1.00:   11.354 ms/op

Iteration   3: 2.938 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.740 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   5.267 ms/op
                 listUser·p0.999:  9.191 ms/op
                 listUser·p0.9999: 11.274 ms/op
                 listUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 325559
  mean =      2.946 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 184 
    [ 1.250,  2.500) = 103678 
    [ 2.500,  3.750) = 187664 
    [ 3.750,  5.000) = 28190 
    [ 5.000,  6.250) = 4783 
    [ 6.250,  7.500) = 459 
    [ 7.500,  8.750) = 249 
    [ 8.750, 10.000) = 195 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     11.654 ms/op
     p(99.9990) =     14.033 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.894 ± 0.986  ops/ms
ClientPb.existUser                       thrpt       3  13.006 ± 0.781  ops/ms
ClientPb.getUser                         thrpt       3  12.894 ± 1.580  ops/ms
ClientPb.listUser                        thrpt       3  10.732 ± 1.051  ops/ms
ClientPb.createUser                       avgt       3   2.495 ± 0.158   ms/op
ClientPb.existUser                        avgt       3   2.438 ± 0.245   ms/op
ClientPb.getUser                          avgt       3   2.479 ± 0.032   ms/op
ClientPb.listUser                         avgt       3   2.971 ± 0.285   ms/op
ClientPb.createUser                     sample  391505   2.450 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.893           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.519           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.974           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.086           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.271           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.975           ms/op
ClientPb.existUser                      sample  393720   2.435 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.882           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.449           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.460           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.412           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.040           ms/op
ClientPb.getUser                        sample  384783   2.492 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.637           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.996           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.550           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.217           ms/op
ClientPb.listUser                       sample  325559   2.946 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.714           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.399           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.864           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.654           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.565           ms/op
