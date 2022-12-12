# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.628 ops/ms
# Warmup Iteration   2: 6.874 ops/ms
# Warmup Iteration   3: 8.923 ops/ms
Iteration   1: 10.192 ops/ms
Iteration   2: 10.498 ops/ms
Iteration   3: 10.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.281 ±(99.9%) 3.437 ops/ms [Average]
  (min, avg, max) = (10.155, 10.281, 10.498), stdev = 0.188
  CI (99.9%): [6.845, 13.718] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.582 ops/ms
# Warmup Iteration   2: 9.895 ops/ms
# Warmup Iteration   3: 10.191 ops/ms
Iteration   1: 10.356 ops/ms
Iteration   2: 10.311 ops/ms
Iteration   3: 10.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.387 ±(99.9%) 1.743 ops/ms [Average]
  (min, avg, max) = (10.311, 10.387, 10.494), stdev = 0.096
  CI (99.9%): [8.644, 12.130] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.673 ops/ms
# Warmup Iteration   2: 9.107 ops/ms
# Warmup Iteration   3: 10.091 ops/ms
Iteration   1: 10.105 ops/ms
Iteration   2: 9.650 ops/ms
Iteration   3: 10.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.035 ±(99.9%) 6.475 ops/ms [Average]
  (min, avg, max) = (9.650, 10.035, 10.349), stdev = 0.355
  CI (99.9%): [3.560, 16.510] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.446 ops/ms
# Warmup Iteration   2: 7.421 ops/ms
# Warmup Iteration   3: 8.469 ops/ms
Iteration   1: 8.512 ops/ms
Iteration   2: 8.660 ops/ms
Iteration   3: 8.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.600 ±(99.9%) 1.419 ops/ms [Average]
  (min, avg, max) = (8.512, 8.600, 8.660), stdev = 0.078
  CI (99.9%): [7.181, 10.019] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.725 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.534 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.006 ms/op
Iteration   1: 3.243 ±(99.9%) 0.007 ms/op
Iteration   2: 3.209 ±(99.9%) 0.006 ms/op
Iteration   3: 3.153 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.202 ±(99.9%) 0.833 ms/op [Average]
  (min, avg, max) = (3.153, 3.202, 3.243), stdev = 0.046
  CI (99.9%): [2.368, 4.035] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.510 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.313 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.004 ms/op
Iteration   1: 2.991 ±(99.9%) 0.003 ms/op
Iteration   2: 3.062 ±(99.9%) 0.009 ms/op
Iteration   3: 2.993 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.015 ±(99.9%) 0.736 ms/op [Average]
  (min, avg, max) = (2.991, 3.015, 3.062), stdev = 0.040
  CI (99.9%): [2.279, 3.751] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.926 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.598 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.005 ms/op
Iteration   1: 3.201 ±(99.9%) 0.008 ms/op
Iteration   2: 3.198 ±(99.9%) 0.008 ms/op
Iteration   3: 3.272 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.224 ±(99.9%) 0.770 ms/op [Average]
  (min, avg, max) = (3.198, 3.224, 3.272), stdev = 0.042
  CI (99.9%): [2.454, 3.993] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.750 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.735 ±(99.9%) 0.009 ms/op
Iteration   1: 3.702 ±(99.9%) 0.009 ms/op
Iteration   2: 3.612 ±(99.9%) 0.010 ms/op
Iteration   3: 3.741 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.685 ±(99.9%) 1.204 ms/op [Average]
  (min, avg, max) = (3.612, 3.685, 3.741), stdev = 0.066
  CI (99.9%): [2.481, 4.889] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.898 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.009 ms/op
Iteration   1: 3.094 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  10.043 ms/op
                 createUser·p0.9999: 30.190 ms/op
                 createUser·p1.00:   31.752 ms/op

Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  8.716 ms/op
                 createUser·p0.9999: 27.767 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   3: 3.302 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  15.260 ms/op
                 createUser·p0.9999: 24.347 ms/op
                 createUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302115
  mean =      3.176 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22075 
    [ 2.500,  5.000) = 274941 
    [ 5.000,  7.500) = 4395 
    [ 7.500, 10.000) = 373 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     14.328 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     31.490 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.497 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.419 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.008 ms/op
Iteration   1: 3.122 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.506 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  8.339 ms/op
                 existUser·p0.9999: 18.169 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  8.598 ms/op
                 existUser·p0.9999: 25.599 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   3: 3.291 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  9.904 ms/op
                 existUser·p0.9999: 21.341 ms/op
                 existUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304290
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25337 
    [ 2.500,  5.000) = 272925 
    [ 5.000,  7.500) = 5435 
    [ 7.500, 10.000) = 304 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     23.986 ms/op
     p(99.9990) =     26.330 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.129 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.433 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.009 ms/op
Iteration   1: 3.254 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.554 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  14.547 ms/op
                 getUser·p0.9999: 25.636 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   2: 3.327 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  18.816 ms/op
                 getUser·p0.9999: 22.656 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   3: 3.240 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.123 ms/op
                 getUser·p0.999:  11.438 ms/op
                 getUser·p0.9999: 21.369 ms/op
                 getUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293027
  mean =      3.273 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22168 
    [ 2.500,  5.000) = 262197 
    [ 5.000,  7.500) = 7851 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 174 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     14.049 ms/op
     p(99.9900) =     23.966 ms/op
     p(99.9990) =     25.826 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.920 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.241 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.013 ms/op
Iteration   1: 3.791 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  18.242 ms/op
                 listUser·p0.9999: 21.902 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   2: 3.827 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  16.040 ms/op
                 listUser·p0.9999: 17.606 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   3: 3.754 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.673 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.925 ms/op
                 listUser·p0.999:  12.780 ms/op
                 listUser·p0.9999: 16.341 ms/op
                 listUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253087
  mean =      3.790 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 82 
    [ 2.500,  5.000) = 242764 
    [ 5.000,  7.500) = 8318 
    [ 7.500, 10.000) = 1135 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     14.527 ms/op
     p(99.9900) =     20.732 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.281 ± 3.437  ops/ms
ClientPb.existUser                       thrpt       3  10.387 ± 1.743  ops/ms
ClientPb.getUser                         thrpt       3  10.035 ± 6.475  ops/ms
ClientPb.listUser                        thrpt       3   8.600 ± 1.419  ops/ms
ClientPb.createUser                       avgt       3   3.202 ± 0.833   ms/op
ClientPb.existUser                        avgt       3   3.015 ± 0.736   ms/op
ClientPb.getUser                          avgt       3   3.224 ± 0.770   ms/op
ClientPb.listUser                         avgt       3   3.685 ± 1.204   ms/op
ClientPb.createUser                     sample  302115   3.176 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.231           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.613           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.328           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.460           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.752           ms/op
ClientPb.existUser                      sample  304290   3.155 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.506           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.520           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.986           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.034           ms/op
ClientPb.getUser                        sample  293027   3.273 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.186           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.021           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.049           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.966           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.919           ms/op
ClientPb.listUser                       sample  253087   3.790 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.409           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.629           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.527           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.732           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.675           ms/op
