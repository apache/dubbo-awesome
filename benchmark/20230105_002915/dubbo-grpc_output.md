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
# Warmup Iteration   1: 2.326 ops/ms
# Warmup Iteration   2: 5.864 ops/ms
# Warmup Iteration   3: 6.997 ops/ms
Iteration   1: 7.454 ops/ms
Iteration   2: 7.407 ops/ms
Iteration   3: 7.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.387 ±(99.9%) 1.445 ops/ms [Average]
  (min, avg, max) = (7.300, 7.387, 7.454), stdev = 0.079
  CI (99.9%): [5.942, 8.832] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.652 ops/ms
# Warmup Iteration   2: 7.418 ops/ms
# Warmup Iteration   3: 7.801 ops/ms
Iteration   1: 7.760 ops/ms
Iteration   2: 8.188 ops/ms
Iteration   3: 8.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.988 ±(99.9%) 3.936 ops/ms [Average]
  (min, avg, max) = (7.760, 7.988, 8.188), stdev = 0.216
  CI (99.9%): [4.052, 11.924] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.133 ops/ms
# Warmup Iteration   2: 6.649 ops/ms
# Warmup Iteration   3: 7.482 ops/ms
Iteration   1: 7.598 ops/ms
Iteration   2: 7.389 ops/ms
Iteration   3: 7.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.505 ±(99.9%) 1.937 ops/ms [Average]
  (min, avg, max) = (7.389, 7.505, 7.598), stdev = 0.106
  CI (99.9%): [5.568, 9.442] (assumes normal distribution)


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
# Warmup Iteration   1: 4.183 ops/ms
# Warmup Iteration   2: 5.687 ops/ms
# Warmup Iteration   3: 5.934 ops/ms
Iteration   1: 5.729 ops/ms
Iteration   2: 5.654 ops/ms
Iteration   3: 5.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.700 ±(99.9%) 0.734 ops/ms [Average]
  (min, avg, max) = (5.654, 5.700, 5.729), stdev = 0.040
  CI (99.9%): [4.967, 6.434] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.366 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.763 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.543 ±(99.9%) 0.022 ms/op
Iteration   1: 4.491 ±(99.9%) 0.004 ms/op
Iteration   2: 4.384 ±(99.9%) 0.005 ms/op
Iteration   3: 4.425 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.434 ±(99.9%) 0.986 ms/op [Average]
  (min, avg, max) = (4.384, 4.434, 4.491), stdev = 0.054
  CI (99.9%): [3.448, 5.419] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.137 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.395 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.005 ms/op
Iteration   1: 4.115 ±(99.9%) 0.005 ms/op
Iteration   2: 4.039 ±(99.9%) 0.005 ms/op
Iteration   3: 3.973 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.042 ±(99.9%) 1.300 ms/op [Average]
  (min, avg, max) = (3.973, 4.042, 4.115), stdev = 0.071
  CI (99.9%): [2.743, 5.342] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.409 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.585 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.329 ±(99.9%) 0.007 ms/op
Iteration   1: 4.147 ±(99.9%) 0.004 ms/op
Iteration   2: 4.228 ±(99.9%) 0.003 ms/op
Iteration   3: 4.166 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.180 ±(99.9%) 0.778 ms/op [Average]
  (min, avg, max) = (4.147, 4.180, 4.228), stdev = 0.043
  CI (99.9%): [3.402, 4.958] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.904 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.844 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.562 ±(99.9%) 0.043 ms/op
Iteration   1: 5.260 ±(99.9%) 0.021 ms/op
Iteration   2: 5.699 ±(99.9%) 0.016 ms/op
Iteration   3: 5.365 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.441 ±(99.9%) 4.175 ms/op [Average]
  (min, avg, max) = (5.260, 5.441, 5.699), stdev = 0.229
  CI (99.9%): [1.266, 9.617] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.833 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.772 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.445 ±(99.9%) 0.014 ms/op
Iteration   1: 4.313 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   4.219 ms/op
                 createUser·p0.90:   5.472 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   6.958 ms/op
                 createUser·p0.999:  9.117 ms/op
                 createUser·p0.9999: 20.906 ms/op
                 createUser·p1.00:   21.463 ms/op

Iteration   2: 4.247 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   4.141 ms/op
                 createUser·p0.90:   5.308 ms/op
                 createUser·p0.95:   5.710 ms/op
                 createUser·p0.99:   7.283 ms/op
                 createUser·p0.999:  13.513 ms/op
                 createUser·p0.9999: 19.545 ms/op
                 createUser·p1.00:   20.120 ms/op

Iteration   3: 4.138 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   4.047 ms/op
                 createUser·p0.90:   5.079 ms/op
                 createUser·p0.95:   5.480 ms/op
                 createUser·p0.99:   6.809 ms/op
                 createUser·p0.999:  13.779 ms/op
                 createUser·p0.9999: 19.768 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 226833
  mean =      4.231 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3637 
    [ 2.500,  5.000) = 187390 
    [ 5.000,  7.500) = 34244 
    [ 7.500, 10.000) = 1110 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      4.129 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      6.993 ms/op
     p(99.9000) =     12.375 ms/op
     p(99.9900) =     19.901 ms/op
     p(99.9990) =     21.338 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.522 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.013 ms/op
Iteration   1: 4.055 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   5.104 ms/op
                 existUser·p0.95:   5.423 ms/op
                 existUser·p0.99:   6.672 ms/op
                 existUser·p0.999:  9.439 ms/op
                 existUser·p0.9999: 19.799 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   2: 3.953 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.997 ms/op
                 existUser·p0.50:   3.887 ms/op
                 existUser·p0.90:   5.022 ms/op
                 existUser·p0.95:   5.349 ms/op
                 existUser·p0.99:   6.741 ms/op
                 existUser·p0.999:  9.375 ms/op
                 existUser·p0.9999: 16.461 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   3: 4.048 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   3.965 ms/op
                 existUser·p0.90:   5.071 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   7.053 ms/op
                 existUser·p0.999:  10.846 ms/op
                 existUser·p0.9999: 18.910 ms/op
                 existUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 238774
  mean =      4.018 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7919 
    [ 2.500,  5.000) = 203872 
    [ 5.000,  7.500) = 25466 
    [ 7.500, 10.000) = 1267 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     10.142 ms/op
     p(99.9900) =     18.780 ms/op
     p(99.9990) =     20.298 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 6.740 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.546 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.325 ±(99.9%) 0.013 ms/op
Iteration   1: 4.160 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   4.043 ms/op
                 getUser·p0.90:   5.104 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   7.499 ms/op
                 getUser·p0.999:  14.057 ms/op
                 getUser·p0.9999: 17.670 ms/op
                 getUser·p1.00:   18.285 ms/op

Iteration   2: 4.193 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   4.084 ms/op
                 getUser·p0.90:   5.292 ms/op
                 getUser·p0.95:   5.767 ms/op
                 getUser·p0.99:   8.004 ms/op
                 getUser·p0.999:  14.002 ms/op
                 getUser·p0.9999: 16.843 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   3: 4.177 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   4.047 ms/op
                 getUser·p0.90:   5.022 ms/op
                 getUser·p0.95:   5.595 ms/op
                 getUser·p0.99:   7.954 ms/op
                 getUser·p0.999:  14.805 ms/op
                 getUser·p0.9999: 20.821 ms/op
                 getUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 229844
  mean =      4.177 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5305 
    [ 2.500,  5.000) = 196108 
    [ 5.000,  7.500) = 25766 
    [ 7.500, 10.000) = 1751 
    [10.000, 12.500) = 506 
    [12.500, 15.000) = 261 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      4.055 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     14.194 ms/op
     p(99.9900) =     19.727 ms/op
     p(99.9990) =     23.256 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 8.071 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.067 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.281 ±(99.9%) 0.021 ms/op
Iteration   1: 5.289 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.479 ms/op
                 listUser·p0.50:   4.981 ms/op
                 listUser·p0.90:   7.217 ms/op
                 listUser·p0.95:   7.946 ms/op
                 listUser·p0.99:   10.131 ms/op
                 listUser·p0.999:  16.878 ms/op
                 listUser·p0.9999: 25.026 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 5.272 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   4.981 ms/op
                 listUser·p0.90:   7.062 ms/op
                 listUser·p0.95:   7.922 ms/op
                 listUser·p0.99:   10.191 ms/op
                 listUser·p0.999:  18.874 ms/op
                 listUser·p0.9999: 27.883 ms/op
                 listUser·p1.00:   28.344 ms/op

Iteration   3: 5.285 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   5.014 ms/op
                 listUser·p0.90:   6.922 ms/op
                 listUser·p0.95:   7.774 ms/op
                 listUser·p0.99:   10.108 ms/op
                 listUser·p0.999:  23.380 ms/op
                 listUser·p0.9999: 35.180 ms/op
                 listUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 181643
  mean =      5.282 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 269 
    [ 2.500,  5.000) = 91148 
    [ 5.000,  7.500) = 77459 
    [ 7.500, 10.000) = 10814 
    [10.000, 12.500) = 1338 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      7.078 ms/op
     p(95.0000) =      7.889 ms/op
     p(99.0000) =     10.142 ms/op
     p(99.9000) =     19.378 ms/op
     p(99.9900) =     28.039 ms/op
     p(99.9990) =     36.200 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.387 ± 1.445  ops/ms
ClientGrpc.existUser                       thrpt       3   7.988 ± 3.936  ops/ms
ClientGrpc.getUser                         thrpt       3   7.505 ± 1.937  ops/ms
ClientGrpc.listUser                        thrpt       3   5.700 ± 0.734  ops/ms
ClientGrpc.createUser                       avgt       3   4.434 ± 0.986   ms/op
ClientGrpc.existUser                        avgt       3   4.042 ± 1.300   ms/op
ClientGrpc.getUser                          avgt       3   4.180 ± 0.778   ms/op
ClientGrpc.listUser                         avgt       3   5.441 ± 4.175   ms/op
ClientGrpc.createUser                     sample  226833   4.231 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.994           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.300           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.718           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.993           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.375           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.901           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.463           ms/op
ClientGrpc.existUser                      sample  238774   4.018 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.769           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.944           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.063           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.399           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.824           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.142           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.780           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.513           ms/op
ClientGrpc.getUser                        sample  229844   4.177 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.883           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.153           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.677           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.799           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.194           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.727           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.855           ms/op
ClientGrpc.listUser                       sample  181643   5.282 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.348           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.889           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.142           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.378           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.039           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.307           ms/op
