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
# Warmup Iteration   1: 2.481 ops/ms
# Warmup Iteration   2: 6.072 ops/ms
# Warmup Iteration   3: 8.760 ops/ms
Iteration   1: 9.107 ops/ms
Iteration   2: 9.531 ops/ms
Iteration   3: 9.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.313 ±(99.9%) 3.880 ops/ms [Average]
  (min, avg, max) = (9.107, 9.313, 9.531), stdev = 0.213
  CI (99.9%): [5.432, 13.193] (assumes normal distribution)


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
# Warmup Iteration   1: 3.587 ops/ms
# Warmup Iteration   2: 9.216 ops/ms
# Warmup Iteration   3: 9.710 ops/ms
Iteration   1: 9.899 ops/ms
Iteration   2: 10.103 ops/ms
Iteration   3: 9.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.963 ±(99.9%) 2.207 ops/ms [Average]
  (min, avg, max) = (9.888, 9.963, 10.103), stdev = 0.121
  CI (99.9%): [7.756, 12.170] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.821 ops/ms
# Warmup Iteration   2: 8.462 ops/ms
# Warmup Iteration   3: 8.867 ops/ms
Iteration   1: 9.333 ops/ms
Iteration   2: 9.192 ops/ms
Iteration   3: 9.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.334 ±(99.9%) 2.608 ops/ms [Average]
  (min, avg, max) = (9.192, 9.334, 9.478), stdev = 0.143
  CI (99.9%): [6.726, 11.942] (assumes normal distribution)


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
# Warmup Iteration   1: 3.141 ops/ms
# Warmup Iteration   2: 7.526 ops/ms
# Warmup Iteration   3: 8.016 ops/ms
Iteration   1: 8.187 ops/ms
Iteration   2: 8.322 ops/ms
Iteration   3: 8.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.282 ±(99.9%) 1.517 ops/ms [Average]
  (min, avg, max) = (8.187, 8.282, 8.338), stdev = 0.083
  CI (99.9%): [6.766, 9.799] (assumes normal distribution)


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
# Warmup Iteration   1: 8.701 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.739 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.663 ±(99.9%) 0.003 ms/op
Iteration   1: 3.324 ±(99.9%) 0.005 ms/op
Iteration   2: 3.245 ±(99.9%) 0.009 ms/op
Iteration   3: 3.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.358 ±(99.9%) 2.444 ms/op [Average]
  (min, avg, max) = (3.245, 3.358, 3.506), stdev = 0.134
  CI (99.9%): [0.914, 5.803] (assumes normal distribution)


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
# Warmup Iteration   1: 8.359 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.005 ms/op
Iteration   1: 3.210 ±(99.9%) 0.011 ms/op
Iteration   2: 3.192 ±(99.9%) 0.009 ms/op
Iteration   3: 3.168 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.190 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (3.168, 3.190, 3.210), stdev = 0.021
  CI (99.9%): [2.803, 3.577] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.552 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.004 ms/op
Iteration   1: 3.431 ±(99.9%) 0.008 ms/op
Iteration   2: 3.343 ±(99.9%) 0.004 ms/op
Iteration   3: 3.289 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.354 ±(99.9%) 1.310 ms/op [Average]
  (min, avg, max) = (3.289, 3.354, 3.431), stdev = 0.072
  CI (99.9%): [2.044, 4.664] (assumes normal distribution)


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
# Warmup Iteration   1: 8.980 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.242 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.927 ±(99.9%) 0.008 ms/op
Iteration   1: 3.962 ±(99.9%) 0.006 ms/op
Iteration   2: 3.858 ±(99.9%) 0.015 ms/op
Iteration   3: 3.929 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.916 ±(99.9%) 0.971 ms/op [Average]
  (min, avg, max) = (3.858, 3.916, 3.962), stdev = 0.053
  CI (99.9%): [2.946, 4.887] (assumes normal distribution)


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
# Warmup Iteration   1: 9.632 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.010 ms/op
Iteration   1: 3.264 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.329 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  13.337 ms/op
                 createUser·p0.9999: 25.388 ms/op
                 createUser·p1.00:   25.952 ms/op

Iteration   2: 3.416 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  21.282 ms/op
                 createUser·p0.9999: 26.629 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   3: 3.313 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.344 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  16.286 ms/op
                 createUser·p0.9999: 24.183 ms/op
                 createUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288291
  mean =      3.330 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15157 
    [ 2.500,  5.000) = 268601 
    [ 5.000,  7.500) = 3620 
    [ 7.500, 10.000) = 482 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.344 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     16.286 ms/op
     p(99.9900) =     25.761 ms/op
     p(99.9990) =     27.839 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 7.607 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.010 ms/op
Iteration   1: 3.301 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.963 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  10.724 ms/op
                 existUser·p0.9999: 22.020 ms/op
                 existUser·p1.00:   22.479 ms/op

Iteration   2: 3.293 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.989 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  13.203 ms/op
                 existUser·p0.9999: 25.831 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   3: 3.328 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.196 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  17.718 ms/op
                 existUser·p0.9999: 27.517 ms/op
                 existUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290078
  mean =      3.307 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18005 
    [ 2.500,  5.000) = 265524 
    [ 5.000,  7.500) = 5622 
    [ 7.500, 10.000) = 515 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     13.034 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     28.053 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 9.358 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.011 ms/op
Iteration   1: 3.450 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.354 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.575 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  19.972 ms/op
                 getUser·p0.9999: 22.184 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   2: 3.357 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  21.294 ms/op
                 getUser·p0.9999: 24.407 ms/op
                 getUser·p1.00:   25.526 ms/op

Iteration   3: 3.344 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.438 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   5.611 ms/op
                 getUser·p0.999:  15.032 ms/op
                 getUser·p0.9999: 25.603 ms/op
                 getUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283720
  mean =      3.383 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2466 
    [ 2.500,  5.000) = 273705 
    [ 5.000,  7.500) = 6558 
    [ 7.500, 10.000) = 607 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     16.646 ms/op
     p(99.9900) =     25.055 ms/op
     p(99.9990) =     25.990 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 9.275 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.011 ms/op
Iteration   1: 4.056 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.873 ms/op
                 listUser·p0.999:  22.287 ms/op
                 listUser·p0.9999: 24.973 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   2: 3.925 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.511 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  14.353 ms/op
                 listUser·p0.9999: 18.612 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   3: 3.953 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  15.024 ms/op
                 listUser·p0.9999: 17.498 ms/op
                 listUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241292
  mean =      3.977 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 232869 
    [ 5.000,  7.500) = 6173 
    [ 7.500, 10.000) = 1394 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.226 ms/op
     p(99.9000) =     15.314 ms/op
     p(99.9900) =     23.986 ms/op
     p(99.9990) =     25.689 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.313 ± 3.880  ops/ms
ClientPb.existUser                       thrpt       3   9.963 ± 2.207  ops/ms
ClientPb.getUser                         thrpt       3   9.334 ± 2.608  ops/ms
ClientPb.listUser                        thrpt       3   8.282 ± 1.517  ops/ms
ClientPb.createUser                       avgt       3   3.358 ± 2.444   ms/op
ClientPb.existUser                        avgt       3   3.190 ± 0.387   ms/op
ClientPb.getUser                          avgt       3   3.354 ± 1.310   ms/op
ClientPb.listUser                         avgt       3   3.916 ± 0.971   ms/op
ClientPb.createUser                     sample  288291   3.330 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.344           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.067           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.286           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.761           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.344           ms/op
ClientPb.existUser                      sample  290078   3.307 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.989           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.961           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.034           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.214           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.115           ms/op
ClientPb.getUser                        sample  283720   3.383 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.732           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.740           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.177           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.646           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.055           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.051           ms/op
ClientPb.listUser                       sample  241292   3.977 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.067           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.226           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.314           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.986           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.116           ms/op
