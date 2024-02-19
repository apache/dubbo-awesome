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
# Warmup Iteration   1: 4.892 ops/ms
# Warmup Iteration   2: 11.982 ops/ms
# Warmup Iteration   3: 12.340 ops/ms
Iteration   1: 12.667 ops/ms
Iteration   2: 12.517 ops/ms
Iteration   3: 12.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.571 ±(99.9%) 1.521 ops/ms [Average]
  (min, avg, max) = (12.517, 12.571, 12.667), stdev = 0.083
  CI (99.9%): [11.050, 14.092] (assumes normal distribution)


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
# Warmup Iteration   1: 8.201 ops/ms
# Warmup Iteration   2: 13.101 ops/ms
# Warmup Iteration   3: 13.025 ops/ms
Iteration   1: 13.189 ops/ms
Iteration   2: 13.034 ops/ms
Iteration   3: 13.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.078 ±(99.9%) 1.768 ops/ms [Average]
  (min, avg, max) = (13.010, 13.078, 13.189), stdev = 0.097
  CI (99.9%): [11.310, 14.846] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.923 ops/ms
# Warmup Iteration   2: 12.492 ops/ms
# Warmup Iteration   3: 12.868 ops/ms
Iteration   1: 12.815 ops/ms
Iteration   2: 12.666 ops/ms
Iteration   3: 12.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.778 ±(99.9%) 1.813 ops/ms [Average]
  (min, avg, max) = (12.666, 12.778, 12.854), stdev = 0.099
  CI (99.9%): [10.965, 14.591] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.652 ops/ms
# Warmup Iteration   2: 10.296 ops/ms
# Warmup Iteration   3: 10.588 ops/ms
Iteration   1: 10.582 ops/ms
Iteration   2: 10.597 ops/ms
Iteration   3: 10.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.585 ±(99.9%) 0.192 ops/ms [Average]
  (min, avg, max) = (10.577, 10.585, 10.597), stdev = 0.011
  CI (99.9%): [10.394, 10.777] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.857 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.522 ±(99.9%) 0.005 ms/op
Iteration   2: 2.551 ±(99.9%) 0.004 ms/op
Iteration   3: 2.529 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.534 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (2.522, 2.534, 2.551), stdev = 0.015
  CI (99.9%): [2.260, 2.808] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.727 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.004 ms/op
Iteration   1: 2.466 ±(99.9%) 0.004 ms/op
Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
Iteration   3: 2.449 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.457 ±(99.9%) 0.161 ms/op [Average]
  (min, avg, max) = (2.449, 2.457, 2.466), stdev = 0.009
  CI (99.9%): [2.296, 2.618] (assumes normal distribution)


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.003 ms/op
Iteration   1: 2.469 ±(99.9%) 0.004 ms/op
Iteration   2: 2.469 ±(99.9%) 0.003 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.475 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (2.469, 2.475, 2.486), stdev = 0.010
  CI (99.9%): [2.291, 2.658] (assumes normal distribution)


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
# Warmup Iteration   1: 4.549 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
Iteration   1: 2.970 ±(99.9%) 0.005 ms/op
Iteration   2: 2.970 ±(99.9%) 0.006 ms/op
Iteration   3: 2.955 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.965 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (2.955, 2.965, 2.970), stdev = 0.009
  CI (99.9%): [2.800, 3.130] (assumes normal distribution)


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
# Warmup Iteration   1: 4.096 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.631 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  11.559 ms/op
                 createUser·p0.9999: 13.766 ms/op
                 createUser·p1.00:   14.500 ms/op

Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.736 ms/op
                 createUser·p0.999:  9.809 ms/op
                 createUser·p0.9999: 12.449 ms/op
                 createUser·p1.00:   12.812 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  8.498 ms/op
                 createUser·p0.9999: 11.403 ms/op
                 createUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383668
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 185304 
    [ 2.500,  3.750) = 194580 
    [ 3.750,  5.000) = 3126 
    [ 5.000,  6.250) = 200 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     13.964 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 3.624 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  6.265 ms/op
                 existUser·p0.9999: 15.066 ms/op
                 existUser·p1.00:   15.499 ms/op

Iteration   2: 2.416 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.391 ms/op
                 existUser·p0.999:  6.021 ms/op
                 existUser·p0.9999: 11.272 ms/op
                 existUser·p1.00:   11.928 ms/op

Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  7.878 ms/op
                 existUser·p0.9999: 12.960 ms/op
                 existUser·p1.00:   13.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395229
  mean =      2.426 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 194766 
    [ 2.500,  3.750) = 197576 
    [ 3.750,  5.000) = 2200 
    [ 5.000,  6.250) = 255 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =      6.128 ms/op
     p(99.9900) =     13.246 ms/op
     p(99.9990) =     15.370 ms/op
     p(99.9999) =     15.499 ms/op
    p(100.0000) =     15.499 ms/op


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.006 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  9.309 ms/op
                 getUser·p0.9999: 13.992 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.330 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.776 ms/op
                 getUser·p0.9999: 12.272 ms/op
                 getUser·p1.00:   13.189 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  6.799 ms/op
                 getUser·p0.9999: 10.866 ms/op
                 getUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383304
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 191529 
    [ 2.500,  3.750) = 185549 
    [ 3.750,  5.000) = 4836 
    [ 5.000,  6.250) = 734 
    [ 6.250,  7.500) = 121 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.067 ms/op
     p(99.9000) =      8.140 ms/op
     p(99.9900) =     13.282 ms/op
     p(99.9990) =     14.238 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 4.630 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.009 ms/op
Iteration   1: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.846 ms/op
                 listUser·p0.9999: 11.062 ms/op
                 listUser·p1.00:   12.517 ms/op

Iteration   2: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.577 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.985 ms/op
                 listUser·p0.9999: 12.403 ms/op
                 listUser·p1.00:   13.451 ms/op

Iteration   3: 3.054 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.647 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.622 ms/op
                 listUser·p0.9999: 12.052 ms/op
                 listUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316357
  mean =      3.032 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 87180 
    [ 2.500,  3.750) = 189073 
    [ 3.750,  5.000) = 32752 
    [ 5.000,  6.250) = 5795 
    [ 6.250,  7.500) = 677 
    [ 7.500,  8.750) = 294 
    [ 8.750, 10.000) = 242 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     11.960 ms/op
     p(99.9990) =     12.846 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.571 ± 1.521  ops/ms
ClientPb.existUser                       thrpt       3  13.078 ± 1.768  ops/ms
ClientPb.getUser                         thrpt       3  12.778 ± 1.813  ops/ms
ClientPb.listUser                        thrpt       3  10.585 ± 0.192  ops/ms
ClientPb.createUser                       avgt       3   2.534 ± 0.274   ms/op
ClientPb.existUser                        avgt       3   2.457 ± 0.161   ms/op
ClientPb.getUser                          avgt       3   2.475 ± 0.183   ms/op
ClientPb.listUser                         avgt       3   2.965 ± 0.165   ms/op
ClientPb.createUser                     sample  383668   2.500 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.695           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.569           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.320           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.500           ms/op
ClientPb.existUser                      sample  395229   2.426 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.721           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.128           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.246           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.499           ms/op
ClientPb.getUser                        sample  383304   2.502 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.693           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.067           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.140           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.282           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.990           ms/op
ClientPb.listUser                       sample  316357   3.032 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.577           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.960           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.451           ms/op
