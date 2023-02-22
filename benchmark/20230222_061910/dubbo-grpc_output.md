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
# Warmup Iteration   1: 5.053 ops/ms
# Warmup Iteration   2: 9.381 ops/ms
# Warmup Iteration   3: 10.561 ops/ms
Iteration   1: 10.431 ops/ms
Iteration   2: 10.420 ops/ms
Iteration   3: 10.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.430 ±(99.9%) 0.171 ops/ms [Average]
  (min, avg, max) = (10.420, 10.430, 10.439), stdev = 0.009
  CI (99.9%): [10.259, 10.601] (assumes normal distribution)


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
# Warmup Iteration   1: 8.729 ops/ms
# Warmup Iteration   2: 11.099 ops/ms
# Warmup Iteration   3: 10.804 ops/ms
Iteration   1: 10.945 ops/ms
Iteration   2: 10.829 ops/ms
Iteration   3: 10.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.823 ±(99.9%) 2.280 ops/ms [Average]
  (min, avg, max) = (10.695, 10.823, 10.945), stdev = 0.125
  CI (99.9%): [8.542, 13.103] (assumes normal distribution)


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
# Warmup Iteration   1: 7.911 ops/ms
# Warmup Iteration   2: 10.338 ops/ms
# Warmup Iteration   3: 10.495 ops/ms
Iteration   1: 10.428 ops/ms
Iteration   2: 10.559 ops/ms
Iteration   3: 10.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.497 ±(99.9%) 1.202 ops/ms [Average]
  (min, avg, max) = (10.428, 10.497, 10.559), stdev = 0.066
  CI (99.9%): [9.296, 11.699] (assumes normal distribution)


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
# Warmup Iteration   1: 6.438 ops/ms
# Warmup Iteration   2: 7.968 ops/ms
# Warmup Iteration   3: 7.928 ops/ms
Iteration   1: 7.948 ops/ms
Iteration   2: 8.001 ops/ms
Iteration   3: 8.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.070 ±(99.9%) 3.052 ops/ms [Average]
  (min, avg, max) = (7.948, 8.070, 8.260), stdev = 0.167
  CI (99.9%): [5.018, 11.122] (assumes normal distribution)


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
# Warmup Iteration   1: 3.966 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
Iteration   1: 2.991 ±(99.9%) 0.002 ms/op
Iteration   2: 3.066 ±(99.9%) 0.002 ms/op
Iteration   3: 3.108 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.055 ±(99.9%) 1.083 ms/op [Average]
  (min, avg, max) = (2.991, 3.055, 3.108), stdev = 0.059
  CI (99.9%): [1.972, 4.138] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.794 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.912 ±(99.9%) 0.003 ms/op
Iteration   1: 3.004 ±(99.9%) 0.002 ms/op
Iteration   2: 2.983 ±(99.9%) 0.002 ms/op
Iteration   3: 2.892 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.959 ±(99.9%) 1.086 ms/op [Average]
  (min, avg, max) = (2.892, 2.959, 3.004), stdev = 0.060
  CI (99.9%): [1.874, 4.045] (assumes normal distribution)


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
# Warmup Iteration   1: 3.735 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.003 ms/op
Iteration   1: 2.961 ±(99.9%) 0.003 ms/op
Iteration   2: 2.987 ±(99.9%) 0.002 ms/op
Iteration   3: 3.047 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.998 ±(99.9%) 0.800 ms/op [Average]
  (min, avg, max) = (2.961, 2.998, 3.047), stdev = 0.044
  CI (99.9%): [2.199, 3.798] (assumes normal distribution)


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
# Warmup Iteration   1: 4.204 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.035 ms/op
Iteration   1: 3.889 ±(99.9%) 0.032 ms/op
Iteration   2: 3.898 ±(99.9%) 0.031 ms/op
Iteration   3: 3.829 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.872 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (3.829, 3.872, 3.898), stdev = 0.037
  CI (99.9%): [3.194, 4.550] (assumes normal distribution)


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.007 ms/op
Iteration   1: 3.014 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.051 ms/op
                 createUser·p0.999:  7.109 ms/op
                 createUser·p0.9999: 20.460 ms/op
                 createUser·p1.00:   20.709 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.611 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  7.938 ms/op
                 createUser·p0.9999: 18.758 ms/op
                 createUser·p1.00:   19.857 ms/op

Iteration   3: 3.138 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.567 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  10.961 ms/op
                 createUser·p0.9999: 30.867 ms/op
                 createUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313600
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29602 
    [ 2.500,  5.000) = 283115 
    [ 5.000,  7.500) = 505 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      8.169 ms/op
     p(99.9900) =     26.944 ms/op
     p(99.9990) =     30.900 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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
# Warmup Iteration   1: 3.640 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.961 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.896 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  7.427 ms/op
                 existUser·p0.9999: 15.324 ms/op
                 existUser·p1.00:   15.499 ms/op

Iteration   2: 2.928 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.626 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  6.271 ms/op
                 existUser·p0.9999: 14.847 ms/op
                 existUser·p1.00:   15.368 ms/op

Iteration   3: 2.899 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.509 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  5.306 ms/op
                 existUser·p0.9999: 15.761 ms/op
                 existUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326528
  mean =      2.941 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1889 
    [ 1.250,  2.500) = 49535 
    [ 2.500,  3.750) = 256450 
    [ 3.750,  5.000) = 18011 
    [ 5.000,  6.250) = 281 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      6.648 ms/op
     p(99.9900) =     15.303 ms/op
     p(99.9990) =     16.027 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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
# Warmup Iteration   1: 3.947 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.006 ms/op
Iteration   1: 2.988 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.266 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  6.963 ms/op
                 getUser·p0.9999: 21.070 ms/op
                 getUser·p1.00:   21.332 ms/op

Iteration   2: 2.973 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.358 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.506 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  7.944 ms/op
                 getUser·p0.9999: 12.554 ms/op
                 getUser·p1.00:   12.780 ms/op

Iteration   3: 3.035 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.666 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  8.585 ms/op
                 getUser·p0.9999: 24.869 ms/op
                 getUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319949
  mean =      2.998 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27648 
    [ 2.500,  5.000) = 291254 
    [ 5.000,  7.500) = 716 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.266 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.586 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     25.153 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 4.838 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.012 ms/op
Iteration   1: 3.953 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  15.657 ms/op
                 listUser·p0.9999: 23.191 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   2: 3.962 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.793 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  15.073 ms/op
                 listUser·p0.9999: 26.603 ms/op
                 listUser·p1.00:   30.015 ms/op

Iteration   3: 3.896 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.566 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.434 ms/op
                 listUser·p0.9999: 20.953 ms/op
                 listUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243644
  mean =      3.937 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5889 
    [ 2.500,  5.000) = 212176 
    [ 5.000,  7.500) = 24633 
    [ 7.500, 10.000) = 588 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     15.341 ms/op
     p(99.9900) =     25.854 ms/op
     p(99.9990) =     29.846 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.430 ± 0.171  ops/ms
ClientGrpc.existUser                       thrpt       3  10.823 ± 2.280  ops/ms
ClientGrpc.getUser                         thrpt       3  10.497 ± 1.202  ops/ms
ClientGrpc.listUser                        thrpt       3   8.070 ± 3.052  ops/ms
ClientGrpc.createUser                       avgt       3   3.055 ± 1.083   ms/op
ClientGrpc.existUser                        avgt       3   2.959 ± 1.086   ms/op
ClientGrpc.getUser                          avgt       3   2.998 ± 0.800   ms/op
ClientGrpc.listUser                         avgt       3   3.872 ± 0.678   ms/op
ClientGrpc.createUser                     sample  313600   3.060 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.567           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.211           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.169           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.944           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.933           ms/op
ClientGrpc.existUser                      sample  326528   2.941 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.509           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.648           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.303           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.155           ms/op
ClientGrpc.getUser                        sample  319949   2.998 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.266           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.586           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.331           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.330           ms/op
ClientGrpc.listUser                       sample  243644   3.937 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.566           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.341           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.854           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.015           ms/op
