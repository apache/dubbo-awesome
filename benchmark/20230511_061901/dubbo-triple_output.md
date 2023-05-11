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
# Warmup Iteration   1: 1.615 ops/ms
# Warmup Iteration   2: 3.580 ops/ms
# Warmup Iteration   3: 6.997 ops/ms
Iteration   1: 7.229 ops/ms
Iteration   2: 7.682 ops/ms
Iteration   3: 7.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.549 ±(99.9%) 5.096 ops/ms [Average]
  (min, avg, max) = (7.229, 7.549, 7.738), stdev = 0.279
  CI (99.9%): [2.453, 12.645] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.036 ops/ms
# Warmup Iteration   2: 6.960 ops/ms
# Warmup Iteration   3: 7.913 ops/ms
Iteration   1: 8.137 ops/ms
Iteration   2: 8.044 ops/ms
Iteration   3: 8.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.176 ±(99.9%) 2.835 ops/ms [Average]
  (min, avg, max) = (8.044, 8.176, 8.347), stdev = 0.155
  CI (99.9%): [5.342, 11.011] (assumes normal distribution)


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
# Warmup Iteration   1: 2.075 ops/ms
# Warmup Iteration   2: 6.474 ops/ms
# Warmup Iteration   3: 7.530 ops/ms
Iteration   1: 8.285 ops/ms
Iteration   2: 8.129 ops/ms
Iteration   3: 8.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.168 ±(99.9%) 1.877 ops/ms [Average]
  (min, avg, max) = (8.090, 8.168, 8.285), stdev = 0.103
  CI (99.9%): [6.291, 10.045] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.944 ops/ms
# Warmup Iteration   2: 5.253 ops/ms
# Warmup Iteration   3: 6.347 ops/ms
Iteration   1: 6.539 ops/ms
Iteration   2: 6.707 ops/ms
Iteration   3: 6.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.713 ±(99.9%) 3.239 ops/ms [Average]
  (min, avg, max) = (6.539, 6.713, 6.894), stdev = 0.178
  CI (99.9%): [3.475, 9.952] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 15.037 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.776 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.007 ms/op
Iteration   1: 4.291 ±(99.9%) 0.006 ms/op
Iteration   2: 4.054 ±(99.9%) 0.003 ms/op
Iteration   3: 4.183 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.176 ±(99.9%) 2.164 ms/op [Average]
  (min, avg, max) = (4.054, 4.176, 4.291), stdev = 0.119
  CI (99.9%): [2.012, 6.340] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.981 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.427 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.007 ms/op
Iteration   1: 3.880 ±(99.9%) 0.004 ms/op
Iteration   2: 3.728 ±(99.9%) 0.006 ms/op
Iteration   3: 3.715 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.774 ±(99.9%) 1.674 ms/op [Average]
  (min, avg, max) = (3.715, 3.774, 3.880), stdev = 0.092
  CI (99.9%): [2.100, 5.448] (assumes normal distribution)


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
# Warmup Iteration   1: 13.776 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.059 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.303 ±(99.9%) 0.005 ms/op
Iteration   1: 3.879 ±(99.9%) 0.014 ms/op
Iteration   2: 3.924 ±(99.9%) 0.013 ms/op
Iteration   3: 4.002 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.935 ±(99.9%) 1.143 ms/op [Average]
  (min, avg, max) = (3.879, 3.935, 4.002), stdev = 0.063
  CI (99.9%): [2.792, 5.077] (assumes normal distribution)


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
# Warmup Iteration   1: 14.701 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.729 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.045 ±(99.9%) 0.007 ms/op
Iteration   1: 4.708 ±(99.9%) 0.011 ms/op
Iteration   2: 4.765 ±(99.9%) 0.013 ms/op
Iteration   3: 4.796 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.756 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (4.708, 4.756, 4.796), stdev = 0.045
  CI (99.9%): [3.939, 5.573] (assumes normal distribution)


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
# Warmup Iteration   1: 14.055 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 5.317 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.565 ±(99.9%) 0.019 ms/op
Iteration   1: 4.191 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.753 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   5.202 ms/op
                 createUser·p0.95:   6.390 ms/op
                 createUser·p0.99:   8.364 ms/op
                 createUser·p0.999:  11.544 ms/op
                 createUser·p0.9999: 25.943 ms/op
                 createUser·p1.00:   28.148 ms/op

Iteration   2: 4.013 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.882 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   7.629 ms/op
                 createUser·p0.999:  26.083 ms/op
                 createUser·p0.9999: 28.445 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   3: 4.031 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.126 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.513 ms/op
                 createUser·p0.99:   7.774 ms/op
                 createUser·p0.999:  14.877 ms/op
                 createUser·p0.9999: 31.591 ms/op
                 createUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235373
  mean =      4.077 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 406 
    [ 2.500,  5.000) = 215331 
    [ 5.000,  7.500) = 16081 
    [ 7.500, 10.000) = 2740 
    [10.000, 12.500) = 460 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.753 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     18.522 ms/op
     p(99.9900) =     30.028 ms/op
     p(99.9990) =     32.114 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 12.165 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.528 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.013 ms/op
Iteration   1: 3.802 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   7.430 ms/op
                 existUser·p0.999:  22.622 ms/op
                 existUser·p0.9999: 26.332 ms/op
                 existUser·p1.00:   27.689 ms/op

Iteration   2: 3.732 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.076 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   6.866 ms/op
                 existUser·p0.999:  15.285 ms/op
                 existUser·p0.9999: 26.589 ms/op
                 existUser·p1.00:   27.296 ms/op

Iteration   3: 3.695 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.860 ms/op
                 existUser·p0.50:   3.568 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.758 ms/op
                 existUser·p0.999:  27.467 ms/op
                 existUser·p0.9999: 34.537 ms/op
                 existUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 256383
  mean =      3.742 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 268 
    [ 2.500,  5.000) = 247274 
    [ 5.000,  7.500) = 6695 
    [ 7.500, 10.000) = 1214 
    [10.000, 12.500) = 519 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     21.524 ms/op
     p(99.9900) =     32.714 ms/op
     p(99.9990) =     35.331 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 13.371 ±(99.9%) 0.231 ms/op
# Warmup Iteration   2: 4.593 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.234 ±(99.9%) 0.015 ms/op
Iteration   1: 4.207 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.282 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   6.300 ms/op
                 getUser·p0.99:   9.372 ms/op
                 getUser·p0.999:  25.166 ms/op
                 getUser·p0.9999: 30.795 ms/op
                 getUser·p1.00:   39.322 ms/op

Iteration   2: 3.864 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.769 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  11.929 ms/op
                 getUser·p0.9999: 28.499 ms/op
                 getUser·p1.00:   29.262 ms/op

Iteration   3: 4.130 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.677 ms/op
                 getUser·p0.99:   7.324 ms/op
                 getUser·p0.999:  30.769 ms/op
                 getUser·p0.9999: 36.569 ms/op
                 getUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236408
  mean =      4.061 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 140 
    [ 2.500,  5.000) = 217072 
    [ 5.000,  7.500) = 16481 
    [ 7.500, 10.000) = 1708 
    [10.000, 12.500) = 526 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 39 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.774 ms/op
     p(99.9000) =     25.166 ms/op
     p(99.9900) =     35.127 ms/op
     p(99.9990) =     37.421 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


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
# Warmup Iteration   1: 14.667 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 5.792 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.192 ±(99.9%) 0.022 ms/op
Iteration   1: 4.741 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  23.233 ms/op
                 listUser·p0.9999: 27.697 ms/op
                 listUser·p1.00:   29.426 ms/op

Iteration   2: 4.616 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.712 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 27.965 ms/op
                 listUser·p1.00:   29.590 ms/op

Iteration   3: 4.769 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.658 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.210 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 21.744 ms/op
                 listUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203859
  mean =      4.707 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 172842 
    [ 5.000,  7.500) = 25872 
    [ 7.500, 10.000) = 4028 
    [10.000, 12.500) = 554 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.593 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      9.028 ms/op
     p(99.9000) =     19.399 ms/op
     p(99.9900) =     27.644 ms/op
     p(99.9990) =     29.412 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.549 ± 5.096  ops/ms
ClientPb.existUser                       thrpt       3   8.176 ± 2.835  ops/ms
ClientPb.getUser                         thrpt       3   8.168 ± 1.877  ops/ms
ClientPb.listUser                        thrpt       3   6.713 ± 3.239  ops/ms
ClientPb.createUser                       avgt       3   4.176 ± 2.164   ms/op
ClientPb.existUser                        avgt       3   3.774 ± 1.674   ms/op
ClientPb.getUser                          avgt       3   3.935 ± 1.143   ms/op
ClientPb.listUser                         avgt       3   4.756 ± 0.817   ms/op
ClientPb.createUser                     sample  235373   4.077 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.753           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.833           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.767           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.094           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.522           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.028           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.309           ms/op
ClientPb.existUser                      sample  256383   3.742 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.178           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.059           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.489           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.135           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.524           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.714           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.372           ms/op
ClientPb.getUser                        sample  236408   4.061 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.282           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.801           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.734           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.774           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.166           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.127           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.322           ms/op
ClientPb.listUser                       sample  203859   4.707 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.593           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.251           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.028           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.399           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.644           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.590           ms/op
