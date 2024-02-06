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
# Warmup Iteration   1: 4.878 ops/ms
# Warmup Iteration   2: 11.753 ops/ms
# Warmup Iteration   3: 12.129 ops/ms
Iteration   1: 12.246 ops/ms
Iteration   2: 12.403 ops/ms
Iteration   3: 12.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.344 ±(99.9%) 1.561 ops/ms [Average]
  (min, avg, max) = (12.246, 12.344, 12.403), stdev = 0.086
  CI (99.9%): [10.784, 13.905] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.349 ops/ms
# Warmup Iteration   2: 13.131 ops/ms
# Warmup Iteration   3: 13.145 ops/ms
Iteration   1: 13.190 ops/ms
Iteration   2: 13.195 ops/ms
Iteration   3: 13.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.150 ±(99.9%) 1.350 ops/ms [Average]
  (min, avg, max) = (13.065, 13.150, 13.195), stdev = 0.074
  CI (99.9%): [11.800, 14.500] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.698 ops/ms
# Warmup Iteration   2: 12.321 ops/ms
# Warmup Iteration   3: 12.693 ops/ms
Iteration   1: 12.700 ops/ms
Iteration   2: 12.695 ops/ms
Iteration   3: 12.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.660 ±(99.9%) 1.203 ops/ms [Average]
  (min, avg, max) = (12.583, 12.660, 12.700), stdev = 0.066
  CI (99.9%): [11.456, 13.863] (assumes normal distribution)


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
# Warmup Iteration   1: 6.618 ops/ms
# Warmup Iteration   2: 10.349 ops/ms
# Warmup Iteration   3: 10.483 ops/ms
Iteration   1: 10.471 ops/ms
Iteration   2: 10.503 ops/ms
Iteration   3: 10.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.473 ±(99.9%) 0.534 ops/ms [Average]
  (min, avg, max) = (10.445, 10.473, 10.503), stdev = 0.029
  CI (99.9%): [9.939, 11.007] (assumes normal distribution)


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
# Warmup Iteration   1: 4.132 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.582 ±(99.9%) 0.004 ms/op
Iteration   1: 2.571 ±(99.9%) 0.004 ms/op
Iteration   2: 2.551 ±(99.9%) 0.005 ms/op
Iteration   3: 2.569 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.564 ±(99.9%) 0.204 ms/op [Average]
  (min, avg, max) = (2.551, 2.564, 2.571), stdev = 0.011
  CI (99.9%): [2.360, 2.768] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.815 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.004 ms/op
Iteration   1: 2.441 ±(99.9%) 0.003 ms/op
Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
Iteration   3: 2.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.454 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (2.441, 2.454, 2.466), stdev = 0.013
  CI (99.9%): [2.225, 2.684] (assumes normal distribution)


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.004 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.507 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.503 ±(99.9%) 0.064 ms/op [Average]
  (min, avg, max) = (2.500, 2.503, 2.507), stdev = 0.003
  CI (99.9%): [2.439, 2.567] (assumes normal distribution)


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
# Warmup Iteration   1: 4.642 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.007 ms/op
Iteration   1: 3.042 ±(99.9%) 0.005 ms/op
Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
Iteration   3: 3.043 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.033 ±(99.9%) 0.326 ms/op [Average]
  (min, avg, max) = (3.012, 3.033, 3.043), stdev = 0.018
  CI (99.9%): [2.706, 3.359] (assumes normal distribution)


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
# Warmup Iteration   1: 4.143 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.640 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
Iteration   1: 2.511 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.944 ms/op
                 createUser·p0.999:  10.797 ms/op
                 createUser·p0.9999: 13.882 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.652 ms/op
                 createUser·p0.999:  10.075 ms/op
                 createUser·p0.9999: 17.278 ms/op
                 createUser·p1.00:   17.400 ms/op

Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.961 ms/op
                 createUser·p0.999:  7.683 ms/op
                 createUser·p0.9999: 11.452 ms/op
                 createUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380404
  mean =      2.521 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 181507 
    [ 2.500,  3.750) = 194307 
    [ 3.750,  5.000) = 3482 
    [ 5.000,  6.250) = 561 
    [ 6.250,  7.500) = 115 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      7.735 ms/op
     p(99.9900) =     13.975 ms/op
     p(99.9990) =     17.373 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 3.709 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.006 ms/op
Iteration   1: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  7.938 ms/op
                 existUser·p0.9999: 15.870 ms/op
                 existUser·p1.00:   16.581 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  5.505 ms/op
                 existUser·p0.9999: 13.140 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  7.334 ms/op
                 existUser·p0.9999: 12.976 ms/op
                 existUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392042
  mean =      2.446 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 195407 
    [ 2.500,  3.750) = 193817 
    [ 3.750,  5.000) = 2076 
    [ 5.000,  6.250) = 302 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.568 ms/op
     p(99.9000) =      6.078 ms/op
     p(99.9900) =     15.483 ms/op
     p(99.9990) =     16.294 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


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
# Warmup Iteration   1: 3.807 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  11.012 ms/op
                 getUser·p0.9999: 13.831 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  9.559 ms/op
                 getUser·p0.9999: 13.045 ms/op
                 getUser·p1.00:   13.631 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.693 ms/op
                 getUser·p0.999:  7.442 ms/op
                 getUser·p0.9999: 12.470 ms/op
                 getUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384125
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 190612 
    [ 2.500,  3.750) = 187954 
    [ 3.750,  5.000) = 4083 
    [ 5.000,  6.250) = 812 
    [ 6.250,  7.500) = 169 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 162 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.941 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      4.067 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     13.395 ms/op
     p(99.9990) =     14.453 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 4.683 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.009 ms/op
Iteration   1: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.633 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  8.978 ms/op
                 listUser·p0.9999: 10.903 ms/op
                 listUser·p1.00:   12.141 ms/op

Iteration   2: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.807 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.577 ms/op
                 listUser·p0.9999: 10.945 ms/op
                 listUser·p1.00:   11.403 ms/op

Iteration   3: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.026 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 13.917 ms/op
                 listUser·p1.00:   14.549 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317865
  mean =      3.017 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 90855 
    [ 2.500,  3.750) = 188124 
    [ 3.750,  5.000) = 31987 
    [ 5.000,  6.250) = 5552 
    [ 6.250,  7.500) = 583 
    [ 7.500,  8.750) = 205 
    [ 8.750, 10.000) = 280 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     13.258 ms/op
     p(99.9990) =     14.247 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.344 ± 1.561  ops/ms
ClientPb.existUser                       thrpt       3  13.150 ± 1.350  ops/ms
ClientPb.getUser                         thrpt       3  12.660 ± 1.203  ops/ms
ClientPb.listUser                        thrpt       3  10.473 ± 0.534  ops/ms
ClientPb.createUser                       avgt       3   2.564 ± 0.204   ms/op
ClientPb.existUser                        avgt       3   2.454 ± 0.229   ms/op
ClientPb.getUser                          avgt       3   2.503 ± 0.064   ms/op
ClientPb.listUser                         avgt       3   3.033 ± 0.326   ms/op
ClientPb.createUser                     sample  380404   2.521 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.945           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.735           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.975           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.400           ms/op
ClientPb.existUser                      sample  392042   2.446 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.819           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.078           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.483           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.581           ms/op
ClientPb.getUser                        sample  384125   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.941           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.067           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.175           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.395           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.565           ms/op
ClientPb.listUser                       sample  317865   3.017 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.633           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.258           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.549           ms/op
