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
# Warmup Iteration   1: 3.121 ops/ms
# Warmup Iteration   2: 6.575 ops/ms
# Warmup Iteration   3: 7.758 ops/ms
Iteration   1: 8.259 ops/ms
Iteration   2: 8.199 ops/ms
Iteration   3: 8.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.170 ±(99.9%) 1.933 ops/ms [Average]
  (min, avg, max) = (8.053, 8.170, 8.259), stdev = 0.106
  CI (99.9%): [6.238, 10.103] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.944 ops/ms
# Warmup Iteration   2: 8.490 ops/ms
# Warmup Iteration   3: 8.771 ops/ms
Iteration   1: 9.375 ops/ms
Iteration   2: 8.924 ops/ms
Iteration   3: 9.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.238 ±(99.9%) 4.962 ops/ms [Average]
  (min, avg, max) = (8.924, 9.238, 9.413), stdev = 0.272
  CI (99.9%): [4.275, 14.200] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.815 ops/ms
# Warmup Iteration   2: 8.154 ops/ms
# Warmup Iteration   3: 8.371 ops/ms
Iteration   1: 8.465 ops/ms
Iteration   2: 8.501 ops/ms
Iteration   3: 8.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.547 ±(99.9%) 2.048 ops/ms [Average]
  (min, avg, max) = (8.465, 8.547, 8.675), stdev = 0.112
  CI (99.9%): [6.499, 10.595] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.229 ops/ms
# Warmup Iteration   2: 5.939 ops/ms
# Warmup Iteration   3: 6.116 ops/ms
Iteration   1: 6.268 ops/ms
Iteration   2: 6.332 ops/ms
Iteration   3: 6.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.317 ±(99.9%) 0.804 ops/ms [Average]
  (min, avg, max) = (6.268, 6.317, 6.353), stdev = 0.044
  CI (99.9%): [5.513, 7.121] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.633 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.006 ms/op
Iteration   1: 3.798 ±(99.9%) 0.003 ms/op
Iteration   2: 3.850 ±(99.9%) 0.004 ms/op
Iteration   3: 3.859 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.836 ±(99.9%) 0.605 ms/op [Average]
  (min, avg, max) = (3.798, 3.836, 3.859), stdev = 0.033
  CI (99.9%): [3.231, 4.441] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.087 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.004 ms/op
Iteration   1: 3.655 ±(99.9%) 0.004 ms/op
Iteration   2: 3.551 ±(99.9%) 0.004 ms/op
Iteration   3: 3.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.562 ±(99.9%) 1.593 ms/op [Average]
  (min, avg, max) = (3.481, 3.562, 3.655), stdev = 0.087
  CI (99.9%): [1.969, 5.156] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.424 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.011 ms/op
Iteration   1: 3.891 ±(99.9%) 0.004 ms/op
Iteration   2: 3.765 ±(99.9%) 0.005 ms/op
Iteration   3: 3.802 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.819 ±(99.9%) 1.178 ms/op [Average]
  (min, avg, max) = (3.765, 3.819, 3.891), stdev = 0.065
  CI (99.9%): [2.641, 4.997] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.289 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.582 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.221 ±(99.9%) 0.014 ms/op
Iteration   1: 5.069 ±(99.9%) 0.021 ms/op
Iteration   2: 5.003 ±(99.9%) 0.011 ms/op
Iteration   3: 4.953 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.008 ±(99.9%) 1.064 ms/op [Average]
  (min, avg, max) = (4.953, 5.008, 5.069), stdev = 0.058
  CI (99.9%): [3.945, 6.072] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.453 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.861 ±(99.9%) 0.012 ms/op
Iteration   1: 3.728 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   7.766 ms/op
                 createUser·p0.999:  10.273 ms/op
                 createUser·p0.9999: 14.799 ms/op
                 createUser·p1.00:   15.254 ms/op

Iteration   2: 3.744 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   7.396 ms/op
                 createUser·p0.999:  11.780 ms/op
                 createUser·p0.9999: 19.494 ms/op
                 createUser·p1.00:   20.021 ms/op

Iteration   3: 3.759 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   7.569 ms/op
                 createUser·p0.999:  15.250 ms/op
                 createUser·p0.9999: 29.032 ms/op
                 createUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 256409
  mean =      3.744 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9060 
    [ 2.500,  5.000) = 233813 
    [ 5.000,  7.500) = 10855 
    [ 7.500, 10.000) = 2072 
    [10.000, 12.500) = 362 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     12.321 ms/op
     p(99.9900) =     27.570 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.356 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.011 ms/op
Iteration   1: 3.649 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.513 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   5.128 ms/op
                 existUser·p0.99:   7.889 ms/op
                 existUser·p0.999:  12.045 ms/op
                 existUser·p0.9999: 20.193 ms/op
                 existUser·p1.00:   20.578 ms/op

Iteration   2: 3.495 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  9.019 ms/op
                 existUser·p0.9999: 18.612 ms/op
                 existUser·p1.00:   18.842 ms/op

Iteration   3: 3.550 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.411 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   7.037 ms/op
                 existUser·p0.999:  11.950 ms/op
                 existUser·p0.9999: 39.846 ms/op
                 existUser·p1.00:   40.174 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 269273
  mean =      3.563 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 258565 
    [ 5.000, 10.000) = 10317 
    [10.000, 15.000) = 231 
    [15.000, 20.000) = 80 
    [20.000, 25.000) = 48 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.411 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     11.174 ms/op
     p(99.9900) =     38.807 ms/op
     p(99.9990) =     40.128 ms/op
     p(99.9999) =     40.174 ms/op
    p(100.0000) =     40.174 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.417 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.013 ms/op
Iteration   1: 3.787 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.337 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   7.266 ms/op
                 getUser·p0.999:  11.805 ms/op
                 getUser·p0.9999: 15.385 ms/op
                 getUser·p1.00:   15.598 ms/op

Iteration   2: 3.802 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   7.168 ms/op
                 getUser·p0.999:  12.599 ms/op
                 getUser·p0.9999: 19.155 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   3: 3.751 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   7.791 ms/op
                 getUser·p0.999:  11.960 ms/op
                 getUser·p0.9999: 25.509 ms/op
                 getUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253992
  mean =      3.780 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9971 
    [ 2.500,  5.000) = 229182 
    [ 5.000,  7.500) = 12469 
    [ 7.500, 10.000) = 1750 
    [10.000, 12.500) = 410 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.337 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     11.993 ms/op
     p(99.9900) =     23.659 ms/op
     p(99.9990) =     25.982 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 6.496 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.322 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.012 ±(99.9%) 0.020 ms/op
Iteration   1: 4.984 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.595 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.685 ms/op
                 listUser·p0.95:   7.635 ms/op
                 listUser·p0.99:   10.256 ms/op
                 listUser·p0.999:  16.637 ms/op
                 listUser·p0.9999: 24.385 ms/op
                 listUser·p1.00:   26.542 ms/op

Iteration   2: 5.094 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.027 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.857 ms/op
                 listUser·p0.95:   7.766 ms/op
                 listUser·p0.99:   10.306 ms/op
                 listUser·p0.999:  19.177 ms/op
                 listUser·p0.9999: 21.592 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   3: 4.837 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.545 ms/op
                 listUser·p0.95:   7.414 ms/op
                 listUser·p0.99:   9.829 ms/op
                 listUser·p0.999:  20.968 ms/op
                 listUser·p0.9999: 35.939 ms/op
                 listUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 193026
  mean =      4.969 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 948 
    [ 2.500,  5.000) = 126974 
    [ 5.000,  7.500) = 54628 
    [ 7.500, 10.000) = 8370 
    [10.000, 12.500) = 1404 
    [12.500, 15.000) = 262 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.602 ms/op
     p(99.0000) =     10.142 ms/op
     p(99.9000) =     19.726 ms/op
     p(99.9900) =     34.518 ms/op
     p(99.9990) =     37.692 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.170 ± 1.933  ops/ms
ClientGrpc.existUser                       thrpt       3   9.238 ± 4.962  ops/ms
ClientGrpc.getUser                         thrpt       3   8.547 ± 2.048  ops/ms
ClientGrpc.listUser                        thrpt       3   6.317 ± 0.804  ops/ms
ClientGrpc.createUser                       avgt       3   3.836 ± 0.605   ms/op
ClientGrpc.existUser                        avgt       3   3.562 ± 1.593   ms/op
ClientGrpc.getUser                          avgt       3   3.819 ± 1.178   ms/op
ClientGrpc.listUser                         avgt       3   5.008 ± 1.064   ms/op
ClientGrpc.createUser                     sample  256409   3.744 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.752           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.054           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.578           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.321           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.570           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.164           ms/op
ClientGrpc.existUser                      sample  269273   3.563 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.411           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.809           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.209           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.174           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          38.807           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          40.174           ms/op
ClientGrpc.getUser                        sample  253992   3.780 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.337           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.145           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.373           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.993           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.659           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.116           ms/op
ClientGrpc.listUser                       sample  193026   4.969 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.027           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.602           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.142           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.726           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.518           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.814           ms/op
