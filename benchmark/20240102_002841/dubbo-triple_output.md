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
# Warmup Iteration   1: 4.715 ops/ms
# Warmup Iteration   2: 11.916 ops/ms
# Warmup Iteration   3: 12.357 ops/ms
Iteration   1: 12.673 ops/ms
Iteration   2: 12.688 ops/ms
Iteration   3: 12.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.702 ±(99.9%) 0.695 ops/ms [Average]
  (min, avg, max) = (12.673, 12.702, 12.745), stdev = 0.038
  CI (99.9%): [12.007, 13.397] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.151 ops/ms
# Warmup Iteration   2: 12.990 ops/ms
# Warmup Iteration   3: 13.092 ops/ms
Iteration   1: 13.077 ops/ms
Iteration   2: 13.131 ops/ms
Iteration   3: 13.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.072 ±(99.9%) 1.137 ops/ms [Average]
  (min, avg, max) = (13.007, 13.072, 13.131), stdev = 0.062
  CI (99.9%): [11.935, 14.208] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.116 ops/ms
# Warmup Iteration   2: 12.616 ops/ms
# Warmup Iteration   3: 12.550 ops/ms
Iteration   1: 12.909 ops/ms
Iteration   2: 12.833 ops/ms
Iteration   3: 12.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.859 ±(99.9%) 0.802 ops/ms [Average]
  (min, avg, max) = (12.833, 12.859, 12.909), stdev = 0.044
  CI (99.9%): [12.056, 13.661] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.876 ops/ms
# Warmup Iteration   2: 10.606 ops/ms
# Warmup Iteration   3: 10.703 ops/ms
Iteration   1: 10.608 ops/ms
Iteration   2: 10.588 ops/ms
Iteration   3: 10.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.636 ±(99.9%) 1.218 ops/ms [Average]
  (min, avg, max) = (10.588, 10.636, 10.713), stdev = 0.067
  CI (99.9%): [9.418, 11.855] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.137 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.004 ms/op
Iteration   1: 2.575 ±(99.9%) 0.004 ms/op
Iteration   2: 2.565 ±(99.9%) 0.004 ms/op
Iteration   3: 2.539 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.560 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (2.539, 2.560, 2.575), stdev = 0.019
  CI (99.9%): [2.218, 2.901] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.781 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.004 ms/op
Iteration   1: 2.453 ±(99.9%) 0.004 ms/op
Iteration   2: 2.422 ±(99.9%) 0.004 ms/op
Iteration   3: 2.407 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.427 ±(99.9%) 0.424 ms/op [Average]
  (min, avg, max) = (2.407, 2.427, 2.453), stdev = 0.023
  CI (99.9%): [2.004, 2.851] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.887 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
Iteration   1: 2.521 ±(99.9%) 0.004 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.489 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (2.468, 2.489, 2.521), stdev = 0.029
  CI (99.9%): [1.967, 3.011] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.750 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.005 ms/op
Iteration   1: 3.052 ±(99.9%) 0.007 ms/op
Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
Iteration   3: 3.066 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.057 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (3.052, 3.057, 3.066), stdev = 0.008
  CI (99.9%): [2.918, 3.196] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.227 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.730 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.610 ±(99.9%) 0.006 ms/op
Iteration   1: 2.571 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  7.269 ms/op
                 createUser·p0.9999: 14.329 ms/op
                 createUser·p1.00:   15.548 ms/op

Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.578 ms/op
                 createUser·p0.999:  8.184 ms/op
                 createUser·p0.9999: 13.189 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   3: 2.593 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  8.314 ms/op
                 createUser·p0.9999: 12.021 ms/op
                 createUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373142
  mean =      2.571 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 176374 
    [ 2.500,  3.750) = 193125 
    [ 3.750,  5.000) = 2751 
    [ 5.000,  6.250) = 394 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.662 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      7.541 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     15.029 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.799 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  8.591 ms/op
                 existUser·p0.9999: 15.026 ms/op
                 existUser·p1.00:   15.483 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  8.714 ms/op
                 existUser·p0.9999: 12.946 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.576 ms/op
                 existUser·p0.999:  8.192 ms/op
                 existUser·p0.9999: 12.403 ms/op
                 existUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385188
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 190123 
    [ 2.500,  3.750) = 192155 
    [ 3.750,  5.000) = 2142 
    [ 5.000,  6.250) = 259 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.568 ms/op
     p(99.9000) =      8.200 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     15.310 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.057 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
Iteration   1: 2.519 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  11.117 ms/op
                 getUser·p0.9999: 14.526 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   2: 2.570 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  10.109 ms/op
                 getUser·p0.9999: 20.203 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  8.386 ms/op
                 getUser·p0.9999: 12.630 ms/op
                 getUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376707
  mean =      2.546 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 184701 
    [ 2.500,  5.000) = 191360 
    [ 5.000,  7.500) = 248 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     15.254 ms/op
     p(99.9990) =     21.512 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.286 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.009 ms/op
Iteration   1: 3.067 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.767 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.334 ms/op
                 listUser·p0.9999: 12.763 ms/op
                 listUser·p1.00:   13.451 ms/op

Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 11.003 ms/op
                 listUser·p1.00:   11.764 ms/op

Iteration   3: 3.080 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.945 ms/op
                 listUser·p0.9999: 11.331 ms/op
                 listUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312521
  mean =      3.069 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 80672 
    [ 2.500,  3.750) = 188824 
    [ 3.750,  5.000) = 35046 
    [ 5.000,  6.250) = 6396 
    [ 6.250,  7.500) = 763 
    [ 7.500,  8.750) = 271 
    [ 8.750, 10.000) = 200 
    [10.000, 11.250) = 173 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.576 ms/op
     p(99.9900) =     12.132 ms/op
     p(99.9990) =     13.271 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.702 ± 0.695  ops/ms
ClientPb.existUser                       thrpt       3  13.072 ± 1.137  ops/ms
ClientPb.getUser                         thrpt       3  12.859 ± 0.802  ops/ms
ClientPb.listUser                        thrpt       3  10.636 ± 1.218  ops/ms
ClientPb.createUser                       avgt       3   2.560 ± 0.341   ms/op
ClientPb.existUser                        avgt       3   2.427 ± 0.424   ms/op
ClientPb.getUser                          avgt       3   2.489 ± 0.522   ms/op
ClientPb.listUser                         avgt       3   3.057 ± 0.139   ms/op
ClientPb.createUser                     sample  373142   2.571 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.904           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.662           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.541           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.550           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.269           ms/op
ClientPb.existUser                      sample  385188   2.490 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.888           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.200           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.566           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.483           ms/op
ClientPb.getUser                        sample  376707   2.546 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.801           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.438           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.254           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.970           ms/op
ClientPb.listUser                       sample  312521   3.069 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.767           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.576           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.132           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.451           ms/op
