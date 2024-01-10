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
# Warmup Iteration   1: 5.155 ops/ms
# Warmup Iteration   2: 12.140 ops/ms
# Warmup Iteration   3: 12.475 ops/ms
Iteration   1: 12.593 ops/ms
Iteration   2: 12.561 ops/ms
Iteration   3: 12.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.554 ±(99.9%) 0.767 ops/ms [Average]
  (min, avg, max) = (12.510, 12.554, 12.593), stdev = 0.042
  CI (99.9%): [11.787, 13.322] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.187 ops/ms
# Warmup Iteration   2: 12.823 ops/ms
# Warmup Iteration   3: 13.031 ops/ms
Iteration   1: 13.040 ops/ms
Iteration   2: 13.029 ops/ms
Iteration   3: 12.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.956 ±(99.9%) 2.471 ops/ms [Average]
  (min, avg, max) = (12.800, 12.956, 13.040), stdev = 0.135
  CI (99.9%): [10.485, 15.428] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.992 ops/ms
# Warmup Iteration   2: 12.685 ops/ms
# Warmup Iteration   3: 12.818 ops/ms
Iteration   1: 13.012 ops/ms
Iteration   2: 12.936 ops/ms
Iteration   3: 12.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.960 ±(99.9%) 0.825 ops/ms [Average]
  (min, avg, max) = (12.932, 12.960, 13.012), stdev = 0.045
  CI (99.9%): [12.135, 13.785] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.533 ops/ms
# Warmup Iteration   2: 10.410 ops/ms
# Warmup Iteration   3: 10.619 ops/ms
Iteration   1: 10.647 ops/ms
Iteration   2: 10.642 ops/ms
Iteration   3: 10.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.646 ±(99.9%) 0.058 ops/ms [Average]
  (min, avg, max) = (10.642, 10.646, 10.648), stdev = 0.003
  CI (99.9%): [10.588, 10.703] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.877 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.510 ±(99.9%) 0.004 ms/op
Iteration   2: 2.510 ±(99.9%) 0.003 ms/op
Iteration   3: 2.521 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.514 ±(99.9%) 0.115 ms/op [Average]
  (min, avg, max) = (2.510, 2.514, 2.521), stdev = 0.006
  CI (99.9%): [2.398, 2.629] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.596 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.464 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.003 ms/op
Iteration   1: 2.430 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.453 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.455 ±(99.9%) 0.482 ms/op [Average]
  (min, avg, max) = (2.430, 2.455, 2.483), stdev = 0.026
  CI (99.9%): [1.973, 2.938] (assumes normal distribution)


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.004 ms/op
Iteration   1: 2.454 ±(99.9%) 0.004 ms/op
Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
Iteration   3: 2.427 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.442 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (2.427, 2.442, 2.454), stdev = 0.014
  CI (99.9%): [2.184, 2.700] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.587 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
Iteration   1: 2.980 ±(99.9%) 0.005 ms/op
Iteration   2: 2.955 ±(99.9%) 0.006 ms/op
Iteration   3: 2.936 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.957 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (2.936, 2.957, 2.980), stdev = 0.022
  CI (99.9%): [2.557, 3.358] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.200 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.674 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.720 ms/op
                 createUser·p0.999:  10.978 ms/op
                 createUser·p0.9999: 15.417 ms/op
                 createUser·p1.00:   16.351 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  9.599 ms/op
                 createUser·p0.9999: 12.550 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  8.304 ms/op
                 createUser·p0.9999: 18.350 ms/op
                 createUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384311
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 186674 
    [ 2.500,  3.750) = 193928 
    [ 3.750,  5.000) = 2818 
    [ 5.000,  6.250) = 326 
    [ 6.250,  7.500) = 102 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     15.899 ms/op
     p(99.9990) =     18.416 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 3.583 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.439 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.006 ms/op
Iteration   1: 2.405 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  5.693 ms/op
                 existUser·p0.9999: 13.840 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 2.413 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  5.907 ms/op
                 existUser·p0.9999: 13.087 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  8.880 ms/op
                 existUser·p0.9999: 11.190 ms/op
                 existUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397242
  mean =      2.415 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 199060 
    [ 2.500,  3.750) = 195365 
    [ 3.750,  5.000) = 2194 
    [ 5.000,  6.250) = 147 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.539 ms/op
     p(99.9000) =      8.663 ms/op
     p(99.9900) =     13.292 ms/op
     p(99.9990) =     14.696 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.502 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.969 ms/op
                 getUser·p0.999:  10.899 ms/op
                 getUser·p0.9999: 16.584 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.613 ms/op
                 getUser·p0.999:  5.831 ms/op
                 getUser·p0.9999: 11.665 ms/op
                 getUser·p1.00:   11.846 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.161 ms/op
                 getUser·p0.999:  8.225 ms/op
                 getUser·p0.9999: 12.869 ms/op
                 getUser·p1.00:   14.254 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385004
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 191807 
    [ 2.500,  3.750) = 188296 
    [ 3.750,  5.000) = 3786 
    [ 5.000,  6.250) = 542 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      8.224 ms/op
     p(99.9900) =     15.213 ms/op
     p(99.9990) =     17.536 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 4.581 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.008 ms/op
Iteration   1: 2.949 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.744 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  8.742 ms/op
                 listUser·p0.9999: 11.996 ms/op
                 listUser·p1.00:   12.976 ms/op

Iteration   2: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.772 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.554 ms/op
                 listUser·p0.9999: 10.977 ms/op
                 listUser·p1.00:   11.534 ms/op

Iteration   3: 2.944 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.546 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 10.717 ms/op
                 listUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324897
  mean =      2.952 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 103611 
    [ 2.500,  3.750) = 186046 
    [ 3.750,  5.000) = 28554 
    [ 5.000,  6.250) = 5258 
    [ 6.250,  7.500) = 639 
    [ 7.500,  8.750) = 219 
    [ 8.750, 10.000) = 222 
    [10.000, 11.250) = 165 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.275 ms/op
     p(99.9900) =     11.346 ms/op
     p(99.9990) =     12.341 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.554 ± 0.767  ops/ms
ClientPb.existUser                       thrpt       3  12.956 ± 2.471  ops/ms
ClientPb.getUser                         thrpt       3  12.960 ± 0.825  ops/ms
ClientPb.listUser                        thrpt       3  10.646 ± 0.058  ops/ms
ClientPb.createUser                       avgt       3   2.514 ± 0.115   ms/op
ClientPb.existUser                        avgt       3   2.455 ± 0.482   ms/op
ClientPb.getUser                          avgt       3   2.442 ± 0.258   ms/op
ClientPb.listUser                         avgt       3   2.957 ± 0.401   ms/op
ClientPb.createUser                     sample  384311   2.495 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.801           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.880           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.899           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.481           ms/op
ClientPb.existUser                      sample  397242   2.415 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.921           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.929           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.663           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.292           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.713           ms/op
ClientPb.getUser                        sample  385004   2.491 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.838           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.224           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.213           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.596           ms/op
ClientPb.listUser                       sample  324897   2.952 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.546           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.801           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.275           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.346           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.976           ms/op
