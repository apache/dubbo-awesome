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
# Warmup Iteration   1: 3.597 ops/ms
# Warmup Iteration   2: 8.111 ops/ms
# Warmup Iteration   3: 9.834 ops/ms
Iteration   1: 9.817 ops/ms
Iteration   2: 10.193 ops/ms
Iteration   3: 10.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.083 ±(99.9%) 4.217 ops/ms [Average]
  (min, avg, max) = (9.817, 10.083, 10.238), stdev = 0.231
  CI (99.9%): [5.866, 14.299] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.491 ops/ms
# Warmup Iteration   2: 10.119 ops/ms
# Warmup Iteration   3: 10.446 ops/ms
Iteration   1: 10.592 ops/ms
Iteration   2: 10.688 ops/ms
Iteration   3: 10.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.584 ±(99.9%) 1.986 ops/ms [Average]
  (min, avg, max) = (10.471, 10.584, 10.688), stdev = 0.109
  CI (99.9%): [8.598, 12.570] (assumes normal distribution)


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
# Warmup Iteration   1: 5.929 ops/ms
# Warmup Iteration   2: 9.362 ops/ms
# Warmup Iteration   3: 9.977 ops/ms
Iteration   1: 10.090 ops/ms
Iteration   2: 9.850 ops/ms
Iteration   3: 9.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.857 ±(99.9%) 4.202 ops/ms [Average]
  (min, avg, max) = (9.630, 9.857, 10.090), stdev = 0.230
  CI (99.9%): [5.655, 14.058] (assumes normal distribution)


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
# Warmup Iteration   1: 5.280 ops/ms
# Warmup Iteration   2: 7.578 ops/ms
# Warmup Iteration   3: 7.701 ops/ms
Iteration   1: 7.748 ops/ms
Iteration   2: 7.970 ops/ms
Iteration   3: 7.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.878 ±(99.9%) 2.118 ops/ms [Average]
  (min, avg, max) = (7.748, 7.878, 7.970), stdev = 0.116
  CI (99.9%): [5.760, 9.995] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.591 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.002 ms/op
Iteration   1: 3.235 ±(99.9%) 0.006 ms/op
Iteration   2: 3.241 ±(99.9%) 0.002 ms/op
Iteration   3: 3.151 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.209 ±(99.9%) 0.919 ms/op [Average]
  (min, avg, max) = (3.151, 3.209, 3.241), stdev = 0.050
  CI (99.9%): [2.290, 4.127] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.460 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.001 ms/op
Iteration   1: 3.002 ±(99.9%) 0.002 ms/op
Iteration   2: 2.998 ±(99.9%) 0.003 ms/op
Iteration   3: 3.018 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.006 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (2.998, 3.006, 3.018), stdev = 0.010
  CI (99.9%): [2.819, 3.193] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.528 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.379 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.001 ms/op
Iteration   1: 3.252 ±(99.9%) 0.002 ms/op
Iteration   2: 3.223 ±(99.9%) 0.003 ms/op
Iteration   3: 3.147 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.207 ±(99.9%) 0.997 ms/op [Average]
  (min, avg, max) = (3.147, 3.207, 3.252), stdev = 0.055
  CI (99.9%): [2.210, 4.204] (assumes normal distribution)


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
# Warmup Iteration   1: 5.260 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.369 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.018 ms/op
Iteration   1: 4.066 ±(99.9%) 0.028 ms/op
Iteration   2: 4.016 ±(99.9%) 0.010 ms/op
Iteration   3: 4.085 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.056 ±(99.9%) 0.645 ms/op [Average]
  (min, avg, max) = (4.016, 4.056, 4.085), stdev = 0.035
  CI (99.9%): [3.410, 4.701] (assumes normal distribution)


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
# Warmup Iteration   1: 4.659 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.007 ms/op
Iteration   1: 3.267 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  7.791 ms/op
                 createUser·p0.9999: 18.592 ms/op
                 createUser·p1.00:   19.038 ms/op

Iteration   2: 3.240 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  11.422 ms/op
                 createUser·p0.9999: 20.324 ms/op
                 createUser·p1.00:   20.677 ms/op

Iteration   3: 3.173 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  19.832 ms/op
                 createUser·p0.9999: 23.785 ms/op
                 createUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 297637
  mean =      3.226 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6473 
    [ 2.500,  5.000) = 288807 
    [ 5.000,  7.500) = 1842 
    [ 7.500, 10.000) = 196 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =     11.223 ms/op
     p(99.9900) =     23.256 ms/op
     p(99.9990) =     24.184 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.165 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.006 ms/op
Iteration   1: 3.079 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.103 ms/op
                 existUser·p0.9999: 12.766 ms/op
                 existUser·p1.00:   13.042 ms/op

Iteration   2: 3.043 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.333 ms/op
                 existUser·p0.999:  9.142 ms/op
                 existUser·p0.9999: 14.828 ms/op
                 existUser·p1.00:   15.352 ms/op

Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  10.511 ms/op
                 existUser·p0.9999: 16.441 ms/op
                 existUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314782
  mean =      3.052 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 734 
    [ 1.250,  2.500) = 15093 
    [ 2.500,  3.750) = 283761 
    [ 3.750,  5.000) = 13479 
    [ 5.000,  6.250) = 927 
    [ 6.250,  7.500) = 319 
    [ 7.500,  8.750) = 142 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 90 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     15.320 ms/op
     p(99.9990) =     16.646 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


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
# Warmup Iteration   1: 4.741 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
Iteration   1: 3.206 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  9.619 ms/op
                 getUser·p0.9999: 19.661 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.245 ms/op
                 getUser·p0.9999: 22.510 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   3: 3.132 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  7.486 ms/op
                 getUser·p0.9999: 22.439 ms/op
                 getUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302617
  mean =      3.173 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7110 
    [ 2.500,  5.000) = 293683 
    [ 5.000,  7.500) = 1438 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.378 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 6.124 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.068 ±(99.9%) 0.009 ms/op
Iteration   1: 4.054 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  12.239 ms/op
                 listUser·p0.9999: 17.013 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   2: 4.092 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.833 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.909 ms/op
                 listUser·p0.999:  14.607 ms/op
                 listUser·p0.9999: 18.172 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   3: 3.996 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  16.129 ms/op
                 listUser·p0.9999: 22.281 ms/op
                 listUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237358
  mean =      4.047 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1429 
    [ 2.500,  5.000) = 218335 
    [ 5.000,  7.500) = 16202 
    [ 7.500, 10.000) = 871 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     20.447 ms/op
     p(99.9990) =     22.803 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.083 ± 4.217  ops/ms
ClientGrpc.existUser                       thrpt       3  10.584 ± 1.986  ops/ms
ClientGrpc.getUser                         thrpt       3   9.857 ± 4.202  ops/ms
ClientGrpc.listUser                        thrpt       3   7.878 ± 2.118  ops/ms
ClientGrpc.createUser                       avgt       3   3.209 ± 0.919   ms/op
ClientGrpc.existUser                        avgt       3   3.006 ± 0.187   ms/op
ClientGrpc.getUser                          avgt       3   3.207 ± 0.997   ms/op
ClientGrpc.listUser                         avgt       3   4.056 ± 0.645   ms/op
ClientGrpc.createUser                     sample  297637   3.226 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.849           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.166           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.014           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.223           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.256           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.216           ms/op
ClientGrpc.existUser                      sample  314782   3.052 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.532           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.015           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.011           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.320           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.761           ms/op
ClientGrpc.getUser                        sample  302617   3.173 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.752           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.113           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.912           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.378           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.348           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.839           ms/op
ClientGrpc.listUser                       sample  237358   4.047 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.037           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.936           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.653           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.172           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.447           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.938           ms/op
