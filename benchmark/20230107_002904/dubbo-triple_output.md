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
# Warmup Iteration   1: 2.070 ops/ms
# Warmup Iteration   2: 5.385 ops/ms
# Warmup Iteration   3: 8.307 ops/ms
Iteration   1: 9.394 ops/ms
Iteration   2: 9.440 ops/ms
Iteration   3: 9.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.447 ±(99.9%) 1.038 ops/ms [Average]
  (min, avg, max) = (9.394, 9.447, 9.507), stdev = 0.057
  CI (99.9%): [8.409, 10.485] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.510 ops/ms
# Warmup Iteration   2: 8.850 ops/ms
# Warmup Iteration   3: 9.906 ops/ms
Iteration   1: 9.927 ops/ms
Iteration   2: 9.919 ops/ms
Iteration   3: 10.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.957 ±(99.9%) 1.065 ops/ms [Average]
  (min, avg, max) = (9.919, 9.957, 10.024), stdev = 0.058
  CI (99.9%): [8.891, 11.022] (assumes normal distribution)


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
# Warmup Iteration   1: 3.318 ops/ms
# Warmup Iteration   2: 8.870 ops/ms
# Warmup Iteration   3: 9.128 ops/ms
Iteration   1: 9.747 ops/ms
Iteration   2: 9.475 ops/ms
Iteration   3: 9.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.549 ±(99.9%) 3.150 ops/ms [Average]
  (min, avg, max) = (9.426, 9.549, 9.747), stdev = 0.173
  CI (99.9%): [6.400, 12.699] (assumes normal distribution)


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
# Warmup Iteration   1: 2.930 ops/ms
# Warmup Iteration   2: 7.473 ops/ms
# Warmup Iteration   3: 8.186 ops/ms
Iteration   1: 8.037 ops/ms
Iteration   2: 8.474 ops/ms
Iteration   3: 8.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.258 ±(99.9%) 3.988 ops/ms [Average]
  (min, avg, max) = (8.037, 8.258, 8.474), stdev = 0.219
  CI (99.9%): [4.270, 12.247] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.629 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.644 ±(99.9%) 0.005 ms/op
Iteration   1: 3.442 ±(99.9%) 0.010 ms/op
Iteration   2: 3.221 ±(99.9%) 0.012 ms/op
Iteration   3: 3.336 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.333 ±(99.9%) 2.016 ms/op [Average]
  (min, avg, max) = (3.221, 3.333, 3.442), stdev = 0.111
  CI (99.9%): [1.316, 5.349] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.797 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.495 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.011 ms/op
Iteration   1: 3.187 ±(99.9%) 0.005 ms/op
Iteration   2: 3.350 ±(99.9%) 0.005 ms/op
Iteration   3: 3.277 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.271 ±(99.9%) 1.486 ms/op [Average]
  (min, avg, max) = (3.187, 3.271, 3.350), stdev = 0.081
  CI (99.9%): [1.785, 4.758] (assumes normal distribution)


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
# Warmup Iteration   1: 9.336 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.011 ms/op
Iteration   1: 3.422 ±(99.9%) 0.006 ms/op
Iteration   2: 3.397 ±(99.9%) 0.003 ms/op
Iteration   3: 3.260 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.360 ±(99.9%) 1.581 ms/op [Average]
  (min, avg, max) = (3.260, 3.360, 3.422), stdev = 0.087
  CI (99.9%): [1.778, 4.941] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.048 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.288 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.008 ms/op
Iteration   1: 3.841 ±(99.9%) 0.012 ms/op
Iteration   2: 3.823 ±(99.9%) 0.012 ms/op
Iteration   3: 3.941 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.868 ±(99.9%) 1.167 ms/op [Average]
  (min, avg, max) = (3.823, 3.868, 3.941), stdev = 0.064
  CI (99.9%): [2.701, 5.035] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.838 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.011 ms/op
Iteration   1: 3.332 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  20.492 ms/op
                 createUser·p0.9999: 22.931 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   2: 3.357 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  20.280 ms/op
                 createUser·p0.9999: 24.674 ms/op
                 createUser·p1.00:   25.330 ms/op

Iteration   3: 3.366 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  21.564 ms/op
                 createUser·p0.9999: 25.870 ms/op
                 createUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 286289
  mean =      3.351 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10221 
    [ 2.500,  5.000) = 269812 
    [ 5.000,  7.500) = 5344 
    [ 7.500, 10.000) = 481 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     20.339 ms/op
     p(99.9900) =     24.981 ms/op
     p(99.9990) =     26.874 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 7.500 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.466 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.008 ms/op
Iteration   1: 3.254 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.182 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  9.798 ms/op
                 existUser·p0.9999: 21.305 ms/op
                 existUser·p1.00:   23.331 ms/op

Iteration   2: 3.253 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.139 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  10.559 ms/op
                 existUser·p0.9999: 22.910 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   3: 3.255 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  14.418 ms/op
                 existUser·p0.9999: 24.102 ms/op
                 existUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294764
  mean =      3.254 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13496 
    [ 2.500,  5.000) = 276122 
    [ 5.000,  7.500) = 4307 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 154 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     12.517 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     25.702 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 10.165 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.012 ms/op
Iteration   1: 3.404 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.741 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  12.911 ms/op
                 getUser·p0.9999: 25.343 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   2: 3.282 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  9.707 ms/op
                 getUser·p0.9999: 27.549 ms/op
                 getUser·p1.00:   28.377 ms/op

Iteration   3: 3.504 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  17.519 ms/op
                 getUser·p0.9999: 26.734 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282894
  mean =      3.394 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13276 
    [ 2.500,  5.000) = 261974 
    [ 5.000,  7.500) = 6422 
    [ 7.500, 10.000) = 770 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     12.911 ms/op
     p(99.9900) =     26.968 ms/op
     p(99.9990) =     28.028 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 10.555 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.192 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.012 ms/op
Iteration   1: 3.975 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  18.563 ms/op
                 listUser·p0.9999: 22.607 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   2: 3.899 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.533 ms/op
                 listUser·p0.9999: 15.837 ms/op
                 listUser·p1.00:   16.073 ms/op

Iteration   3: 3.981 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.806 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.195 ms/op
                 listUser·p0.999:  15.198 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242671
  mean =      3.951 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 235162 
    [ 5.000,  7.500) = 5650 
    [ 7.500, 10.000) = 1124 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     15.603 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     24.212 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.447 ± 1.038  ops/ms
ClientPb.existUser                       thrpt       3   9.957 ± 1.065  ops/ms
ClientPb.getUser                         thrpt       3   9.549 ± 3.150  ops/ms
ClientPb.listUser                        thrpt       3   8.258 ± 3.988  ops/ms
ClientPb.createUser                       avgt       3   3.333 ± 2.016   ms/op
ClientPb.existUser                        avgt       3   3.271 ± 1.486   ms/op
ClientPb.getUser                          avgt       3   3.360 ± 1.581   ms/op
ClientPb.listUser                         avgt       3   3.868 ± 1.167   ms/op
ClientPb.createUser                     sample  286289   3.351 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.032           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.080           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.339           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.981           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.263           ms/op
ClientPb.existUser                      sample  294764   3.254 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.139           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.517           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.331           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.492           ms/op
ClientPb.getUser                        sample  282894   3.394 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.235           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.095           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.911           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.968           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.377           ms/op
ClientPb.listUser                       sample  242671   3.951 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.386           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.086           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.603           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.496           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.904           ms/op
