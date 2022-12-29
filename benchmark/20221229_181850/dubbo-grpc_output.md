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
# Warmup Iteration   1: 4.730 ops/ms
# Warmup Iteration   2: 10.108 ops/ms
# Warmup Iteration   3: 10.388 ops/ms
Iteration   1: 10.489 ops/ms
Iteration   2: 10.319 ops/ms
Iteration   3: 10.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.337 ±(99.9%) 2.614 ops/ms [Average]
  (min, avg, max) = (10.204, 10.337, 10.489), stdev = 0.143
  CI (99.9%): [7.723, 12.952] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.500 ops/ms
# Warmup Iteration   2: 10.609 ops/ms
# Warmup Iteration   3: 10.745 ops/ms
Iteration   1: 10.719 ops/ms
Iteration   2: 11.138 ops/ms
Iteration   3: 10.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.941 ±(99.9%) 3.840 ops/ms [Average]
  (min, avg, max) = (10.719, 10.941, 11.138), stdev = 0.210
  CI (99.9%): [7.101, 14.781] (assumes normal distribution)


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
# Warmup Iteration   1: 7.352 ops/ms
# Warmup Iteration   2: 10.218 ops/ms
# Warmup Iteration   3: 10.401 ops/ms
Iteration   1: 10.528 ops/ms
Iteration   2: 10.682 ops/ms
Iteration   3: 10.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.548 ±(99.9%) 2.278 ops/ms [Average]
  (min, avg, max) = (10.434, 10.548, 10.682), stdev = 0.125
  CI (99.9%): [8.270, 12.826] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.868 ops/ms
# Warmup Iteration   2: 7.760 ops/ms
# Warmup Iteration   3: 7.952 ops/ms
Iteration   1: 8.171 ops/ms
Iteration   2: 8.066 ops/ms
Iteration   3: 8.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.161 ±(99.9%) 1.660 ops/ms [Average]
  (min, avg, max) = (8.066, 8.161, 8.247), stdev = 0.091
  CI (99.9%): [6.501, 9.822] (assumes normal distribution)


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
# Warmup Iteration   1: 4.062 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.001 ms/op
Iteration   1: 3.161 ±(99.9%) 0.002 ms/op
Iteration   2: 3.093 ±(99.9%) 0.001 ms/op
Iteration   3: 3.140 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.131 ±(99.9%) 0.639 ms/op [Average]
  (min, avg, max) = (3.093, 3.131, 3.161), stdev = 0.035
  CI (99.9%): [2.492, 3.771] (assumes normal distribution)


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
# Warmup Iteration   1: 3.586 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.889 ±(99.9%) 0.003 ms/op
Iteration   1: 2.961 ±(99.9%) 0.004 ms/op
Iteration   2: 2.915 ±(99.9%) 0.002 ms/op
Iteration   3: 2.885 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.920 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (2.885, 2.920, 2.961), stdev = 0.038
  CI (99.9%): [2.221, 3.619] (assumes normal distribution)


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
# Warmup Iteration   1: 3.919 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.003 ms/op
Iteration   1: 3.019 ±(99.9%) 0.002 ms/op
Iteration   2: 3.159 ±(99.9%) 0.003 ms/op
Iteration   3: 3.099 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.092 ±(99.9%) 1.287 ms/op [Average]
  (min, avg, max) = (3.019, 3.092, 3.159), stdev = 0.071
  CI (99.9%): [1.805, 4.379] (assumes normal distribution)


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
# Warmup Iteration   1: 5.025 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.026 ms/op
Iteration   1: 3.921 ±(99.9%) 0.016 ms/op
Iteration   2: 4.000 ±(99.9%) 0.017 ms/op
Iteration   3: 4.004 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.975 ±(99.9%) 0.856 ms/op [Average]
  (min, avg, max) = (3.921, 3.975, 4.004), stdev = 0.047
  CI (99.9%): [3.119, 4.831] (assumes normal distribution)


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
# Warmup Iteration   1: 3.923 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
Iteration   1: 3.053 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  9.066 ms/op
                 createUser·p0.9999: 21.825 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   2: 3.135 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  6.101 ms/op
                 createUser·p0.9999: 16.089 ms/op
                 createUser·p1.00:   16.597 ms/op

Iteration   3: 3.104 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.586 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  6.258 ms/op
                 createUser·p0.9999: 17.652 ms/op
                 createUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309926
  mean =      3.097 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27771 
    [ 2.500,  5.000) = 281228 
    [ 5.000,  7.500) = 651 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.013 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     22.768 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.937 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.904 ±(99.9%) 0.007 ms/op
Iteration   1: 2.866 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.467 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.278 ms/op
                 existUser·p0.9999: 12.348 ms/op
                 existUser·p1.00:   12.698 ms/op

Iteration   2: 2.831 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  6.103 ms/op
                 existUser·p0.9999: 16.358 ms/op
                 existUser·p1.00:   17.334 ms/op

Iteration   3: 2.941 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.551 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  6.802 ms/op
                 existUser·p0.9999: 16.456 ms/op
                 existUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333307
  mean =      2.878 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3744 
    [ 1.250,  2.500) = 48517 
    [ 2.500,  3.750) = 269706 
    [ 3.750,  5.000) = 10738 
    [ 5.000,  6.250) = 243 
    [ 6.250,  7.500) = 166 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      6.412 ms/op
     p(99.9900) =     16.248 ms/op
     p(99.9990) =     17.291 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 3.908 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
Iteration   1: 2.990 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.474 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.055 ms/op
                 getUser·p0.999:  6.455 ms/op
                 getUser·p0.9999: 14.673 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   2: 3.052 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.361 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  8.054 ms/op
                 getUser·p0.9999: 19.891 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   3: 3.072 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  6.611 ms/op
                 getUser·p0.9999: 31.018 ms/op
                 getUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316025
  mean =      3.038 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24571 
    [ 2.500,  5.000) = 290411 
    [ 5.000,  7.500) = 701 
    [ 7.500, 10.000) = 150 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.361 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.684 ms/op
     p(99.9900) =     30.304 ms/op
     p(99.9990) =     31.293 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 5.234 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.009 ±(99.9%) 0.011 ms/op
Iteration   1: 4.032 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.624 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  11.960 ms/op
                 listUser·p0.9999: 19.344 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   2: 3.861 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.720 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.437 ms/op
                 listUser·p0.999:  13.290 ms/op
                 listUser·p0.9999: 20.480 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   3: 3.964 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  13.402 ms/op
                 listUser·p0.9999: 16.564 ms/op
                 listUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243050
  mean =      3.951 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5607 
    [ 2.500,  5.000) = 210558 
    [ 5.000,  7.500) = 25991 
    [ 7.500, 10.000) = 519 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     20.316 ms/op
     p(99.9990) =     22.235 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.337 ± 2.614  ops/ms
ClientGrpc.existUser                       thrpt       3  10.941 ± 3.840  ops/ms
ClientGrpc.getUser                         thrpt       3  10.548 ± 2.278  ops/ms
ClientGrpc.listUser                        thrpt       3   8.161 ± 1.660  ops/ms
ClientGrpc.createUser                       avgt       3   3.131 ± 0.639   ms/op
ClientGrpc.existUser                        avgt       3   2.920 ± 0.699   ms/op
ClientGrpc.getUser                          avgt       3   3.092 ± 1.287   ms/op
ClientGrpc.listUser                         avgt       3   3.975 ± 0.856   ms/op
ClientGrpc.createUser                     sample  309926   3.097 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.586           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.013           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.234           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.872           ms/op
ClientGrpc.existUser                      sample  333307   2.878 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.467           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.412           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.248           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.334           ms/op
ClientGrpc.getUser                        sample  316025   3.038 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.361           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.684           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.304           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.392           ms/op
ClientGrpc.listUser                       sample  243050   3.951 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.624           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.206           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.316           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.315           ms/op
