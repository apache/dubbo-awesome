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
# Warmup Iteration   1: 4.271 ops/ms
# Warmup Iteration   2: 11.542 ops/ms
# Warmup Iteration   3: 11.833 ops/ms
Iteration   1: 11.953 ops/ms
Iteration   2: 12.083 ops/ms
Iteration   3: 12.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.042 ±(99.9%) 1.422 ops/ms [Average]
  (min, avg, max) = (11.953, 12.042, 12.092), stdev = 0.078
  CI (99.9%): [10.620, 13.465] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 7.576 ops/ms
# Warmup Iteration   2: 12.538 ops/ms
# Warmup Iteration   3: 12.640 ops/ms
Iteration   1: 12.751 ops/ms
Iteration   2: 12.690 ops/ms
Iteration   3: 12.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.679 ±(99.9%) 1.439 ops/ms [Average]
  (min, avg, max) = (12.595, 12.679, 12.751), stdev = 0.079
  CI (99.9%): [11.240, 14.117] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.045 ops/ms
# Warmup Iteration   2: 12.107 ops/ms
# Warmup Iteration   3: 12.111 ops/ms
Iteration   1: 12.300 ops/ms
Iteration   2: 12.421 ops/ms
Iteration   3: 12.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.309 ±(99.9%) 1.954 ops/ms [Average]
  (min, avg, max) = (12.208, 12.309, 12.421), stdev = 0.107
  CI (99.9%): [10.355, 14.264] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.356 ops/ms
# Warmup Iteration   2: 10.281 ops/ms
# Warmup Iteration   3: 10.341 ops/ms
Iteration   1: 10.408 ops/ms
Iteration   2: 10.378 ops/ms
Iteration   3: 10.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.369 ±(99.9%) 0.823 ops/ms [Average]
  (min, avg, max) = (10.319, 10.369, 10.408), stdev = 0.045
  CI (99.9%): [9.546, 11.191] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.077 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.642 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.612 ±(99.9%) 0.004 ms/op
Iteration   1: 2.588 ±(99.9%) 0.004 ms/op
Iteration   2: 2.592 ±(99.9%) 0.003 ms/op
Iteration   3: 2.552 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.577 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (2.552, 2.577, 2.592), stdev = 0.022
  CI (99.9%): [2.170, 2.985] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.019 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.004 ms/op
Iteration   1: 2.565 ±(99.9%) 0.004 ms/op
Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
Iteration   3: 2.530 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.538 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (2.521, 2.538, 2.565), stdev = 0.023
  CI (99.9%): [2.112, 2.965] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.121 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.660 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.579 ±(99.9%) 0.005 ms/op
Iteration   1: 2.599 ±(99.9%) 0.006 ms/op
Iteration   2: 2.569 ±(99.9%) 0.004 ms/op
Iteration   3: 2.581 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.583 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (2.569, 2.583, 2.599), stdev = 0.015
  CI (99.9%): [2.307, 2.859] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.858 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.006 ms/op
Iteration   1: 3.089 ±(99.9%) 0.005 ms/op
Iteration   2: 3.075 ±(99.9%) 0.007 ms/op
Iteration   3: 3.081 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.082 ±(99.9%) 0.125 ms/op [Average]
  (min, avg, max) = (3.075, 3.082, 3.089), stdev = 0.007
  CI (99.9%): [2.957, 3.207] (assumes normal distribution)


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.737 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.618 ±(99.9%) 0.006 ms/op
Iteration   1: 2.601 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  12.845 ms/op
                 createUser·p0.9999: 14.647 ms/op
                 createUser·p1.00:   15.172 ms/op

Iteration   2: 2.603 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  9.604 ms/op
                 createUser·p0.9999: 16.291 ms/op
                 createUser·p1.00:   16.876 ms/op

Iteration   3: 2.629 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.211 ms/op
                 createUser·p0.95:   3.355 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  8.749 ms/op
                 createUser·p0.9999: 12.632 ms/op
                 createUser·p1.00:   13.058 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 367340
  mean =      2.611 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 173963 
    [ 2.500,  3.750) = 187312 
    [ 3.750,  5.000) = 4617 
    [ 5.000,  6.250) = 931 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      2.654 ms/op
     p(90.0000) =      3.174 ms/op
     p(95.0000) =      3.310 ms/op
     p(99.0000) =      4.116 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     14.869 ms/op
     p(99.9990) =     16.662 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.006 ms/op
Iteration   1: 2.553 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.121 ms/op
                 existUser·p0.95:   3.248 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  5.348 ms/op
                 existUser·p0.9999: 17.743 ms/op
                 existUser·p1.00:   18.252 ms/op

Iteration   2: 2.584 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   2.617 ms/op
                 existUser·p0.90:   3.138 ms/op
                 existUser·p0.95:   3.269 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  10.741 ms/op
                 existUser·p0.9999: 15.635 ms/op
                 existUser·p1.00:   16.728 ms/op

Iteration   3: 2.558 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.125 ms/op
                 existUser·p0.95:   3.244 ms/op
                 existUser·p0.99:   3.871 ms/op
                 existUser·p0.999:  6.316 ms/op
                 existUser·p0.9999: 12.616 ms/op
                 existUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 373912
  mean =      2.565 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 180344 
    [ 2.500,  3.750) = 188766 
    [ 3.750,  5.000) = 3841 
    [ 5.000,  6.250) = 463 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      7.555 ms/op
     p(99.9900) =     16.152 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 4.385 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.751 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.596 ±(99.9%) 0.006 ms/op
Iteration   1: 2.555 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.889 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  6.069 ms/op
                 getUser·p0.9999: 14.402 ms/op
                 getUser·p1.00:   15.843 ms/op

Iteration   2: 2.610 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.178 ms/op
                 getUser·p0.95:   3.355 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  10.356 ms/op
                 getUser·p0.9999: 15.381 ms/op
                 getUser·p1.00:   16.318 ms/op

Iteration   3: 2.591 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   2.634 ms/op
                 getUser·p0.90:   3.154 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  9.191 ms/op
                 getUser·p0.9999: 12.987 ms/op
                 getUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 371022
  mean =      2.585 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 177314 
    [ 2.500,  3.750) = 187686 
    [ 3.750,  5.000) = 4829 
    [ 5.000,  6.250) = 665 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.293 ms/op
     p(99.0000) =      4.026 ms/op
     p(99.9000) =      7.438 ms/op
     p(99.9900) =     14.778 ms/op
     p(99.9990) =     15.867 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


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
# Warmup Iteration   1: 5.264 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.010 ms/op
Iteration   1: 3.141 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.047 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.038 ms/op
                 listUser·p0.999:  10.194 ms/op
                 listUser·p0.9999: 11.397 ms/op
                 listUser·p1.00:   12.026 ms/op

Iteration   2: 3.087 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.822 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.961 ms/op
                 listUser·p0.9999: 11.201 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   3: 3.085 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.539 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  10.174 ms/op
                 listUser·p0.9999: 11.768 ms/op
                 listUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309001
  mean =      3.104 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 77542 
    [ 2.500,  3.750) = 184852 
    [ 3.750,  5.000) = 36979 
    [ 5.000,  6.250) = 7780 
    [ 6.250,  7.500) = 1035 
    [ 7.500,  8.750) = 166 
    [ 8.750, 10.000) = 228 
    [10.000, 11.250) = 289 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     10.125 ms/op
     p(99.9900) =     11.570 ms/op
     p(99.9990) =     11.969 ms/op
     p(99.9999) =     12.026 ms/op
    p(100.0000) =     12.026 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.042 ± 1.422  ops/ms
ClientPb.existUser                       thrpt       3  12.679 ± 1.439  ops/ms
ClientPb.getUser                         thrpt       3  12.309 ± 1.954  ops/ms
ClientPb.listUser                        thrpt       3  10.369 ± 0.823  ops/ms
ClientPb.createUser                       avgt       3   2.577 ± 0.408   ms/op
ClientPb.existUser                        avgt       3   2.538 ± 0.426   ms/op
ClientPb.getUser                          avgt       3   2.583 ± 0.276   ms/op
ClientPb.listUser                         avgt       3   3.082 ± 0.125   ms/op
ClientPb.createUser                     sample  367340   2.611 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.886           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.654           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.815           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.869           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.876           ms/op
ClientPb.existUser                      sample  373912   2.565 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.734           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.593           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.899           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.555           ms/op
ClientPb.existUser:existUser·p0.9999    sample          16.152           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.252           ms/op
ClientPb.getUser                        sample  371022   2.585 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.889           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.601           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.438           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.778           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.318           ms/op
ClientPb.listUser                       sample  309001   3.104 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.822           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.027           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.849           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.125           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.570           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.026           ms/op
