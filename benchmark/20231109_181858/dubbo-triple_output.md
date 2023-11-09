# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.966 ops/ms
# Warmup Iteration   2: 1.957 ops/ms
# Warmup Iteration   3: 4.346 ops/ms
Iteration   1: 4.814 ops/ms
Iteration   2: 5.146 ops/ms
Iteration   3: 5.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.110 ±(99.9%) 5.099 ops/ms [Average]
  (min, avg, max) = (4.814, 5.110, 5.370), stdev = 0.279
  CI (99.9%): [0.011, 10.209] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.292 ops/ms
# Warmup Iteration   2: 4.107 ops/ms
# Warmup Iteration   3: 5.111 ops/ms
Iteration   1: 5.435 ops/ms
Iteration   2: 5.499 ops/ms
Iteration   3: 5.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.472 ±(99.9%) 0.599 ops/ms [Average]
  (min, avg, max) = (5.435, 5.472, 5.499), stdev = 0.033
  CI (99.9%): [4.872, 6.071] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.331 ops/ms
# Warmup Iteration   2: 3.699 ops/ms
# Warmup Iteration   3: 4.930 ops/ms
Iteration   1: 5.043 ops/ms
Iteration   2: 5.105 ops/ms
Iteration   3: 5.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.087 ±(99.9%) 0.698 ops/ms [Average]
  (min, avg, max) = (5.043, 5.087, 5.112), stdev = 0.038
  CI (99.9%): [4.389, 5.784] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.228 ops/ms
# Warmup Iteration   2: 3.425 ops/ms
# Warmup Iteration   3: 4.313 ops/ms
Iteration   1: 4.406 ops/ms
Iteration   2: 4.446 ops/ms
Iteration   3: 4.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.425 ±(99.9%) 0.365 ops/ms [Average]
  (min, avg, max) = (4.406, 4.425, 4.446), stdev = 0.020
  CI (99.9%): [4.061, 4.790] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 20.344 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 7.429 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.567 ±(99.9%) 0.013 ms/op
Iteration   1: 6.320 ±(99.9%) 0.012 ms/op
Iteration   2: 5.954 ±(99.9%) 0.010 ms/op
Iteration   3: 6.112 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.128 ±(99.9%) 3.353 ms/op [Average]
  (min, avg, max) = (5.954, 6.128, 6.320), stdev = 0.184
  CI (99.9%): [2.775, 9.482] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 18.766 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 8.033 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.956 ±(99.9%) 0.010 ms/op
Iteration   1: 5.919 ±(99.9%) 0.010 ms/op
Iteration   2: 6.005 ±(99.9%) 0.009 ms/op
Iteration   3: 6.251 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.059 ±(99.9%) 3.143 ms/op [Average]
  (min, avg, max) = (5.919, 6.059, 6.251), stdev = 0.172
  CI (99.9%): [2.916, 9.202] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 21.288 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 8.603 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.103 ±(99.9%) 0.010 ms/op
Iteration   1: 6.087 ±(99.9%) 0.012 ms/op
Iteration   2: 6.314 ±(99.9%) 0.012 ms/op
Iteration   3: 6.168 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.190 ±(99.9%) 2.104 ms/op [Average]
  (min, avg, max) = (6.087, 6.190, 6.314), stdev = 0.115
  CI (99.9%): [4.086, 8.294] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 22.059 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 9.635 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 7.642 ±(99.9%) 0.015 ms/op
Iteration   1: 7.364 ±(99.9%) 0.014 ms/op
Iteration   2: 7.368 ±(99.9%) 0.016 ms/op
Iteration   3: 7.216 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.316 ±(99.9%) 1.583 ms/op [Average]
  (min, avg, max) = (7.216, 7.316, 7.368), stdev = 0.087
  CI (99.9%): [5.733, 8.898] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.408 ±(99.9%) 0.364 ms/op
# Warmup Iteration   2: 8.212 ±(99.9%) 0.071 ms/op
# Warmup Iteration   3: 6.912 ±(99.9%) 0.044 ms/op
Iteration   1: 6.092 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.171 ms/op
                 createUser·p0.50:   5.628 ms/op
                 createUser·p0.90:   7.954 ms/op
                 createUser·p0.95:   9.273 ms/op
                 createUser·p0.99:   12.317 ms/op
                 createUser·p0.999:  26.179 ms/op
                 createUser·p0.9999: 30.794 ms/op
                 createUser·p1.00:   31.097 ms/op

Iteration   2: 6.013 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.544 ms/op
                 createUser·p0.50:   5.530 ms/op
                 createUser·p0.90:   7.610 ms/op
                 createUser·p0.95:   9.126 ms/op
                 createUser·p0.99:   12.960 ms/op
                 createUser·p0.999:  30.081 ms/op
                 createUser·p0.9999: 37.335 ms/op
                 createUser·p1.00:   38.601 ms/op

Iteration   3: 6.175 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   2.810 ms/op
                 createUser·p0.50:   5.702 ms/op
                 createUser·p0.90:   7.856 ms/op
                 createUser·p0.95:   9.372 ms/op
                 createUser·p0.99:   13.549 ms/op
                 createUser·p0.999:  26.313 ms/op
                 createUser·p0.9999: 38.589 ms/op
                 createUser·p1.00:   39.453 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 157495
  mean =      6.093 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 26288 
    [ 5.000,  7.500) = 112421 
    [ 7.500, 10.000) = 13241 
    [10.000, 12.500) = 3606 
    [12.500, 15.000) = 1157 
    [15.000, 17.500) = 388 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      5.620 ms/op
     p(90.0000) =      7.807 ms/op
     p(95.0000) =      9.260 ms/op
     p(99.0000) =     12.943 ms/op
     p(99.9000) =     26.313 ms/op
     p(99.9900) =     37.962 ms/op
     p(99.9990) =     39.377 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.893 ±(99.9%) 0.339 ms/op
# Warmup Iteration   2: 7.766 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.080 ±(99.9%) 0.029 ms/op
Iteration   1: 6.071 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   2.449 ms/op
                 existUser·p0.50:   5.407 ms/op
                 existUser·p0.90:   8.421 ms/op
                 existUser·p0.95:   9.945 ms/op
                 existUser·p0.99:   13.959 ms/op
                 existUser·p0.999:  32.875 ms/op
                 existUser·p0.9999: 38.207 ms/op
                 existUser·p1.00:   38.535 ms/op

Iteration   2: 5.939 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   2.687 ms/op
                 existUser·p0.50:   5.317 ms/op
                 existUser·p0.90:   8.208 ms/op
                 existUser·p0.95:   9.863 ms/op
                 existUser·p0.99:   13.992 ms/op
                 existUser·p0.999:  19.368 ms/op
                 existUser·p0.9999: 31.051 ms/op
                 existUser·p1.00:   31.654 ms/op

Iteration   3: 6.027 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   5.456 ms/op
                 existUser·p0.90:   8.159 ms/op
                 existUser·p0.95:   9.535 ms/op
                 existUser·p0.99:   12.780 ms/op
                 existUser·p0.999:  33.386 ms/op
                 existUser·p0.9999: 37.466 ms/op
                 existUser·p1.00:   39.322 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 159713
  mean =      6.012 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 41487 
    [ 5.000,  7.500) = 95930 
    [ 7.500, 10.000) = 15147 
    [10.000, 12.500) = 4715 
    [12.500, 15.000) = 1538 
    [15.000, 17.500) = 601 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 45 
    [35.000, 37.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      5.390 ms/op
     p(90.0000) =      8.274 ms/op
     p(95.0000) =      9.781 ms/op
     p(99.0000) =     13.533 ms/op
     p(99.9000) =     28.920 ms/op
     p(99.9900) =     37.490 ms/op
     p(99.9990) =     38.852 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.545 ±(99.9%) 0.375 ms/op
# Warmup Iteration   2: 9.015 ±(99.9%) 0.081 ms/op
# Warmup Iteration   3: 6.560 ±(99.9%) 0.033 ms/op
Iteration   1: 6.393 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   2.666 ms/op
                 getUser·p0.50:   5.734 ms/op
                 getUser·p0.90:   8.733 ms/op
                 getUser·p0.95:   10.338 ms/op
                 getUser·p0.99:   16.122 ms/op
                 getUser·p0.999:  27.817 ms/op
                 getUser·p0.9999: 41.026 ms/op
                 getUser·p1.00:   42.861 ms/op

Iteration   2: 6.307 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   3.015 ms/op
                 getUser·p0.50:   5.693 ms/op
                 getUser·p0.90:   8.651 ms/op
                 getUser·p0.95:   10.338 ms/op
                 getUser·p0.99:   15.106 ms/op
                 getUser·p0.999:  20.906 ms/op
                 getUser·p0.9999: 35.380 ms/op
                 getUser·p1.00:   38.666 ms/op

Iteration   3: 6.214 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.998 ms/op
                 getUser·p0.50:   5.710 ms/op
                 getUser·p0.90:   8.126 ms/op
                 getUser·p0.95:   9.470 ms/op
                 getUser·p0.99:   13.737 ms/op
                 getUser·p0.999:  34.341 ms/op
                 getUser·p0.9999: 39.059 ms/op
                 getUser·p1.00:   40.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 152188
  mean =      6.304 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 23820 
    [ 5.000, 10.000) = 120574 
    [10.000, 15.000) = 6334 
    [15.000, 20.000) = 1127 
    [20.000, 25.000) = 172 
    [25.000, 30.000) = 27 
    [30.000, 35.000) = 51 
    [35.000, 40.000) = 63 
    [40.000, 45.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      2.666 ms/op
     p(50.0000) =      5.710 ms/op
     p(90.0000) =      8.471 ms/op
     p(95.0000) =     10.043 ms/op
     p(99.0000) =     14.844 ms/op
     p(99.9000) =     27.578 ms/op
     p(99.9900) =     40.421 ms/op
     p(99.9990) =     42.690 ms/op
     p(99.9999) =     42.861 ms/op
    p(100.0000) =     42.861 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 23.233 ±(99.9%) 0.467 ms/op
# Warmup Iteration   2: 9.473 ±(99.9%) 0.077 ms/op
# Warmup Iteration   3: 7.524 ±(99.9%) 0.038 ms/op
Iteration   1: 7.330 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   6.693 ms/op
                 listUser·p0.90:   9.830 ms/op
                 listUser·p0.95:   11.469 ms/op
                 listUser·p0.99:   15.093 ms/op
                 listUser·p0.999:  29.622 ms/op
                 listUser·p0.9999: 35.621 ms/op
                 listUser·p1.00:   37.618 ms/op

Iteration   2: 7.207 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   3.404 ms/op
                 listUser·p0.50:   6.668 ms/op
                 listUser·p0.90:   9.372 ms/op
                 listUser·p0.95:   11.092 ms/op
                 listUser·p0.99:   14.395 ms/op
                 listUser·p0.999:  31.050 ms/op
                 listUser·p0.9999: 37.792 ms/op
                 listUser·p1.00:   41.091 ms/op

Iteration   3: 7.051 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   6.480 ms/op
                 listUser·p0.90:   8.946 ms/op
                 listUser·p0.95:   10.813 ms/op
                 listUser·p0.99:   14.596 ms/op
                 listUser·p0.999:  38.233 ms/op
                 listUser·p0.9999: 45.898 ms/op
                 listUser·p1.00:   50.790 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 133421
  mean =      7.194 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2040 
    [ 5.000, 10.000) = 120760 
    [10.000, 15.000) = 9491 
    [15.000, 20.000) = 708 
    [20.000, 25.000) = 85 
    [25.000, 30.000) = 138 
    [30.000, 35.000) = 90 
    [35.000, 40.000) = 80 
    [40.000, 45.000) = 21 
    [45.000, 50.000) = 7 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.126 ms/op
     p(50.0000) =      6.611 ms/op
     p(90.0000) =      9.421 ms/op
     p(95.0000) =     11.141 ms/op
     p(99.0000) =     14.729 ms/op
     p(99.9000) =     33.658 ms/op
     p(99.9900) =     41.331 ms/op
     p(99.9990) =     49.301 ms/op
     p(99.9999) =     50.790 ms/op
    p(100.0000) =     50.790 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.110 ± 5.099  ops/ms
ClientPb.existUser                       thrpt       3   5.472 ± 0.599  ops/ms
ClientPb.getUser                         thrpt       3   5.087 ± 0.698  ops/ms
ClientPb.listUser                        thrpt       3   4.425 ± 0.365  ops/ms
ClientPb.createUser                       avgt       3   6.128 ± 3.353   ms/op
ClientPb.existUser                        avgt       3   6.059 ± 3.143   ms/op
ClientPb.getUser                          avgt       3   6.190 ± 2.104   ms/op
ClientPb.listUser                         avgt       3   7.316 ± 1.583   ms/op
ClientPb.createUser                     sample  157495   6.093 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.171           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.620           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.807           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.260           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.943           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.313           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.962           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.453           ms/op
ClientPb.existUser                      sample  159713   6.012 ± 0.017   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.313           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.390           ms/op
ClientPb.existUser:existUser·p0.90      sample           8.274           ms/op
ClientPb.existUser:existUser·p0.95      sample           9.781           ms/op
ClientPb.existUser:existUser·p0.99      sample          13.533           ms/op
ClientPb.existUser:existUser·p0.999     sample          28.920           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.490           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.322           ms/op
ClientPb.getUser                        sample  152188   6.304 ± 0.018   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.666           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.710           ms/op
ClientPb.getUser:getUser·p0.90          sample           8.471           ms/op
ClientPb.getUser:getUser·p0.95          sample          10.043           ms/op
ClientPb.getUser:getUser·p0.99          sample          14.844           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.578           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.421           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.861           ms/op
ClientPb.listUser                       sample  133421   7.194 ± 0.020   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.126           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.611           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.421           ms/op
ClientPb.listUser:listUser·p0.95        sample          11.141           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.729           ms/op
ClientPb.listUser:listUser·p0.999       sample          33.658           ms/op
ClientPb.listUser:listUser·p0.9999      sample          41.331           ms/op
ClientPb.listUser:listUser·p1.00        sample          50.790           ms/op
