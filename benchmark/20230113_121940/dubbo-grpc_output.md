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
# Warmup Iteration   1: 3.119 ops/ms
# Warmup Iteration   2: 7.001 ops/ms
# Warmup Iteration   3: 8.484 ops/ms
Iteration   1: 8.401 ops/ms
Iteration   2: 8.166 ops/ms
Iteration   3: 7.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.138 ±(99.9%) 5.078 ops/ms [Average]
  (min, avg, max) = (7.846, 8.138, 8.401), stdev = 0.278
  CI (99.9%): [3.059, 13.216] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.549 ops/ms
# Warmup Iteration   2: 7.633 ops/ms
# Warmup Iteration   3: 7.948 ops/ms
Iteration   1: 8.322 ops/ms
Iteration   2: 8.272 ops/ms
Iteration   3: 8.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.347 ±(99.9%) 1.634 ops/ms [Average]
  (min, avg, max) = (8.272, 8.347, 8.446), stdev = 0.090
  CI (99.9%): [6.713, 9.980] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.805 ops/ms
# Warmup Iteration   2: 7.324 ops/ms
# Warmup Iteration   3: 8.318 ops/ms
Iteration   1: 8.305 ops/ms
Iteration   2: 8.146 ops/ms
Iteration   3: 8.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.259 ±(99.9%) 1.794 ops/ms [Average]
  (min, avg, max) = (8.146, 8.259, 8.325), stdev = 0.098
  CI (99.9%): [6.465, 10.052] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.203 ops/ms
# Warmup Iteration   2: 6.246 ops/ms
# Warmup Iteration   3: 6.713 ops/ms
Iteration   1: 6.535 ops/ms
Iteration   2: 6.625 ops/ms
Iteration   3: 6.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.426 ±(99.9%) 4.936 ops/ms [Average]
  (min, avg, max) = (6.118, 6.426, 6.625), stdev = 0.271
  CI (99.9%): [1.490, 11.362] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.741 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.003 ms/op
Iteration   1: 4.125 ±(99.9%) 0.003 ms/op
Iteration   2: 4.002 ±(99.9%) 0.003 ms/op
Iteration   3: 4.046 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.058 ±(99.9%) 1.139 ms/op [Average]
  (min, avg, max) = (4.002, 4.058, 4.125), stdev = 0.062
  CI (99.9%): [2.919, 5.197] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.478 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.002 ms/op
Iteration   1: 3.916 ±(99.9%) 0.003 ms/op
Iteration   2: 4.068 ±(99.9%) 0.003 ms/op
Iteration   3: 3.903 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.962 ±(99.9%) 1.674 ms/op [Average]
  (min, avg, max) = (3.903, 3.962, 4.068), stdev = 0.092
  CI (99.9%): [2.288, 5.636] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.589 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.088 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.005 ms/op
Iteration   1: 4.102 ±(99.9%) 0.003 ms/op
Iteration   2: 4.208 ±(99.9%) 0.002 ms/op
Iteration   3: 4.235 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.182 ±(99.9%) 1.282 ms/op [Average]
  (min, avg, max) = (4.102, 4.182, 4.235), stdev = 0.070
  CI (99.9%): [2.900, 5.464] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.996 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.878 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.136 ±(99.9%) 0.021 ms/op
Iteration   1: 4.967 ±(99.9%) 0.013 ms/op
Iteration   2: 4.987 ±(99.9%) 0.008 ms/op
Iteration   3: 5.033 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.996 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (4.967, 4.996, 5.033), stdev = 0.033
  CI (99.9%): [4.385, 5.606] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.247 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.365 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.203 ±(99.9%) 0.012 ms/op
Iteration   1: 3.985 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  14.443 ms/op
                 createUser·p0.9999: 18.512 ms/op
                 createUser·p1.00:   19.104 ms/op

Iteration   2: 3.824 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  11.862 ms/op
                 createUser·p0.9999: 16.515 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   3: 3.997 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.964 ms/op
                 createUser·p0.95:   5.317 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  18.939 ms/op
                 createUser·p0.9999: 34.079 ms/op
                 createUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 244055
  mean =      3.933 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7670 
    [ 2.500,  5.000) = 218826 
    [ 5.000,  7.500) = 16346 
    [ 7.500, 10.000) = 735 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     13.105 ms/op
     p(99.9900) =     32.892 ms/op
     p(99.9990) =     34.312 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 5.862 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.009 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.010 ms/op
Iteration   1: 3.945 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.431 ms/op
                 existUser·p0.99:   7.930 ms/op
                 existUser·p0.999:  12.239 ms/op
                 existUser·p0.9999: 26.640 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   2: 3.650 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  10.157 ms/op
                 existUser·p0.9999: 34.290 ms/op
                 existUser·p1.00:   34.931 ms/op

Iteration   3: 3.664 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   3.596 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  11.649 ms/op
                 existUser·p0.9999: 20.423 ms/op
                 existUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 256131
  mean =      3.748 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10889 
    [ 2.500,  5.000) = 229194 
    [ 5.000,  7.500) = 14386 
    [ 7.500, 10.000) = 1109 
    [10.000, 12.500) = 357 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      6.625 ms/op
     p(99.9000) =     11.729 ms/op
     p(99.9900) =     33.416 ms/op
     p(99.9990) =     34.763 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.251 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.011 ms/op
Iteration   1: 4.013 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   5.079 ms/op
                 getUser·p0.95:   5.382 ms/op
                 getUser·p0.99:   6.186 ms/op
                 getUser·p0.999:  10.052 ms/op
                 getUser·p0.9999: 17.992 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   2: 3.980 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.997 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  9.803 ms/op
                 getUser·p0.9999: 19.661 ms/op
                 getUser·p1.00:   20.152 ms/op

Iteration   3: 4.113 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.361 ms/op
                 getUser·p0.50:   4.035 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  13.089 ms/op
                 getUser·p0.9999: 33.314 ms/op
                 getUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 237791
  mean =      4.034 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5064 
    [ 2.500,  5.000) = 204198 
    [ 5.000,  7.500) = 27466 
    [ 7.500, 10.000) = 696 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.361 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     11.321 ms/op
     p(99.9900) =     28.483 ms/op
     p(99.9990) =     33.456 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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
# Warmup Iteration   1: 7.539 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.500 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.020 ±(99.9%) 0.016 ms/op
Iteration   1: 5.062 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   4.850 ms/op
                 listUser·p0.90:   6.504 ms/op
                 listUser·p0.95:   7.217 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 17.096 ms/op
                 listUser·p1.00:   17.465 ms/op

Iteration   2: 5.052 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.546 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.488 ms/op
                 listUser·p0.95:   7.283 ms/op
                 listUser·p0.99:   9.487 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 18.722 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   3: 5.018 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.234 ms/op
                 listUser·p0.95:   7.119 ms/op
                 listUser·p0.99:   9.404 ms/op
                 listUser·p0.999:  29.172 ms/op
                 listUser·p0.9999: 35.103 ms/op
                 listUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 190176
  mean =      5.044 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 316 
    [ 2.500,  5.000) = 110896 
    [ 5.000,  7.500) = 71701 
    [ 7.500, 10.000) = 5878 
    [10.000, 12.500) = 759 
    [12.500, 15.000) = 306 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.423 ms/op
     p(95.0000) =      7.209 ms/op
     p(99.0000) =      9.404 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     33.684 ms/op
     p(99.9990) =     35.199 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.138 ± 5.078  ops/ms
ClientGrpc.existUser                       thrpt       3   8.347 ± 1.634  ops/ms
ClientGrpc.getUser                         thrpt       3   8.259 ± 1.794  ops/ms
ClientGrpc.listUser                        thrpt       3   6.426 ± 4.936  ops/ms
ClientGrpc.createUser                       avgt       3   4.058 ± 1.139   ms/op
ClientGrpc.existUser                        avgt       3   3.962 ± 1.674   ms/op
ClientGrpc.getUser                          avgt       3   4.182 ± 1.282   ms/op
ClientGrpc.listUser                         avgt       3   4.996 ± 0.611   ms/op
ClientGrpc.createUser                     sample  244055   3.933 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.879           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.210           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.373           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.105           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.892           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.406           ms/op
ClientGrpc.existUser                      sample  256131   3.748 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.696           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.768           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.112           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.625           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.729           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.416           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.931           ms/op
ClientGrpc.getUser                        sample  237791   4.034 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.361           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.087           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.390           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.308           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.321           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.483           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.489           ms/op
ClientGrpc.listUser                       sample  190176   5.044 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.223           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.423           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.209           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.404           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.170           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.684           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.258           ms/op
