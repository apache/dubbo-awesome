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
# Warmup Iteration   1: 4.867 ops/ms
# Warmup Iteration   2: 12.078 ops/ms
# Warmup Iteration   3: 12.312 ops/ms
Iteration   1: 12.549 ops/ms
Iteration   2: 12.580 ops/ms
Iteration   3: 12.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.590 ±(99.9%) 0.859 ops/ms [Average]
  (min, avg, max) = (12.549, 12.590, 12.641), stdev = 0.047
  CI (99.9%): [11.731, 13.449] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.234 ops/ms
# Warmup Iteration   2: 13.212 ops/ms
# Warmup Iteration   3: 13.004 ops/ms
Iteration   1: 13.086 ops/ms
Iteration   2: 13.118 ops/ms
Iteration   3: 13.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.078 ±(99.9%) 0.813 ops/ms [Average]
  (min, avg, max) = (13.030, 13.078, 13.118), stdev = 0.045
  CI (99.9%): [12.265, 13.892] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.847 ops/ms
# Warmup Iteration   2: 12.646 ops/ms
# Warmup Iteration   3: 12.787 ops/ms
Iteration   1: 13.055 ops/ms
Iteration   2: 12.899 ops/ms
Iteration   3: 12.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.889 ±(99.9%) 3.120 ops/ms [Average]
  (min, avg, max) = (12.713, 12.889, 13.055), stdev = 0.171
  CI (99.9%): [9.770, 16.009] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.845 ops/ms
# Warmup Iteration   2: 10.603 ops/ms
# Warmup Iteration   3: 10.765 ops/ms
Iteration   1: 10.789 ops/ms
Iteration   2: 10.539 ops/ms
Iteration   3: 10.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.675 ±(99.9%) 2.306 ops/ms [Average]
  (min, avg, max) = (10.539, 10.675, 10.789), stdev = 0.126
  CI (99.9%): [8.370, 12.981] (assumes normal distribution)


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
# Warmup Iteration   1: 4.140 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.537 ±(99.9%) 0.004 ms/op
Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
Iteration   3: 2.531 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.533 ±(99.9%) 0.063 ms/op [Average]
  (min, avg, max) = (2.531, 2.533, 2.537), stdev = 0.003
  CI (99.9%): [2.470, 2.597] (assumes normal distribution)


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.003 ms/op
Iteration   1: 2.457 ±(99.9%) 0.003 ms/op
Iteration   2: 2.448 ±(99.9%) 0.003 ms/op
Iteration   3: 2.431 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.445 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.431, 2.445, 2.457), stdev = 0.013
  CI (99.9%): [2.209, 2.682] (assumes normal distribution)


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
# Warmup Iteration   1: 3.820 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.004 ms/op
Iteration   1: 2.547 ±(99.9%) 0.003 ms/op
Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.526 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (2.506, 2.526, 2.547), stdev = 0.021
  CI (99.9%): [2.149, 2.903] (assumes normal distribution)


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
# Warmup Iteration   1: 4.724 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
Iteration   1: 2.994 ±(99.9%) 0.005 ms/op
Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
Iteration   3: 2.995 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.992 ±(99.9%) 0.079 ms/op [Average]
  (min, avg, max) = (2.987, 2.992, 2.995), stdev = 0.004
  CI (99.9%): [2.913, 3.071] (assumes normal distribution)


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.647 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.006 ms/op
Iteration   1: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  11.287 ms/op
                 createUser·p0.9999: 13.926 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  9.384 ms/op
                 createUser·p0.9999: 11.911 ms/op
                 createUser·p1.00:   12.534 ms/op

Iteration   3: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  8.356 ms/op
                 createUser·p0.9999: 10.326 ms/op
                 createUser·p1.00:   10.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378091
  mean =      2.537 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 180827 
    [ 2.500,  3.750) = 193621 
    [ 3.750,  5.000) = 2987 
    [ 5.000,  6.250) = 184 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      8.597 ms/op
     p(99.9900) =     12.714 ms/op
     p(99.9990) =     14.105 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
Iteration   1: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  6.178 ms/op
                 existUser·p0.9999: 13.270 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  5.740 ms/op
                 existUser·p0.9999: 12.827 ms/op
                 existUser·p1.00:   13.287 ms/op

Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  6.218 ms/op
                 existUser·p0.9999: 11.715 ms/op
                 existUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392329
  mean =      2.444 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 194414 
    [ 2.500,  3.750) = 195488 
    [ 3.750,  5.000) = 1811 
    [ 5.000,  6.250) = 181 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.478 ms/op
     p(99.9000) =      6.174 ms/op
     p(99.9900) =     13.067 ms/op
     p(99.9990) =     13.396 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


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
# Warmup Iteration   1: 3.863 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.006 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.486 ms/op
                 getUser·p0.999:  5.997 ms/op
                 getUser·p0.9999: 13.894 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.365 ms/op
                 getUser·p0.999:  8.118 ms/op
                 getUser·p0.9999: 10.517 ms/op
                 getUser·p1.00:   11.125 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.924 ms/op
                 getUser·p0.999:  7.791 ms/op
                 getUser·p0.9999: 11.597 ms/op
                 getUser·p1.00:   14.008 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384464
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 190735 
    [ 2.500,  3.750) = 188638 
    [ 3.750,  5.000) = 3823 
    [ 5.000,  6.250) = 780 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 125 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      7.926 ms/op
     p(99.9900) =     13.420 ms/op
     p(99.9990) =     14.011 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 4.763 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.009 ms/op
Iteration   1: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  8.716 ms/op
                 listUser·p0.9999: 10.170 ms/op
                 listUser·p1.00:   10.781 ms/op

Iteration   2: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  10.384 ms/op
                 listUser·p0.9999: 12.911 ms/op
                 listUser·p1.00:   13.664 ms/op

Iteration   3: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.098 ms/op
                 listUser·p0.9999: 11.619 ms/op
                 listUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316579
  mean =      3.029 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 85401 
    [ 2.500,  3.750) = 191545 
    [ 3.750,  5.000) = 32273 
    [ 5.000,  6.250) = 6020 
    [ 6.250,  7.500) = 581 
    [ 7.500,  8.750) = 232 
    [ 8.750, 10.000) = 233 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     11.977 ms/op
     p(99.9990) =     13.236 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.590 ± 0.859  ops/ms
ClientPb.existUser                       thrpt       3  13.078 ± 0.813  ops/ms
ClientPb.getUser                         thrpt       3  12.889 ± 3.120  ops/ms
ClientPb.listUser                        thrpt       3  10.675 ± 2.306  ops/ms
ClientPb.createUser                       avgt       3   2.533 ± 0.063   ms/op
ClientPb.existUser                        avgt       3   2.445 ± 0.237   ms/op
ClientPb.getUser                          avgt       3   2.526 ± 0.377   ms/op
ClientPb.listUser                         avgt       3   2.992 ± 0.079   ms/op
ClientPb.createUser                     sample  378091   2.537 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.948           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.597           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.714           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.615           ms/op
ClientPb.existUser                      sample  392329   2.444 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.909           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.174           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.067           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.533           ms/op
ClientPb.getUser                        sample  384464   2.495 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.900           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.926           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.420           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.746           ms/op
ClientPb.listUser                       sample  316579   3.029 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.891           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.257           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.977           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.664           ms/op
