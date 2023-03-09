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
# Warmup Iteration   1: 4.607 ops/ms
# Warmup Iteration   2: 9.529 ops/ms
# Warmup Iteration   3: 10.220 ops/ms
Iteration   1: 10.583 ops/ms
Iteration   2: 10.482 ops/ms
Iteration   3: 10.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.686 ±(99.9%) 4.927 ops/ms [Average]
  (min, avg, max) = (10.482, 10.686, 10.992), stdev = 0.270
  CI (99.9%): [5.759, 15.613] (assumes normal distribution)


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
# Warmup Iteration   1: 8.047 ops/ms
# Warmup Iteration   2: 10.862 ops/ms
# Warmup Iteration   3: 11.382 ops/ms
Iteration   1: 11.027 ops/ms
Iteration   2: 11.507 ops/ms
Iteration   3: 11.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.209 ±(99.9%) 4.744 ops/ms [Average]
  (min, avg, max) = (11.027, 11.209, 11.507), stdev = 0.260
  CI (99.9%): [6.465, 15.954] (assumes normal distribution)


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
# Warmup Iteration   1: 7.539 ops/ms
# Warmup Iteration   2: 10.497 ops/ms
# Warmup Iteration   3: 10.826 ops/ms
Iteration   1: 11.034 ops/ms
Iteration   2: 11.004 ops/ms
Iteration   3: 10.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.977 ±(99.9%) 1.369 ops/ms [Average]
  (min, avg, max) = (10.892, 10.977, 11.034), stdev = 0.075
  CI (99.9%): [9.607, 12.346] (assumes normal distribution)


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
# Warmup Iteration   1: 7.126 ops/ms
# Warmup Iteration   2: 7.751 ops/ms
# Warmup Iteration   3: 8.240 ops/ms
Iteration   1: 8.256 ops/ms
Iteration   2: 8.299 ops/ms
Iteration   3: 8.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.323 ±(99.9%) 1.474 ops/ms [Average]
  (min, avg, max) = (8.256, 8.323, 8.413), stdev = 0.081
  CI (99.9%): [6.849, 9.797] (assumes normal distribution)


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.003 ms/op
Iteration   1: 2.968 ±(99.9%) 0.003 ms/op
Iteration   2: 2.983 ±(99.9%) 0.003 ms/op
Iteration   3: 2.890 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.947 ±(99.9%) 0.910 ms/op [Average]
  (min, avg, max) = (2.890, 2.947, 2.983), stdev = 0.050
  CI (99.9%): [2.037, 3.856] (assumes normal distribution)


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
# Warmup Iteration   1: 3.875 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.901 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.840 ±(99.9%) 0.004 ms/op
Iteration   1: 2.854 ±(99.9%) 0.003 ms/op
Iteration   2: 2.873 ±(99.9%) 0.002 ms/op
Iteration   3: 2.875 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.867 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (2.854, 2.867, 2.875), stdev = 0.012
  CI (99.9%): [2.653, 3.081] (assumes normal distribution)


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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.003 ms/op
Iteration   1: 2.923 ±(99.9%) 0.003 ms/op
Iteration   2: 2.993 ±(99.9%) 0.002 ms/op
Iteration   3: 2.979 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.965 ±(99.9%) 0.670 ms/op [Average]
  (min, avg, max) = (2.923, 2.965, 2.993), stdev = 0.037
  CI (99.9%): [2.295, 3.635] (assumes normal distribution)


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
# Warmup Iteration   1: 5.330 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.016 ms/op
Iteration   1: 3.858 ±(99.9%) 0.019 ms/op
Iteration   2: 3.857 ±(99.9%) 0.027 ms/op
Iteration   3: 3.828 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.848 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (3.828, 3.848, 3.858), stdev = 0.017
  CI (99.9%): [3.543, 4.152] (assumes normal distribution)


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
# Warmup Iteration   1: 3.949 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
Iteration   1: 2.998 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.618 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  7.602 ms/op
                 createUser·p0.9999: 11.288 ms/op
                 createUser·p1.00:   11.764 ms/op

Iteration   2: 2.990 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.536 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  10.879 ms/op
                 createUser·p0.9999: 19.399 ms/op
                 createUser·p1.00:   19.628 ms/op

Iteration   3: 2.961 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  11.649 ms/op
                 createUser·p0.9999: 24.707 ms/op
                 createUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322065
  mean =      2.983 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30495 
    [ 2.500,  5.000) = 290362 
    [ 5.000,  7.500) = 770 
    [ 7.500, 10.000) = 118 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      9.811 ms/op
     p(99.9900) =     23.242 ms/op
     p(99.9990) =     24.896 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 3.631 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.880 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.859 ±(99.9%) 0.006 ms/op
Iteration   1: 2.891 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.889 ms/op
                 existUser·p0.9999: 11.943 ms/op
                 existUser·p1.00:   12.485 ms/op

Iteration   2: 2.836 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.006 ms/op
                 existUser·p0.9999: 13.222 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   3: 2.824 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.480 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  5.734 ms/op
                 existUser·p0.9999: 18.655 ms/op
                 existUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336913
  mean =      2.850 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57816 
    [ 2.500,  5.000) = 278272 
    [ 5.000,  7.500) = 580 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.480 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.628 ms/op
     p(99.9900) =     13.581 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.005 ms/op
Iteration   1: 2.962 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.258 ms/op
                 getUser·p0.9999: 14.585 ms/op
                 getUser·p1.00:   14.828 ms/op

Iteration   2: 2.948 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  6.525 ms/op
                 getUser·p0.9999: 13.063 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   3: 2.944 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.370 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.044 ms/op
                 getUser·p0.9999: 17.769 ms/op
                 getUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325362
  mean =      2.951 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1344 
    [ 1.250,  2.500) = 27422 
    [ 2.500,  3.750) = 283389 
    [ 3.750,  5.000) = 12417 
    [ 5.000,  6.250) = 436 
    [ 6.250,  7.500) = 102 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.370 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.488 ms/op
     p(99.9900) =     15.661 ms/op
     p(99.9990) =     18.137 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 5.027 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.930 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.010 ms/op
Iteration   1: 3.843 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.532 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  12.412 ms/op
                 listUser·p0.9999: 20.622 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 3.868 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.450 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  14.597 ms/op
                 listUser·p0.9999: 21.937 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   3: 3.851 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  16.743 ms/op
                 listUser·p0.9999: 23.319 ms/op
                 listUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249157
  mean =      3.854 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4229 
    [ 2.500,  5.000) = 227986 
    [ 5.000,  7.500) = 15835 
    [ 7.500, 10.000) = 615 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     21.409 ms/op
     p(99.9990) =     23.937 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.686 ± 4.927  ops/ms
ClientGrpc.existUser                       thrpt       3  11.209 ± 4.744  ops/ms
ClientGrpc.getUser                         thrpt       3  10.977 ± 1.369  ops/ms
ClientGrpc.listUser                        thrpt       3   8.323 ± 1.474  ops/ms
ClientGrpc.createUser                       avgt       3   2.947 ± 0.910   ms/op
ClientGrpc.existUser                        avgt       3   2.867 ± 0.214   ms/op
ClientGrpc.getUser                          avgt       3   2.965 ± 0.670   ms/op
ClientGrpc.listUser                         avgt       3   3.848 ± 0.305   ms/op
ClientGrpc.createUser                     sample  322065   2.983 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.536           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.811           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.242           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.969           ms/op
ClientGrpc.existUser                      sample  336913   2.850 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.480           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.830           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.628           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.581           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.251           ms/op
ClientGrpc.getUser                        sample  325362   2.951 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.370           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.937           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.445           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.488           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.661           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.285           ms/op
ClientGrpc.listUser                       sample  249157   3.854 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.137           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.736           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.465           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.562           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.860           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.409           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.019           ms/op
