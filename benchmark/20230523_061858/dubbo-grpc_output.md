# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.219 ops/ms
# Warmup Iteration   2: 5.196 ops/ms
# Warmup Iteration   3: 7.091 ops/ms
Iteration   1: 7.274 ops/ms
Iteration   2: 7.333 ops/ms
Iteration   3: 7.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.416 ±(99.9%) 3.585 ops/ms [Average]
  (min, avg, max) = (7.274, 7.416, 7.640), stdev = 0.196
  CI (99.9%): [3.831, 11.000] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.216 ops/ms
# Warmup Iteration   2: 6.578 ops/ms
# Warmup Iteration   3: 7.470 ops/ms
Iteration   1: 7.955 ops/ms
Iteration   2: 7.766 ops/ms
Iteration   3: 8.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.926 ±(99.9%) 2.688 ops/ms [Average]
  (min, avg, max) = (7.766, 7.926, 8.057), stdev = 0.147
  CI (99.9%): [5.238, 10.613] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.064 ops/ms
# Warmup Iteration   2: 6.941 ops/ms
# Warmup Iteration   3: 7.325 ops/ms
Iteration   1: 7.585 ops/ms
Iteration   2: 7.833 ops/ms
Iteration   3: 8.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.897 ±(99.9%) 6.342 ops/ms [Average]
  (min, avg, max) = (7.585, 7.897, 8.271), stdev = 0.348
  CI (99.9%): [1.555, 14.238] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.760 ops/ms
# Warmup Iteration   2: 5.532 ops/ms
# Warmup Iteration   3: 5.545 ops/ms
Iteration   1: 5.601 ops/ms
Iteration   2: 5.649 ops/ms
Iteration   3: 5.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.681 ±(99.9%) 1.836 ops/ms [Average]
  (min, avg, max) = (5.601, 5.681, 5.794), stdev = 0.101
  CI (99.9%): [3.845, 7.518] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.413 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.992 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.619 ±(99.9%) 0.002 ms/op
Iteration   1: 4.456 ±(99.9%) 0.004 ms/op
Iteration   2: 4.407 ±(99.9%) 0.003 ms/op
Iteration   3: 4.385 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.416 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (4.385, 4.416, 4.456), stdev = 0.036
  CI (99.9%): [3.754, 5.078] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.852 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.003 ms/op
Iteration   1: 4.069 ±(99.9%) 0.002 ms/op
Iteration   2: 4.041 ±(99.9%) 0.002 ms/op
Iteration   3: 3.938 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.016 ±(99.9%) 1.253 ms/op [Average]
  (min, avg, max) = (3.938, 4.016, 4.069), stdev = 0.069
  CI (99.9%): [2.763, 5.269] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.451 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.424 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.003 ms/op
Iteration   1: 4.396 ±(99.9%) 0.008 ms/op
Iteration   2: 4.522 ±(99.9%) 0.003 ms/op
Iteration   3: 4.426 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.448 ±(99.9%) 1.206 ms/op [Average]
  (min, avg, max) = (4.396, 4.448, 4.522), stdev = 0.066
  CI (99.9%): [3.242, 5.654] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.869 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.484 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.536 ±(99.9%) 0.034 ms/op
Iteration   1: 5.350 ±(99.9%) 0.014 ms/op
Iteration   2: 5.397 ±(99.9%) 0.013 ms/op
Iteration   3: 5.156 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.301 ±(99.9%) 2.336 ms/op [Average]
  (min, avg, max) = (5.156, 5.301, 5.397), stdev = 0.128
  CI (99.9%): [2.965, 7.638] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.832 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.429 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.261 ±(99.9%) 0.013 ms/op
Iteration   1: 4.185 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   4.030 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   6.136 ms/op
                 createUser·p0.99:   8.208 ms/op
                 createUser·p0.999:  11.944 ms/op
                 createUser·p0.9999: 14.965 ms/op
                 createUser·p1.00:   15.598 ms/op

Iteration   2: 4.265 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.964 ms/op
                 createUser·p0.99:   7.438 ms/op
                 createUser·p0.999:  12.075 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   3: 4.431 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.718 ms/op
                 createUser·p0.95:   6.373 ms/op
                 createUser·p0.99:   8.524 ms/op
                 createUser·p0.999:  16.381 ms/op
                 createUser·p0.9999: 22.457 ms/op
                 createUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 223607
  mean =      4.291 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5048 
    [ 2.500,  5.000) = 176798 
    [ 5.000,  7.500) = 38423 
    [ 7.500, 10.000) = 2704 
    [10.000, 12.500) = 401 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      4.125 ms/op
     p(90.0000) =      5.530 ms/op
     p(95.0000) =      6.169 ms/op
     p(99.0000) =      8.036 ms/op
     p(99.9000) =     12.638 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     24.583 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.259 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.692 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.495 ±(99.9%) 0.013 ms/op
Iteration   1: 4.452 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.327 ms/op
                 existUser·p0.50:   4.260 ms/op
                 existUser·p0.90:   5.669 ms/op
                 existUser·p0.95:   6.332 ms/op
                 existUser·p0.99:   8.389 ms/op
                 existUser·p0.999:  13.834 ms/op
                 existUser·p0.9999: 17.591 ms/op
                 existUser·p1.00:   34.734 ms/op

Iteration   2: 4.326 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   4.149 ms/op
                 existUser·p0.90:   5.407 ms/op
                 existUser·p0.95:   6.054 ms/op
                 existUser·p0.99:   8.550 ms/op
                 existUser·p0.999:  15.063 ms/op
                 existUser·p0.9999: 20.127 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   3: 4.174 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   4.039 ms/op
                 existUser·p0.90:   5.308 ms/op
                 existUser·p0.95:   5.964 ms/op
                 existUser·p0.99:   7.340 ms/op
                 existUser·p0.999:  10.830 ms/op
                 existUser·p0.9999: 20.316 ms/op
                 existUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 222263
  mean =      4.314 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4451 
    [ 2.500,  5.000) = 178242 
    [ 5.000,  7.500) = 36402 
    [ 7.500, 10.000) = 2443 
    [10.000, 12.500) = 438 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      4.145 ms/op
     p(90.0000) =      5.472 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =      8.056 ms/op
     p(99.9000) =     13.553 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     20.698 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.235 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.934 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.631 ±(99.9%) 0.016 ms/op
Iteration   1: 4.453 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   4.284 ms/op
                 getUser·p0.90:   5.800 ms/op
                 getUser·p0.95:   6.488 ms/op
                 getUser·p0.99:   8.249 ms/op
                 getUser·p0.999:  12.055 ms/op
                 getUser·p0.9999: 17.918 ms/op
                 getUser·p1.00:   18.317 ms/op

Iteration   2: 4.559 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.898 ms/op
                 getUser·p0.95:   6.603 ms/op
                 getUser·p0.99:   9.077 ms/op
                 getUser·p0.999:  13.253 ms/op
                 getUser·p0.9999: 33.554 ms/op
                 getUser·p1.00:   33.751 ms/op

Iteration   3: 4.809 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   4.555 ms/op
                 getUser·p0.90:   6.341 ms/op
                 getUser·p0.95:   7.225 ms/op
                 getUser·p0.99:   9.667 ms/op
                 getUser·p0.999:  15.349 ms/op
                 getUser·p0.9999: 32.899 ms/op
                 getUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 208512
  mean =      4.602 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3547 
    [ 2.500,  5.000) = 145858 
    [ 5.000,  7.500) = 53135 
    [ 7.500, 10.000) = 4815 
    [10.000, 12.500) = 782 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      6.775 ms/op
     p(99.0000) =      9.025 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     33.133 ms/op
     p(99.9990) =     33.745 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.001 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 6.134 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.647 ±(99.9%) 0.020 ms/op
Iteration   1: 5.620 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.892 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   11.256 ms/op
                 listUser·p0.999:  19.103 ms/op
                 listUser·p0.9999: 22.462 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   2: 5.530 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.653 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.158 ms/op
                 listUser·p0.999:  16.908 ms/op
                 listUser·p0.9999: 28.810 ms/op
                 listUser·p1.00:   32.834 ms/op

Iteration   3: 5.335 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   6.996 ms/op
                 listUser·p0.95:   8.045 ms/op
                 listUser·p0.99:   10.699 ms/op
                 listUser·p0.999:  26.706 ms/op
                 listUser·p0.9999: 32.048 ms/op
                 listUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 174776
  mean =      5.492 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 241 
    [ 2.500,  5.000) = 74231 
    [ 5.000,  7.500) = 85020 
    [ 7.500, 10.000) = 12299 
    [10.000, 12.500) = 2058 
    [12.500, 15.000) = 466 
    [15.000, 17.500) = 226 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      7.283 ms/op
     p(95.0000) =      8.324 ms/op
     p(99.0000) =     11.076 ms/op
     p(99.9000) =     19.530 ms/op
     p(99.9900) =     31.410 ms/op
     p(99.9990) =     33.260 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.416 ± 3.585  ops/ms
ClientGrpc.existUser                       thrpt       3   7.926 ± 2.688  ops/ms
ClientGrpc.getUser                         thrpt       3   7.897 ± 6.342  ops/ms
ClientGrpc.listUser                        thrpt       3   5.681 ± 1.836  ops/ms
ClientGrpc.createUser                       avgt       3   4.416 ± 0.662   ms/op
ClientGrpc.existUser                        avgt       3   4.016 ± 1.253   ms/op
ClientGrpc.getUser                          avgt       3   4.448 ± 1.206   ms/op
ClientGrpc.listUser                         avgt       3   5.301 ± 2.336   ms/op
ClientGrpc.createUser                     sample  223607   4.291 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.723           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.530           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.169           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.036           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.638           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.151           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.904           ms/op
ClientGrpc.existUser                      sample  222263   4.314 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.918           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.472           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.119           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.056           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.553           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.152           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.734           ms/op
ClientGrpc.getUser                        sample  208512   4.602 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.665           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.021           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.775           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.025           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.926           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.133           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.751           ms/op
ClientGrpc.listUser                       sample  174776   5.492 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.321           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.283           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.324           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.076           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.530           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.410           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.358           ms/op
