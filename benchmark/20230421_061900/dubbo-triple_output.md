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
# Warmup Iteration   1: 1.947 ops/ms
# Warmup Iteration   2: 5.633 ops/ms
# Warmup Iteration   3: 8.301 ops/ms
Iteration   1: 8.978 ops/ms
Iteration   2: 8.957 ops/ms
Iteration   3: 8.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.965 ±(99.9%) 0.211 ops/ms [Average]
  (min, avg, max) = (8.957, 8.965, 8.978), stdev = 0.012
  CI (99.9%): [8.754, 9.176] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.529 ops/ms
# Warmup Iteration   2: 8.795 ops/ms
# Warmup Iteration   3: 9.405 ops/ms
Iteration   1: 9.726 ops/ms
Iteration   2: 9.748 ops/ms
Iteration   3: 9.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.682 ±(99.9%) 1.731 ops/ms [Average]
  (min, avg, max) = (9.573, 9.682, 9.748), stdev = 0.095
  CI (99.9%): [7.952, 11.413] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.548 ops/ms
# Warmup Iteration   2: 7.865 ops/ms
# Warmup Iteration   3: 9.051 ops/ms
Iteration   1: 9.306 ops/ms
Iteration   2: 9.286 ops/ms
Iteration   3: 9.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.336 ±(99.9%) 1.293 ops/ms [Average]
  (min, avg, max) = (9.286, 9.336, 9.417), stdev = 0.071
  CI (99.9%): [8.044, 10.629] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.745 ops/ms
# Warmup Iteration   2: 7.124 ops/ms
# Warmup Iteration   3: 7.955 ops/ms
Iteration   1: 7.839 ops/ms
Iteration   2: 7.891 ops/ms
Iteration   3: 7.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.910 ±(99.9%) 1.479 ops/ms [Average]
  (min, avg, max) = (7.839, 7.910, 7.998), stdev = 0.081
  CI (99.9%): [6.430, 9.389] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.471 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.660 ±(99.9%) 0.007 ms/op
Iteration   1: 3.474 ±(99.9%) 0.011 ms/op
Iteration   2: 3.429 ±(99.9%) 0.012 ms/op
Iteration   3: 3.447 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.450 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (3.429, 3.450, 3.474), stdev = 0.022
  CI (99.9%): [3.041, 3.860] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.238 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.585 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.007 ms/op
Iteration   1: 3.348 ±(99.9%) 0.009 ms/op
Iteration   2: 3.333 ±(99.9%) 0.012 ms/op
Iteration   3: 3.447 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.376 ±(99.9%) 1.132 ms/op [Average]
  (min, avg, max) = (3.333, 3.376, 3.447), stdev = 0.062
  CI (99.9%): [2.244, 4.508] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.819 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.779 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.010 ms/op
Iteration   1: 3.451 ±(99.9%) 0.009 ms/op
Iteration   2: 3.413 ±(99.9%) 0.010 ms/op
Iteration   3: 3.581 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.482 ±(99.9%) 1.609 ms/op [Average]
  (min, avg, max) = (3.413, 3.482, 3.581), stdev = 0.088
  CI (99.9%): [1.872, 5.091] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.894 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.390 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.156 ±(99.9%) 0.012 ms/op
Iteration   1: 4.072 ±(99.9%) 0.014 ms/op
Iteration   2: 3.892 ±(99.9%) 0.013 ms/op
Iteration   3: 3.962 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.975 ±(99.9%) 1.656 ms/op [Average]
  (min, avg, max) = (3.892, 3.975, 4.072), stdev = 0.091
  CI (99.9%): [2.319, 5.632] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.090 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.302 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.012 ms/op
Iteration   1: 3.488 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  21.365 ms/op
                 createUser·p0.9999: 26.602 ms/op
                 createUser·p1.00:   27.099 ms/op

Iteration   2: 3.583 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.602 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  22.040 ms/op
                 createUser·p0.9999: 26.905 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   3: 3.417 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  22.132 ms/op
                 createUser·p0.9999: 29.360 ms/op
                 createUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274469
  mean =      3.495 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8218 
    [ 2.500,  5.000) = 258406 
    [ 5.000,  7.500) = 6555 
    [ 7.500, 10.000) = 722 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 137 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     21.825 ms/op
     p(99.9900) =     27.962 ms/op
     p(99.9990) =     29.967 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.034 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.417 ±(99.9%) 0.009 ms/op
Iteration   1: 3.339 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.722 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  20.157 ms/op
                 existUser·p0.9999: 27.997 ms/op
                 existUser·p1.00:   29.426 ms/op

Iteration   2: 3.238 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.694 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  12.173 ms/op
                 existUser·p0.9999: 30.708 ms/op
                 existUser·p1.00:   31.425 ms/op

Iteration   3: 3.374 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.448 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  22.979 ms/op
                 existUser·p0.9999: 27.592 ms/op
                 existUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289377
  mean =      3.316 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8551 
    [ 2.500,  5.000) = 276781 
    [ 5.000,  7.500) = 3072 
    [ 7.500, 10.000) = 492 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     19.089 ms/op
     p(99.9900) =     29.463 ms/op
     p(99.9990) =     31.337 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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
# Warmup Iteration   1: 9.026 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.954 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.621 ±(99.9%) 0.010 ms/op
Iteration   1: 3.692 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   5.267 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  22.245 ms/op
                 getUser·p0.9999: 54.788 ms/op
                 getUser·p1.00:   56.361 ms/op

Iteration   2: 3.513 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  25.884 ms/op
                 getUser·p0.9999: 31.159 ms/op
                 getUser·p1.00:   31.883 ms/op

Iteration   3: 3.526 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  21.692 ms/op
                 getUser·p0.9999: 28.115 ms/op
                 getUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268229
  mean =      3.575 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 259314 
    [ 5.000, 10.000) = 8398 
    [10.000, 15.000) = 221 
    [15.000, 20.000) = 7 
    [20.000, 25.000) = 68 
    [25.000, 30.000) = 163 
    [30.000, 35.000) = 26 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     22.103 ms/op
     p(99.9900) =     52.976 ms/op
     p(99.9990) =     56.120 ms/op
     p(99.9999) =     56.361 ms/op
    p(100.0000) =     56.361 ms/op


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
# Warmup Iteration   1: 11.075 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.529 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.336 ±(99.9%) 0.014 ms/op
Iteration   1: 4.179 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.911 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.833 ms/op
                 listUser·p0.999:  21.000 ms/op
                 listUser·p0.9999: 29.032 ms/op
                 listUser·p1.00:   29.884 ms/op

Iteration   2: 4.163 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.796 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   8.184 ms/op
                 listUser·p0.999:  16.253 ms/op
                 listUser·p0.9999: 17.847 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   3: 4.040 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  17.165 ms/op
                 listUser·p0.9999: 23.265 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232500
  mean =      4.126 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 225015 
    [ 5.000,  7.500) = 4829 
    [ 7.500, 10.000) = 1678 
    [10.000, 12.500) = 394 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 222 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.796 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     27.484 ms/op
     p(99.9990) =     29.428 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.965 ± 0.211  ops/ms
ClientPb.existUser                       thrpt       3   9.682 ± 1.731  ops/ms
ClientPb.getUser                         thrpt       3   9.336 ± 1.293  ops/ms
ClientPb.listUser                        thrpt       3   7.910 ± 1.479  ops/ms
ClientPb.createUser                       avgt       3   3.450 ± 0.410   ms/op
ClientPb.existUser                        avgt       3   3.376 ± 1.132   ms/op
ClientPb.getUser                          avgt       3   3.482 ± 1.609   ms/op
ClientPb.listUser                         avgt       3   3.975 ± 1.656   ms/op
ClientPb.createUser                     sample  274469   3.495 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.696           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.555           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.029           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.825           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.962           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.147           ms/op
ClientPb.existUser                      sample  289377   3.316 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.448           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.973           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.089           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.463           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.425           ms/op
ClientPb.getUser                        sample  268229   3.575 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.092           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.424           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.398           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.103           ms/op
ClientPb.getUser:getUser·p0.9999        sample          52.976           ms/op
ClientPb.getUser:getUser·p1.00          sample          56.361           ms/op
ClientPb.listUser                       sample  232500   4.126 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.796           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.807           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.908           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.484           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.884           ms/op
