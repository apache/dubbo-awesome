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
# Warmup Iteration   1: 3.908 ops/ms
# Warmup Iteration   2: 8.498 ops/ms
# Warmup Iteration   3: 9.894 ops/ms
Iteration   1: 9.870 ops/ms
Iteration   2: 10.277 ops/ms
Iteration   3: 10.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.057 ±(99.9%) 3.756 ops/ms [Average]
  (min, avg, max) = (9.870, 10.057, 10.277), stdev = 0.206
  CI (99.9%): [6.301, 13.813] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.450 ops/ms
# Warmup Iteration   2: 10.069 ops/ms
# Warmup Iteration   3: 10.303 ops/ms
Iteration   1: 10.361 ops/ms
Iteration   2: 10.435 ops/ms
Iteration   3: 10.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.401 ±(99.9%) 0.686 ops/ms [Average]
  (min, avg, max) = (10.361, 10.401, 10.435), stdev = 0.038
  CI (99.9%): [9.715, 11.087] (assumes normal distribution)


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
# Warmup Iteration   1: 6.531 ops/ms
# Warmup Iteration   2: 9.705 ops/ms
# Warmup Iteration   3: 9.752 ops/ms
Iteration   1: 9.894 ops/ms
Iteration   2: 9.988 ops/ms
Iteration   3: 10.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.049 ±(99.9%) 3.512 ops/ms [Average]
  (min, avg, max) = (9.894, 10.049, 10.264), stdev = 0.193
  CI (99.9%): [6.536, 13.561] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.091 ops/ms
# Warmup Iteration   2: 7.655 ops/ms
# Warmup Iteration   3: 7.888 ops/ms
Iteration   1: 8.104 ops/ms
Iteration   2: 7.719 ops/ms
Iteration   3: 7.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.894 ±(99.9%) 3.549 ops/ms [Average]
  (min, avg, max) = (7.719, 7.894, 8.104), stdev = 0.195
  CI (99.9%): [4.345, 11.443] (assumes normal distribution)


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
# Warmup Iteration   1: 4.579 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.277 ±(99.9%) 0.011 ms/op
Iteration   1: 3.114 ±(99.9%) 0.004 ms/op
Iteration   2: 3.216 ±(99.9%) 0.001 ms/op
Iteration   3: 3.218 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.183 ±(99.9%) 1.082 ms/op [Average]
  (min, avg, max) = (3.114, 3.183, 3.218), stdev = 0.059
  CI (99.9%): [2.101, 4.265] (assumes normal distribution)


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.003 ms/op
Iteration   1: 3.063 ±(99.9%) 0.002 ms/op
Iteration   2: 3.114 ±(99.9%) 0.001 ms/op
Iteration   3: 2.962 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.046 ±(99.9%) 1.418 ms/op [Average]
  (min, avg, max) = (2.962, 3.046, 3.114), stdev = 0.078
  CI (99.9%): [1.628, 4.465] (assumes normal distribution)


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
# Warmup Iteration   1: 4.430 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.002 ms/op
Iteration   1: 3.163 ±(99.9%) 0.002 ms/op
Iteration   2: 3.232 ±(99.9%) 0.002 ms/op
Iteration   3: 3.200 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.198 ±(99.9%) 0.637 ms/op [Average]
  (min, avg, max) = (3.163, 3.198, 3.232), stdev = 0.035
  CI (99.9%): [2.561, 3.836] (assumes normal distribution)


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
# Warmup Iteration   1: 5.066 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.316 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.014 ms/op
Iteration   1: 4.031 ±(99.9%) 0.005 ms/op
Iteration   2: 3.966 ±(99.9%) 0.018 ms/op
Iteration   3: 3.946 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.981 ±(99.9%) 0.805 ms/op [Average]
  (min, avg, max) = (3.946, 3.981, 4.031), stdev = 0.044
  CI (99.9%): [3.176, 4.787] (assumes normal distribution)


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
# Warmup Iteration   1: 4.362 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.007 ms/op
Iteration   1: 3.184 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.049 ms/op
                 createUser·p0.9999: 32.369 ms/op
                 createUser·p1.00:   33.096 ms/op

Iteration   2: 3.193 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.025 ms/op
                 createUser·p0.9999: 19.005 ms/op
                 createUser·p1.00:   19.497 ms/op

Iteration   3: 3.310 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  8.949 ms/op
                 createUser·p0.9999: 35.652 ms/op
                 createUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 297273
  mean =      3.228 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19491 
    [ 2.500,  5.000) = 276469 
    [ 5.000,  7.500) = 1036 
    [ 7.500, 10.000) = 75 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      7.283 ms/op
     p(99.9900) =     34.359 ms/op
     p(99.9990) =     36.700 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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
# Warmup Iteration   1: 4.005 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.006 ms/op
Iteration   1: 3.131 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.279 ms/op
                 existUser·p0.999:  6.824 ms/op
                 existUser·p0.9999: 17.596 ms/op
                 existUser·p1.00:   17.629 ms/op

Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   3.945 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.565 ms/op
                 existUser·p0.9999: 20.459 ms/op
                 existUser·p1.00:   21.332 ms/op

Iteration   3: 3.139 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  8.654 ms/op
                 existUser·p0.9999: 23.431 ms/op
                 existUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 307375
  mean =      3.121 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31482 
    [ 2.500,  5.000) = 275101 
    [ 5.000,  7.500) = 528 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.037 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     23.885 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 4.284 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.007 ms/op
Iteration   1: 3.159 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  9.028 ms/op
                 getUser·p0.9999: 13.812 ms/op
                 getUser·p1.00:   15.745 ms/op

Iteration   2: 3.232 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  8.574 ms/op
                 getUser·p0.9999: 15.191 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.602 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  6.611 ms/op
                 getUser·p0.9999: 15.720 ms/op
                 getUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305306
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 620 
    [ 1.250,  2.500) = 19752 
    [ 2.500,  3.750) = 254074 
    [ 3.750,  5.000) = 29469 
    [ 5.000,  6.250) = 717 
    [ 6.250,  7.500) = 313 
    [ 7.500,  8.750) = 127 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.913 ms/op
     p(99.9900) =     15.244 ms/op
     p(99.9990) =     17.264 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 5.531 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.011 ms/op
Iteration   1: 4.165 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   7.371 ms/op
                 listUser·p0.999:  14.468 ms/op
                 listUser·p0.9999: 17.014 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   2: 4.099 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.829 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 26.922 ms/op
                 listUser·p1.00:   27.492 ms/op

Iteration   3: 4.127 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.623 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  19.741 ms/op
                 listUser·p0.9999: 25.764 ms/op
                 listUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232486
  mean =      4.130 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2511 
    [ 2.500,  5.000) = 194685 
    [ 5.000,  7.500) = 33577 
    [ 7.500, 10.000) = 1227 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     15.901 ms/op
     p(99.9900) =     25.616 ms/op
     p(99.9990) =     27.394 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.057 ± 3.756  ops/ms
ClientGrpc.existUser                       thrpt       3  10.401 ± 0.686  ops/ms
ClientGrpc.getUser                         thrpt       3  10.049 ± 3.512  ops/ms
ClientGrpc.listUser                        thrpt       3   7.894 ± 3.549  ops/ms
ClientGrpc.createUser                       avgt       3   3.183 ± 1.082   ms/op
ClientGrpc.existUser                        avgt       3   3.046 ± 1.418   ms/op
ClientGrpc.getUser                          avgt       3   3.198 ± 0.637   ms/op
ClientGrpc.listUser                         avgt       3   3.981 ± 0.805   ms/op
ClientGrpc.createUser                     sample  297273   3.228 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.859           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.191           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.125           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.283           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.359           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.700           ms/op
ClientGrpc.existUser                      sample  307375   3.121 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.643           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.101           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.973           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.037           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.348           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.248           ms/op
ClientGrpc.getUser                        sample  305306   3.143 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.602           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.953           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.913           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.244           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.645           ms/op
ClientGrpc.listUser                       sample  232486   4.130 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.623           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.916           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.358           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.225           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.901           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.616           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.492           ms/op
