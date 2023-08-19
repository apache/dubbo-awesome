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
# Warmup Iteration   1: 4.698 ops/ms
# Warmup Iteration   2: 9.773 ops/ms
# Warmup Iteration   3: 10.334 ops/ms
Iteration   1: 10.625 ops/ms
Iteration   2: 10.584 ops/ms
Iteration   3: 10.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.615 ±(99.9%) 0.511 ops/ms [Average]
  (min, avg, max) = (10.584, 10.615, 10.637), stdev = 0.028
  CI (99.9%): [10.104, 11.127] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.949 ops/ms
# Warmup Iteration   2: 10.715 ops/ms
# Warmup Iteration   3: 10.897 ops/ms
Iteration   1: 11.117 ops/ms
Iteration   2: 11.311 ops/ms
Iteration   3: 11.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.209 ±(99.9%) 1.777 ops/ms [Average]
  (min, avg, max) = (11.117, 11.209, 11.311), stdev = 0.097
  CI (99.9%): [9.432, 12.986] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.706 ops/ms
# Warmup Iteration   2: 10.442 ops/ms
# Warmup Iteration   3: 10.583 ops/ms
Iteration   1: 10.772 ops/ms
Iteration   2: 10.776 ops/ms
Iteration   3: 10.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.786 ±(99.9%) 0.393 ops/ms [Average]
  (min, avg, max) = (10.772, 10.786, 10.811), stdev = 0.022
  CI (99.9%): [10.394, 11.179] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.927 ops/ms
# Warmup Iteration   2: 7.971 ops/ms
# Warmup Iteration   3: 8.230 ops/ms
Iteration   1: 8.159 ops/ms
Iteration   2: 8.127 ops/ms
Iteration   3: 8.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.197 ±(99.9%) 1.716 ops/ms [Average]
  (min, avg, max) = (8.127, 8.197, 8.303), stdev = 0.094
  CI (99.9%): [6.481, 9.912] (assumes normal distribution)


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.003 ms/op
Iteration   1: 3.024 ±(99.9%) 0.003 ms/op
Iteration   2: 3.016 ±(99.9%) 0.016 ms/op
Iteration   3: 2.995 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.012 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (2.995, 3.012, 3.024), stdev = 0.015
  CI (99.9%): [2.742, 3.281] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.855 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.864 ±(99.9%) 0.003 ms/op
Iteration   1: 2.783 ±(99.9%) 0.005 ms/op
Iteration   2: 2.934 ±(99.9%) 0.003 ms/op
Iteration   3: 2.813 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.843 ±(99.9%) 1.456 ms/op [Average]
  (min, avg, max) = (2.783, 2.843, 2.934), stdev = 0.080
  CI (99.9%): [1.387, 4.300] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.924 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.003 ms/op
Iteration   1: 3.022 ±(99.9%) 0.002 ms/op
Iteration   2: 3.056 ±(99.9%) 0.001 ms/op
Iteration   3: 2.999 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.026 ±(99.9%) 0.530 ms/op [Average]
  (min, avg, max) = (2.999, 3.026, 3.056), stdev = 0.029
  CI (99.9%): [2.495, 3.556] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.183 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.987 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.013 ms/op
Iteration   1: 3.923 ±(99.9%) 0.015 ms/op
Iteration   2: 3.910 ±(99.9%) 0.008 ms/op
Iteration   3: 3.861 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.898 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (3.861, 3.898, 3.923), stdev = 0.032
  CI (99.9%): [3.308, 4.488] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.172 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
Iteration   1: 2.970 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.594 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.815 ms/op
                 createUser·p0.9999: 16.424 ms/op
                 createUser·p1.00:   16.613 ms/op

Iteration   2: 2.964 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  9.568 ms/op
                 createUser·p0.9999: 12.894 ms/op
                 createUser·p1.00:   13.074 ms/op

Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.538 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  7.444 ms/op
                 createUser·p0.9999: 14.123 ms/op
                 createUser·p1.00:   14.828 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321928
  mean =      2.981 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1806 
    [ 1.250,  2.500) = 29454 
    [ 2.500,  3.750) = 273726 
    [ 3.750,  5.000) = 14811 
    [ 5.000,  6.250) = 1112 
    [ 6.250,  7.500) = 591 
    [ 7.500,  8.750) = 152 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      8.126 ms/op
     p(99.9900) =     15.833 ms/op
     p(99.9990) =     16.548 ms/op
     p(99.9999) =     16.613 ms/op
    p(100.0000) =     16.613 ms/op


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
# Warmup Iteration   1: 3.726 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.962 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.007 ms/op
Iteration   1: 2.868 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  9.617 ms/op
                 existUser·p0.9999: 12.217 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   2: 2.862 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.552 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.492 ms/op
                 existUser·p0.999:  7.274 ms/op
                 existUser·p0.9999: 14.235 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   3: 2.813 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  7.531 ms/op
                 existUser·p0.9999: 16.646 ms/op
                 existUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337061
  mean =      2.848 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6771 
    [ 1.250,  2.500) = 49813 
    [ 2.500,  3.750) = 267029 
    [ 3.750,  5.000) = 11867 
    [ 5.000,  6.250) = 801 
    [ 6.250,  7.500) = 415 
    [ 7.500,  8.750) = 111 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.660 ms/op
     p(99.9900) =     16.213 ms/op
     p(99.9990) =     18.293 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 3.949 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.007 ms/op
Iteration   1: 3.043 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.685 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  7.277 ms/op
                 getUser·p0.9999: 12.066 ms/op
                 getUser·p1.00:   12.386 ms/op

Iteration   2: 3.021 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  6.989 ms/op
                 getUser·p0.9999: 20.245 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   3: 3.012 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.693 ms/op
                 getUser·p0.9999: 25.047 ms/op
                 getUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317297
  mean =      3.025 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22120 
    [ 2.500,  5.000) = 293601 
    [ 5.000,  7.500) = 1344 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.119 ms/op
     p(99.9900) =     23.113 ms/op
     p(99.9990) =     25.428 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 5.441 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.010 ms/op
Iteration   1: 3.908 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  11.895 ms/op
                 listUser·p0.9999: 13.298 ms/op
                 listUser·p1.00:   13.615 ms/op

Iteration   2: 3.909 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.811 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.249 ms/op
                 listUser·p0.9999: 19.840 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   3: 3.916 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  17.029 ms/op
                 listUser·p0.9999: 21.414 ms/op
                 listUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245311
  mean =      3.911 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5975 
    [ 2.500,  5.000) = 216488 
    [ 5.000,  7.500) = 21585 
    [ 7.500, 10.000) = 836 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     13.916 ms/op
     p(99.9900) =     20.447 ms/op
     p(99.9990) =     24.141 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.615 ± 0.511  ops/ms
ClientGrpc.existUser                       thrpt       3  11.209 ± 1.777  ops/ms
ClientGrpc.getUser                         thrpt       3  10.786 ± 0.393  ops/ms
ClientGrpc.listUser                        thrpt       3   8.197 ± 1.716  ops/ms
ClientGrpc.createUser                       avgt       3   3.012 ± 0.270   ms/op
ClientGrpc.existUser                        avgt       3   2.843 ± 1.456   ms/op
ClientGrpc.getUser                          avgt       3   3.026 ± 0.530   ms/op
ClientGrpc.listUser                         avgt       3   3.898 ± 0.590   ms/op
ClientGrpc.createUser                     sample  321928   2.981 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.538           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.126           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.833           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.613           ms/op
ClientGrpc.existUser                      sample  337061   2.848 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.547           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.660           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.213           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.448           ms/op
ClientGrpc.getUser                        sample  317297   3.025 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.530           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.119           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.113           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.657           ms/op
ClientGrpc.listUser                       sample  245311   3.911 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.219           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.916           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.447           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.216           ms/op
