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
# Warmup Iteration   1: 3.819 ops/ms
# Warmup Iteration   2: 8.530 ops/ms
# Warmup Iteration   3: 10.000 ops/ms
Iteration   1: 10.426 ops/ms
Iteration   2: 10.277 ops/ms
Iteration   3: 10.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.313 ±(99.9%) 1.825 ops/ms [Average]
  (min, avg, max) = (10.236, 10.313, 10.426), stdev = 0.100
  CI (99.9%): [8.488, 12.138] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 7.654 ops/ms
# Warmup Iteration   2: 10.316 ops/ms
# Warmup Iteration   3: 10.891 ops/ms
Iteration   1: 11.092 ops/ms
Iteration   2: 10.829 ops/ms
Iteration   3: 10.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.900 ±(99.9%) 3.061 ops/ms [Average]
  (min, avg, max) = (10.780, 10.900, 11.092), stdev = 0.168
  CI (99.9%): [7.840, 13.961] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.076 ops/ms
# Warmup Iteration   2: 9.854 ops/ms
# Warmup Iteration   3: 10.163 ops/ms
Iteration   1: 10.574 ops/ms
Iteration   2: 10.572 ops/ms
Iteration   3: 10.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.571 ±(99.9%) 0.073 ops/ms [Average]
  (min, avg, max) = (10.567, 10.571, 10.574), stdev = 0.004
  CI (99.9%): [10.499, 10.644] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.884 ops/ms
# Warmup Iteration   2: 7.593 ops/ms
# Warmup Iteration   3: 8.059 ops/ms
Iteration   1: 8.083 ops/ms
Iteration   2: 7.887 ops/ms
Iteration   3: 8.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.037 ±(99.9%) 2.417 ops/ms [Average]
  (min, avg, max) = (7.887, 8.037, 8.140), stdev = 0.132
  CI (99.9%): [5.620, 10.453] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.289 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.003 ms/op
Iteration   1: 3.031 ±(99.9%) 0.002 ms/op
Iteration   2: 3.098 ±(99.9%) 0.003 ms/op
Iteration   3: 3.035 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.055 ±(99.9%) 0.683 ms/op [Average]
  (min, avg, max) = (3.031, 3.055, 3.098), stdev = 0.037
  CI (99.9%): [2.371, 3.738] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.941 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.926 ±(99.9%) 0.004 ms/op
Iteration   1: 2.936 ±(99.9%) 0.002 ms/op
Iteration   2: 2.880 ±(99.9%) 0.001 ms/op
Iteration   3: 2.861 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.892 ±(99.9%) 0.707 ms/op [Average]
  (min, avg, max) = (2.861, 2.892, 2.936), stdev = 0.039
  CI (99.9%): [2.185, 3.600] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.359 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.022 ms/op
Iteration   1: 3.016 ±(99.9%) 0.003 ms/op
Iteration   2: 3.039 ±(99.9%) 0.002 ms/op
Iteration   3: 3.029 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.028 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (3.016, 3.028, 3.039), stdev = 0.011
  CI (99.9%): [2.818, 3.238] (assumes normal distribution)


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
# Warmup Iteration   1: 5.742 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.031 ms/op
Iteration   1: 3.945 ±(99.9%) 0.010 ms/op
Iteration   2: 3.936 ±(99.9%) 0.015 ms/op
Iteration   3: 3.881 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.921 ±(99.9%) 0.632 ms/op [Average]
  (min, avg, max) = (3.881, 3.921, 3.945), stdev = 0.035
  CI (99.9%): [3.289, 4.553] (assumes normal distribution)


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
# Warmup Iteration   1: 4.303 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.007 ms/op
Iteration   1: 2.997 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  7.000 ms/op
                 createUser·p0.9999: 13.025 ms/op
                 createUser·p1.00:   13.386 ms/op

Iteration   2: 3.106 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  8.020 ms/op
                 createUser·p0.9999: 15.194 ms/op
                 createUser·p1.00:   15.401 ms/op

Iteration   3: 3.036 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.589 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  10.979 ms/op
                 createUser·p0.9999: 21.773 ms/op
                 createUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315253
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25508 
    [ 2.500,  5.000) = 288314 
    [ 5.000,  7.500) = 1015 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      8.761 ms/op
     p(99.9900) =     21.396 ms/op
     p(99.9990) =     21.940 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 4.113 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.007 ms/op
Iteration   1: 2.926 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.429 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.005 ms/op
                 existUser·p0.999:  5.226 ms/op
                 existUser·p0.9999: 13.176 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   2: 2.906 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.308 ms/op
                 existUser·p0.999:  8.077 ms/op
                 existUser·p0.9999: 19.825 ms/op
                 existUser·p1.00:   21.332 ms/op

Iteration   3: 2.978 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.472 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  9.454 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326812
  mean =      2.937 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35328 
    [ 2.500,  5.000) = 290519 
    [ 5.000,  7.500) = 621 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      7.622 ms/op
     p(99.9900) =     19.278 ms/op
     p(99.9990) =     21.175 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 4.549 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.007 ms/op
Iteration   1: 3.065 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.605 ms/op
                 getUser·p0.9999: 23.560 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  10.645 ms/op
                 getUser·p0.9999: 19.152 ms/op
                 getUser·p1.00:   20.021 ms/op

Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.925 ms/op
                 getUser·p0.9999: 20.950 ms/op
                 getUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316340
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21499 
    [ 2.500,  5.000) = 293518 
    [ 5.000,  7.500) = 961 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.995 ms/op
     p(99.9900) =     20.885 ms/op
     p(99.9990) =     23.784 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 4.941 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.011 ms/op
Iteration   1: 3.921 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  14.636 ms/op
                 listUser·p0.9999: 17.629 ms/op
                 listUser·p1.00:   18.186 ms/op

Iteration   2: 3.906 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  17.768 ms/op
                 listUser·p0.9999: 21.360 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   3: 3.960 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  17.637 ms/op
                 listUser·p0.9999: 19.658 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244347
  mean =      3.929 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3552 
    [ 2.500,  5.000) = 218747 
    [ 5.000,  7.500) = 20467 
    [ 7.500, 10.000) = 981 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     17.093 ms/op
     p(99.9900) =     20.517 ms/op
     p(99.9990) =     21.984 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.313 ± 1.825  ops/ms
ClientGrpc.existUser                       thrpt       3  10.900 ± 3.061  ops/ms
ClientGrpc.getUser                         thrpt       3  10.571 ± 0.073  ops/ms
ClientGrpc.listUser                        thrpt       3   8.037 ± 2.417  ops/ms
ClientGrpc.createUser                       avgt       3   3.055 ± 0.683   ms/op
ClientGrpc.existUser                        avgt       3   2.892 ± 0.707   ms/op
ClientGrpc.getUser                          avgt       3   3.028 ± 0.210   ms/op
ClientGrpc.listUser                         avgt       3   3.921 ± 0.632   ms/op
ClientGrpc.createUser                     sample  315253   3.046 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.589           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.761           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.396           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.020           ms/op
ClientGrpc.existUser                      sample  326812   2.937 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.429           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.622           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.278           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.332           ms/op
ClientGrpc.getUser                        sample  316340   3.033 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.732           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.995           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.885           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.888           ms/op
ClientGrpc.listUser                       sample  244347   3.929 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.869           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.093           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.517           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.512           ms/op
