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
# Warmup Iteration   1: 4.791 ops/ms
# Warmup Iteration   2: 12.307 ops/ms
# Warmup Iteration   3: 12.123 ops/ms
Iteration   1: 12.368 ops/ms
Iteration   2: 12.458 ops/ms
Iteration   3: 12.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.463 ±(99.9%) 1.762 ops/ms [Average]
  (min, avg, max) = (12.368, 12.463, 12.561), stdev = 0.097
  CI (99.9%): [10.700, 14.225] (assumes normal distribution)


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
# Warmup Iteration   1: 8.163 ops/ms
# Warmup Iteration   2: 12.961 ops/ms
# Warmup Iteration   3: 12.846 ops/ms
Iteration   1: 12.953 ops/ms
Iteration   2: 12.953 ops/ms
Iteration   3: 13.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.977 ±(99.9%) 0.749 ops/ms [Average]
  (min, avg, max) = (12.953, 12.977, 13.024), stdev = 0.041
  CI (99.9%): [12.228, 13.725] (assumes normal distribution)


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
# Warmup Iteration   1: 7.414 ops/ms
# Warmup Iteration   2: 12.428 ops/ms
# Warmup Iteration   3: 12.370 ops/ms
Iteration   1: 12.673 ops/ms
Iteration   2: 12.811 ops/ms
Iteration   3: 12.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.695 ±(99.9%) 1.951 ops/ms [Average]
  (min, avg, max) = (12.600, 12.695, 12.811), stdev = 0.107
  CI (99.9%): [10.744, 14.645] (assumes normal distribution)


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
# Warmup Iteration   1: 6.748 ops/ms
# Warmup Iteration   2: 10.621 ops/ms
# Warmup Iteration   3: 10.765 ops/ms
Iteration   1: 10.751 ops/ms
Iteration   2: 10.831 ops/ms
Iteration   3: 10.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.749 ±(99.9%) 1.517 ops/ms [Average]
  (min, avg, max) = (10.665, 10.749, 10.831), stdev = 0.083
  CI (99.9%): [9.231, 12.266] (assumes normal distribution)


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.004 ms/op
Iteration   1: 2.513 ±(99.9%) 0.004 ms/op
Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
Iteration   3: 2.478 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.507 ±(99.9%) 0.483 ms/op [Average]
  (min, avg, max) = (2.478, 2.507, 2.529), stdev = 0.026
  CI (99.9%): [2.024, 2.990] (assumes normal distribution)


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
# Warmup Iteration   1: 3.709 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.429 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.003 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
Iteration   2: 2.449 ±(99.9%) 0.004 ms/op
Iteration   3: 2.422 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.436 ±(99.9%) 0.248 ms/op [Average]
  (min, avg, max) = (2.422, 2.436, 2.449), stdev = 0.014
  CI (99.9%): [2.188, 2.684] (assumes normal distribution)


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
# Warmup Iteration   1: 3.881 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.457 ±(99.9%) 0.003 ms/op
Iteration   2: 2.449 ±(99.9%) 0.004 ms/op
Iteration   3: 2.469 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.458 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (2.449, 2.458, 2.469), stdev = 0.010
  CI (99.9%): [2.276, 2.641] (assumes normal distribution)


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
# Warmup Iteration   1: 4.483 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.007 ms/op
Iteration   1: 2.995 ±(99.9%) 0.006 ms/op
Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
Iteration   3: 2.983 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.994 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (2.983, 2.994, 3.004), stdev = 0.010
  CI (99.9%): [2.805, 3.184] (assumes normal distribution)


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
# Warmup Iteration   1: 4.296 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.728 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.006 ms/op
Iteration   1: 2.536 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.436 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  11.123 ms/op
                 createUser·p0.9999: 13.694 ms/op
                 createUser·p1.00:   14.451 ms/op

Iteration   2: 2.560 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   4.030 ms/op
                 createUser·p0.999:  9.568 ms/op
                 createUser·p0.9999: 12.583 ms/op
                 createUser·p1.00:   13.320 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.961 ms/op
                 createUser·p0.999:  8.672 ms/op
                 createUser·p0.9999: 11.010 ms/op
                 createUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376420
  mean =      2.548 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 178190 
    [ 2.500,  3.750) = 193060 
    [ 3.750,  5.000) = 3843 
    [ 5.000,  6.250) = 796 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.436 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.953 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     13.223 ms/op
     p(99.9990) =     14.147 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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
# Warmup Iteration   1: 3.844 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.879 ms/op
                 existUser·p0.999:  7.480 ms/op
                 existUser·p0.9999: 13.651 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  7.741 ms/op
                 existUser·p0.9999: 13.092 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.838 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.871 ms/op
                 existUser·p0.999:  8.002 ms/op
                 existUser·p0.9999: 12.126 ms/op
                 existUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388185
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 190902 
    [ 2.500,  3.750) = 193375 
    [ 3.750,  5.000) = 2857 
    [ 5.000,  6.250) = 571 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      7.740 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     14.235 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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
# Warmup Iteration   1: 3.950 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.006 ms/op
Iteration   1: 2.528 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  11.698 ms/op
                 getUser·p0.9999: 13.725 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.613 ms/op
                 getUser·p0.999:  8.236 ms/op
                 getUser·p0.9999: 13.451 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  8.190 ms/op
                 getUser·p0.9999: 10.781 ms/op
                 getUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383319
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 189987 
    [ 2.500,  3.750) = 189677 
    [ 3.750,  5.000) = 2801 
    [ 5.000,  6.250) = 376 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      8.919 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     14.265 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 4.562 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.009 ms/op
Iteration   1: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.757 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 10.419 ms/op
                 listUser·p1.00:   11.010 ms/op

Iteration   2: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.797 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  10.027 ms/op
                 listUser·p0.9999: 11.330 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   3: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 11.152 ms/op
                 listUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322016
  mean =      2.979 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 171 
    [ 1.250,  2.500) = 100794 
    [ 2.500,  3.750) = 182645 
    [ 3.750,  5.000) = 30809 
    [ 5.000,  6.250) = 6269 
    [ 6.250,  7.500) = 574 
    [ 7.500,  8.750) = 230 
    [ 8.750, 10.000) = 315 
    [10.000, 11.250) = 188 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     11.010 ms/op
     p(99.9990) =     11.957 ms/op
     p(99.9999) =     12.173 ms/op
    p(100.0000) =     12.173 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.463 ± 1.762  ops/ms
ClientPb.existUser                       thrpt       3  12.977 ± 0.749  ops/ms
ClientPb.getUser                         thrpt       3  12.695 ± 1.951  ops/ms
ClientPb.listUser                        thrpt       3  10.749 ± 1.517  ops/ms
ClientPb.createUser                       avgt       3   2.507 ± 0.483   ms/op
ClientPb.existUser                        avgt       3   2.436 ± 0.248   ms/op
ClientPb.getUser                          avgt       3   2.458 ± 0.183   ms/op
ClientPb.listUser                         avgt       3   2.994 ± 0.189   ms/op
ClientPb.createUser                     sample  376420   2.548 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.436           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.864           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.223           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.451           ms/op
ClientPb.existUser                      sample  388185   2.471 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.838           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.740           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.304           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.483           ms/op
ClientPb.getUser                        sample  383319   2.502 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.924           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.919           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.566           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.385           ms/op
ClientPb.listUser                       sample  322016   2.979 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.757           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.404           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.010           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.173           ms/op
