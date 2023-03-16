# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.411 ops/ms
# Warmup Iteration   2: 9.578 ops/ms
# Warmup Iteration   3: 10.265 ops/ms
Iteration   1: 11.310 ops/ms
Iteration   2: 10.767 ops/ms
Iteration   3: 10.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.973 ±(99.9%) 5.368 ops/ms [Average]
  (min, avg, max) = (10.767, 10.973, 11.310), stdev = 0.294
  CI (99.9%): [5.605, 16.341] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.839 ops/ms
# Warmup Iteration   2: 10.715 ops/ms
# Warmup Iteration   3: 11.144 ops/ms
Iteration   1: 11.073 ops/ms
Iteration   2: 11.359 ops/ms
Iteration   3: 11.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.315 ±(99.9%) 4.071 ops/ms [Average]
  (min, avg, max) = (11.073, 11.315, 11.513), stdev = 0.223
  CI (99.9%): [7.244, 15.386] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 6.864 ops/ms
# Warmup Iteration   2: 10.265 ops/ms
# Warmup Iteration   3: 10.576 ops/ms
Iteration   1: 10.799 ops/ms
Iteration   2: 10.833 ops/ms
Iteration   3: 10.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.734 ±(99.9%) 2.605 ops/ms [Average]
  (min, avg, max) = (10.570, 10.734, 10.833), stdev = 0.143
  CI (99.9%): [8.129, 13.339] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.548 ops/ms
# Warmup Iteration   2: 7.611 ops/ms
# Warmup Iteration   3: 7.961 ops/ms
Iteration   1: 8.026 ops/ms
Iteration   2: 8.225 ops/ms
Iteration   3: 8.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.224 ±(99.9%) 3.609 ops/ms [Average]
  (min, avg, max) = (8.026, 8.224, 8.421), stdev = 0.198
  CI (99.9%): [4.615, 11.833] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.191 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.010 ms/op
Iteration   1: 3.040 ±(99.9%) 0.007 ms/op
Iteration   2: 3.002 ±(99.9%) 0.003 ms/op
Iteration   3: 2.965 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.002 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (2.965, 3.002, 3.040), stdev = 0.037
  CI (99.9%): [2.318, 3.686] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.139 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.862 ±(99.9%) 0.003 ms/op
Iteration   1: 2.777 ±(99.9%) 0.002 ms/op
Iteration   2: 2.857 ±(99.9%) 0.002 ms/op
Iteration   3: 2.859 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.831 ±(99.9%) 0.852 ms/op [Average]
  (min, avg, max) = (2.777, 2.831, 2.859), stdev = 0.047
  CI (99.9%): [1.979, 3.683] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.159 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.004 ms/op
Iteration   1: 3.044 ±(99.9%) 0.005 ms/op
Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
Iteration   3: 2.980 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.008 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (2.980, 3.008, 3.044), stdev = 0.033
  CI (99.9%): [2.404, 3.612] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.092 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.019 ms/op
Iteration   1: 3.878 ±(99.9%) 0.015 ms/op
Iteration   2: 3.902 ±(99.9%) 0.020 ms/op
Iteration   3: 3.888 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.889 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (3.878, 3.889, 3.902), stdev = 0.012
  CI (99.9%): [3.666, 4.112] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.019 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
Iteration   1: 2.952 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  6.406 ms/op
                 createUser·p0.9999: 12.686 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   2: 2.998 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  11.494 ms/op
                 createUser·p0.9999: 15.707 ms/op
                 createUser·p1.00:   16.105 ms/op

Iteration   3: 2.973 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.521 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  6.745 ms/op
                 createUser·p0.9999: 25.894 ms/op
                 createUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322815
  mean =      2.974 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35411 
    [ 2.500,  5.000) = 285584 
    [ 5.000,  7.500) = 1454 
    [ 7.500, 10.000) = 125 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      7.929 ms/op
     p(99.9900) =     21.576 ms/op
     p(99.9990) =     26.371 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.941 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.962 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.006 ms/op
Iteration   1: 2.881 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  6.750 ms/op
                 existUser·p0.9999: 11.711 ms/op
                 existUser·p1.00:   12.141 ms/op

Iteration   2: 2.851 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  7.537 ms/op
                 existUser·p0.9999: 13.644 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   3: 2.889 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  9.273 ms/op
                 existUser·p0.9999: 16.941 ms/op
                 existUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333715
  mean =      2.874 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 961 
    [ 1.250,  2.500) = 43123 
    [ 2.500,  3.750) = 282119 
    [ 3.750,  5.000) = 6589 
    [ 5.000,  6.250) = 418 
    [ 6.250,  7.500) = 176 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.297 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =      7.438 ms/op
     p(99.9900) =     15.051 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.089 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  7.453 ms/op
                 getUser·p0.9999: 13.479 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.619 ms/op
                 getUser·p0.9999: 13.461 ms/op
                 getUser·p1.00:   13.877 ms/op

Iteration   3: 3.049 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.392 ms/op
                 getUser·p0.9999: 16.777 ms/op
                 getUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317704
  mean =      3.019 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 834 
    [ 1.250,  2.500) = 24827 
    [ 2.500,  3.750) = 276225 
    [ 3.750,  5.000) = 14465 
    [ 5.000,  6.250) = 791 
    [ 6.250,  7.500) = 313 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.080 ms/op
     p(99.9900) =     16.153 ms/op
     p(99.9990) =     19.944 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.720 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.011 ms/op
Iteration   1: 3.882 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  13.314 ms/op
                 listUser·p0.9999: 17.891 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   2: 3.931 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.886 ms/op
                 listUser·p0.999:  14.746 ms/op
                 listUser·p0.9999: 16.281 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 3.935 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.968 ms/op
                 listUser·p0.9999: 27.319 ms/op
                 listUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245139
  mean =      3.916 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3687 
    [ 2.500,  5.000) = 219589 
    [ 5.000,  7.500) = 20596 
    [ 7.500, 10.000) = 796 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     14.104 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     27.492 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.973 ± 5.368  ops/ms
ClientGrpc.existUser                       thrpt       3  11.315 ± 4.071  ops/ms
ClientGrpc.getUser                         thrpt       3  10.734 ± 2.605  ops/ms
ClientGrpc.listUser                        thrpt       3   8.224 ± 3.609  ops/ms
ClientGrpc.createUser                       avgt       3   3.002 ± 0.684   ms/op
ClientGrpc.existUser                        avgt       3   2.831 ± 0.852   ms/op
ClientGrpc.getUser                          avgt       3   3.008 ± 0.604   ms/op
ClientGrpc.listUser                         avgt       3   3.889 ± 0.223   ms/op
ClientGrpc.createUser                     sample  322815   2.974 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.521           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.929           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.576           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.492           ms/op
ClientGrpc.existUser                      sample  333715   2.874 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.758           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.297           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.166           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.438           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.051           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.007           ms/op
ClientGrpc.getUser                        sample  317704   3.019 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.774           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.080           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.153           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.956           ms/op
ClientGrpc.listUser                       sample  245139   3.916 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.945           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.104           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.804           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.591           ms/op
