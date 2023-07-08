# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.922 ops/ms
# Warmup Iteration   2: 5.616 ops/ms
# Warmup Iteration   3: 8.368 ops/ms
Iteration   1: 9.249 ops/ms
Iteration   2: 9.393 ops/ms
Iteration   3: 9.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.383 ±(99.9%) 2.363 ops/ms [Average]
  (min, avg, max) = (9.249, 9.383, 9.507), stdev = 0.130
  CI (99.9%): [7.020, 11.746] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.089 ops/ms
# Warmup Iteration   2: 8.602 ops/ms
# Warmup Iteration   3: 9.306 ops/ms
Iteration   1: 9.976 ops/ms
Iteration   2: 9.581 ops/ms
Iteration   3: 9.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.652 ±(99.9%) 5.381 ops/ms [Average]
  (min, avg, max) = (9.399, 9.652, 9.976), stdev = 0.295
  CI (99.9%): [4.271, 15.033] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.174 ops/ms
# Warmup Iteration   2: 8.475 ops/ms
# Warmup Iteration   3: 8.884 ops/ms
Iteration   1: 9.289 ops/ms
Iteration   2: 8.913 ops/ms
Iteration   3: 9.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.229 ±(99.9%) 5.287 ops/ms [Average]
  (min, avg, max) = (8.913, 9.229, 9.483), stdev = 0.290
  CI (99.9%): [3.941, 14.516] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.582 ops/ms
# Warmup Iteration   2: 7.145 ops/ms
# Warmup Iteration   3: 7.827 ops/ms
Iteration   1: 8.172 ops/ms
Iteration   2: 7.777 ops/ms
Iteration   3: 7.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.970 ±(99.9%) 3.608 ops/ms [Average]
  (min, avg, max) = (7.777, 7.970, 8.172), stdev = 0.198
  CI (99.9%): [4.362, 11.577] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.595 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.767 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.007 ms/op
Iteration   1: 3.308 ±(99.9%) 0.008 ms/op
Iteration   2: 3.374 ±(99.9%) 0.007 ms/op
Iteration   3: 3.398 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.360 ±(99.9%) 0.854 ms/op [Average]
  (min, avg, max) = (3.308, 3.360, 3.398), stdev = 0.047
  CI (99.9%): [2.506, 4.214] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.223 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.007 ms/op
Iteration   1: 3.289 ±(99.9%) 0.008 ms/op
Iteration   2: 3.230 ±(99.9%) 0.005 ms/op
Iteration   3: 3.253 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.257 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (3.230, 3.257, 3.289), stdev = 0.030
  CI (99.9%): [2.719, 3.796] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.332 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.006 ms/op
Iteration   1: 3.451 ±(99.9%) 0.005 ms/op
Iteration   2: 3.406 ±(99.9%) 0.006 ms/op
Iteration   3: 3.344 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.401 ±(99.9%) 0.986 ms/op [Average]
  (min, avg, max) = (3.344, 3.401, 3.451), stdev = 0.054
  CI (99.9%): [2.414, 4.387] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.100 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.476 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.006 ms/op
Iteration   1: 3.951 ±(99.9%) 0.010 ms/op
Iteration   2: 3.995 ±(99.9%) 0.007 ms/op
Iteration   3: 3.866 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.937 ±(99.9%) 1.200 ms/op [Average]
  (min, avg, max) = (3.866, 3.937, 3.995), stdev = 0.066
  CI (99.9%): [2.737, 5.138] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.000 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.963 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.009 ms/op
Iteration   1: 3.515 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.652 ms/op
                 createUser·p0.999:  19.366 ms/op
                 createUser·p0.9999: 21.955 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   2: 3.436 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.671 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  22.376 ms/op
                 createUser·p0.9999: 24.568 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   3: 3.539 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  17.017 ms/op
                 createUser·p0.9999: 24.935 ms/op
                 createUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274505
  mean =      3.496 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9319 
    [ 2.500,  5.000) = 257655 
    [ 5.000,  7.500) = 6529 
    [ 7.500, 10.000) = 597 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     17.809 ms/op
     p(99.9900) =     24.463 ms/op
     p(99.9990) =     25.609 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.068 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.009 ms/op
Iteration   1: 3.309 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.495 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  12.602 ms/op
                 existUser·p0.9999: 24.149 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   2: 3.378 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  21.476 ms/op
                 existUser·p0.9999: 24.417 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   3: 3.343 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   4.027 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  18.089 ms/op
                 existUser·p0.9999: 25.985 ms/op
                 existUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286981
  mean =      3.343 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10461 
    [ 2.500,  5.000) = 269971 
    [ 5.000,  7.500) = 5561 
    [ 7.500, 10.000) = 473 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.769 ms/op
     p(99.9000) =     18.157 ms/op
     p(99.9900) =     25.569 ms/op
     p(99.9990) =     26.100 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.416 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.010 ms/op
Iteration   1: 3.465 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  12.331 ms/op
                 getUser·p0.9999: 24.585 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   2: 3.412 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.718 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  20.972 ms/op
                 getUser·p0.9999: 26.247 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   3: 3.529 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  22.624 ms/op
                 getUser·p0.9999: 26.700 ms/op
                 getUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276784
  mean =      3.468 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7081 
    [ 2.500,  5.000) = 261257 
    [ 5.000,  7.500) = 7103 
    [ 7.500, 10.000) = 812 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 82 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     15.358 ms/op
     p(99.9900) =     26.170 ms/op
     p(99.9990) =     27.066 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.007 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.114 ±(99.9%) 0.012 ms/op
Iteration   1: 4.021 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  19.051 ms/op
                 listUser·p0.9999: 26.285 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 4.033 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  14.549 ms/op
                 listUser·p0.9999: 16.664 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   3: 3.835 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.293 ms/op
                 listUser·p0.999:  14.599 ms/op
                 listUser·p0.9999: 24.674 ms/op
                 listUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242232
  mean =      3.961 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 233393 
    [ 5.000,  7.500) = 6646 
    [ 7.500, 10.000) = 1260 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 317 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.157 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     25.395 ms/op
     p(99.9990) =     27.230 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.383 ± 2.363  ops/ms
ClientPb.existUser                       thrpt       3   9.652 ± 5.381  ops/ms
ClientPb.getUser                         thrpt       3   9.229 ± 5.287  ops/ms
ClientPb.listUser                        thrpt       3   7.970 ± 3.608  ops/ms
ClientPb.createUser                       avgt       3   3.360 ± 0.854   ms/op
ClientPb.existUser                        avgt       3   3.257 ± 0.539   ms/op
ClientPb.getUser                          avgt       3   3.401 ± 0.986   ms/op
ClientPb.listUser                         avgt       3   3.937 ± 1.200   ms/op
ClientPb.createUser                     sample  274505   3.496 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.167           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.432           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.038           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.809           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.463           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.640           ms/op
ClientPb.existUser                      sample  286981   3.343 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.725           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.301           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.769           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.157           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.569           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.280           ms/op
ClientPb.getUser                        sample  276784   3.468 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.051           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.358           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.170           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.230           ms/op
ClientPb.listUser                       sample  242232   3.961 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.384           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.157           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.155           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.395           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.394           ms/op
