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
# Warmup Iteration   1: 0.861 ops/ms
# Warmup Iteration   2: 2.061 ops/ms
# Warmup Iteration   3: 4.353 ops/ms
Iteration   1: 5.134 ops/ms
Iteration   2: 5.416 ops/ms
Iteration   3: 5.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.384 ±(99.9%) 4.300 ops/ms [Average]
  (min, avg, max) = (5.134, 5.384, 5.602), stdev = 0.236
  CI (99.9%): [1.084, 9.684] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:19
# Fork: 1 of 1
# Warmup Iteration   1: 1.336 ops/ms
# Warmup Iteration   2: 4.363 ops/ms
# Warmup Iteration   3: 5.601 ops/ms
Iteration   1: 5.797 ops/ms
Iteration   2: 5.699 ops/ms
Iteration   3: 5.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.709 ±(99.9%) 1.513 ops/ms [Average]
  (min, avg, max) = (5.632, 5.709, 5.797), stdev = 0.083
  CI (99.9%): [4.196, 7.222] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.420 ops/ms
# Warmup Iteration   2: 4.025 ops/ms
# Warmup Iteration   3: 5.386 ops/ms
Iteration   1: 5.402 ops/ms
Iteration   2: 5.383 ops/ms
Iteration   3: 5.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.403 ±(99.9%) 0.353 ops/ms [Average]
  (min, avg, max) = (5.383, 5.403, 5.422), stdev = 0.019
  CI (99.9%): [5.049, 5.756] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.457 ops/ms
# Warmup Iteration   2: 3.509 ops/ms
# Warmup Iteration   3: 4.581 ops/ms
Iteration   1: 4.592 ops/ms
Iteration   2: 4.595 ops/ms
Iteration   3: 4.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.618 ±(99.9%) 0.781 ops/ms [Average]
  (min, avg, max) = (4.592, 4.618, 4.668), stdev = 0.043
  CI (99.9%): [3.838, 5.399] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 23.222 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 8.722 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.940 ±(99.9%) 0.010 ms/op
Iteration   1: 6.080 ±(99.9%) 0.012 ms/op
Iteration   2: 5.964 ±(99.9%) 0.013 ms/op
Iteration   3: 5.985 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.010 ±(99.9%) 1.126 ms/op [Average]
  (min, avg, max) = (5.964, 6.010, 6.080), stdev = 0.062
  CI (99.9%): [4.884, 7.136] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 19.316 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.758 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.560 ±(99.9%) 0.017 ms/op
Iteration   1: 5.652 ±(99.9%) 0.010 ms/op
Iteration   2: 5.561 ±(99.9%) 0.014 ms/op
Iteration   3: 5.570 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.594 ±(99.9%) 0.912 ms/op [Average]
  (min, avg, max) = (5.561, 5.594, 5.652), stdev = 0.050
  CI (99.9%): [4.682, 6.507] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 18.209 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.650 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.877 ±(99.9%) 0.012 ms/op
Iteration   1: 6.171 ±(99.9%) 0.010 ms/op
Iteration   2: 5.814 ±(99.9%) 0.011 ms/op
Iteration   3: 5.920 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.968 ±(99.9%) 3.340 ms/op [Average]
  (min, avg, max) = (5.814, 5.968, 6.171), stdev = 0.183
  CI (99.9%): [2.629, 9.308] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 20.846 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 9.339 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 7.200 ±(99.9%) 0.017 ms/op
Iteration   1: 6.880 ±(99.9%) 0.015 ms/op
Iteration   2: 6.857 ±(99.9%) 0.014 ms/op
Iteration   3: 7.106 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.948 ±(99.9%) 2.514 ms/op [Average]
  (min, avg, max) = (6.857, 6.948, 7.106), stdev = 0.138
  CI (99.9%): [4.434, 9.462] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:27
# Fork: 1 of 1
# Warmup Iteration   1: 19.399 ±(99.9%) 0.384 ms/op
# Warmup Iteration   2: 8.455 ±(99.9%) 0.070 ms/op
# Warmup Iteration   3: 6.427 ±(99.9%) 0.033 ms/op
Iteration   1: 5.885 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.749 ms/op
                 createUser·p0.50:   5.505 ms/op
                 createUser·p0.90:   7.340 ms/op
                 createUser·p0.95:   8.667 ms/op
                 createUser·p0.99:   11.731 ms/op
                 createUser·p0.999:  25.482 ms/op
                 createUser·p0.9999: 29.893 ms/op
                 createUser·p1.00:   32.539 ms/op

Iteration   2: 6.136 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.347 ms/op
                 createUser·p0.50:   5.685 ms/op
                 createUser·p0.90:   7.840 ms/op
                 createUser·p0.95:   9.404 ms/op
                 createUser·p0.99:   13.124 ms/op
                 createUser·p0.999:  28.459 ms/op
                 createUser·p0.9999: 37.080 ms/op
                 createUser·p1.00:   40.698 ms/op

Iteration   3: 6.078 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.806 ms/op
                 createUser·p0.50:   5.743 ms/op
                 createUser·p0.90:   7.528 ms/op
                 createUser·p0.95:   8.831 ms/op
                 createUser·p0.99:   11.370 ms/op
                 createUser·p0.999:  23.036 ms/op
                 createUser·p0.9999: 40.402 ms/op
                 createUser·p1.00:   43.188 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 159039
  mean =      6.031 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 27195 
    [ 5.000, 10.000) = 127426 
    [10.000, 15.000) = 3850 
    [15.000, 20.000) = 289 
    [20.000, 25.000) = 109 
    [25.000, 30.000) = 92 
    [30.000, 35.000) = 33 
    [35.000, 40.000) = 34 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.749 ms/op
     p(50.0000) =      5.636 ms/op
     p(90.0000) =      7.561 ms/op
     p(95.0000) =      8.978 ms/op
     p(99.0000) =     12.042 ms/op
     p(99.9000) =     25.459 ms/op
     p(99.9900) =     39.596 ms/op
     p(99.9990) =     43.150 ms/op
     p(99.9999) =     43.188 ms/op
    p(100.0000) =     43.188 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 19.897 ±(99.9%) 0.342 ms/op
# Warmup Iteration   2: 7.920 ±(99.9%) 0.067 ms/op
# Warmup Iteration   3: 6.021 ±(99.9%) 0.026 ms/op
Iteration   1: 5.739 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   5.366 ms/op
                 existUser·p0.90:   7.291 ms/op
                 existUser·p0.95:   8.258 ms/op
                 existUser·p0.99:   11.120 ms/op
                 existUser·p0.999:  25.934 ms/op
                 existUser·p0.9999: 33.620 ms/op
                 existUser·p1.00:   34.472 ms/op

Iteration   2: 5.662 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.437 ms/op
                 existUser·p0.50:   5.308 ms/op
                 existUser·p0.90:   7.021 ms/op
                 existUser·p0.95:   8.258 ms/op
                 existUser·p0.99:   11.436 ms/op
                 existUser·p0.999:  17.859 ms/op
                 existUser·p0.9999: 31.644 ms/op
                 existUser·p1.00:   32.276 ms/op

Iteration   3: 5.805 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.445 ms/op
                 existUser·p0.50:   5.456 ms/op
                 existUser·p0.90:   7.234 ms/op
                 existUser·p0.95:   8.259 ms/op
                 existUser·p0.99:   11.190 ms/op
                 existUser·p0.999:  31.387 ms/op
                 existUser·p0.9999: 40.206 ms/op
                 existUser·p1.00:   41.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 167250
  mean =      5.735 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 46179 
    [ 5.000, 10.000) = 118054 
    [10.000, 15.000) = 2651 
    [15.000, 20.000) = 183 
    [20.000, 25.000) = 30 
    [25.000, 30.000) = 30 
    [30.000, 35.000) = 91 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      7.184 ms/op
     p(95.0000) =      8.258 ms/op
     p(99.0000) =     11.239 ms/op
     p(99.9000) =     22.789 ms/op
     p(99.9900) =     38.422 ms/op
     p(99.9990) =     40.976 ms/op
     p(99.9999) =     41.681 ms/op
    p(100.0000) =     41.681 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.607 ±(99.9%) 0.332 ms/op
# Warmup Iteration   2: 8.174 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 6.052 ±(99.9%) 0.026 ms/op
Iteration   1: 5.859 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.126 ms/op
                 getUser·p0.50:   5.538 ms/op
                 getUser·p0.90:   7.266 ms/op
                 getUser·p0.95:   8.333 ms/op
                 getUser·p0.99:   12.468 ms/op
                 getUser·p0.999:  20.611 ms/op
                 getUser·p0.9999: 26.313 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   2: 5.904 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.974 ms/op
                 getUser·p0.50:   5.562 ms/op
                 getUser·p0.90:   7.250 ms/op
                 getUser·p0.95:   8.421 ms/op
                 getUser·p0.99:   11.862 ms/op
                 getUser·p0.999:  26.504 ms/op
                 getUser·p0.9999: 30.605 ms/op
                 getUser·p1.00:   31.097 ms/op

Iteration   3: 5.961 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   3.006 ms/op
                 getUser·p0.50:   5.571 ms/op
                 getUser·p0.90:   7.291 ms/op
                 getUser·p0.95:   8.946 ms/op
                 getUser·p0.99:   12.648 ms/op
                 getUser·p0.999:  29.110 ms/op
                 getUser·p0.9999: 32.229 ms/op
                 getUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 162359
  mean =      5.908 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 28757 
    [ 5.000,  7.500) = 119718 
    [ 7.500, 10.000) = 9503 
    [10.000, 12.500) = 2906 
    [12.500, 15.000) = 919 
    [15.000, 17.500) = 253 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.974 ms/op
     p(50.0000) =      5.554 ms/op
     p(90.0000) =      7.266 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     12.255 ms/op
     p(99.9000) =     23.433 ms/op
     p(99.9900) =     31.654 ms/op
     p(99.9990) =     33.151 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 22.100 ±(99.9%) 0.404 ms/op
# Warmup Iteration   2: 9.382 ±(99.9%) 0.075 ms/op
# Warmup Iteration   3: 7.236 ±(99.9%) 0.035 ms/op
Iteration   1: 6.991 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   6.545 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   10.027 ms/op
                 listUser·p0.99:   13.763 ms/op
                 listUser·p0.999:  30.983 ms/op
                 listUser·p0.9999: 38.394 ms/op
                 listUser·p1.00:   39.322 ms/op

Iteration   2: 6.877 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.677 ms/op
                 listUser·p0.50:   6.357 ms/op
                 listUser·p0.90:   8.585 ms/op
                 listUser·p0.95:   10.191 ms/op
                 listUser·p0.99:   13.848 ms/op
                 listUser·p0.999:  30.062 ms/op
                 listUser·p0.9999: 32.649 ms/op
                 listUser·p1.00:   34.603 ms/op

Iteration   3: 7.067 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   6.603 ms/op
                 listUser·p0.90:   8.880 ms/op
                 listUser·p0.95:   10.387 ms/op
                 listUser·p0.99:   13.468 ms/op
                 listUser·p0.999:  28.580 ms/op
                 listUser·p0.9999: 36.141 ms/op
                 listUser·p1.00:   38.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 137565
  mean =      6.977 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 2117 
    [ 5.000,  7.500) = 106735 
    [ 7.500, 10.000) = 21081 
    [10.000, 12.500) = 5501 
    [12.500, 15.000) = 1190 
    [15.000, 17.500) = 417 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 76 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.677 ms/op
     p(50.0000) =      6.504 ms/op
     p(90.0000) =      8.651 ms/op
     p(95.0000) =     10.240 ms/op
     p(99.0000) =     13.664 ms/op
     p(99.9000) =     30.226 ms/op
     p(99.9900) =     37.797 ms/op
     p(99.9990) =     39.149 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.384 ± 4.300  ops/ms
ClientPb.existUser                       thrpt       3   5.709 ± 1.513  ops/ms
ClientPb.getUser                         thrpt       3   5.403 ± 0.353  ops/ms
ClientPb.listUser                        thrpt       3   4.618 ± 0.781  ops/ms
ClientPb.createUser                       avgt       3   6.010 ± 1.126   ms/op
ClientPb.existUser                        avgt       3   5.594 ± 0.912   ms/op
ClientPb.getUser                          avgt       3   5.968 ± 3.340   ms/op
ClientPb.listUser                         avgt       3   6.948 ± 2.514   ms/op
ClientPb.createUser                     sample  159039   6.031 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.749           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.636           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.561           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.978           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.042           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.459           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.596           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.188           ms/op
ClientPb.existUser                      sample  167250   5.735 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.825           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.374           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.184           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.258           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.239           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.789           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.422           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.681           ms/op
ClientPb.getUser                        sample  162359   5.908 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.974           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.554           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.266           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.536           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.255           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.433           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.654           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.948           ms/op
ClientPb.listUser                       sample  137565   6.977 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.677           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.504           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.240           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.664           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.226           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.797           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.322           ms/op
