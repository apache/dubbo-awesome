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
# Warmup Iteration   1: 4.741 ops/ms
# Warmup Iteration   2: 9.432 ops/ms
# Warmup Iteration   3: 10.262 ops/ms
Iteration   1: 10.657 ops/ms
Iteration   2: 10.480 ops/ms
Iteration   3: 10.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.635 ±(99.9%) 2.659 ops/ms [Average]
  (min, avg, max) = (10.480, 10.635, 10.768), stdev = 0.146
  CI (99.9%): [7.977, 13.294] (assumes normal distribution)


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
# Warmup Iteration   1: 7.628 ops/ms
# Warmup Iteration   2: 11.136 ops/ms
# Warmup Iteration   3: 11.215 ops/ms
Iteration   1: 11.280 ops/ms
Iteration   2: 11.455 ops/ms
Iteration   3: 11.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.499 ±(99.9%) 4.445 ops/ms [Average]
  (min, avg, max) = (11.280, 11.499, 11.761), stdev = 0.244
  CI (99.9%): [7.054, 15.944] (assumes normal distribution)


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
# Warmup Iteration   1: 7.948 ops/ms
# Warmup Iteration   2: 10.377 ops/ms
# Warmup Iteration   3: 10.852 ops/ms
Iteration   1: 10.902 ops/ms
Iteration   2: 10.742 ops/ms
Iteration   3: 10.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.835 ±(99.9%) 1.524 ops/ms [Average]
  (min, avg, max) = (10.742, 10.835, 10.902), stdev = 0.084
  CI (99.9%): [9.311, 12.360] (assumes normal distribution)


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
# Warmup Iteration   1: 6.655 ops/ms
# Warmup Iteration   2: 8.047 ops/ms
# Warmup Iteration   3: 8.311 ops/ms
Iteration   1: 8.288 ops/ms
Iteration   2: 8.275 ops/ms
Iteration   3: 8.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.282 ±(99.9%) 0.129 ops/ms [Average]
  (min, avg, max) = (8.275, 8.282, 8.288), stdev = 0.007
  CI (99.9%): [8.153, 8.412] (assumes normal distribution)


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
# Warmup Iteration   1: 4.230 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.004 ms/op
Iteration   1: 3.007 ±(99.9%) 0.002 ms/op
Iteration   2: 2.955 ±(99.9%) 0.004 ms/op
Iteration   3: 2.997 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.987 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (2.955, 2.987, 3.007), stdev = 0.028
  CI (99.9%): [2.483, 3.490] (assumes normal distribution)


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
# Warmup Iteration   1: 3.600 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 2.972 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.854 ±(99.9%) 0.003 ms/op
Iteration   1: 2.790 ±(99.9%) 0.004 ms/op
Iteration   2: 2.829 ±(99.9%) 0.002 ms/op
Iteration   3: 2.728 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.782 ±(99.9%) 0.934 ms/op [Average]
  (min, avg, max) = (2.728, 2.782, 2.829), stdev = 0.051
  CI (99.9%): [1.849, 3.716] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.887 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.003 ms/op
Iteration   1: 2.958 ±(99.9%) 0.003 ms/op
Iteration   2: 2.963 ±(99.9%) 0.003 ms/op
Iteration   3: 2.967 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.962 ±(99.9%) 0.084 ms/op [Average]
  (min, avg, max) = (2.958, 2.962, 2.967), stdev = 0.005
  CI (99.9%): [2.878, 3.047] (assumes normal distribution)


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
# Warmup Iteration   1: 4.837 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.882 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.019 ms/op
Iteration   1: 3.821 ±(99.9%) 0.006 ms/op
Iteration   2: 3.833 ±(99.9%) 0.038 ms/op
Iteration   3: 3.795 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.816 ±(99.9%) 0.356 ms/op [Average]
  (min, avg, max) = (3.795, 3.816, 3.833), stdev = 0.020
  CI (99.9%): [3.460, 4.172] (assumes normal distribution)


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.007 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.622 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.766 ms/op
                 createUser·p0.9999: 12.170 ms/op
                 createUser·p1.00:   12.485 ms/op

Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.379 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  7.840 ms/op
                 createUser·p0.9999: 14.053 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.529 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  8.256 ms/op
                 createUser·p0.9999: 16.302 ms/op
                 createUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317634
  mean =      3.023 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2060 
    [ 1.250,  2.500) = 26210 
    [ 2.500,  3.750) = 265508 
    [ 3.750,  5.000) = 22070 
    [ 5.000,  6.250) = 878 
    [ 6.250,  7.500) = 481 
    [ 7.500,  8.750) = 166 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.379 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.900 ms/op
     p(99.9900) =     15.818 ms/op
     p(99.9990) =     16.463 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.967 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.867 ±(99.9%) 0.006 ms/op
Iteration   1: 2.823 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  6.873 ms/op
                 existUser·p0.9999: 15.226 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   2: 2.840 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.552 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  7.315 ms/op
                 existUser·p0.9999: 14.159 ms/op
                 existUser·p1.00:   15.598 ms/op

Iteration   3: 2.889 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.497 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  10.475 ms/op
                 existUser·p0.9999: 17.430 ms/op
                 existUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336839
  mean =      2.850 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3989 
    [ 1.250,  2.500) = 51959 
    [ 2.500,  3.750) = 268855 
    [ 3.750,  5.000) = 10342 
    [ 5.000,  6.250) = 944 
    [ 6.250,  7.500) = 441 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.324 ms/op
     p(99.9900) =     15.721 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 2.988 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  8.552 ms/op
                 getUser·p0.9999: 11.403 ms/op
                 getUser·p1.00:   11.583 ms/op

Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.574 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.585 ms/op
                 getUser·p0.9999: 19.244 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.848 ms/op
                 getUser·p0.9999: 15.519 ms/op
                 getUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322153
  mean =      2.979 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1586 
    [ 1.250,  2.500) = 25636 
    [ 2.500,  3.750) = 280358 
    [ 3.750,  5.000) = 12887 
    [ 5.000,  6.250) = 834 
    [ 6.250,  7.500) = 428 
    [ 7.500,  8.750) = 231 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.905 ms/op
     p(99.9900) =     18.248 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 4.764 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.010 ms/op
Iteration   1: 3.812 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.191 ms/op
                 listUser·p0.9999: 19.845 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   2: 3.739 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  14.315 ms/op
                 listUser·p0.9999: 16.843 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   3: 3.802 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.540 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 253802
  mean =      3.784 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5266 
    [ 2.500,  5.000) = 228241 
    [ 5.000,  7.500) = 18858 
    [ 7.500, 10.000) = 844 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 240 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     13.848 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     20.969 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.635 ± 2.659  ops/ms
ClientGrpc.existUser                       thrpt       3  11.499 ± 4.445  ops/ms
ClientGrpc.getUser                         thrpt       3  10.835 ± 1.524  ops/ms
ClientGrpc.listUser                        thrpt       3   8.282 ± 0.129  ops/ms
ClientGrpc.createUser                       avgt       3   2.987 ± 0.503   ms/op
ClientGrpc.existUser                        avgt       3   2.782 ± 0.934   ms/op
ClientGrpc.getUser                          avgt       3   2.962 ± 0.084   ms/op
ClientGrpc.listUser                         avgt       3   3.816 ± 0.356   ms/op
ClientGrpc.createUser                     sample  317634   3.023 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.379           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.900           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.818           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.826           ms/op
ClientGrpc.existUser                      sample  336839   2.850 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.497           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.324           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.721           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.727           ms/op
ClientGrpc.getUser                        sample  322153   2.979 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.574           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.905           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.248           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.628           ms/op
ClientGrpc.listUser                       sample  253802   3.784 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.926           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.637           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.848           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.514           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.692           ms/op
