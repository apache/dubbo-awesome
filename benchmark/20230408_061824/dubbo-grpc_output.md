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
# Warmup Iteration   1: 4.479 ops/ms
# Warmup Iteration   2: 9.274 ops/ms
# Warmup Iteration   3: 10.237 ops/ms
Iteration   1: 10.651 ops/ms
Iteration   2: 10.885 ops/ms
Iteration   3: 10.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.748 ±(99.9%) 2.221 ops/ms [Average]
  (min, avg, max) = (10.651, 10.748, 10.885), stdev = 0.122
  CI (99.9%): [8.528, 12.969] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.874 ops/ms
# Warmup Iteration   2: 10.833 ops/ms
# Warmup Iteration   3: 11.310 ops/ms
Iteration   1: 11.286 ops/ms
Iteration   2: 11.123 ops/ms
Iteration   3: 11.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.223 ±(99.9%) 1.597 ops/ms [Average]
  (min, avg, max) = (11.123, 11.223, 11.286), stdev = 0.088
  CI (99.9%): [9.626, 12.820] (assumes normal distribution)


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
# Warmup Iteration   1: 7.384 ops/ms
# Warmup Iteration   2: 10.578 ops/ms
# Warmup Iteration   3: 10.748 ops/ms
Iteration   1: 10.836 ops/ms
Iteration   2: 10.857 ops/ms
Iteration   3: 10.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.802 ±(99.9%) 1.422 ops/ms [Average]
  (min, avg, max) = (10.713, 10.802, 10.857), stdev = 0.078
  CI (99.9%): [9.380, 12.224] (assumes normal distribution)


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
# Warmup Iteration   1: 5.813 ops/ms
# Warmup Iteration   2: 7.910 ops/ms
# Warmup Iteration   3: 8.343 ops/ms
Iteration   1: 8.164 ops/ms
Iteration   2: 8.289 ops/ms
Iteration   3: 8.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.324 ±(99.9%) 3.273 ops/ms [Average]
  (min, avg, max) = (8.164, 8.324, 8.518), stdev = 0.179
  CI (99.9%): [5.051, 11.597] (assumes normal distribution)


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
# Warmup Iteration   1: 4.037 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.003 ms/op
Iteration   1: 3.000 ±(99.9%) 0.002 ms/op
Iteration   2: 3.020 ±(99.9%) 0.002 ms/op
Iteration   3: 3.013 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.011 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (3.000, 3.011, 3.020), stdev = 0.010
  CI (99.9%): [2.823, 3.199] (assumes normal distribution)


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.922 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.933 ±(99.9%) 0.003 ms/op
Iteration   1: 3.227 ±(99.9%) 0.004 ms/op
Iteration   2: 3.075 ±(99.9%) 0.004 ms/op
Iteration   3: 2.893 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.065 ±(99.9%) 3.055 ms/op [Average]
  (min, avg, max) = (2.893, 3.065, 3.227), stdev = 0.167
  CI (99.9%): [0.010, 6.121] (assumes normal distribution)


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
# Warmup Iteration   1: 4.342 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.002 ms/op
Iteration   1: 3.061 ±(99.9%) 0.002 ms/op
Iteration   2: 2.969 ±(99.9%) 0.005 ms/op
Iteration   3: 2.944 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.991 ±(99.9%) 1.125 ms/op [Average]
  (min, avg, max) = (2.944, 2.991, 3.061), stdev = 0.062
  CI (99.9%): [1.866, 4.116] (assumes normal distribution)


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
# Warmup Iteration   1: 5.055 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.223 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 3.924 ±(99.9%) 0.037 ms/op
Iteration   1: 3.963 ±(99.9%) 0.020 ms/op
Iteration   2: 3.905 ±(99.9%) 0.015 ms/op
Iteration   3: 3.878 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.916 ±(99.9%) 0.789 ms/op [Average]
  (min, avg, max) = (3.878, 3.916, 3.963), stdev = 0.043
  CI (99.9%): [3.126, 4.705] (assumes normal distribution)


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
# Warmup Iteration   1: 5.107 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.762 ±(99.9%) 0.009 ms/op
Iteration   1: 3.297 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.079 ms/op
                 createUser·p0.999:  10.552 ms/op
                 createUser·p0.9999: 12.957 ms/op
                 createUser·p1.00:   13.517 ms/op

Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  6.479 ms/op
                 createUser·p0.9999: 18.953 ms/op
                 createUser·p1.00:   20.218 ms/op

Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  12.526 ms/op
                 createUser·p0.9999: 19.381 ms/op
                 createUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310511
  mean =      3.094 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23905 
    [ 2.500,  5.000) = 284844 
    [ 5.000,  7.500) = 1275 
    [ 7.500, 10.000) = 185 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      9.715 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     19.625 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 4.485 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.961 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.833 ±(99.9%) 0.007 ms/op
Iteration   1: 2.887 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  6.791 ms/op
                 existUser·p0.9999: 11.911 ms/op
                 existUser·p1.00:   12.042 ms/op

Iteration   2: 2.878 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.353 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.152 ms/op
                 existUser·p0.9999: 13.496 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.881 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  9.600 ms/op
                 existUser·p0.9999: 15.217 ms/op
                 existUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333128
  mean =      2.882 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1874 
    [ 1.250,  2.500) = 32039 
    [ 2.500,  3.750) = 290539 
    [ 3.750,  5.000) = 7803 
    [ 5.000,  6.250) = 343 
    [ 6.250,  7.500) = 226 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.265 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.249 ms/op
     p(99.9900) =     13.839 ms/op
     p(99.9990) =     16.592 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 3.820 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.007 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.449 ms/op
                 getUser·p0.9999: 13.475 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   2: 2.995 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.639 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.251 ms/op
                 getUser·p0.9999: 26.870 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.684 ms/op
                 getUser·p0.9999: 17.531 ms/op
                 getUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321133
  mean =      2.990 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30350 
    [ 2.500,  5.000) = 289642 
    [ 5.000,  7.500) = 795 
    [ 7.500, 10.000) = 115 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.804 ms/op
     p(99.9900) =     25.332 ms/op
     p(99.9990) =     27.092 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 5.121 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.844 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.012 ms/op
Iteration   1: 3.888 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.304 ms/op
                 listUser·p0.9999: 18.368 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   2: 3.701 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  15.296 ms/op
                 listUser·p0.9999: 18.493 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   3: 3.817 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.578 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  16.499 ms/op
                 listUser·p0.9999: 23.470 ms/op
                 listUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252485
  mean =      3.800 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6540 
    [ 2.500,  5.000) = 225554 
    [ 5.000,  7.500) = 19229 
    [ 7.500, 10.000) = 714 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     15.508 ms/op
     p(99.9900) =     22.012 ms/op
     p(99.9990) =     23.952 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.748 ± 2.221  ops/ms
ClientGrpc.existUser                       thrpt       3  11.223 ± 1.597  ops/ms
ClientGrpc.getUser                         thrpt       3  10.802 ± 1.422  ops/ms
ClientGrpc.listUser                        thrpt       3   8.324 ± 3.273  ops/ms
ClientGrpc.createUser                       avgt       3   3.011 ± 0.188   ms/op
ClientGrpc.existUser                        avgt       3   3.065 ± 3.055   ms/op
ClientGrpc.getUser                          avgt       3   2.991 ± 1.125   ms/op
ClientGrpc.listUser                         avgt       3   3.916 ± 0.789   ms/op
ClientGrpc.createUser                     sample  310511   3.094 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.647           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.973           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.715           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.071           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.218           ms/op
ClientGrpc.existUser                      sample  333128   2.882 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.558           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.265           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.249           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.839           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.810           ms/op
ClientGrpc.getUser                        sample  321133   2.990 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.546           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.804           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.332           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.197           ms/op
ClientGrpc.listUser                       sample  252485   3.800 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.578           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.674           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.776           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.508           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.012           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.084           ms/op
