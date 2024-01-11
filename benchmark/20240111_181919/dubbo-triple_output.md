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
# Warmup Iteration   1: 4.952 ops/ms
# Warmup Iteration   2: 12.174 ops/ms
# Warmup Iteration   3: 12.387 ops/ms
Iteration   1: 12.605 ops/ms
Iteration   2: 12.770 ops/ms
Iteration   3: 12.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.679 ±(99.9%) 1.533 ops/ms [Average]
  (min, avg, max) = (12.605, 12.679, 12.770), stdev = 0.084
  CI (99.9%): [11.146, 14.211] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.291 ops/ms
# Warmup Iteration   2: 13.089 ops/ms
# Warmup Iteration   3: 13.063 ops/ms
Iteration   1: 13.217 ops/ms
Iteration   2: 13.157 ops/ms
Iteration   3: 12.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.115 ±(99.9%) 2.338 ops/ms [Average]
  (min, avg, max) = (12.972, 13.115, 13.217), stdev = 0.128
  CI (99.9%): [10.778, 15.453] (assumes normal distribution)


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
# Warmup Iteration   1: 7.559 ops/ms
# Warmup Iteration   2: 12.400 ops/ms
# Warmup Iteration   3: 12.900 ops/ms
Iteration   1: 13.210 ops/ms
Iteration   2: 12.784 ops/ms
Iteration   3: 12.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.892 ±(99.9%) 5.100 ops/ms [Average]
  (min, avg, max) = (12.683, 12.892, 13.210), stdev = 0.280
  CI (99.9%): [7.792, 17.992] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.731 ops/ms
# Warmup Iteration   2: 10.648 ops/ms
# Warmup Iteration   3: 10.916 ops/ms
Iteration   1: 10.707 ops/ms
Iteration   2: 10.771 ops/ms
Iteration   3: 10.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.744 ±(99.9%) 0.602 ops/ms [Average]
  (min, avg, max) = (10.707, 10.744, 10.771), stdev = 0.033
  CI (99.9%): [10.141, 11.346] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.031 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.003 ms/op
Iteration   1: 2.536 ±(99.9%) 0.004 ms/op
Iteration   2: 2.488 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.505 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (2.488, 2.505, 2.536), stdev = 0.027
  CI (99.9%): [2.016, 2.994] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.650 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.428 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
Iteration   1: 2.466 ±(99.9%) 0.004 ms/op
Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
Iteration   3: 2.465 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.458 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (2.441, 2.458, 2.466), stdev = 0.014
  CI (99.9%): [2.199, 2.716] (assumes normal distribution)


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.004 ms/op
Iteration   1: 2.512 ±(99.9%) 0.004 ms/op
Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
Iteration   3: 2.488 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.495 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (2.484, 2.495, 2.512), stdev = 0.015
  CI (99.9%): [2.226, 2.764] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.506 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.994 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.005 ms/op
Iteration   1: 2.960 ±(99.9%) 0.005 ms/op
Iteration   2: 2.968 ±(99.9%) 0.005 ms/op
Iteration   3: 2.952 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.960 ±(99.9%) 0.145 ms/op [Average]
  (min, avg, max) = (2.952, 2.960, 2.968), stdev = 0.008
  CI (99.9%): [2.815, 3.105] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.159 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.637 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.006 ms/op
Iteration   1: 2.504 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  11.580 ms/op
                 createUser·p0.9999: 14.704 ms/op
                 createUser·p1.00:   16.564 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.966 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  8.772 ms/op
                 createUser·p0.9999: 14.213 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  8.946 ms/op
                 createUser·p0.9999: 10.228 ms/op
                 createUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383877
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 187951 
    [ 2.500,  3.750) = 192038 
    [ 3.750,  5.000) = 3005 
    [ 5.000,  6.250) = 343 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 137 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      8.931 ms/op
     p(99.9900) =     14.303 ms/op
     p(99.9990) =     16.499 ms/op
     p(99.9999) =     16.564 ms/op
    p(100.0000) =     16.564 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.720 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  7.425 ms/op
                 existUser·p0.9999: 13.190 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   2: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  5.692 ms/op
                 existUser·p0.9999: 13.634 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   3: 2.406 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  7.983 ms/op
                 existUser·p0.9999: 11.426 ms/op
                 existUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394813
  mean =      2.429 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 199599 
    [ 2.500,  3.750) = 192039 
    [ 3.750,  5.000) = 2328 
    [ 5.000,  6.250) = 368 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =      7.278 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     14.091 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.938 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  7.428 ms/op
                 getUser·p0.9999: 13.925 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   2: 2.490 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  8.145 ms/op
                 getUser·p0.9999: 13.337 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.588 ms/op
                 getUser·p0.999:  5.677 ms/op
                 getUser·p0.9999: 11.239 ms/op
                 getUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389249
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 197287 
    [ 2.500,  3.750) = 186738 
    [ 3.750,  5.000) = 3824 
    [ 5.000,  6.250) = 887 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 122 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      7.299 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     14.414 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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
# Warmup Iteration   1: 4.821 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
Iteration   1: 2.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 11.895 ms/op
                 listUser·p1.00:   15.892 ms/op

Iteration   2: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  10.092 ms/op
                 listUser·p0.9999: 11.246 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   3: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.811 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 10.835 ms/op
                 listUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322063
  mean =      2.978 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 100701 
    [ 2.500,  3.750) = 184268 
    [ 3.750,  5.000) = 29897 
    [ 5.000,  6.250) = 5591 
    [ 6.250,  7.500) = 741 
    [ 7.500,  8.750) = 245 
    [ 8.750, 10.000) = 244 
    [10.000, 11.250) = 201 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     11.616 ms/op
     p(99.9990) =     13.351 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.679 ± 1.533  ops/ms
ClientPb.existUser                       thrpt       3  13.115 ± 2.338  ops/ms
ClientPb.getUser                         thrpt       3  12.892 ± 5.100  ops/ms
ClientPb.listUser                        thrpt       3  10.744 ± 0.602  ops/ms
ClientPb.createUser                       avgt       3   2.505 ± 0.489   ms/op
ClientPb.existUser                        avgt       3   2.458 ± 0.259   ms/op
ClientPb.getUser                          avgt       3   2.495 ± 0.269   ms/op
ClientPb.listUser                         avgt       3   2.960 ± 0.145   ms/op
ClientPb.createUser                     sample  383877   2.499 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.966           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.931           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.303           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.564           ms/op
ClientPb.existUser                      sample  394813   2.429 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.771           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.278           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.107           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.189           ms/op
ClientPb.getUser                        sample  389249   2.464 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.771           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.470           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.299           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.304           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.204           ms/op
ClientPb.listUser                       sample  322063   2.978 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.811           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.616           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.892           ms/op
