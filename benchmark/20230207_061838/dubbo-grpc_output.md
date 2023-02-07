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
# Warmup Iteration   1: 4.053 ops/ms
# Warmup Iteration   2: 9.254 ops/ms
# Warmup Iteration   3: 9.721 ops/ms
Iteration   1: 10.147 ops/ms
Iteration   2: 9.884 ops/ms
Iteration   3: 9.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.989 ±(99.9%) 2.535 ops/ms [Average]
  (min, avg, max) = (9.884, 9.989, 10.147), stdev = 0.139
  CI (99.9%): [7.454, 12.524] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.240 ops/ms
# Warmup Iteration   2: 9.559 ops/ms
# Warmup Iteration   3: 9.975 ops/ms
Iteration   1: 9.981 ops/ms
Iteration   2: 10.425 ops/ms
Iteration   3: 10.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.232 ±(99.9%) 4.157 ops/ms [Average]
  (min, avg, max) = (9.981, 10.232, 10.425), stdev = 0.228
  CI (99.9%): [6.076, 14.389] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.525 ops/ms
# Warmup Iteration   2: 9.192 ops/ms
# Warmup Iteration   3: 9.270 ops/ms
Iteration   1: 9.689 ops/ms
Iteration   2: 9.679 ops/ms
Iteration   3: 9.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.751 ±(99.9%) 2.118 ops/ms [Average]
  (min, avg, max) = (9.679, 9.751, 9.885), stdev = 0.116
  CI (99.9%): [7.633, 11.869] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.613 ops/ms
# Warmup Iteration   2: 7.651 ops/ms
# Warmup Iteration   3: 7.674 ops/ms
Iteration   1: 7.891 ops/ms
Iteration   2: 7.934 ops/ms
Iteration   3: 7.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.893 ±(99.9%) 0.731 ops/ms [Average]
  (min, avg, max) = (7.854, 7.893, 7.934), stdev = 0.040
  CI (99.9%): [7.162, 8.624] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.260 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.008 ms/op
Iteration   1: 3.119 ±(99.9%) 0.003 ms/op
Iteration   2: 3.195 ±(99.9%) 0.003 ms/op
Iteration   3: 3.326 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.213 ±(99.9%) 1.904 ms/op [Average]
  (min, avg, max) = (3.119, 3.213, 3.326), stdev = 0.104
  CI (99.9%): [1.309, 5.117] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.103 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.002 ms/op
Iteration   1: 3.068 ±(99.9%) 0.002 ms/op
Iteration   2: 3.063 ±(99.9%) 0.002 ms/op
Iteration   3: 3.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.067 ±(99.9%) 0.085 ms/op [Average]
  (min, avg, max) = (3.063, 3.067, 3.072), stdev = 0.005
  CI (99.9%): [2.983, 3.152] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.243 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.002 ms/op
Iteration   1: 3.182 ±(99.9%) 0.002 ms/op
Iteration   2: 3.260 ±(99.9%) 0.004 ms/op
Iteration   3: 3.243 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.228 ±(99.9%) 0.744 ms/op [Average]
  (min, avg, max) = (3.182, 3.228, 3.260), stdev = 0.041
  CI (99.9%): [2.484, 3.973] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.806 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.010 ms/op
Iteration   1: 4.050 ±(99.9%) 0.006 ms/op
Iteration   2: 4.229 ±(99.9%) 0.009 ms/op
Iteration   3: 4.358 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.212 ±(99.9%) 2.822 ms/op [Average]
  (min, avg, max) = (4.050, 4.212, 4.358), stdev = 0.155
  CI (99.9%): [1.390, 7.034] (assumes normal distribution)


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
# Warmup Iteration   1: 4.943 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.008 ms/op
Iteration   1: 3.516 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.071 ms/op
                 createUser·p0.999:  8.619 ms/op
                 createUser·p0.9999: 15.854 ms/op
                 createUser·p1.00:   16.351 ms/op

Iteration   2: 3.674 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  8.167 ms/op
                 createUser·p0.9999: 16.667 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   3: 3.634 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   3.609 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   5.112 ms/op
                 createUser·p0.999:  9.537 ms/op
                 createUser·p0.9999: 19.438 ms/op
                 createUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265965
  mean =      3.607 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 189 
    [ 1.250,  2.500) = 7469 
    [ 2.500,  3.750) = 156502 
    [ 3.750,  5.000) = 97680 
    [ 5.000,  6.250) = 3436 
    [ 6.250,  7.500) = 228 
    [ 7.500,  8.750) = 184 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 60 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      5.136 ms/op
     p(99.9000) =      8.881 ms/op
     p(99.9900) =     17.007 ms/op
     p(99.9990) =     19.781 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 4.664 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.443 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.006 ms/op
Iteration   1: 3.264 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  7.545 ms/op
                 existUser·p0.9999: 13.553 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   2: 3.288 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  7.508 ms/op
                 existUser·p0.9999: 16.386 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   3: 3.384 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   4.768 ms/op
                 existUser·p0.999:  14.958 ms/op
                 existUser·p0.9999: 17.385 ms/op
                 existUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 289940
  mean =      3.311 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1303 
    [ 1.250,  2.500) = 20507 
    [ 2.500,  3.750) = 203254 
    [ 3.750,  5.000) = 63445 
    [ 5.000,  6.250) = 936 
    [ 6.250,  7.500) = 171 
    [ 7.500,  8.750) = 84 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 65 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      7.923 ms/op
     p(99.9900) =     17.236 ms/op
     p(99.9990) =     17.682 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 5.082 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.007 ms/op
Iteration   1: 3.303 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  7.227 ms/op
                 getUser·p0.9999: 17.378 ms/op
                 getUser·p1.00:   17.793 ms/op

Iteration   2: 3.214 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  6.218 ms/op
                 getUser·p0.9999: 17.958 ms/op
                 getUser·p1.00:   18.285 ms/op

Iteration   3: 3.270 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.066 ms/op
                 getUser·p0.9999: 20.822 ms/op
                 getUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 294333
  mean =      3.262 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14058 
    [ 2.500,  5.000) = 279137 
    [ 5.000,  7.500) = 931 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      6.917 ms/op
     p(99.9900) =     20.513 ms/op
     p(99.9990) =     21.334 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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
# Warmup Iteration   1: 4.652 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.364 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.130 ±(99.9%) 0.013 ms/op
Iteration   1: 4.078 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.359 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 19.807 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   2: 4.032 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.853 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  16.379 ms/op
                 listUser·p0.9999: 19.464 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   3: 4.068 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  17.742 ms/op
                 listUser·p0.9999: 20.817 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236273
  mean =      4.059 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3066 
    [ 2.500,  5.000) = 207219 
    [ 5.000,  7.500) = 24796 
    [ 7.500, 10.000) = 803 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 182 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.359 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     16.965 ms/op
     p(99.9900) =     19.804 ms/op
     p(99.9990) =     21.398 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.989 ± 2.535  ops/ms
ClientGrpc.existUser                       thrpt       3  10.232 ± 4.157  ops/ms
ClientGrpc.getUser                         thrpt       3   9.751 ± 2.118  ops/ms
ClientGrpc.listUser                        thrpt       3   7.893 ± 0.731  ops/ms
ClientGrpc.createUser                       avgt       3   3.213 ± 1.904   ms/op
ClientGrpc.existUser                        avgt       3   3.067 ± 0.085   ms/op
ClientGrpc.getUser                          avgt       3   3.228 ± 0.744   ms/op
ClientGrpc.listUser                         avgt       3   4.212 ± 2.822   ms/op
ClientGrpc.createUser                     sample  265965   3.607 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.837           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.136           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.881           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.007           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.923           ms/op
ClientGrpc.existUser                      sample  289940   3.311 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.741           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.076           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.710           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.923           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.236           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.285           ms/op
ClientGrpc.getUser                        sample  294333   3.262 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.628           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.236           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.953           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.133           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.917           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.513           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.430           ms/op
ClientGrpc.listUser                       sample  236273   4.059 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.359           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.903           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.965           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.804           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.529           ms/op
