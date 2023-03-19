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
# Warmup Iteration   1: 2.701 ops/ms
# Warmup Iteration   2: 6.492 ops/ms
# Warmup Iteration   3: 7.356 ops/ms
Iteration   1: 7.791 ops/ms
Iteration   2: 8.039 ops/ms
Iteration   3: 7.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.853 ±(99.9%) 2.984 ops/ms [Average]
  (min, avg, max) = (7.730, 7.853, 8.039), stdev = 0.164
  CI (99.9%): [4.869, 10.837] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.823 ops/ms
# Warmup Iteration   2: 8.192 ops/ms
# Warmup Iteration   3: 8.582 ops/ms
Iteration   1: 8.808 ops/ms
Iteration   2: 8.986 ops/ms
Iteration   3: 8.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.881 ±(99.9%) 1.701 ops/ms [Average]
  (min, avg, max) = (8.808, 8.881, 8.986), stdev = 0.093
  CI (99.9%): [7.180, 10.582] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.141 ops/ms
# Warmup Iteration   2: 7.064 ops/ms
# Warmup Iteration   3: 7.828 ops/ms
Iteration   1: 7.849 ops/ms
Iteration   2: 7.829 ops/ms
Iteration   3: 7.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.846 ±(99.9%) 0.304 ops/ms [Average]
  (min, avg, max) = (7.829, 7.846, 7.861), stdev = 0.017
  CI (99.9%): [7.543, 8.150] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.130 ops/ms
# Warmup Iteration   2: 5.756 ops/ms
# Warmup Iteration   3: 6.171 ops/ms
Iteration   1: 5.945 ops/ms
Iteration   2: 5.979 ops/ms
Iteration   3: 6.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.981 ±(99.9%) 0.685 ops/ms [Average]
  (min, avg, max) = (5.945, 5.981, 6.020), stdev = 0.038
  CI (99.9%): [5.296, 6.667] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.047 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.282 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.008 ms/op
Iteration   1: 4.131 ±(99.9%) 0.003 ms/op
Iteration   2: 4.034 ±(99.9%) 0.003 ms/op
Iteration   3: 4.083 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.083 ±(99.9%) 0.885 ms/op [Average]
  (min, avg, max) = (4.034, 4.083, 4.131), stdev = 0.049
  CI (99.9%): [3.198, 4.968] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.603 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.707 ±(99.9%) 0.004 ms/op
Iteration   1: 3.779 ±(99.9%) 0.002 ms/op
Iteration   2: 3.703 ±(99.9%) 0.003 ms/op
Iteration   3: 3.778 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.753 ±(99.9%) 0.790 ms/op [Average]
  (min, avg, max) = (3.703, 3.753, 3.779), stdev = 0.043
  CI (99.9%): [2.963, 4.543] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 6.255 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.325 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.002 ms/op
Iteration   1: 4.202 ±(99.9%) 0.018 ms/op
Iteration   2: 4.004 ±(99.9%) 0.006 ms/op
Iteration   3: 4.069 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.092 ±(99.9%) 1.842 ms/op [Average]
  (min, avg, max) = (4.004, 4.092, 4.202), stdev = 0.101
  CI (99.9%): [2.250, 5.934] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.977 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.899 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.518 ±(99.9%) 0.021 ms/op
Iteration   1: 5.186 ±(99.9%) 0.008 ms/op
Iteration   2: 5.289 ±(99.9%) 0.010 ms/op
Iteration   3: 5.370 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.281 ±(99.9%) 1.686 ms/op [Average]
  (min, avg, max) = (5.186, 5.281, 5.370), stdev = 0.092
  CI (99.9%): [3.596, 6.967] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.333 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.423 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.011 ms/op
Iteration   1: 4.109 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   4.018 ms/op
                 createUser·p0.90:   5.087 ms/op
                 createUser·p0.95:   5.489 ms/op
                 createUser·p0.99:   6.579 ms/op
                 createUser·p0.999:  10.801 ms/op
                 createUser·p0.9999: 17.093 ms/op
                 createUser·p1.00:   18.252 ms/op

Iteration   2: 3.876 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  9.781 ms/op
                 createUser·p0.9999: 22.692 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   3: 4.150 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   4.030 ms/op
                 createUser·p0.90:   5.112 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   6.849 ms/op
                 createUser·p0.999:  18.122 ms/op
                 createUser·p0.9999: 28.803 ms/op
                 createUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 237370
  mean =      4.041 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5560 
    [ 2.500,  5.000) = 207624 
    [ 5.000,  7.500) = 22911 
    [ 7.500, 10.000) = 845 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     12.335 ms/op
     p(99.9900) =     28.410 ms/op
     p(99.9990) =     29.041 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 5.645 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.009 ms/op
Iteration   1: 3.654 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  9.052 ms/op
                 existUser·p0.9999: 18.047 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   2: 4.137 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   3.908 ms/op
                 existUser·p0.90:   5.341 ms/op
                 existUser·p0.95:   6.242 ms/op
                 existUser·p0.99:   8.765 ms/op
                 existUser·p0.999:  13.638 ms/op
                 existUser·p0.9999: 20.063 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   3: 3.753 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  13.901 ms/op
                 existUser·p0.9999: 30.769 ms/op
                 existUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 250005
  mean =      3.837 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11006 
    [ 2.500,  5.000) = 220552 
    [ 5.000,  7.500) = 16348 
    [ 7.500, 10.000) = 1595 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     12.075 ms/op
     p(99.9900) =     28.574 ms/op
     p(99.9990) =     31.113 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.841 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.277 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.011 ms/op
Iteration   1: 4.123 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   4.051 ms/op
                 getUser·p0.90:   5.054 ms/op
                 getUser·p0.95:   5.399 ms/op
                 getUser·p0.99:   6.444 ms/op
                 getUser·p0.999:  9.346 ms/op
                 getUser·p0.9999: 16.011 ms/op
                 getUser·p1.00:   16.204 ms/op

Iteration   2: 4.085 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   5.071 ms/op
                 getUser·p0.95:   5.423 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  10.777 ms/op
                 getUser·p0.9999: 18.427 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   3: 3.910 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.833 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  13.568 ms/op
                 getUser·p0.9999: 26.798 ms/op
                 getUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 237647
  mean =      4.037 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5622 
    [ 2.500,  5.000) = 208282 
    [ 5.000,  7.500) = 22666 
    [ 7.500, 10.000) = 777 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     11.163 ms/op
     p(99.9900) =     24.936 ms/op
     p(99.9990) =     27.287 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 7.212 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.913 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.366 ±(99.9%) 0.018 ms/op
Iteration   1: 5.283 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   5.120 ms/op
                 listUser·p0.90:   6.218 ms/op
                 listUser·p0.95:   7.234 ms/op
                 listUser·p0.99:   9.465 ms/op
                 listUser·p0.999:  16.179 ms/op
                 listUser·p0.9999: 24.281 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   2: 5.341 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.679 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   6.652 ms/op
                 listUser·p0.95:   7.660 ms/op
                 listUser·p0.99:   10.289 ms/op
                 listUser·p0.999:  15.237 ms/op
                 listUser·p0.9999: 19.662 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   3: 5.257 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   5.063 ms/op
                 listUser·p0.90:   6.472 ms/op
                 listUser·p0.95:   7.504 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  17.623 ms/op
                 listUser·p0.9999: 20.472 ms/op
                 listUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 181214
  mean =      5.294 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 103 
    [ 2.500,  5.000) = 80292 
    [ 5.000,  7.500) = 91906 
    [ 7.500, 10.000) = 7349 
    [10.000, 12.500) = 1109 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.455 ms/op
     p(95.0000) =      7.471 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     16.531 ms/op
     p(99.9900) =     22.631 ms/op
     p(99.9990) =     24.719 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.853 ± 2.984  ops/ms
ClientGrpc.existUser                       thrpt       3   8.881 ± 1.701  ops/ms
ClientGrpc.getUser                         thrpt       3   7.846 ± 0.304  ops/ms
ClientGrpc.listUser                        thrpt       3   5.981 ± 0.685  ops/ms
ClientGrpc.createUser                       avgt       3   4.083 ± 0.885   ms/op
ClientGrpc.existUser                        avgt       3   3.753 ± 0.790   ms/op
ClientGrpc.getUser                          avgt       3   4.092 ± 1.842   ms/op
ClientGrpc.listUser                         avgt       3   5.281 ± 1.686   ms/op
ClientGrpc.createUser                     sample  237370   4.041 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.877           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.014           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.366           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.472           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.335           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.410           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.131           ms/op
ClientGrpc.existUser                      sample  250005   3.837 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.865           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.784           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.292           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.225           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.075           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.574           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.326           ms/op
ClientGrpc.getUser                        sample  237647   4.037 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.558           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.997           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.358           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.463           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.163           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.936           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.460           ms/op
ClientGrpc.listUser                       sample  181214   5.294 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.190           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.455           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.471           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.781           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.531           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.631           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.773           ms/op
