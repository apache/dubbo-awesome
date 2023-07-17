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
# Warmup Iteration   1: 0.926 ops/ms
# Warmup Iteration   2: 2.107 ops/ms
# Warmup Iteration   3: 4.581 ops/ms
Iteration   1: 5.565 ops/ms
Iteration   2: 5.598 ops/ms
Iteration   3: 5.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.665 ±(99.9%) 2.641 ops/ms [Average]
  (min, avg, max) = (5.565, 5.665, 5.831), stdev = 0.145
  CI (99.9%): [3.024, 8.306] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.649 ops/ms
# Warmup Iteration   2: 4.542 ops/ms
# Warmup Iteration   3: 5.711 ops/ms
Iteration   1: 6.240 ops/ms
Iteration   2: 6.187 ops/ms
Iteration   3: 5.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.059 ±(99.9%) 4.907 ops/ms [Average]
  (min, avg, max) = (5.750, 6.059, 6.240), stdev = 0.269
  CI (99.9%): [1.152, 10.966] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.418 ops/ms
# Warmup Iteration   2: 3.703 ops/ms
# Warmup Iteration   3: 5.189 ops/ms
Iteration   1: 5.317 ops/ms
Iteration   2: 5.529 ops/ms
Iteration   3: 5.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.557 ±(99.9%) 4.658 ops/ms [Average]
  (min, avg, max) = (5.317, 5.557, 5.825), stdev = 0.255
  CI (99.9%): [0.899, 10.215] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.454 ops/ms
# Warmup Iteration   2: 3.959 ops/ms
# Warmup Iteration   3: 4.732 ops/ms
Iteration   1: 5.091 ops/ms
Iteration   2: 4.877 ops/ms
Iteration   3: 4.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.986 ±(99.9%) 1.961 ops/ms [Average]
  (min, avg, max) = (4.877, 4.986, 5.091), stdev = 0.107
  CI (99.9%): [3.026, 6.947] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 19.449 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 6.657 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.015 ±(99.9%) 0.007 ms/op
Iteration   1: 5.821 ±(99.9%) 0.014 ms/op
Iteration   2: 5.633 ±(99.9%) 0.011 ms/op
Iteration   3: 5.667 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.707 ±(99.9%) 1.828 ms/op [Average]
  (min, avg, max) = (5.633, 5.707, 5.821), stdev = 0.100
  CI (99.9%): [3.878, 7.535] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.162 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.089 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.412 ±(99.9%) 0.009 ms/op
Iteration   1: 5.551 ±(99.9%) 0.010 ms/op
Iteration   2: 5.518 ±(99.9%) 0.013 ms/op
Iteration   3: 5.343 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.471 ±(99.9%) 2.038 ms/op [Average]
  (min, avg, max) = (5.343, 5.471, 5.551), stdev = 0.112
  CI (99.9%): [3.433, 7.509] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.240 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.558 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.656 ±(99.9%) 0.011 ms/op
Iteration   1: 5.761 ±(99.9%) 0.007 ms/op
Iteration   2: 5.416 ±(99.9%) 0.014 ms/op
Iteration   3: 5.420 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.533 ±(99.9%) 3.612 ms/op [Average]
  (min, avg, max) = (5.416, 5.533, 5.761), stdev = 0.198
  CI (99.9%): [1.921, 9.144] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 21.436 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 8.019 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.722 ±(99.9%) 0.017 ms/op
Iteration   1: 6.503 ±(99.9%) 0.016 ms/op
Iteration   2: 6.569 ±(99.9%) 0.014 ms/op
Iteration   3: 6.682 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.585 ±(99.9%) 1.654 ms/op [Average]
  (min, avg, max) = (6.503, 6.585, 6.682), stdev = 0.091
  CI (99.9%): [4.930, 8.239] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 15.912 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 7.528 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.453 ±(99.9%) 0.038 ms/op
Iteration   1: 5.870 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.564 ms/op
                 createUser·p0.50:   5.497 ms/op
                 createUser·p0.90:   7.365 ms/op
                 createUser·p0.95:   8.520 ms/op
                 createUser·p0.99:   11.321 ms/op
                 createUser·p0.999:  27.060 ms/op
                 createUser·p0.9999: 30.820 ms/op
                 createUser·p1.00:   32.047 ms/op

Iteration   2: 5.718 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.343 ms/op
                 createUser·p0.50:   5.390 ms/op
                 createUser·p0.90:   7.029 ms/op
                 createUser·p0.95:   8.004 ms/op
                 createUser·p0.99:   11.059 ms/op
                 createUser·p0.999:  30.207 ms/op
                 createUser·p0.9999: 33.677 ms/op
                 createUser·p1.00:   34.865 ms/op

Iteration   3: 5.713 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.339 ms/op
                 createUser·p0.50:   5.399 ms/op
                 createUser·p0.90:   7.053 ms/op
                 createUser·p0.95:   8.069 ms/op
                 createUser·p0.99:   11.076 ms/op
                 createUser·p0.999:  28.574 ms/op
                 createUser·p0.9999: 37.578 ms/op
                 createUser·p1.00:   38.601 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 166442
  mean =      5.766 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 42127 
    [ 5.000,  7.500) = 111516 
    [ 7.500, 10.000) = 9680 
    [10.000, 12.500) = 2400 
    [12.500, 15.000) = 363 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      2.339 ms/op
     p(50.0000) =      5.423 ms/op
     p(90.0000) =      7.152 ms/op
     p(95.0000) =      8.208 ms/op
     p(99.0000) =     11.158 ms/op
     p(99.9000) =     27.984 ms/op
     p(99.9900) =     36.967 ms/op
     p(99.9990) =     38.078 ms/op
     p(99.9999) =     38.601 ms/op
    p(100.0000) =     38.601 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.001 ±(99.9%) 0.257 ms/op
# Warmup Iteration   2: 6.081 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.585 ±(99.9%) 0.020 ms/op
Iteration   1: 5.380 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.474 ms/op
                 existUser·p0.50:   5.063 ms/op
                 existUser·p0.90:   6.709 ms/op
                 existUser·p0.95:   7.520 ms/op
                 existUser·p0.99:   9.814 ms/op
                 existUser·p0.999:  16.155 ms/op
                 existUser·p0.9999: 32.871 ms/op
                 existUser·p1.00:   33.817 ms/op

Iteration   2: 5.162 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.134 ms/op
                 existUser·p0.50:   4.809 ms/op
                 existUser·p0.90:   6.480 ms/op
                 existUser·p0.95:   7.610 ms/op
                 existUser·p0.99:   10.273 ms/op
                 existUser·p0.999:  26.837 ms/op
                 existUser·p0.9999: 32.192 ms/op
                 existUser·p1.00:   34.537 ms/op

Iteration   3: 5.232 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.294 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.373 ms/op
                 existUser·p0.95:   7.160 ms/op
                 existUser·p0.99:   9.912 ms/op
                 existUser·p0.999:  30.179 ms/op
                 existUser·p0.9999: 33.482 ms/op
                 existUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182540
  mean =      5.256 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 96212 
    [ 5.000,  7.500) = 77579 
    [ 7.500, 10.000) = 6862 
    [10.000, 12.500) = 1248 
    [12.500, 15.000) = 299 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 67 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.134 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.529 ms/op
     p(95.0000) =      7.438 ms/op
     p(99.0000) =     10.027 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     32.924 ms/op
     p(99.9990) =     34.429 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.370 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 6.613 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.670 ±(99.9%) 0.022 ms/op
Iteration   1: 5.475 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.050 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   6.824 ms/op
                 getUser·p0.95:   8.290 ms/op
                 getUser·p0.99:   11.220 ms/op
                 getUser·p0.999:  24.362 ms/op
                 getUser·p0.9999: 29.222 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   2: 5.440 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.687 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   6.685 ms/op
                 getUser·p0.95:   7.610 ms/op
                 getUser·p0.99:   10.385 ms/op
                 getUser·p0.999:  19.005 ms/op
                 getUser·p0.9999: 34.480 ms/op
                 getUser·p1.00:   34.800 ms/op

Iteration   3: 5.309 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.154 ms/op
                 getUser·p0.50:   5.054 ms/op
                 getUser·p0.90:   6.545 ms/op
                 getUser·p0.95:   7.307 ms/op
                 getUser·p0.99:   9.863 ms/op
                 getUser·p0.999:  27.361 ms/op
                 getUser·p0.9999: 31.096 ms/op
                 getUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177450
  mean =      5.407 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 77648 
    [ 5.000,  7.500) = 89725 
    [ 7.500, 10.000) = 7739 
    [10.000, 12.500) = 1569 
    [12.500, 15.000) = 399 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.050 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      6.668 ms/op
     p(95.0000) =      7.700 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     19.530 ms/op
     p(99.9900) =     32.744 ms/op
     p(99.9990) =     34.698 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 17.631 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 8.151 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 7.034 ±(99.9%) 0.036 ms/op
Iteration   1: 6.589 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   6.095 ms/op
                 listUser·p0.90:   8.159 ms/op
                 listUser·p0.95:   9.683 ms/op
                 listUser·p0.99:   14.811 ms/op
                 listUser·p0.999:  29.164 ms/op
                 listUser·p0.9999: 37.159 ms/op
                 listUser·p1.00:   38.470 ms/op

Iteration   2: 6.667 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.868 ms/op
                 listUser·p0.50:   6.291 ms/op
                 listUser·p0.90:   8.176 ms/op
                 listUser·p0.95:   9.388 ms/op
                 listUser·p0.99:   12.442 ms/op
                 listUser·p0.999:  29.461 ms/op
                 listUser·p0.9999: 33.280 ms/op
                 listUser·p1.00:   33.948 ms/op

Iteration   3: 6.597 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.931 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   8.438 ms/op
                 listUser·p0.95:   9.781 ms/op
                 listUser·p0.99:   13.304 ms/op
                 listUser·p0.999:  25.183 ms/op
                 listUser·p0.9999: 33.826 ms/op
                 listUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144978
  mean =      6.617 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 6013 
    [ 5.000,  7.500) = 115490 
    [ 7.500, 10.000) = 17511 
    [10.000, 12.500) = 3745 
    [12.500, 15.000) = 1308 
    [15.000, 17.500) = 470 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      6.193 ms/op
     p(90.0000) =      8.249 ms/op
     p(95.0000) =      9.617 ms/op
     p(99.0000) =     13.533 ms/op
     p(99.9000) =     28.739 ms/op
     p(99.9900) =     35.488 ms/op
     p(99.9990) =     38.263 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.665 ± 2.641  ops/ms
ClientPb.existUser                       thrpt       3   6.059 ± 4.907  ops/ms
ClientPb.getUser                         thrpt       3   5.557 ± 4.658  ops/ms
ClientPb.listUser                        thrpt       3   4.986 ± 1.961  ops/ms
ClientPb.createUser                       avgt       3   5.707 ± 1.828   ms/op
ClientPb.existUser                        avgt       3   5.471 ± 2.038   ms/op
ClientPb.getUser                          avgt       3   5.533 ± 3.612   ms/op
ClientPb.listUser                         avgt       3   6.585 ± 1.654   ms/op
ClientPb.createUser                     sample  166442   5.766 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.339           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.152           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.208           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.158           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.984           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.967           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.601           ms/op
ClientPb.existUser                      sample  182540   5.256 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.134           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.948           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.529           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.438           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.027           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.448           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.924           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.537           ms/op
ClientPb.getUser                        sample  177450   5.407 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.050           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.112           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.668           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.700           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.519           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.530           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.744           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.800           ms/op
ClientPb.listUser                       sample  144978   6.617 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.930           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.193           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.249           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.617           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.533           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.739           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.488           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.470           ms/op
