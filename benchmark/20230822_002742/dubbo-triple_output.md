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
# Warmup Iteration   1: 1.118 ops/ms
# Warmup Iteration   2: 2.765 ops/ms
# Warmup Iteration   3: 5.031 ops/ms
Iteration   1: 5.342 ops/ms
Iteration   2: 5.592 ops/ms
Iteration   3: 5.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.548 ±(99.9%) 3.428 ops/ms [Average]
  (min, avg, max) = (5.342, 5.548, 5.710), stdev = 0.188
  CI (99.9%): [2.120, 8.976] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.611 ops/ms
# Warmup Iteration   2: 4.612 ops/ms
# Warmup Iteration   3: 5.659 ops/ms
Iteration   1: 5.825 ops/ms
Iteration   2: 6.032 ops/ms
Iteration   3: 5.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.891 ±(99.9%) 2.235 ops/ms [Average]
  (min, avg, max) = (5.815, 5.891, 6.032), stdev = 0.122
  CI (99.9%): [3.656, 8.125] (assumes normal distribution)


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
# Warmup Iteration   1: 1.663 ops/ms
# Warmup Iteration   2: 4.505 ops/ms
# Warmup Iteration   3: 5.555 ops/ms
Iteration   1: 5.778 ops/ms
Iteration   2: 5.497 ops/ms
Iteration   3: 5.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.606 ±(99.9%) 2.749 ops/ms [Average]
  (min, avg, max) = (5.497, 5.606, 5.778), stdev = 0.151
  CI (99.9%): [2.857, 8.355] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.532 ops/ms
# Warmup Iteration   2: 3.729 ops/ms
# Warmup Iteration   3: 4.664 ops/ms
Iteration   1: 4.998 ops/ms
Iteration   2: 4.992 ops/ms
Iteration   3: 5.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.999 ±(99.9%) 0.148 ops/ms [Average]
  (min, avg, max) = (4.992, 4.999, 5.008), stdev = 0.008
  CI (99.9%): [4.851, 5.147] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 19.521 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 6.920 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.784 ±(99.9%) 0.010 ms/op
Iteration   1: 5.801 ±(99.9%) 0.009 ms/op
Iteration   2: 5.579 ±(99.9%) 0.018 ms/op
Iteration   3: 5.765 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.715 ±(99.9%) 2.176 ms/op [Average]
  (min, avg, max) = (5.579, 5.715, 5.801), stdev = 0.119
  CI (99.9%): [3.539, 7.891] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 17.175 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 6.186 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.323 ±(99.9%) 0.008 ms/op
Iteration   1: 5.151 ±(99.9%) 0.011 ms/op
Iteration   2: 5.199 ±(99.9%) 0.010 ms/op
Iteration   3: 5.348 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.232 ±(99.9%) 1.874 ms/op [Average]
  (min, avg, max) = (5.151, 5.232, 5.348), stdev = 0.103
  CI (99.9%): [3.358, 7.106] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.016 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.585 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.786 ±(99.9%) 0.008 ms/op
Iteration   1: 5.858 ±(99.9%) 0.009 ms/op
Iteration   2: 5.631 ±(99.9%) 0.011 ms/op
Iteration   3: 5.818 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.769 ±(99.9%) 2.206 ms/op [Average]
  (min, avg, max) = (5.631, 5.769, 5.858), stdev = 0.121
  CI (99.9%): [3.562, 7.975] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.782 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 8.158 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.799 ±(99.9%) 0.014 ms/op
Iteration   1: 6.964 ±(99.9%) 0.010 ms/op
Iteration   2: 6.865 ±(99.9%) 0.011 ms/op
Iteration   3: 6.608 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.812 ±(99.9%) 3.348 ms/op [Average]
  (min, avg, max) = (6.608, 6.812, 6.964), stdev = 0.184
  CI (99.9%): [3.464, 10.160] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.169 ±(99.9%) 0.267 ms/op
# Warmup Iteration   2: 6.865 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.897 ±(99.9%) 0.029 ms/op
Iteration   1: 5.677 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.265 ms/op
                 createUser·p0.50:   5.341 ms/op
                 createUser·p0.90:   6.996 ms/op
                 createUser·p0.95:   8.389 ms/op
                 createUser·p0.99:   11.705 ms/op
                 createUser·p0.999:  27.895 ms/op
                 createUser·p0.9999: 47.258 ms/op
                 createUser·p1.00:   49.545 ms/op

Iteration   2: 5.516 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.273 ms/op
                 createUser·p0.50:   5.153 ms/op
                 createUser·p0.90:   6.955 ms/op
                 createUser·p0.95:   8.053 ms/op
                 createUser·p0.99:   11.272 ms/op
                 createUser·p0.999:  30.540 ms/op
                 createUser·p0.9999: 38.746 ms/op
                 createUser·p1.00:   40.501 ms/op

Iteration   3: 5.504 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.400 ms/op
                 createUser·p0.50:   5.153 ms/op
                 createUser·p0.90:   6.955 ms/op
                 createUser·p0.95:   8.036 ms/op
                 createUser·p0.99:   10.666 ms/op
                 createUser·p0.999:  15.442 ms/op
                 createUser·p0.9999: 36.396 ms/op
                 createUser·p1.00:   37.880 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172513
  mean =      5.564 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 65363 
    [ 5.000, 10.000) = 103798 
    [10.000, 15.000) = 2935 
    [15.000, 20.000) = 234 
    [20.000, 25.000) = 23 
    [25.000, 30.000) = 24 
    [30.000, 35.000) = 60 
    [35.000, 40.000) = 43 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.265 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      8.167 ms/op
     p(99.0000) =     11.305 ms/op
     p(99.9000) =     21.643 ms/op
     p(99.9900) =     45.613 ms/op
     p(99.9990) =     49.545 ms/op
     p(99.9999) =     49.545 ms/op
    p(100.0000) =     49.545 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.989 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 6.362 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.754 ±(99.9%) 0.025 ms/op
Iteration   1: 5.480 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.089 ms/op
                 existUser·p0.50:   5.153 ms/op
                 existUser·p0.90:   6.947 ms/op
                 existUser·p0.95:   8.151 ms/op
                 existUser·p0.99:   11.764 ms/op
                 existUser·p0.999:  16.278 ms/op
                 existUser·p0.9999: 31.593 ms/op
                 existUser·p1.00:   32.375 ms/op

Iteration   2: 5.416 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.413 ms/op
                 existUser·p0.50:   5.063 ms/op
                 existUser·p0.90:   6.734 ms/op
                 existUser·p0.95:   7.930 ms/op
                 existUser·p0.99:   11.354 ms/op
                 existUser·p0.999:  26.930 ms/op
                 existUser·p0.9999: 30.588 ms/op
                 existUser·p1.00:   31.162 ms/op

Iteration   3: 5.541 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   5.128 ms/op
                 existUser·p0.90:   6.996 ms/op
                 existUser·p0.95:   8.634 ms/op
                 existUser·p0.99:   11.731 ms/op
                 existUser·p0.999:  27.959 ms/op
                 existUser·p0.9999: 31.850 ms/op
                 existUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 175280
  mean =      5.478 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 74979 
    [ 5.000,  7.500) = 87596 
    [ 7.500, 10.000) = 8875 
    [10.000, 12.500) = 2700 
    [12.500, 15.000) = 708 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      6.881 ms/op
     p(95.0000) =      8.274 ms/op
     p(99.0000) =     11.616 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     31.457 ms/op
     p(99.9990) =     32.537 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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
# Warmup Iteration   1: 19.356 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 7.003 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.755 ±(99.9%) 0.025 ms/op
Iteration   1: 5.954 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.699 ms/op
                 getUser·p0.50:   5.382 ms/op
                 getUser·p0.90:   8.274 ms/op
                 getUser·p0.95:   10.027 ms/op
                 getUser·p0.99:   13.681 ms/op
                 getUser·p0.999:  23.472 ms/op
                 getUser·p0.9999: 30.671 ms/op
                 getUser·p1.00:   31.850 ms/op

Iteration   2: 5.537 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.892 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   6.660 ms/op
                 getUser·p0.95:   7.793 ms/op
                 getUser·p0.99:   11.469 ms/op
                 getUser·p0.999:  27.301 ms/op
                 getUser·p0.9999: 31.118 ms/op
                 getUser·p1.00:   32.735 ms/op

Iteration   3: 5.658 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.327 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   7.144 ms/op
                 getUser·p0.95:   8.847 ms/op
                 getUser·p0.99:   12.304 ms/op
                 getUser·p0.999:  28.908 ms/op
                 getUser·p0.9999: 36.899 ms/op
                 getUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168110
  mean =      5.711 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 56597 
    [ 5.000,  7.500) = 96235 
    [ 7.500, 10.000) = 9867 
    [10.000, 12.500) = 3466 
    [12.500, 15.000) = 1343 
    [15.000, 17.500) = 304 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 87 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.327 ms/op
     p(50.0000) =      5.276 ms/op
     p(90.0000) =      7.283 ms/op
     p(95.0000) =      8.962 ms/op
     p(99.0000) =     12.812 ms/op
     p(99.9000) =     26.342 ms/op
     p(99.9900) =     33.554 ms/op
     p(99.9990) =     37.945 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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
# Warmup Iteration   1: 21.456 ±(99.9%) 0.355 ms/op
# Warmup Iteration   2: 8.762 ±(99.9%) 0.069 ms/op
# Warmup Iteration   3: 6.764 ±(99.9%) 0.033 ms/op
Iteration   1: 6.616 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.019 ms/op
                 listUser·p0.50:   6.205 ms/op
                 listUser·p0.90:   7.949 ms/op
                 listUser·p0.95:   9.847 ms/op
                 listUser·p0.99:   13.517 ms/op
                 listUser·p0.999:  30.638 ms/op
                 listUser·p0.9999: 34.625 ms/op
                 listUser·p1.00:   37.093 ms/op

Iteration   2: 6.453 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.162 ms/op
                 listUser·p0.50:   6.013 ms/op
                 listUser·p0.90:   7.897 ms/op
                 listUser·p0.95:   9.339 ms/op
                 listUser·p0.99:   12.767 ms/op
                 listUser·p0.999:  31.733 ms/op
                 listUser·p0.9999: 43.057 ms/op
                 listUser·p1.00:   43.254 ms/op

Iteration   3: 6.459 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.830 ms/op
                 listUser·p0.50:   6.038 ms/op
                 listUser·p0.90:   8.086 ms/op
                 listUser·p0.95:   9.254 ms/op
                 listUser·p0.99:   12.337 ms/op
                 listUser·p0.999:  23.232 ms/op
                 listUser·p0.9999: 33.561 ms/op
                 listUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147402
  mean =      6.508 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6405 
    [ 5.000, 10.000) = 134956 
    [10.000, 15.000) = 5518 
    [15.000, 20.000) = 216 
    [20.000, 25.000) = 47 
    [25.000, 30.000) = 117 
    [30.000, 35.000) = 108 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      2.019 ms/op
     p(50.0000) =      6.087 ms/op
     p(90.0000) =      7.979 ms/op
     p(95.0000) =      9.470 ms/op
     p(99.0000) =     12.894 ms/op
     p(99.9000) =     29.884 ms/op
     p(99.9900) =     42.795 ms/op
     p(99.9990) =     43.223 ms/op
     p(99.9999) =     43.254 ms/op
    p(100.0000) =     43.254 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.548 ± 3.428  ops/ms
ClientPb.existUser                       thrpt       3   5.891 ± 2.235  ops/ms
ClientPb.getUser                         thrpt       3   5.606 ± 2.749  ops/ms
ClientPb.listUser                        thrpt       3   4.999 ± 0.148  ops/ms
ClientPb.createUser                       avgt       3   5.715 ± 2.176   ms/op
ClientPb.existUser                        avgt       3   5.232 ± 1.874   ms/op
ClientPb.getUser                          avgt       3   5.769 ± 2.206   ms/op
ClientPb.listUser                         avgt       3   6.812 ± 3.348   ms/op
ClientPb.createUser                     sample  172513   5.564 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.265           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.971           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.167           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.305           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.643           ms/op
ClientPb.createUser:createUser·p0.9999  sample          45.613           ms/op
ClientPb.createUser:createUser·p1.00    sample          49.545           ms/op
ClientPb.existUser                      sample  175280   5.478 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.843           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.120           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.881           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.274           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.616           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.759           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.457           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.030           ms/op
ClientPb.getUser                        sample  168110   5.711 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.327           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.276           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.283           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.962           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.812           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.342           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.554           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.945           ms/op
ClientPb.listUser                       sample  147402   6.508 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.019           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.087           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.979           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.470           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.894           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.884           ms/op
ClientPb.listUser:listUser·p0.9999      sample          42.795           ms/op
ClientPb.listUser:listUser·p1.00        sample          43.254           ms/op
