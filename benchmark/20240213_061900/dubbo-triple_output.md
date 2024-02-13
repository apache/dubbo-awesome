# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.053 ops/ms
# Warmup Iteration   2: 12.383 ops/ms
# Warmup Iteration   3: 12.656 ops/ms
Iteration   1: 12.713 ops/ms
Iteration   2: 12.865 ops/ms
Iteration   3: 12.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.792 ±(99.9%) 1.394 ops/ms [Average]
  (min, avg, max) = (12.713, 12.792, 12.865), stdev = 0.076
  CI (99.9%): [11.398, 14.186] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.573 ops/ms
# Warmup Iteration   2: 13.554 ops/ms
# Warmup Iteration   3: 13.674 ops/ms
Iteration   1: 13.646 ops/ms
Iteration   2: 13.469 ops/ms
Iteration   3: 13.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.503 ±(99.9%) 2.355 ops/ms [Average]
  (min, avg, max) = (13.394, 13.503, 13.646), stdev = 0.129
  CI (99.9%): [11.147, 15.858] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.755 ops/ms
# Warmup Iteration   2: 13.233 ops/ms
# Warmup Iteration   3: 13.010 ops/ms
Iteration   1: 13.218 ops/ms
Iteration   2: 13.190 ops/ms
Iteration   3: 13.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.205 ±(99.9%) 0.258 ops/ms [Average]
  (min, avg, max) = (13.190, 13.205, 13.218), stdev = 0.014
  CI (99.9%): [12.947, 13.462] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.210 ops/ms
# Warmup Iteration   2: 10.916 ops/ms
# Warmup Iteration   3: 11.024 ops/ms
Iteration   1: 11.054 ops/ms
Iteration   2: 11.053 ops/ms
Iteration   3: 11.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  11.054 ±(99.9%) 0.029 ops/ms [Average]
  (min, avg, max) = (11.053, 11.054, 11.056), stdev = 0.002
  CI (99.9%): [11.026, 11.083] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.946 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.004 ms/op
Iteration   1: 2.440 ±(99.9%) 0.004 ms/op
Iteration   2: 2.428 ±(99.9%) 0.004 ms/op
Iteration   3: 2.420 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.429 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.420, 2.429, 2.440), stdev = 0.010
  CI (99.9%): [2.238, 2.621] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.515 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.397 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.371 ±(99.9%) 0.004 ms/op
Iteration   1: 2.381 ±(99.9%) 0.004 ms/op
Iteration   2: 2.395 ±(99.9%) 0.003 ms/op
Iteration   3: 2.367 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.381 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (2.367, 2.381, 2.395), stdev = 0.014
  CI (99.9%): [2.127, 2.636] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.622 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.420 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.406 ±(99.9%) 0.004 ms/op
Iteration   1: 2.430 ±(99.9%) 0.004 ms/op
Iteration   2: 2.403 ±(99.9%) 0.004 ms/op
Iteration   3: 2.403 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.412 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (2.403, 2.412, 2.430), stdev = 0.015
  CI (99.9%): [2.134, 2.690] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.649 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.004 ms/op
Iteration   1: 2.940 ±(99.9%) 0.005 ms/op
Iteration   2: 2.928 ±(99.9%) 0.006 ms/op
Iteration   3: 2.925 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.931 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (2.925, 2.931, 2.940), stdev = 0.008
  CI (99.9%): [2.792, 3.070] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.876 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.388 ±(99.9%) 0.005 ms/op
Iteration   1: 2.399 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   2.437 ms/op
                 createUser·p0.90:   2.937 ms/op
                 createUser·p0.95:   3.056 ms/op
                 createUser·p0.99:   3.527 ms/op
                 createUser·p0.999:  5.895 ms/op
                 createUser·p0.9999: 13.615 ms/op
                 createUser·p1.00:   14.385 ms/op

Iteration   2: 2.398 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   2.433 ms/op
                 createUser·p0.90:   2.937 ms/op
                 createUser·p0.95:   3.047 ms/op
                 createUser·p0.99:   3.518 ms/op
                 createUser·p0.999:  5.792 ms/op
                 createUser·p0.9999: 11.108 ms/op
                 createUser·p1.00:   11.534 ms/op

Iteration   3: 2.399 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.642 ms/op
                 createUser·p0.50:   2.429 ms/op
                 createUser·p0.90:   2.945 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   3.621 ms/op
                 createUser·p0.999:  8.171 ms/op
                 createUser·p0.9999: 10.213 ms/op
                 createUser·p1.00:   10.961 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 399822
  mean =      2.399 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 210291 
    [ 2.500,  3.750) = 186666 
    [ 3.750,  5.000) = 2177 
    [ 5.000,  6.250) = 187 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 164 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =      8.062 ms/op
     p(99.9900) =     12.078 ms/op
     p(99.9990) =     14.254 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.528 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.385 ±(99.9%) 0.005 ms/op
Iteration   1: 2.366 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.884 ms/op
                 existUser·p0.95:   2.978 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  6.211 ms/op
                 existUser·p0.9999: 13.672 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   2: 2.384 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  5.808 ms/op
                 existUser·p0.9999: 13.929 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   3: 2.376 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.408 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  8.146 ms/op
                 existUser·p0.9999: 10.955 ms/op
                 existUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 403738
  mean =      2.375 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 213210 
    [ 2.500,  3.750) = 187516 
    [ 3.750,  5.000) = 2096 
    [ 5.000,  6.250) = 369 
    [ 6.250,  7.500) = 107 
    [ 7.500,  8.750) = 78 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.429 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.011 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =      7.219 ms/op
     p(99.9900) =     13.718 ms/op
     p(99.9990) =     14.496 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.074 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
Iteration   1: 2.439 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.015 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   4.019 ms/op
                 getUser·p0.999:  6.341 ms/op
                 getUser·p0.9999: 13.430 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   2: 2.418 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.433 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.060 ms/op
                 getUser·p0.99:   3.473 ms/op
                 getUser·p0.999:  9.401 ms/op
                 getUser·p0.9999: 12.759 ms/op
                 getUser·p1.00:   13.435 ms/op

Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   2.449 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  7.159 ms/op
                 getUser·p0.9999: 9.634 ms/op
                 getUser·p1.00:   10.535 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 394399
  mean =      2.432 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 203262 
    [ 2.500,  3.750) = 186851 
    [ 3.750,  5.000) = 3103 
    [ 5.000,  6.250) = 655 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 160 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.449 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      8.398 ms/op
     p(99.9900) =     12.789 ms/op
     p(99.9990) =     13.550 ms/op
     p(99.9999) =     13.582 ms/op
    p(100.0000) =     13.582 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.568 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.962 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.008 ms/op
Iteration   1: 2.896 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   2.834 ms/op
                 listUser·p0.90:   3.752 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   5.366 ms/op
                 listUser·p0.999:  8.808 ms/op
                 listUser·p0.9999: 10.320 ms/op
                 listUser·p1.00:   10.600 ms/op

Iteration   2: 2.889 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   2.826 ms/op
                 listUser·p0.90:   3.723 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   5.285 ms/op
                 listUser·p0.999:  8.607 ms/op
                 listUser·p0.9999: 13.153 ms/op
                 listUser·p1.00:   13.828 ms/op

Iteration   3: 2.915 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   2.851 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   5.366 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 11.290 ms/op
                 listUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 330765
  mean =      2.900 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 211 
    [ 1.250,  2.500) = 111256 
    [ 2.500,  3.750) = 186346 
    [ 3.750,  5.000) = 27340 
    [ 5.000,  6.250) = 4607 
    [ 6.250,  7.500) = 369 
    [ 7.500,  8.750) = 269 
    [ 8.750, 10.000) = 200 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =      8.933 ms/op
     p(99.9900) =     11.436 ms/op
     p(99.9990) =     13.660 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.792 ± 1.394  ops/ms
ClientPb.existUser                       thrpt       3  13.503 ± 2.355  ops/ms
ClientPb.getUser                         thrpt       3  13.205 ± 0.258  ops/ms
ClientPb.listUser                        thrpt       3  11.054 ± 0.029  ops/ms
ClientPb.createUser                       avgt       3   2.429 ± 0.191   ms/op
ClientPb.existUser                        avgt       3   2.381 ± 0.254   ms/op
ClientPb.getUser                          avgt       3   2.412 ± 0.278   ms/op
ClientPb.listUser                         avgt       3   2.931 ± 0.139   ms/op
ClientPb.createUser                     sample  399822   2.399 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.642           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.433           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.941           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.555           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.062           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.078           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.385           ms/op
ClientPb.existUser                      sample  403738   2.375 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.741           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.429           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.904           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.219           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.718           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.762           ms/op
ClientPb.getUser                        sample  394399   2.432 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.868           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.449           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.978           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.398           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.789           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.582           ms/op
ClientPb.listUser                       sample  330765   2.900 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.798           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.748           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.341           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.933           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.436           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.828           ms/op
