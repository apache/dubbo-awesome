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
# Warmup Iteration   1: 2.130 ops/ms
# Warmup Iteration   2: 5.861 ops/ms
# Warmup Iteration   3: 8.709 ops/ms
Iteration   1: 8.983 ops/ms
Iteration   2: 9.744 ops/ms
Iteration   3: 9.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.255 ±(99.9%) 7.736 ops/ms [Average]
  (min, avg, max) = (8.983, 9.255, 9.744), stdev = 0.424
  CI (99.9%): [1.519, 16.992] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.309 ops/ms
# Warmup Iteration   2: 9.029 ops/ms
# Warmup Iteration   3: 9.437 ops/ms
Iteration   1: 9.546 ops/ms
Iteration   2: 9.339 ops/ms
Iteration   3: 9.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.551 ±(99.9%) 3.926 ops/ms [Average]
  (min, avg, max) = (9.339, 9.551, 9.769), stdev = 0.215
  CI (99.9%): [5.625, 13.477] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.053 ops/ms
# Warmup Iteration   2: 8.585 ops/ms
# Warmup Iteration   3: 8.992 ops/ms
Iteration   1: 8.987 ops/ms
Iteration   2: 9.367 ops/ms
Iteration   3: 9.188 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.181 ±(99.9%) 3.468 ops/ms [Average]
  (min, avg, max) = (8.987, 9.181, 9.367), stdev = 0.190
  CI (99.9%): [5.713, 12.649] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.593 ops/ms
# Warmup Iteration   2: 7.552 ops/ms
# Warmup Iteration   3: 7.484 ops/ms
Iteration   1: 7.919 ops/ms
Iteration   2: 8.010 ops/ms
Iteration   3: 8.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.072 ±(99.9%) 3.492 ops/ms [Average]
  (min, avg, max) = (7.919, 8.072, 8.287), stdev = 0.191
  CI (99.9%): [4.580, 11.565] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.467 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.005 ms/op
Iteration   1: 3.390 ±(99.9%) 0.008 ms/op
Iteration   2: 3.297 ±(99.9%) 0.013 ms/op
Iteration   3: 3.295 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.327 ±(99.9%) 0.984 ms/op [Average]
  (min, avg, max) = (3.295, 3.327, 3.390), stdev = 0.054
  CI (99.9%): [2.343, 4.312] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.571 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.412 ±(99.9%) 0.006 ms/op
Iteration   1: 3.550 ±(99.9%) 0.006 ms/op
Iteration   2: 3.282 ±(99.9%) 0.009 ms/op
Iteration   3: 3.245 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.359 ±(99.9%) 3.038 ms/op [Average]
  (min, avg, max) = (3.245, 3.359, 3.550), stdev = 0.167
  CI (99.9%): [0.321, 6.397] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 10.878 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.007 ms/op
Iteration   1: 3.482 ±(99.9%) 0.009 ms/op
Iteration   2: 3.406 ±(99.9%) 0.005 ms/op
Iteration   3: 3.323 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.404 ±(99.9%) 1.451 ms/op [Average]
  (min, avg, max) = (3.323, 3.404, 3.482), stdev = 0.080
  CI (99.9%): [1.953, 4.854] (assumes normal distribution)


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
# Warmup Iteration   1: 9.893 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.575 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.006 ms/op
Iteration   1: 3.907 ±(99.9%) 0.012 ms/op
Iteration   2: 3.993 ±(99.9%) 0.004 ms/op
Iteration   3: 3.678 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.859 ±(99.9%) 2.970 ms/op [Average]
  (min, avg, max) = (3.678, 3.859, 3.993), stdev = 0.163
  CI (99.9%): [0.889, 6.829] (assumes normal distribution)


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
# Warmup Iteration   1: 8.959 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.010 ms/op
Iteration   1: 3.502 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  24.926 ms/op
                 createUser·p0.9999: 31.473 ms/op
                 createUser·p1.00:   32.309 ms/op

Iteration   2: 3.197 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.958 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.079 ms/op
                 createUser·p0.999:  13.051 ms/op
                 createUser·p0.9999: 32.866 ms/op
                 createUser·p1.00:   33.522 ms/op

Iteration   3: 3.418 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.463 ms/op
                 createUser·p0.999:  20.808 ms/op
                 createUser·p0.9999: 29.247 ms/op
                 createUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284884
  mean =      3.368 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12210 
    [ 2.500,  5.000) = 267639 
    [ 5.000,  7.500) = 3742 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     20.815 ms/op
     p(99.9900) =     31.834 ms/op
     p(99.9990) =     33.340 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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
# Warmup Iteration   1: 9.223 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.687 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.009 ms/op
Iteration   1: 3.131 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.556 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  10.221 ms/op
                 existUser·p0.9999: 24.912 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   2: 3.383 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.659 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  25.049 ms/op
                 existUser·p0.9999: 27.558 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   3: 3.394 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.427 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.878 ms/op
                 existUser·p0.999:  19.692 ms/op
                 existUser·p0.9999: 28.920 ms/op
                 existUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291090
  mean =      3.298 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7887 
    [ 2.500,  5.000) = 278860 
    [ 5.000,  7.500) = 3522 
    [ 7.500, 10.000) = 275 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 107 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     19.845 ms/op
     p(99.9900) =     28.049 ms/op
     p(99.9990) =     29.370 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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
# Warmup Iteration   1: 10.641 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.092 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.011 ms/op
Iteration   1: 3.658 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.767 ms/op
                 getUser·p0.50:   3.498 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   7.577 ms/op
                 getUser·p0.999:  26.037 ms/op
                 getUser·p0.9999: 34.916 ms/op
                 getUser·p1.00:   39.911 ms/op

Iteration   2: 3.496 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.929 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   7.709 ms/op
                 getUser·p0.999:  26.362 ms/op
                 getUser·p0.9999: 32.187 ms/op
                 getUser·p1.00:   34.341 ms/op

Iteration   3: 3.650 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   7.119 ms/op
                 getUser·p0.999:  15.335 ms/op
                 getUser·p0.9999: 28.284 ms/op
                 getUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266550
  mean =      3.600 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5051 
    [ 2.500,  5.000) = 251688 
    [ 5.000,  7.500) = 7261 
    [ 7.500, 10.000) = 1846 
    [10.000, 12.500) = 309 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     33.839 ms/op
     p(99.9990) =     37.181 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


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
# Warmup Iteration   1: 13.891 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 4.608 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.015 ms/op
Iteration   1: 3.942 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  22.704 ms/op
                 listUser·p0.9999: 26.706 ms/op
                 listUser·p1.00:   27.787 ms/op

Iteration   2: 4.144 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  17.493 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   3: 4.126 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  17.973 ms/op
                 listUser·p0.9999: 20.750 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235782
  mean =      4.068 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 222170 
    [ 5.000,  7.500) = 11097 
    [ 7.500, 10.000) = 1486 
    [10.000, 12.500) = 363 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 158 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      2.146 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.143 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     26.195 ms/op
     p(99.9990) =     27.244 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.255 ± 7.736  ops/ms
ClientPb.existUser                       thrpt       3   9.551 ± 3.926  ops/ms
ClientPb.getUser                         thrpt       3   9.181 ± 3.468  ops/ms
ClientPb.listUser                        thrpt       3   8.072 ± 3.492  ops/ms
ClientPb.createUser                       avgt       3   3.327 ± 0.984   ms/op
ClientPb.existUser                        avgt       3   3.359 ± 3.038   ms/op
ClientPb.getUser                          avgt       3   3.404 ± 1.451   ms/op
ClientPb.listUser                         avgt       3   3.859 ± 2.970   ms/op
ClientPb.createUser                     sample  284884   3.368 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.176           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.923           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.815           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.834           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.522           ms/op
ClientPb.existUser                      sample  291090   3.298 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.427           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.883           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.530           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.845           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.049           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.556           ms/op
ClientPb.getUser                        sample  266550   3.600 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.264           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.445           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.422           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.941           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.839           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.911           ms/op
ClientPb.listUser                       sample  235782   4.068 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.146           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.143           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.578           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.022           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.195           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.787           ms/op
