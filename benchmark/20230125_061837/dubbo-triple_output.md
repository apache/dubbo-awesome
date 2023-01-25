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
# Warmup Iteration   1: 2.624 ops/ms
# Warmup Iteration   2: 6.223 ops/ms
# Warmup Iteration   3: 9.149 ops/ms
Iteration   1: 9.528 ops/ms
Iteration   2: 10.130 ops/ms
Iteration   3: 10.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.022 ±(99.9%) 8.207 ops/ms [Average]
  (min, avg, max) = (9.528, 10.022, 10.408), stdev = 0.450
  CI (99.9%): [1.816, 18.229] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.589 ops/ms
# Warmup Iteration   2: 9.190 ops/ms
# Warmup Iteration   3: 9.937 ops/ms
Iteration   1: 10.301 ops/ms
Iteration   2: 10.066 ops/ms
Iteration   3: 10.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.353 ±(99.9%) 5.754 ops/ms [Average]
  (min, avg, max) = (10.066, 10.353, 10.691), stdev = 0.315
  CI (99.9%): [4.598, 16.107] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.694 ops/ms
# Warmup Iteration   2: 9.172 ops/ms
# Warmup Iteration   3: 10.019 ops/ms
Iteration   1: 10.275 ops/ms
Iteration   2: 10.053 ops/ms
Iteration   3: 10.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.222 ±(99.9%) 2.733 ops/ms [Average]
  (min, avg, max) = (10.053, 10.222, 10.338), stdev = 0.150
  CI (99.9%): [7.489, 12.955] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.598 ops/ms
# Warmup Iteration   2: 7.962 ops/ms
# Warmup Iteration   3: 8.427 ops/ms
Iteration   1: 8.446 ops/ms
Iteration   2: 8.793 ops/ms
Iteration   3: 8.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.592 ±(99.9%) 3.290 ops/ms [Average]
  (min, avg, max) = (8.446, 8.592, 8.793), stdev = 0.180
  CI (99.9%): [5.301, 11.882] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.732 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.496 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.002 ms/op
Iteration   1: 3.170 ±(99.9%) 0.005 ms/op
Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
Iteration   3: 3.102 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.113 ±(99.9%) 0.946 ms/op [Average]
  (min, avg, max) = (3.068, 3.113, 3.170), stdev = 0.052
  CI (99.9%): [2.168, 4.059] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.228 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.345 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.006 ms/op
Iteration   1: 3.160 ±(99.9%) 0.002 ms/op
Iteration   2: 2.996 ±(99.9%) 0.003 ms/op
Iteration   3: 3.091 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.082 ±(99.9%) 1.496 ms/op [Average]
  (min, avg, max) = (2.996, 3.082, 3.160), stdev = 0.082
  CI (99.9%): [1.586, 4.578] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.212 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.257 ±(99.9%) 0.002 ms/op
Iteration   1: 3.197 ±(99.9%) 0.003 ms/op
Iteration   2: 3.264 ±(99.9%) 0.004 ms/op
Iteration   3: 3.180 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.214 ±(99.9%) 0.805 ms/op [Average]
  (min, avg, max) = (3.180, 3.214, 3.264), stdev = 0.044
  CI (99.9%): [2.408, 4.019] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.953 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.753 ±(99.9%) 0.004 ms/op
Iteration   1: 3.725 ±(99.9%) 0.009 ms/op
Iteration   2: 3.758 ±(99.9%) 0.008 ms/op
Iteration   3: 3.774 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.752 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (3.725, 3.752, 3.774), stdev = 0.025
  CI (99.9%): [3.293, 4.212] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.271 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.009 ms/op
Iteration   1: 3.234 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  12.550 ms/op
                 createUser·p0.9999: 21.336 ms/op
                 createUser·p1.00:   21.791 ms/op

Iteration   2: 3.123 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.198 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.281 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  9.929 ms/op
                 createUser·p0.9999: 21.955 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   3: 3.220 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  13.552 ms/op
                 createUser·p0.9999: 18.975 ms/op
                 createUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300555
  mean =      3.192 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26686 
    [ 2.500,  5.000) = 267658 
    [ 5.000,  7.500) = 5268 
    [ 7.500, 10.000) = 511 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     12.541 ms/op
     p(99.9900) =     21.396 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 7.464 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
Iteration   1: 3.094 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  9.404 ms/op
                 existUser·p0.9999: 25.722 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   2: 3.096 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  12.998 ms/op
                 existUser·p0.9999: 26.914 ms/op
                 existUser·p1.00:   27.263 ms/op

Iteration   3: 3.070 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.196 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.330 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  9.667 ms/op
                 existUser·p0.9999: 20.051 ms/op
                 existUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310872
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24135 
    [ 2.500,  5.000) = 282000 
    [ 5.000,  7.500) = 3949 
    [ 7.500, 10.000) = 368 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     12.435 ms/op
     p(99.9900) =     25.649 ms/op
     p(99.9990) =     27.128 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 7.778 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.009 ms/op
Iteration   1: 3.273 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  13.020 ms/op
                 getUser·p0.9999: 18.980 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   5.358 ms/op
                 getUser·p0.999:  10.976 ms/op
                 getUser·p0.9999: 21.859 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   3: 3.226 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.855 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  10.011 ms/op
                 getUser·p0.9999: 30.021 ms/op
                 getUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299896
  mean =      3.198 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22228 
    [ 2.500,  5.000) = 270580 
    [ 5.000,  7.500) = 6238 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     12.896 ms/op
     p(99.9900) =     28.153 ms/op
     p(99.9990) =     30.605 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 9.827 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.013 ms/op
Iteration   1: 3.768 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.993 ms/op
                 listUser·p0.9999: 20.055 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   2: 3.903 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.311 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  13.423 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   3: 3.743 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  14.033 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252237
  mean =      3.804 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 99 
    [ 2.500,  5.000) = 241588 
    [ 5.000,  7.500) = 8816 
    [ 7.500, 10.000) = 1072 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 288 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.311 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     20.627 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.022 ± 8.207  ops/ms
ClientPb.existUser                       thrpt       3  10.353 ± 5.754  ops/ms
ClientPb.getUser                         thrpt       3  10.222 ± 2.733  ops/ms
ClientPb.listUser                        thrpt       3   8.592 ± 3.290  ops/ms
ClientPb.createUser                       avgt       3   3.113 ± 0.946   ms/op
ClientPb.existUser                        avgt       3   3.082 ± 1.496   ms/op
ClientPb.getUser                          avgt       3   3.214 ± 0.805   ms/op
ClientPb.listUser                         avgt       3   3.752 ± 0.459   ms/op
ClientPb.createUser                     sample  300555   3.192 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.847           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.559           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.644           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.541           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.396           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.233           ms/op
ClientPb.existUser                      sample  310872   3.087 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.910           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.292           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.435           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.649           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.263           ms/op
ClientPb.getUser                        sample  299896   3.198 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.977           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.625           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.677           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.896           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.153           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.671           ms/op
ClientPb.listUser                       sample  252237   3.804 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.311           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.695           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.170           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.631           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.956           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.644           ms/op
