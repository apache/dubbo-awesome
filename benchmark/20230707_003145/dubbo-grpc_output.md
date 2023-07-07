# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.899 ops/ms
# Warmup Iteration   2: 8.680 ops/ms
# Warmup Iteration   3: 10.491 ops/ms
Iteration   1: 10.731 ops/ms
Iteration   2: 10.433 ops/ms
Iteration   3: 10.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.624 ±(99.9%) 3.021 ops/ms [Average]
  (min, avg, max) = (10.433, 10.624, 10.731), stdev = 0.166
  CI (99.9%): [7.603, 13.645] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.405 ops/ms
# Warmup Iteration   2: 10.806 ops/ms
# Warmup Iteration   3: 11.180 ops/ms
Iteration   1: 11.161 ops/ms
Iteration   2: 11.657 ops/ms
Iteration   3: 11.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.346 ±(99.9%) 4.946 ops/ms [Average]
  (min, avg, max) = (11.161, 11.346, 11.657), stdev = 0.271
  CI (99.9%): [6.400, 16.292] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.488 ops/ms
# Warmup Iteration   2: 10.313 ops/ms
# Warmup Iteration   3: 10.547 ops/ms
Iteration   1: 10.703 ops/ms
Iteration   2: 10.746 ops/ms
Iteration   3: 10.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.731 ±(99.9%) 0.441 ops/ms [Average]
  (min, avg, max) = (10.703, 10.731, 10.746), stdev = 0.024
  CI (99.9%): [10.290, 11.172] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.773 ops/ms
# Warmup Iteration   2: 7.860 ops/ms
# Warmup Iteration   3: 8.170 ops/ms
Iteration   1: 8.129 ops/ms
Iteration   2: 8.424 ops/ms
Iteration   3: 8.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.211 ±(99.9%) 3.387 ops/ms [Average]
  (min, avg, max) = (8.082, 8.211, 8.424), stdev = 0.186
  CI (99.9%): [4.825, 11.598] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.357 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.003 ms/op
Iteration   2: 2.973 ±(99.9%) 0.002 ms/op
Iteration   3: 2.966 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.989 ±(99.9%) 0.623 ms/op [Average]
  (min, avg, max) = (2.966, 2.989, 3.028), stdev = 0.034
  CI (99.9%): [2.366, 3.612] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.829 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.926 ±(99.9%) 0.002 ms/op
Iteration   1: 2.837 ±(99.9%) 0.003 ms/op
Iteration   2: 2.876 ±(99.9%) 0.003 ms/op
Iteration   3: 2.759 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.824 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (2.759, 2.824, 2.876), stdev = 0.060
  CI (99.9%): [1.736, 3.913] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.078 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.005 ms/op
Iteration   1: 3.053 ±(99.9%) 0.005 ms/op
Iteration   2: 2.952 ±(99.9%) 0.008 ms/op
Iteration   3: 3.003 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.003 ±(99.9%) 0.923 ms/op [Average]
  (min, avg, max) = (2.952, 3.003, 3.053), stdev = 0.051
  CI (99.9%): [2.079, 3.926] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.520 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.020 ms/op
Iteration   1: 3.858 ±(99.9%) 0.013 ms/op
Iteration   2: 3.827 ±(99.9%) 0.028 ms/op
Iteration   3: 3.853 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.846 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (3.827, 3.846, 3.858), stdev = 0.016
  CI (99.9%): [3.545, 4.147] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.216 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  7.309 ms/op
                 createUser·p0.9999: 15.621 ms/op
                 createUser·p1.00:   16.105 ms/op

Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.623 ms/op
                 createUser·p0.9999: 15.489 ms/op
                 createUser·p1.00:   15.925 ms/op

Iteration   3: 3.003 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  9.814 ms/op
                 createUser·p0.9999: 24.194 ms/op
                 createUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318442
  mean =      3.011 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28937 
    [ 2.500,  5.000) = 288078 
    [ 5.000,  7.500) = 1064 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.036 ms/op
     p(99.9900) =     22.756 ms/op
     p(99.9990) =     24.963 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.774 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.870 ±(99.9%) 0.005 ms/op
Iteration   1: 2.872 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.517 ms/op
                 existUser·p0.9999: 19.951 ms/op
                 existUser·p1.00:   20.152 ms/op

Iteration   2: 2.921 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.796 ms/op
                 existUser·p0.9999: 14.845 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   3: 2.816 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.414 ms/op
                 existUser·p0.9999: 18.383 ms/op
                 existUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334409
  mean =      2.869 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47266 
    [ 2.500,  5.000) = 286009 
    [ 5.000,  7.500) = 871 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.627 ms/op
     p(99.9900) =     18.995 ms/op
     p(99.9990) =     20.076 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.339 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.007 ms/op
Iteration   1: 2.990 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.276 ms/op
                 getUser·p0.9999: 17.561 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   2: 3.007 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  7.149 ms/op
                 getUser·p0.9999: 21.922 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   3: 3.004 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  6.964 ms/op
                 getUser·p0.9999: 22.502 ms/op
                 getUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319782
  mean =      3.000 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28054 
    [ 2.500,  5.000) = 290376 
    [ 5.000,  7.500) = 1072 
    [ 7.500, 10.000) = 78 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.111 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     22.866 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.482 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.011 ms/op
Iteration   1: 3.935 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.601 ms/op
                 listUser·p0.9999: 20.468 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   2: 3.963 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  13.480 ms/op
                 listUser·p0.9999: 22.116 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   3: 3.945 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.668 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  15.743 ms/op
                 listUser·p0.9999: 21.641 ms/op
                 listUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243208
  mean =      3.948 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2897 
    [ 2.500,  5.000) = 216405 
    [ 5.000,  7.500) = 22388 
    [ 7.500, 10.000) = 1017 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     14.811 ms/op
     p(99.9900) =     21.813 ms/op
     p(99.9990) =     22.436 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.624 ± 3.021  ops/ms
ClientGrpc.existUser                       thrpt       3  11.346 ± 4.946  ops/ms
ClientGrpc.getUser                         thrpt       3  10.731 ± 0.441  ops/ms
ClientGrpc.listUser                        thrpt       3   8.211 ± 3.387  ops/ms
ClientGrpc.createUser                       avgt       3   2.989 ± 0.623   ms/op
ClientGrpc.existUser                        avgt       3   2.824 ± 1.089   ms/op
ClientGrpc.getUser                          avgt       3   3.003 ± 0.923   ms/op
ClientGrpc.listUser                         avgt       3   3.846 ± 0.301   ms/op
ClientGrpc.createUser                     sample  318442   3.011 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.847           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.036           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.756           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.100           ms/op
ClientGrpc.existUser                      sample  334409   2.869 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.729           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.627           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.995           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.152           ms/op
ClientGrpc.getUser                        sample  319782   3.000 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.737           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.111           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.889           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.036           ms/op
ClientGrpc.listUser                       sample  243208   3.948 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.668           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.981           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.811           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.813           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.281           ms/op
