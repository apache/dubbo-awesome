# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.993 ops/ms
# Warmup Iteration   2: 5.146 ops/ms
# Warmup Iteration   3: 8.591 ops/ms
Iteration   1: 9.069 ops/ms
Iteration   2: 8.871 ops/ms
Iteration   3: 8.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.937 ±(99.9%) 2.088 ops/ms [Average]
  (min, avg, max) = (8.871, 8.937, 9.069), stdev = 0.114
  CI (99.9%): [6.849, 11.025] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.559 ops/ms
# Warmup Iteration   2: 8.521 ops/ms
# Warmup Iteration   3: 9.320 ops/ms
Iteration   1: 9.539 ops/ms
Iteration   2: 9.659 ops/ms
Iteration   3: 9.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.524 ±(99.9%) 2.615 ops/ms [Average]
  (min, avg, max) = (9.374, 9.524, 9.659), stdev = 0.143
  CI (99.9%): [6.909, 12.139] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.515 ops/ms
# Warmup Iteration   2: 7.803 ops/ms
# Warmup Iteration   3: 8.750 ops/ms
Iteration   1: 8.794 ops/ms
Iteration   2: 8.736 ops/ms
Iteration   3: 9.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.909 ±(99.9%) 4.592 ops/ms [Average]
  (min, avg, max) = (8.736, 8.909, 9.198), stdev = 0.252
  CI (99.9%): [4.317, 13.501] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.337 ops/ms
# Warmup Iteration   2: 6.800 ops/ms
# Warmup Iteration   3: 7.699 ops/ms
Iteration   1: 7.767 ops/ms
Iteration   2: 7.886 ops/ms
Iteration   3: 7.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.840 ±(99.9%) 1.167 ops/ms [Average]
  (min, avg, max) = (7.767, 7.840, 7.886), stdev = 0.064
  CI (99.9%): [6.673, 9.007] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 11.316 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.004 ms/op
Iteration   1: 3.664 ±(99.9%) 0.007 ms/op
Iteration   2: 3.643 ±(99.9%) 0.010 ms/op
Iteration   3: 3.752 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.686 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (3.643, 3.686, 3.752), stdev = 0.058
  CI (99.9%): [2.632, 4.741] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 13.004 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.696 ±(99.9%) 0.003 ms/op
Iteration   1: 3.563 ±(99.9%) 0.008 ms/op
Iteration   2: 3.357 ±(99.9%) 0.005 ms/op
Iteration   3: 3.275 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.398 ±(99.9%) 2.708 ms/op [Average]
  (min, avg, max) = (3.275, 3.398, 3.563), stdev = 0.148
  CI (99.9%): [0.691, 6.106] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.618 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.004 ms/op
Iteration   1: 3.684 ±(99.9%) 0.007 ms/op
Iteration   2: 3.515 ±(99.9%) 0.006 ms/op
Iteration   3: 3.601 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.600 ±(99.9%) 1.542 ms/op [Average]
  (min, avg, max) = (3.515, 3.600, 3.684), stdev = 0.085
  CI (99.9%): [2.058, 5.142] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.519 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.107 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.242 ±(99.9%) 0.006 ms/op
Iteration   1: 4.089 ±(99.9%) 0.012 ms/op
Iteration   2: 4.077 ±(99.9%) 0.015 ms/op
Iteration   3: 3.924 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.030 ±(99.9%) 1.672 ms/op [Average]
  (min, avg, max) = (3.924, 4.030, 4.089), stdev = 0.092
  CI (99.9%): [2.359, 5.702] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.775 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.126 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.015 ms/op
Iteration   1: 3.461 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  21.463 ms/op
                 createUser·p0.9999: 23.872 ms/op
                 createUser·p1.00:   28.148 ms/op

Iteration   2: 3.593 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  22.861 ms/op
                 createUser·p0.9999: 32.997 ms/op
                 createUser·p1.00:   33.817 ms/op

Iteration   3: 3.881 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   3.478 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   7.225 ms/op
                 createUser·p0.99:   8.036 ms/op
                 createUser·p0.999:  26.028 ms/op
                 createUser·p0.9999: 31.745 ms/op
                 createUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 263825
  mean =      3.637 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2786 
    [ 2.500,  5.000) = 247398 
    [ 5.000,  7.500) = 10679 
    [ 7.500, 10.000) = 2342 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     21.993 ms/op
     p(99.9900) =     31.838 ms/op
     p(99.9990) =     33.667 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.693 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.008 ms/op
Iteration   1: 3.299 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  11.155 ms/op
                 existUser·p0.9999: 30.362 ms/op
                 existUser·p1.00:   32.670 ms/op

Iteration   2: 3.342 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.552 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  23.429 ms/op
                 existUser·p0.9999: 25.887 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   3: 3.318 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  19.399 ms/op
                 existUser·p0.9999: 27.254 ms/op
                 existUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289117
  mean =      3.319 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4410 
    [ 2.500,  5.000) = 278953 
    [ 5.000,  7.500) = 4735 
    [ 7.500, 10.000) = 473 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     19.395 ms/op
     p(99.9900) =     28.916 ms/op
     p(99.9990) =     32.637 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.507 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.638 ±(99.9%) 0.011 ms/op
Iteration   1: 3.551 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.901 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.158 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  20.152 ms/op
                 getUser·p0.9999: 23.461 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   2: 3.429 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.483 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  24.314 ms/op
                 getUser·p0.9999: 28.465 ms/op
                 getUser·p1.00:   31.097 ms/op

Iteration   3: 3.604 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.589 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  18.139 ms/op
                 getUser·p0.9999: 26.542 ms/op
                 getUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271961
  mean =      3.526 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4583 
    [ 2.500,  5.000) = 259731 
    [ 5.000,  7.500) = 6445 
    [ 7.500, 10.000) = 804 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.483 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     19.367 ms/op
     p(99.9900) =     27.525 ms/op
     p(99.9990) =     29.995 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.273 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 4.564 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.194 ±(99.9%) 0.013 ms/op
Iteration   1: 4.065 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.700 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  21.647 ms/op
                 listUser·p0.9999: 28.120 ms/op
                 listUser·p1.00:   28.803 ms/op

Iteration   2: 4.086 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.522 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  16.182 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   3: 4.139 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   8.233 ms/op
                 listUser·p0.999:  15.619 ms/op
                 listUser·p0.9999: 21.998 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234275
  mean =      4.096 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 226100 
    [ 5.000,  7.500) = 5630 
    [ 7.500, 10.000) = 1607 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 243 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.522 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.661 ms/op
     p(99.9000) =     16.899 ms/op
     p(99.9900) =     27.165 ms/op
     p(99.9990) =     28.593 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.937 ± 2.088  ops/ms
ClientPb.existUser                       thrpt       3   9.524 ± 2.615  ops/ms
ClientPb.getUser                         thrpt       3   8.909 ± 4.592  ops/ms
ClientPb.listUser                        thrpt       3   7.840 ± 1.167  ops/ms
ClientPb.createUser                       avgt       3   3.686 ± 1.054   ms/op
ClientPb.existUser                        avgt       3   3.398 ± 2.708   ms/op
ClientPb.getUser                          avgt       3   3.600 ± 1.542   ms/op
ClientPb.listUser                         avgt       3   4.030 ± 1.672   ms/op
ClientPb.createUser                     sample  263825   3.637 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.114           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.408           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.190           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.071           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.561           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.993           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.838           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.817           ms/op
ClientPb.existUser                      sample  289117   3.319 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.386           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.751           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.395           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.916           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.670           ms/op
ClientPb.getUser                        sample  271961   3.526 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.483           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.398           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.367           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.525           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.097           ms/op
ClientPb.listUser                       sample  234275   4.096 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.522           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.661           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.899           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.165           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.803           ms/op
