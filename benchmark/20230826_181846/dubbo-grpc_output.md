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
# Warmup Iteration   1: 3.161 ops/ms
# Warmup Iteration   2: 7.113 ops/ms
# Warmup Iteration   3: 8.270 ops/ms
Iteration   1: 8.528 ops/ms
Iteration   2: 8.572 ops/ms
Iteration   3: 8.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.583 ±(99.9%) 1.132 ops/ms [Average]
  (min, avg, max) = (8.528, 8.583, 8.650), stdev = 0.062
  CI (99.9%): [7.451, 9.716] (assumes normal distribution)


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
# Warmup Iteration   1: 6.225 ops/ms
# Warmup Iteration   2: 8.698 ops/ms
# Warmup Iteration   3: 8.926 ops/ms
Iteration   1: 9.060 ops/ms
Iteration   2: 9.077 ops/ms
Iteration   3: 9.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.072 ±(99.9%) 0.190 ops/ms [Average]
  (min, avg, max) = (9.060, 9.072, 9.079), stdev = 0.010
  CI (99.9%): [8.882, 9.262] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.263 ops/ms
# Warmup Iteration   2: 8.200 ops/ms
# Warmup Iteration   3: 8.528 ops/ms
Iteration   1: 8.328 ops/ms
Iteration   2: 8.962 ops/ms
Iteration   3: 8.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.660 ±(99.9%) 5.806 ops/ms [Average]
  (min, avg, max) = (8.328, 8.660, 8.962), stdev = 0.318
  CI (99.9%): [2.855, 14.466] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.805 ops/ms
# Warmup Iteration   2: 5.963 ops/ms
# Warmup Iteration   3: 6.236 ops/ms
Iteration   1: 6.282 ops/ms
Iteration   2: 6.455 ops/ms
Iteration   3: 6.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.432 ±(99.9%) 2.547 ops/ms [Average]
  (min, avg, max) = (6.282, 6.432, 6.559), stdev = 0.140
  CI (99.9%): [3.886, 8.979] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.050 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.003 ms/op
Iteration   1: 3.657 ±(99.9%) 0.004 ms/op
Iteration   2: 3.724 ±(99.9%) 0.004 ms/op
Iteration   3: 3.708 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.696 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.657, 3.696, 3.724), stdev = 0.035
  CI (99.9%): [3.054, 4.339] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.096 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.004 ms/op
Iteration   1: 3.579 ±(99.9%) 0.003 ms/op
Iteration   2: 3.468 ±(99.9%) 0.004 ms/op
Iteration   3: 3.595 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.547 ±(99.9%) 1.262 ms/op [Average]
  (min, avg, max) = (3.468, 3.547, 3.595), stdev = 0.069
  CI (99.9%): [2.285, 4.810] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.514 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.981 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.004 ms/op
Iteration   1: 3.724 ±(99.9%) 0.004 ms/op
Iteration   2: 3.741 ±(99.9%) 0.003 ms/op
Iteration   3: 3.739 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.734 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (3.724, 3.734, 3.741), stdev = 0.009
  CI (99.9%): [3.566, 3.902] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.852 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.037 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.898 ±(99.9%) 0.014 ms/op
Iteration   1: 4.836 ±(99.9%) 0.016 ms/op
Iteration   2: 4.739 ±(99.9%) 0.013 ms/op
Iteration   3: 4.799 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.792 ±(99.9%) 0.893 ms/op [Average]
  (min, avg, max) = (4.739, 4.792, 4.836), stdev = 0.049
  CI (99.9%): [3.899, 5.684] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.387 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.010 ms/op
Iteration   1: 3.655 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  8.958 ms/op
                 createUser·p0.9999: 15.122 ms/op
                 createUser·p1.00:   15.385 ms/op

Iteration   2: 3.720 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  12.090 ms/op
                 createUser·p0.9999: 16.967 ms/op
                 createUser·p1.00:   17.400 ms/op

Iteration   3: 3.625 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  14.025 ms/op
                 createUser·p0.9999: 21.610 ms/op
                 createUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 262065
  mean =      3.666 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7376 
    [ 2.500,  5.000) = 246392 
    [ 5.000,  7.500) = 7146 
    [ 7.500, 10.000) = 798 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     11.076 ms/op
     p(99.9900) =     19.542 ms/op
     p(99.9990) =     22.176 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.029 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.522 ±(99.9%) 0.009 ms/op
Iteration   1: 3.517 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  8.899 ms/op
                 existUser·p0.9999: 16.873 ms/op
                 existUser·p1.00:   18.350 ms/op

Iteration   2: 3.538 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   6.397 ms/op
                 existUser·p0.999:  11.661 ms/op
                 existUser·p0.9999: 16.679 ms/op
                 existUser·p1.00:   17.170 ms/op

Iteration   3: 3.511 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  11.762 ms/op
                 existUser·p0.9999: 19.137 ms/op
                 existUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272328
  mean =      3.522 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 300 
    [ 1.250,  2.500) = 11300 
    [ 2.500,  3.750) = 190715 
    [ 3.750,  5.000) = 62457 
    [ 5.000,  6.250) = 5236 
    [ 6.250,  7.500) = 1100 
    [ 7.500,  8.750) = 542 
    [ 8.750, 10.000) = 322 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     11.272 ms/op
     p(99.9900) =     19.005 ms/op
     p(99.9990) =     19.694 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.431 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.729 ±(99.9%) 0.009 ms/op
Iteration   1: 3.680 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  10.633 ms/op
                 getUser·p0.9999: 19.157 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   2: 3.648 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  12.084 ms/op
                 getUser·p0.9999: 23.681 ms/op
                 getUser·p1.00:   25.395 ms/op

Iteration   3: 3.666 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  11.047 ms/op
                 getUser·p0.9999: 22.219 ms/op
                 getUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261958
  mean =      3.665 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7729 
    [ 2.500,  5.000) = 245231 
    [ 5.000,  7.500) = 7983 
    [ 7.500, 10.000) = 698 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     11.043 ms/op
     p(99.9900) =     22.604 ms/op
     p(99.9990) =     25.342 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 6.611 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.440 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.893 ±(99.9%) 0.016 ms/op
Iteration   1: 4.784 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.011 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.997 ms/op
                 listUser·p0.95:   6.865 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  15.237 ms/op
                 listUser·p0.9999: 20.195 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   2: 4.868 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.620 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.185 ms/op
                 listUser·p0.95:   6.898 ms/op
                 listUser·p0.99:   8.612 ms/op
                 listUser·p0.999:  17.703 ms/op
                 listUser·p0.9999: 28.798 ms/op
                 listUser·p1.00:   29.065 ms/op

Iteration   3: 4.683 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   6.021 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  19.848 ms/op
                 listUser·p0.9999: 21.993 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200924
  mean =      4.777 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 508 
    [ 2.500,  5.000) = 147733 
    [ 5.000,  7.500) = 46924 
    [ 7.500, 10.000) = 4853 
    [10.000, 12.500) = 468 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      6.087 ms/op
     p(95.0000) =      6.930 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     16.746 ms/op
     p(99.9900) =     27.352 ms/op
     p(99.9990) =     29.031 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.583 ± 1.132  ops/ms
ClientGrpc.existUser                       thrpt       3   9.072 ± 0.190  ops/ms
ClientGrpc.getUser                         thrpt       3   8.660 ± 5.806  ops/ms
ClientGrpc.listUser                        thrpt       3   6.432 ± 2.547  ops/ms
ClientGrpc.createUser                       avgt       3   3.696 ± 0.643   ms/op
ClientGrpc.existUser                        avgt       3   3.547 ± 1.262   ms/op
ClientGrpc.getUser                          avgt       3   3.734 ± 0.168   ms/op
ClientGrpc.listUser                         avgt       3   4.792 ± 0.893   ms/op
ClientGrpc.createUser                     sample  262065   3.666 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.682           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.144           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.076           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.542           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.282           ms/op
ClientGrpc.existUser                      sample  272328   3.522 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.647           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.988           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.272           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.005           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.825           ms/op
ClientGrpc.getUser                        sample  261958   3.665 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.793           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.776           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.103           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.043           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.604           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.395           ms/op
ClientGrpc.listUser                       sample  200924   4.777 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.620           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.555           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.667           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.746           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.352           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.065           ms/op
