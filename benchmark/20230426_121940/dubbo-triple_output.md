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
# Warmup Iteration   1: 2.182 ops/ms
# Warmup Iteration   2: 5.733 ops/ms
# Warmup Iteration   3: 8.931 ops/ms
Iteration   1: 9.294 ops/ms
Iteration   2: 9.622 ops/ms
Iteration   3: 9.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.370 ±(99.9%) 4.072 ops/ms [Average]
  (min, avg, max) = (9.196, 9.370, 9.622), stdev = 0.223
  CI (99.9%): [5.298, 13.442] (assumes normal distribution)


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
# Warmup Iteration   1: 3.026 ops/ms
# Warmup Iteration   2: 8.957 ops/ms
# Warmup Iteration   3: 9.656 ops/ms
Iteration   1: 9.745 ops/ms
Iteration   2: 9.515 ops/ms
Iteration   3: 10.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.775 ±(99.9%) 5.053 ops/ms [Average]
  (min, avg, max) = (9.515, 9.775, 10.066), stdev = 0.277
  CI (99.9%): [4.722, 14.829] (assumes normal distribution)


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
# Warmup Iteration   1: 2.957 ops/ms
# Warmup Iteration   2: 8.571 ops/ms
# Warmup Iteration   3: 9.019 ops/ms
Iteration   1: 9.421 ops/ms
Iteration   2: 9.069 ops/ms
Iteration   3: 9.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.288 ±(99.9%) 3.493 ops/ms [Average]
  (min, avg, max) = (9.069, 9.288, 9.421), stdev = 0.191
  CI (99.9%): [5.795, 12.782] (assumes normal distribution)


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
# Warmup Iteration   1: 2.840 ops/ms
# Warmup Iteration   2: 7.400 ops/ms
# Warmup Iteration   3: 7.670 ops/ms
Iteration   1: 7.839 ops/ms
Iteration   2: 8.031 ops/ms
Iteration   3: 8.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.021 ±(99.9%) 3.232 ops/ms [Average]
  (min, avg, max) = (7.839, 8.021, 8.193), stdev = 0.177
  CI (99.9%): [4.789, 11.253] (assumes normal distribution)


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
# Warmup Iteration   1: 9.187 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.818 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.005 ms/op
Iteration   1: 3.580 ±(99.9%) 0.002 ms/op
Iteration   2: 3.528 ±(99.9%) 0.009 ms/op
Iteration   3: 3.309 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.473 ±(99.9%) 2.630 ms/op [Average]
  (min, avg, max) = (3.309, 3.473, 3.580), stdev = 0.144
  CI (99.9%): [0.843, 6.102] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.732 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.005 ms/op
Iteration   1: 3.227 ±(99.9%) 0.008 ms/op
Iteration   2: 3.161 ±(99.9%) 0.011 ms/op
Iteration   3: 3.269 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.219 ±(99.9%) 1.001 ms/op [Average]
  (min, avg, max) = (3.161, 3.219, 3.269), stdev = 0.055
  CI (99.9%): [2.218, 4.220] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.932 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.004 ms/op
Iteration   1: 3.434 ±(99.9%) 0.003 ms/op
Iteration   2: 3.400 ±(99.9%) 0.008 ms/op
Iteration   3: 3.346 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.393 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (3.346, 3.393, 3.434), stdev = 0.045
  CI (99.9%): [2.578, 4.208] (assumes normal distribution)


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
# Warmup Iteration   1: 11.287 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.023 ±(99.9%) 0.009 ms/op
Iteration   1: 3.968 ±(99.9%) 0.007 ms/op
Iteration   2: 4.036 ±(99.9%) 0.009 ms/op
Iteration   3: 3.881 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.962 ±(99.9%) 1.419 ms/op [Average]
  (min, avg, max) = (3.881, 3.962, 4.036), stdev = 0.078
  CI (99.9%): [2.543, 5.381] (assumes normal distribution)


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
# Warmup Iteration   1: 9.392 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.007 ms/op
Iteration   1: 3.350 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  19.135 ms/op
                 createUser·p0.9999: 22.195 ms/op
                 createUser·p1.00:   23.069 ms/op

Iteration   2: 3.404 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  21.371 ms/op
                 createUser·p0.9999: 25.874 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   3: 3.376 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  15.899 ms/op
                 createUser·p0.9999: 23.094 ms/op
                 createUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283941
  mean =      3.376 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3635 
    [ 2.500,  5.000) = 274019 
    [ 5.000,  7.500) = 5157 
    [ 7.500, 10.000) = 667 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     15.968 ms/op
     p(99.9900) =     24.871 ms/op
     p(99.9990) =     26.089 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 7.713 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.011 ms/op
Iteration   1: 3.344 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.649 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  20.057 ms/op
                 existUser·p0.9999: 22.554 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   2: 3.225 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.321 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  9.961 ms/op
                 existUser·p0.9999: 24.707 ms/op
                 existUser·p1.00:   25.690 ms/op

Iteration   3: 3.278 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  7.512 ms/op
                 existUser·p0.9999: 26.689 ms/op
                 existUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292474
  mean =      3.281 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11032 
    [ 2.500,  5.000) = 275169 
    [ 5.000,  7.500) = 5433 
    [ 7.500, 10.000) = 501 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     10.961 ms/op
     p(99.9900) =     25.510 ms/op
     p(99.9990) =     26.971 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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
# Warmup Iteration   1: 8.745 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.010 ms/op
Iteration   1: 3.573 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.714 ms/op
                 getUser·p0.99:   7.375 ms/op
                 getUser·p0.999:  21.113 ms/op
                 getUser·p0.9999: 26.871 ms/op
                 getUser·p1.00:   29.327 ms/op

Iteration   2: 3.542 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  22.430 ms/op
                 getUser·p0.9999: 24.672 ms/op
                 getUser·p1.00:   25.756 ms/op

Iteration   3: 3.631 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.802 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  23.161 ms/op
                 getUser·p0.9999: 26.030 ms/op
                 getUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268115
  mean =      3.582 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14012 
    [ 2.500,  5.000) = 244301 
    [ 5.000,  7.500) = 8366 
    [ 7.500, 10.000) = 970 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 188 
    [25.000, 27.500) = 70 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     22.373 ms/op
     p(99.9900) =     25.991 ms/op
     p(99.9990) =     28.049 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 9.489 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.493 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.146 ±(99.9%) 0.014 ms/op
Iteration   1: 3.950 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  17.759 ms/op
                 listUser·p0.9999: 24.875 ms/op
                 listUser·p1.00:   25.952 ms/op

Iteration   2: 3.884 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  14.296 ms/op
                 listUser·p0.9999: 15.991 ms/op
                 listUser·p1.00:   16.400 ms/op

Iteration   3: 3.955 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  15.944 ms/op
                 listUser·p0.9999: 19.688 ms/op
                 listUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244354
  mean =      3.929 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 238254 
    [ 5.000,  7.500) = 4587 
    [ 7.500, 10.000) = 766 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     15.461 ms/op
     p(99.9900) =     23.423 ms/op
     p(99.9990) =     25.523 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.370 ± 4.072  ops/ms
ClientPb.existUser                       thrpt       3   9.775 ± 5.053  ops/ms
ClientPb.getUser                         thrpt       3   9.288 ± 3.493  ops/ms
ClientPb.listUser                        thrpt       3   8.021 ± 3.232  ops/ms
ClientPb.createUser                       avgt       3   3.473 ± 2.630   ms/op
ClientPb.existUser                        avgt       3   3.219 ± 1.001   ms/op
ClientPb.getUser                          avgt       3   3.393 ± 0.815   ms/op
ClientPb.listUser                         avgt       3   3.962 ± 1.419   ms/op
ClientPb.createUser                     sample  283941   3.376 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.988           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.964           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.968           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.871           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.378           ms/op
ClientPb.existUser                      sample  292474   3.281 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.321           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.985           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.961           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.510           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.099           ms/op
ClientPb.getUser                        sample  268115   3.582 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.262           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.441           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.595           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.373           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.991           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.327           ms/op
ClientPb.listUser                       sample  244354   3.929 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.896           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.611           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.461           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.423           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.952           ms/op
