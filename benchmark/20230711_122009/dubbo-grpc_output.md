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
# Warmup Iteration   1: 4.209 ops/ms
# Warmup Iteration   2: 8.856 ops/ms
# Warmup Iteration   3: 10.054 ops/ms
Iteration   1: 10.293 ops/ms
Iteration   2: 10.441 ops/ms
Iteration   3: 10.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.387 ±(99.9%) 1.479 ops/ms [Average]
  (min, avg, max) = (10.293, 10.387, 10.441), stdev = 0.081
  CI (99.9%): [8.907, 11.866] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.583 ops/ms
# Warmup Iteration   2: 10.411 ops/ms
# Warmup Iteration   3: 10.919 ops/ms
Iteration   1: 10.875 ops/ms
Iteration   2: 11.019 ops/ms
Iteration   3: 11.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.000 ±(99.9%) 2.128 ops/ms [Average]
  (min, avg, max) = (10.875, 11.000, 11.106), stdev = 0.117
  CI (99.9%): [8.872, 13.128] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.307 ops/ms
# Warmup Iteration   2: 9.973 ops/ms
# Warmup Iteration   3: 10.476 ops/ms
Iteration   1: 10.635 ops/ms
Iteration   2: 10.438 ops/ms
Iteration   3: 10.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.507 ±(99.9%) 2.023 ops/ms [Average]
  (min, avg, max) = (10.438, 10.507, 10.635), stdev = 0.111
  CI (99.9%): [8.484, 12.530] (assumes normal distribution)


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
# Warmup Iteration   1: 5.327 ops/ms
# Warmup Iteration   2: 7.838 ops/ms
# Warmup Iteration   3: 7.954 ops/ms
Iteration   1: 7.931 ops/ms
Iteration   2: 8.062 ops/ms
Iteration   3: 7.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.990 ±(99.9%) 1.213 ops/ms [Average]
  (min, avg, max) = (7.931, 7.990, 8.062), stdev = 0.066
  CI (99.9%): [6.777, 9.203] (assumes normal distribution)


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.003 ms/op
Iteration   1: 3.043 ±(99.9%) 0.003 ms/op
Iteration   2: 3.132 ±(99.9%) 0.001 ms/op
Iteration   3: 3.052 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.076 ±(99.9%) 0.895 ms/op [Average]
  (min, avg, max) = (3.043, 3.076, 3.132), stdev = 0.049
  CI (99.9%): [2.180, 3.971] (assumes normal distribution)


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.994 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.006 ms/op
Iteration   1: 2.980 ±(99.9%) 0.002 ms/op
Iteration   2: 2.897 ±(99.9%) 0.003 ms/op
Iteration   3: 2.907 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.928 ±(99.9%) 0.820 ms/op [Average]
  (min, avg, max) = (2.897, 2.928, 2.980), stdev = 0.045
  CI (99.9%): [2.108, 3.748] (assumes normal distribution)


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
# Warmup Iteration   1: 4.466 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.003 ms/op
Iteration   1: 3.060 ±(99.9%) 0.003 ms/op
Iteration   2: 3.053 ±(99.9%) 0.003 ms/op
Iteration   3: 3.107 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.073 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (3.053, 3.073, 3.107), stdev = 0.029
  CI (99.9%): [2.536, 3.611] (assumes normal distribution)


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
# Warmup Iteration   1: 5.536 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.224 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.024 ms/op
Iteration   1: 4.076 ±(99.9%) 0.011 ms/op
Iteration   2: 3.928 ±(99.9%) 0.021 ms/op
Iteration   3: 3.976 ±(99.9%) 0.049 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.993 ±(99.9%) 1.380 ms/op [Average]
  (min, avg, max) = (3.928, 3.993, 4.076), stdev = 0.076
  CI (99.9%): [2.613, 5.374] (assumes normal distribution)


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
# Warmup Iteration   1: 4.277 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.322 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
Iteration   1: 3.093 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  8.880 ms/op
                 createUser·p0.9999: 18.098 ms/op
                 createUser·p1.00:   21.037 ms/op

Iteration   2: 3.053 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  7.407 ms/op
                 createUser·p0.9999: 16.278 ms/op
                 createUser·p1.00:   16.695 ms/op

Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.301 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  8.904 ms/op
                 createUser·p0.9999: 19.734 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311961
  mean =      3.075 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18337 
    [ 2.500,  5.000) = 291762 
    [ 5.000,  7.500) = 1513 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.301 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.799 ms/op
     p(99.9900) =     18.049 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.172 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.005 ms/op
Iteration   1: 2.950 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  7.001 ms/op
                 existUser·p0.9999: 13.124 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   2: 2.932 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  5.972 ms/op
                 existUser·p0.9999: 14.373 ms/op
                 existUser·p1.00:   14.959 ms/op

Iteration   3: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.026 ms/op
                 existUser·p0.999:  10.374 ms/op
                 existUser·p0.9999: 18.361 ms/op
                 existUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326365
  mean =      2.942 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 578 
    [ 1.250,  2.500) = 27965 
    [ 2.500,  3.750) = 287929 
    [ 3.750,  5.000) = 8949 
    [ 5.000,  6.250) = 400 
    [ 6.250,  7.500) = 248 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.116 ms/op
     p(99.9000) =      7.176 ms/op
     p(99.9900) =     17.531 ms/op
     p(99.9990) =     18.726 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.064 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.504 ms/op
                 getUser·p0.9999: 14.439 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   2: 3.085 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.505 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.104 ms/op
                 getUser·p0.9999: 16.484 ms/op
                 getUser·p1.00:   16.941 ms/op

Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.292 ms/op
                 getUser·p0.999:  7.242 ms/op
                 getUser·p0.9999: 18.206 ms/op
                 getUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312150
  mean =      3.075 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 338 
    [ 1.250,  2.500) = 16915 
    [ 2.500,  3.750) = 275042 
    [ 3.750,  5.000) = 18455 
    [ 5.000,  6.250) = 821 
    [ 6.250,  7.500) = 318 
    [ 7.500,  8.750) = 96 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.505 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.274 ms/op
     p(99.9900) =     17.360 ms/op
     p(99.9990) =     18.281 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 5.219 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.011 ms/op
Iteration   1: 4.038 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.808 ms/op
                 listUser·p0.9999: 23.628 ms/op
                 listUser·p1.00:   24.314 ms/op

Iteration   2: 4.038 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  18.967 ms/op
                 listUser·p0.9999: 25.234 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   3: 4.005 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  17.994 ms/op
                 listUser·p0.9999: 49.283 ms/op
                 listUser·p1.00:   50.528 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238229
  mean =      4.027 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 212864 
    [ 5.000, 10.000) = 24912 
    [10.000, 15.000) = 102 
    [15.000, 20.000) = 202 
    [20.000, 25.000) = 100 
    [25.000, 30.000) = 17 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 30 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     17.818 ms/op
     p(99.9900) =     47.448 ms/op
     p(99.9990) =     49.778 ms/op
     p(99.9999) =     50.528 ms/op
    p(100.0000) =     50.528 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.387 ± 1.479  ops/ms
ClientGrpc.existUser                       thrpt       3  11.000 ± 2.128  ops/ms
ClientGrpc.getUser                         thrpt       3  10.507 ± 2.023  ops/ms
ClientGrpc.listUser                        thrpt       3   7.990 ± 1.213  ops/ms
ClientGrpc.createUser                       avgt       3   3.076 ± 0.895   ms/op
ClientGrpc.existUser                        avgt       3   2.928 ± 0.820   ms/op
ClientGrpc.getUser                          avgt       3   3.073 ± 0.537   ms/op
ClientGrpc.listUser                         avgt       3   3.993 ± 1.380   ms/op
ClientGrpc.createUser                     sample  311961   3.075 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.301           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.799           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.049           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.037           ms/op
ClientGrpc.existUser                      sample  326365   2.942 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.607           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.116           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.176           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.531           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.842           ms/op
ClientGrpc.getUser                        sample  312150   3.075 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.505           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.274           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.360           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.448           ms/op
ClientGrpc.listUser                       sample  238229   4.027 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.169           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.102           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.818           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          47.448           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          50.528           ms/op
