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
# Warmup Iteration   1: 4.210 ops/ms
# Warmup Iteration   2: 12.326 ops/ms
# Warmup Iteration   3: 12.430 ops/ms
Iteration   1: 12.718 ops/ms
Iteration   2: 12.822 ops/ms
Iteration   3: 12.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.789 ±(99.9%) 1.122 ops/ms [Average]
  (min, avg, max) = (12.718, 12.789, 12.826), stdev = 0.061
  CI (99.9%): [11.667, 13.911] (assumes normal distribution)


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
# Warmup Iteration   1: 8.102 ops/ms
# Warmup Iteration   2: 12.904 ops/ms
# Warmup Iteration   3: 12.845 ops/ms
Iteration   1: 12.825 ops/ms
Iteration   2: 13.027 ops/ms
Iteration   3: 12.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.948 ±(99.9%) 1.972 ops/ms [Average]
  (min, avg, max) = (12.825, 12.948, 13.027), stdev = 0.108
  CI (99.9%): [10.976, 14.919] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.960 ops/ms
# Warmup Iteration   2: 12.686 ops/ms
# Warmup Iteration   3: 12.928 ops/ms
Iteration   1: 13.083 ops/ms
Iteration   2: 12.847 ops/ms
Iteration   3: 12.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.938 ±(99.9%) 2.320 ops/ms [Average]
  (min, avg, max) = (12.847, 12.938, 13.083), stdev = 0.127
  CI (99.9%): [10.618, 15.257] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.534 ops/ms
# Warmup Iteration   2: 10.481 ops/ms
# Warmup Iteration   3: 10.586 ops/ms
Iteration   1: 10.635 ops/ms
Iteration   2: 10.644 ops/ms
Iteration   3: 10.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.608 ±(99.9%) 0.987 ops/ms [Average]
  (min, avg, max) = (10.546, 10.608, 10.644), stdev = 0.054
  CI (99.9%): [9.621, 11.595] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.168 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.005 ms/op
Iteration   1: 2.588 ±(99.9%) 0.004 ms/op
Iteration   2: 2.547 ±(99.9%) 0.004 ms/op
Iteration   3: 2.570 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.568 ±(99.9%) 0.378 ms/op [Average]
  (min, avg, max) = (2.547, 2.568, 2.588), stdev = 0.021
  CI (99.9%): [2.190, 2.947] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.754 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.004 ms/op
Iteration   1: 2.429 ±(99.9%) 0.003 ms/op
Iteration   2: 2.429 ±(99.9%) 0.003 ms/op
Iteration   3: 2.429 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.429 ±(99.9%) 0.001 ms/op [Average]
  (min, avg, max) = (2.429, 2.429, 2.429), stdev = 0.001
  CI (99.9%): [2.428, 2.430] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.812 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.004 ms/op
Iteration   1: 2.449 ±(99.9%) 0.003 ms/op
Iteration   2: 2.443 ±(99.9%) 0.004 ms/op
Iteration   3: 2.424 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.439 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.424, 2.439, 2.449), stdev = 0.013
  CI (99.9%): [2.202, 2.676] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.906 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.005 ms/op
Iteration   2: 3.030 ±(99.9%) 0.005 ms/op
Iteration   3: 3.038 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.036 ±(99.9%) 0.085 ms/op [Average]
  (min, avg, max) = (3.030, 3.036, 3.039), stdev = 0.005
  CI (99.9%): [2.951, 3.121] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.200 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.624 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.006 ms/op
Iteration   1: 2.465 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   2.499 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.787 ms/op
                 createUser·p0.999:  12.894 ms/op
                 createUser·p0.9999: 14.386 ms/op
                 createUser·p1.00:   14.942 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  6.880 ms/op
                 createUser·p0.9999: 12.667 ms/op
                 createUser·p1.00:   13.074 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.924 ms/op
                 createUser·p0.999:  8.306 ms/op
                 createUser·p0.9999: 10.190 ms/op
                 createUser·p1.00:   15.122 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386743
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 192143 
    [ 2.500,  3.750) = 190256 
    [ 3.750,  5.000) = 3353 
    [ 5.000,  6.250) = 338 
    [ 6.250,  7.500) = 120 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      8.905 ms/op
     p(99.9900) =     13.866 ms/op
     p(99.9990) =     14.897 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.453 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.397 ±(99.9%) 0.005 ms/op
Iteration   1: 2.385 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.445 ms/op
                 existUser·p0.999:  5.701 ms/op
                 existUser·p0.9999: 13.386 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.418 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  6.833 ms/op
                 existUser·p0.9999: 14.218 ms/op
                 existUser·p1.00:   15.270 ms/op

Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   4.018 ms/op
                 existUser·p0.999:  7.234 ms/op
                 existUser·p0.9999: 12.419 ms/op
                 existUser·p1.00:   14.615 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396937
  mean =      2.416 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 201900 
    [ 2.500,  3.750) = 191556 
    [ 3.750,  5.000) = 2410 
    [ 5.000,  6.250) = 560 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      7.111 ms/op
     p(99.9900) =     13.456 ms/op
     p(99.9990) =     14.926 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


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
# Warmup Iteration   1: 3.987 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.006 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.981 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.621 ms/op
                 getUser·p0.999:  6.885 ms/op
                 getUser·p0.9999: 14.254 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.055 ms/op
                 getUser·p0.999:  8.928 ms/op
                 getUser·p0.9999: 14.588 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.892 ms/op
                 getUser·p0.999:  7.013 ms/op
                 getUser·p0.9999: 11.370 ms/op
                 getUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386808
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 193866 
    [ 2.500,  3.750) = 188124 
    [ 3.750,  5.000) = 3910 
    [ 5.000,  6.250) = 350 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      8.288 ms/op
     p(99.9900) =     14.238 ms/op
     p(99.9990) =     15.160 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 4.958 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.009 ms/op
Iteration   1: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 11.272 ms/op
                 listUser·p1.00:   11.616 ms/op

Iteration   2: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.564 ms/op
                 listUser·p0.9999: 11.633 ms/op
                 listUser·p1.00:   12.829 ms/op

Iteration   3: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.722 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 11.642 ms/op
                 listUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321321
  mean =      2.985 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 184 
    [ 1.250,  2.500) = 96645 
    [ 2.500,  3.750) = 185384 
    [ 3.750,  5.000) = 31512 
    [ 5.000,  6.250) = 6125 
    [ 6.250,  7.500) = 748 
    [ 7.500,  8.750) = 239 
    [ 8.750, 10.000) = 284 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     11.467 ms/op
     p(99.9990) =     12.626 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.789 ± 1.122  ops/ms
ClientPb.existUser                       thrpt       3  12.948 ± 1.972  ops/ms
ClientPb.getUser                         thrpt       3  12.938 ± 2.320  ops/ms
ClientPb.listUser                        thrpt       3  10.608 ± 0.987  ops/ms
ClientPb.createUser                       avgt       3   2.568 ± 0.378   ms/op
ClientPb.existUser                        avgt       3   2.429 ± 0.001   ms/op
ClientPb.getUser                          avgt       3   2.439 ± 0.237   ms/op
ClientPb.listUser                         avgt       3   3.036 ± 0.085   ms/op
ClientPb.createUser                     sample  386743   2.480 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.682           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.511           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.905           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.866           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.122           ms/op
ClientPb.existUser                      sample  396937   2.416 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.939           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.111           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.456           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.270           ms/op
ClientPb.getUser                        sample  386808   2.479 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.887           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.288           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.238           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.401           ms/op
ClientPb.listUser                       sample  321321   2.985 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.722           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.467           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.829           ms/op
