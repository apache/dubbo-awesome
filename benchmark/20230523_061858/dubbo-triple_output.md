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
# Warmup Iteration   1: 1.841 ops/ms
# Warmup Iteration   2: 4.827 ops/ms
# Warmup Iteration   3: 8.391 ops/ms
Iteration   1: 8.432 ops/ms
Iteration   2: 9.144 ops/ms
Iteration   3: 9.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.949 ±(99.9%) 8.252 ops/ms [Average]
  (min, avg, max) = (8.432, 8.949, 9.272), stdev = 0.452
  CI (99.9%): [0.697, 17.202] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.842 ops/ms
# Warmup Iteration   2: 8.257 ops/ms
# Warmup Iteration   3: 8.942 ops/ms
Iteration   1: 9.463 ops/ms
Iteration   2: 8.909 ops/ms
Iteration   3: 9.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.182 ±(99.9%) 5.062 ops/ms [Average]
  (min, avg, max) = (8.909, 9.182, 9.463), stdev = 0.277
  CI (99.9%): [4.120, 14.244] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.509 ops/ms
# Warmup Iteration   2: 7.999 ops/ms
# Warmup Iteration   3: 8.913 ops/ms
Iteration   1: 9.152 ops/ms
Iteration   2: 9.524 ops/ms
Iteration   3: 9.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.232 ±(99.9%) 4.775 ops/ms [Average]
  (min, avg, max) = (9.019, 9.232, 9.524), stdev = 0.262
  CI (99.9%): [4.456, 14.007] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.677 ops/ms
# Warmup Iteration   2: 7.088 ops/ms
# Warmup Iteration   3: 7.647 ops/ms
Iteration   1: 7.933 ops/ms
Iteration   2: 7.955 ops/ms
Iteration   3: 8.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.020 ±(99.9%) 2.415 ops/ms [Average]
  (min, avg, max) = (7.933, 8.020, 8.172), stdev = 0.132
  CI (99.9%): [5.605, 10.435] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.772 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.663 ±(99.9%) 0.006 ms/op
Iteration   1: 3.541 ±(99.9%) 0.004 ms/op
Iteration   2: 3.701 ±(99.9%) 0.005 ms/op
Iteration   3: 3.421 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.555 ±(99.9%) 2.562 ms/op [Average]
  (min, avg, max) = (3.421, 3.555, 3.701), stdev = 0.140
  CI (99.9%): [0.992, 6.117] (assumes normal distribution)


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
# Warmup Iteration   1: 9.911 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.004 ms/op
Iteration   1: 3.404 ±(99.9%) 0.012 ms/op
Iteration   2: 3.228 ±(99.9%) 0.008 ms/op
Iteration   3: 3.277 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.303 ±(99.9%) 1.658 ms/op [Average]
  (min, avg, max) = (3.228, 3.303, 3.404), stdev = 0.091
  CI (99.9%): [1.645, 4.961] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.523 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.006 ms/op
Iteration   1: 3.493 ±(99.9%) 0.008 ms/op
Iteration   2: 3.374 ±(99.9%) 0.002 ms/op
Iteration   3: 3.409 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.425 ±(99.9%) 1.117 ms/op [Average]
  (min, avg, max) = (3.374, 3.425, 3.493), stdev = 0.061
  CI (99.9%): [2.308, 4.543] (assumes normal distribution)


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
# Warmup Iteration   1: 11.314 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.441 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.008 ms/op
Iteration   1: 3.867 ±(99.9%) 0.012 ms/op
Iteration   2: 3.906 ±(99.9%) 0.014 ms/op
Iteration   3: 3.930 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.901 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (3.867, 3.901, 3.930), stdev = 0.032
  CI (99.9%): [3.322, 4.480] (assumes normal distribution)


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
# Warmup Iteration   1: 10.138 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.008 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.638 ±(99.9%) 0.012 ms/op
Iteration   1: 3.780 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   6.439 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  20.283 ms/op
                 createUser·p0.9999: 23.021 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   2: 3.417 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  22.242 ms/op
                 createUser·p0.9999: 27.206 ms/op
                 createUser·p1.00:   27.886 ms/op

Iteration   3: 3.500 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  19.454 ms/op
                 createUser·p0.9999: 28.806 ms/op
                 createUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269561
  mean =      3.559 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3220 
    [ 2.500,  5.000) = 253829 
    [ 5.000,  7.500) = 11067 
    [ 7.500, 10.000) = 931 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     20.134 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     30.000 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.277 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.010 ms/op
Iteration   1: 3.362 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  20.259 ms/op
                 existUser·p0.9999: 23.083 ms/op
                 existUser·p1.00:   23.724 ms/op

Iteration   2: 3.368 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  11.436 ms/op
                 existUser·p0.9999: 25.903 ms/op
                 existUser·p1.00:   27.165 ms/op

Iteration   3: 3.569 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.325 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  21.425 ms/op
                 existUser·p0.9999: 28.475 ms/op
                 existUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279805
  mean =      3.430 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9762 
    [ 2.500,  5.000) = 263524 
    [ 5.000,  7.500) = 5599 
    [ 7.500, 10.000) = 533 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      0.325 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =     27.951 ms/op
     p(99.9990) =     28.922 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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
# Warmup Iteration   1: 9.055 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.707 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.011 ms/op
Iteration   1: 3.448 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.593 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  20.914 ms/op
                 getUser·p0.9999: 23.730 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   2: 3.436 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  21.167 ms/op
                 getUser·p0.9999: 24.785 ms/op
                 getUser·p1.00:   28.606 ms/op

Iteration   3: 3.449 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  21.277 ms/op
                 getUser·p0.9999: 35.241 ms/op
                 getUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278476
  mean =      3.444 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3717 
    [ 2.500,  5.000) = 266477 
    [ 5.000,  7.500) = 6908 
    [ 7.500, 10.000) = 874 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     35.666 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.615 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.547 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.394 ±(99.9%) 0.016 ms/op
Iteration   1: 4.247 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.021 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  22.658 ms/op
                 listUser·p0.9999: 30.621 ms/op
                 listUser·p1.00:   31.457 ms/op

Iteration   2: 4.080 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  15.560 ms/op
                 listUser·p0.9999: 28.874 ms/op
                 listUser·p1.00:   31.064 ms/op

Iteration   3: 4.153 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.905 ms/op
                 listUser·p0.999:  14.974 ms/op
                 listUser·p0.9999: 17.157 ms/op
                 listUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230599
  mean =      4.159 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 221378 
    [ 5.000,  7.500) = 6474 
    [ 7.500, 10.000) = 1990 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.021 ms/op
     p(50.0000) =      4.030 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     15.647 ms/op
     p(99.9900) =     29.715 ms/op
     p(99.9990) =     31.306 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.949 ± 8.252  ops/ms
ClientPb.existUser                       thrpt       3   9.182 ± 5.062  ops/ms
ClientPb.getUser                         thrpt       3   9.232 ± 4.775  ops/ms
ClientPb.listUser                        thrpt       3   8.020 ± 2.415  ops/ms
ClientPb.createUser                       avgt       3   3.555 ± 2.562   ms/op
ClientPb.existUser                        avgt       3   3.303 ± 1.658   ms/op
ClientPb.getUser                          avgt       3   3.425 ± 1.117   ms/op
ClientPb.listUser                         avgt       3   3.901 ± 0.579   ms/op
ClientPb.createUser                     sample  269561   3.559 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.133           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.096           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.874           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.012           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.134           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.623           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.147           ms/op
ClientPb.existUser                      sample  279805   3.430 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.325           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.912           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.898           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.418           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.951           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.721           ms/op
ClientPb.getUser                        sample  278476   3.444 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.266           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.084           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.414           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.037           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.406           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.307           ms/op
ClientPb.listUser                       sample  230599   4.159 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.021           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.030           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.807           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.647           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.715           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.457           ms/op
