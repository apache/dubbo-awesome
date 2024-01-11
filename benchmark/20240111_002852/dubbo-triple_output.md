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
# Warmup Iteration   1: 4.659 ops/ms
# Warmup Iteration   2: 11.854 ops/ms
# Warmup Iteration   3: 12.170 ops/ms
Iteration   1: 12.439 ops/ms
Iteration   2: 12.458 ops/ms
Iteration   3: 12.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.507 ±(99.9%) 1.843 ops/ms [Average]
  (min, avg, max) = (12.439, 12.507, 12.623), stdev = 0.101
  CI (99.9%): [10.663, 14.350] (assumes normal distribution)


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
# Warmup Iteration   1: 7.893 ops/ms
# Warmup Iteration   2: 12.974 ops/ms
# Warmup Iteration   3: 13.015 ops/ms
Iteration   1: 13.157 ops/ms
Iteration   2: 13.066 ops/ms
Iteration   3: 13.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.119 ±(99.9%) 0.861 ops/ms [Average]
  (min, avg, max) = (13.066, 13.119, 13.157), stdev = 0.047
  CI (99.9%): [12.258, 13.980] (assumes normal distribution)


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
# Warmup Iteration   1: 7.762 ops/ms
# Warmup Iteration   2: 12.453 ops/ms
# Warmup Iteration   3: 12.824 ops/ms
Iteration   1: 12.913 ops/ms
Iteration   2: 12.905 ops/ms
Iteration   3: 12.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.817 ±(99.9%) 2.892 ops/ms [Average]
  (min, avg, max) = (12.634, 12.817, 12.913), stdev = 0.159
  CI (99.9%): [9.925, 15.709] (assumes normal distribution)


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
# Warmup Iteration   1: 6.780 ops/ms
# Warmup Iteration   2: 10.364 ops/ms
# Warmup Iteration   3: 10.496 ops/ms
Iteration   1: 10.615 ops/ms
Iteration   2: 10.548 ops/ms
Iteration   3: 10.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.597 ±(99.9%) 0.767 ops/ms [Average]
  (min, avg, max) = (10.548, 10.597, 10.626), stdev = 0.042
  CI (99.9%): [9.830, 11.364] (assumes normal distribution)


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
# Warmup Iteration   1: 4.117 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.004 ms/op
Iteration   1: 2.536 ±(99.9%) 0.003 ms/op
Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
Iteration   3: 2.505 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.521 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (2.505, 2.521, 2.536), stdev = 0.015
  CI (99.9%): [2.239, 2.803] (assumes normal distribution)


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
# Warmup Iteration   1: 3.772 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.003 ms/op
Iteration   1: 2.447 ±(99.9%) 0.004 ms/op
Iteration   2: 2.434 ±(99.9%) 0.004 ms/op
Iteration   3: 2.435 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.439 ±(99.9%) 0.137 ms/op [Average]
  (min, avg, max) = (2.434, 2.439, 2.447), stdev = 0.008
  CI (99.9%): [2.302, 2.576] (assumes normal distribution)


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
# Warmup Iteration   1: 3.686 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.004 ms/op
Iteration   1: 2.455 ±(99.9%) 0.003 ms/op
Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.468 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.455, 2.468, 2.477), stdev = 0.011
  CI (99.9%): [2.261, 2.675] (assumes normal distribution)


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
# Warmup Iteration   1: 4.579 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
Iteration   1: 2.973 ±(99.9%) 0.004 ms/op
Iteration   2: 2.992 ±(99.9%) 0.004 ms/op
Iteration   3: 2.976 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.980 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (2.973, 2.980, 2.992), stdev = 0.010
  CI (99.9%): [2.797, 3.164] (assumes normal distribution)


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
Iteration   1: 2.530 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.944 ms/op
                 createUser·p0.999:  11.670 ms/op
                 createUser·p0.9999: 14.077 ms/op
                 createUser·p1.00:   14.549 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  9.346 ms/op
                 createUser·p0.9999: 12.094 ms/op
                 createUser·p1.00:   12.550 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.606 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  8.934 ms/op
                 createUser·p0.9999: 11.158 ms/op
                 createUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381200
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 182076 
    [ 2.500,  3.750) = 195023 
    [ 3.750,  5.000) = 3179 
    [ 5.000,  6.250) = 374 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      8.975 ms/op
     p(99.9900) =     13.072 ms/op
     p(99.9990) =     14.467 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 3.576 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  8.151 ms/op
                 existUser·p0.9999: 13.402 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.017 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  8.748 ms/op
                 existUser·p0.9999: 12.700 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  8.437 ms/op
                 existUser·p0.9999: 11.584 ms/op
                 existUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387691
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 191008 
    [ 2.500,  3.750) = 193721 
    [ 3.750,  5.000) = 2221 
    [ 5.000,  6.250) = 270 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 133 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.564 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     13.945 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 3.967 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  11.272 ms/op
                 getUser·p0.9999: 13.996 ms/op
                 getUser·p1.00:   14.975 ms/op

Iteration   2: 2.556 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.310 ms/op
                 getUser·p0.99:   4.819 ms/op
                 getUser·p0.999:  6.431 ms/op
                 getUser·p0.9999: 12.222 ms/op
                 getUser·p1.00:   12.452 ms/op

Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   2.583 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  8.780 ms/op
                 getUser·p0.9999: 10.771 ms/op
                 getUser·p1.00:   11.158 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378427
  mean =      2.534 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 184081 
    [ 2.500,  3.750) = 187974 
    [ 3.750,  5.000) = 4598 
    [ 5.000,  6.250) = 1327 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.431 ms/op
     p(99.9900) =     13.287 ms/op
     p(99.9990) =     14.728 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 4.514 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.008 ms/op
Iteration   1: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.618 ms/op
                 listUser·p0.9999: 9.934 ms/op
                 listUser·p1.00:   10.224 ms/op

Iteration   2: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.590 ms/op
                 listUser·p0.999:  8.928 ms/op
                 listUser·p0.9999: 10.250 ms/op
                 listUser·p1.00:   11.403 ms/op

Iteration   3: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 10.985 ms/op
                 listUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321292
  mean =      2.985 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 158 
    [ 1.250,  2.500) = 99157 
    [ 2.500,  3.750) = 183980 
    [ 3.750,  5.000) = 31232 
    [ 5.000,  6.250) = 5449 
    [ 6.250,  7.500) = 676 
    [ 7.500,  8.750) = 248 
    [ 8.750, 10.000) = 322 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     10.551 ms/op
     p(99.9990) =     11.737 ms/op
     p(99.9999) =     11.878 ms/op
    p(100.0000) =     11.878 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.507 ± 1.843  ops/ms
ClientPb.existUser                       thrpt       3  13.119 ± 0.861  ops/ms
ClientPb.getUser                         thrpt       3  12.817 ± 2.892  ops/ms
ClientPb.listUser                        thrpt       3  10.597 ± 0.767  ops/ms
ClientPb.createUser                       avgt       3   2.521 ± 0.282   ms/op
ClientPb.existUser                        avgt       3   2.439 ± 0.137   ms/op
ClientPb.getUser                          avgt       3   2.468 ± 0.207   ms/op
ClientPb.listUser                         avgt       3   2.980 ± 0.184   ms/op
ClientPb.createUser                     sample  381200   2.516 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.606           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.975           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.072           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.549           ms/op
ClientPb.existUser                      sample  387691   2.474 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.934           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.733           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.107           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.270           ms/op
ClientPb.getUser                        sample  378427   2.534 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.751           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.431           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.287           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.975           ms/op
ClientPb.listUser                       sample  321292   2.985 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.788           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.962           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.551           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.878           ms/op
