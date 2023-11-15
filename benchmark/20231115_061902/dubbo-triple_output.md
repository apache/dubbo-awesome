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
# Warmup Iteration   1: 1.934 ops/ms
# Warmup Iteration   2: 4.861 ops/ms
# Warmup Iteration   3: 8.001 ops/ms
Iteration   1: 8.644 ops/ms
Iteration   2: 8.724 ops/ms
Iteration   3: 9.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.807 ±(99.9%) 3.955 ops/ms [Average]
  (min, avg, max) = (8.644, 8.807, 9.053), stdev = 0.217
  CI (99.9%): [4.852, 12.762] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.780 ops/ms
# Warmup Iteration   2: 7.950 ops/ms
# Warmup Iteration   3: 8.999 ops/ms
Iteration   1: 9.049 ops/ms
Iteration   2: 8.940 ops/ms
Iteration   3: 9.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.036 ±(99.9%) 1.655 ops/ms [Average]
  (min, avg, max) = (8.940, 9.036, 9.120), stdev = 0.091
  CI (99.9%): [7.381, 10.692] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.308 ops/ms
# Warmup Iteration   2: 7.914 ops/ms
# Warmup Iteration   3: 8.571 ops/ms
Iteration   1: 8.667 ops/ms
Iteration   2: 8.946 ops/ms
Iteration   3: 8.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.817 ±(99.9%) 2.569 ops/ms [Average]
  (min, avg, max) = (8.667, 8.817, 8.946), stdev = 0.141
  CI (99.9%): [6.248, 11.386] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.437 ops/ms
# Warmup Iteration   2: 6.578 ops/ms
# Warmup Iteration   3: 6.907 ops/ms
Iteration   1: 7.050 ops/ms
Iteration   2: 7.126 ops/ms
Iteration   3: 7.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.082 ±(99.9%) 0.719 ops/ms [Average]
  (min, avg, max) = (7.050, 7.082, 7.126), stdev = 0.039
  CI (99.9%): [6.363, 7.801] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 14.332 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.497 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.006 ms/op
Iteration   1: 3.740 ±(99.9%) 0.006 ms/op
Iteration   2: 3.858 ±(99.9%) 0.004 ms/op
Iteration   3: 3.853 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.817 ±(99.9%) 1.217 ms/op [Average]
  (min, avg, max) = (3.740, 3.817, 3.858), stdev = 0.067
  CI (99.9%): [2.600, 5.034] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.159 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.002 ms/op
Iteration   1: 3.551 ±(99.9%) 0.004 ms/op
Iteration   2: 3.548 ±(99.9%) 0.003 ms/op
Iteration   3: 3.631 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.576 ±(99.9%) 0.858 ms/op [Average]
  (min, avg, max) = (3.548, 3.576, 3.631), stdev = 0.047
  CI (99.9%): [2.718, 4.435] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.770 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.003 ms/op
Iteration   1: 3.791 ±(99.9%) 0.005 ms/op
Iteration   2: 3.782 ±(99.9%) 0.004 ms/op
Iteration   3: 3.732 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.768 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (3.732, 3.768, 3.791), stdev = 0.032
  CI (99.9%): [3.189, 4.347] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.214 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.901 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.485 ±(99.9%) 0.008 ms/op
Iteration   1: 4.475 ±(99.9%) 0.008 ms/op
Iteration   2: 4.531 ±(99.9%) 0.006 ms/op
Iteration   3: 4.475 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.493 ±(99.9%) 0.587 ms/op [Average]
  (min, avg, max) = (4.475, 4.493, 4.531), stdev = 0.032
  CI (99.9%): [3.906, 5.081] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.787 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.016 ms/op
Iteration   1: 3.781 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  16.411 ms/op
                 createUser·p0.9999: 26.608 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   2: 3.648 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.539 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  22.161 ms/op
                 createUser·p0.9999: 25.272 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   3: 3.651 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  24.849 ms/op
                 createUser·p0.9999: 27.427 ms/op
                 createUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 260051
  mean =      3.692 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2006 
    [ 2.500,  5.000) = 250682 
    [ 5.000,  7.500) = 6239 
    [ 7.500, 10.000) = 531 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 137 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     26.968 ms/op
     p(99.9990) =     28.246 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.287 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.010 ms/op
Iteration   1: 3.674 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.640 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   6.611 ms/op
                 existUser·p0.999:  11.728 ms/op
                 existUser·p0.9999: 23.785 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   2: 3.575 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  24.053 ms/op
                 existUser·p0.9999: 31.657 ms/op
                 existUser·p1.00:   32.571 ms/op

Iteration   3: 3.636 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.398 ms/op
                 existUser·p0.50:   3.547 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  13.567 ms/op
                 existUser·p0.9999: 31.038 ms/op
                 existUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 264612
  mean =      3.628 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2821 
    [ 2.500,  5.000) = 255178 
    [ 5.000,  7.500) = 5385 
    [ 7.500, 10.000) = 636 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.398 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     30.870 ms/op
     p(99.9990) =     32.334 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.526 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.013 ms/op
Iteration   1: 3.526 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  14.090 ms/op
                 getUser·p0.9999: 23.527 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   2: 3.479 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  22.938 ms/op
                 getUser·p0.9999: 26.503 ms/op
                 getUser·p1.00:   28.180 ms/op

Iteration   3: 3.489 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.247 ms/op
                 getUser·p0.999:  23.539 ms/op
                 getUser·p0.9999: 30.693 ms/op
                 getUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274222
  mean =      3.498 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5804 
    [ 2.500,  5.000) = 262320 
    [ 5.000,  7.500) = 4916 
    [ 7.500, 10.000) = 449 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     19.653 ms/op
     p(99.9900) =     28.893 ms/op
     p(99.9990) =     31.441 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.588 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.498 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.015 ms/op
Iteration   1: 4.198 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.726 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  21.358 ms/op
                 listUser·p0.9999: 25.190 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   2: 4.169 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 17.880 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   3: 4.171 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.882 ms/op
                 listUser·p0.9999: 17.542 ms/op
                 listUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229485
  mean =      4.179 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 104 
    [ 2.500,  5.000) = 216741 
    [ 5.000,  7.500) = 10401 
    [ 7.500, 10.000) = 1193 
    [10.000, 12.500) = 326 
    [12.500, 15.000) = 310 
    [15.000, 17.500) = 267 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.726 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     23.826 ms/op
     p(99.9990) =     25.846 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.807 ± 3.955  ops/ms
ClientPb.existUser                       thrpt       3   9.036 ± 1.655  ops/ms
ClientPb.getUser                         thrpt       3   8.817 ± 2.569  ops/ms
ClientPb.listUser                        thrpt       3   7.082 ± 0.719  ops/ms
ClientPb.createUser                       avgt       3   3.817 ± 1.217   ms/op
ClientPb.existUser                        avgt       3   3.576 ± 0.858   ms/op
ClientPb.getUser                          avgt       3   3.768 ± 0.579   ms/op
ClientPb.listUser                         avgt       3   4.493 ± 0.587   ms/op
ClientPb.createUser                     sample  260051   3.692 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.290           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.612           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.316           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.252           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.968           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.524           ms/op
ClientPb.existUser                      sample  264612   3.628 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.398           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.100           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.267           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.484           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.870           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.571           ms/op
ClientPb.getUser                        sample  274222   3.498 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.968           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.424           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.350           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.046           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.653           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.893           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.556           ms/op
ClientPb.listUser                       sample  229485   4.179 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.726           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.046           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.810           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.826           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.051           ms/op
