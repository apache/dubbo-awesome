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
# Warmup Iteration   1: 2.331 ops/ms
# Warmup Iteration   2: 5.758 ops/ms
# Warmup Iteration   3: 7.494 ops/ms
Iteration   1: 7.653 ops/ms
Iteration   2: 7.768 ops/ms
Iteration   3: 8.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.823 ±(99.9%) 3.701 ops/ms [Average]
  (min, avg, max) = (7.653, 7.823, 8.047), stdev = 0.203
  CI (99.9%): [4.122, 11.524] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.857 ops/ms
# Warmup Iteration   2: 8.290 ops/ms
# Warmup Iteration   3: 8.536 ops/ms
Iteration   1: 8.478 ops/ms
Iteration   2: 8.759 ops/ms
Iteration   3: 8.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.653 ±(99.9%) 2.791 ops/ms [Average]
  (min, avg, max) = (8.478, 8.653, 8.759), stdev = 0.153
  CI (99.9%): [5.863, 11.444] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.583 ops/ms
# Warmup Iteration   2: 7.631 ops/ms
# Warmup Iteration   3: 8.139 ops/ms
Iteration   1: 8.059 ops/ms
Iteration   2: 8.134 ops/ms
Iteration   3: 8.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.131 ±(99.9%) 1.293 ops/ms [Average]
  (min, avg, max) = (8.059, 8.131, 8.200), stdev = 0.071
  CI (99.9%): [6.838, 9.424] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.912 ops/ms
# Warmup Iteration   2: 5.652 ops/ms
# Warmup Iteration   3: 6.194 ops/ms
Iteration   1: 6.228 ops/ms
Iteration   2: 6.242 ops/ms
Iteration   3: 6.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.216 ±(99.9%) 0.636 ops/ms [Average]
  (min, avg, max) = (6.176, 6.216, 6.242), stdev = 0.035
  CI (99.9%): [5.579, 6.852] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.042 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.216 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.004 ms/op
Iteration   1: 4.043 ±(99.9%) 0.002 ms/op
Iteration   2: 3.964 ±(99.9%) 0.004 ms/op
Iteration   3: 3.996 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.001 ±(99.9%) 0.724 ms/op [Average]
  (min, avg, max) = (3.964, 4.001, 4.043), stdev = 0.040
  CI (99.9%): [3.278, 4.725] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.522 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.688 ±(99.9%) 0.005 ms/op
Iteration   1: 3.825 ±(99.9%) 0.003 ms/op
Iteration   2: 3.676 ±(99.9%) 0.002 ms/op
Iteration   3: 3.685 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.729 ±(99.9%) 1.519 ms/op [Average]
  (min, avg, max) = (3.676, 3.729, 3.825), stdev = 0.083
  CI (99.9%): [2.209, 5.248] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.182 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.211 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.005 ms/op
Iteration   1: 4.038 ±(99.9%) 0.002 ms/op
Iteration   2: 3.953 ±(99.9%) 0.002 ms/op
Iteration   3: 4.062 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.018 ±(99.9%) 1.040 ms/op [Average]
  (min, avg, max) = (3.953, 4.018, 4.062), stdev = 0.057
  CI (99.9%): [2.978, 5.058] (assumes normal distribution)


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
# Warmup Iteration   1: 7.597 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.320 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.296 ±(99.9%) 0.014 ms/op
Iteration   1: 5.133 ±(99.9%) 0.012 ms/op
Iteration   2: 5.124 ±(99.9%) 0.019 ms/op
Iteration   3: 5.056 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.104 ±(99.9%) 0.761 ms/op [Average]
  (min, avg, max) = (5.056, 5.104, 5.133), stdev = 0.042
  CI (99.9%): [4.344, 5.865] (assumes normal distribution)


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
# Warmup Iteration   1: 6.155 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.341 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.012 ms/op
Iteration   1: 3.884 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.527 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  12.097 ms/op
                 createUser·p0.9999: 19.325 ms/op
                 createUser·p1.00:   20.218 ms/op

Iteration   2: 4.071 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   5.038 ms/op
                 createUser·p0.95:   5.390 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  12.681 ms/op
                 createUser·p0.9999: 23.991 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   3: 3.765 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  11.652 ms/op
                 createUser·p0.9999: 29.000 ms/op
                 createUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 245903
  mean =      3.903 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8228 
    [ 2.500,  5.000) = 217689 
    [ 5.000,  7.500) = 18846 
    [ 7.500, 10.000) = 734 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     12.206 ms/op
     p(99.9900) =     28.404 ms/op
     p(99.9990) =     29.229 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


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
# Warmup Iteration   1: 5.402 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.767 ±(99.9%) 0.011 ms/op
Iteration   1: 3.810 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.161 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  11.028 ms/op
                 existUser·p0.9999: 15.562 ms/op
                 existUser·p1.00:   16.335 ms/op

Iteration   2: 3.793 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.710 ms/op
                 existUser·p0.95:   5.128 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  10.608 ms/op
                 existUser·p0.9999: 18.467 ms/op
                 existUser·p1.00:   19.005 ms/op

Iteration   3: 3.815 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.719 ms/op
                 existUser·p0.95:   5.120 ms/op
                 existUser·p0.99:   6.652 ms/op
                 existUser·p0.999:  17.697 ms/op
                 existUser·p0.9999: 22.728 ms/op
                 existUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 252235
  mean =      3.806 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5535 
    [ 2.500,  5.000) = 230770 
    [ 5.000,  7.500) = 14786 
    [ 7.500, 10.000) = 599 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     12.370 ms/op
     p(99.9900) =     20.531 ms/op
     p(99.9990) =     23.291 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 5.711 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.232 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.011 ms/op
Iteration   1: 3.913 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.171 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.226 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  10.125 ms/op
                 getUser·p0.9999: 17.845 ms/op
                 getUser·p1.00:   18.612 ms/op

Iteration   2: 3.981 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.866 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  9.382 ms/op
                 getUser·p0.9999: 19.691 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   3: 3.941 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.028 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  11.593 ms/op
                 getUser·p0.9999: 28.628 ms/op
                 getUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 243262
  mean =      3.945 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4742 
    [ 2.500,  5.000) = 219385 
    [ 5.000,  7.500) = 17978 
    [ 7.500, 10.000) = 898 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      6.450 ms/op
     p(99.9000) =     10.109 ms/op
     p(99.9900) =     26.761 ms/op
     p(99.9990) =     29.037 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 7.613 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 5.552 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.276 ±(99.9%) 0.019 ms/op
Iteration   1: 5.161 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   4.891 ms/op
                 listUser·p0.90:   6.726 ms/op
                 listUser·p0.95:   7.641 ms/op
                 listUser·p0.99:   9.814 ms/op
                 listUser·p0.999:  16.711 ms/op
                 listUser·p0.9999: 21.830 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   2: 5.048 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   4.841 ms/op
                 listUser·p0.90:   6.357 ms/op
                 listUser·p0.95:   7.340 ms/op
                 listUser·p0.99:   9.503 ms/op
                 listUser·p0.999:  18.350 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   3: 5.065 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.513 ms/op
                 listUser·p0.95:   7.463 ms/op
                 listUser·p0.99:   9.994 ms/op
                 listUser·p0.999:  19.095 ms/op
                 listUser·p0.9999: 21.245 ms/op
                 listUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 188633
  mean =      5.091 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 395 
    [ 2.500,  5.000) = 107483 
    [ 5.000,  7.500) = 71346 
    [ 7.500, 10.000) = 7776 
    [10.000, 12.500) = 1063 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 160 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      4.850 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      7.496 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     21.042 ms/op
     p(99.9990) =     22.175 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.823 ± 3.701  ops/ms
ClientGrpc.existUser                       thrpt       3   8.653 ± 2.791  ops/ms
ClientGrpc.getUser                         thrpt       3   8.131 ± 1.293  ops/ms
ClientGrpc.listUser                        thrpt       3   6.216 ± 0.636  ops/ms
ClientGrpc.createUser                       avgt       3   4.001 ± 0.724   ms/op
ClientGrpc.existUser                        avgt       3   3.729 ± 1.519   ms/op
ClientGrpc.getUser                          avgt       3   4.018 ± 1.040   ms/op
ClientGrpc.listUser                         avgt       3   5.104 ± 0.761   ms/op
ClientGrpc.createUser                     sample  245903   3.903 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.527           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.882           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.276           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.439           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.206           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.404           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.688           ms/op
ClientGrpc.existUser                      sample  252235   3.806 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.546           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.735           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.136           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.341           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.370           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.531           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.593           ms/op
ClientGrpc.getUser                        sample  243262   3.945 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.028           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.866           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.259           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.450           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.109           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.761           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.196           ms/op
ClientGrpc.listUser                       sample  188633   5.091 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.198           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.496           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.781           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.957           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.042           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.872           ms/op
