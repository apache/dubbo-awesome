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
# Warmup Iteration   1: 4.253 ops/ms
# Warmup Iteration   2: 8.906 ops/ms
# Warmup Iteration   3: 9.815 ops/ms
Iteration   1: 10.143 ops/ms
Iteration   2: 10.061 ops/ms
Iteration   3: 9.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.019 ±(99.9%) 2.731 ops/ms [Average]
  (min, avg, max) = (9.853, 10.019, 10.143), stdev = 0.150
  CI (99.9%): [7.288, 12.750] (assumes normal distribution)


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
# Warmup Iteration   1: 7.289 ops/ms
# Warmup Iteration   2: 10.016 ops/ms
# Warmup Iteration   3: 10.516 ops/ms
Iteration   1: 10.318 ops/ms
Iteration   2: 10.829 ops/ms
Iteration   3: 10.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.609 ±(99.9%) 4.801 ops/ms [Average]
  (min, avg, max) = (10.318, 10.609, 10.829), stdev = 0.263
  CI (99.9%): [5.808, 15.411] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.807 ops/ms
# Warmup Iteration   2: 10.040 ops/ms
# Warmup Iteration   3: 10.084 ops/ms
Iteration   1: 9.881 ops/ms
Iteration   2: 9.807 ops/ms
Iteration   3: 10.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.913 ±(99.9%) 2.287 ops/ms [Average]
  (min, avg, max) = (9.807, 9.913, 10.052), stdev = 0.125
  CI (99.9%): [7.626, 12.200] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.728 ops/ms
# Warmup Iteration   2: 7.721 ops/ms
# Warmup Iteration   3: 7.871 ops/ms
Iteration   1: 7.914 ops/ms
Iteration   2: 8.009 ops/ms
Iteration   3: 7.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.969 ±(99.9%) 0.896 ops/ms [Average]
  (min, avg, max) = (7.914, 7.969, 8.009), stdev = 0.049
  CI (99.9%): [7.073, 8.865] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.195 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.003 ms/op
Iteration   1: 3.201 ±(99.9%) 0.009 ms/op
Iteration   2: 3.247 ±(99.9%) 0.002 ms/op
Iteration   3: 3.239 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.229 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (3.201, 3.229, 3.247), stdev = 0.024
  CI (99.9%): [2.782, 3.676] (assumes normal distribution)


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
# Warmup Iteration   1: 4.158 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.003 ms/op
Iteration   1: 3.048 ±(99.9%) 0.002 ms/op
Iteration   2: 2.928 ±(99.9%) 0.002 ms/op
Iteration   3: 3.047 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.008 ±(99.9%) 1.258 ms/op [Average]
  (min, avg, max) = (2.928, 3.008, 3.048), stdev = 0.069
  CI (99.9%): [1.750, 4.266] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.366 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.003 ms/op
Iteration   1: 3.160 ±(99.9%) 0.002 ms/op
Iteration   2: 3.204 ±(99.9%) 0.002 ms/op
Iteration   3: 3.203 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.189 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (3.160, 3.189, 3.204), stdev = 0.025
  CI (99.9%): [2.725, 3.653] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.903 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.173 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.015 ms/op
Iteration   1: 4.014 ±(99.9%) 0.024 ms/op
Iteration   2: 4.025 ±(99.9%) 0.022 ms/op
Iteration   3: 4.104 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.048 ±(99.9%) 0.899 ms/op [Average]
  (min, avg, max) = (4.014, 4.048, 4.104), stdev = 0.049
  CI (99.9%): [3.149, 4.947] (assumes normal distribution)


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
# Warmup Iteration   1: 4.336 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.359 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.006 ms/op
Iteration   1: 3.230 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  7.750 ms/op
                 createUser·p0.9999: 17.471 ms/op
                 createUser·p1.00:   18.022 ms/op

Iteration   2: 3.240 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  8.014 ms/op
                 createUser·p0.9999: 20.873 ms/op
                 createUser·p1.00:   21.299 ms/op

Iteration   3: 3.160 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  9.884 ms/op
                 createUser·p0.9999: 31.748 ms/op
                 createUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 299098
  mean =      3.210 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18765 
    [ 2.500,  5.000) = 278952 
    [ 5.000,  7.500) = 951 
    [ 7.500, 10.000) = 206 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      8.240 ms/op
     p(99.9900) =     30.638 ms/op
     p(99.9990) =     31.883 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 4.132 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.006 ms/op
Iteration   1: 3.088 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  6.426 ms/op
                 existUser·p0.9999: 13.356 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   2: 2.992 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.880 ms/op
                 existUser·p0.9999: 22.194 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 3.090 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.279 ms/op
                 existUser·p0.9999: 17.017 ms/op
                 existUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314119
  mean =      3.056 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42150 
    [ 2.500,  5.000) = 271250 
    [ 5.000,  7.500) = 496 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.610 ms/op
     p(99.9900) =     21.567 ms/op
     p(99.9990) =     22.437 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.006 ms/op
Iteration   1: 3.170 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  7.866 ms/op
                 getUser·p0.9999: 12.826 ms/op
                 getUser·p1.00:   13.042 ms/op

Iteration   2: 3.164 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  9.927 ms/op
                 getUser·p0.9999: 15.663 ms/op
                 getUser·p1.00:   15.991 ms/op

Iteration   3: 3.231 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.444 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.432 ms/op
                 getUser·p0.9999: 16.850 ms/op
                 getUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300817
  mean =      3.188 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 380 
    [ 1.250,  2.500) = 18756 
    [ 2.500,  3.750) = 238989 
    [ 3.750,  5.000) = 41082 
    [ 5.000,  6.250) = 938 
    [ 6.250,  7.500) = 292 
    [ 7.500,  8.750) = 134 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.954 ms/op
     p(99.9900) =     16.443 ms/op
     p(99.9990) =     17.137 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 5.242 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.011 ms/op
Iteration   1: 3.967 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  16.477 ms/op
                 listUser·p0.9999: 24.738 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   2: 4.034 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.783 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  17.124 ms/op
                 listUser·p0.9999: 23.366 ms/op
                 listUser·p1.00:   24.936 ms/op

Iteration   3: 3.988 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  16.018 ms/op
                 listUser·p0.9999: 24.935 ms/op
                 listUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240187
  mean =      3.996 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2679 
    [ 2.500,  5.000) = 212883 
    [ 5.000,  7.500) = 23498 
    [ 7.500, 10.000) = 695 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     16.378 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     26.024 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.019 ± 2.731  ops/ms
ClientGrpc.existUser                       thrpt       3  10.609 ± 4.801  ops/ms
ClientGrpc.getUser                         thrpt       3   9.913 ± 2.287  ops/ms
ClientGrpc.listUser                        thrpt       3   7.969 ± 0.896  ops/ms
ClientGrpc.createUser                       avgt       3   3.229 ± 0.447   ms/op
ClientGrpc.existUser                        avgt       3   3.008 ± 1.258   ms/op
ClientGrpc.getUser                          avgt       3   3.189 ± 0.464   ms/op
ClientGrpc.listUser                         avgt       3   4.048 ± 0.899   ms/op
ClientGrpc.createUser                     sample  299098   3.210 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.784           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.166           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.899           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.096           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.240           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.638           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.949           ms/op
ClientGrpc.existUser                      sample  314119   3.056 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.753           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.052           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.973           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.610           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.567           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.577           ms/op
ClientGrpc.getUser                        sample  300817   3.188 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.444           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.154           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.059           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.954           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.443           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.302           ms/op
ClientGrpc.listUser                       sample  240187   3.996 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.783           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.378           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.773           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.083           ms/op
