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
# Warmup Iteration   1: 5.235 ops/ms
# Warmup Iteration   2: 12.153 ops/ms
# Warmup Iteration   3: 12.557 ops/ms
Iteration   1: 12.628 ops/ms
Iteration   2: 12.752 ops/ms
Iteration   3: 12.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.759 ±(99.9%) 2.471 ops/ms [Average]
  (min, avg, max) = (12.628, 12.759, 12.898), stdev = 0.135
  CI (99.9%): [10.288, 15.231] (assumes normal distribution)


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
# Warmup Iteration   1: 8.034 ops/ms
# Warmup Iteration   2: 13.083 ops/ms
# Warmup Iteration   3: 13.091 ops/ms
Iteration   1: 13.004 ops/ms
Iteration   2: 13.242 ops/ms
Iteration   3: 13.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.129 ±(99.9%) 2.170 ops/ms [Average]
  (min, avg, max) = (13.004, 13.129, 13.242), stdev = 0.119
  CI (99.9%): [10.958, 15.299] (assumes normal distribution)


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
# Warmup Iteration   1: 7.578 ops/ms
# Warmup Iteration   2: 12.710 ops/ms
# Warmup Iteration   3: 12.940 ops/ms
Iteration   1: 13.116 ops/ms
Iteration   2: 12.976 ops/ms
Iteration   3: 13.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.038 ±(99.9%) 1.302 ops/ms [Average]
  (min, avg, max) = (12.976, 13.038, 13.116), stdev = 0.071
  CI (99.9%): [11.736, 14.340] (assumes normal distribution)


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
# Warmup Iteration   1: 6.942 ops/ms
# Warmup Iteration   2: 10.738 ops/ms
# Warmup Iteration   3: 10.855 ops/ms
Iteration   1: 10.759 ops/ms
Iteration   2: 10.897 ops/ms
Iteration   3: 10.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.833 ±(99.9%) 1.267 ops/ms [Average]
  (min, avg, max) = (10.759, 10.833, 10.897), stdev = 0.069
  CI (99.9%): [9.565, 12.100] (assumes normal distribution)


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.003 ms/op
Iteration   1: 2.485 ±(99.9%) 0.004 ms/op
Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
Iteration   3: 2.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.472 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (2.464, 2.472, 2.485), stdev = 0.011
  CI (99.9%): [2.263, 2.681] (assumes normal distribution)


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
# Warmup Iteration   1: 3.588 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.418 ±(99.9%) 0.003 ms/op
Iteration   1: 2.417 ±(99.9%) 0.005 ms/op
Iteration   2: 2.405 ±(99.9%) 0.004 ms/op
Iteration   3: 2.414 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.412 ±(99.9%) 0.114 ms/op [Average]
  (min, avg, max) = (2.405, 2.412, 2.417), stdev = 0.006
  CI (99.9%): [2.298, 2.526] (assumes normal distribution)


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
# Warmup Iteration   1: 3.743 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.003 ms/op
Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
Iteration   3: 2.457 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.462 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (2.457, 2.462, 2.473), stdev = 0.009
  CI (99.9%): [2.296, 2.629] (assumes normal distribution)


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
# Warmup Iteration   1: 4.500 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.004 ms/op
Iteration   1: 2.977 ±(99.9%) 0.004 ms/op
Iteration   2: 2.955 ±(99.9%) 0.005 ms/op
Iteration   3: 2.958 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.963 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (2.955, 2.963, 2.977), stdev = 0.012
  CI (99.9%): [2.748, 3.179] (assumes normal distribution)


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.630 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  10.604 ms/op
                 createUser·p0.9999: 12.835 ms/op
                 createUser·p1.00:   13.468 ms/op

Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  7.280 ms/op
                 createUser·p0.9999: 12.452 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  7.354 ms/op
                 createUser·p0.9999: 10.503 ms/op
                 createUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 390000
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 191813 
    [ 2.500,  3.750) = 194179 
    [ 3.750,  5.000) = 3028 
    [ 5.000,  6.250) = 437 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 147 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     12.321 ms/op
     p(99.9990) =     13.332 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


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
# Warmup Iteration   1: 3.602 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.440 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
Iteration   1: 2.408 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   2.978 ms/op
                 existUser·p0.99:   3.207 ms/op
                 existUser·p0.999:  5.037 ms/op
                 existUser·p0.9999: 13.655 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   2: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  6.924 ms/op
                 existUser·p0.9999: 12.322 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  8.286 ms/op
                 existUser·p0.9999: 12.501 ms/op
                 existUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394469
  mean =      2.431 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 193892 
    [ 2.500,  3.750) = 196983 
    [ 3.750,  5.000) = 2525 
    [ 5.000,  6.250) = 579 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 153 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      7.525 ms/op
     p(99.9900) =     12.896 ms/op
     p(99.9990) =     14.387 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.628 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  9.402 ms/op
                 getUser·p0.9999: 13.440 ms/op
                 getUser·p1.00:   13.976 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.969 ms/op
                 getUser·p0.999:  8.463 ms/op
                 getUser·p0.9999: 12.454 ms/op
                 getUser·p1.00:   12.878 ms/op

Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.937 ms/op
                 getUser·p0.95:   3.035 ms/op
                 getUser·p0.99:   3.518 ms/op
                 getUser·p0.999:  5.747 ms/op
                 getUser·p0.9999: 11.993 ms/op
                 getUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389170
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 193710 
    [ 2.500,  3.750) = 191279 
    [ 3.750,  5.000) = 3337 
    [ 5.000,  6.250) = 352 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      7.302 ms/op
     p(99.9900) =     12.896 ms/op
     p(99.9990) =     13.844 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


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
# Warmup Iteration   1: 4.663 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.008 ms/op
Iteration   1: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 10.797 ms/op
                 listUser·p1.00:   10.928 ms/op

Iteration   2: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  10.682 ms/op
                 listUser·p0.9999: 13.150 ms/op
                 listUser·p1.00:   13.582 ms/op

Iteration   3: 2.948 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.801 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  8.882 ms/op
                 listUser·p0.9999: 11.165 ms/op
                 listUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324445
  mean =      2.956 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 165 
    [ 1.250,  2.500) = 102152 
    [ 2.500,  3.750) = 186730 
    [ 3.750,  5.000) = 28957 
    [ 5.000,  6.250) = 5305 
    [ 6.250,  7.500) = 493 
    [ 7.500,  8.750) = 198 
    [ 8.750, 10.000) = 254 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     11.993 ms/op
     p(99.9990) =     13.378 ms/op
     p(99.9999) =     13.582 ms/op
    p(100.0000) =     13.582 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.759 ± 2.471  ops/ms
ClientPb.existUser                       thrpt       3  13.129 ± 2.170  ops/ms
ClientPb.getUser                         thrpt       3  13.038 ± 1.302  ops/ms
ClientPb.listUser                        thrpt       3  10.833 ± 1.267  ops/ms
ClientPb.createUser                       avgt       3   2.472 ± 0.209   ms/op
ClientPb.existUser                        avgt       3   2.412 ± 0.114   ms/op
ClientPb.getUser                          avgt       3   2.462 ± 0.166   ms/op
ClientPb.listUser                         avgt       3   2.963 ± 0.215   ms/op
ClientPb.createUser                     sample  390000   2.459 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.895           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.527           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.986           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.716           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.321           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.550           ms/op
ClientPb.existUser                      sample  394469   2.431 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.876           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.525           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.896           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.451           ms/op
ClientPb.getUser                        sample  389170   2.464 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.924           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.302           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.896           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.976           ms/op
ClientPb.listUser                       sample  324445   2.956 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.801           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.809           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.993           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.582           ms/op
