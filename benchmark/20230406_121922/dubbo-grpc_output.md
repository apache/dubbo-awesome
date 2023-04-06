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
# Warmup Iteration   1: 3.960 ops/ms
# Warmup Iteration   2: 8.248 ops/ms
# Warmup Iteration   3: 9.850 ops/ms
Iteration   1: 10.284 ops/ms
Iteration   2: 10.597 ops/ms
Iteration   3: 10.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.434 ±(99.9%) 2.860 ops/ms [Average]
  (min, avg, max) = (10.284, 10.434, 10.597), stdev = 0.157
  CI (99.9%): [7.574, 13.293] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.131 ops/ms
# Warmup Iteration   2: 10.353 ops/ms
# Warmup Iteration   3: 11.102 ops/ms
Iteration   1: 10.982 ops/ms
Iteration   2: 10.926 ops/ms
Iteration   3: 10.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.961 ±(99.9%) 0.566 ops/ms [Average]
  (min, avg, max) = (10.926, 10.961, 10.982), stdev = 0.031
  CI (99.9%): [10.395, 11.528] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.964 ops/ms
# Warmup Iteration   2: 10.202 ops/ms
# Warmup Iteration   3: 10.471 ops/ms
Iteration   1: 10.488 ops/ms
Iteration   2: 10.514 ops/ms
Iteration   3: 10.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.547 ±(99.9%) 1.489 ops/ms [Average]
  (min, avg, max) = (10.488, 10.547, 10.640), stdev = 0.082
  CI (99.9%): [9.058, 12.037] (assumes normal distribution)


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
# Warmup Iteration   1: 5.430 ops/ms
# Warmup Iteration   2: 7.620 ops/ms
# Warmup Iteration   3: 7.906 ops/ms
Iteration   1: 7.905 ops/ms
Iteration   2: 7.951 ops/ms
Iteration   3: 8.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.958 ±(99.9%) 1.044 ops/ms [Average]
  (min, avg, max) = (7.905, 7.958, 8.018), stdev = 0.057
  CI (99.9%): [6.914, 9.002] (assumes normal distribution)


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
# Warmup Iteration   1: 4.340 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.010 ms/op
Iteration   1: 3.047 ±(99.9%) 0.001 ms/op
Iteration   2: 3.028 ±(99.9%) 0.003 ms/op
Iteration   3: 3.115 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.063 ±(99.9%) 0.836 ms/op [Average]
  (min, avg, max) = (3.028, 3.063, 3.115), stdev = 0.046
  CI (99.9%): [2.227, 3.899] (assumes normal distribution)


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
# Warmup Iteration   1: 4.135 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.002 ms/op
Iteration   1: 2.849 ±(99.9%) 0.003 ms/op
Iteration   2: 2.950 ±(99.9%) 0.001 ms/op
Iteration   3: 2.977 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.926 ±(99.9%) 1.233 ms/op [Average]
  (min, avg, max) = (2.849, 2.926, 2.977), stdev = 0.068
  CI (99.9%): [1.692, 4.159] (assumes normal distribution)


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
# Warmup Iteration   1: 4.429 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.002 ms/op
Iteration   1: 3.104 ±(99.9%) 0.003 ms/op
Iteration   2: 3.063 ±(99.9%) 0.002 ms/op
Iteration   3: 3.077 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.082 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.063, 3.082, 3.104), stdev = 0.021
  CI (99.9%): [2.696, 3.467] (assumes normal distribution)


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
# Warmup Iteration   1: 5.357 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.398 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.171 ±(99.9%) 0.032 ms/op
Iteration   1: 4.097 ±(99.9%) 0.024 ms/op
Iteration   2: 4.017 ±(99.9%) 0.008 ms/op
Iteration   3: 4.015 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.043 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (4.015, 4.043, 4.097), stdev = 0.047
  CI (99.9%): [3.190, 4.895] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.494 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.006 ms/op
Iteration   1: 3.113 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.656 ms/op
                 createUser·p0.9999: 12.943 ms/op
                 createUser·p1.00:   13.451 ms/op

Iteration   2: 3.106 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  6.407 ms/op
                 createUser·p0.9999: 19.028 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   3: 3.129 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.631 ms/op
                 createUser·p0.9999: 25.919 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307881
  mean =      3.116 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9960 
    [ 2.500,  5.000) = 296587 
    [ 5.000,  7.500) = 1054 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.315 ms/op
     p(99.9900) =     25.664 ms/op
     p(99.9990) =     26.275 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.047 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
Iteration   1: 2.945 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  7.193 ms/op
                 existUser·p0.9999: 12.653 ms/op
                 existUser·p1.00:   13.107 ms/op

Iteration   2: 2.925 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.039 ms/op
                 existUser·p0.999:  7.099 ms/op
                 existUser·p0.9999: 14.996 ms/op
                 existUser·p1.00:   16.318 ms/op

Iteration   3: 2.907 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.282 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.315 ms/op
                 existUser·p0.9999: 17.367 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328001
  mean =      2.925 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 977 
    [ 1.250,  2.500) = 41492 
    [ 2.500,  3.750) = 277267 
    [ 3.750,  5.000) = 7250 
    [ 5.000,  6.250) = 455 
    [ 6.250,  7.500) = 301 
    [ 7.500,  8.750) = 99 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.282 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      7.201 ms/op
     p(99.9900) =     15.925 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 4.483 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.220 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  6.507 ms/op
                 getUser·p0.9999: 12.632 ms/op
                 getUser·p1.00:   12.780 ms/op

Iteration   2: 3.106 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.946 ms/op
                 getUser·p0.9999: 14.670 ms/op
                 getUser·p1.00:   14.811 ms/op

Iteration   3: 3.053 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  7.746 ms/op
                 getUser·p0.9999: 18.531 ms/op
                 getUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314244
  mean =      3.055 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 276 
    [ 1.250,  2.500) = 14119 
    [ 2.500,  3.750) = 285069 
    [ 3.750,  5.000) = 13568 
    [ 5.000,  6.250) = 642 
    [ 6.250,  7.500) = 250 
    [ 7.500,  8.750) = 103 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.649 ms/op
     p(99.9900) =     18.140 ms/op
     p(99.9990) =     18.673 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 4.802 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.012 ms/op
Iteration   1: 3.978 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  14.625 ms/op
                 listUser·p0.9999: 17.493 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   2: 4.004 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  18.186 ms/op
                 listUser·p0.9999: 22.839 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   3: 3.933 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  16.152 ms/op
                 listUser·p0.9999: 25.461 ms/op
                 listUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241614
  mean =      3.972 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2849 
    [ 2.500,  5.000) = 216190 
    [ 5.000,  7.500) = 21335 
    [ 7.500, 10.000) = 821 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     16.079 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.434 ± 2.860  ops/ms
ClientGrpc.existUser                       thrpt       3  10.961 ± 0.566  ops/ms
ClientGrpc.getUser                         thrpt       3  10.547 ± 1.489  ops/ms
ClientGrpc.listUser                        thrpt       3   7.958 ± 1.044  ops/ms
ClientGrpc.createUser                       avgt       3   3.063 ± 0.836   ms/op
ClientGrpc.existUser                        avgt       3   2.926 ± 1.233   ms/op
ClientGrpc.getUser                          avgt       3   3.082 ± 0.385   ms/op
ClientGrpc.listUser                         avgt       3   4.043 ± 0.853   ms/op
ClientGrpc.createUser                     sample  307881   3.116 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.683           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.315           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.664           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.345           ms/op
ClientGrpc.existUser                      sample  328001   2.925 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.282           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.201           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.925           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.400           ms/op
ClientGrpc.getUser                        sample  314244   3.055 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.872           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.649           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.140           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.874           ms/op
ClientGrpc.listUser                       sample  241614   3.972 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.985           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.079           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.805           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.723           ms/op
