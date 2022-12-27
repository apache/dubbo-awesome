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
# Warmup Iteration   1: 2.777 ops/ms
# Warmup Iteration   2: 7.013 ops/ms
# Warmup Iteration   3: 9.194 ops/ms
Iteration   1: 10.316 ops/ms
Iteration   2: 10.159 ops/ms
Iteration   3: 9.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.090 ±(99.9%) 4.856 ops/ms [Average]
  (min, avg, max) = (9.797, 10.090, 10.316), stdev = 0.266
  CI (99.9%): [5.234, 14.946] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.649 ops/ms
# Warmup Iteration   2: 9.395 ops/ms
# Warmup Iteration   3: 10.636 ops/ms
Iteration   1: 10.727 ops/ms
Iteration   2: 10.461 ops/ms
Iteration   3: 10.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.532 ±(99.9%) 3.101 ops/ms [Average]
  (min, avg, max) = (10.410, 10.532, 10.727), stdev = 0.170
  CI (99.9%): [7.432, 13.633] (assumes normal distribution)


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
# Warmup Iteration   1: 3.801 ops/ms
# Warmup Iteration   2: 9.507 ops/ms
# Warmup Iteration   3: 9.959 ops/ms
Iteration   1: 9.516 ops/ms
Iteration   2: 9.701 ops/ms
Iteration   3: 9.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.734 ±(99.9%) 4.318 ops/ms [Average]
  (min, avg, max) = (9.516, 9.734, 9.986), stdev = 0.237
  CI (99.9%): [5.416, 14.052] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.618 ops/ms
# Warmup Iteration   2: 7.972 ops/ms
# Warmup Iteration   3: 8.534 ops/ms
Iteration   1: 8.441 ops/ms
Iteration   2: 8.756 ops/ms
Iteration   3: 8.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.646 ±(99.9%) 3.252 ops/ms [Average]
  (min, avg, max) = (8.441, 8.646, 8.756), stdev = 0.178
  CI (99.9%): [5.395, 11.898] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.378 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.414 ±(99.9%) 0.004 ms/op
Iteration   1: 3.226 ±(99.9%) 0.004 ms/op
Iteration   2: 3.203 ±(99.9%) 0.004 ms/op
Iteration   3: 3.083 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.171 ±(99.9%) 1.403 ms/op [Average]
  (min, avg, max) = (3.083, 3.171, 3.226), stdev = 0.077
  CI (99.9%): [1.768, 4.573] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.360 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.002 ms/op
Iteration   1: 3.103 ±(99.9%) 0.005 ms/op
Iteration   2: 3.178 ±(99.9%) 0.003 ms/op
Iteration   3: 2.940 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.074 ±(99.9%) 2.213 ms/op [Average]
  (min, avg, max) = (2.940, 3.074, 3.178), stdev = 0.121
  CI (99.9%): [0.861, 5.287] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 6.916 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.003 ms/op
Iteration   1: 3.203 ±(99.9%) 0.005 ms/op
Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
Iteration   3: 3.109 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.142 ±(99.9%) 0.967 ms/op [Average]
  (min, avg, max) = (3.109, 3.142, 3.203), stdev = 0.053
  CI (99.9%): [2.174, 4.109] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.140 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.004 ms/op
Iteration   1: 3.667 ±(99.9%) 0.009 ms/op
Iteration   2: 3.695 ±(99.9%) 0.006 ms/op
Iteration   3: 3.682 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.681 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (3.667, 3.681, 3.695), stdev = 0.014
  CI (99.9%): [3.424, 3.939] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.829 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.209 ±(99.9%) 0.009 ms/op
Iteration   1: 3.208 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  17.826 ms/op
                 createUser·p0.9999: 24.217 ms/op
                 createUser·p1.00:   25.002 ms/op

Iteration   2: 3.168 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  14.794 ms/op
                 createUser·p0.9999: 21.365 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   3: 3.123 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   5.128 ms/op
                 createUser·p0.999:  17.523 ms/op
                 createUser·p0.9999: 28.086 ms/op
                 createUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303008
  mean =      3.166 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17753 
    [ 2.500,  5.000) = 279441 
    [ 5.000,  7.500) = 4973 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.981 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     26.316 ms/op
     p(99.9990) =     28.344 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.272 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.475 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.008 ms/op
Iteration   1: 3.167 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  8.700 ms/op
                 existUser·p0.9999: 20.218 ms/op
                 existUser·p1.00:   20.414 ms/op

Iteration   2: 3.083 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.321 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  10.781 ms/op
                 existUser·p0.9999: 22.893 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   3: 3.082 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  14.267 ms/op
                 existUser·p0.9999: 24.836 ms/op
                 existUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308430
  mean =      3.110 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25568 
    [ 2.500,  5.000) = 278406 
    [ 5.000,  7.500) = 3826 
    [ 7.500, 10.000) = 225 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.161 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     23.401 ms/op
     p(99.9990) =     25.261 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 8.151 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.494 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.009 ms/op
Iteration   1: 3.289 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.536 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  17.651 ms/op
                 getUser·p0.9999: 23.134 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 3.132 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.616 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  10.270 ms/op
                 getUser·p0.9999: 25.093 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   3: 3.215 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.496 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  12.506 ms/op
                 getUser·p0.9999: 23.757 ms/op
                 getUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298893
  mean =      3.210 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14232 
    [ 2.500,  5.000) = 277175 
    [ 5.000,  7.500) = 6626 
    [ 7.500, 10.000) = 378 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     16.271 ms/op
     p(99.9900) =     23.928 ms/op
     p(99.9990) =     25.889 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 9.860 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.787 ±(99.9%) 0.011 ms/op
Iteration   1: 3.704 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  15.133 ms/op
                 listUser·p0.9999: 18.309 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   2: 3.732 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  12.506 ms/op
                 listUser·p0.9999: 14.287 ms/op
                 listUser·p1.00:   14.926 ms/op

Iteration   3: 3.693 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.276 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 14.877 ms/op
                 listUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258611
  mean =      3.709 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 46 
    [ 2.500,  3.750) = 204526 
    [ 3.750,  5.000) = 46307 
    [ 5.000,  6.250) = 3643 
    [ 6.250,  7.500) = 2399 
    [ 7.500,  8.750) = 853 
    [ 8.750, 10.000) = 274 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 193 
    [13.750, 15.000) = 100 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      2.126 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     17.859 ms/op
     p(99.9990) =     18.593 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.090 ± 4.856  ops/ms
ClientPb.existUser                       thrpt       3  10.532 ± 3.101  ops/ms
ClientPb.getUser                         thrpt       3   9.734 ± 4.318  ops/ms
ClientPb.listUser                        thrpt       3   8.646 ± 3.252  ops/ms
ClientPb.createUser                       avgt       3   3.171 ± 1.403   ms/op
ClientPb.existUser                        avgt       3   3.074 ± 2.213   ms/op
ClientPb.getUser                          avgt       3   3.142 ± 0.967   ms/op
ClientPb.listUser                         avgt       3   3.681 ± 0.258   ms/op
ClientPb.createUser                     sample  303008   3.166 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.981           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.527           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.531           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.316           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.901           ms/op
ClientPb.existUser                      sample  308430   3.110 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.188           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.161           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.582           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.401           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.494           ms/op
ClientPb.getUser                        sample  298893   3.210 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.496           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.617           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.857           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.271           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.928           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.444           ms/op
ClientPb.listUser                       sample  258611   3.709 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.126           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.799           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.517           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.859           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.711           ms/op
