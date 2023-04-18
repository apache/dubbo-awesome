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
# Warmup Iteration   1: 1.264 ops/ms
# Warmup Iteration   2: 2.931 ops/ms
# Warmup Iteration   3: 5.757 ops/ms
Iteration   1: 5.899 ops/ms
Iteration   2: 6.048 ops/ms
Iteration   3: 6.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.072 ±(99.9%) 3.401 ops/ms [Average]
  (min, avg, max) = (5.899, 6.072, 6.269), stdev = 0.186
  CI (99.9%): [2.671, 9.473] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.018 ops/ms
# Warmup Iteration   2: 5.681 ops/ms
# Warmup Iteration   3: 6.509 ops/ms
Iteration   1: 6.547 ops/ms
Iteration   2: 6.037 ops/ms
Iteration   3: 5.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.126 ±(99.9%) 6.998 ops/ms [Average]
  (min, avg, max) = (5.795, 6.126, 6.547), stdev = 0.384
  CI (99.9%): [≈ 0, 13.125] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.669 ops/ms
# Warmup Iteration   2: 4.938 ops/ms
# Warmup Iteration   3: 5.901 ops/ms
Iteration   1: 5.647 ops/ms
Iteration   2: 5.834 ops/ms
Iteration   3: 5.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.786 ±(99.9%) 2.228 ops/ms [Average]
  (min, avg, max) = (5.647, 5.786, 5.877), stdev = 0.122
  CI (99.9%): [3.558, 8.014] (assumes normal distribution)


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
# Warmup Iteration   1: 1.506 ops/ms
# Warmup Iteration   2: 4.047 ops/ms
# Warmup Iteration   3: 4.869 ops/ms
Iteration   1: 4.868 ops/ms
Iteration   2: 5.060 ops/ms
Iteration   3: 4.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.966 ±(99.9%) 1.753 ops/ms [Average]
  (min, avg, max) = (4.868, 4.966, 5.060), stdev = 0.096
  CI (99.9%): [3.213, 6.720] (assumes normal distribution)


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
# Warmup Iteration   1: 17.101 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.516 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.755 ±(99.9%) 0.013 ms/op
Iteration   1: 5.654 ±(99.9%) 0.013 ms/op
Iteration   2: 5.334 ±(99.9%) 0.016 ms/op
Iteration   3: 5.385 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.457 ±(99.9%) 3.135 ms/op [Average]
  (min, avg, max) = (5.334, 5.457, 5.654), stdev = 0.172
  CI (99.9%): [2.323, 8.592] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.122 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.980 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.395 ±(99.9%) 0.008 ms/op
Iteration   1: 5.693 ±(99.9%) 0.018 ms/op
Iteration   2: 5.118 ±(99.9%) 0.015 ms/op
Iteration   3: 5.367 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.392 ±(99.9%) 5.260 ms/op [Average]
  (min, avg, max) = (5.118, 5.392, 5.693), stdev = 0.288
  CI (99.9%): [0.133, 10.652] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 16.098 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.350 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.406 ±(99.9%) 0.006 ms/op
Iteration   1: 5.208 ±(99.9%) 0.016 ms/op
Iteration   2: 5.207 ±(99.9%) 0.017 ms/op
Iteration   3: 5.185 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.200 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (5.185, 5.200, 5.208), stdev = 0.013
  CI (99.9%): [4.966, 5.434] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.408 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 7.678 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.207 ±(99.9%) 0.012 ms/op
Iteration   1: 6.147 ±(99.9%) 0.016 ms/op
Iteration   2: 6.392 ±(99.9%) 0.013 ms/op
Iteration   3: 6.005 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.181 ±(99.9%) 3.567 ms/op [Average]
  (min, avg, max) = (6.005, 6.181, 6.392), stdev = 0.196
  CI (99.9%): [2.614, 9.748] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.856 ±(99.9%) 0.239 ms/op
# Warmup Iteration   2: 6.596 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.800 ±(99.9%) 0.026 ms/op
Iteration   1: 5.320 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.109 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.504 ms/op
                 createUser·p0.95:   7.176 ms/op
                 createUser·p0.99:   9.716 ms/op
                 createUser·p0.999:  21.453 ms/op
                 createUser·p0.9999: 39.584 ms/op
                 createUser·p1.00:   41.353 ms/op

Iteration   2: 5.465 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.220 ms/op
                 createUser·p0.50:   5.267 ms/op
                 createUser·p0.90:   6.791 ms/op
                 createUser·p0.95:   7.422 ms/op
                 createUser·p0.99:   9.126 ms/op
                 createUser·p0.999:  24.490 ms/op
                 createUser·p0.9999: 28.082 ms/op
                 createUser·p1.00:   31.785 ms/op

Iteration   3: 5.474 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.980 ms/op
                 createUser·p0.50:   5.186 ms/op
                 createUser·p0.90:   6.930 ms/op
                 createUser·p0.95:   7.815 ms/op
                 createUser·p0.99:   10.241 ms/op
                 createUser·p0.999:  27.558 ms/op
                 createUser·p0.9999: 30.933 ms/op
                 createUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 177249
  mean =      5.419 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 74471 
    [ 5.000, 10.000) = 101195 
    [10.000, 15.000) = 1290 
    [15.000, 20.000) = 51 
    [20.000, 25.000) = 77 
    [25.000, 30.000) = 120 
    [30.000, 35.000) = 13 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.980 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.742 ms/op
     p(95.0000) =      7.479 ms/op
     p(99.0000) =      9.765 ms/op
     p(99.9000) =     24.543 ms/op
     p(99.9900) =     37.750 ms/op
     p(99.9990) =     41.303 ms/op
     p(99.9999) =     41.353 ms/op
    p(100.0000) =     41.353 ms/op


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
# Warmup Iteration   1: 14.751 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 5.548 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.207 ±(99.9%) 0.017 ms/op
Iteration   1: 5.015 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.208 ms/op
                 existUser·p0.50:   4.801 ms/op
                 existUser·p0.90:   6.111 ms/op
                 existUser·p0.95:   6.726 ms/op
                 existUser·p0.99:   8.864 ms/op
                 existUser·p0.999:  20.209 ms/op
                 existUser·p0.9999: 23.712 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   2: 5.031 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   4.801 ms/op
                 existUser·p0.90:   6.128 ms/op
                 existUser·p0.95:   6.889 ms/op
                 existUser·p0.99:   9.322 ms/op
                 existUser·p0.999:  22.429 ms/op
                 existUser·p0.9999: 27.317 ms/op
                 existUser·p1.00:   27.525 ms/op

Iteration   3: 5.189 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.339 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   6.406 ms/op
                 existUser·p0.95:   7.127 ms/op
                 existUser·p0.99:   9.978 ms/op
                 existUser·p0.999:  25.408 ms/op
                 existUser·p0.9999: 30.076 ms/op
                 existUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188821
  mean =      5.077 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 108136 
    [ 5.000,  7.500) = 74669 
    [ 7.500, 10.000) = 4549 
    [10.000, 12.500) = 867 
    [12.500, 15.000) = 224 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      6.218 ms/op
     p(95.0000) =      6.930 ms/op
     p(99.0000) =      9.339 ms/op
     p(99.9000) =     20.563 ms/op
     p(99.9900) =     28.807 ms/op
     p(99.9990) =     30.653 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 16.244 ±(99.9%) 0.265 ms/op
# Warmup Iteration   2: 6.201 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.251 ±(99.9%) 0.020 ms/op
Iteration   1: 5.250 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   4.932 ms/op
                 getUser·p0.90:   6.341 ms/op
                 getUser·p0.95:   7.643 ms/op
                 getUser·p0.99:   11.436 ms/op
                 getUser·p0.999:  26.119 ms/op
                 getUser·p0.9999: 31.734 ms/op
                 getUser·p1.00:   33.227 ms/op

Iteration   2: 5.346 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.523 ms/op
                 getUser·p0.50:   5.046 ms/op
                 getUser·p0.90:   6.496 ms/op
                 getUser·p0.95:   7.864 ms/op
                 getUser·p0.99:   10.748 ms/op
                 getUser·p0.999:  25.035 ms/op
                 getUser·p0.9999: 46.620 ms/op
                 getUser·p1.00:   50.332 ms/op

Iteration   3: 5.272 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.165 ms/op
                 getUser·p0.50:   4.989 ms/op
                 getUser·p0.90:   6.578 ms/op
                 getUser·p0.95:   7.627 ms/op
                 getUser·p0.99:   9.863 ms/op
                 getUser·p0.999:  25.519 ms/op
                 getUser·p0.9999: 32.143 ms/op
                 getUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 181383
  mean =      5.289 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 91882 
    [ 5.000, 10.000) = 86955 
    [10.000, 15.000) = 2168 
    [15.000, 20.000) = 144 
    [20.000, 25.000) = 28 
    [25.000, 30.000) = 149 
    [30.000, 35.000) = 25 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 22 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      6.488 ms/op
     p(95.0000) =      7.700 ms/op
     p(99.0000) =     10.764 ms/op
     p(99.9000) =     25.657 ms/op
     p(99.9900) =     43.376 ms/op
     p(99.9990) =     50.118 ms/op
     p(99.9999) =     50.332 ms/op
    p(100.0000) =     50.332 ms/op


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
# Warmup Iteration   1: 18.199 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 7.180 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.145 ±(99.9%) 0.021 ms/op
Iteration   1: 6.239 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.978 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   8.233 ms/op
                 listUser·p0.99:   11.321 ms/op
                 listUser·p0.999:  23.588 ms/op
                 listUser·p0.9999: 26.374 ms/op
                 listUser·p1.00:   27.623 ms/op

Iteration   2: 6.114 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.183 ms/op
                 listUser·p0.50:   5.816 ms/op
                 listUser·p0.90:   7.151 ms/op
                 listUser·p0.95:   8.020 ms/op
                 listUser·p0.99:   12.648 ms/op
                 listUser·p0.999:  25.690 ms/op
                 listUser·p0.9999: 29.402 ms/op
                 listUser·p1.00:   31.064 ms/op

Iteration   3: 6.074 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.150 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   7.315 ms/op
                 listUser·p0.95:   8.176 ms/op
                 listUser·p0.99:   10.977 ms/op
                 listUser·p0.999:  25.383 ms/op
                 listUser·p0.9999: 32.708 ms/op
                 listUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 156280
  mean =      6.142 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 14645 
    [ 5.000,  7.500) = 128636 
    [ 7.500, 10.000) = 9959 
    [10.000, 12.500) = 1902 
    [12.500, 15.000) = 517 
    [15.000, 17.500) = 228 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.978 ms/op
     p(50.0000) =      5.865 ms/op
     p(90.0000) =      7.299 ms/op
     p(95.0000) =      8.159 ms/op
     p(99.0000) =     11.583 ms/op
     p(99.9000) =     24.721 ms/op
     p(99.9900) =     31.271 ms/op
     p(99.9990) =     33.102 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.072 ± 3.401  ops/ms
ClientPb.existUser                       thrpt       3   6.126 ± 6.998  ops/ms
ClientPb.getUser                         thrpt       3   5.786 ± 2.228  ops/ms
ClientPb.listUser                        thrpt       3   4.966 ± 1.753  ops/ms
ClientPb.createUser                       avgt       3   5.457 ± 3.135   ms/op
ClientPb.existUser                        avgt       3   5.392 ± 5.260   ms/op
ClientPb.getUser                          avgt       3   5.200 ± 0.234   ms/op
ClientPb.listUser                         avgt       3   6.181 ± 3.567   ms/op
ClientPb.createUser                     sample  177249   5.419 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.980           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.169           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.742           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.479           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.765           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.543           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.750           ms/op
ClientPb.createUser:createUser·p1.00    sample          41.353           ms/op
ClientPb.existUser                      sample  188821   5.077 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.732           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.866           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.218           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.930           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.339           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.563           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.807           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.031           ms/op
ClientPb.getUser                        sample  181383   5.289 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.165           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.989           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.488           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.700           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.764           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.657           ms/op
ClientPb.getUser:getUser·p0.9999        sample          43.376           ms/op
ClientPb.getUser:getUser·p1.00          sample          50.332           ms/op
ClientPb.listUser                       sample  156280   6.142 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.865           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.299           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.159           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.583           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.721           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.271           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.489           ms/op
