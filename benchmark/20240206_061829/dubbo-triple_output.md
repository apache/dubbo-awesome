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
# Warmup Iteration   1: 5.223 ops/ms
# Warmup Iteration   2: 12.317 ops/ms
# Warmup Iteration   3: 12.742 ops/ms
Iteration   1: 12.777 ops/ms
Iteration   2: 12.895 ops/ms
Iteration   3: 12.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.826 ±(99.9%) 1.129 ops/ms [Average]
  (min, avg, max) = (12.777, 12.826, 12.895), stdev = 0.062
  CI (99.9%): [11.697, 13.955] (assumes normal distribution)


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
# Warmup Iteration   1: 8.598 ops/ms
# Warmup Iteration   2: 13.244 ops/ms
# Warmup Iteration   3: 13.271 ops/ms
Iteration   1: 13.231 ops/ms
Iteration   2: 13.262 ops/ms
Iteration   3: 13.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.229 ±(99.9%) 0.615 ops/ms [Average]
  (min, avg, max) = (13.195, 13.229, 13.262), stdev = 0.034
  CI (99.9%): [12.614, 13.844] (assumes normal distribution)


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
# Warmup Iteration   1: 8.367 ops/ms
# Warmup Iteration   2: 12.518 ops/ms
# Warmup Iteration   3: 12.736 ops/ms
Iteration   1: 12.981 ops/ms
Iteration   2: 12.883 ops/ms
Iteration   3: 12.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.880 ±(99.9%) 1.873 ops/ms [Average]
  (min, avg, max) = (12.776, 12.880, 12.981), stdev = 0.103
  CI (99.9%): [11.007, 14.753] (assumes normal distribution)


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
# Warmup Iteration   1: 6.749 ops/ms
# Warmup Iteration   2: 10.542 ops/ms
# Warmup Iteration   3: 10.686 ops/ms
Iteration   1: 10.682 ops/ms
Iteration   2: 10.697 ops/ms
Iteration   3: 10.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.700 ±(99.9%) 0.365 ops/ms [Average]
  (min, avg, max) = (10.682, 10.700, 10.721), stdev = 0.020
  CI (99.9%): [10.335, 11.066] (assumes normal distribution)


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.004 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.507 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (2.495, 2.507, 2.513), stdev = 0.010
  CI (99.9%): [2.320, 2.694] (assumes normal distribution)


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
# Warmup Iteration   1: 3.622 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.004 ms/op
Iteration   1: 2.461 ±(99.9%) 0.003 ms/op
Iteration   2: 2.442 ±(99.9%) 0.003 ms/op
Iteration   3: 2.449 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.169 ms/op [Average]
  (min, avg, max) = (2.442, 2.450, 2.461), stdev = 0.009
  CI (99.9%): [2.282, 2.619] (assumes normal distribution)


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
# Warmup Iteration   1: 3.711 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.482 ±(99.9%) 0.004 ms/op
Iteration   2: 2.477 ±(99.9%) 0.003 ms/op
Iteration   3: 2.499 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.486 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (2.477, 2.486, 2.499), stdev = 0.012
  CI (99.9%): [2.272, 2.700] (assumes normal distribution)


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
# Warmup Iteration   1: 4.640 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.005 ms/op
Iteration   1: 2.935 ±(99.9%) 0.006 ms/op
Iteration   2: 2.955 ±(99.9%) 0.005 ms/op
Iteration   3: 2.939 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.943 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.935, 2.943, 2.955), stdev = 0.010
  CI (99.9%): [2.752, 3.134] (assumes normal distribution)


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
# Warmup Iteration   1: 4.302 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.645 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
Iteration   1: 2.559 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.848 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.763 ms/op
                 createUser·p0.999:  11.851 ms/op
                 createUser·p0.9999: 15.213 ms/op
                 createUser·p1.00:   15.827 ms/op

Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  9.309 ms/op
                 createUser·p0.9999: 13.753 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.478 ms/op
                 createUser·p0.999:  8.380 ms/op
                 createUser·p0.9999: 10.555 ms/op
                 createUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378457
  mean =      2.534 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 181261 
    [ 2.500,  3.750) = 193817 
    [ 3.750,  5.000) = 2552 
    [ 5.000,  6.250) = 300 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     14.051 ms/op
     p(99.9990) =     15.565 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 3.815 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  11.652 ms/op
                 existUser·p0.9999: 13.763 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.406 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  6.202 ms/op
                 existUser·p0.9999: 15.614 ms/op
                 existUser·p1.00:   16.237 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.605 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 13.713 ms/op
                 existUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387577
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 189451 
    [ 2.500,  3.750) = 195304 
    [ 3.750,  5.000) = 1915 
    [ 5.000,  6.250) = 333 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 135 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.406 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.527 ms/op
     p(99.9000) =      9.264 ms/op
     p(99.9900) =     14.373 ms/op
     p(99.9990) =     15.811 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.534 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  11.466 ms/op
                 getUser·p0.9999: 17.531 ms/op
                 getUser·p1.00:   17.859 ms/op

Iteration   2: 2.543 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  10.179 ms/op
                 getUser·p0.9999: 14.881 ms/op
                 getUser·p1.00:   15.745 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.600 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  7.989 ms/op
                 getUser·p0.9999: 11.403 ms/op
                 getUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378349
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 185067 
    [ 2.500,  3.750) = 188378 
    [ 3.750,  5.000) = 3656 
    [ 5.000,  6.250) = 809 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      8.304 ms/op
     p(99.9900) =     15.669 ms/op
     p(99.9990) =     17.793 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 4.717 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.009 ms/op
Iteration   1: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.214 ms/op
                 listUser·p0.9999: 11.133 ms/op
                 listUser·p1.00:   11.698 ms/op

Iteration   2: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.778 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.561 ms/op
                 listUser·p0.999:  8.701 ms/op
                 listUser·p0.9999: 13.553 ms/op
                 listUser·p1.00:   14.238 ms/op

Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.945 ms/op
                 listUser·p0.9999: 11.338 ms/op
                 listUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322608
  mean =      2.973 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 104101 
    [ 2.500,  3.750) = 179333 
    [ 3.750,  5.000) = 31465 
    [ 5.000,  6.250) = 6051 
    [ 6.250,  7.500) = 814 
    [ 7.500,  8.750) = 280 
    [ 8.750, 10.000) = 220 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     12.344 ms/op
     p(99.9990) =     14.053 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.826 ± 1.129  ops/ms
ClientPb.existUser                       thrpt       3  13.229 ± 0.615  ops/ms
ClientPb.getUser                         thrpt       3  12.880 ± 1.873  ops/ms
ClientPb.listUser                        thrpt       3  10.700 ± 0.365  ops/ms
ClientPb.createUser                       avgt       3   2.507 ± 0.187   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.169   ms/op
ClientPb.getUser                          avgt       3   2.486 ± 0.214   ms/op
ClientPb.listUser                         avgt       3   2.943 ± 0.191   ms/op
ClientPb.createUser                     sample  378457   2.534 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.848           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.503           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.051           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.827           ms/op
ClientPb.existUser                      sample  387577   2.475 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.406           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.264           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.373           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.237           ms/op
ClientPb.getUser                        sample  378349   2.535 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.600           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.304           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.669           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.859           ms/op
ClientPb.listUser                       sample  322608   2.973 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.778           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.344           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.238           ms/op
