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
# Warmup Iteration   1: 4.518 ops/ms
# Warmup Iteration   2: 9.575 ops/ms
# Warmup Iteration   3: 10.044 ops/ms
Iteration   1: 10.536 ops/ms
Iteration   2: 10.285 ops/ms
Iteration   3: 10.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.366 ±(99.9%) 2.688 ops/ms [Average]
  (min, avg, max) = (10.277, 10.366, 10.536), stdev = 0.147
  CI (99.9%): [7.678, 13.054] (assumes normal distribution)


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
# Warmup Iteration   1: 8.070 ops/ms
# Warmup Iteration   2: 10.782 ops/ms
# Warmup Iteration   3: 10.966 ops/ms
Iteration   1: 10.878 ops/ms
Iteration   2: 10.414 ops/ms
Iteration   3: 10.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.725 ±(99.9%) 4.907 ops/ms [Average]
  (min, avg, max) = (10.414, 10.725, 10.882), stdev = 0.269
  CI (99.9%): [5.817, 15.632] (assumes normal distribution)


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
# Warmup Iteration   1: 7.735 ops/ms
# Warmup Iteration   2: 10.322 ops/ms
# Warmup Iteration   3: 10.084 ops/ms
Iteration   1: 10.309 ops/ms
Iteration   2: 10.137 ops/ms
Iteration   3: 10.188 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.212 ±(99.9%) 1.604 ops/ms [Average]
  (min, avg, max) = (10.137, 10.212, 10.309), stdev = 0.088
  CI (99.9%): [8.608, 11.815] (assumes normal distribution)


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
# Warmup Iteration   1: 7.046 ops/ms
# Warmup Iteration   2: 7.494 ops/ms
# Warmup Iteration   3: 7.791 ops/ms
Iteration   1: 8.068 ops/ms
Iteration   2: 8.177 ops/ms
Iteration   3: 8.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.098 ±(99.9%) 1.271 ops/ms [Average]
  (min, avg, max) = (8.048, 8.098, 8.177), stdev = 0.070
  CI (99.9%): [6.826, 9.369] (assumes normal distribution)


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
# Warmup Iteration   1: 3.959 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.009 ms/op
Iteration   1: 3.162 ±(99.9%) 0.002 ms/op
Iteration   2: 3.236 ±(99.9%) 0.009 ms/op
Iteration   3: 3.071 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.156 ±(99.9%) 1.514 ms/op [Average]
  (min, avg, max) = (3.071, 3.156, 3.236), stdev = 0.083
  CI (99.9%): [1.642, 4.670] (assumes normal distribution)


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
# Warmup Iteration   1: 3.569 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.002 ms/op
Iteration   1: 3.040 ±(99.9%) 0.002 ms/op
Iteration   2: 3.020 ±(99.9%) 0.002 ms/op
Iteration   3: 3.024 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.028 ±(99.9%) 0.190 ms/op [Average]
  (min, avg, max) = (3.020, 3.028, 3.040), stdev = 0.010
  CI (99.9%): [2.838, 3.217] (assumes normal distribution)


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.002 ms/op
Iteration   1: 3.032 ±(99.9%) 0.002 ms/op
Iteration   2: 3.153 ±(99.9%) 0.003 ms/op
Iteration   3: 3.125 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.103 ±(99.9%) 1.156 ms/op [Average]
  (min, avg, max) = (3.032, 3.103, 3.153), stdev = 0.063
  CI (99.9%): [1.947, 4.259] (assumes normal distribution)


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
# Warmup Iteration   1: 5.087 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.024 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.028 ms/op
Iteration   1: 3.962 ±(99.9%) 0.010 ms/op
Iteration   2: 4.143 ±(99.9%) 0.018 ms/op
Iteration   3: 3.957 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.021 ±(99.9%) 1.931 ms/op [Average]
  (min, avg, max) = (3.957, 4.021, 4.143), stdev = 0.106
  CI (99.9%): [2.089, 5.952] (assumes normal distribution)


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
# Warmup Iteration   1: 3.990 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.007 ms/op
Iteration   1: 3.161 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.670 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  8.284 ms/op
                 createUser·p0.9999: 11.633 ms/op
                 createUser·p1.00:   11.878 ms/op

Iteration   2: 3.203 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.524 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  8.005 ms/op
                 createUser·p0.9999: 20.907 ms/op
                 createUser·p1.00:   21.266 ms/op

Iteration   3: 3.116 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.343 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  8.890 ms/op
                 createUser·p0.9999: 25.148 ms/op
                 createUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303685
  mean =      3.159 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22367 
    [ 2.500,  5.000) = 279786 
    [ 5.000,  7.500) = 1138 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.343 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     24.748 ms/op
     p(99.9990) =     25.427 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 3.828 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.007 ms/op
Iteration   1: 3.061 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.676 ms/op
                 existUser·p0.9999: 13.192 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  7.075 ms/op
                 existUser·p0.9999: 12.496 ms/op
                 existUser·p1.00:   12.812 ms/op

Iteration   3: 2.993 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  5.685 ms/op
                 existUser·p0.9999: 25.952 ms/op
                 existUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315746
  mean =      3.041 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36235 
    [ 2.500,  5.000) = 278241 
    [ 5.000,  7.500) = 1107 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      6.468 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 3.626 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.007 ms/op
Iteration   1: 3.035 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.444 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.960 ms/op
                 getUser·p0.9999: 15.563 ms/op
                 getUser·p1.00:   16.187 ms/op

Iteration   2: 3.183 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.627 ms/op
                 getUser·p0.9999: 26.606 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   3: 3.053 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.777 ms/op
                 getUser·p0.9999: 31.999 ms/op
                 getUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310661
  mean =      3.089 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27489 
    [ 2.500,  5.000) = 282082 
    [ 5.000,  7.500) = 819 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.328 ms/op
     p(99.9000) =      7.206 ms/op
     p(99.9900) =     31.226 ms/op
     p(99.9990) =     32.178 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 4.856 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.201 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.117 ±(99.9%) 0.013 ms/op
Iteration   1: 4.086 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.853 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  14.598 ms/op
                 listUser·p0.9999: 19.732 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   2: 4.040 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  14.317 ms/op
                 listUser·p0.9999: 24.855 ms/op
                 listUser·p1.00:   25.494 ms/op

Iteration   3: 4.120 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.587 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   7.050 ms/op
                 listUser·p0.999:  15.892 ms/op
                 listUser·p0.9999: 22.061 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235182
  mean =      4.082 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4181 
    [ 2.500,  5.000) = 194174 
    [ 5.000,  7.500) = 35060 
    [ 7.500, 10.000) = 1147 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 233 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     15.291 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     25.187 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.366 ± 2.688  ops/ms
ClientGrpc.existUser                       thrpt       3  10.725 ± 4.907  ops/ms
ClientGrpc.getUser                         thrpt       3  10.212 ± 1.604  ops/ms
ClientGrpc.listUser                        thrpt       3   8.098 ± 1.271  ops/ms
ClientGrpc.createUser                       avgt       3   3.156 ± 1.514   ms/op
ClientGrpc.existUser                        avgt       3   3.028 ± 0.190   ms/op
ClientGrpc.getUser                          avgt       3   3.103 ± 1.156   ms/op
ClientGrpc.listUser                         avgt       3   4.021 ± 1.931   ms/op
ClientGrpc.createUser                     sample  303685   3.159 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.343           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.138           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.998           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.421           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.748           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.494           ms/op
ClientGrpc.existUser                      sample  315746   3.041 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.638           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.023           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.871           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.468           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.707           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.313           ms/op
ClientGrpc.getUser                        sample  310661   3.089 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.444           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.920           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.328           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.206           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.226           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.276           ms/op
ClientGrpc.listUser                       sample  235182   4.082 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.587           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.284           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.168           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.291           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.839           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.494           ms/op
