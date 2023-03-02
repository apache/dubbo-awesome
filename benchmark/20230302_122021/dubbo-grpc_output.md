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
# Warmup Iteration   1: 4.395 ops/ms
# Warmup Iteration   2: 8.931 ops/ms
# Warmup Iteration   3: 10.090 ops/ms
Iteration   1: 10.146 ops/ms
Iteration   2: 10.228 ops/ms
Iteration   3: 10.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.179 ±(99.9%) 0.788 ops/ms [Average]
  (min, avg, max) = (10.146, 10.179, 10.228), stdev = 0.043
  CI (99.9%): [9.391, 10.968] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.377 ops/ms
# Warmup Iteration   2: 10.423 ops/ms
# Warmup Iteration   3: 10.858 ops/ms
Iteration   1: 10.551 ops/ms
Iteration   2: 10.503 ops/ms
Iteration   3: 10.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.492 ±(99.9%) 1.184 ops/ms [Average]
  (min, avg, max) = (10.422, 10.492, 10.551), stdev = 0.065
  CI (99.9%): [9.308, 11.676] (assumes normal distribution)


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
# Warmup Iteration   1: 6.960 ops/ms
# Warmup Iteration   2: 10.057 ops/ms
# Warmup Iteration   3: 10.171 ops/ms
Iteration   1: 10.189 ops/ms
Iteration   2: 10.080 ops/ms
Iteration   3: 10.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.145 ±(99.9%) 1.053 ops/ms [Average]
  (min, avg, max) = (10.080, 10.145, 10.189), stdev = 0.058
  CI (99.9%): [9.093, 11.198] (assumes normal distribution)


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
# Warmup Iteration   1: 6.143 ops/ms
# Warmup Iteration   2: 7.605 ops/ms
# Warmup Iteration   3: 7.885 ops/ms
Iteration   1: 8.133 ops/ms
Iteration   2: 7.999 ops/ms
Iteration   3: 8.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.056 ±(99.9%) 1.271 ops/ms [Average]
  (min, avg, max) = (7.999, 8.056, 8.133), stdev = 0.070
  CI (99.9%): [6.785, 9.326] (assumes normal distribution)


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
# Warmup Iteration   1: 4.253 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.002 ms/op
Iteration   1: 3.034 ±(99.9%) 0.003 ms/op
Iteration   2: 3.107 ±(99.9%) 0.003 ms/op
Iteration   3: 3.207 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.116 ±(99.9%) 1.577 ms/op [Average]
  (min, avg, max) = (3.034, 3.116, 3.207), stdev = 0.086
  CI (99.9%): [1.540, 4.693] (assumes normal distribution)


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.002 ms/op
Iteration   1: 3.109 ±(99.9%) 0.001 ms/op
Iteration   2: 3.041 ±(99.9%) 0.002 ms/op
Iteration   3: 2.988 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.046 ±(99.9%) 1.106 ms/op [Average]
  (min, avg, max) = (2.988, 3.046, 3.109), stdev = 0.061
  CI (99.9%): [1.940, 4.152] (assumes normal distribution)


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.003 ms/op
Iteration   1: 3.200 ±(99.9%) 0.003 ms/op
Iteration   2: 3.076 ±(99.9%) 0.004 ms/op
Iteration   3: 3.089 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.121 ±(99.9%) 1.240 ms/op [Average]
  (min, avg, max) = (3.076, 3.121, 3.200), stdev = 0.068
  CI (99.9%): [1.882, 4.361] (assumes normal distribution)


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
# Warmup Iteration   1: 5.057 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.178 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.024 ms/op
Iteration   1: 3.927 ±(99.9%) 0.006 ms/op
Iteration   2: 3.952 ±(99.9%) 0.006 ms/op
Iteration   3: 3.963 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.947 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (3.927, 3.947, 3.963), stdev = 0.019
  CI (99.9%): [3.607, 4.288] (assumes normal distribution)


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.006 ms/op
Iteration   1: 3.146 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.741 ms/op
                 createUser·p0.9999: 12.856 ms/op
                 createUser·p1.00:   13.173 ms/op

Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.094 ms/op
                 createUser·p0.9999: 15.091 ms/op
                 createUser·p1.00:   16.286 ms/op

Iteration   3: 3.225 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.828 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  9.557 ms/op
                 createUser·p0.9999: 16.777 ms/op
                 createUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307211
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 629 
    [ 1.250,  2.500) = 26937 
    [ 2.500,  3.750) = 243764 
    [ 3.750,  5.000) = 34623 
    [ 5.000,  6.250) = 678 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.676 ms/op
     p(99.9900) =     16.470 ms/op
     p(99.9990) =     16.906 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.006 ms/op
Iteration   1: 3.048 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.496 ms/op
                 existUser·p0.9999: 12.378 ms/op
                 existUser·p1.00:   12.943 ms/op

Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  5.906 ms/op
                 existUser·p0.9999: 14.330 ms/op
                 existUser·p1.00:   14.778 ms/op

Iteration   3: 2.966 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.301 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  9.735 ms/op
                 existUser·p0.9999: 26.378 ms/op
                 existUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318782
  mean =      3.011 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46793 
    [ 2.500,  5.000) = 271118 
    [ 5.000,  7.500) = 551 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.301 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.522 ms/op
     p(99.9900) =     25.825 ms/op
     p(99.9990) =     26.655 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 4.164 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
Iteration   1: 3.184 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  8.320 ms/op
                 getUser·p0.9999: 13.500 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   2: 3.185 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   4.362 ms/op
                 getUser·p0.999:  6.696 ms/op
                 getUser·p0.9999: 13.973 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   3: 3.138 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.870 ms/op
                 getUser·p0.9999: 31.057 ms/op
                 getUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303007
  mean =      3.169 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20871 
    [ 2.500,  5.000) = 280930 
    [ 5.000,  7.500) = 905 
    [ 7.500, 10.000) = 120 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.487 ms/op
     p(99.9900) =     30.350 ms/op
     p(99.9990) =     31.454 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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
# Warmup Iteration   1: 5.217 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.296 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.012 ms/op
Iteration   1: 3.992 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.582 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  13.660 ms/op
                 listUser·p0.9999: 17.268 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   2: 3.942 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.432 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   3: 4.053 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.031 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  16.532 ms/op
                 listUser·p0.9999: 28.511 ms/op
                 listUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240189
  mean =      3.995 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4016 
    [ 2.500,  5.000) = 209765 
    [ 5.000,  7.500) = 25235 
    [ 7.500, 10.000) = 672 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     27.228 ms/op
     p(99.9990) =     28.875 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.179 ± 0.788  ops/ms
ClientGrpc.existUser                       thrpt       3  10.492 ± 1.184  ops/ms
ClientGrpc.getUser                         thrpt       3  10.145 ± 1.053  ops/ms
ClientGrpc.listUser                        thrpt       3   8.056 ± 1.271  ops/ms
ClientGrpc.createUser                       avgt       3   3.116 ± 1.577   ms/op
ClientGrpc.existUser                        avgt       3   3.046 ± 1.106   ms/op
ClientGrpc.getUser                          avgt       3   3.121 ± 1.240   ms/op
ClientGrpc.listUser                         avgt       3   3.947 ± 0.341   ms/op
ClientGrpc.createUser                     sample  307211   3.123 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.796           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.022           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.676           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.470           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.039           ms/op
ClientGrpc.existUser                      sample  318782   3.011 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.301           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.023           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.891           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.522           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.825           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.918           ms/op
ClientGrpc.getUser                        sample  303007   3.169 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.558           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.142           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.022           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.487           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.350           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.556           ms/op
ClientGrpc.listUser                       sample  240189   3.995 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.582           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.139           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.228           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.032           ms/op
