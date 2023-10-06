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
# Warmup Iteration   1: 2.486 ops/ms
# Warmup Iteration   2: 6.305 ops/ms
# Warmup Iteration   3: 8.851 ops/ms
Iteration   1: 9.454 ops/ms
Iteration   2: 9.379 ops/ms
Iteration   3: 9.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.578 ±(99.9%) 5.121 ops/ms [Average]
  (min, avg, max) = (9.379, 9.578, 9.899), stdev = 0.281
  CI (99.9%): [4.456, 14.699] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.305 ops/ms
# Warmup Iteration   2: 9.416 ops/ms
# Warmup Iteration   3: 10.012 ops/ms
Iteration   1: 10.106 ops/ms
Iteration   2: 10.180 ops/ms
Iteration   3: 10.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.114 ±(99.9%) 1.145 ops/ms [Average]
  (min, avg, max) = (10.055, 10.114, 10.180), stdev = 0.063
  CI (99.9%): [8.969, 11.259] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.511 ops/ms
# Warmup Iteration   2: 8.966 ops/ms
# Warmup Iteration   3: 9.743 ops/ms
Iteration   1: 9.646 ops/ms
Iteration   2: 9.509 ops/ms
Iteration   3: 9.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.636 ±(99.9%) 2.234 ops/ms [Average]
  (min, avg, max) = (9.509, 9.636, 9.753), stdev = 0.122
  CI (99.9%): [7.402, 11.870] (assumes normal distribution)


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
# Warmup Iteration   1: 3.265 ops/ms
# Warmup Iteration   2: 7.752 ops/ms
# Warmup Iteration   3: 8.176 ops/ms
Iteration   1: 8.258 ops/ms
Iteration   2: 8.340 ops/ms
Iteration   3: 8.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.322 ±(99.9%) 1.043 ops/ms [Average]
  (min, avg, max) = (8.258, 8.322, 8.369), stdev = 0.057
  CI (99.9%): [7.279, 9.366] (assumes normal distribution)


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
# Warmup Iteration   1: 9.339 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.003 ms/op
Iteration   1: 3.250 ±(99.9%) 0.002 ms/op
Iteration   2: 3.239 ±(99.9%) 0.002 ms/op
Iteration   3: 3.244 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.245 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (3.239, 3.245, 3.250), stdev = 0.005
  CI (99.9%): [3.146, 3.343] (assumes normal distribution)


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
# Warmup Iteration   1: 8.332 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.003 ms/op
Iteration   1: 3.156 ±(99.9%) 0.002 ms/op
Iteration   2: 3.051 ±(99.9%) 0.002 ms/op
Iteration   3: 3.100 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.103 ±(99.9%) 0.959 ms/op [Average]
  (min, avg, max) = (3.051, 3.103, 3.156), stdev = 0.053
  CI (99.9%): [2.144, 4.062] (assumes normal distribution)


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
# Warmup Iteration   1: 7.284 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.402 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.002 ms/op
Iteration   1: 3.277 ±(99.9%) 0.003 ms/op
Iteration   2: 3.274 ±(99.9%) 0.002 ms/op
Iteration   3: 3.203 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.252 ±(99.9%) 0.765 ms/op [Average]
  (min, avg, max) = (3.203, 3.252, 3.277), stdev = 0.042
  CI (99.9%): [2.487, 4.016] (assumes normal distribution)


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
# Warmup Iteration   1: 9.207 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.005 ms/op
Iteration   1: 3.848 ±(99.9%) 0.004 ms/op
Iteration   2: 3.828 ±(99.9%) 0.004 ms/op
Iteration   3: 3.813 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.830 ±(99.9%) 0.312 ms/op [Average]
  (min, avg, max) = (3.813, 3.830, 3.848), stdev = 0.017
  CI (99.9%): [3.517, 4.142] (assumes normal distribution)


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
# Warmup Iteration   1: 7.773 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.009 ms/op
Iteration   1: 3.316 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.559 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  17.072 ms/op
                 createUser·p0.9999: 19.815 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  18.907 ms/op
                 createUser·p0.9999: 20.513 ms/op
                 createUser·p1.00:   22.086 ms/op

Iteration   3: 3.212 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  14.500 ms/op
                 createUser·p0.9999: 19.438 ms/op
                 createUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295833
  mean =      3.244 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9455 
    [ 2.500,  5.000) = 280897 
    [ 5.000,  7.500) = 4541 
    [ 7.500, 10.000) = 350 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 187 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     15.248 ms/op
     p(99.9900) =     20.199 ms/op
     p(99.9990) =     20.879 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 7.592 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.334 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.008 ms/op
Iteration   1: 3.207 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  16.015 ms/op
                 existUser·p0.9999: 20.186 ms/op
                 existUser·p1.00:   20.906 ms/op

Iteration   2: 3.209 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  15.748 ms/op
                 existUser·p0.9999: 22.413 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   3: 3.087 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.651 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.938 ms/op
                 existUser·p0.9999: 20.239 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302836
  mean =      3.167 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22104 
    [ 2.500,  5.000) = 276820 
    [ 5.000,  7.500) = 3075 
    [ 7.500, 10.000) = 259 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     21.323 ms/op
     p(99.9990) =     23.033 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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
# Warmup Iteration   1: 8.866 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.009 ms/op
Iteration   1: 3.330 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  16.105 ms/op
                 getUser·p0.9999: 19.300 ms/op
                 getUser·p1.00:   19.759 ms/op

Iteration   2: 3.226 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  8.892 ms/op
                 getUser·p0.9999: 23.626 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   3: 3.260 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  17.493 ms/op
                 getUser·p0.9999: 21.266 ms/op
                 getUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293374
  mean =      3.272 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19146 
    [ 2.500,  5.000) = 267017 
    [ 5.000,  7.500) = 6336 
    [ 7.500, 10.000) = 427 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     16.224 ms/op
     p(99.9900) =     22.435 ms/op
     p(99.9990) =     24.095 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 8.031 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.011 ms/op
Iteration   1: 3.854 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.622 ms/op
                 listUser·p0.9999: 20.667 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   2: 3.834 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  14.133 ms/op
                 listUser·p0.9999: 16.951 ms/op
                 listUser·p1.00:   17.662 ms/op

Iteration   3: 3.857 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  13.765 ms/op
                 listUser·p0.9999: 20.044 ms/op
                 listUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249286
  mean =      3.848 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 242652 
    [ 5.000,  7.500) = 5128 
    [ 7.500, 10.000) = 769 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 400 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.468 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     14.380 ms/op
     p(99.9900) =     19.490 ms/op
     p(99.9990) =     21.546 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.578 ± 5.121  ops/ms
ClientPb.existUser                       thrpt       3  10.114 ± 1.145  ops/ms
ClientPb.getUser                         thrpt       3   9.636 ± 2.234  ops/ms
ClientPb.listUser                        thrpt       3   8.322 ± 1.043  ops/ms
ClientPb.createUser                       avgt       3   3.245 ± 0.099   ms/op
ClientPb.existUser                        avgt       3   3.103 ± 0.959   ms/op
ClientPb.getUser                          avgt       3   3.252 ± 0.765   ms/op
ClientPb.listUser                         avgt       3   3.830 ± 0.312   ms/op
ClientPb.createUser                     sample  295833   3.244 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.143           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.248           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.199           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.086           ms/op
ClientPb.existUser                      sample  302836   3.167 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.219           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.469           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.467           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.323           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.134           ms/op
ClientPb.getUser                        sample  293374   3.272 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.067           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.234           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.224           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.435           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.347           ms/op
ClientPb.listUser                       sample  249286   3.848 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.468           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.736           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.849           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.380           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.490           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.692           ms/op
