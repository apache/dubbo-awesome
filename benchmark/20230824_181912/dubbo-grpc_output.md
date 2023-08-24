# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.171 ops/ms
# Warmup Iteration   2: 8.359 ops/ms
# Warmup Iteration   3: 9.652 ops/ms
Iteration   1: 10.411 ops/ms
Iteration   2: 10.223 ops/ms
Iteration   3: 10.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.281 ±(99.9%) 2.061 ops/ms [Average]
  (min, avg, max) = (10.209, 10.281, 10.411), stdev = 0.113
  CI (99.9%): [8.220, 12.342] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.589 ops/ms
# Warmup Iteration   2: 10.516 ops/ms
# Warmup Iteration   3: 10.659 ops/ms
Iteration   1: 10.760 ops/ms
Iteration   2: 10.865 ops/ms
Iteration   3: 10.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.732 ±(99.9%) 2.724 ops/ms [Average]
  (min, avg, max) = (10.570, 10.732, 10.865), stdev = 0.149
  CI (99.9%): [8.008, 13.456] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.680 ops/ms
# Warmup Iteration   2: 9.687 ops/ms
# Warmup Iteration   3: 10.160 ops/ms
Iteration   1: 10.346 ops/ms
Iteration   2: 10.301 ops/ms
Iteration   3: 10.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.306 ±(99.9%) 0.701 ops/ms [Average]
  (min, avg, max) = (10.270, 10.306, 10.346), stdev = 0.038
  CI (99.9%): [9.605, 11.007] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.141 ops/ms
# Warmup Iteration   2: 7.506 ops/ms
# Warmup Iteration   3: 7.783 ops/ms
Iteration   1: 7.689 ops/ms
Iteration   2: 7.854 ops/ms
Iteration   3: 7.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.796 ±(99.9%) 1.693 ops/ms [Average]
  (min, avg, max) = (7.689, 7.796, 7.854), stdev = 0.093
  CI (99.9%): [6.103, 9.489] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.400 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.003 ms/op
Iteration   1: 3.076 ±(99.9%) 0.002 ms/op
Iteration   2: 3.117 ±(99.9%) 0.003 ms/op
Iteration   3: 3.131 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.108 ±(99.9%) 0.516 ms/op [Average]
  (min, avg, max) = (3.076, 3.108, 3.131), stdev = 0.028
  CI (99.9%): [2.592, 3.624] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.157 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.003 ms/op
Iteration   1: 2.928 ±(99.9%) 0.005 ms/op
Iteration   2: 3.002 ±(99.9%) 0.003 ms/op
Iteration   3: 2.918 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.949 ±(99.9%) 0.833 ms/op [Average]
  (min, avg, max) = (2.918, 2.949, 3.002), stdev = 0.046
  CI (99.9%): [2.117, 3.782] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.004 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.002 ms/op
Iteration   1: 3.104 ±(99.9%) 0.003 ms/op
Iteration   2: 3.115 ±(99.9%) 0.002 ms/op
Iteration   3: 3.119 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.113 ±(99.9%) 0.146 ms/op [Average]
  (min, avg, max) = (3.104, 3.113, 3.119), stdev = 0.008
  CI (99.9%): [2.967, 3.259] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.719 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.246 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.007 ms/op
Iteration   1: 4.106 ±(99.9%) 0.011 ms/op
Iteration   2: 4.085 ±(99.9%) 0.021 ms/op
Iteration   3: 4.093 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.094 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (4.085, 4.094, 4.106), stdev = 0.011
  CI (99.9%): [3.902, 4.287] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.429 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
Iteration   1: 3.114 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.989 ms/op
                 createUser·p0.999:  9.126 ms/op
                 createUser·p0.9999: 14.348 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  8.080 ms/op
                 createUser·p0.9999: 13.445 ms/op
                 createUser·p1.00:   13.615 ms/op

Iteration   3: 3.198 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.553 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  10.060 ms/op
                 createUser·p0.9999: 16.679 ms/op
                 createUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306630
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 817 
    [ 1.250,  2.500) = 15641 
    [ 2.500,  3.750) = 263818 
    [ 3.750,  5.000) = 23703 
    [ 5.000,  6.250) = 1586 
    [ 6.250,  7.500) = 502 
    [ 7.500,  8.750) = 256 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.891 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     15.653 ms/op
     p(99.9990) =     17.002 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.998 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.007 ms/op
Iteration   1: 2.960 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.596 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.819 ms/op
                 existUser·p0.999:  7.905 ms/op
                 existUser·p0.9999: 14.126 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   2: 3.006 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  7.454 ms/op
                 existUser·p0.9999: 14.369 ms/op
                 existUser·p1.00:   15.237 ms/op

Iteration   3: 2.973 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.989 ms/op
                 existUser·p0.999:  12.262 ms/op
                 existUser·p0.9999: 20.160 ms/op
                 existUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322183
  mean =      2.979 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31858 
    [ 2.500,  5.000) = 287684 
    [ 5.000,  7.500) = 2164 
    [ 7.500, 10.000) = 166 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     19.172 ms/op
     p(99.9990) =     20.531 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.628 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.007 ms/op
Iteration   1: 3.117 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.779 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  9.919 ms/op
                 getUser·p0.9999: 13.037 ms/op
                 getUser·p1.00:   13.386 ms/op

Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  7.522 ms/op
                 getUser·p0.9999: 14.143 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  7.292 ms/op
                 getUser·p0.9999: 27.676 ms/op
                 getUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310407
  mean =      3.092 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21724 
    [ 2.500,  5.000) = 286330 
    [ 5.000,  7.500) = 1899 
    [ 7.500, 10.000) = 266 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =      7.935 ms/op
     p(99.9900) =     25.230 ms/op
     p(99.9990) =     28.108 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.684 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.255 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.199 ±(99.9%) 0.012 ms/op
Iteration   1: 4.111 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  13.585 ms/op
                 listUser·p0.9999: 17.185 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   2: 4.203 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.119 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  15.758 ms/op
                 listUser·p0.9999: 21.665 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   3: 4.158 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.413 ms/op
                 listUser·p0.999:  16.469 ms/op
                 listUser·p0.9999: 21.670 ms/op
                 listUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230949
  mean =      4.157 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1769 
    [ 2.500,  5.000) = 200893 
    [ 5.000,  7.500) = 26026 
    [ 7.500, 10.000) = 1681 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     15.794 ms/op
     p(99.9900) =     21.195 ms/op
     p(99.9990) =     22.372 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.281 ± 2.061  ops/ms
ClientGrpc.existUser                       thrpt       3  10.732 ± 2.724  ops/ms
ClientGrpc.getUser                         thrpt       3  10.306 ± 0.701  ops/ms
ClientGrpc.listUser                        thrpt       3   7.796 ± 1.693  ops/ms
ClientGrpc.createUser                       avgt       3   3.108 ± 0.516   ms/op
ClientGrpc.existUser                        avgt       3   2.949 ± 0.833   ms/op
ClientGrpc.getUser                          avgt       3   3.113 ± 0.146   ms/op
ClientGrpc.listUser                         avgt       3   4.094 ± 0.192   ms/op
ClientGrpc.createUser                     sample  306630   3.129 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.553           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.891           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.782           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.653           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.138           ms/op
ClientGrpc.existUser                      sample  322183   2.979 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.543           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.772           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.817           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.602           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.172           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.611           ms/op
ClientGrpc.getUser                        sample  310407   3.092 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.776           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.751           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.935           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.230           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.180           ms/op
ClientGrpc.listUser                       sample  230949   4.157 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.225           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.969           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.186           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.923           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.471           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.794           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.195           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.643           ms/op
