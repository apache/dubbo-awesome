# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.474 ops/ms
# Warmup Iteration   2: 5.963 ops/ms
# Warmup Iteration   3: 9.230 ops/ms
Iteration   1: 9.517 ops/ms
Iteration   2: 9.986 ops/ms
Iteration   3: 9.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.725 ±(99.9%) 4.352 ops/ms [Average]
  (min, avg, max) = (9.517, 9.725, 9.986), stdev = 0.239
  CI (99.9%): [5.374, 14.077] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.088 ops/ms
# Warmup Iteration   2: 9.240 ops/ms
# Warmup Iteration   3: 10.010 ops/ms
Iteration   1: 10.358 ops/ms
Iteration   2: 10.506 ops/ms
Iteration   3: 10.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.515 ±(99.9%) 2.955 ops/ms [Average]
  (min, avg, max) = (10.358, 10.515, 10.681), stdev = 0.162
  CI (99.9%): [7.560, 13.470] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.394 ops/ms
# Warmup Iteration   2: 9.119 ops/ms
# Warmup Iteration   3: 9.325 ops/ms
Iteration   1: 10.365 ops/ms
Iteration   2: 10.221 ops/ms
Iteration   3: 10.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.244 ±(99.9%) 2.049 ops/ms [Average]
  (min, avg, max) = (10.144, 10.244, 10.365), stdev = 0.112
  CI (99.9%): [8.195, 12.293] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.998 ops/ms
# Warmup Iteration   2: 6.935 ops/ms
# Warmup Iteration   3: 8.383 ops/ms
Iteration   1: 8.479 ops/ms
Iteration   2: 8.582 ops/ms
Iteration   3: 8.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.532 ±(99.9%) 0.939 ops/ms [Average]
  (min, avg, max) = (8.479, 8.532, 8.582), stdev = 0.051
  CI (99.9%): [7.594, 9.471] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.272 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.533 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.006 ms/op
Iteration   1: 3.178 ±(99.9%) 0.008 ms/op
Iteration   2: 3.193 ±(99.9%) 0.005 ms/op
Iteration   3: 3.086 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.153 ±(99.9%) 1.057 ms/op [Average]
  (min, avg, max) = (3.086, 3.153, 3.193), stdev = 0.058
  CI (99.9%): [2.095, 4.210] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.110 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.422 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.006 ms/op
Iteration   1: 3.078 ±(99.9%) 0.005 ms/op
Iteration   2: 3.197 ±(99.9%) 0.006 ms/op
Iteration   3: 3.074 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.117 ±(99.9%) 1.274 ms/op [Average]
  (min, avg, max) = (3.074, 3.117, 3.197), stdev = 0.070
  CI (99.9%): [1.842, 4.391] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.354 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.318 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.002 ms/op
Iteration   1: 3.212 ±(99.9%) 0.003 ms/op
Iteration   2: 3.200 ±(99.9%) 0.006 ms/op
Iteration   3: 3.121 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.178 ±(99.9%) 0.903 ms/op [Average]
  (min, avg, max) = (3.121, 3.178, 3.212), stdev = 0.049
  CI (99.9%): [2.275, 4.081] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.673 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.003 ms/op
Iteration   1: 3.753 ±(99.9%) 0.007 ms/op
Iteration   2: 3.716 ±(99.9%) 0.007 ms/op
Iteration   3: 3.766 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.745 ±(99.9%) 0.471 ms/op [Average]
  (min, avg, max) = (3.716, 3.745, 3.766), stdev = 0.026
  CI (99.9%): [3.274, 4.216] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.142 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.009 ms/op
Iteration   1: 3.294 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   5.858 ms/op
                 createUser·p0.999:  12.145 ms/op
                 createUser·p0.9999: 22.966 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   2: 3.111 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.281 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  9.896 ms/op
                 createUser·p0.9999: 24.239 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   3: 3.166 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  13.943 ms/op
                 createUser·p0.9999: 35.586 ms/op
                 createUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301010
  mean =      3.188 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23708 
    [ 2.500,  5.000) = 270962 
    [ 5.000,  7.500) = 5438 
    [ 7.500, 10.000) = 515 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     28.665 ms/op
     p(99.9990) =     35.783 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.142 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.384 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.008 ms/op
Iteration   1: 3.207 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  9.914 ms/op
                 existUser·p0.9999: 20.620 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   2: 3.066 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.339 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  8.810 ms/op
                 existUser·p0.9999: 23.022 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   3: 3.229 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.704 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  15.303 ms/op
                 existUser·p0.9999: 20.516 ms/op
                 existUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303185
  mean =      3.166 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24570 
    [ 2.500,  5.000) = 273055 
    [ 5.000,  7.500) = 5006 
    [ 7.500, 10.000) = 234 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     23.396 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.085 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.467 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.009 ms/op
Iteration   1: 3.160 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  18.505 ms/op
                 getUser·p0.9999: 20.111 ms/op
                 getUser·p1.00:   21.496 ms/op

Iteration   2: 3.162 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.651 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  11.076 ms/op
                 getUser·p0.9999: 23.851 ms/op
                 getUser·p1.00:   25.526 ms/op

Iteration   3: 3.133 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.489 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  10.502 ms/op
                 getUser·p0.9999: 20.788 ms/op
                 getUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304487
  mean =      3.151 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14901 
    [ 2.500,  5.000) = 282910 
    [ 5.000,  7.500) = 5694 
    [ 7.500, 10.000) = 509 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 180 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     22.435 ms/op
     p(99.9990) =     25.284 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.351 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.696 ±(99.9%) 0.010 ms/op
Iteration   1: 3.779 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  16.236 ms/op
                 listUser·p0.9999: 22.485 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   2: 3.694 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  14.090 ms/op
                 listUser·p0.9999: 18.317 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   3: 3.693 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.599 ms/op
                 listUser·p0.9999: 15.832 ms/op
                 listUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258106
  mean =      3.721 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 250362 
    [ 5.000,  7.500) = 5578 
    [ 7.500, 10.000) = 1528 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     14.418 ms/op
     p(99.9900) =     21.305 ms/op
     p(99.9990) =     23.263 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.725 ± 4.352  ops/ms
ClientPb.existUser                       thrpt       3  10.515 ± 2.955  ops/ms
ClientPb.getUser                         thrpt       3  10.244 ± 2.049  ops/ms
ClientPb.listUser                        thrpt       3   8.532 ± 0.939  ops/ms
ClientPb.createUser                       avgt       3   3.153 ± 1.057   ms/op
ClientPb.existUser                        avgt       3   3.117 ± 1.274   ms/op
ClientPb.getUser                          avgt       3   3.178 ± 0.903   ms/op
ClientPb.listUser                         avgt       3   3.745 ± 0.471   ms/op
ClientPb.createUser                     sample  301010   3.188 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.621           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.498           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.926           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.665           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.307           ms/op
ClientPb.existUser                      sample  303185   3.166 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.000           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.374           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.155           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.544           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.019           ms/op
ClientPb.getUser                        sample  304487   3.151 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.343           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.486           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.751           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.039           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.435           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.526           ms/op
ClientPb.listUser                       sample  258106   3.721 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.859           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.584           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.418           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.305           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.560           ms/op
