# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.642 ops/ms
# Warmup Iteration   2: 5.959 ops/ms
# Warmup Iteration   3: 9.058 ops/ms
Iteration   1: 9.735 ops/ms
Iteration   2: 9.909 ops/ms
Iteration   3: 10.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.896 ±(99.9%) 2.833 ops/ms [Average]
  (min, avg, max) = (9.735, 9.896, 10.044), stdev = 0.155
  CI (99.9%): [7.063, 12.729] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.496 ops/ms
# Warmup Iteration   2: 8.772 ops/ms
# Warmup Iteration   3: 10.283 ops/ms
Iteration   1: 10.157 ops/ms
Iteration   2: 10.497 ops/ms
Iteration   3: 10.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.360 ±(99.9%) 3.273 ops/ms [Average]
  (min, avg, max) = (10.157, 10.360, 10.497), stdev = 0.179
  CI (99.9%): [7.088, 13.633] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.159 ops/ms
# Warmup Iteration   2: 8.941 ops/ms
# Warmup Iteration   3: 9.563 ops/ms
Iteration   1: 9.789 ops/ms
Iteration   2: 9.773 ops/ms
Iteration   3: 10.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.040 ±(99.9%) 8.184 ops/ms [Average]
  (min, avg, max) = (9.773, 10.040, 10.558), stdev = 0.449
  CI (99.9%): [1.856, 18.224] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.176 ops/ms
# Warmup Iteration   2: 7.839 ops/ms
# Warmup Iteration   3: 8.190 ops/ms
Iteration   1: 8.188 ops/ms
Iteration   2: 8.668 ops/ms
Iteration   3: 8.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.509 ±(99.9%) 5.072 ops/ms [Average]
  (min, avg, max) = (8.188, 8.509, 8.671), stdev = 0.278
  CI (99.9%): [3.437, 13.581] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.868 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.372 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.008 ms/op
Iteration   1: 3.304 ±(99.9%) 0.002 ms/op
Iteration   2: 3.168 ±(99.9%) 0.008 ms/op
Iteration   3: 3.269 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.247 ±(99.9%) 1.286 ms/op [Average]
  (min, avg, max) = (3.168, 3.247, 3.304), stdev = 0.070
  CI (99.9%): [1.961, 4.533] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.716 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.005 ms/op
Iteration   1: 3.046 ±(99.9%) 0.003 ms/op
Iteration   2: 3.114 ±(99.9%) 0.004 ms/op
Iteration   3: 3.136 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.099 ±(99.9%) 0.851 ms/op [Average]
  (min, avg, max) = (3.046, 3.099, 3.136), stdev = 0.047
  CI (99.9%): [2.248, 3.949] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.612 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.395 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.004 ms/op
Iteration   1: 3.176 ±(99.9%) 0.003 ms/op
Iteration   2: 3.217 ±(99.9%) 0.004 ms/op
Iteration   3: 3.282 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.225 ±(99.9%) 0.972 ms/op [Average]
  (min, avg, max) = (3.176, 3.225, 3.282), stdev = 0.053
  CI (99.9%): [2.252, 4.197] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.266 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.346 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.005 ms/op
Iteration   1: 3.740 ±(99.9%) 0.004 ms/op
Iteration   2: 3.820 ±(99.9%) 0.006 ms/op
Iteration   3: 3.766 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.775 ±(99.9%) 0.748 ms/op [Average]
  (min, avg, max) = (3.740, 3.775, 3.820), stdev = 0.041
  CI (99.9%): [3.027, 4.524] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.591 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.009 ms/op
Iteration   1: 3.244 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  16.810 ms/op
                 createUser·p0.9999: 28.011 ms/op
                 createUser·p1.00:   30.212 ms/op

Iteration   2: 3.256 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.809 ms/op
                 createUser·p0.999:  13.402 ms/op
                 createUser·p0.9999: 22.719 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   3: 3.226 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.595 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  14.828 ms/op
                 createUser·p0.9999: 22.426 ms/op
                 createUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296110
  mean =      3.242 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16888 
    [ 2.500,  5.000) = 271824 
    [ 5.000,  7.500) = 6416 
    [ 7.500, 10.000) = 345 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     26.742 ms/op
     p(99.9990) =     30.085 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.554 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.343 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.008 ms/op
Iteration   1: 3.059 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.264 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   5.577 ms/op
                 existUser·p0.999:  13.550 ms/op
                 existUser·p0.9999: 19.958 ms/op
                 existUser·p1.00:   21.332 ms/op

Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.618 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  10.951 ms/op
                 existUser·p0.9999: 21.121 ms/op
                 existUser·p1.00:   22.315 ms/op

Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.272 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.371 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  12.424 ms/op
                 existUser·p0.9999: 20.966 ms/op
                 existUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314934
  mean =      3.047 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16089 
    [ 2.500,  5.000) = 293197 
    [ 5.000,  7.500) = 4929 
    [ 7.500, 10.000) = 306 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.265 ms/op
     p(95.0000) =      3.465 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     12.715 ms/op
     p(99.9900) =     20.906 ms/op
     p(99.9990) =     21.976 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.041 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.323 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.009 ms/op
Iteration   1: 3.441 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.290 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  18.448 ms/op
                 getUser·p0.9999: 20.821 ms/op
                 getUser·p1.00:   22.381 ms/op

Iteration   2: 3.213 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  20.724 ms/op
                 getUser·p0.9999: 24.347 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   3: 3.155 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  15.811 ms/op
                 getUser·p0.9999: 20.307 ms/op
                 getUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293862
  mean =      3.265 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15875 
    [ 2.500,  5.000) = 267830 
    [ 5.000,  7.500) = 9199 
    [ 7.500, 10.000) = 431 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.290 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.398 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     17.634 ms/op
     p(99.9900) =     22.761 ms/op
     p(99.9990) =     24.643 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.578 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.010 ms/op
Iteration   1: 3.824 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.062 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 26.742 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   2: 3.835 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.089 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  13.324 ms/op
                 listUser·p0.9999: 14.691 ms/op
                 listUser·p1.00:   14.795 ms/op

Iteration   3: 3.736 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.300 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 14.753 ms/op
                 listUser·p1.00:   14.778 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252769
  mean =      3.798 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 245151 
    [ 5.000,  7.500) = 5923 
    [ 7.500, 10.000) = 971 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 373 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      2.062 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.156 ms/op
     p(99.9900) =     24.851 ms/op
     p(99.9990) =     27.196 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.896 ± 2.833  ops/ms
ClientPb.existUser                       thrpt       3  10.360 ± 3.273  ops/ms
ClientPb.getUser                         thrpt       3  10.040 ± 8.184  ops/ms
ClientPb.listUser                        thrpt       3   8.509 ± 5.072  ops/ms
ClientPb.createUser                       avgt       3   3.247 ± 1.286   ms/op
ClientPb.existUser                        avgt       3   3.099 ± 0.851   ms/op
ClientPb.getUser                          avgt       3   3.225 ± 0.972   ms/op
ClientPb.listUser                         avgt       3   3.775 ± 0.748   ms/op
ClientPb.createUser                     sample  296110   3.242 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.014           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.677           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.777           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.742           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.212           ms/op
ClientPb.existUser                      sample  314934   3.047 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.264           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.715           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.906           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.315           ms/op
ClientPb.getUser                        sample  293862   3.265 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.290           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.740           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.398           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.634           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.761           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.330           ms/op
ClientPb.listUser                       sample  252769   3.798 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.062           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.699           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.156           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.851           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.296           ms/op
