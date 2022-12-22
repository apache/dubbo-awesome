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
# Warmup Iteration   1: 4.707 ops/ms
# Warmup Iteration   2: 9.827 ops/ms
# Warmup Iteration   3: 10.283 ops/ms
Iteration   1: 11.062 ops/ms
Iteration   2: 10.488 ops/ms
Iteration   3: 10.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.760 ±(99.9%) 5.259 ops/ms [Average]
  (min, avg, max) = (10.488, 10.760, 11.062), stdev = 0.288
  CI (99.9%): [5.502, 16.019] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.182 ops/ms
# Warmup Iteration   2: 10.622 ops/ms
# Warmup Iteration   3: 10.971 ops/ms
Iteration   1: 10.896 ops/ms
Iteration   2: 10.714 ops/ms
Iteration   3: 10.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.854 ±(99.9%) 2.283 ops/ms [Average]
  (min, avg, max) = (10.714, 10.854, 10.954), stdev = 0.125
  CI (99.9%): [8.571, 13.137] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.459 ops/ms
# Warmup Iteration   2: 10.183 ops/ms
# Warmup Iteration   3: 10.777 ops/ms
Iteration   1: 10.397 ops/ms
Iteration   2: 10.517 ops/ms
Iteration   3: 10.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.523 ±(99.9%) 2.342 ops/ms [Average]
  (min, avg, max) = (10.397, 10.523, 10.654), stdev = 0.128
  CI (99.9%): [8.180, 12.865] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.214 ops/ms
# Warmup Iteration   2: 7.729 ops/ms
# Warmup Iteration   3: 8.074 ops/ms
Iteration   1: 7.874 ops/ms
Iteration   2: 8.138 ops/ms
Iteration   3: 8.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.126 ±(99.9%) 4.471 ops/ms [Average]
  (min, avg, max) = (7.874, 8.126, 8.364), stdev = 0.245
  CI (99.9%): [3.654, 12.597] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.107 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.003 ms/op
Iteration   1: 3.126 ±(99.9%) 0.002 ms/op
Iteration   2: 3.112 ±(99.9%) 0.002 ms/op
Iteration   3: 3.065 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.101 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (3.065, 3.101, 3.126), stdev = 0.032
  CI (99.9%): [2.523, 3.679] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.812 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.009 ms/op
Iteration   2: 2.943 ±(99.9%) 0.002 ms/op
Iteration   3: 2.984 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.972 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (2.943, 2.972, 2.988), stdev = 0.025
  CI (99.9%): [2.514, 3.430] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.784 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.003 ms/op
Iteration   1: 3.035 ±(99.9%) 0.002 ms/op
Iteration   2: 3.022 ±(99.9%) 0.002 ms/op
Iteration   3: 2.994 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.017 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (2.994, 3.017, 3.035), stdev = 0.021
  CI (99.9%): [2.638, 3.396] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.053 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.029 ms/op
Iteration   1: 4.058 ±(99.9%) 0.043 ms/op
Iteration   2: 3.904 ±(99.9%) 0.026 ms/op
Iteration   3: 3.918 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.960 ±(99.9%) 1.555 ms/op [Average]
  (min, avg, max) = (3.904, 3.960, 4.058), stdev = 0.085
  CI (99.9%): [2.405, 5.515] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.913 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
Iteration   1: 2.988 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.604 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  7.239 ms/op
                 createUser·p0.9999: 11.684 ms/op
                 createUser·p1.00:   12.222 ms/op

Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.596 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  8.623 ms/op
                 createUser·p0.9999: 18.759 ms/op
                 createUser·p1.00:   19.038 ms/op

Iteration   3: 3.005 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.509 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.547 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  11.638 ms/op
                 createUser·p0.9999: 20.393 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318963
  mean =      3.012 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23566 
    [ 2.500,  5.000) = 294416 
    [ 5.000,  7.500) = 529 
    [ 7.500, 10.000) = 164 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.631 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  6.768 ms/op
                 existUser·p0.9999: 11.256 ms/op
                 existUser·p1.00:   11.452 ms/op

Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.980 ms/op
                 existUser·p0.9999: 13.806 ms/op
                 existUser·p1.00:   15.335 ms/op

Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  6.354 ms/op
                 existUser·p0.9999: 18.195 ms/op
                 existUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323043
  mean =      2.969 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1540 
    [ 1.250,  2.500) = 46664 
    [ 2.500,  3.750) = 252348 
    [ 3.750,  5.000) = 21588 
    [ 5.000,  6.250) = 493 
    [ 6.250,  7.500) = 162 
    [ 7.500,  8.750) = 87 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.897 ms/op
     p(99.9900) =     15.655 ms/op
     p(99.9990) =     18.375 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.007 ms/op
Iteration   1: 3.008 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  6.685 ms/op
                 getUser·p0.9999: 19.837 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  6.048 ms/op
                 getUser·p0.9999: 15.991 ms/op
                 getUser·p1.00:   16.466 ms/op

Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.428 ms/op
                 getUser·p0.9999: 16.531 ms/op
                 getUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317306
  mean =      3.023 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32987 
    [ 2.500,  5.000) = 283371 
    [ 5.000,  7.500) = 706 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.053 ms/op
     p(99.9900) =     18.743 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 4.394 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.011 ms/op
Iteration   1: 3.921 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  12.410 ms/op
                 listUser·p0.9999: 15.276 ms/op
                 listUser·p1.00:   16.417 ms/op

Iteration   2: 3.976 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  16.922 ms/op
                 listUser·p0.9999: 23.001 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 3.919 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.678 ms/op
                 listUser·p0.999:  14.500 ms/op
                 listUser·p0.9999: 16.668 ms/op
                 listUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243797
  mean =      3.939 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5204 
    [ 2.500,  5.000) = 210057 
    [ 5.000,  7.500) = 27390 
    [ 7.500, 10.000) = 690 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     22.466 ms/op
     p(99.9990) =     23.466 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.760 ± 5.259  ops/ms
ClientGrpc.existUser                       thrpt       3  10.854 ± 2.283  ops/ms
ClientGrpc.getUser                         thrpt       3  10.523 ± 2.342  ops/ms
ClientGrpc.listUser                        thrpt       3   8.126 ± 4.471  ops/ms
ClientGrpc.createUser                       avgt       3   3.101 ± 0.578   ms/op
ClientGrpc.existUser                        avgt       3   2.972 ± 0.458   ms/op
ClientGrpc.getUser                          avgt       3   3.017 ± 0.379   ms/op
ClientGrpc.listUser                         avgt       3   3.960 ± 1.555   ms/op
ClientGrpc.createUser                     sample  318963   3.012 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.509           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.457           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.227           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.765           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.185           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.709           ms/op
ClientGrpc.existUser                      sample  323043   2.969 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.594           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.834           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.897           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.655           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.416           ms/op
ClientGrpc.getUser                        sample  317306   3.023 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.644           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.053           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.743           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.513           ms/op
ClientGrpc.listUser                       sample  243797   3.939 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.788           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.844           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.466           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.527           ms/op
