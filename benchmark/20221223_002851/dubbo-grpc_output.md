# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.780 ops/ms
# Warmup Iteration   2: 9.432 ops/ms
# Warmup Iteration   3: 10.450 ops/ms
Iteration   1: 10.571 ops/ms
Iteration   2: 10.366 ops/ms
Iteration   3: 10.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.420 ±(99.9%) 2.412 ops/ms [Average]
  (min, avg, max) = (10.323, 10.420, 10.571), stdev = 0.132
  CI (99.9%): [8.008, 12.832] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.935 ops/ms
# Warmup Iteration   2: 10.854 ops/ms
# Warmup Iteration   3: 10.960 ops/ms
Iteration   1: 11.271 ops/ms
Iteration   2: 11.074 ops/ms
Iteration   3: 11.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.195 ±(99.9%) 1.939 ops/ms [Average]
  (min, avg, max) = (11.074, 11.195, 11.271), stdev = 0.106
  CI (99.9%): [9.256, 13.134] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.222 ops/ms
# Warmup Iteration   2: 10.316 ops/ms
# Warmup Iteration   3: 10.426 ops/ms
Iteration   1: 10.416 ops/ms
Iteration   2: 10.342 ops/ms
Iteration   3: 10.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.361 ±(99.9%) 0.875 ops/ms [Average]
  (min, avg, max) = (10.326, 10.361, 10.416), stdev = 0.048
  CI (99.9%): [9.486, 11.236] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.863 ops/ms
# Warmup Iteration   2: 7.876 ops/ms
# Warmup Iteration   3: 7.824 ops/ms
Iteration   1: 7.973 ops/ms
Iteration   2: 8.036 ops/ms
Iteration   3: 7.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.941 ±(99.9%) 2.085 ops/ms [Average]
  (min, avg, max) = (7.814, 7.941, 8.036), stdev = 0.114
  CI (99.9%): [5.856, 10.025] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.036 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.002 ms/op
Iteration   2: 3.148 ±(99.9%) 0.006 ms/op
Iteration   3: 2.954 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.043 ±(99.9%) 1.783 ms/op [Average]
  (min, avg, max) = (2.954, 3.043, 3.148), stdev = 0.098
  CI (99.9%): [1.260, 4.827] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.555 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 2.950 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.004 ms/op
Iteration   1: 2.929 ±(99.9%) 0.002 ms/op
Iteration   2: 2.837 ±(99.9%) 0.004 ms/op
Iteration   3: 2.871 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.879 ±(99.9%) 0.849 ms/op [Average]
  (min, avg, max) = (2.837, 2.879, 2.929), stdev = 0.047
  CI (99.9%): [2.029, 3.728] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.843 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.002 ms/op
Iteration   1: 3.046 ±(99.9%) 0.003 ms/op
Iteration   2: 3.017 ±(99.9%) 0.003 ms/op
Iteration   3: 3.078 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.047 ±(99.9%) 0.565 ms/op [Average]
  (min, avg, max) = (3.017, 3.047, 3.078), stdev = 0.031
  CI (99.9%): [2.482, 3.612] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.667 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.045 ms/op
Iteration   1: 4.026 ±(99.9%) 0.013 ms/op
Iteration   2: 4.089 ±(99.9%) 0.014 ms/op
Iteration   3: 3.884 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.999 ±(99.9%) 1.919 ms/op [Average]
  (min, avg, max) = (3.884, 3.999, 4.089), stdev = 0.105
  CI (99.9%): [2.081, 5.918] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.997 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
Iteration   1: 3.090 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.492 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  8.843 ms/op
                 createUser·p0.9999: 11.354 ms/op
                 createUser·p1.00:   11.895 ms/op

Iteration   2: 3.029 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.112 ms/op
                 createUser·p0.999:  5.857 ms/op
                 createUser·p0.9999: 12.834 ms/op
                 createUser·p1.00:   13.107 ms/op

Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.701 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  13.033 ms/op
                 createUser·p0.9999: 17.170 ms/op
                 createUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315052
  mean =      3.048 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1099 
    [ 1.250,  2.500) = 26562 
    [ 2.500,  3.750) = 266817 
    [ 3.750,  5.000) = 19606 
    [ 5.000,  6.250) = 421 
    [ 6.250,  7.500) = 174 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     15.843 ms/op
     p(99.9990) =     17.203 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.185 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.006 ms/op
Iteration   1: 2.914 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  5.898 ms/op
                 existUser·p0.9999: 14.565 ms/op
                 existUser·p1.00:   14.844 ms/op

Iteration   2: 2.907 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.499 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  6.692 ms/op
                 existUser·p0.9999: 19.529 ms/op
                 existUser·p1.00:   20.021 ms/op

Iteration   3: 2.838 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  5.739 ms/op
                 existUser·p0.9999: 13.631 ms/op
                 existUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332568
  mean =      2.886 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57005 
    [ 2.500,  5.000) = 274915 
    [ 5.000,  7.500) = 424 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.000 ms/op
     p(99.9900) =     14.840 ms/op
     p(99.9990) =     19.912 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.773 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.277 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.167 ms/op
                 getUser·p0.9999: 17.726 ms/op
                 getUser·p1.00:   18.055 ms/op

Iteration   2: 3.045 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  5.833 ms/op
                 getUser·p0.9999: 12.608 ms/op
                 getUser·p1.00:   12.780 ms/op

Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.244 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.877 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  5.980 ms/op
                 getUser·p0.9999: 18.383 ms/op
                 getUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314987
  mean =      3.046 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1975 
    [ 1.250,  2.500) = 21301 
    [ 2.500,  3.750) = 271453 
    [ 3.750,  5.000) = 19540 
    [ 5.000,  6.250) = 428 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.244 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.111 ms/op
     p(99.9900) =     17.777 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.247 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.199 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.011 ms/op
Iteration   1: 3.959 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.044 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  12.229 ms/op
                 listUser·p0.9999: 17.583 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   2: 4.007 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.526 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.782 ms/op
                 listUser·p0.999:  20.090 ms/op
                 listUser·p0.9999: 24.380 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   3: 3.894 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.382 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  15.608 ms/op
                 listUser·p0.9999: 22.177 ms/op
                 listUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242825
  mean =      3.953 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4108 
    [ 2.500,  5.000) = 213451 
    [ 5.000,  7.500) = 24232 
    [ 7.500, 10.000) = 580 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     15.251 ms/op
     p(99.9900) =     23.715 ms/op
     p(99.9990) =     24.515 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.420 ± 2.412  ops/ms
ClientGrpc.existUser                       thrpt       3  11.195 ± 1.939  ops/ms
ClientGrpc.getUser                         thrpt       3  10.361 ± 0.875  ops/ms
ClientGrpc.listUser                        thrpt       3   7.941 ± 2.085  ops/ms
ClientGrpc.createUser                       avgt       3   3.043 ± 1.783   ms/op
ClientGrpc.existUser                        avgt       3   2.879 ± 0.849   ms/op
ClientGrpc.getUser                          avgt       3   3.047 ± 0.565   ms/op
ClientGrpc.listUser                         avgt       3   3.999 ± 1.919   ms/op
ClientGrpc.createUser                     sample  315052   3.048 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.492           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.503           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.843           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.842           ms/op
ClientGrpc.existUser                      sample  332568   2.886 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.499           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.000           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.840           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.021           ms/op
ClientGrpc.getUser                        sample  314987   3.046 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.244           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.111           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.777           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.579           ms/op
ClientGrpc.listUser                       sample  242825   3.953 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.526           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.251           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.715           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.576           ms/op
