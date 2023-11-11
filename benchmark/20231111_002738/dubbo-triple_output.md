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
# Warmup Iteration   1: 4.522 ops/ms
# Warmup Iteration   2: 11.762 ops/ms
# Warmup Iteration   3: 12.139 ops/ms
Iteration   1: 12.427 ops/ms
Iteration   2: 12.537 ops/ms
Iteration   3: 12.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.442 ±(99.9%) 1.621 ops/ms [Average]
  (min, avg, max) = (12.362, 12.442, 12.537), stdev = 0.089
  CI (99.9%): [10.821, 14.063] (assumes normal distribution)


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
# Warmup Iteration   1: 8.416 ops/ms
# Warmup Iteration   2: 12.957 ops/ms
# Warmup Iteration   3: 12.872 ops/ms
Iteration   1: 12.743 ops/ms
Iteration   2: 13.147 ops/ms
Iteration   3: 12.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.937 ±(99.9%) 3.696 ops/ms [Average]
  (min, avg, max) = (12.743, 12.937, 13.147), stdev = 0.203
  CI (99.9%): [9.240, 16.633] (assumes normal distribution)


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
# Warmup Iteration   1: 7.375 ops/ms
# Warmup Iteration   2: 12.364 ops/ms
# Warmup Iteration   3: 12.367 ops/ms
Iteration   1: 12.578 ops/ms
Iteration   2: 12.579 ops/ms
Iteration   3: 12.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.564 ±(99.9%) 0.442 ops/ms [Average]
  (min, avg, max) = (12.536, 12.564, 12.579), stdev = 0.024
  CI (99.9%): [12.122, 13.007] (assumes normal distribution)


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
# Warmup Iteration   1: 6.179 ops/ms
# Warmup Iteration   2: 10.261 ops/ms
# Warmup Iteration   3: 10.197 ops/ms
Iteration   1: 10.434 ops/ms
Iteration   2: 10.463 ops/ms
Iteration   3: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.465 ±(99.9%) 0.585 ops/ms [Average]
  (min, avg, max) = (10.434, 10.465, 10.498), stdev = 0.032
  CI (99.9%): [9.881, 11.050] (assumes normal distribution)


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.004 ms/op
Iteration   1: 2.554 ±(99.9%) 0.004 ms/op
Iteration   2: 2.604 ±(99.9%) 0.004 ms/op
Iteration   3: 2.561 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.573 ±(99.9%) 0.491 ms/op [Average]
  (min, avg, max) = (2.554, 2.573, 2.604), stdev = 0.027
  CI (99.9%): [2.081, 3.064] (assumes normal distribution)


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
# Warmup Iteration   1: 3.829 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.003 ms/op
Iteration   1: 2.448 ±(99.9%) 0.004 ms/op
Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
Iteration   3: 2.454 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.453 ±(99.9%) 0.091 ms/op [Average]
  (min, avg, max) = (2.448, 2.453, 2.458), stdev = 0.005
  CI (99.9%): [2.362, 2.544] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.993 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.004 ms/op
Iteration   1: 2.526 ±(99.9%) 0.004 ms/op
Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
Iteration   3: 2.548 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.537 ±(99.9%) 0.201 ms/op [Average]
  (min, avg, max) = (2.526, 2.537, 2.548), stdev = 0.011
  CI (99.9%): [2.335, 2.738] (assumes normal distribution)


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
Iteration   1: 3.036 ±(99.9%) 0.007 ms/op
Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
Iteration   3: 3.023 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.029 ±(99.9%) 0.120 ms/op [Average]
  (min, avg, max) = (3.023, 3.029, 3.036), stdev = 0.007
  CI (99.9%): [2.909, 3.149] (assumes normal distribution)


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
# Warmup Iteration   1: 4.372 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.684 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.544 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.036 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.990 ms/op
                 createUser·p0.999:  11.365 ms/op
                 createUser·p0.9999: 13.844 ms/op
                 createUser·p1.00:   14.696 ms/op

Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.828 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  9.748 ms/op
                 createUser·p0.9999: 12.318 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   3: 2.553 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   4.022 ms/op
                 createUser·p0.999:  8.498 ms/op
                 createUser·p0.9999: 10.281 ms/op
                 createUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377239
  mean =      2.543 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 177711 
    [ 2.500,  3.750) = 194832 
    [ 3.750,  5.000) = 3407 
    [ 5.000,  6.250) = 705 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      8.811 ms/op
     p(99.9900) =     13.599 ms/op
     p(99.9990) =     14.539 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.997 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  11.925 ms/op
                 existUser·p0.9999: 13.631 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.626 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.739 ms/op
                 existUser·p0.999:  6.073 ms/op
                 existUser·p0.9999: 13.484 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.887 ms/op
                 existUser·p0.999:  6.287 ms/op
                 existUser·p0.9999: 12.222 ms/op
                 existUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381438
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 185972 
    [ 2.500,  3.750) = 191777 
    [ 3.750,  5.000) = 2629 
    [ 5.000,  6.250) = 642 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 133 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      6.259 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     13.971 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 3.840 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  12.090 ms/op
                 getUser·p0.9999: 14.025 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.027 ms/op
                 getUser·p0.999:  9.657 ms/op
                 getUser·p0.9999: 13.277 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   3: 2.564 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.297 ms/op
                 getUser·p0.99:   4.133 ms/op
                 getUser·p0.999:  8.639 ms/op
                 getUser·p0.9999: 11.314 ms/op
                 getUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378597
  mean =      2.534 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 184975 
    [ 2.500,  3.750) = 187955 
    [ 3.750,  5.000) = 4358 
    [ 5.000,  6.250) = 712 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      4.010 ms/op
     p(99.9000) =      8.657 ms/op
     p(99.9900) =     13.877 ms/op
     p(99.9990) =     14.137 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.774 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.009 ms/op
Iteration   1: 3.086 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  9.767 ms/op
                 listUser·p0.9999: 11.911 ms/op
                 listUser·p1.00:   12.124 ms/op

Iteration   2: 3.075 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.897 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.860 ms/op
                 listUser·p0.999:  9.667 ms/op
                 listUser·p0.9999: 15.123 ms/op
                 listUser·p1.00:   15.663 ms/op

Iteration   3: 3.050 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.030 ms/op
                 listUser·p0.9999: 10.338 ms/op
                 listUser·p1.00:   10.912 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312416
  mean =      3.070 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 84422 
    [ 2.500,  3.750) = 185487 
    [ 3.750,  5.000) = 33759 
    [ 5.000,  6.250) = 7034 
    [ 6.250,  7.500) = 923 
    [ 7.500,  8.750) = 271 
    [ 8.750, 10.000) = 210 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =      9.299 ms/op
     p(99.9900) =     13.557 ms/op
     p(99.9990) =     15.499 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.442 ± 1.621  ops/ms
ClientPb.existUser                       thrpt       3  12.937 ± 3.696  ops/ms
ClientPb.getUser                         thrpt       3  12.564 ± 0.442  ops/ms
ClientPb.listUser                        thrpt       3  10.465 ± 0.585  ops/ms
ClientPb.createUser                       avgt       3   2.573 ± 0.491   ms/op
ClientPb.existUser                        avgt       3   2.453 ± 0.091   ms/op
ClientPb.getUser                          avgt       3   2.537 ± 0.201   ms/op
ClientPb.listUser                         avgt       3   3.029 ± 0.120   ms/op
ClientPb.createUser                     sample  377239   2.543 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.828           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.650           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.811           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.599           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.696           ms/op
ClientPb.existUser                      sample  381438   2.514 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.997           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.259           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.500           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.189           ms/op
ClientPb.getUser                        sample  378597   2.534 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.966           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.657           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.877           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.189           ms/op
ClientPb.listUser                       sample  312416   3.070 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.867           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.759           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.299           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.557           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.663           ms/op
