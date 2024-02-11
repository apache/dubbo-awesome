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
# Warmup Iteration   1: 4.792 ops/ms
# Warmup Iteration   2: 11.956 ops/ms
# Warmup Iteration   3: 12.401 ops/ms
Iteration   1: 12.666 ops/ms
Iteration   2: 12.612 ops/ms
Iteration   3: 12.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.613 ±(99.9%) 0.966 ops/ms [Average]
  (min, avg, max) = (12.561, 12.613, 12.666), stdev = 0.053
  CI (99.9%): [11.647, 13.579] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.287 ops/ms
# Warmup Iteration   2: 13.087 ops/ms
# Warmup Iteration   3: 13.066 ops/ms
Iteration   1: 13.008 ops/ms
Iteration   2: 12.853 ops/ms
Iteration   3: 12.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.925 ±(99.9%) 1.420 ops/ms [Average]
  (min, avg, max) = (12.853, 12.925, 13.008), stdev = 0.078
  CI (99.9%): [11.506, 14.345] (assumes normal distribution)


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
# Warmup Iteration   1: 7.730 ops/ms
# Warmup Iteration   2: 12.523 ops/ms
# Warmup Iteration   3: 12.717 ops/ms
Iteration   1: 12.764 ops/ms
Iteration   2: 12.766 ops/ms
Iteration   3: 12.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.769 ±(99.9%) 0.131 ops/ms [Average]
  (min, avg, max) = (12.764, 12.769, 12.777), stdev = 0.007
  CI (99.9%): [12.638, 12.900] (assumes normal distribution)


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
# Warmup Iteration   1: 6.734 ops/ms
# Warmup Iteration   2: 10.236 ops/ms
# Warmup Iteration   3: 10.522 ops/ms
Iteration   1: 10.466 ops/ms
Iteration   2: 10.519 ops/ms
Iteration   3: 10.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.502 ±(99.9%) 0.583 ops/ms [Average]
  (min, avg, max) = (10.466, 10.502, 10.523), stdev = 0.032
  CI (99.9%): [9.919, 11.086] (assumes normal distribution)


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
Iteration   1: 2.552 ±(99.9%) 0.004 ms/op
Iteration   2: 2.560 ±(99.9%) 0.005 ms/op
Iteration   3: 2.542 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.551 ±(99.9%) 0.161 ms/op [Average]
  (min, avg, max) = (2.542, 2.551, 2.560), stdev = 0.009
  CI (99.9%): [2.390, 2.713] (assumes normal distribution)


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
# Warmup Iteration   1: 3.712 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.003 ms/op
Iteration   1: 2.430 ±(99.9%) 0.004 ms/op
Iteration   2: 2.426 ±(99.9%) 0.003 ms/op
Iteration   3: 2.427 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.428 ±(99.9%) 0.039 ms/op [Average]
  (min, avg, max) = (2.426, 2.428, 2.430), stdev = 0.002
  CI (99.9%): [2.389, 2.467] (assumes normal distribution)


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
# Warmup Iteration   1: 3.874 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.003 ms/op
Iteration   1: 2.519 ±(99.9%) 0.004 ms/op
Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
Iteration   3: 2.521 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.511 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (2.492, 2.511, 2.521), stdev = 0.016
  CI (99.9%): [2.219, 2.803] (assumes normal distribution)


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
# Warmup Iteration   1: 4.867 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 3.027 ±(99.9%) 0.005 ms/op
Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
Iteration   3: 3.027 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.025 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (3.022, 3.025, 3.027), stdev = 0.003
  CI (99.9%): [2.969, 3.081] (assumes normal distribution)


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
# Warmup Iteration   1: 4.108 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.661 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.554 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.129 ms/op
                 createUser·p0.999:  11.040 ms/op
                 createUser·p0.9999: 13.115 ms/op
                 createUser·p1.00:   14.107 ms/op

Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  10.522 ms/op
                 createUser·p0.9999: 13.926 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  8.298 ms/op
                 createUser·p0.9999: 10.705 ms/op
                 createUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378360
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 179654 
    [ 2.500,  3.750) = 194119 
    [ 3.750,  5.000) = 3277 
    [ 5.000,  6.250) = 726 
    [ 6.250,  7.500) = 106 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.973 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     14.448 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 3.730 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
Iteration   1: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.416 ms/op
                 existUser·p0.999:  8.046 ms/op
                 existUser·p0.9999: 13.745 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  6.193 ms/op
                 existUser·p0.9999: 12.631 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  7.206 ms/op
                 existUser·p0.9999: 12.763 ms/op
                 existUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392394
  mean =      2.445 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 196837 
    [ 2.500,  3.750) = 192658 
    [ 3.750,  5.000) = 2134 
    [ 5.000,  6.250) = 258 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 122 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =      7.907 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     13.943 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


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
# Warmup Iteration   1: 4.122 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.006 ms/op
Iteration   1: 2.554 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  11.414 ms/op
                 getUser·p0.9999: 13.664 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   2: 2.535 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  9.064 ms/op
                 getUser·p0.9999: 12.927 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  6.007 ms/op
                 getUser·p0.9999: 13.356 ms/op
                 getUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377017
  mean =      2.544 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 185245 
    [ 2.500,  3.750) = 187714 
    [ 3.750,  5.000) = 3235 
    [ 5.000,  6.250) = 391 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 123 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      6.463 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.074 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.666 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.009 ms/op
Iteration   1: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.602 ms/op
                 listUser·p0.999:  8.944 ms/op
                 listUser·p0.9999: 11.144 ms/op
                 listUser·p1.00:   12.501 ms/op

Iteration   2: 2.961 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 11.990 ms/op
                 listUser·p1.00:   12.861 ms/op

Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 10.840 ms/op
                 listUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322067
  mean =      2.978 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 195 
    [ 1.250,  2.500) = 99220 
    [ 2.500,  3.750) = 184747 
    [ 3.750,  5.000) = 30663 
    [ 5.000,  6.250) = 5917 
    [ 6.250,  7.500) = 632 
    [ 7.500,  8.750) = 259 
    [ 8.750, 10.000) = 252 
    [10.000, 11.250) = 150 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.190 ms/op
     p(99.9900) =     11.265 ms/op
     p(99.9990) =     12.497 ms/op
     p(99.9999) =     12.861 ms/op
    p(100.0000) =     12.861 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.613 ± 0.966  ops/ms
ClientPb.existUser                       thrpt       3  12.925 ± 1.420  ops/ms
ClientPb.getUser                         thrpt       3  12.769 ± 0.131  ops/ms
ClientPb.listUser                        thrpt       3  10.502 ± 0.583  ops/ms
ClientPb.createUser                       avgt       3   2.551 ± 0.161   ms/op
ClientPb.existUser                        avgt       3   2.428 ± 0.039   ms/op
ClientPb.getUser                          avgt       3   2.511 ± 0.292   ms/op
ClientPb.listUser                         avgt       3   3.025 ± 0.056   ms/op
ClientPb.createUser                     sample  378360   2.535 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.879           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.973           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.582           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.647           ms/op
ClientPb.existUser                      sample  392394   2.445 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.811           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.907           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.418           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.008           ms/op
ClientPb.getUser                        sample  377017   2.544 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.943           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.463           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.435           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.860           ms/op
ClientPb.listUser                       sample  322067   2.978 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.824           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.190           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.265           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.861           ms/op
