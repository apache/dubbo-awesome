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
# Warmup Iteration   1: 2.115 ops/ms
# Warmup Iteration   2: 5.072 ops/ms
# Warmup Iteration   3: 7.061 ops/ms
Iteration   1: 7.457 ops/ms
Iteration   2: 7.625 ops/ms
Iteration   3: 7.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.507 ±(99.9%) 1.866 ops/ms [Average]
  (min, avg, max) = (7.439, 7.507, 7.625), stdev = 0.102
  CI (99.9%): [5.641, 9.373] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.795 ops/ms
# Warmup Iteration   2: 7.444 ops/ms
# Warmup Iteration   3: 7.985 ops/ms
Iteration   1: 8.228 ops/ms
Iteration   2: 8.289 ops/ms
Iteration   3: 8.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.175 ±(99.9%) 2.693 ops/ms [Average]
  (min, avg, max) = (8.009, 8.175, 8.289), stdev = 0.148
  CI (99.9%): [5.483, 10.868] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.444 ops/ms
# Warmup Iteration   2: 7.149 ops/ms
# Warmup Iteration   3: 7.415 ops/ms
Iteration   1: 7.375 ops/ms
Iteration   2: 7.233 ops/ms
Iteration   3: 7.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.384 ±(99.9%) 2.830 ops/ms [Average]
  (min, avg, max) = (7.233, 7.384, 7.543), stdev = 0.155
  CI (99.9%): [4.553, 10.214] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.552 ops/ms
# Warmup Iteration   2: 5.118 ops/ms
# Warmup Iteration   3: 5.745 ops/ms
Iteration   1: 6.216 ops/ms
Iteration   2: 6.162 ops/ms
Iteration   3: 5.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.120 ±(99.9%) 2.240 ops/ms [Average]
  (min, avg, max) = (5.982, 6.120, 6.216), stdev = 0.123
  CI (99.9%): [3.880, 8.360] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.580 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.369 ±(99.9%) 0.010 ms/op
Iteration   1: 4.280 ±(99.9%) 0.005 ms/op
Iteration   2: 4.175 ±(99.9%) 0.004 ms/op
Iteration   3: 4.227 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.227 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (4.175, 4.227, 4.280), stdev = 0.052
  CI (99.9%): [3.274, 5.181] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.167 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.549 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.003 ms/op
Iteration   1: 4.021 ±(99.9%) 0.004 ms/op
Iteration   2: 4.028 ±(99.9%) 0.003 ms/op
Iteration   3: 3.974 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.008 ±(99.9%) 0.532 ms/op [Average]
  (min, avg, max) = (3.974, 4.008, 4.028), stdev = 0.029
  CI (99.9%): [3.476, 4.539] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.121 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.586 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.549 ±(99.9%) 0.005 ms/op
Iteration   1: 4.270 ±(99.9%) 0.004 ms/op
Iteration   2: 4.337 ±(99.9%) 0.004 ms/op
Iteration   3: 4.157 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.255 ±(99.9%) 1.656 ms/op [Average]
  (min, avg, max) = (4.157, 4.255, 4.337), stdev = 0.091
  CI (99.9%): [2.599, 5.911] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.425 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 6.046 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.604 ±(99.9%) 0.013 ms/op
Iteration   1: 5.585 ±(99.9%) 0.015 ms/op
Iteration   2: 5.209 ±(99.9%) 0.014 ms/op
Iteration   3: 5.283 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.359 ±(99.9%) 3.634 ms/op [Average]
  (min, avg, max) = (5.209, 5.359, 5.585), stdev = 0.199
  CI (99.9%): [1.725, 8.992] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.805 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.540 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.414 ±(99.9%) 0.016 ms/op
Iteration   1: 4.426 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.734 ms/op
                 createUser·p0.95:   6.398 ms/op
                 createUser·p0.99:   8.536 ms/op
                 createUser·p0.999:  12.202 ms/op
                 createUser·p0.9999: 25.355 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   2: 4.360 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   4.162 ms/op
                 createUser·p0.90:   5.620 ms/op
                 createUser·p0.95:   6.291 ms/op
                 createUser·p0.99:   9.175 ms/op
                 createUser·p0.999:  15.942 ms/op
                 createUser·p0.9999: 28.442 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   3: 4.335 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.565 ms/op
                 createUser·p0.50:   4.125 ms/op
                 createUser·p0.90:   5.579 ms/op
                 createUser·p0.95:   6.275 ms/op
                 createUser·p0.99:   8.716 ms/op
                 createUser·p0.999:  14.469 ms/op
                 createUser·p0.9999: 30.842 ms/op
                 createUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219492
  mean =      4.373 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5041 
    [ 2.500,  5.000) = 168131 
    [ 5.000,  7.500) = 41734 
    [ 7.500, 10.000) = 3504 
    [10.000, 12.500) = 750 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      4.170 ms/op
     p(90.0000) =      5.644 ms/op
     p(95.0000) =      6.332 ms/op
     p(99.0000) =      8.782 ms/op
     p(99.9000) =     14.164 ms/op
     p(99.9900) =     30.117 ms/op
     p(99.9990) =     31.235 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.870 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.547 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.012 ms/op
Iteration   1: 3.947 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.932 ms/op
                 existUser·p0.95:   5.374 ms/op
                 existUser·p0.99:   7.012 ms/op
                 existUser·p0.999:  11.698 ms/op
                 existUser·p0.9999: 25.130 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   2: 3.892 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.899 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   6.980 ms/op
                 existUser·p0.999:  9.798 ms/op
                 existUser·p0.9999: 20.080 ms/op
                 existUser·p1.00:   21.037 ms/op

Iteration   3: 3.850 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   5.030 ms/op
                 existUser·p0.99:   7.510 ms/op
                 existUser·p0.999:  14.139 ms/op
                 existUser·p0.9999: 21.846 ms/op
                 existUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 246284
  mean =      3.896 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7422 
    [ 2.500,  5.000) = 220215 
    [ 5.000,  7.500) = 16544 
    [ 7.500, 10.000) = 1638 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     12.464 ms/op
     p(99.9900) =     24.392 ms/op
     p(99.9990) =     25.728 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.188 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.693 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.280 ±(99.9%) 0.014 ms/op
Iteration   1: 4.000 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  11.682 ms/op
                 getUser·p0.9999: 34.669 ms/op
                 getUser·p1.00:   34.931 ms/op

Iteration   2: 4.066 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   5.030 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   6.969 ms/op
                 getUser·p0.999:  12.428 ms/op
                 getUser·p0.9999: 24.978 ms/op
                 getUser·p1.00:   25.854 ms/op

Iteration   3: 4.244 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.456 ms/op
                 getUser·p0.95:   6.160 ms/op
                 getUser·p0.99:   8.765 ms/op
                 getUser·p0.999:  14.117 ms/op
                 getUser·p0.9999: 23.495 ms/op
                 getUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 234024
  mean =      4.101 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7745 
    [ 2.500,  5.000) = 199082 
    [ 5.000,  7.500) = 24611 
    [ 7.500, 10.000) = 1959 
    [10.000, 12.500) = 317 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     13.566 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.978 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 5.797 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.402 ±(99.9%) 0.019 ms/op
Iteration   1: 5.251 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   4.973 ms/op
                 listUser·p0.90:   6.963 ms/op
                 listUser·p0.95:   7.799 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  17.831 ms/op
                 listUser·p0.9999: 24.665 ms/op
                 listUser·p1.00:   27.623 ms/op

Iteration   2: 5.400 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.513 ms/op
                 listUser·p0.50:   5.063 ms/op
                 listUser·p0.90:   7.307 ms/op
                 listUser·p0.95:   8.192 ms/op
                 listUser·p0.99:   10.813 ms/op
                 listUser·p0.999:  16.252 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   3: 5.327 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   5.038 ms/op
                 listUser·p0.90:   6.974 ms/op
                 listUser·p0.95:   7.815 ms/op
                 listUser·p0.99:   10.224 ms/op
                 listUser·p0.999:  22.573 ms/op
                 listUser·p0.9999: 34.340 ms/op
                 listUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180348
  mean =      5.325 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 181 
    [ 2.500,  5.000) = 88320 
    [ 5.000,  7.500) = 78951 
    [ 7.500, 10.000) = 10842 
    [10.000, 12.500) = 1451 
    [12.500, 15.000) = 307 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      5.022 ms/op
     p(90.0000) =      7.078 ms/op
     p(95.0000) =      7.946 ms/op
     p(99.0000) =     10.224 ms/op
     p(99.9000) =     17.978 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     35.337 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.507 ± 1.866  ops/ms
ClientGrpc.existUser                       thrpt       3   8.175 ± 2.693  ops/ms
ClientGrpc.getUser                         thrpt       3   7.384 ± 2.830  ops/ms
ClientGrpc.listUser                        thrpt       3   6.120 ± 2.240  ops/ms
ClientGrpc.createUser                       avgt       3   4.227 ± 0.954   ms/op
ClientGrpc.existUser                        avgt       3   4.008 ± 0.532   ms/op
ClientGrpc.getUser                          avgt       3   4.255 ± 1.656   ms/op
ClientGrpc.listUser                         avgt       3   5.359 ± 3.634   ms/op
ClientGrpc.createUser                     sample  219492   4.373 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.565           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.170           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.644           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.332           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.782           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.164           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.117           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.326           ms/op
ClientGrpc.existUser                      sample  246284   3.896 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.725           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.817           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.292           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.160           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.464           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.392           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.854           ms/op
ClientGrpc.getUser                        sample  234024   4.101 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.864           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.981           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.112           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.652           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.692           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.566           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.948           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.931           ms/op
ClientGrpc.listUser                       sample  180348   5.325 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.087           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.946           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.224           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.978           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.144           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.339           ms/op
