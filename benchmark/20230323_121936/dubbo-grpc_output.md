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
# Warmup Iteration   1: 3.194 ops/ms
# Warmup Iteration   2: 6.260 ops/ms
# Warmup Iteration   3: 7.314 ops/ms
Iteration   1: 7.884 ops/ms
Iteration   2: 7.722 ops/ms
Iteration   3: 8.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.935 ±(99.9%) 4.431 ops/ms [Average]
  (min, avg, max) = (7.722, 7.935, 8.199), stdev = 0.243
  CI (99.9%): [3.504, 12.366] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.758 ops/ms
# Warmup Iteration   2: 7.380 ops/ms
# Warmup Iteration   3: 7.483 ops/ms
Iteration   1: 7.794 ops/ms
Iteration   2: 8.226 ops/ms
Iteration   3: 8.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.018 ±(99.9%) 3.947 ops/ms [Average]
  (min, avg, max) = (7.794, 8.018, 8.226), stdev = 0.216
  CI (99.9%): [4.071, 11.965] (assumes normal distribution)


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
# Warmup Iteration   1: 5.507 ops/ms
# Warmup Iteration   2: 7.555 ops/ms
# Warmup Iteration   3: 6.894 ops/ms
Iteration   1: 7.840 ops/ms
Iteration   2: 7.749 ops/ms
Iteration   3: 7.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.765 ±(99.9%) 1.252 ops/ms [Average]
  (min, avg, max) = (7.706, 7.765, 7.840), stdev = 0.069
  CI (99.9%): [6.513, 9.017] (assumes normal distribution)


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
# Warmup Iteration   1: 3.943 ops/ms
# Warmup Iteration   2: 5.213 ops/ms
# Warmup Iteration   3: 5.466 ops/ms
Iteration   1: 5.623 ops/ms
Iteration   2: 6.065 ops/ms
Iteration   3: 6.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.950 ±(99.9%) 5.241 ops/ms [Average]
  (min, avg, max) = (5.623, 5.950, 6.163), stdev = 0.287
  CI (99.9%): [0.709, 11.192] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.160 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.399 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.017 ms/op
Iteration   1: 4.213 ±(99.9%) 0.008 ms/op
Iteration   2: 4.077 ±(99.9%) 0.004 ms/op
Iteration   3: 4.314 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.202 ±(99.9%) 2.175 ms/op [Average]
  (min, avg, max) = (4.077, 4.202, 4.314), stdev = 0.119
  CI (99.9%): [2.027, 6.376] (assumes normal distribution)


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
# Warmup Iteration   1: 5.407 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.018 ms/op
Iteration   1: 3.797 ±(99.9%) 0.004 ms/op
Iteration   2: 3.727 ±(99.9%) 0.004 ms/op
Iteration   3: 3.660 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.728 ±(99.9%) 1.253 ms/op [Average]
  (min, avg, max) = (3.660, 3.728, 3.797), stdev = 0.069
  CI (99.9%): [2.475, 4.981] (assumes normal distribution)


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
# Warmup Iteration   1: 5.685 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.005 ms/op
Iteration   1: 3.827 ±(99.9%) 0.004 ms/op
Iteration   2: 3.774 ±(99.9%) 0.004 ms/op
Iteration   3: 4.161 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.921 ±(99.9%) 3.821 ms/op [Average]
  (min, avg, max) = (3.774, 3.921, 4.161), stdev = 0.209
  CI (99.9%): [0.100, 7.741] (assumes normal distribution)


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
# Warmup Iteration   1: 7.180 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.756 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 5.536 ±(99.9%) 0.018 ms/op
Iteration   1: 4.829 ±(99.9%) 0.013 ms/op
Iteration   2: 4.924 ±(99.9%) 0.009 ms/op
Iteration   3: 5.109 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.954 ±(99.9%) 2.604 ms/op [Average]
  (min, avg, max) = (4.829, 4.954, 5.109), stdev = 0.143
  CI (99.9%): [2.350, 7.558] (assumes normal distribution)


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
# Warmup Iteration   1: 5.975 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.206 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.016 ms/op
Iteration   1: 4.053 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   5.325 ms/op
                 createUser·p0.95:   6.103 ms/op
                 createUser·p0.99:   8.170 ms/op
                 createUser·p0.999:  12.796 ms/op
                 createUser·p0.9999: 15.760 ms/op
                 createUser·p1.00:   16.253 ms/op

Iteration   2: 3.890 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.571 ms/op
                 createUser·p0.99:   8.471 ms/op
                 createUser·p0.999:  18.176 ms/op
                 createUser·p0.9999: 26.567 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   3: 3.859 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.915 ms/op
                 createUser·p0.95:   5.718 ms/op
                 createUser·p0.99:   8.053 ms/op
                 createUser·p0.999:  14.060 ms/op
                 createUser·p0.9999: 20.536 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 244109
  mean =      3.932 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12745 
    [ 2.500,  5.000) = 205882 
    [ 5.000,  7.500) = 21808 
    [ 7.500, 10.000) = 2900 
    [10.000, 12.500) = 348 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      8.225 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     24.391 ms/op
     p(99.9990) =     26.710 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 5.507 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.573 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.015 ms/op
Iteration   1: 4.199 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   3.928 ms/op
                 existUser·p0.90:   5.751 ms/op
                 existUser·p0.95:   6.775 ms/op
                 existUser·p0.99:   8.913 ms/op
                 existUser·p0.999:  12.825 ms/op
                 existUser·p0.9999: 42.904 ms/op
                 existUser·p1.00:   44.761 ms/op

Iteration   2: 4.267 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   4.002 ms/op
                 existUser·p0.90:   5.808 ms/op
                 existUser·p0.95:   6.717 ms/op
                 existUser·p0.99:   9.175 ms/op
                 existUser·p0.999:  13.058 ms/op
                 existUser·p0.9999: 19.218 ms/op
                 existUser·p1.00:   19.694 ms/op

Iteration   3: 4.022 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   5.374 ms/op
                 existUser·p0.95:   6.373 ms/op
                 existUser·p0.99:   8.651 ms/op
                 existUser·p0.999:  11.459 ms/op
                 existUser·p0.9999: 23.791 ms/op
                 existUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 230860
  mean =      4.160 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 191230 
    [ 5.000, 10.000) = 38709 
    [10.000, 15.000) = 804 
    [15.000, 20.000) = 51 
    [20.000, 25.000) = 34 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.652 ms/op
     p(95.0000) =      6.636 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     12.454 ms/op
     p(99.9900) =     40.627 ms/op
     p(99.9990) =     44.136 ms/op
     p(99.9999) =     44.761 ms/op
    p(100.0000) =     44.761 ms/op


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
# Warmup Iteration   1: 5.987 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.404 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.258 ±(99.9%) 0.016 ms/op
Iteration   1: 4.094 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   5.276 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   8.405 ms/op
                 getUser·p0.999:  12.056 ms/op
                 getUser·p0.9999: 16.170 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   2: 4.166 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   5.325 ms/op
                 getUser·p0.95:   6.210 ms/op
                 getUser·p0.99:   8.536 ms/op
                 getUser·p0.999:  14.570 ms/op
                 getUser·p0.9999: 21.037 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   3: 4.145 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   5.350 ms/op
                 getUser·p0.95:   6.177 ms/op
                 getUser·p0.99:   8.602 ms/op
                 getUser·p0.999:  13.124 ms/op
                 getUser·p0.9999: 20.382 ms/op
                 getUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 232296
  mean =      4.135 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5131 
    [ 2.500,  5.000) = 195668 
    [ 5.000,  7.500) = 26972 
    [ 7.500, 10.000) = 3657 
    [10.000, 12.500) = 594 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      6.160 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     21.683 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 7.699 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.658 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.164 ±(99.9%) 0.020 ms/op
Iteration   1: 5.493 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.015 ms/op
                 listUser·p0.50:   5.014 ms/op
                 listUser·p0.90:   7.594 ms/op
                 listUser·p0.95:   8.667 ms/op
                 listUser·p0.99:   11.583 ms/op
                 listUser·p0.999:  18.088 ms/op
                 listUser·p0.9999: 25.859 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   2: 5.474 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   4.956 ms/op
                 listUser·p0.90:   7.692 ms/op
                 listUser·p0.95:   8.782 ms/op
                 listUser·p0.99:   11.551 ms/op
                 listUser·p0.999:  18.711 ms/op
                 listUser·p0.9999: 27.087 ms/op
                 listUser·p1.00:   38.011 ms/op

Iteration   3: 5.432 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   4.997 ms/op
                 listUser·p0.90:   7.543 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   10.998 ms/op
                 listUser·p0.999:  21.823 ms/op
                 listUser·p0.9999: 34.634 ms/op
                 listUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 175647
  mean =      5.466 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 397 
    [ 2.500,  5.000) = 88094 
    [ 5.000,  7.500) = 68215 
    [ 7.500, 10.000) = 15120 
    [10.000, 12.500) = 2796 
    [12.500, 15.000) = 608 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      7.610 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     11.412 ms/op
     p(99.9000) =     20.426 ms/op
     p(99.9900) =     33.968 ms/op
     p(99.9990) =     37.961 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.935 ± 4.431  ops/ms
ClientGrpc.existUser                       thrpt       3   8.018 ± 3.947  ops/ms
ClientGrpc.getUser                         thrpt       3   7.765 ± 1.252  ops/ms
ClientGrpc.listUser                        thrpt       3   5.950 ± 5.241  ops/ms
ClientGrpc.createUser                       avgt       3   4.202 ± 2.175   ms/op
ClientGrpc.existUser                        avgt       3   3.728 ± 1.253   ms/op
ClientGrpc.getUser                          avgt       3   3.921 ± 3.821   ms/op
ClientGrpc.listUser                         avgt       3   4.954 ± 2.604   ms/op
ClientGrpc.createUser                     sample  244109   3.932 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.788           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.046           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.816           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.225           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.221           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.391           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.066           ms/op
ClientGrpc.existUser                      sample  230860   4.160 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.589           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.883           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.652           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.636           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.897           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.454           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          40.627           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          44.761           ms/op
ClientGrpc.getUser                        sample  232296   4.135 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.939           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.317           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.160           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.520           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.042           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.480           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.823           ms/op
ClientGrpc.listUser                       sample  175647   5.466 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.015           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.610           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.651           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.412           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.426           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.968           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.011           ms/op
