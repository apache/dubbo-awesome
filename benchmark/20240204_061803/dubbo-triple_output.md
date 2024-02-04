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
# Warmup Iteration   1: 4.418 ops/ms
# Warmup Iteration   2: 12.164 ops/ms
# Warmup Iteration   3: 12.190 ops/ms
Iteration   1: 12.711 ops/ms
Iteration   2: 12.755 ops/ms
Iteration   3: 12.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.757 ±(99.9%) 0.863 ops/ms [Average]
  (min, avg, max) = (12.711, 12.757, 12.805), stdev = 0.047
  CI (99.9%): [11.894, 13.620] (assumes normal distribution)


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
# Warmup Iteration   1: 7.929 ops/ms
# Warmup Iteration   2: 13.039 ops/ms
# Warmup Iteration   3: 13.139 ops/ms
Iteration   1: 13.131 ops/ms
Iteration   2: 13.287 ops/ms
Iteration   3: 13.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.191 ±(99.9%) 1.527 ops/ms [Average]
  (min, avg, max) = (13.131, 13.191, 13.287), stdev = 0.084
  CI (99.9%): [11.664, 14.718] (assumes normal distribution)


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
# Warmup Iteration   1: 7.221 ops/ms
# Warmup Iteration   2: 12.661 ops/ms
# Warmup Iteration   3: 12.744 ops/ms
Iteration   1: 12.660 ops/ms
Iteration   2: 13.081 ops/ms
Iteration   3: 13.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.960 ±(99.9%) 4.779 ops/ms [Average]
  (min, avg, max) = (12.660, 12.960, 13.141), stdev = 0.262
  CI (99.9%): [8.182, 17.739] (assumes normal distribution)


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
# Warmup Iteration   1: 6.621 ops/ms
# Warmup Iteration   2: 10.697 ops/ms
# Warmup Iteration   3: 10.743 ops/ms
Iteration   1: 10.884 ops/ms
Iteration   2: 10.770 ops/ms
Iteration   3: 10.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.806 ±(99.9%) 1.240 ops/ms [Average]
  (min, avg, max) = (10.763, 10.806, 10.884), stdev = 0.068
  CI (99.9%): [9.565, 12.046] (assumes normal distribution)


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.004 ms/op
Iteration   1: 2.488 ±(99.9%) 0.004 ms/op
Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.502 ±(99.9%) 0.233 ms/op [Average]
  (min, avg, max) = (2.488, 2.502, 2.513), stdev = 0.013
  CI (99.9%): [2.269, 2.734] (assumes normal distribution)


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
# Warmup Iteration   1: 3.633 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.434 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.402 ±(99.9%) 0.004 ms/op
Iteration   1: 2.394 ±(99.9%) 0.004 ms/op
Iteration   2: 2.420 ±(99.9%) 0.004 ms/op
Iteration   3: 2.419 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.411 ±(99.9%) 0.273 ms/op [Average]
  (min, avg, max) = (2.394, 2.411, 2.420), stdev = 0.015
  CI (99.9%): [2.139, 2.684] (assumes normal distribution)


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
# Warmup Iteration   1: 3.652 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.004 ms/op
Iteration   1: 2.459 ±(99.9%) 0.004 ms/op
Iteration   2: 2.441 ±(99.9%) 0.003 ms/op
Iteration   3: 2.472 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.458 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (2.441, 2.458, 2.472), stdev = 0.016
  CI (99.9%): [2.172, 2.743] (assumes normal distribution)


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
# Warmup Iteration   1: 4.949 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.005 ms/op
Iteration   1: 3.004 ±(99.9%) 0.006 ms/op
Iteration   2: 2.983 ±(99.9%) 0.005 ms/op
Iteration   3: 2.985 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.991 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (2.983, 2.991, 3.004), stdev = 0.012
  CI (99.9%): [2.777, 3.205] (assumes normal distribution)


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
# Warmup Iteration   1: 4.082 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  11.370 ms/op
                 createUser·p0.9999: 13.946 ms/op
                 createUser·p1.00:   14.696 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.584 ms/op
                 createUser·p0.999:  9.090 ms/op
                 createUser·p0.9999: 12.695 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  8.880 ms/op
                 createUser·p0.9999: 11.173 ms/op
                 createUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384383
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 186394 
    [ 2.500,  3.750) = 194466 
    [ 3.750,  5.000) = 2661 
    [ 5.000,  6.250) = 327 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      8.874 ms/op
     p(99.9900) =     13.624 ms/op
     p(99.9990) =     14.664 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 3.637 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.440 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.393 ±(99.9%) 0.005 ms/op
Iteration   1: 2.407 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  6.235 ms/op
                 existUser·p0.9999: 13.227 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  5.177 ms/op
                 existUser·p0.9999: 13.628 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.688 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.916 ms/op
                 existUser·p0.999:  5.856 ms/op
                 existUser·p0.9999: 13.060 ms/op
                 existUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393791
  mean =      2.435 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 196201 
    [ 2.500,  3.750) = 193750 
    [ 3.750,  5.000) = 3011 
    [ 5.000,  6.250) = 422 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      5.693 ms/op
     p(99.9900) =     13.156 ms/op
     p(99.9990) =     13.926 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.006 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  12.029 ms/op
                 getUser·p0.9999: 13.790 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   2: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  11.047 ms/op
                 getUser·p0.9999: 13.961 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  8.390 ms/op
                 getUser·p0.9999: 12.029 ms/op
                 getUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381467
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 188088 
    [ 2.500,  3.750) = 187867 
    [ 3.750,  5.000) = 4212 
    [ 5.000,  6.250) = 734 
    [ 6.250,  7.500) = 93 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 149 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =      8.605 ms/op
     p(99.9900) =     13.629 ms/op
     p(99.9990) =     14.417 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 4.963 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
Iteration   1: 3.043 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.681 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 11.362 ms/op
                 listUser·p1.00:   11.829 ms/op

Iteration   2: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.787 ms/op
                 listUser·p0.9999: 14.025 ms/op
                 listUser·p1.00:   14.352 ms/op

Iteration   3: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  8.988 ms/op
                 listUser·p0.9999: 11.158 ms/op
                 listUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317346
  mean =      3.022 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 149 
    [ 1.250,  2.500) = 90279 
    [ 2.500,  3.750) = 185892 
    [ 3.750,  5.000) = 33496 
    [ 5.000,  6.250) = 6073 
    [ 6.250,  7.500) = 728 
    [ 7.500,  8.750) = 250 
    [ 8.750, 10.000) = 272 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     12.198 ms/op
     p(99.9990) =     14.205 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.757 ± 0.863  ops/ms
ClientPb.existUser                       thrpt       3  13.191 ± 1.527  ops/ms
ClientPb.getUser                         thrpt       3  12.960 ± 4.779  ops/ms
ClientPb.listUser                        thrpt       3  10.806 ± 1.240  ops/ms
ClientPb.createUser                       avgt       3   2.502 ± 0.233   ms/op
ClientPb.existUser                        avgt       3   2.411 ± 0.273   ms/op
ClientPb.getUser                          avgt       3   2.458 ± 0.286   ms/op
ClientPb.listUser                         avgt       3   2.991 ± 0.214   ms/op
ClientPb.createUser                     sample  384383   2.495 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.814           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.874           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.624           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.696           ms/op
ClientPb.existUser                      sample  393791   2.435 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.688           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.693           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.156           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.582           ms/op
ClientPb.getUser                        sample  381467   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.756           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.605           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.629           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.516           ms/op
ClientPb.listUser                       sample  317346   3.022 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.877           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.198           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.352           ms/op
