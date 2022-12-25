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
# Warmup Iteration   1: 4.169 ops/ms
# Warmup Iteration   2: 8.496 ops/ms
# Warmup Iteration   3: 9.383 ops/ms
Iteration   1: 9.980 ops/ms
Iteration   2: 10.318 ops/ms
Iteration   3: 10.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.150 ±(99.9%) 3.081 ops/ms [Average]
  (min, avg, max) = (9.980, 10.150, 10.318), stdev = 0.169
  CI (99.9%): [7.069, 13.231] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.068 ops/ms
# Warmup Iteration   2: 10.120 ops/ms
# Warmup Iteration   3: 10.115 ops/ms
Iteration   1: 10.451 ops/ms
Iteration   2: 10.696 ops/ms
Iteration   3: 10.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.610 ±(99.9%) 2.517 ops/ms [Average]
  (min, avg, max) = (10.451, 10.610, 10.696), stdev = 0.138
  CI (99.9%): [8.093, 13.127] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.316 ops/ms
# Warmup Iteration   2: 9.882 ops/ms
# Warmup Iteration   3: 10.345 ops/ms
Iteration   1: 10.395 ops/ms
Iteration   2: 10.371 ops/ms
Iteration   3: 9.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.252 ±(99.9%) 4.165 ops/ms [Average]
  (min, avg, max) = (9.989, 10.252, 10.395), stdev = 0.228
  CI (99.9%): [6.087, 14.417] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.482 ops/ms
# Warmup Iteration   2: 7.624 ops/ms
# Warmup Iteration   3: 7.839 ops/ms
Iteration   1: 7.997 ops/ms
Iteration   2: 8.160 ops/ms
Iteration   3: 7.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.035 ±(99.9%) 2.027 ops/ms [Average]
  (min, avg, max) = (7.948, 8.035, 8.160), stdev = 0.111
  CI (99.9%): [6.008, 10.061] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.669 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.002 ms/op
Iteration   1: 3.243 ±(99.9%) 0.002 ms/op
Iteration   2: 3.058 ±(99.9%) 0.001 ms/op
Iteration   3: 3.262 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.188 ±(99.9%) 2.054 ms/op [Average]
  (min, avg, max) = (3.058, 3.188, 3.262), stdev = 0.113
  CI (99.9%): [1.133, 5.242] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.002 ms/op
Iteration   1: 3.088 ±(99.9%) 0.001 ms/op
Iteration   2: 3.022 ±(99.9%) 0.002 ms/op
Iteration   3: 3.043 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.051 ±(99.9%) 0.615 ms/op [Average]
  (min, avg, max) = (3.022, 3.051, 3.088), stdev = 0.034
  CI (99.9%): [2.436, 3.666] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.214 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.002 ms/op
Iteration   1: 3.224 ±(99.9%) 0.003 ms/op
Iteration   2: 3.199 ±(99.9%) 0.002 ms/op
Iteration   3: 3.204 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.209 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (3.199, 3.209, 3.224), stdev = 0.013
  CI (99.9%): [2.975, 3.443] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.781 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.012 ms/op
Iteration   1: 4.122 ±(99.9%) 0.018 ms/op
Iteration   2: 4.104 ±(99.9%) 0.017 ms/op
Iteration   3: 3.911 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.046 ±(99.9%) 2.136 ms/op [Average]
  (min, avg, max) = (3.911, 4.046, 4.122), stdev = 0.117
  CI (99.9%): [1.910, 6.182] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.568 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.007 ms/op
Iteration   1: 3.237 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  10.392 ms/op
                 createUser·p0.9999: 21.499 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   2: 3.146 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  10.545 ms/op
                 createUser·p0.9999: 23.319 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   3: 3.199 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  8.995 ms/op
                 createUser·p0.9999: 23.560 ms/op
                 createUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300955
  mean =      3.194 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17411 
    [ 2.500,  5.000) = 282244 
    [ 5.000,  7.500) = 859 
    [ 7.500, 10.000) = 117 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =     10.405 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     24.117 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 4.148 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.876 ms/op
                 existUser·p0.9999: 13.229 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.994 ms/op
                 existUser·p0.9999: 22.523 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  8.631 ms/op
                 existUser·p0.9999: 19.253 ms/op
                 existUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318587
  mean =      3.013 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40154 
    [ 2.500,  5.000) = 277603 
    [ 5.000,  7.500) = 555 
    [ 7.500, 10.000) = 115 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.098 ms/op
     p(99.9900) =     21.556 ms/op
     p(99.9990) =     23.489 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 4.196 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
Iteration   1: 3.079 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.457 ms/op
                 getUser·p0.9999: 13.789 ms/op
                 getUser·p1.00:   14.156 ms/op

Iteration   2: 3.134 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.889 ms/op
                 getUser·p0.9999: 16.777 ms/op
                 getUser·p1.00:   17.465 ms/op

Iteration   3: 3.219 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.930 ms/op
                 getUser·p0.9999: 24.873 ms/op
                 getUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305238
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24737 
    [ 2.500,  5.000) = 279387 
    [ 5.000,  7.500) = 827 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.340 ms/op
     p(99.9900) =     24.050 ms/op
     p(99.9990) =     25.097 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 4.634 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.273 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.011 ms/op
Iteration   1: 3.944 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 22.340 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 4.040 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  17.386 ms/op
                 listUser·p0.9999: 28.738 ms/op
                 listUser·p1.00:   30.900 ms/op

Iteration   3: 4.116 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  21.004 ms/op
                 listUser·p0.9999: 27.041 ms/op
                 listUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238151
  mean =      4.032 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1521 
    [ 2.500,  5.000) = 213043 
    [ 5.000,  7.500) = 22221 
    [ 7.500, 10.000) = 935 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     16.218 ms/op
     p(99.9900) =     27.787 ms/op
     p(99.9990) =     30.735 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.150 ± 3.081  ops/ms
ClientGrpc.existUser                       thrpt       3  10.610 ± 2.517  ops/ms
ClientGrpc.getUser                         thrpt       3  10.252 ± 4.165  ops/ms
ClientGrpc.listUser                        thrpt       3   8.035 ± 2.027  ops/ms
ClientGrpc.createUser                       avgt       3   3.188 ± 2.054   ms/op
ClientGrpc.existUser                        avgt       3   3.051 ± 0.615   ms/op
ClientGrpc.getUser                          avgt       3   3.209 ± 0.234   ms/op
ClientGrpc.listUser                         avgt       3   4.046 ± 2.136   ms/op
ClientGrpc.createUser                     sample  300955   3.194 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.727           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.142           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.051           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.405           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.200           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.216           ms/op
ClientGrpc.existUser                      sample  318587   3.013 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.751           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.858           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.098           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.556           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.626           ms/op
ClientGrpc.getUser                        sample  305238   3.143 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.748           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.113           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.998           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.340           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.050           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.199           ms/op
ClientGrpc.listUser                       sample  238151   4.032 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.907           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.218           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.787           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.900           ms/op
