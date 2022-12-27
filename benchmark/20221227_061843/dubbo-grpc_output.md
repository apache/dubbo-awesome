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
# Warmup Iteration   1: 3.934 ops/ms
# Warmup Iteration   2: 8.622 ops/ms
# Warmup Iteration   3: 9.847 ops/ms
Iteration   1: 9.964 ops/ms
Iteration   2: 9.801 ops/ms
Iteration   3: 9.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.851 ±(99.9%) 1.797 ops/ms [Average]
  (min, avg, max) = (9.787, 9.851, 9.964), stdev = 0.098
  CI (99.9%): [8.054, 11.648] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.447 ops/ms
# Warmup Iteration   2: 10.210 ops/ms
# Warmup Iteration   3: 10.530 ops/ms
Iteration   1: 10.632 ops/ms
Iteration   2: 10.626 ops/ms
Iteration   3: 10.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.698 ±(99.9%) 2.171 ops/ms [Average]
  (min, avg, max) = (10.626, 10.698, 10.835), stdev = 0.119
  CI (99.9%): [8.526, 12.869] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.868 ops/ms
# Warmup Iteration   2: 9.921 ops/ms
# Warmup Iteration   3: 10.055 ops/ms
Iteration   1: 10.151 ops/ms
Iteration   2: 10.202 ops/ms
Iteration   3: 10.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.223 ±(99.9%) 1.556 ops/ms [Average]
  (min, avg, max) = (10.151, 10.223, 10.317), stdev = 0.085
  CI (99.9%): [8.667, 11.780] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.345 ops/ms
# Warmup Iteration   2: 7.490 ops/ms
# Warmup Iteration   3: 7.823 ops/ms
Iteration   1: 7.925 ops/ms
Iteration   2: 8.037 ops/ms
Iteration   3: 7.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.964 ±(99.9%) 1.153 ops/ms [Average]
  (min, avg, max) = (7.925, 7.964, 8.037), stdev = 0.063
  CI (99.9%): [6.811, 9.117] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.424 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.002 ms/op
Iteration   1: 3.180 ±(99.9%) 0.004 ms/op
Iteration   2: 3.209 ±(99.9%) 0.002 ms/op
Iteration   3: 3.202 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.197 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (3.180, 3.197, 3.209), stdev = 0.015
  CI (99.9%): [2.922, 3.472] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.091 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.002 ms/op
Iteration   1: 3.088 ±(99.9%) 0.001 ms/op
Iteration   2: 3.051 ±(99.9%) 0.003 ms/op
Iteration   3: 2.976 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.039 ±(99.9%) 1.041 ms/op [Average]
  (min, avg, max) = (2.976, 3.039, 3.088), stdev = 0.057
  CI (99.9%): [1.998, 4.079] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.296 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.002 ms/op
Iteration   1: 3.146 ±(99.9%) 0.003 ms/op
Iteration   2: 3.225 ±(99.9%) 0.003 ms/op
Iteration   3: 3.242 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.204 ±(99.9%) 0.937 ms/op [Average]
  (min, avg, max) = (3.146, 3.204, 3.242), stdev = 0.051
  CI (99.9%): [2.268, 4.141] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.249 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.241 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.012 ms/op
Iteration   1: 4.012 ±(99.9%) 0.011 ms/op
Iteration   2: 4.078 ±(99.9%) 0.008 ms/op
Iteration   3: 4.105 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.065 ±(99.9%) 0.869 ms/op [Average]
  (min, avg, max) = (4.012, 4.065, 4.105), stdev = 0.048
  CI (99.9%): [3.195, 4.934] (assumes normal distribution)


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
# Warmup Iteration   1: 4.562 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.007 ms/op
Iteration   1: 3.205 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   4.973 ms/op
                 createUser·p0.999:  8.969 ms/op
                 createUser·p0.9999: 15.173 ms/op
                 createUser·p1.00:   17.236 ms/op

Iteration   2: 3.265 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  11.289 ms/op
                 createUser·p0.9999: 15.886 ms/op
                 createUser·p1.00:   16.105 ms/op

Iteration   3: 3.246 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  12.607 ms/op
                 createUser·p0.9999: 19.759 ms/op
                 createUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 296327
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18329 
    [ 2.500,  5.000) = 273379 
    [ 5.000,  7.500) = 3863 
    [ 7.500, 10.000) = 357 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     11.272 ms/op
     p(99.9900) =     19.542 ms/op
     p(99.9990) =     19.957 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 4.081 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
Iteration   1: 3.118 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.508 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  7.707 ms/op
                 existUser·p0.9999: 15.687 ms/op
                 existUser·p1.00:   16.122 ms/op

Iteration   2: 3.064 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.583 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  8.327 ms/op
                 existUser·p0.9999: 16.459 ms/op
                 existUser·p1.00:   16.712 ms/op

Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  8.749 ms/op
                 existUser·p0.9999: 17.452 ms/op
                 existUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311074
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1349 
    [ 1.250,  2.500) = 34659 
    [ 2.500,  3.750) = 242044 
    [ 3.750,  5.000) = 30296 
    [ 5.000,  6.250) = 1601 
    [ 6.250,  7.500) = 654 
    [ 7.500,  8.750) = 220 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 61 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =      8.264 ms/op
     p(99.9900) =     16.466 ms/op
     p(99.9990) =     17.819 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 4.243 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.007 ms/op
Iteration   1: 3.246 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.046 ms/op
                 getUser·p0.999:  7.275 ms/op
                 getUser·p0.9999: 13.943 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 3.236 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   5.019 ms/op
                 getUser·p0.999:  7.489 ms/op
                 getUser·p0.9999: 16.702 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 3.237 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  12.248 ms/op
                 getUser·p0.9999: 17.990 ms/op
                 getUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 296298
  mean =      3.240 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 341 
    [ 1.250,  2.500) = 19409 
    [ 2.500,  3.750) = 225035 
    [ 3.750,  5.000) = 48627 
    [ 5.000,  6.250) = 1835 
    [ 6.250,  7.500) = 610 
    [ 7.500,  8.750) = 147 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      4.981 ms/op
     p(99.9000) =      8.711 ms/op
     p(99.9900) =     17.891 ms/op
     p(99.9990) =     18.353 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 5.815 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.184 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.011 ms/op
Iteration   1: 3.940 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  14.462 ms/op
                 listUser·p0.9999: 20.665 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   2: 4.092 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  20.054 ms/op
                 listUser·p0.9999: 25.467 ms/op
                 listUser·p1.00:   26.345 ms/op

Iteration   3: 3.976 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  16.407 ms/op
                 listUser·p0.9999: 23.853 ms/op
                 listUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239905
  mean =      4.002 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2725 
    [ 2.500,  5.000) = 211039 
    [ 5.000,  7.500) = 24066 
    [ 7.500, 10.000) = 1473 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     15.892 ms/op
     p(99.9900) =     25.134 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.851 ± 1.797  ops/ms
ClientGrpc.existUser                       thrpt       3  10.698 ± 2.171  ops/ms
ClientGrpc.getUser                         thrpt       3  10.223 ± 1.556  ops/ms
ClientGrpc.listUser                        thrpt       3   7.964 ± 1.153  ops/ms
ClientGrpc.createUser                       avgt       3   3.197 ± 0.275   ms/op
ClientGrpc.existUser                        avgt       3   3.039 ± 1.041   ms/op
ClientGrpc.getUser                          avgt       3   3.204 ± 0.937   ms/op
ClientGrpc.listUser                         avgt       3   4.065 ± 0.869   ms/op
ClientGrpc.createUser                     sample  296327   3.238 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.631           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.174           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.186           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.513           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.272           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.542           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.054           ms/op
ClientGrpc.existUser                      sample  311074   3.087 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.508           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.056           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.977           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.833           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.264           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.466           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.957           ms/op
ClientGrpc.getUser                        sample  296298   3.240 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.735           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.203           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.940           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.145           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.981           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.711           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.891           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.612           ms/op
ClientGrpc.listUser                       sample  239905   4.002 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.892           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.332           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.892           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.134           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.345           ms/op
