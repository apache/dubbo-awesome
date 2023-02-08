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
# Warmup Iteration   1: 4.000 ops/ms
# Warmup Iteration   2: 8.654 ops/ms
# Warmup Iteration   3: 9.880 ops/ms
Iteration   1: 9.942 ops/ms
Iteration   2: 9.859 ops/ms
Iteration   3: 9.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.867 ±(99.9%) 1.315 ops/ms [Average]
  (min, avg, max) = (9.799, 9.867, 9.942), stdev = 0.072
  CI (99.9%): [8.552, 11.181] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.288 ops/ms
# Warmup Iteration   2: 9.956 ops/ms
# Warmup Iteration   3: 10.119 ops/ms
Iteration   1: 10.513 ops/ms
Iteration   2: 10.369 ops/ms
Iteration   3: 10.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.393 ±(99.9%) 1.999 ops/ms [Average]
  (min, avg, max) = (10.298, 10.393, 10.513), stdev = 0.110
  CI (99.9%): [8.394, 12.392] (assumes normal distribution)


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
# Warmup Iteration   1: 6.148 ops/ms
# Warmup Iteration   2: 9.675 ops/ms
# Warmup Iteration   3: 9.852 ops/ms
Iteration   1: 9.771 ops/ms
Iteration   2: 9.644 ops/ms
Iteration   3: 9.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.735 ±(99.9%) 1.454 ops/ms [Average]
  (min, avg, max) = (9.644, 9.735, 9.791), stdev = 0.080
  CI (99.9%): [8.281, 11.189] (assumes normal distribution)


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
# Warmup Iteration   1: 4.687 ops/ms
# Warmup Iteration   2: 7.275 ops/ms
# Warmup Iteration   3: 7.566 ops/ms
Iteration   1: 7.524 ops/ms
Iteration   2: 7.603 ops/ms
Iteration   3: 7.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.613 ±(99.9%) 1.718 ops/ms [Average]
  (min, avg, max) = (7.524, 7.613, 7.711), stdev = 0.094
  CI (99.9%): [5.894, 9.331] (assumes normal distribution)


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
# Warmup Iteration   1: 4.519 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.003 ms/op
Iteration   1: 3.207 ±(99.9%) 0.001 ms/op
Iteration   2: 3.213 ±(99.9%) 0.002 ms/op
Iteration   3: 3.276 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.232 ±(99.9%) 0.702 ms/op [Average]
  (min, avg, max) = (3.207, 3.232, 3.276), stdev = 0.038
  CI (99.9%): [2.530, 3.934] (assumes normal distribution)


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
# Warmup Iteration   1: 4.238 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.003 ms/op
Iteration   1: 3.096 ±(99.9%) 0.002 ms/op
Iteration   2: 3.139 ±(99.9%) 0.002 ms/op
Iteration   3: 3.137 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.124 ±(99.9%) 0.442 ms/op [Average]
  (min, avg, max) = (3.096, 3.124, 3.139), stdev = 0.024
  CI (99.9%): [2.682, 3.566] (assumes normal distribution)


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
# Warmup Iteration   1: 4.843 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.413 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.002 ms/op
Iteration   1: 3.342 ±(99.9%) 0.002 ms/op
Iteration   2: 3.253 ±(99.9%) 0.002 ms/op
Iteration   3: 3.300 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.298 ±(99.9%) 0.805 ms/op [Average]
  (min, avg, max) = (3.253, 3.298, 3.342), stdev = 0.044
  CI (99.9%): [2.494, 4.103] (assumes normal distribution)


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
# Warmup Iteration   1: 5.708 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.426 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.292 ±(99.9%) 0.014 ms/op
Iteration   1: 4.230 ±(99.9%) 0.022 ms/op
Iteration   2: 4.261 ±(99.9%) 0.007 ms/op
Iteration   3: 4.230 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.240 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (4.230, 4.240, 4.261), stdev = 0.018
  CI (99.9%): [3.914, 4.567] (assumes normal distribution)


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.315 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.007 ms/op
Iteration   1: 3.286 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  9.167 ms/op
                 createUser·p0.9999: 13.441 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   2: 3.302 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  8.199 ms/op
                 createUser·p0.9999: 15.027 ms/op
                 createUser·p1.00:   15.385 ms/op

Iteration   3: 3.293 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  7.517 ms/op
                 createUser·p0.9999: 18.179 ms/op
                 createUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 291710
  mean =      3.294 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 398 
    [ 1.250,  2.500) = 14248 
    [ 2.500,  3.750) = 218984 
    [ 3.750,  5.000) = 56482 
    [ 5.000,  6.250) = 797 
    [ 6.250,  7.500) = 420 
    [ 7.500,  8.750) = 118 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      8.235 ms/op
     p(99.9900) =     17.138 ms/op
     p(99.9990) =     18.585 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.006 ms/op
Iteration   1: 3.124 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  7.370 ms/op
                 existUser·p0.9999: 21.881 ms/op
                 existUser·p1.00:   22.512 ms/op

Iteration   2: 3.065 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.549 ms/op
                 existUser·p0.9999: 22.646 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  7.579 ms/op
                 existUser·p0.9999: 17.072 ms/op
                 existUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312075
  mean =      3.075 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35891 
    [ 2.500,  5.000) = 274965 
    [ 5.000,  7.500) = 899 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.528 ms/op
     p(99.9900) =     22.046 ms/op
     p(99.9990) =     23.028 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 4.397 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.315 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.296 ±(99.9%) 0.007 ms/op
Iteration   1: 3.221 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.999 ms/op
                 getUser·p0.9999: 15.256 ms/op
                 getUser·p1.00:   15.712 ms/op

Iteration   2: 3.297 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.199 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  11.519 ms/op
                 getUser·p0.9999: 20.303 ms/op
                 getUser·p1.00:   21.266 ms/op

Iteration   3: 3.266 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.529 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  10.530 ms/op
                 getUser·p0.9999: 17.695 ms/op
                 getUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 294329
  mean =      3.261 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15732 
    [ 2.500,  5.000) = 276766 
    [ 5.000,  7.500) = 1350 
    [ 7.500, 10.000) = 198 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.199 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.176 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      9.792 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     21.139 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


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
# Warmup Iteration   1: 6.034 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.306 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.218 ±(99.9%) 0.013 ms/op
Iteration   1: 4.206 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 22.831 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   2: 4.247 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  13.936 ms/op
                 listUser·p0.9999: 20.233 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   3: 4.186 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.205 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 21.245 ms/op
                 listUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 228198
  mean =      4.213 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1431 
    [ 2.500,  5.000) = 194046 
    [ 5.000,  7.500) = 31030 
    [ 7.500, 10.000) = 1218 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     16.597 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     23.125 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.867 ± 1.315  ops/ms
ClientGrpc.existUser                       thrpt       3  10.393 ± 1.999  ops/ms
ClientGrpc.getUser                         thrpt       3   9.735 ± 1.454  ops/ms
ClientGrpc.listUser                        thrpt       3   7.613 ± 1.718  ops/ms
ClientGrpc.createUser                       avgt       3   3.232 ± 0.702   ms/op
ClientGrpc.existUser                        avgt       3   3.124 ± 0.442   ms/op
ClientGrpc.getUser                          avgt       3   3.298 ± 0.805   ms/op
ClientGrpc.listUser                         avgt       3   4.240 ± 0.327   ms/op
ClientGrpc.createUser                     sample  291710   3.294 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.772           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.260           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.014           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.235           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.138           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.711           ms/op
ClientGrpc.existUser                      sample  312075   3.075 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.665           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.056           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.756           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.949           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.528           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.046           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.167           ms/op
ClientGrpc.getUser                        sample  294329   3.261 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.199           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.228           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.969           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.176           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.628           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.792           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.366           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.266           ms/op
ClientGrpc.listUser                       sample  228198   4.213 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.057           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.022           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.956           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.258           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.597           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.332           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.167           ms/op
