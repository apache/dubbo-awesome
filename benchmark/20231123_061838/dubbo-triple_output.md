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
# Warmup Iteration   1: 4.735 ops/ms
# Warmup Iteration   2: 12.307 ops/ms
# Warmup Iteration   3: 12.453 ops/ms
Iteration   1: 12.665 ops/ms
Iteration   2: 12.702 ops/ms
Iteration   3: 12.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.718 ±(99.9%) 1.161 ops/ms [Average]
  (min, avg, max) = (12.665, 12.718, 12.789), stdev = 0.064
  CI (99.9%): [11.557, 13.879] (assumes normal distribution)


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
# Warmup Iteration   1: 7.941 ops/ms
# Warmup Iteration   2: 13.103 ops/ms
# Warmup Iteration   3: 13.125 ops/ms
Iteration   1: 13.254 ops/ms
Iteration   2: 13.177 ops/ms
Iteration   3: 13.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.242 ±(99.9%) 1.079 ops/ms [Average]
  (min, avg, max) = (13.177, 13.242, 13.294), stdev = 0.059
  CI (99.9%): [12.162, 14.321] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.860 ops/ms
# Warmup Iteration   2: 12.735 ops/ms
# Warmup Iteration   3: 12.816 ops/ms
Iteration   1: 12.956 ops/ms
Iteration   2: 12.982 ops/ms
Iteration   3: 12.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.941 ±(99.9%) 0.913 ops/ms [Average]
  (min, avg, max) = (12.885, 12.941, 12.982), stdev = 0.050
  CI (99.9%): [12.028, 13.854] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.309 ops/ms
# Warmup Iteration   2: 10.439 ops/ms
# Warmup Iteration   3: 10.405 ops/ms
Iteration   1: 10.433 ops/ms
Iteration   2: 10.585 ops/ms
Iteration   3: 10.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.555 ±(99.9%) 1.994 ops/ms [Average]
  (min, avg, max) = (10.433, 10.555, 10.646), stdev = 0.109
  CI (99.9%): [8.561, 12.548] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.028 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.580 ±(99.9%) 0.005 ms/op
Iteration   1: 2.535 ±(99.9%) 0.004 ms/op
Iteration   2: 2.612 ±(99.9%) 0.005 ms/op
Iteration   3: 2.557 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.568 ±(99.9%) 0.728 ms/op [Average]
  (min, avg, max) = (2.535, 2.568, 2.612), stdev = 0.040
  CI (99.9%): [1.840, 3.296] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.641 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.004 ms/op
Iteration   1: 2.439 ±(99.9%) 0.004 ms/op
Iteration   2: 2.451 ±(99.9%) 0.004 ms/op
Iteration   3: 2.448 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.446 ±(99.9%) 0.106 ms/op [Average]
  (min, avg, max) = (2.439, 2.446, 2.451), stdev = 0.006
  CI (99.9%): [2.340, 2.552] (assumes normal distribution)


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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
Iteration   1: 2.476 ±(99.9%) 0.003 ms/op
Iteration   2: 2.482 ±(99.9%) 0.004 ms/op
Iteration   3: 2.479 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.479 ±(99.9%) 0.062 ms/op [Average]
  (min, avg, max) = (2.476, 2.479, 2.482), stdev = 0.003
  CI (99.9%): [2.417, 2.541] (assumes normal distribution)


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
# Warmup Iteration   1: 4.621 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
Iteration   1: 3.014 ±(99.9%) 0.007 ms/op
Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
Iteration   3: 3.029 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.022 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (3.014, 3.022, 3.029), stdev = 0.008
  CI (99.9%): [2.878, 3.165] (assumes normal distribution)


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
# Warmup Iteration   1: 4.006 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  7.822 ms/op
                 createUser·p0.9999: 13.648 ms/op
                 createUser·p1.00:   15.925 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  7.955 ms/op
                 createUser·p0.9999: 12.091 ms/op
                 createUser·p1.00:   12.354 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  8.771 ms/op
                 createUser·p0.9999: 10.780 ms/op
                 createUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389870
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 191737 
    [ 2.500,  3.750) = 193984 
    [ 3.750,  5.000) = 3137 
    [ 5.000,  6.250) = 469 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      8.456 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.303 ms/op
     p(99.9999) =     15.925 ms/op
    p(100.0000) =     15.925 ms/op


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
# Warmup Iteration   1: 3.685 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.005 ms/op
Iteration   1: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  6.218 ms/op
                 existUser·p0.9999: 13.320 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.956 ms/op
                 existUser·p0.999:  7.627 ms/op
                 existUser·p0.9999: 12.059 ms/op
                 existUser·p1.00:   12.730 ms/op

Iteration   3: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  8.049 ms/op
                 existUser·p0.9999: 11.977 ms/op
                 existUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394620
  mean =      2.431 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 197778 
    [ 2.500,  3.750) = 193066 
    [ 3.750,  5.000) = 2799 
    [ 5.000,  6.250) = 447 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 96 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      7.627 ms/op
     p(99.9900) =     13.050 ms/op
     p(99.9990) =     13.435 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.006 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.645 ms/op
                 getUser·p0.999:  6.683 ms/op
                 getUser·p0.9999: 13.844 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  6.887 ms/op
                 getUser·p0.9999: 11.616 ms/op
                 getUser·p1.00:   12.419 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.117 ms/op
                 getUser·p0.999:  8.119 ms/op
                 getUser·p0.9999: 12.014 ms/op
                 getUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385523
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 191977 
    [ 2.500,  3.750) = 188907 
    [ 3.750,  5.000) = 3571 
    [ 5.000,  6.250) = 606 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      6.831 ms/op
     p(99.9900) =     13.308 ms/op
     p(99.9990) =     14.123 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 4.678 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.008 ms/op
Iteration   1: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 11.594 ms/op
                 listUser·p1.00:   12.452 ms/op

Iteration   2: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.187 ms/op
                 listUser·p0.9999: 11.110 ms/op
                 listUser·p1.00:   12.763 ms/op

Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 11.272 ms/op
                 listUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321125
  mean =      2.987 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 98573 
    [ 2.500,  3.750) = 183897 
    [ 3.750,  5.000) = 30765 
    [ 5.000,  6.250) = 6340 
    [ 6.250,  7.500) = 744 
    [ 7.500,  8.750) = 210 
    [ 8.750, 10.000) = 214 
    [10.000, 11.250) = 183 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     11.289 ms/op
     p(99.9990) =     12.452 ms/op
     p(99.9999) =     12.763 ms/op
    p(100.0000) =     12.763 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.718 ± 1.161  ops/ms
ClientPb.existUser                       thrpt       3  13.242 ± 1.079  ops/ms
ClientPb.getUser                         thrpt       3  12.941 ± 0.913  ops/ms
ClientPb.listUser                        thrpt       3  10.555 ± 1.994  ops/ms
ClientPb.createUser                       avgt       3   2.568 ± 0.728   ms/op
ClientPb.existUser                        avgt       3   2.446 ± 0.106   ms/op
ClientPb.getUser                          avgt       3   2.479 ± 0.062   ms/op
ClientPb.listUser                         avgt       3   3.022 ± 0.144   ms/op
ClientPb.createUser                     sample  389870   2.460 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.855           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.527           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.982           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.456           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.337           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.925           ms/op
ClientPb.existUser                      sample  394620   2.431 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.937           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.627           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.050           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.681           ms/op
ClientPb.getUser                        sample  385523   2.488 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.886           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.831           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.308           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.402           ms/op
ClientPb.listUser                       sample  321125   2.987 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.785           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.289           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.763           ms/op
