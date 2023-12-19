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
# Warmup Iteration   1: 4.997 ops/ms
# Warmup Iteration   2: 12.078 ops/ms
# Warmup Iteration   3: 12.383 ops/ms
Iteration   1: 12.601 ops/ms
Iteration   2: 12.566 ops/ms
Iteration   3: 12.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.614 ±(99.9%) 1.013 ops/ms [Average]
  (min, avg, max) = (12.566, 12.614, 12.675), stdev = 0.056
  CI (99.9%): [11.601, 13.626] (assumes normal distribution)


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
# Warmup Iteration   1: 8.103 ops/ms
# Warmup Iteration   2: 13.177 ops/ms
# Warmup Iteration   3: 12.938 ops/ms
Iteration   1: 12.879 ops/ms
Iteration   2: 13.035 ops/ms
Iteration   3: 12.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.928 ±(99.9%) 1.689 ops/ms [Average]
  (min, avg, max) = (12.871, 12.928, 13.035), stdev = 0.093
  CI (99.9%): [11.239, 14.618] (assumes normal distribution)


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
# Warmup Iteration   1: 7.815 ops/ms
# Warmup Iteration   2: 12.810 ops/ms
# Warmup Iteration   3: 12.901 ops/ms
Iteration   1: 12.906 ops/ms
Iteration   2: 12.968 ops/ms
Iteration   3: 12.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.873 ±(99.9%) 2.108 ops/ms [Average]
  (min, avg, max) = (12.744, 12.873, 12.968), stdev = 0.116
  CI (99.9%): [10.765, 14.981] (assumes normal distribution)


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
# Warmup Iteration   1: 6.806 ops/ms
# Warmup Iteration   2: 10.572 ops/ms
# Warmup Iteration   3: 10.652 ops/ms
Iteration   1: 10.759 ops/ms
Iteration   2: 10.686 ops/ms
Iteration   3: 10.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.696 ±(99.9%) 1.055 ops/ms [Average]
  (min, avg, max) = (10.644, 10.696, 10.759), stdev = 0.058
  CI (99.9%): [9.641, 11.751] (assumes normal distribution)


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.003 ms/op
Iteration   1: 2.563 ±(99.9%) 0.004 ms/op
Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
Iteration   3: 2.521 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.537 ±(99.9%) 0.415 ms/op [Average]
  (min, avg, max) = (2.521, 2.537, 2.563), stdev = 0.023
  CI (99.9%): [2.122, 2.952] (assumes normal distribution)


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.451 ±(99.9%) 0.004 ms/op
Iteration   3: 2.425 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.446 ±(99.9%) 0.353 ms/op [Average]
  (min, avg, max) = (2.425, 2.446, 2.462), stdev = 0.019
  CI (99.9%): [2.093, 2.799] (assumes normal distribution)


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.004 ms/op
Iteration   1: 2.511 ±(99.9%) 0.003 ms/op
Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.512 ±(99.9%) 0.037 ms/op [Average]
  (min, avg, max) = (2.510, 2.512, 2.514), stdev = 0.002
  CI (99.9%): [2.475, 2.549] (assumes normal distribution)


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
# Warmup Iteration   1: 4.885 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.005 ms/op
Iteration   1: 2.997 ±(99.9%) 0.007 ms/op
Iteration   2: 2.975 ±(99.9%) 0.008 ms/op
Iteration   3: 3.003 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.992 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (2.975, 2.992, 3.003), stdev = 0.015
  CI (99.9%): [2.724, 3.259] (assumes normal distribution)


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.741 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.568 ±(99.9%) 0.006 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.373 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  11.749 ms/op
                 createUser·p0.9999: 14.778 ms/op
                 createUser·p1.00:   15.663 ms/op

Iteration   2: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.657 ms/op
                 createUser·p0.999:  9.845 ms/op
                 createUser·p0.9999: 12.399 ms/op
                 createUser·p1.00:   12.812 ms/op

Iteration   3: 2.561 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  8.690 ms/op
                 createUser·p0.9999: 11.141 ms/op
                 createUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378374
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 181040 
    [ 2.500,  3.750) = 193135 
    [ 3.750,  5.000) = 3213 
    [ 5.000,  6.250) = 424 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.373 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     13.472 ms/op
     p(99.9990) =     15.335 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


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
# Warmup Iteration   1: 3.800 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.365 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  6.347 ms/op
                 existUser·p0.9999: 13.920 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.941 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.412 ms/op
                 existUser·p0.999:  7.814 ms/op
                 existUser·p0.9999: 13.859 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  5.218 ms/op
                 existUser·p0.9999: 11.862 ms/op
                 existUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392483
  mean =      2.444 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 195333 
    [ 2.500,  3.750) = 194743 
    [ 3.750,  5.000) = 1761 
    [ 5.000,  6.250) = 207 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 142 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.365 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.461 ms/op
     p(99.9000) =      6.198 ms/op
     p(99.9900) =     13.660 ms/op
     p(99.9990) =     14.394 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 4.030 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.645 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.516 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  11.480 ms/op
                 getUser·p0.9999: 14.722 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   2: 2.540 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.378 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  9.178 ms/op
                 getUser·p0.9999: 13.723 ms/op
                 getUser·p1.00:   15.450 ms/op

Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.973 ms/op
                 getUser·p0.999:  8.167 ms/op
                 getUser·p0.9999: 10.433 ms/op
                 getUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378950
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 186491 
    [ 2.500,  3.750) = 187771 
    [ 3.750,  5.000) = 3631 
    [ 5.000,  6.250) = 531 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.378 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.258 ms/op
     p(99.9900) =     13.667 ms/op
     p(99.9990) =     14.975 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


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
# Warmup Iteration   1: 4.780 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.008 ms/op
Iteration   1: 2.949 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.470 ms/op
                 listUser·p0.999:  8.709 ms/op
                 listUser·p0.9999: 11.397 ms/op
                 listUser·p1.00:   12.583 ms/op

Iteration   2: 2.954 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.675 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.188 ms/op
                 listUser·p0.9999: 11.035 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   3: 2.943 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.796 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.781 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.722 ms/op
                 listUser·p0.9999: 10.881 ms/op
                 listUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 325262
  mean =      2.949 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 179 
    [ 1.250,  2.500) = 102594 
    [ 2.500,  3.750) = 187023 
    [ 3.750,  5.000) = 29190 
    [ 5.000,  6.250) = 5076 
    [ 6.250,  7.500) = 577 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 273 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     11.001 ms/op
     p(99.9990) =     12.152 ms/op
     p(99.9999) =     12.583 ms/op
    p(100.0000) =     12.583 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.614 ± 1.013  ops/ms
ClientPb.existUser                       thrpt       3  12.928 ± 1.689  ops/ms
ClientPb.getUser                         thrpt       3  12.873 ± 2.108  ops/ms
ClientPb.listUser                        thrpt       3  10.696 ± 1.055  ops/ms
ClientPb.createUser                       avgt       3   2.537 ± 0.415   ms/op
ClientPb.existUser                        avgt       3   2.446 ± 0.353   ms/op
ClientPb.getUser                          avgt       3   2.512 ± 0.037   ms/op
ClientPb.listUser                         avgt       3   2.992 ± 0.267   ms/op
ClientPb.createUser                     sample  378374   2.535 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.373           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.733           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.472           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.663           ms/op
ClientPb.existUser                      sample  392483   2.444 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.365           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.461           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.198           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.660           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.828           ms/op
ClientPb.getUser                        sample  378950   2.531 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.378           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.258           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.667           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.450           ms/op
ClientPb.listUser                       sample  325262   2.949 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.675           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.888           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.809           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.110           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.001           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.583           ms/op
