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
# Warmup Iteration   1: 2.369 ops/ms
# Warmup Iteration   2: 5.938 ops/ms
# Warmup Iteration   3: 7.723 ops/ms
Iteration   1: 7.556 ops/ms
Iteration   2: 7.635 ops/ms
Iteration   3: 7.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.650 ±(99.9%) 1.875 ops/ms [Average]
  (min, avg, max) = (7.556, 7.650, 7.760), stdev = 0.103
  CI (99.9%): [5.775, 9.525] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.040 ops/ms
# Warmup Iteration   2: 7.667 ops/ms
# Warmup Iteration   3: 7.908 ops/ms
Iteration   1: 7.915 ops/ms
Iteration   2: 7.898 ops/ms
Iteration   3: 8.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.967 ±(99.9%) 1.908 ops/ms [Average]
  (min, avg, max) = (7.898, 7.967, 8.087), stdev = 0.105
  CI (99.9%): [6.059, 9.874] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.704 ops/ms
# Warmup Iteration   2: 7.113 ops/ms
# Warmup Iteration   3: 7.396 ops/ms
Iteration   1: 7.395 ops/ms
Iteration   2: 7.587 ops/ms
Iteration   3: 7.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.520 ±(99.9%) 1.980 ops/ms [Average]
  (min, avg, max) = (7.395, 7.520, 7.587), stdev = 0.109
  CI (99.9%): [5.540, 9.500] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.230 ops/ms
# Warmup Iteration   2: 5.741 ops/ms
# Warmup Iteration   3: 6.078 ops/ms
Iteration   1: 6.206 ops/ms
Iteration   2: 6.061 ops/ms
Iteration   3: 6.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.169 ±(99.9%) 1.741 ops/ms [Average]
  (min, avg, max) = (6.061, 6.169, 6.241), stdev = 0.095
  CI (99.9%): [4.427, 7.910] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.211 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.534 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.397 ±(99.9%) 0.008 ms/op
Iteration   1: 4.428 ±(99.9%) 0.003 ms/op
Iteration   2: 4.428 ±(99.9%) 0.002 ms/op
Iteration   3: 4.340 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.399 ±(99.9%) 0.924 ms/op [Average]
  (min, avg, max) = (4.340, 4.399, 4.428), stdev = 0.051
  CI (99.9%): [3.475, 5.323] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.372 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.003 ms/op
Iteration   1: 3.995 ±(99.9%) 0.004 ms/op
Iteration   2: 4.139 ±(99.9%) 0.003 ms/op
Iteration   3: 3.894 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.009 ±(99.9%) 2.241 ms/op [Average]
  (min, avg, max) = (3.894, 4.009, 4.139), stdev = 0.123
  CI (99.9%): [1.768, 6.251] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.440 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.277 ±(99.9%) 0.002 ms/op
Iteration   1: 4.288 ±(99.9%) 0.002 ms/op
Iteration   2: 4.251 ±(99.9%) 0.004 ms/op
Iteration   3: 4.283 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.274 ±(99.9%) 0.365 ms/op [Average]
  (min, avg, max) = (4.251, 4.274, 4.288), stdev = 0.020
  CI (99.9%): [3.909, 4.639] (assumes normal distribution)


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
# Warmup Iteration   1: 6.786 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.508 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.990 ±(99.9%) 0.019 ms/op
Iteration   1: 5.171 ±(99.9%) 0.011 ms/op
Iteration   2: 5.042 ±(99.9%) 0.022 ms/op
Iteration   3: 5.155 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.123 ±(99.9%) 1.287 ms/op [Average]
  (min, avg, max) = (5.042, 5.123, 5.171), stdev = 0.071
  CI (99.9%): [3.836, 6.410] (assumes normal distribution)


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
# Warmup Iteration   1: 5.916 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.293 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.010 ms/op
Iteration   1: 4.215 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   4.145 ms/op
                 createUser·p0.90:   5.333 ms/op
                 createUser·p0.95:   5.620 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  8.471 ms/op
                 createUser·p0.9999: 18.784 ms/op
                 createUser·p1.00:   19.268 ms/op

Iteration   2: 4.278 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   4.219 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   6.586 ms/op
                 createUser·p0.999:  12.870 ms/op
                 createUser·p0.9999: 23.808 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   3: 4.232 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   4.174 ms/op
                 createUser·p0.90:   5.308 ms/op
                 createUser·p0.95:   5.612 ms/op
                 createUser·p0.99:   6.863 ms/op
                 createUser·p0.999:  14.680 ms/op
                 createUser·p0.9999: 25.821 ms/op
                 createUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 226356
  mean =      4.242 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3944 
    [ 2.500,  5.000) = 179896 
    [ 5.000,  7.500) = 41429 
    [ 7.500, 10.000) = 709 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      4.178 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     11.420 ms/op
     p(99.9900) =     23.891 ms/op
     p(99.9990) =     26.018 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 5.491 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.010 ms/op
Iteration   1: 3.791 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.417 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   6.250 ms/op
                 existUser·p0.999:  10.634 ms/op
                 existUser·p0.9999: 15.936 ms/op
                 existUser·p1.00:   16.187 ms/op

Iteration   2: 3.942 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   3.854 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.390 ms/op
                 existUser·p0.99:   6.537 ms/op
                 existUser·p0.999:  9.845 ms/op
                 existUser·p0.9999: 15.037 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   3: 3.933 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   3.854 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   5.308 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  11.829 ms/op
                 existUser·p0.9999: 18.903 ms/op
                 existUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 246972
  mean =      3.887 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 7959 
    [ 2.500,  3.750) = 109151 
    [ 3.750,  5.000) = 108183 
    [ 5.000,  6.250) = 18802 
    [ 6.250,  7.500) = 1564 
    [ 7.500,  8.750) = 585 
    [ 8.750, 10.000) = 269 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.417 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     10.617 ms/op
     p(99.9900) =     18.085 ms/op
     p(99.9990) =     18.925 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 6.285 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.419 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.338 ±(99.9%) 0.012 ms/op
Iteration   1: 4.247 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   4.153 ms/op
                 getUser·p0.90:   5.292 ms/op
                 getUser·p0.95:   5.620 ms/op
                 getUser·p0.99:   7.209 ms/op
                 getUser·p0.999:  12.680 ms/op
                 getUser·p0.9999: 27.296 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   2: 4.147 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.276 ms/op
                 getUser·p0.95:   5.595 ms/op
                 getUser·p0.99:   6.294 ms/op
                 getUser·p0.999:  11.234 ms/op
                 getUser·p0.9999: 30.966 ms/op
                 getUser·p1.00:   31.326 ms/op

Iteration   3: 4.205 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   4.112 ms/op
                 getUser·p0.90:   5.325 ms/op
                 getUser·p0.95:   5.677 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  9.617 ms/op
                 getUser·p0.9999: 30.479 ms/op
                 getUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 228511
  mean =      4.200 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4747 
    [ 2.500,  5.000) = 186008 
    [ 5.000,  7.500) = 36397 
    [ 7.500, 10.000) = 1036 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      4.108 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     10.912 ms/op
     p(99.9900) =     30.774 ms/op
     p(99.9990) =     32.085 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


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
# Warmup Iteration   1: 6.686 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.693 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.203 ±(99.9%) 0.018 ms/op
Iteration   1: 5.207 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   5.014 ms/op
                 listUser·p0.90:   6.488 ms/op
                 listUser·p0.95:   7.299 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  22.650 ms/op
                 listUser·p0.9999: 26.644 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 5.164 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   4.932 ms/op
                 listUser·p0.90:   6.849 ms/op
                 listUser·p0.95:   7.578 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  17.461 ms/op
                 listUser·p0.9999: 22.157 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   3: 4.983 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.324 ms/op
                 listUser·p0.95:   7.160 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  19.672 ms/op
                 listUser·p0.9999: 22.353 ms/op
                 listUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 187749
  mean =      5.116 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 279 
    [ 2.500,  5.000) = 101777 
    [ 5.000,  7.500) = 77351 
    [ 7.500, 10.000) = 7137 
    [10.000, 12.500) = 743 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      4.915 ms/op
     p(90.0000) =      6.578 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =      9.273 ms/op
     p(99.9000) =     19.210 ms/op
     p(99.9900) =     25.730 ms/op
     p(99.9990) =     27.365 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.650 ± 1.875  ops/ms
ClientGrpc.existUser                       thrpt       3   7.967 ± 1.908  ops/ms
ClientGrpc.getUser                         thrpt       3   7.520 ± 1.980  ops/ms
ClientGrpc.listUser                        thrpt       3   6.169 ± 1.741  ops/ms
ClientGrpc.createUser                       avgt       3   4.399 ± 0.924   ms/op
ClientGrpc.existUser                        avgt       3   4.009 ± 2.241   ms/op
ClientGrpc.getUser                          avgt       3   4.274 ± 0.365   ms/op
ClientGrpc.listUser                         avgt       3   5.123 ± 1.287   ms/op
ClientGrpc.createUser                     sample  226356   4.242 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.967           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.178           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.358           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.661           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.545           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.420           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.891           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.051           ms/op
ClientGrpc.existUser                      sample  246972   3.887 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.417           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.923           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.300           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.365           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.617           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.085           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.005           ms/op
ClientGrpc.getUser                        sample  228511   4.200 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.879           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.108           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.300           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.628           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.660           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.912           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.774           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.211           ms/op
ClientGrpc.listUser                       sample  187749   5.116 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.403           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.365           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.273           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.210           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.730           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.394           ms/op
