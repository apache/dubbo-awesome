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
# Warmup Iteration   1: 2.140 ops/ms
# Warmup Iteration   2: 5.713 ops/ms
# Warmup Iteration   3: 8.412 ops/ms
Iteration   1: 9.049 ops/ms
Iteration   2: 9.246 ops/ms
Iteration   3: 9.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.238 ±(99.9%) 3.375 ops/ms [Average]
  (min, avg, max) = (9.049, 9.238, 9.419), stdev = 0.185
  CI (99.9%): [5.863, 12.613] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.918 ops/ms
# Warmup Iteration   2: 9.111 ops/ms
# Warmup Iteration   3: 9.396 ops/ms
Iteration   1: 9.911 ops/ms
Iteration   2: 9.817 ops/ms
Iteration   3: 9.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.866 ±(99.9%) 0.858 ops/ms [Average]
  (min, avg, max) = (9.817, 9.866, 9.911), stdev = 0.047
  CI (99.9%): [9.008, 10.724] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.110 ops/ms
# Warmup Iteration   2: 7.950 ops/ms
# Warmup Iteration   3: 9.183 ops/ms
Iteration   1: 8.977 ops/ms
Iteration   2: 9.645 ops/ms
Iteration   3: 9.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.315 ±(99.9%) 6.099 ops/ms [Average]
  (min, avg, max) = (8.977, 9.315, 9.645), stdev = 0.334
  CI (99.9%): [3.215, 15.414] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.672 ops/ms
# Warmup Iteration   2: 7.138 ops/ms
# Warmup Iteration   3: 7.700 ops/ms
Iteration   1: 7.636 ops/ms
Iteration   2: 7.873 ops/ms
Iteration   3: 8.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.836 ±(99.9%) 3.382 ops/ms [Average]
  (min, avg, max) = (7.636, 7.836, 8.001), stdev = 0.185
  CI (99.9%): [4.454, 11.218] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.491 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.599 ±(99.9%) 0.008 ms/op
Iteration   1: 3.511 ±(99.9%) 0.007 ms/op
Iteration   2: 3.412 ±(99.9%) 0.011 ms/op
Iteration   3: 3.477 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.467 ±(99.9%) 0.919 ms/op [Average]
  (min, avg, max) = (3.412, 3.467, 3.511), stdev = 0.050
  CI (99.9%): [2.547, 4.386] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.689 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.739 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.004 ms/op
Iteration   1: 3.383 ±(99.9%) 0.009 ms/op
Iteration   2: 3.355 ±(99.9%) 0.003 ms/op
Iteration   3: 3.255 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.331 ±(99.9%) 1.226 ms/op [Average]
  (min, avg, max) = (3.255, 3.331, 3.383), stdev = 0.067
  CI (99.9%): [2.106, 4.557] (assumes normal distribution)


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
# Warmup Iteration   1: 10.086 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.006 ms/op
Iteration   1: 3.478 ±(99.9%) 0.006 ms/op
Iteration   2: 3.479 ±(99.9%) 0.006 ms/op
Iteration   3: 3.416 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.458 ±(99.9%) 0.665 ms/op [Average]
  (min, avg, max) = (3.416, 3.458, 3.479), stdev = 0.036
  CI (99.9%): [2.793, 4.123] (assumes normal distribution)


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
# Warmup Iteration   1: 9.829 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.376 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.012 ms/op
Iteration   1: 4.167 ±(99.9%) 0.005 ms/op
Iteration   2: 4.021 ±(99.9%) 0.011 ms/op
Iteration   3: 4.068 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.085 ±(99.9%) 1.355 ms/op [Average]
  (min, avg, max) = (4.021, 4.085, 4.167), stdev = 0.074
  CI (99.9%): [2.730, 5.441] (assumes normal distribution)


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
# Warmup Iteration   1: 10.420 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.014 ms/op
Iteration   1: 3.464 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.817 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  21.553 ms/op
                 createUser·p0.9999: 25.056 ms/op
                 createUser·p1.00:   26.051 ms/op

Iteration   2: 3.504 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.035 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.073 ms/op
                 createUser·p0.999:  21.633 ms/op
                 createUser·p0.9999: 32.534 ms/op
                 createUser·p1.00:   33.620 ms/op

Iteration   3: 3.545 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.329 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  22.086 ms/op
                 createUser·p0.9999: 31.883 ms/op
                 createUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273720
  mean =      3.504 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5466 
    [ 2.500,  5.000) = 261268 
    [ 5.000,  7.500) = 5602 
    [ 7.500, 10.000) = 749 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     21.955 ms/op
     p(99.9900) =     31.904 ms/op
     p(99.9990) =     33.620 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 8.187 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.009 ms/op
Iteration   1: 3.338 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.894 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  21.137 ms/op
                 existUser·p0.9999: 23.862 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   2: 3.391 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  20.266 ms/op
                 existUser·p0.9999: 28.246 ms/op
                 existUser·p1.00:   29.098 ms/op

Iteration   3: 3.505 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  18.486 ms/op
                 existUser·p0.9999: 26.935 ms/op
                 existUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281663
  mean =      3.410 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16185 
    [ 2.500,  5.000) = 257755 
    [ 5.000,  7.500) = 6538 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     18.634 ms/op
     p(99.9900) =     27.290 ms/op
     p(99.9990) =     28.815 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 9.076 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.011 ms/op
Iteration   1: 3.457 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.442 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  16.959 ms/op
                 getUser·p0.9999: 23.724 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   2: 3.679 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.539 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  22.759 ms/op
                 getUser·p0.9999: 26.575 ms/op
                 getUser·p1.00:   27.230 ms/op

Iteration   3: 3.513 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  20.571 ms/op
                 getUser·p0.9999: 30.270 ms/op
                 getUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270536
  mean =      3.547 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4405 
    [ 2.500,  5.000) = 257768 
    [ 5.000,  7.500) = 6989 
    [ 7.500, 10.000) = 821 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     19.137 ms/op
     p(99.9900) =     28.244 ms/op
     p(99.9990) =     31.352 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 11.086 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.514 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.014 ms/op
Iteration   1: 4.114 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.935 ms/op
                 listUser·p0.999:  23.451 ms/op
                 listUser·p0.9999: 25.238 ms/op
                 listUser·p1.00:   25.461 ms/op

Iteration   2: 4.000 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.638 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.169 ms/op
                 listUser·p0.999:  15.483 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   3: 3.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.687 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 16.530 ms/op
                 listUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238059
  mean =      4.033 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 229701 
    [ 5.000,  7.500) = 6168 
    [ 7.500, 10.000) = 1308 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     24.674 ms/op
     p(99.9990) =     25.415 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.238 ± 3.375  ops/ms
ClientPb.existUser                       thrpt       3   9.866 ± 0.858  ops/ms
ClientPb.getUser                         thrpt       3   9.315 ± 6.099  ops/ms
ClientPb.listUser                        thrpt       3   7.836 ± 3.382  ops/ms
ClientPb.createUser                       avgt       3   3.467 ± 0.919   ms/op
ClientPb.existUser                        avgt       3   3.331 ± 1.226   ms/op
ClientPb.getUser                          avgt       3   3.458 ± 0.665   ms/op
ClientPb.listUser                         avgt       3   4.085 ± 1.355   ms/op
ClientPb.createUser                     sample  273720   3.504 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.329           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.210           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.955           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.904           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.817           ms/op
ClientPb.existUser                      sample  281663   3.410 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.137           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.046           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.634           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.290           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.098           ms/op
ClientPb.getUser                        sample  270536   3.547 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.053           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.375           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.537           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.137           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.244           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.014           ms/op
ClientPb.listUser                       sample  238059   4.033 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.575           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.217           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.860           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.674           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.461           ms/op
