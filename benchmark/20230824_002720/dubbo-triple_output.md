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
# Warmup Iteration   1: 2.617 ops/ms
# Warmup Iteration   2: 6.451 ops/ms
# Warmup Iteration   3: 8.769 ops/ms
Iteration   1: 9.973 ops/ms
Iteration   2: 9.519 ops/ms
Iteration   3: 9.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.679 ±(99.9%) 4.648 ops/ms [Average]
  (min, avg, max) = (9.519, 9.679, 9.973), stdev = 0.255
  CI (99.9%): [5.030, 14.327] (assumes normal distribution)


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
# Warmup Iteration   1: 3.321 ops/ms
# Warmup Iteration   2: 9.263 ops/ms
# Warmup Iteration   3: 10.274 ops/ms
Iteration   1: 10.020 ops/ms
Iteration   2: 10.074 ops/ms
Iteration   3: 10.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.075 ±(99.9%) 0.993 ops/ms [Average]
  (min, avg, max) = (10.020, 10.075, 10.129), stdev = 0.054
  CI (99.9%): [9.082, 11.068] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.402 ops/ms
# Warmup Iteration   2: 9.054 ops/ms
# Warmup Iteration   3: 9.498 ops/ms
Iteration   1: 9.627 ops/ms
Iteration   2: 9.735 ops/ms
Iteration   3: 9.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.677 ±(99.9%) 0.992 ops/ms [Average]
  (min, avg, max) = (9.627, 9.677, 9.735), stdev = 0.054
  CI (99.9%): [8.685, 10.668] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.257 ops/ms
# Warmup Iteration   2: 7.769 ops/ms
# Warmup Iteration   3: 8.274 ops/ms
Iteration   1: 8.184 ops/ms
Iteration   2: 8.209 ops/ms
Iteration   3: 8.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.240 ±(99.9%) 1.394 ops/ms [Average]
  (min, avg, max) = (8.184, 8.240, 8.327), stdev = 0.076
  CI (99.9%): [6.845, 9.634] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.458 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.002 ms/op
Iteration   1: 3.363 ±(99.9%) 0.003 ms/op
Iteration   2: 3.311 ±(99.9%) 0.004 ms/op
Iteration   3: 3.288 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.321 ±(99.9%) 0.708 ms/op [Average]
  (min, avg, max) = (3.288, 3.321, 3.363), stdev = 0.039
  CI (99.9%): [2.612, 4.029] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.138 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.003 ms/op
Iteration   1: 3.202 ±(99.9%) 0.007 ms/op
Iteration   2: 3.136 ±(99.9%) 0.006 ms/op
Iteration   3: 3.071 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.136 ±(99.9%) 1.190 ms/op [Average]
  (min, avg, max) = (3.071, 3.136, 3.202), stdev = 0.065
  CI (99.9%): [1.946, 4.326] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.877 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.437 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.003 ms/op
Iteration   1: 3.162 ±(99.9%) 0.006 ms/op
Iteration   2: 3.143 ±(99.9%) 0.005 ms/op
Iteration   3: 3.212 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.172 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (3.143, 3.172, 3.212), stdev = 0.036
  CI (99.9%): [2.524, 3.820] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.442 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.004 ms/op
Iteration   1: 3.758 ±(99.9%) 0.009 ms/op
Iteration   2: 3.751 ±(99.9%) 0.011 ms/op
Iteration   3: 3.779 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.763 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (3.751, 3.763, 3.779), stdev = 0.015
  CI (99.9%): [3.494, 4.032] (assumes normal distribution)


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
# Warmup Iteration   1: 7.448 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.201 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.011 ms/op
Iteration   1: 3.214 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  18.838 ms/op
                 createUser·p0.9999: 21.823 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   2: 3.230 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   5.876 ms/op
                 createUser·p0.999:  13.473 ms/op
                 createUser·p0.9999: 23.953 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   3: 3.303 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  14.189 ms/op
                 createUser·p0.9999: 21.319 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295697
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22365 
    [ 2.500,  5.000) = 265941 
    [ 5.000,  7.500) = 5751 
    [ 7.500, 10.000) = 1163 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 155 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     16.304 ms/op
     p(99.9900) =     22.362 ms/op
     p(99.9990) =     24.577 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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
# Warmup Iteration   1: 7.190 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.008 ms/op
Iteration   1: 3.186 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.554 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.417 ms/op
                 existUser·p0.999:  11.340 ms/op
                 existUser·p0.9999: 21.755 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   2: 3.146 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.753 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  10.819 ms/op
                 existUser·p0.9999: 25.554 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   3: 3.197 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  11.469 ms/op
                 existUser·p0.9999: 40.829 ms/op
                 existUser·p1.00:   42.205 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302039
  mean =      3.176 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 295823 
    [ 5.000, 10.000) = 5793 
    [10.000, 15.000) = 167 
    [15.000, 20.000) = 89 
    [20.000, 25.000) = 75 
    [25.000, 30.000) = 60 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     10.928 ms/op
     p(99.9900) =     38.784 ms/op
     p(99.9990) =     41.732 ms/op
     p(99.9999) =     42.205 ms/op
    p(100.0000) =     42.205 ms/op


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
# Warmup Iteration   1: 8.762 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.700 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.011 ms/op
Iteration   1: 3.393 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   7.021 ms/op
                 getUser·p0.999:  16.390 ms/op
                 getUser·p0.9999: 26.412 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   2: 3.327 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.497 ms/op
                 getUser·p0.999:  18.367 ms/op
                 getUser·p0.9999: 21.849 ms/op
                 getUser·p1.00:   23.658 ms/op

Iteration   3: 3.239 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  15.008 ms/op
                 getUser·p0.9999: 23.733 ms/op
                 getUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289100
  mean =      3.318 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14080 
    [ 2.500,  5.000) = 263924 
    [ 5.000,  7.500) = 9034 
    [ 7.500, 10.000) = 1515 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     26.972 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 9.119 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.013 ms/op
Iteration   1: 3.817 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  20.028 ms/op
                 listUser·p0.9999: 24.990 ms/op
                 listUser·p1.00:   28.508 ms/op

Iteration   2: 3.784 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  13.582 ms/op
                 listUser·p0.9999: 16.059 ms/op
                 listUser·p1.00:   16.384 ms/op

Iteration   3: 3.717 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.880 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  12.550 ms/op
                 listUser·p0.9999: 15.447 ms/op
                 listUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254371
  mean =      3.772 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 93 
    [ 2.500,  5.000) = 245296 
    [ 5.000,  7.500) = 6355 
    [ 7.500, 10.000) = 1758 
    [10.000, 12.500) = 415 
    [12.500, 15.000) = 309 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     13.675 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     25.608 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.679 ± 4.648  ops/ms
ClientPb.existUser                       thrpt       3  10.075 ± 0.993  ops/ms
ClientPb.getUser                         thrpt       3   9.677 ± 0.992  ops/ms
ClientPb.listUser                        thrpt       3   8.240 ± 1.394  ops/ms
ClientPb.createUser                       avgt       3   3.321 ± 0.708   ms/op
ClientPb.existUser                        avgt       3   3.136 ± 1.190   ms/op
ClientPb.getUser                          avgt       3   3.172 ± 0.648   ms/op
ClientPb.listUser                         avgt       3   3.763 ± 0.269   ms/op
ClientPb.createUser                     sample  295697   3.248 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.932           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.564           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.046           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.304           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.362           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.609           ms/op
ClientPb.existUser                      sample  302039   3.176 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.403           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.416           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.562           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.928           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.784           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.205           ms/op
ClientPb.getUser                        sample  289100   3.318 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.130           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.498           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.822           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.460           ms/op
ClientPb.listUser                       sample  254371   3.772 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.360           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.553           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.675           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.150           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.508           ms/op
