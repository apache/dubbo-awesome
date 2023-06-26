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
# Warmup Iteration   1: 2.404 ops/ms
# Warmup Iteration   2: 6.057 ops/ms
# Warmup Iteration   3: 9.148 ops/ms
Iteration   1: 9.627 ops/ms
Iteration   2: 10.146 ops/ms
Iteration   3: 9.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.772 ±(99.9%) 5.967 ops/ms [Average]
  (min, avg, max) = (9.542, 9.772, 10.146), stdev = 0.327
  CI (99.9%): [3.805, 15.739] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.361 ops/ms
# Warmup Iteration   2: 9.132 ops/ms
# Warmup Iteration   3: 10.459 ops/ms
Iteration   1: 10.088 ops/ms
Iteration   2: 10.127 ops/ms
Iteration   3: 10.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.179 ±(99.9%) 2.281 ops/ms [Average]
  (min, avg, max) = (10.088, 10.179, 10.321), stdev = 0.125
  CI (99.9%): [7.898, 12.460] (assumes normal distribution)


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
# Warmup Iteration   1: 3.619 ops/ms
# Warmup Iteration   2: 9.154 ops/ms
# Warmup Iteration   3: 9.706 ops/ms
Iteration   1: 9.784 ops/ms
Iteration   2: 9.979 ops/ms
Iteration   3: 9.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.898 ±(99.9%) 1.865 ops/ms [Average]
  (min, avg, max) = (9.784, 9.898, 9.979), stdev = 0.102
  CI (99.9%): [8.034, 11.763] (assumes normal distribution)


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
# Warmup Iteration   1: 2.950 ops/ms
# Warmup Iteration   2: 7.364 ops/ms
# Warmup Iteration   3: 8.008 ops/ms
Iteration   1: 8.393 ops/ms
Iteration   2: 8.566 ops/ms
Iteration   3: 8.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.475 ±(99.9%) 1.592 ops/ms [Average]
  (min, avg, max) = (8.393, 8.475, 8.566), stdev = 0.087
  CI (99.9%): [6.883, 10.067] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.133 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.007 ms/op
Iteration   1: 3.155 ±(99.9%) 0.005 ms/op
Iteration   2: 3.155 ±(99.9%) 0.004 ms/op
Iteration   3: 3.258 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.189 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (3.155, 3.189, 3.258), stdev = 0.060
  CI (99.9%): [2.100, 4.279] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.584 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.009 ms/op
Iteration   1: 3.268 ±(99.9%) 0.005 ms/op
Iteration   2: 3.144 ±(99.9%) 0.007 ms/op
Iteration   3: 3.207 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.206 ±(99.9%) 1.134 ms/op [Average]
  (min, avg, max) = (3.144, 3.206, 3.268), stdev = 0.062
  CI (99.9%): [2.073, 4.340] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.346 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.002 ms/op
Iteration   1: 3.137 ±(99.9%) 0.004 ms/op
Iteration   2: 3.269 ±(99.9%) 0.006 ms/op
Iteration   3: 3.206 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.204 ±(99.9%) 1.198 ms/op [Average]
  (min, avg, max) = (3.137, 3.204, 3.269), stdev = 0.066
  CI (99.9%): [2.006, 4.402] (assumes normal distribution)


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
# Warmup Iteration   1: 8.792 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.006 ms/op
Iteration   1: 3.677 ±(99.9%) 0.010 ms/op
Iteration   2: 3.740 ±(99.9%) 0.010 ms/op
Iteration   3: 3.833 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.750 ±(99.9%) 1.435 ms/op [Average]
  (min, avg, max) = (3.677, 3.750, 3.833), stdev = 0.079
  CI (99.9%): [2.315, 5.185] (assumes normal distribution)


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
# Warmup Iteration   1: 8.697 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.009 ms/op
Iteration   1: 3.269 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.286 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  14.642 ms/op
                 createUser·p0.9999: 21.962 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  18.711 ms/op
                 createUser·p0.9999: 22.931 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   3: 3.235 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  10.256 ms/op
                 createUser·p0.9999: 23.990 ms/op
                 createUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294410
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18929 
    [ 2.500,  5.000) = 269066 
    [ 5.000,  7.500) = 5497 
    [ 7.500, 10.000) = 459 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.286 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     15.355 ms/op
     p(99.9900) =     23.353 ms/op
     p(99.9990) =     24.989 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 7.582 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.426 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.009 ms/op
Iteration   1: 3.174 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.001 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  15.499 ms/op
                 existUser·p0.9999: 22.706 ms/op
                 existUser·p1.00:   24.084 ms/op

Iteration   2: 3.159 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  9.060 ms/op
                 existUser·p0.9999: 36.045 ms/op
                 existUser·p1.00:   37.093 ms/op

Iteration   3: 3.062 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   5.170 ms/op
                 existUser·p0.999:  12.607 ms/op
                 existUser·p0.9999: 26.546 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306470
  mean =      3.131 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21686 
    [ 2.500,  5.000) = 279446 
    [ 5.000,  7.500) = 4338 
    [ 7.500, 10.000) = 532 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.995 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     12.403 ms/op
     p(99.9900) =     34.430 ms/op
     p(99.9990) =     36.958 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


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
# Warmup Iteration   1: 8.376 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.010 ms/op
Iteration   1: 3.202 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  13.271 ms/op
                 getUser·p0.9999: 20.349 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   2: 3.263 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  10.879 ms/op
                 getUser·p0.9999: 21.942 ms/op
                 getUser·p1.00:   23.069 ms/op

Iteration   3: 3.251 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  9.513 ms/op
                 getUser·p0.9999: 22.517 ms/op
                 getUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296289
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15402 
    [ 2.500,  5.000) = 272054 
    [ 5.000,  7.500) = 7859 
    [ 7.500, 10.000) = 604 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     13.203 ms/op
     p(99.9900) =     21.520 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 10.376 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.106 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.012 ms/op
Iteration   1: 3.763 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.511 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  15.779 ms/op
                 listUser·p0.9999: 19.318 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   2: 3.795 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  13.824 ms/op
                 listUser·p0.9999: 16.712 ms/op
                 listUser·p1.00:   16.761 ms/op

Iteration   3: 3.703 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.182 ms/op
                 listUser·p0.99:   6.259 ms/op
                 listUser·p0.999:  12.685 ms/op
                 listUser·p0.9999: 13.599 ms/op
                 listUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255536
  mean =      3.753 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 249004 
    [ 5.000,  7.500) = 4549 
    [ 7.500, 10.000) = 1230 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 311 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.511 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     13.763 ms/op
     p(99.9900) =     18.183 ms/op
     p(99.9990) =     19.876 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.772 ± 5.967  ops/ms
ClientPb.existUser                       thrpt       3  10.179 ± 2.281  ops/ms
ClientPb.getUser                         thrpt       3   9.898 ± 1.865  ops/ms
ClientPb.listUser                        thrpt       3   8.475 ± 1.592  ops/ms
ClientPb.createUser                       avgt       3   3.189 ± 1.089   ms/op
ClientPb.existUser                        avgt       3   3.206 ± 1.134   ms/op
ClientPb.getUser                          avgt       3   3.204 ± 1.198   ms/op
ClientPb.listUser                         avgt       3   3.750 ± 1.435   ms/op
ClientPb.createUser                     sample  294410   3.257 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.286           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.645           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.767           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.355           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.353           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.330           ms/op
ClientPb.existUser                      sample  306470   3.131 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.995           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.403           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.430           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.093           ms/op
ClientPb.getUser                        sample  296289   3.238 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.085           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.357           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.203           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.520           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.069           ms/op
ClientPb.listUser                       sample  255536   3.753 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.511           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.763           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.183           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.021           ms/op
