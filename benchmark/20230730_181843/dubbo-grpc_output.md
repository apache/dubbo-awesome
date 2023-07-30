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
# Warmup Iteration   1: 3.894 ops/ms
# Warmup Iteration   2: 8.831 ops/ms
# Warmup Iteration   3: 9.841 ops/ms
Iteration   1: 10.328 ops/ms
Iteration   2: 10.425 ops/ms
Iteration   3: 10.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.405 ±(99.9%) 1.258 ops/ms [Average]
  (min, avg, max) = (10.328, 10.405, 10.462), stdev = 0.069
  CI (99.9%): [9.147, 11.663] (assumes normal distribution)


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
# Warmup Iteration   1: 7.313 ops/ms
# Warmup Iteration   2: 10.503 ops/ms
# Warmup Iteration   3: 11.056 ops/ms
Iteration   1: 11.027 ops/ms
Iteration   2: 11.054 ops/ms
Iteration   3: 11.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.086 ±(99.9%) 1.451 ops/ms [Average]
  (min, avg, max) = (11.027, 11.086, 11.176), stdev = 0.080
  CI (99.9%): [9.635, 12.537] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.420 ops/ms
# Warmup Iteration   2: 10.103 ops/ms
# Warmup Iteration   3: 10.411 ops/ms
Iteration   1: 10.623 ops/ms
Iteration   2: 10.483 ops/ms
Iteration   3: 10.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.464 ±(99.9%) 3.098 ops/ms [Average]
  (min, avg, max) = (10.285, 10.464, 10.623), stdev = 0.170
  CI (99.9%): [7.366, 13.562] (assumes normal distribution)


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
# Warmup Iteration   1: 6.143 ops/ms
# Warmup Iteration   2: 7.290 ops/ms
# Warmup Iteration   3: 7.872 ops/ms
Iteration   1: 7.889 ops/ms
Iteration   2: 7.955 ops/ms
Iteration   3: 7.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.941 ±(99.9%) 0.845 ops/ms [Average]
  (min, avg, max) = (7.889, 7.941, 7.978), stdev = 0.046
  CI (99.9%): [7.096, 8.786] (assumes normal distribution)


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.002 ms/op
Iteration   1: 3.039 ±(99.9%) 0.002 ms/op
Iteration   2: 3.037 ±(99.9%) 0.003 ms/op
Iteration   3: 3.032 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.036 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (3.032, 3.036, 3.039), stdev = 0.003
  CI (99.9%): [2.980, 3.092] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.800 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.003 ms/op
Iteration   1: 2.923 ±(99.9%) 0.002 ms/op
Iteration   2: 2.872 ±(99.9%) 0.002 ms/op
Iteration   3: 2.884 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.893 ±(99.9%) 0.491 ms/op [Average]
  (min, avg, max) = (2.872, 2.893, 2.923), stdev = 0.027
  CI (99.9%): [2.402, 3.384] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.344 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.002 ms/op
Iteration   1: 3.110 ±(99.9%) 0.003 ms/op
Iteration   2: 3.038 ±(99.9%) 0.004 ms/op
Iteration   3: 3.055 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.067 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (3.038, 3.067, 3.110), stdev = 0.038
  CI (99.9%): [2.377, 3.758] (assumes normal distribution)


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
# Warmup Iteration   1: 5.620 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.177 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.087 ±(99.9%) 0.011 ms/op
Iteration   1: 4.101 ±(99.9%) 0.008 ms/op
Iteration   2: 4.072 ±(99.9%) 0.017 ms/op
Iteration   3: 3.901 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.025 ±(99.9%) 1.975 ms/op [Average]
  (min, avg, max) = (3.901, 4.025, 4.101), stdev = 0.108
  CI (99.9%): [2.050, 5.999] (assumes normal distribution)


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
# Warmup Iteration   1: 4.605 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.284 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.007 ms/op
Iteration   1: 3.105 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  8.299 ms/op
                 createUser·p0.9999: 12.496 ms/op
                 createUser·p1.00:   12.780 ms/op

Iteration   2: 3.094 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.000 ms/op
                 createUser·p0.9999: 14.144 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   3: 3.079 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  15.592 ms/op
                 createUser·p0.9999: 18.612 ms/op
                 createUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310573
  mean =      3.093 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15134 
    [ 2.500,  5.000) = 293948 
    [ 5.000,  7.500) = 1084 
    [ 7.500, 10.000) = 109 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      9.608 ms/op
     p(99.9900) =     17.889 ms/op
     p(99.9990) =     18.838 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 4.256 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.005 ms/op
Iteration   1: 2.954 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  8.002 ms/op
                 existUser·p0.9999: 12.583 ms/op
                 existUser·p1.00:   12.714 ms/op

Iteration   2: 2.957 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  7.654 ms/op
                 existUser·p0.9999: 14.692 ms/op
                 existUser·p1.00:   15.041 ms/op

Iteration   3: 2.944 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  6.578 ms/op
                 existUser·p0.9999: 26.083 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325195
  mean =      2.952 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31285 
    [ 2.500,  5.000) = 292734 
    [ 5.000,  7.500) = 871 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.207 ms/op
     p(99.9900) =     21.884 ms/op
     p(99.9990) =     26.190 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 4.275 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.005 ms/op
Iteration   1: 3.036 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  7.479 ms/op
                 getUser·p0.9999: 14.056 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 3.028 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.547 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  7.940 ms/op
                 getUser·p0.9999: 14.666 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   3: 3.056 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.396 ms/op
                 getUser·p0.9999: 18.088 ms/op
                 getUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315683
  mean =      3.040 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 345 
    [ 1.250,  2.500) = 14360 
    [ 2.500,  3.750) = 287482 
    [ 3.750,  5.000) = 12220 
    [ 5.000,  6.250) = 684 
    [ 6.250,  7.500) = 288 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.406 ms/op
     p(99.9900) =     16.653 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 5.697 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.198 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.088 ±(99.9%) 0.011 ms/op
Iteration   1: 4.067 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.432 ms/op
                 listUser·p0.50:   3.910 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  13.750 ms/op
                 listUser·p0.9999: 17.506 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   2: 4.096 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.240 ms/op
                 listUser·p0.999:  14.300 ms/op
                 listUser·p0.9999: 19.470 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 4.010 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  16.427 ms/op
                 listUser·p0.9999: 25.494 ms/op
                 listUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236751
  mean =      4.057 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1341 
    [ 2.500,  5.000) = 211617 
    [ 5.000,  7.500) = 22147 
    [ 7.500, 10.000) = 1157 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     15.073 ms/op
     p(99.9900) =     25.395 ms/op
     p(99.9990) =     26.956 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.405 ± 1.258  ops/ms
ClientGrpc.existUser                       thrpt       3  11.086 ± 1.451  ops/ms
ClientGrpc.getUser                         thrpt       3  10.464 ± 3.098  ops/ms
ClientGrpc.listUser                        thrpt       3   7.941 ± 0.845  ops/ms
ClientGrpc.createUser                       avgt       3   3.036 ± 0.056   ms/op
ClientGrpc.existUser                        avgt       3   2.893 ± 0.491   ms/op
ClientGrpc.getUser                          avgt       3   3.067 ± 0.691   ms/op
ClientGrpc.listUser                         avgt       3   4.025 ± 1.975   ms/op
ClientGrpc.createUser                     sample  310573   3.093 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.897           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.608           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.889           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.054           ms/op
ClientGrpc.existUser                      sample  325195   2.952 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.731           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.207           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.884           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.361           ms/op
ClientGrpc.getUser                        sample  315683   3.040 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.563           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.406           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.653           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.350           ms/op
ClientGrpc.listUser                       sample  236751   4.057 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.823           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.073           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.395           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.099           ms/op
