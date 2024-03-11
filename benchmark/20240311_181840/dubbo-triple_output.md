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
# Warmup Iteration   1: 4.682 ops/ms
# Warmup Iteration   2: 11.948 ops/ms
# Warmup Iteration   3: 12.433 ops/ms
Iteration   1: 12.619 ops/ms
Iteration   2: 12.648 ops/ms
Iteration   3: 12.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.639 ±(99.9%) 0.328 ops/ms [Average]
  (min, avg, max) = (12.619, 12.639, 12.652), stdev = 0.018
  CI (99.9%): [12.312, 12.967] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.115 ops/ms
# Warmup Iteration   2: 13.210 ops/ms
# Warmup Iteration   3: 13.100 ops/ms
Iteration   1: 13.214 ops/ms
Iteration   2: 13.191 ops/ms
Iteration   3: 13.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.174 ±(99.9%) 0.916 ops/ms [Average]
  (min, avg, max) = (13.118, 13.174, 13.214), stdev = 0.050
  CI (99.9%): [12.259, 14.090] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.313 ops/ms
# Warmup Iteration   2: 12.544 ops/ms
# Warmup Iteration   3: 12.663 ops/ms
Iteration   1: 12.696 ops/ms
Iteration   2: 12.744 ops/ms
Iteration   3: 12.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.716 ±(99.9%) 0.462 ops/ms [Average]
  (min, avg, max) = (12.696, 12.716, 12.744), stdev = 0.025
  CI (99.9%): [12.254, 13.178] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.597 ops/ms
# Warmup Iteration   2: 10.387 ops/ms
# Warmup Iteration   3: 10.555 ops/ms
Iteration   1: 10.391 ops/ms
Iteration   2: 10.604 ops/ms
Iteration   3: 10.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.482 ±(99.9%) 2.010 ops/ms [Average]
  (min, avg, max) = (10.391, 10.482, 10.604), stdev = 0.110
  CI (99.9%): [8.472, 12.492] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.330 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.004 ms/op
Iteration   1: 2.552 ±(99.9%) 0.003 ms/op
Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
Iteration   3: 2.518 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.534 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (2.518, 2.534, 2.552), stdev = 0.017
  CI (99.9%): [2.220, 2.848] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.678 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.003 ms/op
Iteration   1: 2.456 ±(99.9%) 0.003 ms/op
Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
Iteration   3: 2.458 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.456 ±(99.9%) 0.041 ms/op [Average]
  (min, avg, max) = (2.454, 2.456, 2.458), stdev = 0.002
  CI (99.9%): [2.415, 2.497] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.953 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.004 ms/op
Iteration   1: 2.472 ±(99.9%) 0.003 ms/op
Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.488 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (2.472, 2.488, 2.511), stdev = 0.020
  CI (99.9%): [2.117, 2.859] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.666 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.005 ms/op
Iteration   1: 3.058 ±(99.9%) 0.004 ms/op
Iteration   2: 3.049 ±(99.9%) 0.005 ms/op
Iteration   3: 3.058 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.055 ±(99.9%) 0.094 ms/op [Average]
  (min, avg, max) = (3.049, 3.055, 3.058), stdev = 0.005
  CI (99.9%): [2.961, 3.149] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.312 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.715 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.006 ms/op
Iteration   1: 2.571 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  11.682 ms/op
                 createUser·p0.9999: 13.706 ms/op
                 createUser·p1.00:   14.107 ms/op

Iteration   2: 2.552 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  9.314 ms/op
                 createUser·p0.9999: 13.221 ms/op
                 createUser·p1.00:   13.877 ms/op

Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  8.200 ms/op
                 createUser·p0.9999: 10.338 ms/op
                 createUser·p1.00:   11.338 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375280
  mean =      2.556 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 179824 
    [ 2.500,  3.750) = 191202 
    [ 3.750,  5.000) = 3359 
    [ 5.000,  6.250) = 395 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     13.393 ms/op
     p(99.9990) =     13.881 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.603 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.424 ±(99.9%) 0.005 ms/op
Iteration   1: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  6.021 ms/op
                 existUser·p0.9999: 13.891 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   2: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  8.088 ms/op
                 existUser·p0.9999: 17.919 ms/op
                 existUser·p1.00:   18.219 ms/op

Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  8.150 ms/op
                 existUser·p0.9999: 11.221 ms/op
                 existUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393315
  mean =      2.438 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 195652 
    [ 2.500,  3.750) = 193775 
    [ 3.750,  5.000) = 2876 
    [ 5.000,  6.250) = 463 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 133 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      8.086 ms/op
     p(99.9900) =     14.008 ms/op
     p(99.9990) =     18.123 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.013 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.559 ms/op
                 getUser·p0.999:  11.469 ms/op
                 getUser·p0.9999: 14.028 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   2: 2.566 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.333 ms/op
                 getUser·p0.999:  9.876 ms/op
                 getUser·p0.9999: 13.543 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.877 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  8.304 ms/op
                 getUser·p0.9999: 12.063 ms/op
                 getUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378249
  mean =      2.536 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 184966 
    [ 2.500,  3.750) = 188203 
    [ 3.750,  5.000) = 3814 
    [ 5.000,  6.250) = 741 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 145 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     14.902 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.710 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.009 ms/op
Iteration   1: 3.074 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 13.300 ms/op
                 listUser·p1.00:   14.107 ms/op

Iteration   2: 3.059 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.536 ms/op
                 listUser·p0.999:  10.256 ms/op
                 listUser·p0.9999: 12.313 ms/op
                 listUser·p1.00:   12.911 ms/op

Iteration   3: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.760 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.444 ms/op
                 listUser·p0.9999: 11.018 ms/op
                 listUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313826
  mean =      3.056 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 82882 
    [ 2.500,  3.750) = 188852 
    [ 3.750,  5.000) = 34662 
    [ 5.000,  6.250) = 6120 
    [ 6.250,  7.500) = 581 
    [ 7.500,  8.750) = 134 
    [ 8.750, 10.000) = 280 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     12.354 ms/op
     p(99.9990) =     13.660 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.639 ± 0.328  ops/ms
ClientPb.existUser                       thrpt       3  13.174 ± 0.916  ops/ms
ClientPb.getUser                         thrpt       3  12.716 ± 0.462  ops/ms
ClientPb.listUser                        thrpt       3  10.482 ± 2.010  ops/ms
ClientPb.createUser                       avgt       3   2.534 ± 0.314   ms/op
ClientPb.existUser                        avgt       3   2.456 ± 0.041   ms/op
ClientPb.getUser                          avgt       3   2.488 ± 0.371   ms/op
ClientPb.listUser                         avgt       3   3.055 ± 0.094   ms/op
ClientPb.createUser                     sample  375280   2.556 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.020           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.471           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.393           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.107           ms/op
ClientPb.existUser                      sample  393315   2.438 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.756           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.086           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.008           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.219           ms/op
ClientPb.getUser                        sample  378249   2.536 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.877           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.962           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.517           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.057           ms/op
ClientPb.listUser                       sample  313826   3.056 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.760           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.552           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.354           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.107           ms/op
