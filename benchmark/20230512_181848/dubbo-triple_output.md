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
# Warmup Iteration   1: 2.303 ops/ms
# Warmup Iteration   2: 5.356 ops/ms
# Warmup Iteration   3: 8.512 ops/ms
Iteration   1: 9.104 ops/ms
Iteration   2: 9.448 ops/ms
Iteration   3: 9.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.444 ±(99.9%) 6.166 ops/ms [Average]
  (min, avg, max) = (9.104, 9.444, 9.780), stdev = 0.338
  CI (99.9%): [3.279, 15.610] (assumes normal distribution)


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
# Warmup Iteration   1: 3.153 ops/ms
# Warmup Iteration   2: 8.692 ops/ms
# Warmup Iteration   3: 9.828 ops/ms
Iteration   1: 10.211 ops/ms
Iteration   2: 10.109 ops/ms
Iteration   3: 9.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.060 ±(99.9%) 3.283 ops/ms [Average]
  (min, avg, max) = (9.861, 10.060, 10.211), stdev = 0.180
  CI (99.9%): [6.777, 13.343] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.131 ops/ms
# Warmup Iteration   2: 8.847 ops/ms
# Warmup Iteration   3: 9.234 ops/ms
Iteration   1: 9.374 ops/ms
Iteration   2: 9.111 ops/ms
Iteration   3: 9.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.315 ±(99.9%) 3.329 ops/ms [Average]
  (min, avg, max) = (9.111, 9.315, 9.461), stdev = 0.182
  CI (99.9%): [5.986, 12.644] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.741 ops/ms
# Warmup Iteration   2: 7.618 ops/ms
# Warmup Iteration   3: 8.159 ops/ms
Iteration   1: 8.067 ops/ms
Iteration   2: 8.343 ops/ms
Iteration   3: 8.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.276 ±(99.9%) 3.388 ops/ms [Average]
  (min, avg, max) = (8.067, 8.276, 8.419), stdev = 0.186
  CI (99.9%): [4.889, 11.664] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.033 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.006 ms/op
Iteration   1: 3.363 ±(99.9%) 0.009 ms/op
Iteration   2: 3.303 ±(99.9%) 0.013 ms/op
Iteration   3: 3.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.392 ±(99.9%) 1.928 ms/op [Average]
  (min, avg, max) = (3.303, 3.392, 3.509), stdev = 0.106
  CI (99.9%): [1.464, 5.320] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.989 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.003 ms/op
Iteration   1: 3.186 ±(99.9%) 0.006 ms/op
Iteration   2: 3.134 ±(99.9%) 0.006 ms/op
Iteration   3: 3.177 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.166 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (3.134, 3.166, 3.186), stdev = 0.028
  CI (99.9%): [2.663, 3.669] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.995 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.005 ms/op
Iteration   1: 3.357 ±(99.9%) 0.005 ms/op
Iteration   2: 3.378 ±(99.9%) 0.008 ms/op
Iteration   3: 3.319 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.351 ±(99.9%) 0.547 ms/op [Average]
  (min, avg, max) = (3.319, 3.351, 3.378), stdev = 0.030
  CI (99.9%): [2.805, 3.898] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.376 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.010 ms/op
Iteration   1: 3.942 ±(99.9%) 0.009 ms/op
Iteration   2: 3.856 ±(99.9%) 0.014 ms/op
Iteration   3: 3.806 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.868 ±(99.9%) 1.261 ms/op [Average]
  (min, avg, max) = (3.806, 3.868, 3.942), stdev = 0.069
  CI (99.9%): [2.608, 5.129] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.627 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.012 ms/op
Iteration   1: 3.228 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.210 ms/op
                 createUser·p0.999:  14.189 ms/op
                 createUser·p0.9999: 21.925 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   2: 3.432 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  21.029 ms/op
                 createUser·p0.9999: 25.429 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   3: 3.291 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.278 ms/op
                 createUser·p0.999:  19.149 ms/op
                 createUser·p0.9999: 26.977 ms/op
                 createUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289557
  mean =      3.315 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8621 
    [ 2.500,  5.000) = 275878 
    [ 5.000,  7.500) = 4049 
    [ 7.500, 10.000) = 569 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 70 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     26.085 ms/op
     p(99.9990) =     27.594 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 8.372 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.009 ms/op
Iteration   1: 3.160 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.698 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  10.174 ms/op
                 existUser·p0.9999: 21.459 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  11.298 ms/op
                 existUser·p0.9999: 25.431 ms/op
                 existUser·p1.00:   26.477 ms/op

Iteration   3: 3.192 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.345 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  12.648 ms/op
                 existUser·p0.9999: 25.854 ms/op
                 existUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300268
  mean =      3.193 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15670 
    [ 2.500,  5.000) = 279824 
    [ 5.000,  7.500) = 3933 
    [ 7.500, 10.000) = 413 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     12.502 ms/op
     p(99.9900) =     25.295 ms/op
     p(99.9990) =     26.378 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 7.771 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.433 ±(99.9%) 0.011 ms/op
Iteration   1: 3.430 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  19.781 ms/op
                 getUser·p0.9999: 28.049 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   2: 3.393 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  21.516 ms/op
                 getUser·p0.9999: 25.227 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   3: 3.468 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.419 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  17.138 ms/op
                 getUser·p0.9999: 22.807 ms/op
                 getUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279719
  mean =      3.430 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8570 
    [ 2.500,  5.000) = 258023 
    [ 5.000,  7.500) = 11936 
    [ 7.500, 10.000) = 865 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     17.311 ms/op
     p(99.9900) =     27.101 ms/op
     p(99.9990) =     29.170 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 9.445 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.321 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.012 ms/op
Iteration   1: 4.070 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.520 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  18.186 ms/op
                 listUser·p0.9999: 23.757 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   2: 4.012 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 18.229 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.947 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239243
  mean =      4.009 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 230241 
    [ 5.000,  7.500) = 6710 
    [ 7.500, 10.000) = 1495 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.520 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     16.269 ms/op
     p(99.9900) =     22.292 ms/op
     p(99.9990) =     24.616 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.444 ± 6.166  ops/ms
ClientPb.existUser                       thrpt       3  10.060 ± 3.283  ops/ms
ClientPb.getUser                         thrpt       3   9.315 ± 3.329  ops/ms
ClientPb.listUser                        thrpt       3   8.276 ± 3.388  ops/ms
ClientPb.createUser                       avgt       3   3.392 ± 1.928   ms/op
ClientPb.existUser                        avgt       3   3.166 ± 0.503   ms/op
ClientPb.getUser                          avgt       3   3.351 ± 0.547   ms/op
ClientPb.listUser                         avgt       3   3.868 ± 1.261   ms/op
ClientPb.createUser                     sample  289557   3.315 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.945           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.157           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.514           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.085           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.656           ms/op
ClientPb.existUser                      sample  300268   3.193 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.345           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.502           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.295           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.542           ms/op
ClientPb.getUser                        sample  279719   3.430 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.966           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.841           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.554           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.311           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.101           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.360           ms/op
ClientPb.listUser                       sample  239243   4.009 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.520           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.397           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.269           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.292           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.707           ms/op
