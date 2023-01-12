# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.061 ops/ms
# Warmup Iteration   2: 2.498 ops/ms
# Warmup Iteration   3: 5.190 ops/ms
Iteration   1: 5.618 ops/ms
Iteration   2: 5.755 ops/ms
Iteration   3: 5.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.780 ±(99.9%) 3.191 ops/ms [Average]
  (min, avg, max) = (5.618, 5.780, 5.966), stdev = 0.175
  CI (99.9%): [2.589, 8.971] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.612 ops/ms
# Warmup Iteration   2: 4.490 ops/ms
# Warmup Iteration   3: 5.960 ops/ms
Iteration   1: 5.686 ops/ms
Iteration   2: 6.149 ops/ms
Iteration   3: 6.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.980 ±(99.9%) 4.661 ops/ms [Average]
  (min, avg, max) = (5.686, 5.980, 6.149), stdev = 0.255
  CI (99.9%): [1.319, 10.641] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.622 ops/ms
# Warmup Iteration   2: 4.747 ops/ms
# Warmup Iteration   3: 5.783 ops/ms
Iteration   1: 5.856 ops/ms
Iteration   2: 5.767 ops/ms
Iteration   3: 5.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.848 ±(99.9%) 1.416 ops/ms [Average]
  (min, avg, max) = (5.767, 5.848, 5.922), stdev = 0.078
  CI (99.9%): [4.432, 7.264] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.435 ops/ms
# Warmup Iteration   2: 4.030 ops/ms
# Warmup Iteration   3: 4.776 ops/ms
Iteration   1: 4.982 ops/ms
Iteration   2: 4.919 ops/ms
Iteration   3: 5.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.003 ±(99.9%) 1.749 ops/ms [Average]
  (min, avg, max) = (4.919, 5.003, 5.107), stdev = 0.096
  CI (99.9%): [3.253, 6.752] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 19.106 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 6.382 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.506 ±(99.9%) 0.018 ms/op
Iteration   1: 5.608 ±(99.9%) 0.010 ms/op
Iteration   2: 5.541 ±(99.9%) 0.010 ms/op
Iteration   3: 5.392 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.514 ±(99.9%) 2.017 ms/op [Average]
  (min, avg, max) = (5.392, 5.514, 5.608), stdev = 0.111
  CI (99.9%): [3.497, 7.530] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 18.182 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 6.363 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.420 ±(99.9%) 0.007 ms/op
Iteration   1: 5.118 ±(99.9%) 0.010 ms/op
Iteration   2: 5.067 ±(99.9%) 0.012 ms/op
Iteration   3: 5.160 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.115 ±(99.9%) 0.854 ms/op [Average]
  (min, avg, max) = (5.067, 5.115, 5.160), stdev = 0.047
  CI (99.9%): [4.261, 5.969] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 19.631 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.560 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.707 ±(99.9%) 0.008 ms/op
Iteration   1: 5.424 ±(99.9%) 0.013 ms/op
Iteration   2: 5.469 ±(99.9%) 0.011 ms/op
Iteration   3: 5.329 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.407 ±(99.9%) 1.312 ms/op [Average]
  (min, avg, max) = (5.329, 5.407, 5.469), stdev = 0.072
  CI (99.9%): [4.096, 6.719] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 17.226 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 8.371 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.383 ±(99.9%) 0.012 ms/op
Iteration   1: 6.328 ±(99.9%) 0.015 ms/op
Iteration   2: 6.099 ±(99.9%) 0.018 ms/op
Iteration   3: 6.081 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.169 ±(99.9%) 2.513 ms/op [Average]
  (min, avg, max) = (6.081, 6.169, 6.328), stdev = 0.138
  CI (99.9%): [3.656, 8.682] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 18.390 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 6.805 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.823 ±(99.9%) 0.026 ms/op
Iteration   1: 5.576 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   5.251 ms/op
                 createUser·p0.90:   6.996 ms/op
                 createUser·p0.95:   8.036 ms/op
                 createUser·p0.99:   11.022 ms/op
                 createUser·p0.999:  22.348 ms/op
                 createUser·p0.9999: 32.425 ms/op
                 createUser·p1.00:   32.866 ms/op

Iteration   2: 5.501 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.884 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   6.840 ms/op
                 createUser·p0.95:   7.995 ms/op
                 createUser·p0.99:   11.174 ms/op
                 createUser·p0.999:  24.280 ms/op
                 createUser·p0.9999: 36.910 ms/op
                 createUser·p1.00:   38.404 ms/op

Iteration   3: 5.537 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   5.169 ms/op
                 createUser·p0.90:   7.021 ms/op
                 createUser·p0.95:   8.282 ms/op
                 createUser·p0.99:   11.256 ms/op
                 createUser·p0.999:  25.559 ms/op
                 createUser·p0.9999: 28.614 ms/op
                 createUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173119
  mean =      5.538 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 69612 
    [ 5.000,  7.500) = 90772 
    [ 7.500, 10.000) = 9595 
    [10.000, 12.500) = 1993 
    [12.500, 15.000) = 519 
    [15.000, 17.500) = 310 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      8.094 ms/op
     p(99.0000) =     11.158 ms/op
     p(99.9000) =     23.999 ms/op
     p(99.9900) =     33.315 ms/op
     p(99.9990) =     37.542 ms/op
     p(99.9999) =     38.404 ms/op
    p(100.0000) =     38.404 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.442 ±(99.9%) 0.259 ms/op
# Warmup Iteration   2: 6.023 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.332 ±(99.9%) 0.022 ms/op
Iteration   1: 5.234 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.443 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.586 ms/op
                 existUser·p0.95:   7.739 ms/op
                 existUser·p0.99:   10.724 ms/op
                 existUser·p0.999:  19.586 ms/op
                 existUser·p0.9999: 25.515 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   2: 5.309 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.331 ms/op
                 existUser·p0.50:   4.899 ms/op
                 existUser·p0.90:   6.914 ms/op
                 existUser·p0.95:   8.077 ms/op
                 existUser·p0.99:   10.753 ms/op
                 existUser·p0.999:  22.787 ms/op
                 existUser·p0.9999: 33.554 ms/op
                 existUser·p1.00:   35.324 ms/op

Iteration   3: 5.264 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.335 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.521 ms/op
                 existUser·p0.95:   7.586 ms/op
                 existUser·p0.99:   10.224 ms/op
                 existUser·p0.999:  15.090 ms/op
                 existUser·p0.9999: 28.604 ms/op
                 existUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182139
  mean =      5.269 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 100198 
    [ 5.000,  7.500) = 70854 
    [ 7.500, 10.000) = 8530 
    [10.000, 12.500) = 1602 
    [12.500, 15.000) = 541 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.443 ms/op
     p(50.0000) =      4.915 ms/op
     p(90.0000) =      6.668 ms/op
     p(95.0000) =      7.832 ms/op
     p(99.0000) =     10.561 ms/op
     p(99.9000) =     18.299 ms/op
     p(99.9900) =     32.983 ms/op
     p(99.9990) =     35.109 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.635 ±(99.9%) 0.298 ms/op
# Warmup Iteration   2: 6.514 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.642 ±(99.9%) 0.022 ms/op
Iteration   1: 5.464 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   6.816 ms/op
                 getUser·p0.95:   7.963 ms/op
                 getUser·p0.99:   11.348 ms/op
                 getUser·p0.999:  22.282 ms/op
                 getUser·p0.9999: 29.669 ms/op
                 getUser·p1.00:   36.962 ms/op

Iteration   2: 5.463 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.408 ms/op
                 getUser·p0.50:   5.104 ms/op
                 getUser·p0.90:   6.865 ms/op
                 getUser·p0.95:   8.159 ms/op
                 getUser·p0.99:   11.059 ms/op
                 getUser·p0.999:  22.524 ms/op
                 getUser·p0.9999: 29.610 ms/op
                 getUser·p1.00:   30.867 ms/op

Iteration   3: 5.508 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.183 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   6.906 ms/op
                 getUser·p0.95:   8.167 ms/op
                 getUser·p0.99:   11.600 ms/op
                 getUser·p0.999:  27.409 ms/op
                 getUser·p0.9999: 36.070 ms/op
                 getUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 175043
  mean =      5.479 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 75711 
    [ 5.000,  7.500) = 86825 
    [ 7.500, 10.000) = 9306 
    [10.000, 12.500) = 1982 
    [12.500, 15.000) = 669 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      6.849 ms/op
     p(95.0000) =      8.118 ms/op
     p(99.0000) =     11.387 ms/op
     p(99.9000) =     22.542 ms/op
     p(99.9900) =     34.701 ms/op
     p(99.9990) =     36.716 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.601 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 8.178 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.488 ±(99.9%) 0.027 ms/op
Iteration   1: 6.262 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   5.939 ms/op
                 listUser·p0.90:   7.610 ms/op
                 listUser·p0.95:   8.847 ms/op
                 listUser·p0.99:   11.272 ms/op
                 listUser·p0.999:  26.309 ms/op
                 listUser·p0.9999: 29.127 ms/op
                 listUser·p1.00:   29.590 ms/op

Iteration   2: 6.078 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   7.528 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   12.091 ms/op
                 listUser·p0.999:  27.591 ms/op
                 listUser·p0.9999: 36.535 ms/op
                 listUser·p1.00:   43.516 ms/op

Iteration   3: 6.436 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.523 ms/op
                 listUser·p0.50:   6.029 ms/op
                 listUser·p0.90:   8.053 ms/op
                 listUser·p0.95:   9.485 ms/op
                 listUser·p0.99:   12.917 ms/op
                 listUser·p0.999:  26.116 ms/op
                 listUser·p0.9999: 28.740 ms/op
                 listUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 153462
  mean =      6.255 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 11316 
    [ 5.000, 10.000) = 137763 
    [10.000, 15.000) = 3709 
    [15.000, 20.000) = 339 
    [20.000, 25.000) = 76 
    [25.000, 30.000) = 227 
    [30.000, 35.000) = 9 
    [35.000, 40.000) = 20 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      5.857 ms/op
     p(90.0000) =      7.725 ms/op
     p(95.0000) =      9.060 ms/op
     p(99.0000) =     12.157 ms/op
     p(99.9000) =     26.461 ms/op
     p(99.9900) =     35.848 ms/op
     p(99.9990) =     43.271 ms/op
     p(99.9999) =     43.516 ms/op
    p(100.0000) =     43.516 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.780 ± 3.191  ops/ms
ClientPb.existUser                       thrpt       3   5.980 ± 4.661  ops/ms
ClientPb.getUser                         thrpt       3   5.848 ± 1.416  ops/ms
ClientPb.listUser                        thrpt       3   5.003 ± 1.749  ops/ms
ClientPb.createUser                       avgt       3   5.514 ± 2.017   ms/op
ClientPb.existUser                        avgt       3   5.115 ± 0.854   ms/op
ClientPb.getUser                          avgt       3   5.407 ± 1.312   ms/op
ClientPb.listUser                         avgt       3   6.169 ± 2.513   ms/op
ClientPb.createUser                     sample  173119   5.538 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.818           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.194           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.955           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.094           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.158           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.999           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.315           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.404           ms/op
ClientPb.existUser                      sample  182139   5.269 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.443           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.668           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.832           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.561           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.299           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.983           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.324           ms/op
ClientPb.getUser                        sample  175043   5.479 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.300           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.120           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.849           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.118           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.387           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.542           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.701           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.962           ms/op
ClientPb.listUser                       sample  153462   6.255 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.523           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.857           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.725           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.060           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.157           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.461           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.848           ms/op
ClientPb.listUser:listUser·p1.00        sample          43.516           ms/op
