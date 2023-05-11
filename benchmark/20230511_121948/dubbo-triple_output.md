# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.251 ops/ms
# Warmup Iteration   2: 2.938 ops/ms
# Warmup Iteration   3: 6.584 ops/ms
Iteration   1: 6.946 ops/ms
Iteration   2: 8.061 ops/ms
Iteration   3: 7.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.602 ±(99.9%) 10.633 ops/ms [Average]
  (min, avg, max) = (6.946, 7.602, 8.061), stdev = 0.583
  CI (99.9%): [≈ 0, 18.235] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.155 ops/ms
# Warmup Iteration   2: 6.523 ops/ms
# Warmup Iteration   3: 7.994 ops/ms
Iteration   1: 8.242 ops/ms
Iteration   2: 8.570 ops/ms
Iteration   3: 8.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.424 ±(99.9%) 3.039 ops/ms [Average]
  (min, avg, max) = (8.242, 8.424, 8.570), stdev = 0.167
  CI (99.9%): [5.385, 11.464] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.258 ops/ms
# Warmup Iteration   2: 6.730 ops/ms
# Warmup Iteration   3: 7.803 ops/ms
Iteration   1: 8.278 ops/ms
Iteration   2: 8.081 ops/ms
Iteration   3: 8.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.201 ±(99.9%) 1.920 ops/ms [Average]
  (min, avg, max) = (8.081, 8.201, 8.278), stdev = 0.105
  CI (99.9%): [6.281, 10.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.221 ops/ms
# Warmup Iteration   2: 5.474 ops/ms
# Warmup Iteration   3: 6.508 ops/ms
Iteration   1: 6.962 ops/ms
Iteration   2: 6.872 ops/ms
Iteration   3: 6.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.877 ±(99.9%) 1.487 ops/ms [Average]
  (min, avg, max) = (6.799, 6.877, 6.962), stdev = 0.082
  CI (99.9%): [5.390, 8.365] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.907 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.419 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.008 ms/op
Iteration   1: 3.817 ±(99.9%) 0.008 ms/op
Iteration   2: 3.835 ±(99.9%) 0.010 ms/op
Iteration   3: 3.903 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.852 ±(99.9%) 0.825 ms/op [Average]
  (min, avg, max) = (3.817, 3.852, 3.903), stdev = 0.045
  CI (99.9%): [3.027, 4.677] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.976 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.349 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.006 ms/op
Iteration   1: 3.625 ±(99.9%) 0.006 ms/op
Iteration   2: 3.753 ±(99.9%) 0.009 ms/op
Iteration   3: 3.772 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.717 ±(99.9%) 1.455 ms/op [Average]
  (min, avg, max) = (3.625, 3.717, 3.772), stdev = 0.080
  CI (99.9%): [2.262, 5.171] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.359 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.558 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.156 ±(99.9%) 0.006 ms/op
Iteration   1: 3.964 ±(99.9%) 0.006 ms/op
Iteration   2: 3.957 ±(99.9%) 0.007 ms/op
Iteration   3: 3.930 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.951 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (3.930, 3.951, 3.964), stdev = 0.018
  CI (99.9%): [3.623, 4.279] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.037 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.538 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.674 ±(99.9%) 0.011 ms/op
Iteration   1: 4.616 ±(99.9%) 0.013 ms/op
Iteration   2: 4.608 ±(99.9%) 0.008 ms/op
Iteration   3: 4.576 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.600 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (4.576, 4.600, 4.616), stdev = 0.021
  CI (99.9%): [4.215, 4.985] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.815 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 5.249 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.242 ±(99.9%) 0.016 ms/op
Iteration   1: 4.090 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.645 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.685 ms/op
                 createUser·p0.99:   7.907 ms/op
                 createUser·p0.999:  24.046 ms/op
                 createUser·p0.9999: 25.925 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   2: 4.045 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.649 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  20.316 ms/op
                 createUser·p0.9999: 28.479 ms/op
                 createUser·p1.00:   30.474 ms/op

Iteration   3: 4.060 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.808 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.112 ms/op
                 createUser·p0.99:   7.438 ms/op
                 createUser·p0.999:  30.450 ms/op
                 createUser·p0.9999: 32.780 ms/op
                 createUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235903
  mean =      4.065 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 311 
    [ 2.500,  5.000) = 220383 
    [ 5.000,  7.500) = 12878 
    [ 7.500, 10.000) = 1626 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 73 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.645 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     24.183 ms/op
     p(99.9900) =     32.028 ms/op
     p(99.9990) =     33.334 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.430 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 4.421 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.012 ms/op
Iteration   1: 3.791 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.935 ms/op
                 existUser·p0.50:   3.633 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   6.668 ms/op
                 existUser·p0.999:  10.475 ms/op
                 existUser·p0.9999: 26.387 ms/op
                 existUser·p1.00:   27.427 ms/op

Iteration   2: 3.779 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  24.752 ms/op
                 existUser·p0.9999: 27.104 ms/op
                 existUser·p1.00:   28.475 ms/op

Iteration   3: 3.763 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.649 ms/op
                 existUser·p0.50:   3.633 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   7.111 ms/op
                 existUser·p0.999:  11.420 ms/op
                 existUser·p0.9999: 28.672 ms/op
                 existUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254072
  mean =      3.778 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 183 
    [ 2.500,  5.000) = 244784 
    [ 5.000,  7.500) = 7705 
    [ 7.500, 10.000) = 1029 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 115 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     12.354 ms/op
     p(99.9900) =     28.298 ms/op
     p(99.9990) =     28.923 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.465 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.776 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.015 ms/op
Iteration   1: 3.969 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.872 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   7.621 ms/op
                 getUser·p0.999:  12.528 ms/op
                 getUser·p0.9999: 24.703 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   2: 4.034 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.700 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.788 ms/op
                 getUser·p0.999:  17.058 ms/op
                 getUser·p0.9999: 26.773 ms/op
                 getUser·p1.00:   27.525 ms/op

Iteration   3: 3.963 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.833 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  13.308 ms/op
                 getUser·p0.9999: 29.149 ms/op
                 getUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240829
  mean =      3.988 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 231734 
    [ 5.000,  7.500) = 7204 
    [ 7.500, 10.000) = 1198 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.700 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     13.520 ms/op
     p(99.9900) =     28.410 ms/op
     p(99.9990) =     29.530 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.097 ±(99.9%) 0.220 ms/op
# Warmup Iteration   2: 5.344 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.911 ±(99.9%) 0.017 ms/op
Iteration   1: 4.818 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.642 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   6.160 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  24.707 ms/op
                 listUser·p0.9999: 28.073 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   2: 4.930 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.700 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   6.463 ms/op
                 listUser·p0.99:   9.863 ms/op
                 listUser·p0.999:  21.730 ms/op
                 listUser·p0.9999: 25.055 ms/op
                 listUser·p1.00:   27.787 ms/op

Iteration   3: 4.722 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.597 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  17.706 ms/op
                 listUser·p0.9999: 22.151 ms/op
                 listUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198863
  mean =      4.821 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 157670 
    [ 5.000,  7.500) = 34847 
    [ 7.500, 10.000) = 4986 
    [10.000, 12.500) = 723 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     21.955 ms/op
     p(99.9900) =     27.037 ms/op
     p(99.9990) =     28.249 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.602 ± 10.633  ops/ms
ClientPb.existUser                       thrpt       3   8.424 ±  3.039  ops/ms
ClientPb.getUser                         thrpt       3   8.201 ±  1.920  ops/ms
ClientPb.listUser                        thrpt       3   6.877 ±  1.487  ops/ms
ClientPb.createUser                       avgt       3   3.852 ±  0.825   ms/op
ClientPb.existUser                        avgt       3   3.717 ±  1.455   ms/op
ClientPb.getUser                          avgt       3   3.951 ±  0.328   ms/op
ClientPb.listUser                         avgt       3   4.600 ±  0.385   ms/op
ClientPb.createUser                     sample  235903   4.065 ±  0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.645            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.912            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.686            ms/op
ClientPb.createUser:createUser·p0.95    sample           5.226            ms/op
ClientPb.createUser:createUser·p0.99    sample           7.471            ms/op
ClientPb.createUser:createUser·p0.999   sample          24.183            ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.028            ms/op
ClientPb.createUser:createUser·p1.00    sample          35.389            ms/op
ClientPb.existUser                      sample  254072   3.778 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.397            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.650            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.157            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.596            ms/op
ClientPb.existUser:existUser·p0.99      sample           6.873            ms/op
ClientPb.existUser:existUser·p0.999     sample          12.354            ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.298            ms/op
ClientPb.existUser:existUser·p1.00      sample          29.196            ms/op
ClientPb.getUser                        sample  240829   3.988 ±  0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.700            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.867            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.440            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.760            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.053            ms/op
ClientPb.getUser:getUser·p0.999         sample          13.520            ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.410            ms/op
ClientPb.getUser:getUser·p1.00          sample          29.590            ms/op
ClientPb.listUser                       sample  198863   4.821 ±  0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.642            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.588            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.317            ms/op
ClientPb.listUser:listUser·p0.95        sample           6.046            ms/op
ClientPb.listUser:listUser·p0.99        sample           9.224            ms/op
ClientPb.listUser:listUser·p0.999       sample          21.955            ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.037            ms/op
ClientPb.listUser:listUser·p1.00        sample          28.475            ms/op
