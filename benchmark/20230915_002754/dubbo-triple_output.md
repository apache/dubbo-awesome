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
# Warmup Iteration   1: 1.935 ops/ms
# Warmup Iteration   2: 5.387 ops/ms
# Warmup Iteration   3: 8.652 ops/ms
Iteration   1: 9.017 ops/ms
Iteration   2: 9.269 ops/ms
Iteration   3: 9.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.201 ±(99.9%) 2.925 ops/ms [Average]
  (min, avg, max) = (9.017, 9.201, 9.315), stdev = 0.160
  CI (99.9%): [6.275, 12.126] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.925 ops/ms
# Warmup Iteration   2: 8.763 ops/ms
# Warmup Iteration   3: 9.144 ops/ms
Iteration   1: 9.371 ops/ms
Iteration   2: 9.796 ops/ms
Iteration   3: 9.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.585 ±(99.9%) 3.882 ops/ms [Average]
  (min, avg, max) = (9.371, 9.585, 9.796), stdev = 0.213
  CI (99.9%): [5.703, 13.467] (assumes normal distribution)


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
# Warmup Iteration   1: 3.147 ops/ms
# Warmup Iteration   2: 8.618 ops/ms
# Warmup Iteration   3: 9.041 ops/ms
Iteration   1: 9.172 ops/ms
Iteration   2: 9.218 ops/ms
Iteration   3: 9.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.177 ±(99.9%) 0.711 ops/ms [Average]
  (min, avg, max) = (9.140, 9.177, 9.218), stdev = 0.039
  CI (99.9%): [8.465, 9.888] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.113 ops/ms
# Warmup Iteration   2: 7.218 ops/ms
# Warmup Iteration   3: 7.726 ops/ms
Iteration   1: 7.969 ops/ms
Iteration   2: 7.901 ops/ms
Iteration   3: 7.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.918 ±(99.9%) 0.809 ops/ms [Average]
  (min, avg, max) = (7.886, 7.918, 7.969), stdev = 0.044
  CI (99.9%): [7.109, 8.728] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.953 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.811 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.006 ms/op
Iteration   1: 3.478 ±(99.9%) 0.007 ms/op
Iteration   2: 3.537 ±(99.9%) 0.005 ms/op
Iteration   3: 3.426 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.480 ±(99.9%) 1.009 ms/op [Average]
  (min, avg, max) = (3.426, 3.480, 3.537), stdev = 0.055
  CI (99.9%): [2.471, 4.489] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.102 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.003 ms/op
Iteration   1: 3.270 ±(99.9%) 0.005 ms/op
Iteration   2: 3.293 ±(99.9%) 0.003 ms/op
Iteration   3: 3.334 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.299 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (3.270, 3.299, 3.334), stdev = 0.033
  CI (99.9%): [2.705, 3.893] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.043 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.004 ms/op
Iteration   1: 3.512 ±(99.9%) 0.004 ms/op
Iteration   2: 3.384 ±(99.9%) 0.003 ms/op
Iteration   3: 3.372 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.423 ±(99.9%) 1.409 ms/op [Average]
  (min, avg, max) = (3.372, 3.423, 3.512), stdev = 0.077
  CI (99.9%): [2.014, 4.832] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.701 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.412 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.131 ±(99.9%) 0.004 ms/op
Iteration   1: 4.047 ±(99.9%) 0.007 ms/op
Iteration   2: 4.102 ±(99.9%) 0.005 ms/op
Iteration   3: 4.070 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.073 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (4.047, 4.073, 4.102), stdev = 0.028
  CI (99.9%): [3.569, 4.578] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.847 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.010 ms/op
Iteration   1: 3.413 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  19.973 ms/op
                 createUser·p0.9999: 22.692 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   2: 3.510 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  20.702 ms/op
                 createUser·p0.9999: 24.900 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   3: 3.487 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.217 ms/op
                 createUser·p0.999:  19.411 ms/op
                 createUser·p0.9999: 23.194 ms/op
                 createUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276777
  mean =      3.470 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5494 
    [ 2.500,  5.000) = 267211 
    [ 5.000,  7.500) = 2956 
    [ 7.500, 10.000) = 555 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 179 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     19.570 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     25.305 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 8.310 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.009 ms/op
Iteration   1: 3.421 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.259 ms/op
                 existUser·p0.99:   6.183 ms/op
                 existUser·p0.999:  10.656 ms/op
                 existUser·p0.9999: 22.050 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   2: 3.259 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.102 ms/op
                 existUser·p0.999:  12.958 ms/op
                 existUser·p0.9999: 24.412 ms/op
                 existUser·p1.00:   25.166 ms/op

Iteration   3: 3.423 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.362 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  18.932 ms/op
                 existUser·p0.9999: 25.350 ms/op
                 existUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285150
  mean =      3.366 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10183 
    [ 2.500,  5.000) = 270113 
    [ 5.000,  7.500) = 3725 
    [ 7.500, 10.000) = 643 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 134 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     12.056 ms/op
     p(99.9900) =     24.657 ms/op
     p(99.9990) =     26.222 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 9.320 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.009 ms/op
Iteration   1: 3.469 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.522 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  20.048 ms/op
                 getUser·p0.9999: 22.118 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   2: 3.508 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.948 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  19.133 ms/op
                 getUser·p0.9999: 23.196 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   3: 3.461 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.569 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  17.998 ms/op
                 getUser·p0.9999: 25.027 ms/op
                 getUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275714
  mean =      3.479 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3349 
    [ 2.500,  5.000) = 263734 
    [ 5.000,  7.500) = 7618 
    [ 7.500, 10.000) = 426 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 182 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.522 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     18.205 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     25.935 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 9.614 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.013 ms/op
Iteration   1: 4.118 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.081 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  18.088 ms/op
                 listUser·p0.9999: 21.504 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   2: 4.062 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  14.963 ms/op
                 listUser·p0.9999: 16.400 ms/op
                 listUser·p1.00:   16.728 ms/op

Iteration   3: 4.082 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.394 ms/op
                 listUser·p0.999:  15.953 ms/op
                 listUser·p0.9999: 19.399 ms/op
                 listUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234695
  mean =      4.087 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 227217 
    [ 5.000,  7.500) = 5868 
    [ 7.500, 10.000) = 771 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.081 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     15.553 ms/op
     p(99.9900) =     20.677 ms/op
     p(99.9990) =     21.909 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.201 ± 2.925  ops/ms
ClientPb.existUser                       thrpt       3   9.585 ± 3.882  ops/ms
ClientPb.getUser                         thrpt       3   9.177 ± 0.711  ops/ms
ClientPb.listUser                        thrpt       3   7.918 ± 0.809  ops/ms
ClientPb.createUser                       avgt       3   3.480 ± 1.009   ms/op
ClientPb.existUser                        avgt       3   3.299 ± 0.594   ms/op
ClientPb.getUser                          avgt       3   3.423 ± 1.409   ms/op
ClientPb.listUser                         avgt       3   4.073 ± 0.504   ms/op
ClientPb.createUser                     sample  276777   3.470 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.296           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.570           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.593           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.362           ms/op
ClientPb.existUser                      sample  285150   3.366 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.035           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.825           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.056           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.657           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.066           ms/op
ClientPb.getUser                        sample  275714   3.479 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.522           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.431           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.205           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.790           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.804           ms/op
ClientPb.listUser                       sample  234695   4.087 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.081           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.849           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.553           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.677           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.053           ms/op
