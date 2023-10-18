# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.110 ops/ms
# Warmup Iteration   2: 2.489 ops/ms
# Warmup Iteration   3: 5.270 ops/ms
Iteration   1: 5.743 ops/ms
Iteration   2: 6.032 ops/ms
Iteration   3: 6.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.944 ±(99.9%) 3.186 ops/ms [Average]
  (min, avg, max) = (5.743, 5.944, 6.058), stdev = 0.175
  CI (99.9%): [2.759, 9.130] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.835 ops/ms
# Warmup Iteration   2: 5.046 ops/ms
# Warmup Iteration   3: 5.892 ops/ms
Iteration   1: 5.781 ops/ms
Iteration   2: 5.811 ops/ms
Iteration   3: 5.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.789 ±(99.9%) 0.354 ops/ms [Average]
  (min, avg, max) = (5.775, 5.789, 5.811), stdev = 0.019
  CI (99.9%): [5.435, 6.143] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.446 ops/ms
# Warmup Iteration   2: 4.277 ops/ms
# Warmup Iteration   3: 5.565 ops/ms
Iteration   1: 5.650 ops/ms
Iteration   2: 5.752 ops/ms
Iteration   3: 5.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.747 ±(99.9%) 1.717 ops/ms [Average]
  (min, avg, max) = (5.650, 5.747, 5.838), stdev = 0.094
  CI (99.9%): [4.030, 7.464] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.608 ops/ms
# Warmup Iteration   2: 4.377 ops/ms
# Warmup Iteration   3: 5.178 ops/ms
Iteration   1: 4.624 ops/ms
Iteration   2: 5.041 ops/ms
Iteration   3: 4.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.859 ±(99.9%) 3.894 ops/ms [Average]
  (min, avg, max) = (4.624, 4.859, 5.041), stdev = 0.213
  CI (99.9%): [0.964, 8.753] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 19.498 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 7.072 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.716 ±(99.9%) 0.010 ms/op
Iteration   1: 5.671 ±(99.9%) 0.011 ms/op
Iteration   2: 5.527 ±(99.9%) 0.012 ms/op
Iteration   3: 5.582 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.593 ±(99.9%) 1.329 ms/op [Average]
  (min, avg, max) = (5.527, 5.593, 5.671), stdev = 0.073
  CI (99.9%): [4.264, 6.922] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 16.078 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.636 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.494 ±(99.9%) 0.005 ms/op
Iteration   1: 5.234 ±(99.9%) 0.009 ms/op
Iteration   2: 5.138 ±(99.9%) 0.008 ms/op
Iteration   3: 5.083 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.151 ±(99.9%) 1.389 ms/op [Average]
  (min, avg, max) = (5.083, 5.151, 5.234), stdev = 0.076
  CI (99.9%): [3.763, 6.540] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 18.055 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 7.037 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.749 ±(99.9%) 0.006 ms/op
Iteration   1: 5.516 ±(99.9%) 0.008 ms/op
Iteration   2: 5.548 ±(99.9%) 0.008 ms/op
Iteration   3: 5.382 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.482 ±(99.9%) 1.602 ms/op [Average]
  (min, avg, max) = (5.382, 5.482, 5.548), stdev = 0.088
  CI (99.9%): [3.880, 7.084] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 20.541 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 7.613 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.661 ±(99.9%) 0.010 ms/op
Iteration   1: 6.527 ±(99.9%) 0.018 ms/op
Iteration   2: 6.718 ±(99.9%) 0.009 ms/op
Iteration   3: 6.503 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.582 ±(99.9%) 2.148 ms/op [Average]
  (min, avg, max) = (6.503, 6.582, 6.718), stdev = 0.118
  CI (99.9%): [4.434, 8.731] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.317 ±(99.9%) 0.310 ms/op
# Warmup Iteration   2: 7.352 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 5.566 ±(99.9%) 0.023 ms/op
Iteration   1: 5.554 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.927 ms/op
                 createUser·p0.50:   5.251 ms/op
                 createUser·p0.90:   6.988 ms/op
                 createUser·p0.95:   7.881 ms/op
                 createUser·p0.99:   10.306 ms/op
                 createUser·p0.999:  28.042 ms/op
                 createUser·p0.9999: 31.400 ms/op
                 createUser·p1.00:   33.096 ms/op

Iteration   2: 5.219 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.825 ms/op
                 createUser·p0.50:   4.997 ms/op
                 createUser·p0.90:   6.463 ms/op
                 createUser·p0.95:   7.143 ms/op
                 createUser·p0.99:   9.978 ms/op
                 createUser·p0.999:  24.454 ms/op
                 createUser·p0.9999: 31.912 ms/op
                 createUser·p1.00:   32.571 ms/op

Iteration   3: 5.272 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.474 ms/op
                 createUser·p0.50:   5.014 ms/op
                 createUser·p0.90:   6.578 ms/op
                 createUser·p0.95:   7.349 ms/op
                 createUser·p0.99:   10.535 ms/op
                 createUser·p0.999:  31.174 ms/op
                 createUser·p0.9999: 34.144 ms/op
                 createUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 179596
  mean =      5.344 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 82439 
    [ 5.000,  7.500) = 88365 
    [ 7.500, 10.000) = 6705 
    [10.000, 12.500) = 1363 
    [12.500, 15.000) = 328 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 72 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      5.095 ms/op
     p(90.0000) =      6.660 ms/op
     p(95.0000) =      7.455 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     27.886 ms/op
     p(99.9900) =     33.228 ms/op
     p(99.9990) =     34.643 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 16.053 ±(99.9%) 0.268 ms/op
# Warmup Iteration   2: 5.812 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.189 ±(99.9%) 0.019 ms/op
Iteration   1: 5.249 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.445 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.644 ms/op
                 existUser·p0.95:   8.405 ms/op
                 existUser·p0.99:   10.928 ms/op
                 existUser·p0.999:  22.454 ms/op
                 existUser·p0.9999: 27.355 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   2: 5.481 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.257 ms/op
                 existUser·p0.50:   5.177 ms/op
                 existUser·p0.90:   6.816 ms/op
                 existUser·p0.95:   7.815 ms/op
                 existUser·p0.99:   10.715 ms/op
                 existUser·p0.999:  17.454 ms/op
                 existUser·p0.9999: 31.495 ms/op
                 existUser·p1.00:   32.506 ms/op

Iteration   3: 5.442 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.478 ms/op
                 existUser·p0.50:   5.014 ms/op
                 existUser·p0.90:   6.832 ms/op
                 existUser·p0.95:   8.061 ms/op
                 existUser·p0.99:   12.009 ms/op
                 existUser·p0.999:  28.747 ms/op
                 existUser·p0.9999: 33.289 ms/op
                 existUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 178141
  mean =      5.389 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 89837 
    [ 5.000,  7.500) = 76735 
    [ 7.500, 10.000) = 8605 
    [10.000, 12.500) = 1885 
    [12.500, 15.000) = 647 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.257 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      6.767 ms/op
     p(95.0000) =      8.045 ms/op
     p(99.0000) =     11.223 ms/op
     p(99.9000) =     21.398 ms/op
     p(99.9900) =     32.506 ms/op
     p(99.9990) =     34.683 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.475 ±(99.9%) 0.291 ms/op
# Warmup Iteration   2: 6.932 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.506 ±(99.9%) 0.019 ms/op
Iteration   1: 5.431 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.597 ms/op
                 getUser·p0.50:   4.989 ms/op
                 getUser·p0.90:   7.340 ms/op
                 getUser·p0.95:   8.372 ms/op
                 getUser·p0.99:   11.387 ms/op
                 getUser·p0.999:  23.469 ms/op
                 getUser·p0.9999: 26.582 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   2: 5.438 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.925 ms/op
                 getUser·p0.50:   5.014 ms/op
                 getUser·p0.90:   6.963 ms/op
                 getUser·p0.95:   8.569 ms/op
                 getUser·p0.99:   12.304 ms/op
                 getUser·p0.999:  25.112 ms/op
                 getUser·p0.9999: 30.744 ms/op
                 getUser·p1.00:   32.702 ms/op

Iteration   3: 5.429 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.425 ms/op
                 getUser·p0.50:   5.128 ms/op
                 getUser·p0.90:   6.701 ms/op
                 getUser·p0.95:   7.561 ms/op
                 getUser·p0.99:   11.633 ms/op
                 getUser·p0.999:  17.433 ms/op
                 getUser·p0.9999: 28.627 ms/op
                 getUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176648
  mean =      5.433 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 84062 
    [ 5.000,  7.500) = 78997 
    [ 7.500, 10.000) = 10212 
    [10.000, 12.500) = 2069 
    [12.500, 15.000) = 773 
    [15.000, 17.500) = 277 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.597 ms/op
     p(50.0000) =      5.046 ms/op
     p(90.0000) =      6.922 ms/op
     p(95.0000) =      8.274 ms/op
     p(99.0000) =     11.682 ms/op
     p(99.9000) =     22.392 ms/op
     p(99.9900) =     29.120 ms/op
     p(99.9990) =     31.999 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.201 ±(99.9%) 0.337 ms/op
# Warmup Iteration   2: 8.686 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 6.685 ±(99.9%) 0.029 ms/op
Iteration   1: 6.335 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.830 ms/op
                 listUser·p0.50:   5.956 ms/op
                 listUser·p0.90:   7.710 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   12.485 ms/op
                 listUser·p0.999:  27.994 ms/op
                 listUser·p0.9999: 33.878 ms/op
                 listUser·p1.00:   34.341 ms/op

Iteration   2: 6.596 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.056 ms/op
                 listUser·p0.50:   6.259 ms/op
                 listUser·p0.90:   7.807 ms/op
                 listUser·p0.95:   8.995 ms/op
                 listUser·p0.99:   12.916 ms/op
                 listUser·p0.999:  32.487 ms/op
                 listUser·p0.9999: 42.832 ms/op
                 listUser·p1.00:   43.319 ms/op

Iteration   3: 6.400 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   6.021 ms/op
                 listUser·p0.90:   7.791 ms/op
                 listUser·p0.95:   8.995 ms/op
                 listUser·p0.99:   12.469 ms/op
                 listUser·p0.999:  23.364 ms/op
                 listUser·p0.9999: 29.459 ms/op
                 listUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 149133
  mean =      6.442 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6354 
    [ 5.000, 10.000) = 138205 
    [10.000, 15.000) = 3834 
    [15.000, 20.000) = 415 
    [20.000, 25.000) = 94 
    [25.000, 30.000) = 125 
    [30.000, 35.000) = 73 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      2.314 ms/op
     p(50.0000) =      6.087 ms/op
     p(90.0000) =      7.774 ms/op
     p(95.0000) =      8.995 ms/op
     p(99.0000) =     12.616 ms/op
     p(99.9000) =     28.541 ms/op
     p(99.9900) =     41.000 ms/op
     p(99.9990) =     43.255 ms/op
     p(99.9999) =     43.319 ms/op
    p(100.0000) =     43.319 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.944 ± 3.186  ops/ms
ClientPb.existUser                       thrpt       3   5.789 ± 0.354  ops/ms
ClientPb.getUser                         thrpt       3   5.747 ± 1.717  ops/ms
ClientPb.listUser                        thrpt       3   4.859 ± 3.894  ops/ms
ClientPb.createUser                       avgt       3   5.593 ± 1.329   ms/op
ClientPb.existUser                        avgt       3   5.151 ± 1.389   ms/op
ClientPb.getUser                          avgt       3   5.482 ± 1.602   ms/op
ClientPb.listUser                         avgt       3   6.582 ± 2.148   ms/op
ClientPb.createUser                     sample  179596   5.344 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.474           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.095           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.660           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.455           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.273           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.886           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.228           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.800           ms/op
ClientPb.existUser                      sample  178141   5.389 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.257           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.997           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.767           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.045           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.223           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.398           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.506           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.734           ms/op
ClientPb.getUser                        sample  176648   5.433 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.597           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.046           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.922           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.274           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.682           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.392           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.120           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.702           ms/op
ClientPb.listUser                       sample  149133   6.442 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.314           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.087           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.774           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.995           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.616           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.541           ms/op
ClientPb.listUser:listUser·p0.9999      sample          41.000           ms/op
ClientPb.listUser:listUser·p1.00        sample          43.319           ms/op
