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
# Warmup Iteration   1: 2.562 ops/ms
# Warmup Iteration   2: 5.596 ops/ms
# Warmup Iteration   3: 8.971 ops/ms
Iteration   1: 9.425 ops/ms
Iteration   2: 9.374 ops/ms
Iteration   3: 9.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.488 ±(99.9%) 2.819 ops/ms [Average]
  (min, avg, max) = (9.374, 9.488, 9.664), stdev = 0.155
  CI (99.9%): [6.668, 12.307] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.662 ops/ms
# Warmup Iteration   2: 9.461 ops/ms
# Warmup Iteration   3: 9.881 ops/ms
Iteration   1: 9.841 ops/ms
Iteration   2: 9.806 ops/ms
Iteration   3: 10.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.966 ±(99.9%) 4.510 ops/ms [Average]
  (min, avg, max) = (9.806, 9.966, 10.250), stdev = 0.247
  CI (99.9%): [5.456, 14.476] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.958 ops/ms
# Warmup Iteration   2: 8.759 ops/ms
# Warmup Iteration   3: 9.169 ops/ms
Iteration   1: 10.022 ops/ms
Iteration   2: 9.682 ops/ms
Iteration   3: 9.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.872 ±(99.9%) 3.158 ops/ms [Average]
  (min, avg, max) = (9.682, 9.872, 10.022), stdev = 0.173
  CI (99.9%): [6.714, 13.031] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.327 ops/ms
# Warmup Iteration   2: 7.437 ops/ms
# Warmup Iteration   3: 8.198 ops/ms
Iteration   1: 8.592 ops/ms
Iteration   2: 8.609 ops/ms
Iteration   3: 8.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.587 ±(99.9%) 0.455 ops/ms [Average]
  (min, avg, max) = (8.560, 8.587, 8.609), stdev = 0.025
  CI (99.9%): [8.132, 9.042] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.781 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.442 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.006 ms/op
Iteration   1: 3.252 ±(99.9%) 0.005 ms/op
Iteration   2: 3.305 ±(99.9%) 0.004 ms/op
Iteration   3: 3.213 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.257 ±(99.9%) 0.845 ms/op [Average]
  (min, avg, max) = (3.213, 3.257, 3.305), stdev = 0.046
  CI (99.9%): [2.412, 4.101] (assumes normal distribution)


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
# Warmup Iteration   1: 7.657 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.002 ms/op
Iteration   1: 3.175 ±(99.9%) 0.004 ms/op
Iteration   2: 3.149 ±(99.9%) 0.008 ms/op
Iteration   3: 3.135 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.153 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (3.135, 3.153, 3.175), stdev = 0.020
  CI (99.9%): [2.786, 3.519] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.783 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.004 ms/op
Iteration   1: 3.283 ±(99.9%) 0.002 ms/op
Iteration   2: 3.170 ±(99.9%) 0.004 ms/op
Iteration   3: 3.195 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.216 ±(99.9%) 1.079 ms/op [Average]
  (min, avg, max) = (3.170, 3.216, 3.283), stdev = 0.059
  CI (99.9%): [2.137, 4.295] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.619 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.007 ms/op
Iteration   1: 3.894 ±(99.9%) 0.004 ms/op
Iteration   2: 3.985 ±(99.9%) 0.004 ms/op
Iteration   3: 3.813 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.897 ±(99.9%) 1.565 ms/op [Average]
  (min, avg, max) = (3.813, 3.897, 3.985), stdev = 0.086
  CI (99.9%): [2.332, 5.463] (assumes normal distribution)


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
# Warmup Iteration   1: 8.758 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.010 ms/op
Iteration   1: 3.178 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.318 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  12.359 ms/op
                 createUser·p0.9999: 20.052 ms/op
                 createUser·p1.00:   20.677 ms/op

Iteration   2: 3.280 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  17.952 ms/op
                 createUser·p0.9999: 21.712 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   3: 3.280 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  15.938 ms/op
                 createUser·p0.9999: 22.094 ms/op
                 createUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295493
  mean =      3.245 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20516 
    [ 2.500,  5.000) = 266262 
    [ 5.000,  7.500) = 7218 
    [ 7.500, 10.000) = 1046 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     15.655 ms/op
     p(99.9900) =     21.609 ms/op
     p(99.9990) =     22.482 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.402 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.010 ms/op
Iteration   1: 3.205 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  11.055 ms/op
                 existUser·p0.9999: 20.449 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 3.153 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  9.709 ms/op
                 existUser·p0.9999: 22.628 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.485 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  8.889 ms/op
                 existUser·p0.9999: 21.959 ms/op
                 existUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304125
  mean =      3.155 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16171 
    [ 2.500,  5.000) = 281268 
    [ 5.000,  7.500) = 5540 
    [ 7.500, 10.000) = 829 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     10.174 ms/op
     p(99.9900) =     21.843 ms/op
     p(99.9990) =     23.854 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 7.650 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.010 ms/op
Iteration   1: 3.266 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  18.186 ms/op
                 getUser·p0.9999: 23.140 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   2: 3.244 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   6.231 ms/op
                 getUser·p0.999:  11.649 ms/op
                 getUser·p0.9999: 23.466 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   3: 3.336 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.221 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  9.473 ms/op
                 getUser·p0.9999: 21.987 ms/op
                 getUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292654
  mean =      3.282 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11947 
    [ 2.500,  5.000) = 271489 
    [ 5.000,  7.500) = 7907 
    [ 7.500, 10.000) = 901 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 143 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     11.974 ms/op
     p(99.9900) =     22.879 ms/op
     p(99.9990) =     24.021 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 9.003 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.014 ms/op
Iteration   1: 3.780 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.227 ms/op
                 listUser·p0.999:  16.187 ms/op
                 listUser·p0.9999: 23.141 ms/op
                 listUser·p1.00:   25.002 ms/op

Iteration   2: 3.764 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  12.878 ms/op
                 listUser·p0.9999: 19.219 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 3.854 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  16.945 ms/op
                 listUser·p0.9999: 20.634 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252564
  mean =      3.799 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 245104 
    [ 5.000,  7.500) = 5080 
    [ 7.500, 10.000) = 1544 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 283 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     15.286 ms/op
     p(99.9900) =     21.682 ms/op
     p(99.9990) =     24.568 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.488 ± 2.819  ops/ms
ClientPb.existUser                       thrpt       3   9.966 ± 4.510  ops/ms
ClientPb.getUser                         thrpt       3   9.872 ± 3.158  ops/ms
ClientPb.listUser                        thrpt       3   8.587 ± 0.455  ops/ms
ClientPb.createUser                       avgt       3   3.257 ± 0.845   ms/op
ClientPb.existUser                        avgt       3   3.153 ± 0.366   ms/op
ClientPb.getUser                          avgt       3   3.216 ± 1.079   ms/op
ClientPb.listUser                         avgt       3   3.897 ± 1.565   ms/op
ClientPb.createUser                     sample  295493   3.245 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.968           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.275           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.655           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.609           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.560           ms/op
ClientPb.existUser                      sample  304125   3.155 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.800           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.437           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.612           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.174           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.843           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.052           ms/op
ClientPb.getUser                        sample  292654   3.282 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.967           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.695           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.974           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.879           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.052           ms/op
ClientPb.listUser                       sample  252564   3.799 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.274           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.291           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.286           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.682           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.002           ms/op
