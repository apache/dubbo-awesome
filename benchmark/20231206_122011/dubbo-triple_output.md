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
# Warmup Iteration   1: 4.986 ops/ms
# Warmup Iteration   2: 12.137 ops/ms
# Warmup Iteration   3: 12.500 ops/ms
Iteration   1: 12.809 ops/ms
Iteration   2: 12.847 ops/ms
Iteration   3: 12.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.851 ±(99.9%) 0.801 ops/ms [Average]
  (min, avg, max) = (12.809, 12.851, 12.896), stdev = 0.044
  CI (99.9%): [12.050, 13.652] (assumes normal distribution)


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
# Warmup Iteration   1: 8.205 ops/ms
# Warmup Iteration   2: 13.042 ops/ms
# Warmup Iteration   3: 13.114 ops/ms
Iteration   1: 12.885 ops/ms
Iteration   2: 12.865 ops/ms
Iteration   3: 12.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.842 ±(99.9%) 1.060 ops/ms [Average]
  (min, avg, max) = (12.776, 12.842, 12.885), stdev = 0.058
  CI (99.9%): [11.782, 13.902] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.392 ops/ms
# Warmup Iteration   2: 12.508 ops/ms
# Warmup Iteration   3: 12.628 ops/ms
Iteration   1: 12.672 ops/ms
Iteration   2: 12.821 ops/ms
Iteration   3: 12.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.673 ±(99.9%) 2.682 ops/ms [Average]
  (min, avg, max) = (12.527, 12.673, 12.821), stdev = 0.147
  CI (99.9%): [9.991, 15.356] (assumes normal distribution)


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
# Warmup Iteration   1: 6.834 ops/ms
# Warmup Iteration   2: 10.594 ops/ms
# Warmup Iteration   3: 10.614 ops/ms
Iteration   1: 10.725 ops/ms
Iteration   2: 10.754 ops/ms
Iteration   3: 10.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.653 ±(99.9%) 2.733 ops/ms [Average]
  (min, avg, max) = (10.481, 10.653, 10.754), stdev = 0.150
  CI (99.9%): [7.920, 13.387] (assumes normal distribution)


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.004 ms/op
Iteration   1: 2.494 ±(99.9%) 0.004 ms/op
Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.514 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (2.494, 2.514, 2.553), stdev = 0.034
  CI (99.9%): [1.897, 3.130] (assumes normal distribution)


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
# Warmup Iteration   1: 3.578 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.003 ms/op
Iteration   1: 2.444 ±(99.9%) 0.003 ms/op
Iteration   2: 2.450 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (2.444, 2.450, 2.455), stdev = 0.005
  CI (99.9%): [2.350, 2.550] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.986 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
Iteration   1: 2.455 ±(99.9%) 0.004 ms/op
Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.457 ±(99.9%) 0.044 ms/op [Average]
  (min, avg, max) = (2.455, 2.457, 2.460), stdev = 0.002
  CI (99.9%): [2.413, 2.502] (assumes normal distribution)


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
# Warmup Iteration   1: 4.644 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.004 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
Iteration   2: 3.053 ±(99.9%) 0.005 ms/op
Iteration   3: 3.013 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.032 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (3.013, 3.032, 3.053), stdev = 0.020
  CI (99.9%): [2.673, 3.391] (assumes normal distribution)


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
# Warmup Iteration   1: 4.135 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.664 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
Iteration   1: 2.547 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   4.035 ms/op
                 createUser·p0.999:  11.126 ms/op
                 createUser·p0.9999: 13.852 ms/op
                 createUser·p1.00:   14.172 ms/op

Iteration   2: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  9.318 ms/op
                 createUser·p0.9999: 12.392 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.017 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  8.436 ms/op
                 createUser·p0.9999: 10.732 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378107
  mean =      2.536 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 181797 
    [ 2.500,  3.750) = 191499 
    [ 3.750,  5.000) = 3816 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      9.091 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     14.010 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 3.568 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.006 ms/op
Iteration   1: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  7.203 ms/op
                 existUser·p0.9999: 13.891 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  8.226 ms/op
                 existUser·p0.9999: 13.453 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.793 ms/op
                 existUser·p0.999:  7.552 ms/op
                 existUser·p0.9999: 11.339 ms/op
                 existUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390443
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 192239 
    [ 2.500,  3.750) = 194983 
    [ 3.750,  5.000) = 2297 
    [ 5.000,  6.250) = 451 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      7.553 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     13.964 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  11.470 ms/op
                 getUser·p0.9999: 13.966 ms/op
                 getUser·p1.00:   14.647 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.006 ms/op
                 getUser·p0.999:  9.172 ms/op
                 getUser·p0.9999: 14.145 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   3: 2.516 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.539 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  8.666 ms/op
                 getUser·p0.9999: 11.359 ms/op
                 getUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383319
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 189400 
    [ 2.500,  3.750) = 186899 
    [ 3.750,  5.000) = 5608 
    [ 5.000,  6.250) = 796 
    [ 6.250,  7.500) = 133 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      8.662 ms/op
     p(99.9900) =     13.806 ms/op
     p(99.9990) =     14.702 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 4.573 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.009 ms/op
Iteration   1: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.838 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  8.782 ms/op
                 listUser·p0.9999: 10.378 ms/op
                 listUser·p1.00:   10.961 ms/op

Iteration   2: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 13.334 ms/op
                 listUser·p1.00:   14.500 ms/op

Iteration   3: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.333 ms/op
                 listUser·p0.9999: 11.373 ms/op
                 listUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317130
  mean =      3.024 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 91155 
    [ 2.500,  3.750) = 184342 
    [ 3.750,  5.000) = 34194 
    [ 5.000,  6.250) = 6119 
    [ 6.250,  7.500) = 561 
    [ 7.500,  8.750) = 186 
    [ 8.750, 10.000) = 320 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.189 ms/op
     p(99.9900) =     12.363 ms/op
     p(99.9990) =     13.836 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.851 ± 0.801  ops/ms
ClientPb.existUser                       thrpt       3  12.842 ± 1.060  ops/ms
ClientPb.getUser                         thrpt       3  12.673 ± 2.682  ops/ms
ClientPb.listUser                        thrpt       3  10.653 ± 2.733  ops/ms
ClientPb.createUser                       avgt       3   2.514 ± 0.617   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.100   ms/op
ClientPb.getUser                          avgt       3   2.457 ± 0.044   ms/op
ClientPb.listUser                         avgt       3   3.032 ± 0.359   ms/op
ClientPb.createUser                     sample  378107   2.536 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.765           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.091           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.320           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.776           ms/op
ClientPb.existUser                      sample  390443   2.456 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.799           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.553           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.500           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.074           ms/op
ClientPb.getUser                        sample  383319   2.502 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.539           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.662           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.806           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.991           ms/op
ClientPb.listUser                       sample  317130   3.024 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.838           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.189           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.363           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.500           ms/op
