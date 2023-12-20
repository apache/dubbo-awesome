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
# Warmup Iteration   1: 4.916 ops/ms
# Warmup Iteration   2: 12.091 ops/ms
# Warmup Iteration   3: 12.331 ops/ms
Iteration   1: 12.784 ops/ms
Iteration   2: 12.835 ops/ms
Iteration   3: 12.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.816 ±(99.9%) 0.507 ops/ms [Average]
  (min, avg, max) = (12.784, 12.816, 12.835), stdev = 0.028
  CI (99.9%): [12.309, 13.323] (assumes normal distribution)


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
# Warmup Iteration   1: 8.295 ops/ms
# Warmup Iteration   2: 13.089 ops/ms
# Warmup Iteration   3: 13.026 ops/ms
Iteration   1: 13.151 ops/ms
Iteration   2: 13.215 ops/ms
Iteration   3: 13.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.203 ±(99.9%) 0.856 ops/ms [Average]
  (min, avg, max) = (13.151, 13.203, 13.243), stdev = 0.047
  CI (99.9%): [12.348, 14.059] (assumes normal distribution)


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
# Warmup Iteration   1: 7.499 ops/ms
# Warmup Iteration   2: 12.530 ops/ms
# Warmup Iteration   3: 12.597 ops/ms
Iteration   1: 12.933 ops/ms
Iteration   2: 12.739 ops/ms
Iteration   3: 12.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.853 ±(99.9%) 1.842 ops/ms [Average]
  (min, avg, max) = (12.739, 12.853, 12.933), stdev = 0.101
  CI (99.9%): [11.011, 14.694] (assumes normal distribution)


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
# Warmup Iteration   1: 6.909 ops/ms
# Warmup Iteration   2: 10.420 ops/ms
# Warmup Iteration   3: 10.469 ops/ms
Iteration   1: 10.494 ops/ms
Iteration   2: 10.529 ops/ms
Iteration   3: 10.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.561 ±(99.9%) 1.602 ops/ms [Average]
  (min, avg, max) = (10.494, 10.561, 10.661), stdev = 0.088
  CI (99.9%): [8.960, 12.163] (assumes normal distribution)


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
Iteration   3: 2.471 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.494 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (2.471, 2.494, 2.511), stdev = 0.021
  CI (99.9%): [2.111, 2.877] (assumes normal distribution)


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
# Warmup Iteration   1: 3.759 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.004 ms/op
Iteration   1: 2.449 ±(99.9%) 0.004 ms/op
Iteration   2: 2.425 ±(99.9%) 0.004 ms/op
Iteration   3: 2.428 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.434 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (2.425, 2.434, 2.449), stdev = 0.013
  CI (99.9%): [2.193, 2.675] (assumes normal distribution)


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
# Warmup Iteration   1: 3.761 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.004 ms/op
Iteration   1: 2.458 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
Iteration   3: 2.454 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.462 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (2.454, 2.462, 2.475), stdev = 0.011
  CI (99.9%): [2.258, 2.667] (assumes normal distribution)


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
# Warmup Iteration   1: 4.495 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.013 ±(99.9%) 0.007 ms/op
Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
Iteration   3: 3.017 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.017 ±(99.9%) 0.069 ms/op [Average]
  (min, avg, max) = (3.013, 3.017, 3.020), stdev = 0.004
  CI (99.9%): [2.948, 3.086] (assumes normal distribution)


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
# Warmup Iteration   1: 4.073 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.006 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  6.192 ms/op
                 createUser·p0.9999: 13.517 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.604 ms/op
                 createUser·p0.999:  7.192 ms/op
                 createUser·p0.9999: 12.814 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  8.405 ms/op
                 createUser·p0.9999: 11.704 ms/op
                 createUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387227
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 188973 
    [ 2.500,  3.750) = 194675 
    [ 3.750,  5.000) = 2863 
    [ 5.000,  6.250) = 208 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 144 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      8.372 ms/op
     p(99.9900) =     12.796 ms/op
     p(99.9990) =     13.748 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  5.673 ms/op
                 existUser·p0.9999: 14.138 ms/op
                 existUser·p1.00:   15.237 ms/op

Iteration   2: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  5.598 ms/op
                 existUser·p0.9999: 12.773 ms/op
                 existUser·p1.00:   13.353 ms/op

Iteration   3: 2.426 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  8.268 ms/op
                 existUser·p0.9999: 11.878 ms/op
                 existUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393327
  mean =      2.438 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 196874 
    [ 2.500,  3.750) = 193353 
    [ 3.750,  5.000) = 2351 
    [ 5.000,  6.250) = 293 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =      6.136 ms/op
     p(99.9900) =     13.429 ms/op
     p(99.9990) =     15.205 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 3.882 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.497 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  11.879 ms/op
                 getUser·p0.9999: 16.876 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   2: 2.537 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  8.995 ms/op
                 getUser·p0.9999: 16.259 ms/op
                 getUser·p1.00:   16.466 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  7.570 ms/op
                 getUser·p0.9999: 11.878 ms/op
                 getUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382255
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 188873 
    [ 2.500,  3.750) = 187224 
    [ 3.750,  5.000) = 4996 
    [ 5.000,  6.250) = 669 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 59 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =      8.647 ms/op
     p(99.9900) =     16.302 ms/op
     p(99.9990) =     17.674 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 4.729 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.009 ms/op
Iteration   1: 3.040 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.759 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.320 ms/op
                 listUser·p0.9999: 11.165 ms/op
                 listUser·p1.00:   11.715 ms/op

Iteration   2: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.524 ms/op
                 listUser·p0.9999: 11.726 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   3: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 11.755 ms/op
                 listUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316053
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 165 
    [ 1.250,  2.500) = 87165 
    [ 2.500,  3.750) = 187300 
    [ 3.750,  5.000) = 33847 
    [ 5.000,  6.250) = 6380 
    [ 6.250,  7.500) = 536 
    [ 7.500,  8.750) = 172 
    [ 8.750, 10.000) = 266 
    [10.000, 11.250) = 173 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     11.574 ms/op
     p(99.9990) =     12.042 ms/op
     p(99.9999) =     12.059 ms/op
    p(100.0000) =     12.059 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.816 ± 0.507  ops/ms
ClientPb.existUser                       thrpt       3  13.203 ± 0.856  ops/ms
ClientPb.getUser                         thrpt       3  12.853 ± 1.842  ops/ms
ClientPb.listUser                        thrpt       3  10.561 ± 1.602  ops/ms
ClientPb.createUser                       avgt       3   2.494 ± 0.383   ms/op
ClientPb.existUser                        avgt       3   2.434 ± 0.241   ms/op
ClientPb.getUser                          avgt       3   2.462 ± 0.205   ms/op
ClientPb.listUser                         avgt       3   3.017 ± 0.069   ms/op
ClientPb.createUser                     sample  387227   2.477 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.946           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.372           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.796           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.008           ms/op
ClientPb.existUser                      sample  393327   2.438 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.724           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.136           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.429           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.237           ms/op
ClientPb.getUser                        sample  382255   2.509 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.845           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.647           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.302           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.826           ms/op
ClientPb.listUser                       sample  316053   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.759           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.574           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.059           ms/op
