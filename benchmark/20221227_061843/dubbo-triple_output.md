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
# Warmup Iteration   1: 2.340 ops/ms
# Warmup Iteration   2: 5.752 ops/ms
# Warmup Iteration   3: 8.812 ops/ms
Iteration   1: 9.540 ops/ms
Iteration   2: 9.207 ops/ms
Iteration   3: 9.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.494 ±(99.9%) 4.867 ops/ms [Average]
  (min, avg, max) = (9.207, 9.494, 9.735), stdev = 0.267
  CI (99.9%): [4.627, 14.361] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.252 ops/ms
# Warmup Iteration   2: 8.171 ops/ms
# Warmup Iteration   3: 9.880 ops/ms
Iteration   1: 10.069 ops/ms
Iteration   2: 9.904 ops/ms
Iteration   3: 10.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.008 ±(99.9%) 1.647 ops/ms [Average]
  (min, avg, max) = (9.904, 10.008, 10.069), stdev = 0.090
  CI (99.9%): [8.361, 11.654] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.690 ops/ms
# Warmup Iteration   2: 8.834 ops/ms
# Warmup Iteration   3: 9.238 ops/ms
Iteration   1: 9.689 ops/ms
Iteration   2: 9.453 ops/ms
Iteration   3: 9.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.382 ±(99.9%) 6.354 ops/ms [Average]
  (min, avg, max) = (9.003, 9.382, 9.689), stdev = 0.348
  CI (99.9%): [3.028, 15.736] (assumes normal distribution)


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
# Warmup Iteration   1: 3.136 ops/ms
# Warmup Iteration   2: 7.607 ops/ms
# Warmup Iteration   3: 7.898 ops/ms
Iteration   1: 7.951 ops/ms
Iteration   2: 8.080 ops/ms
Iteration   3: 8.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.156 ±(99.9%) 4.600 ops/ms [Average]
  (min, avg, max) = (7.951, 8.156, 8.438), stdev = 0.252
  CI (99.9%): [3.556, 12.757] (assumes normal distribution)


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
# Warmup Iteration   1: 8.628 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.644 ±(99.9%) 0.005 ms/op
Iteration   1: 3.337 ±(99.9%) 0.008 ms/op
Iteration   2: 3.403 ±(99.9%) 0.006 ms/op
Iteration   3: 3.469 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.403 ±(99.9%) 1.204 ms/op [Average]
  (min, avg, max) = (3.337, 3.403, 3.469), stdev = 0.066
  CI (99.9%): [2.198, 4.607] (assumes normal distribution)


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
# Warmup Iteration   1: 8.264 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.517 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.006 ms/op
Iteration   1: 3.289 ±(99.9%) 0.006 ms/op
Iteration   2: 3.242 ±(99.9%) 0.004 ms/op
Iteration   3: 3.147 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.226 ±(99.9%) 1.322 ms/op [Average]
  (min, avg, max) = (3.147, 3.226, 3.289), stdev = 0.072
  CI (99.9%): [1.904, 4.548] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.038 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.846 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.005 ms/op
Iteration   1: 3.308 ±(99.9%) 0.009 ms/op
Iteration   2: 3.279 ±(99.9%) 0.011 ms/op
Iteration   3: 3.426 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.338 ±(99.9%) 1.414 ms/op [Average]
  (min, avg, max) = (3.279, 3.338, 3.426), stdev = 0.078
  CI (99.9%): [1.924, 4.752] (assumes normal distribution)


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
# Warmup Iteration   1: 10.090 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.009 ms/op
Iteration   1: 3.954 ±(99.9%) 0.012 ms/op
Iteration   2: 3.881 ±(99.9%) 0.009 ms/op
Iteration   3: 3.836 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.890 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (3.836, 3.890, 3.954), stdev = 0.060
  CI (99.9%): [2.801, 4.979] (assumes normal distribution)


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
# Warmup Iteration   1: 8.846 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.009 ms/op
Iteration   1: 3.540 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  17.948 ms/op
                 createUser·p0.9999: 19.922 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   2: 3.513 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.462 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  20.217 ms/op
                 createUser·p0.9999: 27.165 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   3: 3.334 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.270 ms/op
                 createUser·p0.999:  18.612 ms/op
                 createUser·p0.9999: 27.342 ms/op
                 createUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277158
  mean =      3.460 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8631 
    [ 2.500,  5.000) = 261889 
    [ 5.000,  7.500) = 5856 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     18.279 ms/op
     p(99.9900) =     26.954 ms/op
     p(99.9990) =     27.802 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 7.802 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.008 ms/op
Iteration   1: 3.240 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  11.473 ms/op
                 existUser·p0.9999: 23.626 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   2: 3.280 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.415 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  12.206 ms/op
                 existUser·p0.9999: 25.721 ms/op
                 existUser·p1.00:   26.444 ms/op

Iteration   3: 3.295 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  15.735 ms/op
                 existUser·p0.9999: 21.254 ms/op
                 existUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293222
  mean =      3.272 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14051 
    [ 2.500,  5.000) = 274793 
    [ 5.000,  7.500) = 3423 
    [ 7.500, 10.000) = 410 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     15.594 ms/op
     p(99.9900) =     24.402 ms/op
     p(99.9990) =     26.086 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.643 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.010 ms/op
Iteration   1: 3.387 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.452 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   6.009 ms/op
                 getUser·p0.999:  20.349 ms/op
                 getUser·p0.9999: 23.350 ms/op
                 getUser·p1.00:   24.838 ms/op

Iteration   2: 3.451 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  19.541 ms/op
                 getUser·p0.9999: 23.748 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   3: 3.404 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.712 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  16.896 ms/op
                 getUser·p0.9999: 26.088 ms/op
                 getUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280937
  mean =      3.414 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3342 
    [ 2.500,  5.000) = 269760 
    [ 5.000,  7.500) = 6789 
    [ 7.500, 10.000) = 667 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.452 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     24.570 ms/op
     p(99.9990) =     27.105 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 9.946 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.364 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.087 ±(99.9%) 0.014 ms/op
Iteration   1: 3.868 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.888 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  17.163 ms/op
                 listUser·p0.9999: 23.125 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   2: 3.989 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  14.402 ms/op
                 listUser·p0.9999: 19.625 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 4.020 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  15.392 ms/op
                 listUser·p0.9999: 21.727 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242469
  mean =      3.958 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 232134 
    [ 5.000,  7.500) = 8749 
    [ 7.500, 10.000) = 865 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     22.266 ms/op
     p(99.9990) =     23.481 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.494 ± 4.867  ops/ms
ClientPb.existUser                       thrpt       3  10.008 ± 1.647  ops/ms
ClientPb.getUser                         thrpt       3   9.382 ± 6.354  ops/ms
ClientPb.listUser                        thrpt       3   8.156 ± 4.600  ops/ms
ClientPb.createUser                       avgt       3   3.403 ± 1.204   ms/op
ClientPb.existUser                        avgt       3   3.226 ± 1.322   ms/op
ClientPb.getUser                          avgt       3   3.338 ± 1.414   ms/op
ClientPb.listUser                         avgt       3   3.890 ± 1.089   ms/op
ClientPb.createUser                     sample  277158   3.460 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.376           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.677           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.279           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.954           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.951           ms/op
ClientPb.existUser                      sample  293222   3.272 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.223           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.530           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.594           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.402           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.444           ms/op
ClientPb.getUser                        sample  280937   3.414 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.452           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.760           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.570           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.918           ms/op
ClientPb.listUser                       sample  242469   3.958 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.315           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.882           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.483           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.266           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.495           ms/op
