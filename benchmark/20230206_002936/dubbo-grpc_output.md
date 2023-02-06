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
# Warmup Iteration   1: 1.743 ops/ms
# Warmup Iteration   2: 4.229 ops/ms
# Warmup Iteration   3: 5.793 ops/ms
Iteration   1: 6.028 ops/ms
Iteration   2: 6.056 ops/ms
Iteration   3: 6.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.213 ±(99.9%) 5.398 ops/ms [Average]
  (min, avg, max) = (6.028, 6.213, 6.554), stdev = 0.296
  CI (99.9%): [0.815, 11.611] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.964 ops/ms
# Warmup Iteration   2: 6.095 ops/ms
# Warmup Iteration   3: 6.270 ops/ms
Iteration   1: 6.579 ops/ms
Iteration   2: 6.648 ops/ms
Iteration   3: 6.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.637 ±(99.9%) 0.971 ops/ms [Average]
  (min, avg, max) = (6.579, 6.637, 6.684), stdev = 0.053
  CI (99.9%): [5.666, 7.608] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.437 ops/ms
# Warmup Iteration   2: 5.447 ops/ms
# Warmup Iteration   3: 5.992 ops/ms
Iteration   1: 6.171 ops/ms
Iteration   2: 6.152 ops/ms
Iteration   3: 6.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.150 ±(99.9%) 0.384 ops/ms [Average]
  (min, avg, max) = (6.129, 6.150, 6.171), stdev = 0.021
  CI (99.9%): [5.766, 6.534] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.214 ops/ms
# Warmup Iteration   2: 4.603 ops/ms
# Warmup Iteration   3: 5.128 ops/ms
Iteration   1: 4.952 ops/ms
Iteration   2: 5.212 ops/ms
Iteration   3: 5.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.124 ±(99.9%) 2.711 ops/ms [Average]
  (min, avg, max) = (4.952, 5.124, 5.212), stdev = 0.149
  CI (99.9%): [2.413, 7.834] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.985 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.527 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.182 ±(99.9%) 0.005 ms/op
Iteration   1: 5.164 ±(99.9%) 0.005 ms/op
Iteration   2: 5.142 ±(99.9%) 0.004 ms/op
Iteration   3: 5.159 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.155 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (5.142, 5.155, 5.164), stdev = 0.011
  CI (99.9%): [4.947, 5.364] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.938 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.250 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.849 ±(99.9%) 0.015 ms/op
Iteration   1: 4.831 ±(99.9%) 0.003 ms/op
Iteration   2: 4.873 ±(99.9%) 0.005 ms/op
Iteration   3: 4.700 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.802 ±(99.9%) 1.648 ms/op [Average]
  (min, avg, max) = (4.700, 4.802, 4.873), stdev = 0.090
  CI (99.9%): [3.154, 6.449] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.781 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.504 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.231 ±(99.9%) 0.006 ms/op
Iteration   1: 5.210 ±(99.9%) 0.005 ms/op
Iteration   2: 5.134 ±(99.9%) 0.004 ms/op
Iteration   3: 5.062 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  5.135 ±(99.9%) 1.348 ms/op [Average]
  (min, avg, max) = (5.062, 5.135, 5.210), stdev = 0.074
  CI (99.9%): [3.787, 6.484] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.927 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 6.916 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 6.429 ±(99.9%) 0.018 ms/op
Iteration   1: 6.260 ±(99.9%) 0.015 ms/op
Iteration   2: 6.248 ±(99.9%) 0.019 ms/op
Iteration   3: 6.069 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.192 ±(99.9%) 1.952 ms/op [Average]
  (min, avg, max) = (6.069, 6.192, 6.260), stdev = 0.107
  CI (99.9%): [4.240, 8.144] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.901 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 5.466 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.244 ±(99.9%) 0.020 ms/op
Iteration   1: 5.188 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.339 ms/op
                 createUser·p0.50:   5.022 ms/op
                 createUser·p0.90:   6.586 ms/op
                 createUser·p0.95:   7.242 ms/op
                 createUser·p0.99:   9.658 ms/op
                 createUser·p0.999:  20.547 ms/op
                 createUser·p0.9999: 32.593 ms/op
                 createUser·p1.00:   32.997 ms/op

Iteration   2: 4.827 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   4.669 ms/op
                 createUser·p0.90:   6.046 ms/op
                 createUser·p0.95:   6.775 ms/op
                 createUser·p0.99:   8.913 ms/op
                 createUser·p0.999:  15.659 ms/op
                 createUser·p0.9999: 26.751 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   3: 4.894 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   4.727 ms/op
                 createUser·p0.90:   6.177 ms/op
                 createUser·p0.95:   6.840 ms/op
                 createUser·p0.99:   9.110 ms/op
                 createUser·p0.999:  16.828 ms/op
                 createUser·p0.9999: 28.782 ms/op
                 createUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 193190
  mean =      4.965 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2621 
    [ 2.500,  5.000) = 112036 
    [ 5.000,  7.500) = 72499 
    [ 7.500, 10.000) = 4743 
    [10.000, 12.500) = 918 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      6.971 ms/op
     p(99.0000) =      9.290 ms/op
     p(99.9000) =     15.807 ms/op
     p(99.9900) =     31.611 ms/op
     p(99.9990) =     32.875 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.845 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 5.009 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.976 ±(99.9%) 0.016 ms/op
Iteration   1: 4.768 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.292 ms/op
                 existUser·p0.50:   4.579 ms/op
                 existUser·p0.90:   6.152 ms/op
                 existUser·p0.95:   6.808 ms/op
                 existUser·p0.99:   8.733 ms/op
                 existUser·p0.999:  13.877 ms/op
                 existUser·p0.9999: 19.766 ms/op
                 existUser·p1.00:   20.447 ms/op

Iteration   2: 4.838 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   4.735 ms/op
                 existUser·p0.90:   6.324 ms/op
                 existUser·p0.95:   6.988 ms/op
                 existUser·p0.99:   9.168 ms/op
                 existUser·p0.999:  13.735 ms/op
                 existUser·p0.9999: 21.705 ms/op
                 existUser·p1.00:   22.184 ms/op

Iteration   3: 4.836 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   4.710 ms/op
                 existUser·p0.90:   6.349 ms/op
                 existUser·p0.95:   7.053 ms/op
                 existUser·p0.99:   9.421 ms/op
                 existUser·p0.999:  13.906 ms/op
                 existUser·p0.9999: 31.654 ms/op
                 existUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 199343
  mean =      4.814 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7036 
    [ 2.500,  5.000) = 117003 
    [ 5.000,  7.500) = 68947 
    [ 7.500, 10.000) = 5268 
    [10.000, 12.500) = 747 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      6.275 ms/op
     p(95.0000) =      6.947 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     13.839 ms/op
     p(99.9900) =     29.827 ms/op
     p(99.9990) =     33.132 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.220 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 5.435 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.344 ±(99.9%) 0.018 ms/op
Iteration   1: 5.185 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.208 ms/op
                 getUser·p0.50:   5.030 ms/op
                 getUser·p0.90:   6.701 ms/op
                 getUser·p0.95:   7.307 ms/op
                 getUser·p0.99:   9.411 ms/op
                 getUser·p0.999:  14.844 ms/op
                 getUser·p0.9999: 17.492 ms/op
                 getUser·p1.00:   18.022 ms/op

Iteration   2: 5.099 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   4.932 ms/op
                 getUser·p0.90:   6.513 ms/op
                 getUser·p0.95:   7.176 ms/op
                 getUser·p0.99:   9.373 ms/op
                 getUser·p0.999:  14.587 ms/op
                 getUser·p0.9999: 19.980 ms/op
                 getUser·p1.00:   21.168 ms/op

Iteration   3: 4.984 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   4.874 ms/op
                 getUser·p0.90:   6.398 ms/op
                 getUser·p0.95:   6.979 ms/op
                 getUser·p0.99:   8.897 ms/op
                 getUser·p0.999:  13.662 ms/op
                 getUser·p0.9999: 19.123 ms/op
                 getUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 188569
  mean =      5.088 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3114 
    [ 2.500,  5.000) = 95316 
    [ 5.000,  7.500) = 83403 
    [ 7.500, 10.000) = 5658 
    [10.000, 12.500) = 767 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.039 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.545 ms/op
     p(95.0000) =      7.168 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     14.507 ms/op
     p(99.9900) =     19.548 ms/op
     p(99.9990) =     21.741 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 9.138 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 7.047 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 6.581 ±(99.9%) 0.029 ms/op
Iteration   1: 6.676 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   6.152 ms/op
                 listUser·p0.90:   9.306 ms/op
                 listUser·p0.95:   10.535 ms/op
                 listUser·p0.99:   13.550 ms/op
                 listUser·p0.999:  25.559 ms/op
                 listUser·p0.9999: 30.920 ms/op
                 listUser·p1.00:   31.359 ms/op

Iteration   2: 6.533 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   9.290 ms/op
                 listUser·p0.95:   10.289 ms/op
                 listUser·p0.99:   13.058 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 30.553 ms/op
                 listUser·p1.00:   38.207 ms/op

Iteration   3: 6.510 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.864 ms/op
                 listUser·p0.50:   6.038 ms/op
                 listUser·p0.90:   9.028 ms/op
                 listUser·p0.95:   10.076 ms/op
                 listUser·p0.99:   12.173 ms/op
                 listUser·p0.999:  25.686 ms/op
                 listUser·p0.9999: 30.268 ms/op
                 listUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 146062
  mean =      6.572 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 26655 
    [ 5.000,  7.500) = 83683 
    [ 7.500, 10.000) = 26943 
    [10.000, 12.500) = 6863 
    [12.500, 15.000) = 1312 
    [15.000, 17.500) = 273 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.864 ms/op
     p(50.0000) =      6.054 ms/op
     p(90.0000) =      9.208 ms/op
     p(95.0000) =     10.289 ms/op
     p(99.0000) =     12.966 ms/op
     p(99.9000) =     24.478 ms/op
     p(99.9900) =     30.684 ms/op
     p(99.9990) =     38.177 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.213 ± 5.398  ops/ms
ClientGrpc.existUser                       thrpt       3   6.637 ± 0.971  ops/ms
ClientGrpc.getUser                         thrpt       3   6.150 ± 0.384  ops/ms
ClientGrpc.listUser                        thrpt       3   5.124 ± 2.711  ops/ms
ClientGrpc.createUser                       avgt       3   5.155 ± 0.209   ms/op
ClientGrpc.existUser                        avgt       3   4.802 ± 1.648   ms/op
ClientGrpc.getUser                          avgt       3   5.135 ± 1.348   ms/op
ClientGrpc.listUser                         avgt       3   6.192 ± 1.952   ms/op
ClientGrpc.createUser                     sample  193190   4.965 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.108           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.784           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.308           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.971           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.290           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.807           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.611           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.997           ms/op
ClientGrpc.existUser                      sample  199343   4.814 ± 0.010   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.931           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.669           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           6.275           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.947           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.110           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.839           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.827           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.686           ms/op
ClientGrpc.getUser                        sample  188569   5.088 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.039           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.940           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.545           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.168           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.224           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.507           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.548           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.118           ms/op
ClientGrpc.listUser                       sample  146062   6.572 ± 0.018   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.864           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           6.054           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           9.208           ms/op
ClientGrpc.listUser:listUser·p0.95        sample          10.289           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.966           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          24.478           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.684           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.207           ms/op
