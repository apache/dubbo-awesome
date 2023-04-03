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
# Warmup Iteration   1: 3.826 ops/ms
# Warmup Iteration   2: 8.543 ops/ms
# Warmup Iteration   3: 9.895 ops/ms
Iteration   1: 10.319 ops/ms
Iteration   2: 10.606 ops/ms
Iteration   3: 10.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.409 ±(99.9%) 3.123 ops/ms [Average]
  (min, avg, max) = (10.302, 10.409, 10.606), stdev = 0.171
  CI (99.9%): [7.286, 13.532] (assumes normal distribution)


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
# Warmup Iteration   1: 6.888 ops/ms
# Warmup Iteration   2: 10.639 ops/ms
# Warmup Iteration   3: 11.036 ops/ms
Iteration   1: 11.028 ops/ms
Iteration   2: 11.048 ops/ms
Iteration   3: 10.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.021 ±(99.9%) 0.579 ops/ms [Average]
  (min, avg, max) = (10.986, 11.021, 11.048), stdev = 0.032
  CI (99.9%): [10.442, 11.599] (assumes normal distribution)


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
# Warmup Iteration   1: 6.695 ops/ms
# Warmup Iteration   2: 9.788 ops/ms
# Warmup Iteration   3: 10.298 ops/ms
Iteration   1: 10.568 ops/ms
Iteration   2: 10.383 ops/ms
Iteration   3: 10.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.461 ±(99.9%) 1.751 ops/ms [Average]
  (min, avg, max) = (10.383, 10.461, 10.568), stdev = 0.096
  CI (99.9%): [8.710, 12.212] (assumes normal distribution)


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
# Warmup Iteration   1: 5.502 ops/ms
# Warmup Iteration   2: 7.669 ops/ms
# Warmup Iteration   3: 7.857 ops/ms
Iteration   1: 7.999 ops/ms
Iteration   2: 7.935 ops/ms
Iteration   3: 7.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.926 ±(99.9%) 1.413 ops/ms [Average]
  (min, avg, max) = (7.845, 7.926, 7.999), stdev = 0.077
  CI (99.9%): [6.513, 9.340] (assumes normal distribution)


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
# Warmup Iteration   1: 4.607 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.004 ms/op
Iteration   1: 3.026 ±(99.9%) 0.003 ms/op
Iteration   2: 3.079 ±(99.9%) 0.002 ms/op
Iteration   3: 3.021 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.042 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (3.021, 3.042, 3.079), stdev = 0.032
  CI (99.9%): [2.456, 3.628] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.914 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.002 ms/op
Iteration   1: 2.886 ±(99.9%) 0.003 ms/op
Iteration   2: 2.949 ±(99.9%) 0.002 ms/op
Iteration   3: 2.977 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.937 ±(99.9%) 0.843 ms/op [Average]
  (min, avg, max) = (2.886, 2.937, 2.977), stdev = 0.046
  CI (99.9%): [2.094, 3.781] (assumes normal distribution)


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
# Warmup Iteration   1: 4.438 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.004 ms/op
Iteration   1: 3.101 ±(99.9%) 0.002 ms/op
Iteration   2: 3.064 ±(99.9%) 0.002 ms/op
Iteration   3: 3.044 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.069 ±(99.9%) 0.529 ms/op [Average]
  (min, avg, max) = (3.044, 3.069, 3.101), stdev = 0.029
  CI (99.9%): [2.541, 3.598] (assumes normal distribution)


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
# Warmup Iteration   1: 5.286 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.014 ms/op
Iteration   1: 4.009 ±(99.9%) 0.017 ms/op
Iteration   2: 4.038 ±(99.9%) 0.028 ms/op
Iteration   3: 3.946 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.998 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.946, 3.998, 4.038), stdev = 0.047
  CI (99.9%): [3.145, 4.851] (assumes normal distribution)


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
# Warmup Iteration   1: 4.277 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.006 ms/op
Iteration   1: 3.035 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.875 ms/op
                 createUser·p0.9999: 12.451 ms/op
                 createUser·p1.00:   13.976 ms/op

Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.229 ms/op
                 createUser·p0.9999: 22.662 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   3: 3.036 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  9.614 ms/op
                 createUser·p0.9999: 23.364 ms/op
                 createUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315104
  mean =      3.047 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21885 
    [ 2.500,  5.000) = 291811 
    [ 5.000,  7.500) = 1040 
    [ 7.500, 10.000) = 144 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.864 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     24.097 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 3.983 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.005 ms/op
Iteration   1: 2.977 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.893 ms/op
                 existUser·p0.9999: 13.157 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   2: 2.991 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  11.289 ms/op
                 existUser·p0.9999: 24.642 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   3: 3.018 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  13.319 ms/op
                 existUser·p0.9999: 17.478 ms/op
                 existUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320414
  mean =      2.995 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28153 
    [ 2.500,  5.000) = 290850 
    [ 5.000,  7.500) = 860 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =     11.275 ms/op
     p(99.9900) =     23.142 ms/op
     p(99.9990) =     24.858 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 4.591 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.006 ms/op
Iteration   1: 3.084 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.607 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.673 ms/op
                 getUser·p0.9999: 16.214 ms/op
                 getUser·p1.00:   16.482 ms/op

Iteration   2: 3.062 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.476 ms/op
                 getUser·p0.999:  7.512 ms/op
                 getUser·p0.9999: 14.986 ms/op
                 getUser·p1.00:   15.417 ms/op

Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.496 ms/op
                 getUser·p0.9999: 17.045 ms/op
                 getUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312264
  mean =      3.074 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 448 
    [ 1.250,  2.500) = 13205 
    [ 2.500,  3.750) = 282131 
    [ 3.750,  5.000) = 14815 
    [ 5.000,  6.250) = 1059 
    [ 6.250,  7.500) = 272 
    [ 7.500,  8.750) = 132 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 91 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.610 ms/op
     p(99.9900) =     16.348 ms/op
     p(99.9990) =     17.392 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 5.306 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.011 ms/op
Iteration   1: 3.986 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.004 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 18.348 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   2: 4.076 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  18.030 ms/op
                 listUser·p0.9999: 19.609 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   3: 4.022 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  18.438 ms/op
                 listUser·p0.9999: 22.809 ms/op
                 listUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238611
  mean =      4.027 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2530 
    [ 2.500,  5.000) = 207426 
    [ 5.000,  7.500) = 26966 
    [ 7.500, 10.000) = 1231 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     15.987 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     24.904 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.409 ± 3.123  ops/ms
ClientGrpc.existUser                       thrpt       3  11.021 ± 0.579  ops/ms
ClientGrpc.getUser                         thrpt       3  10.461 ± 1.751  ops/ms
ClientGrpc.listUser                        thrpt       3   7.926 ± 1.413  ops/ms
ClientGrpc.createUser                       avgt       3   3.042 ± 0.586   ms/op
ClientGrpc.existUser                        avgt       3   2.937 ± 0.843   ms/op
ClientGrpc.getUser                          avgt       3   3.069 ± 0.529   ms/op
ClientGrpc.listUser                         avgt       3   3.998 ± 0.853   ms/op
ClientGrpc.createUser                     sample  315104   3.047 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.717           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.864           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.610           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.150           ms/op
ClientGrpc.existUser                      sample  320414   2.995 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.732           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.275           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.142           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.461           ms/op
ClientGrpc.getUser                        sample  312264   3.074 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.607           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.610           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.348           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.531           ms/op
ClientGrpc.listUser                       sample  238611   4.027 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.861           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.841           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.184           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.987           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.413           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.378           ms/op
