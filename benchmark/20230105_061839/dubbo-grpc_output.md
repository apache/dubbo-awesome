# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.357 ops/ms
# Warmup Iteration   2: 7.253 ops/ms
# Warmup Iteration   3: 8.490 ops/ms
Iteration   1: 8.646 ops/ms
Iteration   2: 8.778 ops/ms
Iteration   3: 8.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.715 ±(99.9%) 1.206 ops/ms [Average]
  (min, avg, max) = (8.646, 8.715, 8.778), stdev = 0.066
  CI (99.9%): [7.509, 9.921] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.096 ops/ms
# Warmup Iteration   2: 8.695 ops/ms
# Warmup Iteration   3: 9.086 ops/ms
Iteration   1: 8.972 ops/ms
Iteration   2: 8.965 ops/ms
Iteration   3: 9.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.025 ±(99.9%) 1.797 ops/ms [Average]
  (min, avg, max) = (8.965, 9.025, 9.139), stdev = 0.098
  CI (99.9%): [7.228, 10.822] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.521 ops/ms
# Warmup Iteration   2: 8.591 ops/ms
# Warmup Iteration   3: 8.607 ops/ms
Iteration   1: 9.109 ops/ms
Iteration   2: 8.685 ops/ms
Iteration   3: 8.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.889 ±(99.9%) 3.874 ops/ms [Average]
  (min, avg, max) = (8.685, 8.889, 9.109), stdev = 0.212
  CI (99.9%): [5.016, 12.763] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.526 ops/ms
# Warmup Iteration   2: 6.488 ops/ms
# Warmup Iteration   3: 6.692 ops/ms
Iteration   1: 6.833 ops/ms
Iteration   2: 6.732 ops/ms
Iteration   3: 6.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.837 ±(99.9%) 1.951 ops/ms [Average]
  (min, avg, max) = (6.732, 6.837, 6.946), stdev = 0.107
  CI (99.9%): [4.886, 8.788] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.049 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.002 ms/op
Iteration   1: 3.704 ±(99.9%) 0.004 ms/op
Iteration   2: 3.697 ±(99.9%) 0.003 ms/op
Iteration   3: 3.750 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.717 ±(99.9%) 0.523 ms/op [Average]
  (min, avg, max) = (3.697, 3.717, 3.750), stdev = 0.029
  CI (99.9%): [3.194, 4.240] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.862 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.002 ms/op
Iteration   1: 3.495 ±(99.9%) 0.003 ms/op
Iteration   2: 3.565 ±(99.9%) 0.003 ms/op
Iteration   3: 3.521 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.527 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (3.495, 3.527, 3.565), stdev = 0.035
  CI (99.9%): [2.883, 4.171] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.197 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.005 ms/op
Iteration   1: 3.789 ±(99.9%) 0.002 ms/op
Iteration   2: 3.674 ±(99.9%) 0.005 ms/op
Iteration   3: 3.633 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.699 ±(99.9%) 1.479 ms/op [Average]
  (min, avg, max) = (3.633, 3.699, 3.789), stdev = 0.081
  CI (99.9%): [2.220, 5.177] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.461 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.885 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.702 ±(99.9%) 0.009 ms/op
Iteration   1: 4.737 ±(99.9%) 0.010 ms/op
Iteration   2: 4.613 ±(99.9%) 0.004 ms/op
Iteration   3: 4.682 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.678 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (4.613, 4.678, 4.737), stdev = 0.062
  CI (99.9%): [3.542, 5.813] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.217 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.963 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.009 ms/op
Iteration   1: 3.595 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  11.895 ms/op
                 createUser·p0.9999: 15.126 ms/op
                 createUser·p1.00:   15.548 ms/op

Iteration   2: 3.731 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  11.108 ms/op
                 createUser·p0.9999: 17.297 ms/op
                 createUser·p1.00:   17.859 ms/op

Iteration   3: 3.659 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  7.878 ms/op
                 createUser·p0.9999: 24.519 ms/op
                 createUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 262105
  mean =      3.661 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7532 
    [ 2.500,  5.000) = 248474 
    [ 5.000,  7.500) = 5532 
    [ 7.500, 10.000) = 273 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     11.125 ms/op
     p(99.9900) =     24.216 ms/op
     p(99.9990) =     24.699 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.962 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.700 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.535 ±(99.9%) 0.008 ms/op
Iteration   1: 3.527 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  8.154 ms/op
                 existUser·p0.9999: 14.170 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   2: 3.514 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  7.368 ms/op
                 existUser·p0.9999: 16.174 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   3: 3.505 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   3.473 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   5.046 ms/op
                 existUser·p0.999:  7.028 ms/op
                 existUser·p0.9999: 17.924 ms/op
                 existUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 273176
  mean =      3.515 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 398 
    [ 1.250,  2.500) = 12694 
    [ 2.500,  3.750) = 170887 
    [ 3.750,  5.000) = 85574 
    [ 5.000,  6.250) = 2962 
    [ 6.250,  7.500) = 340 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.136 ms/op
     p(99.9000) =      7.766 ms/op
     p(99.9900) =     16.898 ms/op
     p(99.9990) =     18.293 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.085 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.720 ±(99.9%) 0.009 ms/op
Iteration   1: 3.634 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.618 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  8.864 ms/op
                 getUser·p0.9999: 19.700 ms/op
                 getUser·p1.00:   20.021 ms/op

Iteration   2: 3.642 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.407 ms/op
                 getUser·p0.999:  8.700 ms/op
                 getUser·p0.9999: 21.569 ms/op
                 getUser·p1.00:   21.856 ms/op

Iteration   3: 3.695 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   5.145 ms/op
                 getUser·p0.999:  7.274 ms/op
                 getUser·p0.9999: 21.868 ms/op
                 getUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262346
  mean =      3.657 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8041 
    [ 2.500,  5.000) = 249738 
    [ 5.000,  7.500) = 4153 
    [ 7.500, 10.000) = 255 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =      8.328 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     24.056 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.130 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.832 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.761 ±(99.9%) 0.014 ms/op
Iteration   1: 4.608 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.228 ms/op
                 listUser·p0.99:   8.122 ms/op
                 listUser·p0.999:  14.416 ms/op
                 listUser·p0.9999: 23.696 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   2: 4.708 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.454 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.726 ms/op
                 listUser·p0.95:   6.455 ms/op
                 listUser·p0.99:   7.897 ms/op
                 listUser·p0.999:  16.024 ms/op
                 listUser·p0.9999: 21.135 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   3: 4.736 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.923 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  18.920 ms/op
                 listUser·p0.9999: 22.076 ms/op
                 listUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 205160
  mean =      4.683 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 334 
    [ 2.500,  5.000) = 162513 
    [ 5.000,  7.500) = 38466 
    [ 7.500, 10.000) = 3362 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.669 ms/op
     p(95.0000) =      6.463 ms/op
     p(99.0000) =      8.077 ms/op
     p(99.9000) =     16.775 ms/op
     p(99.9900) =     23.052 ms/op
     p(99.9990) =     24.112 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.715 ± 1.206  ops/ms
ClientGrpc.existUser                       thrpt       3   9.025 ± 1.797  ops/ms
ClientGrpc.getUser                         thrpt       3   8.889 ± 3.874  ops/ms
ClientGrpc.listUser                        thrpt       3   6.837 ± 1.951  ops/ms
ClientGrpc.createUser                       avgt       3   3.717 ± 0.523   ms/op
ClientGrpc.existUser                        avgt       3   3.527 ± 0.644   ms/op
ClientGrpc.getUser                          avgt       3   3.699 ± 1.479   ms/op
ClientGrpc.listUser                         avgt       3   4.678 ± 1.135   ms/op
ClientGrpc.createUser                     sample  262105   3.661 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.746           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.694           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.125           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.216           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.838           ms/op
ClientGrpc.existUser                      sample  273176   3.515 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.753           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.136           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.766           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.898           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.842           ms/op
ClientGrpc.getUser                        sample  262346   3.657 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.618           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.328           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.561           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.183           ms/op
ClientGrpc.listUser                       sample  205160   4.683 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.998           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.463           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.077           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.775           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.052           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.150           ms/op
