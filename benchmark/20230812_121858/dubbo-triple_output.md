# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.206 ops/ms
# Warmup Iteration   2: 4.978 ops/ms
# Warmup Iteration   3: 8.410 ops/ms
Iteration   1: 8.772 ops/ms
Iteration   2: 8.760 ops/ms
Iteration   3: 9.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.878 ±(99.9%) 3.536 ops/ms [Average]
  (min, avg, max) = (8.760, 8.878, 9.101), stdev = 0.194
  CI (99.9%): [5.342, 12.414] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.672 ops/ms
# Warmup Iteration   2: 8.747 ops/ms
# Warmup Iteration   3: 9.601 ops/ms
Iteration   1: 9.604 ops/ms
Iteration   2: 9.394 ops/ms
Iteration   3: 9.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.485 ±(99.9%) 1.963 ops/ms [Average]
  (min, avg, max) = (9.394, 9.485, 9.604), stdev = 0.108
  CI (99.9%): [7.522, 11.448] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.773 ops/ms
# Warmup Iteration   2: 8.411 ops/ms
# Warmup Iteration   3: 9.097 ops/ms
Iteration   1: 9.245 ops/ms
Iteration   2: 9.037 ops/ms
Iteration   3: 9.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.173 ±(99.9%) 2.147 ops/ms [Average]
  (min, avg, max) = (9.037, 9.173, 9.245), stdev = 0.118
  CI (99.9%): [7.026, 11.320] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.790 ops/ms
# Warmup Iteration   2: 7.271 ops/ms
# Warmup Iteration   3: 7.701 ops/ms
Iteration   1: 7.995 ops/ms
Iteration   2: 8.054 ops/ms
Iteration   3: 7.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.941 ±(99.9%) 2.708 ops/ms [Average]
  (min, avg, max) = (7.773, 7.941, 8.054), stdev = 0.148
  CI (99.9%): [5.233, 10.648] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.759 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.856 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.010 ms/op
Iteration   1: 3.560 ±(99.9%) 0.005 ms/op
Iteration   2: 3.534 ±(99.9%) 0.002 ms/op
Iteration   3: 3.421 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.505 ±(99.9%) 1.347 ms/op [Average]
  (min, avg, max) = (3.421, 3.505, 3.560), stdev = 0.074
  CI (99.9%): [2.158, 4.852] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.126 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.006 ms/op
Iteration   1: 3.346 ±(99.9%) 0.004 ms/op
Iteration   2: 3.357 ±(99.9%) 0.010 ms/op
Iteration   3: 3.361 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.355 ±(99.9%) 0.140 ms/op [Average]
  (min, avg, max) = (3.346, 3.355, 3.361), stdev = 0.008
  CI (99.9%): [3.215, 3.495] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 10.049 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.006 ms/op
Iteration   1: 3.581 ±(99.9%) 0.002 ms/op
Iteration   2: 3.437 ±(99.9%) 0.005 ms/op
Iteration   3: 3.392 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.470 ±(99.9%) 1.804 ms/op [Average]
  (min, avg, max) = (3.392, 3.470, 3.581), stdev = 0.099
  CI (99.9%): [1.666, 5.273] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.935 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.389 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.287 ±(99.9%) 0.007 ms/op
Iteration   1: 4.061 ±(99.9%) 0.014 ms/op
Iteration   2: 4.148 ±(99.9%) 0.011 ms/op
Iteration   3: 4.112 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.107 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (4.061, 4.107, 4.148), stdev = 0.044
  CI (99.9%): [3.306, 4.908] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.265 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.010 ms/op
Iteration   1: 3.702 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   5.759 ms/op
                 createUser·p0.99:   7.660 ms/op
                 createUser·p0.999:  10.060 ms/op
                 createUser·p0.9999: 29.667 ms/op
                 createUser·p1.00:   30.474 ms/op

Iteration   2: 3.505 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.765 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  24.498 ms/op
                 createUser·p0.9999: 27.844 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   3: 3.501 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  22.513 ms/op
                 createUser·p0.9999: 28.962 ms/op
                 createUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269240
  mean =      3.567 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4703 
    [ 2.500,  5.000) = 252303 
    [ 5.000,  7.500) = 10367 
    [ 7.500, 10.000) = 1383 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 127 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     12.595 ms/op
     p(99.9900) =     29.360 ms/op
     p(99.9990) =     30.265 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.702 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.640 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.009 ms/op
Iteration   1: 3.331 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  19.849 ms/op
                 existUser·p0.9999: 23.855 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   2: 3.343 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   6.988 ms/op
                 existUser·p0.999:  21.293 ms/op
                 existUser·p0.9999: 38.069 ms/op
                 existUser·p1.00:   38.207 ms/op

Iteration   3: 3.391 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.645 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.947 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  17.885 ms/op
                 existUser·p0.9999: 25.199 ms/op
                 existUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285868
  mean =      3.355 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9547 
    [ 2.500,  5.000) = 269457 
    [ 5.000,  7.500) = 5394 
    [ 7.500, 10.000) = 1129 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     17.896 ms/op
     p(99.9900) =     36.989 ms/op
     p(99.9990) =     38.207 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.791 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.701 ±(99.9%) 0.014 ms/op
Iteration   1: 3.405 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.370 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  16.122 ms/op
                 getUser·p0.9999: 25.023 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   2: 3.636 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.604 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  20.939 ms/op
                 getUser·p0.9999: 27.099 ms/op
                 getUser·p1.00:   28.180 ms/op

Iteration   3: 3.455 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  17.662 ms/op
                 getUser·p0.9999: 27.123 ms/op
                 getUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274525
  mean =      3.496 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2495 
    [ 2.500,  5.000) = 261869 
    [ 5.000,  7.500) = 8318 
    [ 7.500, 10.000) = 1287 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     16.695 ms/op
     p(99.9900) =     26.888 ms/op
     p(99.9990) =     28.033 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.519 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.591 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.013 ms/op
Iteration   1: 4.021 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.716 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   8.025 ms/op
                 listUser·p0.999:  19.357 ms/op
                 listUser·p0.9999: 22.742 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   2: 3.935 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  14.778 ms/op
                 listUser·p0.9999: 17.522 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   3: 4.158 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.589 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   7.766 ms/op
                 listUser·p0.999:  14.583 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237877
  mean =      4.036 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 227356 
    [ 5.000,  7.500) = 7982 
    [ 7.500, 10.000) = 1531 
    [10.000, 12.500) = 427 
    [12.500, 15.000) = 268 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.716 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     15.663 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.878 ± 3.536  ops/ms
ClientPb.existUser                       thrpt       3   9.485 ± 1.963  ops/ms
ClientPb.getUser                         thrpt       3   9.173 ± 2.147  ops/ms
ClientPb.listUser                        thrpt       3   7.941 ± 2.708  ops/ms
ClientPb.createUser                       avgt       3   3.505 ± 1.347   ms/op
ClientPb.existUser                        avgt       3   3.355 ± 0.140   ms/op
ClientPb.getUser                          avgt       3   3.470 ± 1.804   ms/op
ClientPb.listUser                         avgt       3   4.107 ± 0.801   ms/op
ClientPb.createUser                     sample  269240   3.567 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.231           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.930           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.595           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.360           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.474           ms/op
ClientPb.existUser                      sample  285868   3.355 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.241           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.447           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.896           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.989           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.207           ms/op
ClientPb.getUser                        sample  274525   3.496 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.358           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.513           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.695           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.888           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.180           ms/op
ClientPb.listUser                       sample  237877   4.036 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.716           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.692           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.663           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.151           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.560           ms/op
