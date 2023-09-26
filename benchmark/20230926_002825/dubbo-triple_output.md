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
# Warmup Iteration   1: 2.635 ops/ms
# Warmup Iteration   2: 6.227 ops/ms
# Warmup Iteration   3: 8.709 ops/ms
Iteration   1: 9.557 ops/ms
Iteration   2: 9.514 ops/ms
Iteration   3: 9.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.541 ±(99.9%) 0.435 ops/ms [Average]
  (min, avg, max) = (9.514, 9.541, 9.557), stdev = 0.024
  CI (99.9%): [9.106, 9.976] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.333 ops/ms
# Warmup Iteration   2: 8.993 ops/ms
# Warmup Iteration   3: 9.941 ops/ms
Iteration   1: 10.061 ops/ms
Iteration   2: 10.283 ops/ms
Iteration   3: 10.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.181 ±(99.9%) 2.036 ops/ms [Average]
  (min, avg, max) = (10.061, 10.181, 10.283), stdev = 0.112
  CI (99.9%): [8.145, 12.217] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.700 ops/ms
# Warmup Iteration   2: 9.236 ops/ms
# Warmup Iteration   3: 9.388 ops/ms
Iteration   1: 9.595 ops/ms
Iteration   2: 9.781 ops/ms
Iteration   3: 9.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.693 ±(99.9%) 1.698 ops/ms [Average]
  (min, avg, max) = (9.595, 9.693, 9.781), stdev = 0.093
  CI (99.9%): [7.995, 11.391] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.968 ops/ms
# Warmup Iteration   2: 7.530 ops/ms
# Warmup Iteration   3: 7.919 ops/ms
Iteration   1: 8.182 ops/ms
Iteration   2: 8.263 ops/ms
Iteration   3: 8.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.221 ±(99.9%) 0.743 ops/ms [Average]
  (min, avg, max) = (8.182, 8.221, 8.263), stdev = 0.041
  CI (99.9%): [7.478, 8.963] (assumes normal distribution)


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
# Warmup Iteration   1: 8.833 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.002 ms/op
Iteration   1: 3.291 ±(99.9%) 0.003 ms/op
Iteration   2: 3.405 ±(99.9%) 0.003 ms/op
Iteration   3: 3.291 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.329 ±(99.9%) 1.195 ms/op [Average]
  (min, avg, max) = (3.291, 3.329, 3.405), stdev = 0.066
  CI (99.9%): [2.134, 4.524] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.962 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.390 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.003 ms/op
Iteration   1: 3.172 ±(99.9%) 0.003 ms/op
Iteration   2: 3.150 ±(99.9%) 0.003 ms/op
Iteration   3: 3.285 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.202 ±(99.9%) 1.316 ms/op [Average]
  (min, avg, max) = (3.150, 3.202, 3.285), stdev = 0.072
  CI (99.9%): [1.887, 4.518] (assumes normal distribution)


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
# Warmup Iteration   1: 8.492 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.658 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.003 ms/op
Iteration   1: 3.227 ±(99.9%) 0.002 ms/op
Iteration   2: 3.280 ±(99.9%) 0.003 ms/op
Iteration   3: 3.215 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.240 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (3.215, 3.240, 3.280), stdev = 0.035
  CI (99.9%): [2.607, 3.874] (assumes normal distribution)


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
# Warmup Iteration   1: 10.820 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.004 ms/op
Iteration   1: 3.823 ±(99.9%) 0.004 ms/op
Iteration   2: 3.842 ±(99.9%) 0.004 ms/op
Iteration   3: 3.832 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.832 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (3.823, 3.832, 3.842), stdev = 0.010
  CI (99.9%): [3.656, 4.009] (assumes normal distribution)


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
# Warmup Iteration   1: 8.873 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.010 ms/op
Iteration   1: 3.335 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.245 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  17.554 ms/op
                 createUser·p0.9999: 21.555 ms/op
                 createUser·p1.00:   22.348 ms/op

Iteration   2: 3.258 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  8.796 ms/op
                 createUser·p0.9999: 23.310 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   3: 3.277 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   5.161 ms/op
                 createUser·p0.999:  17.051 ms/op
                 createUser·p0.9999: 23.601 ms/op
                 createUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291690
  mean =      3.290 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6850 
    [ 2.500,  5.000) = 280573 
    [ 5.000,  7.500) = 3455 
    [ 7.500, 10.000) = 360 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     22.998 ms/op
     p(99.9990) =     24.052 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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
# Warmup Iteration   1: 8.981 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.484 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.008 ms/op
Iteration   1: 3.227 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  12.222 ms/op
                 existUser·p0.9999: 21.109 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   2: 3.147 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.932 ms/op
                 existUser·p0.999:  12.704 ms/op
                 existUser·p0.9999: 24.538 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   3: 3.206 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.940 ms/op
                 existUser·p0.999:  11.610 ms/op
                 existUser·p0.9999: 23.309 ms/op
                 existUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300306
  mean =      3.193 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19879 
    [ 2.500,  5.000) = 276002 
    [ 5.000,  7.500) = 3537 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     12.255 ms/op
     p(99.9900) =     24.051 ms/op
     p(99.9990) =     24.773 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 8.862 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.010 ms/op
Iteration   1: 3.324 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.047 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  16.640 ms/op
                 getUser·p0.9999: 21.129 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   2: 3.228 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  8.504 ms/op
                 getUser·p0.9999: 21.070 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   3: 3.301 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   6.150 ms/op
                 getUser·p0.999:  11.960 ms/op
                 getUser·p0.9999: 20.757 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292288
  mean =      3.284 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10659 
    [ 2.500,  5.000) = 274249 
    [ 5.000,  7.500) = 6463 
    [ 7.500, 10.000) = 371 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     12.812 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     22.197 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.166 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.804 ±(99.9%) 0.010 ms/op
Iteration   1: 3.846 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.860 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.807 ms/op
                 listUser·p0.999:  13.353 ms/op
                 listUser·p0.9999: 20.054 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   2: 3.789 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  13.126 ms/op
                 listUser·p0.9999: 14.057 ms/op
                 listUser·p1.00:   14.107 ms/op

Iteration   3: 3.842 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.242 ms/op
                 listUser·p0.999:  13.021 ms/op
                 listUser·p0.9999: 17.236 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250923
  mean =      3.825 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 245053 
    [ 5.000,  7.500) = 4481 
    [ 7.500, 10.000) = 601 
    [10.000, 12.500) = 392 
    [12.500, 15.000) = 280 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.860 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     13.158 ms/op
     p(99.9900) =     19.399 ms/op
     p(99.9990) =     20.315 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.541 ± 0.435  ops/ms
ClientPb.existUser                       thrpt       3  10.181 ± 2.036  ops/ms
ClientPb.getUser                         thrpt       3   9.693 ± 1.698  ops/ms
ClientPb.listUser                        thrpt       3   8.221 ± 0.743  ops/ms
ClientPb.createUser                       avgt       3   3.329 ± 1.195   ms/op
ClientPb.existUser                        avgt       3   3.202 ± 1.316   ms/op
ClientPb.getUser                          avgt       3   3.240 ± 0.634   ms/op
ClientPb.listUser                         avgt       3   3.832 ± 0.177   ms/op
ClientPb.createUser                     sample  291690   3.290 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.958           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.007           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.998           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.445           ms/op
ClientPb.existUser                      sample  300306   3.193 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.102           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.441           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.255           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.051           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.068           ms/op
ClientPb.getUser                        sample  292288   3.284 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.047           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.629           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.812           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.037           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.003           ms/op
ClientPb.listUser                       sample  250923   3.825 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.133           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.636           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.158           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.399           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.480           ms/op
