# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.015 ops/ms
# Warmup Iteration   2: 12.192 ops/ms
# Warmup Iteration   3: 12.419 ops/ms
Iteration   1: 12.466 ops/ms
Iteration   2: 12.738 ops/ms
Iteration   3: 12.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.633 ±(99.9%) 2.672 ops/ms [Average]
  (min, avg, max) = (12.466, 12.633, 12.738), stdev = 0.146
  CI (99.9%): [9.961, 15.305] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.995 ops/ms
# Warmup Iteration   2: 12.919 ops/ms
# Warmup Iteration   3: 13.240 ops/ms
Iteration   1: 13.118 ops/ms
Iteration   2: 12.822 ops/ms
Iteration   3: 13.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.003 ±(99.9%) 2.896 ops/ms [Average]
  (min, avg, max) = (12.822, 13.003, 13.118), stdev = 0.159
  CI (99.9%): [10.106, 15.899] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.760 ops/ms
# Warmup Iteration   2: 12.567 ops/ms
# Warmup Iteration   3: 12.686 ops/ms
Iteration   1: 12.636 ops/ms
Iteration   2: 12.930 ops/ms
Iteration   3: 12.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.732 ±(99.9%) 3.142 ops/ms [Average]
  (min, avg, max) = (12.628, 12.732, 12.930), stdev = 0.172
  CI (99.9%): [9.590, 15.873] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.609 ops/ms
# Warmup Iteration   2: 10.599 ops/ms
# Warmup Iteration   3: 10.452 ops/ms
Iteration   1: 10.635 ops/ms
Iteration   2: 10.406 ops/ms
Iteration   3: 10.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.536 ±(99.9%) 2.151 ops/ms [Average]
  (min, avg, max) = (10.406, 10.536, 10.635), stdev = 0.118
  CI (99.9%): [8.385, 12.687] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.210 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.631 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.529 ±(99.9%) 0.003 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.498 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (2.464, 2.498, 2.529), stdev = 0.033
  CI (99.9%): [1.901, 3.095] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.811 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.004 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
Iteration   2: 2.428 ±(99.9%) 0.004 ms/op
Iteration   3: 2.381 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.808 ms/op [Average]
  (min, avg, max) = (2.381, 2.426, 2.470), stdev = 0.044
  CI (99.9%): [1.618, 3.235] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.023 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.006 ms/op
Iteration   1: 2.428 ±(99.9%) 0.006 ms/op
Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
Iteration   3: 2.453 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.446 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (2.428, 2.446, 2.458), stdev = 0.016
  CI (99.9%): [2.148, 2.745] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.543 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.926 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.008 ms/op
Iteration   1: 2.942 ±(99.9%) 0.010 ms/op
Iteration   2: 2.929 ±(99.9%) 0.010 ms/op
Iteration   3: 2.928 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.933 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (2.928, 2.933, 2.942), stdev = 0.008
  CI (99.9%): [2.789, 3.076] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.384 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.006 ms/op
Iteration   1: 2.453 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   2.384 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.383 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  9.680 ms/op
                 createUser·p0.9999: 14.418 ms/op
                 createUser·p1.00:   14.860 ms/op

Iteration   2: 2.476 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   2.425 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.330 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  10.795 ms/op
                 createUser·p0.9999: 12.437 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   2.388 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.297 ms/op
                 createUser·p0.99:   4.104 ms/op
                 createUser·p0.999:  8.031 ms/op
                 createUser·p0.9999: 10.597 ms/op
                 createUser·p1.00:   11.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 390507
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 216380 
    [ 2.500,  3.750) = 165595 
    [ 3.750,  5.000) = 7011 
    [ 5.000,  6.250) = 720 
    [ 6.250,  7.500) = 185 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.400 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.334 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      8.724 ms/op
     p(99.9900) =     14.156 ms/op
     p(99.9990) =     14.621 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.621 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.409 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.397 ±(99.9%) 0.006 ms/op
Iteration   1: 2.426 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   2.347 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.863 ms/op
                 existUser·p0.999:  8.043 ms/op
                 existUser·p0.9999: 14.238 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.842 ms/op
                 existUser·p0.999:  7.393 ms/op
                 existUser·p0.9999: 13.304 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.226 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  7.244 ms/op
                 existUser·p0.9999: 11.731 ms/op
                 existUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390749
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 205669 
    [ 2.500,  3.750) = 179127 
    [ 3.750,  5.000) = 4569 
    [ 5.000,  6.250) = 769 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 128 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.413 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      4.030 ms/op
     p(99.9000) =      7.512 ms/op
     p(99.9900) =     13.729 ms/op
     p(99.9990) =     14.461 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.110 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  8.957 ms/op
                 getUser·p0.9999: 14.160 ms/op
                 getUser·p1.00:   14.811 ms/op

Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.146 ms/op
                 getUser·p0.999:  9.762 ms/op
                 getUser·p0.9999: 14.596 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.410 ms/op
                 getUser·p0.999:  8.652 ms/op
                 getUser·p0.9999: 10.837 ms/op
                 getUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381264
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 186990 
    [ 2.500,  3.750) = 188328 
    [ 3.750,  5.000) = 4175 
    [ 5.000,  6.250) = 1235 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 128 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =      8.658 ms/op
     p(99.9900) =     14.107 ms/op
     p(99.9990) =     15.352 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.839 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.009 ms/op
Iteration   1: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.833 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.684 ms/op
                 listUser·p0.999:  9.642 ms/op
                 listUser·p0.9999: 12.534 ms/op
                 listUser·p1.00:   13.402 ms/op

Iteration   2: 3.073 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  10.272 ms/op
                 listUser·p0.9999: 13.746 ms/op
                 listUser·p1.00:   14.467 ms/op

Iteration   3: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.504 ms/op
                 listUser·p0.9999: 12.647 ms/op
                 listUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314720
  mean =      3.048 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 88205 
    [ 2.500,  3.750) = 183585 
    [ 3.750,  5.000) = 34132 
    [ 5.000,  6.250) = 7102 
    [ 6.250,  7.500) = 827 
    [ 7.500,  8.750) = 204 
    [ 8.750, 10.000) = 211 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.950 ms/op
     p(99.9900) =     12.952 ms/op
     p(99.9990) =     14.189 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.633 ± 2.672  ops/ms
ClientPb.existUser                       thrpt       3  13.003 ± 2.896  ops/ms
ClientPb.getUser                         thrpt       3  12.732 ± 3.142  ops/ms
ClientPb.listUser                        thrpt       3  10.536 ± 2.151  ops/ms
ClientPb.createUser                       avgt       3   2.498 ± 0.597   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.808   ms/op
ClientPb.getUser                          avgt       3   2.446 ± 0.298   ms/op
ClientPb.listUser                         avgt       3   2.933 ± 0.144   ms/op
ClientPb.createUser                     sample  390507   2.455 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.751           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.724           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.156           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.860           ms/op
ClientPb.existUser                      sample  390749   2.454 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.597           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.413           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.030           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.512           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.729           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.008           ms/op
ClientPb.getUser                        sample  381264   2.516 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.772           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.100           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.658           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.107           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.401           ms/op
ClientPb.listUser                       sample  314720   3.048 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.833           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.950           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.952           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.467           ms/op
