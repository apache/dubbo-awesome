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
# Warmup Iteration   1: 4.033 ops/ms
# Warmup Iteration   2: 8.409 ops/ms
# Warmup Iteration   3: 9.802 ops/ms
Iteration   1: 10.022 ops/ms
Iteration   2: 9.877 ops/ms
Iteration   3: 9.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.911 ±(99.9%) 1.785 ops/ms [Average]
  (min, avg, max) = (9.835, 9.911, 10.022), stdev = 0.098
  CI (99.9%): [8.127, 11.696] (assumes normal distribution)


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
# Warmup Iteration   1: 6.923 ops/ms
# Warmup Iteration   2: 10.085 ops/ms
# Warmup Iteration   3: 10.424 ops/ms
Iteration   1: 10.132 ops/ms
Iteration   2: 10.457 ops/ms
Iteration   3: 10.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.350 ±(99.9%) 3.431 ops/ms [Average]
  (min, avg, max) = (10.132, 10.350, 10.459), stdev = 0.188
  CI (99.9%): [6.918, 13.781] (assumes normal distribution)


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
# Warmup Iteration   1: 7.570 ops/ms
# Warmup Iteration   2: 9.545 ops/ms
# Warmup Iteration   3: 9.866 ops/ms
Iteration   1: 9.770 ops/ms
Iteration   2: 9.895 ops/ms
Iteration   3: 9.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.858 ±(99.9%) 1.398 ops/ms [Average]
  (min, avg, max) = (9.770, 9.858, 9.910), stdev = 0.077
  CI (99.9%): [8.460, 11.257] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.009 ops/ms
# Warmup Iteration   2: 7.630 ops/ms
# Warmup Iteration   3: 7.773 ops/ms
Iteration   1: 8.000 ops/ms
Iteration   2: 7.902 ops/ms
Iteration   3: 7.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.897 ±(99.9%) 1.906 ops/ms [Average]
  (min, avg, max) = (7.791, 7.897, 8.000), stdev = 0.104
  CI (99.9%): [5.992, 9.803] (assumes normal distribution)


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
# Warmup Iteration   1: 4.420 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.003 ms/op
Iteration   1: 3.197 ±(99.9%) 0.009 ms/op
Iteration   2: 3.229 ±(99.9%) 0.004 ms/op
Iteration   3: 3.249 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.225 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (3.197, 3.225, 3.249), stdev = 0.027
  CI (99.9%): [2.741, 3.710] (assumes normal distribution)


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
# Warmup Iteration   1: 3.950 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.002 ms/op
Iteration   1: 2.986 ±(99.9%) 0.002 ms/op
Iteration   2: 3.071 ±(99.9%) 0.003 ms/op
Iteration   3: 3.121 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.059 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (2.986, 3.059, 3.121), stdev = 0.069
  CI (99.9%): [1.808, 4.310] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.390 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.002 ms/op
Iteration   1: 3.237 ±(99.9%) 0.003 ms/op
Iteration   2: 3.204 ±(99.9%) 0.004 ms/op
Iteration   3: 3.212 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.218 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (3.204, 3.218, 3.237), stdev = 0.017
  CI (99.9%): [2.904, 3.532] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.621 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.206 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.176 ±(99.9%) 0.016 ms/op
Iteration   1: 4.053 ±(99.9%) 0.009 ms/op
Iteration   2: 4.031 ±(99.9%) 0.005 ms/op
Iteration   3: 4.075 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.053 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (4.031, 4.053, 4.075), stdev = 0.022
  CI (99.9%): [3.651, 4.455] (assumes normal distribution)


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
# Warmup Iteration   1: 4.444 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.307 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.007 ms/op
Iteration   1: 3.206 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.347 ms/op
                 createUser·p0.9999: 12.567 ms/op
                 createUser·p1.00:   12.829 ms/op

Iteration   2: 3.279 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  8.864 ms/op
                 createUser·p0.9999: 16.089 ms/op
                 createUser·p1.00:   18.809 ms/op

Iteration   3: 3.239 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  10.011 ms/op
                 createUser·p0.9999: 24.714 ms/op
                 createUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 296236
  mean =      3.241 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19432 
    [ 2.500,  5.000) = 275208 
    [ 5.000,  7.500) = 1164 
    [ 7.500, 10.000) = 200 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      4.544 ms/op
     p(99.9000) =      8.827 ms/op
     p(99.9900) =     23.618 ms/op
     p(99.9990) =     26.020 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
Iteration   1: 3.045 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.389 ms/op
                 existUser·p0.9999: 13.500 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  7.671 ms/op
                 existUser·p0.9999: 14.457 ms/op
                 existUser·p1.00:   16.466 ms/op

Iteration   3: 3.094 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.632 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  9.847 ms/op
                 existUser·p0.9999: 25.154 ms/op
                 existUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313836
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35396 
    [ 2.500,  5.000) = 276889 
    [ 5.000,  7.500) = 1170 
    [ 7.500, 10.000) = 192 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.934 ms/op
     p(99.9900) =     24.165 ms/op
     p(99.9990) =     26.430 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 4.149 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.339 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
Iteration   1: 3.218 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  8.995 ms/op
                 getUser·p0.9999: 19.499 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  8.780 ms/op
                 getUser·p0.9999: 32.670 ms/op
                 getUser·p1.00:   33.686 ms/op

Iteration   3: 3.285 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.716 ms/op
                 getUser·p0.9999: 19.538 ms/op
                 getUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297169
  mean =      3.229 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15962 
    [ 2.500,  5.000) = 279034 
    [ 5.000,  7.500) = 1524 
    [ 7.500, 10.000) = 402 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      8.910 ms/op
     p(99.9900) =     31.541 ms/op
     p(99.9990) =     33.556 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.589 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.012 ms/op
Iteration   1: 3.999 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.847 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.926 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.302 ms/op
                 listUser·p0.9999: 16.220 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   2: 3.973 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 25.231 ms/op
                 listUser·p1.00:   25.690 ms/op

Iteration   3: 4.097 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  15.974 ms/op
                 listUser·p0.9999: 19.340 ms/op
                 listUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238617
  mean =      4.022 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1617 
    [ 2.500,  5.000) = 213241 
    [ 5.000,  7.500) = 22339 
    [ 7.500, 10.000) = 979 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.994 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     24.552 ms/op
     p(99.9990) =     25.534 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.911 ± 1.785  ops/ms
ClientGrpc.existUser                       thrpt       3  10.350 ± 3.431  ops/ms
ClientGrpc.getUser                         thrpt       3   9.858 ± 1.398  ops/ms
ClientGrpc.listUser                        thrpt       3   7.897 ± 1.906  ops/ms
ClientGrpc.createUser                       avgt       3   3.225 ± 0.485   ms/op
ClientGrpc.existUser                        avgt       3   3.059 ± 1.251   ms/op
ClientGrpc.getUser                          avgt       3   3.218 ± 0.314   ms/op
ClientGrpc.listUser                         avgt       3   4.053 ± 0.402   ms/op
ClientGrpc.createUser                     sample  296236   3.241 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.790           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.215           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.084           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.544           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.827           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.618           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.149           ms/op
ClientGrpc.existUser                      sample  313836   3.059 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.632           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.043           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.883           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.934           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.165           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.542           ms/op
ClientGrpc.getUser                        sample  297169   3.229 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.800           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.178           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.100           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.910           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.541           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.686           ms/op
ClientGrpc.listUser                       sample  238617   4.022 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.847           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.994           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.352           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.552           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.690           ms/op
