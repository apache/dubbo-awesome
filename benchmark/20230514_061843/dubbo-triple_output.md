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
# Warmup Iteration   1: 1.043 ops/ms
# Warmup Iteration   2: 2.438 ops/ms
# Warmup Iteration   3: 4.971 ops/ms
Iteration   1: 5.450 ops/ms
Iteration   2: 5.485 ops/ms
Iteration   3: 5.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.551 ±(99.9%) 2.648 ops/ms [Average]
  (min, avg, max) = (5.450, 5.551, 5.717), stdev = 0.145
  CI (99.9%): [2.903, 8.199] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.462 ops/ms
# Warmup Iteration   2: 3.850 ops/ms
# Warmup Iteration   3: 5.535 ops/ms
Iteration   1: 5.759 ops/ms
Iteration   2: 5.935 ops/ms
Iteration   3: 5.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.850 ±(99.9%) 1.603 ops/ms [Average]
  (min, avg, max) = (5.759, 5.850, 5.935), stdev = 0.088
  CI (99.9%): [4.247, 7.453] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.609 ops/ms
# Warmup Iteration   2: 4.306 ops/ms
# Warmup Iteration   3: 5.550 ops/ms
Iteration   1: 5.666 ops/ms
Iteration   2: 5.537 ops/ms
Iteration   3: 5.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.626 ±(99.9%) 1.419 ops/ms [Average]
  (min, avg, max) = (5.537, 5.626, 5.676), stdev = 0.078
  CI (99.9%): [4.207, 7.046] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.429 ops/ms
# Warmup Iteration   2: 3.640 ops/ms
# Warmup Iteration   3: 4.630 ops/ms
Iteration   1: 4.747 ops/ms
Iteration   2: 4.716 ops/ms
Iteration   3: 4.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.731 ±(99.9%) 0.280 ops/ms [Average]
  (min, avg, max) = (4.716, 4.731, 4.747), stdev = 0.015
  CI (99.9%): [4.451, 5.011] (assumes normal distribution)


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
# Warmup Iteration   1: 18.993 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 7.393 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.951 ±(99.9%) 0.013 ms/op
Iteration   1: 5.700 ±(99.9%) 0.017 ms/op
Iteration   2: 5.653 ±(99.9%) 0.014 ms/op
Iteration   3: 5.686 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.680 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (5.653, 5.680, 5.700), stdev = 0.024
  CI (99.9%): [5.241, 6.119] (assumes normal distribution)


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
# Warmup Iteration   1: 16.970 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 6.700 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.556 ±(99.9%) 0.015 ms/op
Iteration   1: 5.385 ±(99.9%) 0.016 ms/op
Iteration   2: 5.277 ±(99.9%) 0.016 ms/op
Iteration   3: 5.258 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.307 ±(99.9%) 1.252 ms/op [Average]
  (min, avg, max) = (5.258, 5.307, 5.385), stdev = 0.069
  CI (99.9%): [4.054, 6.559] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 19.349 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.626 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.733 ±(99.9%) 0.010 ms/op
Iteration   1: 5.780 ±(99.9%) 0.015 ms/op
Iteration   2: 5.615 ±(99.9%) 0.019 ms/op
Iteration   3: 5.552 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.649 ±(99.9%) 2.146 ms/op [Average]
  (min, avg, max) = (5.552, 5.649, 5.780), stdev = 0.118
  CI (99.9%): [3.503, 7.795] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.688 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 7.716 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.846 ±(99.9%) 0.012 ms/op
Iteration   1: 6.788 ±(99.9%) 0.013 ms/op
Iteration   2: 6.596 ±(99.9%) 0.017 ms/op
Iteration   3: 6.682 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.688 ±(99.9%) 1.760 ms/op [Average]
  (min, avg, max) = (6.596, 6.688, 6.788), stdev = 0.096
  CI (99.9%): [4.928, 8.449] (assumes normal distribution)


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
# Warmup Iteration   1: 17.960 ±(99.9%) 0.346 ms/op
# Warmup Iteration   2: 6.952 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.889 ±(99.9%) 0.025 ms/op
Iteration   1: 5.809 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.997 ms/op
                 createUser·p0.50:   5.497 ms/op
                 createUser·p0.90:   7.062 ms/op
                 createUser·p0.95:   8.102 ms/op
                 createUser·p0.99:   11.239 ms/op
                 createUser·p0.999:  28.309 ms/op
                 createUser·p0.9999: 31.474 ms/op
                 createUser·p1.00:   32.047 ms/op

Iteration   2: 5.444 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.703 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   6.341 ms/op
                 createUser·p0.95:   7.053 ms/op
                 createUser·p0.99:   10.027 ms/op
                 createUser·p0.999:  32.473 ms/op
                 createUser·p0.9999: 35.922 ms/op
                 createUser·p1.00:   36.110 ms/op

Iteration   3: 5.630 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.699 ms/op
                 createUser·p0.50:   5.423 ms/op
                 createUser·p0.90:   6.767 ms/op
                 createUser·p0.95:   7.373 ms/op
                 createUser·p0.99:   9.896 ms/op
                 createUser·p0.999:  28.720 ms/op
                 createUser·p0.9999: 31.927 ms/op
                 createUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170610
  mean =      5.624 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 44962 
    [ 5.000,  7.500) = 117110 
    [ 7.500, 10.000) = 6427 
    [10.000, 12.500) = 1405 
    [12.500, 15.000) = 386 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.997 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      6.758 ms/op
     p(95.0000) =      7.504 ms/op
     p(99.0000) =     10.418 ms/op
     p(99.9000) =     28.599 ms/op
     p(99.9900) =     34.927 ms/op
     p(99.9990) =     36.110 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.673 ±(99.9%) 0.289 ms/op
# Warmup Iteration   2: 6.453 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.648 ±(99.9%) 0.020 ms/op
Iteration   1: 5.204 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.204 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.365 ms/op
                 existUser·p0.95:   7.234 ms/op
                 existUser·p0.99:   9.847 ms/op
                 existUser·p0.999:  13.854 ms/op
                 existUser·p0.9999: 28.985 ms/op
                 existUser·p1.00:   29.262 ms/op

Iteration   2: 5.108 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.306 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   6.070 ms/op
                 existUser·p0.95:   6.701 ms/op
                 existUser·p0.99:   8.831 ms/op
                 existUser·p0.999:  26.364 ms/op
                 existUser·p0.9999: 45.023 ms/op
                 existUser·p1.00:   45.613 ms/op

Iteration   3: 5.103 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.025 ms/op
                 existUser·p0.50:   4.866 ms/op
                 existUser·p0.90:   6.054 ms/op
                 existUser·p0.95:   6.873 ms/op
                 existUser·p0.99:   9.372 ms/op
                 existUser·p0.999:  25.459 ms/op
                 existUser·p0.9999: 30.129 ms/op
                 existUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 186691
  mean =      5.138 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 105940 
    [ 5.000, 10.000) = 79384 
    [10.000, 15.000) = 1173 
    [15.000, 20.000) = 30 
    [20.000, 25.000) = 6 
    [25.000, 30.000) = 117 
    [30.000, 35.000) = 9 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.025 ms/op
     p(50.0000) =      4.915 ms/op
     p(90.0000) =      6.160 ms/op
     p(95.0000) =      6.922 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     16.005 ms/op
     p(99.9900) =     37.552 ms/op
     p(99.9990) =     45.272 ms/op
     p(99.9999) =     45.613 ms/op
    p(100.0000) =     45.613 ms/op


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
# Warmup Iteration   1: 17.205 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 6.733 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.351 ±(99.9%) 0.019 ms/op
Iteration   1: 5.684 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.564 ms/op
                 getUser·p0.50:   5.374 ms/op
                 getUser·p0.90:   6.980 ms/op
                 getUser·p0.95:   8.421 ms/op
                 getUser·p0.99:   11.420 ms/op
                 getUser·p0.999:  23.647 ms/op
                 getUser·p0.9999: 27.361 ms/op
                 getUser·p1.00:   27.787 ms/op

Iteration   2: 5.629 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.499 ms/op
                 getUser·p0.50:   5.317 ms/op
                 getUser·p0.90:   6.758 ms/op
                 getUser·p0.95:   8.118 ms/op
                 getUser·p0.99:   11.141 ms/op
                 getUser·p0.999:  28.803 ms/op
                 getUser·p0.9999: 39.599 ms/op
                 getUser·p1.00:   40.960 ms/op

Iteration   3: 5.569 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.694 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   6.873 ms/op
                 getUser·p0.95:   7.741 ms/op
                 getUser·p0.99:   9.896 ms/op
                 getUser·p0.999:  27.886 ms/op
                 getUser·p0.9999: 33.767 ms/op
                 getUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170633
  mean =      5.627 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 52135 
    [ 5.000, 10.000) = 115981 
    [10.000, 15.000) = 2168 
    [15.000, 20.000) = 117 
    [20.000, 25.000) = 38 
    [25.000, 30.000) = 116 
    [30.000, 35.000) = 61 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.499 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      6.865 ms/op
     p(95.0000) =      8.004 ms/op
     p(99.0000) =     10.863 ms/op
     p(99.9000) =     26.444 ms/op
     p(99.9900) =     35.524 ms/op
     p(99.9990) =     40.682 ms/op
     p(99.9999) =     40.960 ms/op
    p(100.0000) =     40.960 ms/op


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
# Warmup Iteration   1: 19.609 ±(99.9%) 0.396 ms/op
# Warmup Iteration   2: 8.197 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 6.633 ±(99.9%) 0.026 ms/op
Iteration   1: 6.670 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.058 ms/op
                 listUser·p0.50:   6.218 ms/op
                 listUser·p0.90:   8.258 ms/op
                 listUser·p0.95:   10.093 ms/op
                 listUser·p0.99:   12.986 ms/op
                 listUser·p0.999:  26.214 ms/op
                 listUser·p0.9999: 31.281 ms/op
                 listUser·p1.00:   32.309 ms/op

Iteration   2: 6.806 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.101 ms/op
                 listUser·p0.50:   6.357 ms/op
                 listUser·p0.90:   8.585 ms/op
                 listUser·p0.95:   9.765 ms/op
                 listUser·p0.99:   12.698 ms/op
                 listUser·p0.999:  27.853 ms/op
                 listUser·p0.9999: 30.920 ms/op
                 listUser·p1.00:   31.228 ms/op

Iteration   3: 6.492 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.428 ms/op
                 listUser·p0.50:   6.152 ms/op
                 listUser·p0.90:   7.709 ms/op
                 listUser·p0.95:   9.028 ms/op
                 listUser·p0.99:   12.190 ms/op
                 listUser·p0.999:  25.978 ms/op
                 listUser·p0.9999: 31.856 ms/op
                 listUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144187
  mean =      6.654 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 3329 
    [ 5.000,  7.500) = 118667 
    [ 7.500, 10.000) = 16360 
    [10.000, 12.500) = 4248 
    [12.500, 15.000) = 848 
    [15.000, 17.500) = 374 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.058 ms/op
     p(50.0000) =      6.234 ms/op
     p(90.0000) =      8.217 ms/op
     p(95.0000) =      9.568 ms/op
     p(99.0000) =     12.681 ms/op
     p(99.9000) =     26.995 ms/op
     p(99.9900) =     31.228 ms/op
     p(99.9990) =     33.297 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.551 ± 2.648  ops/ms
ClientPb.existUser                       thrpt       3   5.850 ± 1.603  ops/ms
ClientPb.getUser                         thrpt       3   5.626 ± 1.419  ops/ms
ClientPb.listUser                        thrpt       3   4.731 ± 0.280  ops/ms
ClientPb.createUser                       avgt       3   5.680 ± 0.439   ms/op
ClientPb.existUser                        avgt       3   5.307 ± 1.252   ms/op
ClientPb.getUser                          avgt       3   5.649 ± 2.146   ms/op
ClientPb.listUser                         avgt       3   6.688 ± 1.760   ms/op
ClientPb.createUser                     sample  170610   5.624 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.997           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.758           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.504           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.418           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.599           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.927           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.110           ms/op
ClientPb.existUser                      sample  186691   5.138 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.025           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.160           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.922           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.306           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.005           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.552           ms/op
ClientPb.existUser:existUser·p1.00      sample          45.613           ms/op
ClientPb.getUser                        sample  170633   5.627 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.499           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.325           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.865           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.004           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.863           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.444           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.524           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.960           ms/op
ClientPb.listUser                       sample  144187   6.654 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.058           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.234           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.217           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.568           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.681           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.995           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.228           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.079           ms/op
