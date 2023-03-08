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
# Warmup Iteration   1: 4.210 ops/ms
# Warmup Iteration   2: 8.742 ops/ms
# Warmup Iteration   3: 9.799 ops/ms
Iteration   1: 10.024 ops/ms
Iteration   2: 9.772 ops/ms
Iteration   3: 9.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.862 ±(99.9%) 2.564 ops/ms [Average]
  (min, avg, max) = (9.772, 9.862, 10.024), stdev = 0.141
  CI (99.9%): [7.298, 12.427] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.848 ops/ms
# Warmup Iteration   2: 9.816 ops/ms
# Warmup Iteration   3: 10.333 ops/ms
Iteration   1: 10.206 ops/ms
Iteration   2: 10.566 ops/ms
Iteration   3: 10.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.377 ±(99.9%) 3.289 ops/ms [Average]
  (min, avg, max) = (10.206, 10.377, 10.566), stdev = 0.180
  CI (99.9%): [7.088, 13.666] (assumes normal distribution)


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
# Warmup Iteration   1: 7.195 ops/ms
# Warmup Iteration   2: 9.810 ops/ms
# Warmup Iteration   3: 9.972 ops/ms
Iteration   1: 9.813 ops/ms
Iteration   2: 10.046 ops/ms
Iteration   3: 9.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.949 ±(99.9%) 2.216 ops/ms [Average]
  (min, avg, max) = (9.813, 9.949, 10.046), stdev = 0.121
  CI (99.9%): [7.734, 12.165] (assumes normal distribution)


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
# Warmup Iteration   1: 5.397 ops/ms
# Warmup Iteration   2: 7.515 ops/ms
# Warmup Iteration   3: 7.767 ops/ms
Iteration   1: 8.147 ops/ms
Iteration   2: 8.071 ops/ms
Iteration   3: 7.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.007 ±(99.9%) 3.278 ops/ms [Average]
  (min, avg, max) = (7.805, 8.007, 8.147), stdev = 0.180
  CI (99.9%): [4.730, 11.285] (assumes normal distribution)


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
# Warmup Iteration   1: 4.607 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.003 ms/op
Iteration   1: 3.226 ±(99.9%) 0.002 ms/op
Iteration   2: 3.259 ±(99.9%) 0.001 ms/op
Iteration   3: 3.323 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.269 ±(99.9%) 0.895 ms/op [Average]
  (min, avg, max) = (3.226, 3.269, 3.323), stdev = 0.049
  CI (99.9%): [2.374, 4.165] (assumes normal distribution)


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
# Warmup Iteration   1: 4.291 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.002 ms/op
Iteration   1: 3.097 ±(99.9%) 0.002 ms/op
Iteration   2: 3.060 ±(99.9%) 0.002 ms/op
Iteration   3: 3.042 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.066 ±(99.9%) 0.517 ms/op [Average]
  (min, avg, max) = (3.042, 3.066, 3.097), stdev = 0.028
  CI (99.9%): [2.550, 3.583] (assumes normal distribution)


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
# Warmup Iteration   1: 4.380 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.002 ms/op
Iteration   1: 3.172 ±(99.9%) 0.004 ms/op
Iteration   2: 3.171 ±(99.9%) 0.001 ms/op
Iteration   3: 3.230 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.191 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (3.171, 3.191, 3.230), stdev = 0.034
  CI (99.9%): [2.574, 3.808] (assumes normal distribution)


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
# Warmup Iteration   1: 5.732 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.278 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.126 ±(99.9%) 0.030 ms/op
Iteration   1: 4.037 ±(99.9%) 0.010 ms/op
Iteration   2: 3.981 ±(99.9%) 0.010 ms/op
Iteration   3: 4.077 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.032 ±(99.9%) 0.876 ms/op [Average]
  (min, avg, max) = (3.981, 4.032, 4.077), stdev = 0.048
  CI (99.9%): [3.156, 4.907] (assumes normal distribution)


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
# Warmup Iteration   1: 4.574 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.007 ms/op
Iteration   1: 3.078 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  9.570 ms/op
                 createUser·p0.9999: 19.045 ms/op
                 createUser·p1.00:   19.595 ms/op

Iteration   2: 3.259 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  10.581 ms/op
                 createUser·p0.9999: 13.460 ms/op
                 createUser·p1.00:   13.926 ms/op

Iteration   3: 3.211 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.294 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  6.781 ms/op
                 createUser·p0.9999: 17.713 ms/op
                 createUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301672
  mean =      3.181 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 458 
    [ 1.250,  2.500) = 18679 
    [ 2.500,  3.750) = 245422 
    [ 3.750,  5.000) = 35322 
    [ 5.000,  6.250) = 852 
    [ 6.250,  7.500) = 349 
    [ 7.500,  8.750) = 170 
    [ 8.750, 10.000) = 133 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.294 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      9.852 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     19.431 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 4.090 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.006 ms/op
Iteration   1: 3.088 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  7.660 ms/op
                 existUser·p0.9999: 14.795 ms/op
                 existUser·p1.00:   15.270 ms/op

Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.957 ms/op
                 existUser·p0.9999: 15.960 ms/op
                 existUser·p1.00:   16.450 ms/op

Iteration   3: 3.142 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  10.174 ms/op
                 existUser·p0.9999: 16.433 ms/op
                 existUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 309828
  mean =      3.099 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 813 
    [ 1.250,  2.500) = 32111 
    [ 2.500,  3.750) = 243526 
    [ 3.750,  5.000) = 32236 
    [ 5.000,  6.250) = 564 
    [ 6.250,  7.500) = 174 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      9.456 ms/op
     p(99.9900) =     15.811 ms/op
     p(99.9990) =     17.134 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 4.531 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.355 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.007 ms/op
Iteration   1: 3.168 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.332 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  10.127 ms/op
                 getUser·p0.9999: 25.199 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   2: 3.133 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.426 ms/op
                 getUser·p0.9999: 23.619 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   3: 3.182 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  8.202 ms/op
                 getUser·p0.9999: 36.630 ms/op
                 getUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303464
  mean =      3.161 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20983 
    [ 2.500,  5.000) = 281286 
    [ 5.000,  7.500) = 792 
    [ 7.500, 10.000) = 204 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.332 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     35.301 ms/op
     p(99.9990) =     37.091 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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
# Warmup Iteration   1: 5.910 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.236 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.251 ±(99.9%) 0.014 ms/op
Iteration   1: 4.010 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.389 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  13.526 ms/op
                 listUser·p0.9999: 20.776 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   2: 3.968 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.670 ms/op
                 listUser·p0.9999: 21.985 ms/op
                 listUser·p1.00:   30.114 ms/op

Iteration   3: 3.946 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.559 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  17.498 ms/op
                 listUser·p0.9999: 24.930 ms/op
                 listUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241372
  mean =      3.975 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2369 
    [ 2.500,  5.000) = 216963 
    [ 5.000,  7.500) = 20771 
    [ 7.500, 10.000) = 857 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.924 ms/op
     p(99.9000) =     14.281 ms/op
     p(99.9900) =     23.916 ms/op
     p(99.9990) =     30.013 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.862 ± 2.564  ops/ms
ClientGrpc.existUser                       thrpt       3  10.377 ± 3.289  ops/ms
ClientGrpc.getUser                         thrpt       3   9.949 ± 2.216  ops/ms
ClientGrpc.listUser                        thrpt       3   8.007 ± 3.278  ops/ms
ClientGrpc.createUser                       avgt       3   3.269 ± 0.895   ms/op
ClientGrpc.existUser                        avgt       3   3.066 ± 0.517   ms/op
ClientGrpc.getUser                          avgt       3   3.191 ± 0.617   ms/op
ClientGrpc.listUser                         avgt       3   4.032 ± 0.876   ms/op
ClientGrpc.createUser                     sample  301672   3.181 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.294           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.138           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.047           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.852           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.383           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.595           ms/op
ClientGrpc.existUser                      sample  309828   3.099 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.715           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.080           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.772           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.949           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.456           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.811           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.170           ms/op
ClientGrpc.getUser                        sample  303464   3.161 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.332           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.002           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.569           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          35.301           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          37.159           ms/op
ClientGrpc.listUser                       sample  241372   3.975 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.887           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.924           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.281           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.916           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.114           ms/op
