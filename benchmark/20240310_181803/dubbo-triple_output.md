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
# Warmup Iteration   1: 5.466 ops/ms
# Warmup Iteration   2: 12.533 ops/ms
# Warmup Iteration   3: 12.831 ops/ms
Iteration   1: 12.925 ops/ms
Iteration   2: 12.860 ops/ms
Iteration   3: 12.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.881 ±(99.9%) 0.704 ops/ms [Average]
  (min, avg, max) = (12.857, 12.881, 12.925), stdev = 0.039
  CI (99.9%): [12.177, 13.585] (assumes normal distribution)


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
# Warmup Iteration   1: 7.877 ops/ms
# Warmup Iteration   2: 13.347 ops/ms
# Warmup Iteration   3: 13.353 ops/ms
Iteration   1: 13.062 ops/ms
Iteration   2: 13.269 ops/ms
Iteration   3: 13.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.153 ±(99.9%) 1.928 ops/ms [Average]
  (min, avg, max) = (13.062, 13.153, 13.269), stdev = 0.106
  CI (99.9%): [11.225, 15.081] (assumes normal distribution)


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
# Warmup Iteration   1: 7.800 ops/ms
# Warmup Iteration   2: 12.485 ops/ms
# Warmup Iteration   3: 12.864 ops/ms
Iteration   1: 12.986 ops/ms
Iteration   2: 12.918 ops/ms
Iteration   3: 12.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.958 ±(99.9%) 0.649 ops/ms [Average]
  (min, avg, max) = (12.918, 12.958, 12.986), stdev = 0.036
  CI (99.9%): [12.309, 13.607] (assumes normal distribution)


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
# Warmup Iteration   1: 6.721 ops/ms
# Warmup Iteration   2: 10.386 ops/ms
# Warmup Iteration   3: 10.596 ops/ms
Iteration   1: 10.658 ops/ms
Iteration   2: 10.660 ops/ms
Iteration   3: 10.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.640 ±(99.9%) 0.590 ops/ms [Average]
  (min, avg, max) = (10.603, 10.640, 10.660), stdev = 0.032
  CI (99.9%): [10.051, 11.230] (assumes normal distribution)


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
# Warmup Iteration   1: 4.175 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.003 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
Iteration   3: 2.529 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.517 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (2.504, 2.517, 2.529), stdev = 0.012
  CI (99.9%): [2.289, 2.744] (assumes normal distribution)


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.415 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.386 ±(99.9%) 0.004 ms/op
Iteration   1: 2.401 ±(99.9%) 0.004 ms/op
Iteration   2: 2.383 ±(99.9%) 0.003 ms/op
Iteration   3: 2.392 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.392 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (2.383, 2.392, 2.401), stdev = 0.009
  CI (99.9%): [2.222, 2.562] (assumes normal distribution)


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
# Warmup Iteration   1: 3.762 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.004 ms/op
Iteration   1: 2.455 ±(99.9%) 0.003 ms/op
Iteration   2: 2.439 ±(99.9%) 0.004 ms/op
Iteration   3: 2.440 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.444 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (2.439, 2.444, 2.455), stdev = 0.009
  CI (99.9%): [2.283, 2.606] (assumes normal distribution)


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
# Warmup Iteration   1: 4.492 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.005 ms/op
Iteration   1: 2.978 ±(99.9%) 0.005 ms/op
Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
Iteration   3: 2.973 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.980 ±(99.9%) 0.132 ms/op [Average]
  (min, avg, max) = (2.973, 2.980, 2.987), stdev = 0.007
  CI (99.9%): [2.847, 3.112] (assumes normal distribution)


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   2.490 ms/op
                 createUser·p0.90:   2.945 ms/op
                 createUser·p0.95:   3.060 ms/op
                 createUser·p0.99:   3.551 ms/op
                 createUser·p0.999:  5.721 ms/op
                 createUser·p0.9999: 13.435 ms/op
                 createUser·p1.00:   13.959 ms/op

Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   2.499 ms/op
                 createUser·p0.90:   2.949 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   3.572 ms/op
                 createUser·p0.999:  7.039 ms/op
                 createUser·p0.9999: 12.293 ms/op
                 createUser·p1.00:   15.221 ms/op

Iteration   3: 2.435 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   2.503 ms/op
                 createUser·p0.90:   2.953 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  8.831 ms/op
                 createUser·p0.9999: 11.534 ms/op
                 createUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 395145
  mean =      2.427 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 198000 
    [ 2.500,  3.750) = 193896 
    [ 3.750,  5.000) = 2427 
    [ 5.000,  6.250) = 241 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 141 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =      8.749 ms/op
     p(99.9900) =     13.197 ms/op
     p(99.9990) =     13.732 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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
# Warmup Iteration   1: 3.673 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.411 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.414 ±(99.9%) 0.005 ms/op
Iteration   1: 2.385 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.413 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  5.995 ms/op
                 existUser·p0.9999: 14.192 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   2: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.822 ms/op
                 existUser·p0.999:  6.860 ms/op
                 existUser·p0.9999: 15.315 ms/op
                 existUser·p1.00:   16.204 ms/op

Iteration   3: 2.400 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  7.707 ms/op
                 existUser·p0.9999: 11.385 ms/op
                 existUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399764
  mean =      2.400 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 208205 
    [ 2.500,  3.750) = 187955 
    [ 3.750,  5.000) = 2770 
    [ 5.000,  6.250) = 293 
    [ 6.250,  7.500) = 90 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.437 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      6.852 ms/op
     p(99.9900) =     14.206 ms/op
     p(99.9990) =     15.401 ms/op
     p(99.9999) =     16.204 ms/op
    p(100.0000) =     16.204 ms/op


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
# Warmup Iteration   1: 3.815 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
Iteration   1: 2.455 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.703 ms/op
                 getUser·p0.999:  5.639 ms/op
                 getUser·p0.9999: 13.762 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  8.490 ms/op
                 getUser·p0.9999: 12.220 ms/op
                 getUser·p1.00:   13.287 ms/op

Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  5.971 ms/op
                 getUser·p0.9999: 11.433 ms/op
                 getUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 391194
  mean =      2.452 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 198164 
    [ 2.500,  3.750) = 188078 
    [ 3.750,  5.000) = 3834 
    [ 5.000,  6.250) = 596 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      7.976 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     14.044 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   2: 3.056 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.009 ms/op
Iteration   1: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  8.569 ms/op
                 listUser·p0.9999: 11.736 ms/op
                 listUser·p1.00:   12.354 ms/op

Iteration   2: 2.969 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.756 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 10.735 ms/op
                 listUser·p1.00:   12.009 ms/op

Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.186 ms/op
                 listUser·p0.9999: 11.068 ms/op
                 listUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322027
  mean =      2.978 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 100257 
    [ 2.500,  3.750) = 183134 
    [ 3.750,  5.000) = 31341 
    [ 5.000,  6.250) = 5771 
    [ 6.250,  7.500) = 710 
    [ 7.500,  8.750) = 257 
    [ 8.750, 10.000) = 232 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     11.465 ms/op
     p(99.9990) =     12.239 ms/op
     p(99.9999) =     12.354 ms/op
    p(100.0000) =     12.354 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.881 ± 0.704  ops/ms
ClientPb.existUser                       thrpt       3  13.153 ± 1.928  ops/ms
ClientPb.getUser                         thrpt       3  12.958 ± 0.649  ops/ms
ClientPb.listUser                        thrpt       3  10.640 ± 0.590  ops/ms
ClientPb.createUser                       avgt       3   2.517 ± 0.228   ms/op
ClientPb.existUser                        avgt       3   2.392 ± 0.170   ms/op
ClientPb.getUser                          avgt       3   2.444 ± 0.162   ms/op
ClientPb.listUser                         avgt       3   2.980 ± 0.132   ms/op
ClientPb.createUser                     sample  395145   2.427 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.659           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.499           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.949           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.621           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.749           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.197           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.221           ms/op
ClientPb.existUser                      sample  399764   2.400 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.653           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.437           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.920           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.852           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.206           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.204           ms/op
ClientPb.getUser                        sample  391194   2.452 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.725           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.976           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.353           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.270           ms/op
ClientPb.listUser                       sample  322027   2.978 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.756           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.175           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.465           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.354           ms/op
