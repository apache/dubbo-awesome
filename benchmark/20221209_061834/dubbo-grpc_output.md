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
# Warmup Iteration   1: 3.851 ops/ms
# Warmup Iteration   2: 8.435 ops/ms
# Warmup Iteration   3: 10.064 ops/ms
Iteration   1: 9.767 ops/ms
Iteration   2: 9.965 ops/ms
Iteration   3: 9.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.808 ±(99.9%) 2.580 ops/ms [Average]
  (min, avg, max) = (9.692, 9.808, 9.965), stdev = 0.141
  CI (99.9%): [7.228, 12.388] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.296 ops/ms
# Warmup Iteration   2: 9.909 ops/ms
# Warmup Iteration   3: 10.262 ops/ms
Iteration   1: 10.204 ops/ms
Iteration   2: 9.973 ops/ms
Iteration   3: 10.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.107 ±(99.9%) 2.194 ops/ms [Average]
  (min, avg, max) = (9.973, 10.107, 10.204), stdev = 0.120
  CI (99.9%): [7.913, 12.302] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.284 ops/ms
# Warmup Iteration   2: 9.577 ops/ms
# Warmup Iteration   3: 9.794 ops/ms
Iteration   1: 9.929 ops/ms
Iteration   2: 9.809 ops/ms
Iteration   3: 10.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.935 ±(99.9%) 2.347 ops/ms [Average]
  (min, avg, max) = (9.809, 9.935, 10.066), stdev = 0.129
  CI (99.9%): [7.588, 12.281] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.097 ops/ms
# Warmup Iteration   2: 7.420 ops/ms
# Warmup Iteration   3: 7.795 ops/ms
Iteration   1: 7.678 ops/ms
Iteration   2: 7.387 ops/ms
Iteration   3: 7.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.546 ±(99.9%) 2.688 ops/ms [Average]
  (min, avg, max) = (7.387, 7.546, 7.678), stdev = 0.147
  CI (99.9%): [4.858, 10.234] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.667 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.316 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.004 ms/op
Iteration   1: 3.281 ±(99.9%) 0.001 ms/op
Iteration   2: 3.269 ±(99.9%) 0.001 ms/op
Iteration   3: 3.261 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.270 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (3.261, 3.270, 3.281), stdev = 0.010
  CI (99.9%): [3.082, 3.458] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.207 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.003 ms/op
Iteration   1: 3.104 ±(99.9%) 0.002 ms/op
Iteration   2: 3.130 ±(99.9%) 0.002 ms/op
Iteration   3: 3.014 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.083 ±(99.9%) 1.108 ms/op [Average]
  (min, avg, max) = (3.014, 3.083, 3.130), stdev = 0.061
  CI (99.9%): [1.975, 4.191] (assumes normal distribution)


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
# Warmup Iteration   1: 4.480 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.004 ms/op
Iteration   1: 3.249 ±(99.9%) 0.002 ms/op
Iteration   2: 3.153 ±(99.9%) 0.003 ms/op
Iteration   3: 3.279 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.227 ±(99.9%) 1.203 ms/op [Average]
  (min, avg, max) = (3.153, 3.227, 3.279), stdev = 0.066
  CI (99.9%): [2.024, 4.429] (assumes normal distribution)


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
# Warmup Iteration   1: 6.293 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.350 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.251 ±(99.9%) 0.037 ms/op
Iteration   1: 4.158 ±(99.9%) 0.021 ms/op
Iteration   2: 4.029 ±(99.9%) 0.007 ms/op
Iteration   3: 4.084 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.090 ±(99.9%) 1.186 ms/op [Average]
  (min, avg, max) = (4.029, 4.090, 4.158), stdev = 0.065
  CI (99.9%): [2.905, 5.276] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.607 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.353 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.006 ms/op
Iteration   1: 3.326 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   4.885 ms/op
                 createUser·p0.999:  9.486 ms/op
                 createUser·p0.9999: 27.806 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   2: 3.324 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.285 ms/op
                 createUser·p0.999:  8.798 ms/op
                 createUser·p0.9999: 22.229 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   3: 3.303 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  11.792 ms/op
                 createUser·p0.9999: 23.790 ms/op
                 createUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 289487
  mean =      3.318 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14117 
    [ 2.500,  5.000) = 272092 
    [ 5.000,  7.500) = 2578 
    [ 7.500, 10.000) = 396 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =     10.797 ms/op
     p(99.9900) =     26.513 ms/op
     p(99.9990) =     28.748 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.474 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
Iteration   1: 3.192 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.783 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.961 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  9.726 ms/op
                 existUser·p0.9999: 15.597 ms/op
                 existUser·p1.00:   16.171 ms/op

Iteration   2: 3.165 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  7.330 ms/op
                 existUser·p0.9999: 18.834 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   3: 3.165 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  11.142 ms/op
                 existUser·p0.9999: 24.737 ms/op
                 existUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 302305
  mean =      3.174 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25964 
    [ 2.500,  5.000) = 274300 
    [ 5.000,  7.500) = 1418 
    [ 7.500, 10.000) = 362 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     23.913 ms/op
     p(99.9990) =     25.065 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 4.446 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.357 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.259 ±(99.9%) 0.008 ms/op
Iteration   1: 3.259 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  7.069 ms/op
                 getUser·p0.9999: 14.512 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   2: 3.333 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   4.767 ms/op
                 getUser·p0.999:  7.938 ms/op
                 getUser·p0.9999: 18.907 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   3: 3.272 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   4.932 ms/op
                 getUser·p0.999:  10.087 ms/op
                 getUser·p0.9999: 18.816 ms/op
                 getUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 292003
  mean =      3.288 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 522 
    [ 1.250,  2.500) = 13216 
    [ 2.500,  3.750) = 222409 
    [ 3.750,  5.000) = 53641 
    [ 5.000,  6.250) = 1377 
    [ 6.250,  7.500) = 401 
    [ 7.500,  8.750) = 208 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 67 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =      8.086 ms/op
     p(99.9900) =     18.743 ms/op
     p(99.9990) =     19.240 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 5.869 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.419 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.013 ms/op
Iteration   1: 4.267 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.516 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  15.626 ms/op
                 listUser·p0.9999: 17.482 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   2: 4.184 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.468 ms/op
                 listUser·p0.999:  18.645 ms/op
                 listUser·p0.9999: 30.870 ms/op
                 listUser·p1.00:   31.654 ms/op

Iteration   3: 4.127 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  17.820 ms/op
                 listUser·p0.9999: 27.171 ms/op
                 listUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 229084
  mean =      4.192 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1754 
    [ 2.500,  5.000) = 193613 
    [ 5.000,  7.500) = 31739 
    [ 7.500, 10.000) = 1368 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     17.102 ms/op
     p(99.9900) =     30.021 ms/op
     p(99.9990) =     31.386 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.808 ± 2.580  ops/ms
ClientGrpc.existUser                       thrpt       3  10.107 ± 2.194  ops/ms
ClientGrpc.getUser                         thrpt       3   9.935 ± 2.347  ops/ms
ClientGrpc.listUser                        thrpt       3   7.546 ± 2.688  ops/ms
ClientGrpc.createUser                       avgt       3   3.270 ± 0.188   ms/op
ClientGrpc.existUser                        avgt       3   3.083 ± 1.108   ms/op
ClientGrpc.getUser                          avgt       3   3.227 ± 1.203   ms/op
ClientGrpc.listUser                         avgt       3   4.090 ± 1.186   ms/op
ClientGrpc.createUser                     sample  289487   3.318 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.702           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.256           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.039           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.120           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.797           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.513           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.901           ms/op
ClientGrpc.existUser                      sample  302305   3.174 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.650           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.142           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.875           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.088           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.694           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.126           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.913           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.166           ms/op
ClientGrpc.getUser                        sample  292003   3.288 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.784           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.256           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.990           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.817           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.086           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.743           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.431           ms/op
ClientGrpc.listUser                       sample  229084   4.192 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.922           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.981           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.332           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.102           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.021           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.654           ms/op
