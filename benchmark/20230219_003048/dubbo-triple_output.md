# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.554 ops/ms
# Warmup Iteration   2: 5.885 ops/ms
# Warmup Iteration   3: 8.850 ops/ms
Iteration   1: 9.880 ops/ms
Iteration   2: 9.517 ops/ms
Iteration   3: 9.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.731 ±(99.9%) 3.458 ops/ms [Average]
  (min, avg, max) = (9.517, 9.731, 9.880), stdev = 0.190
  CI (99.9%): [6.273, 13.188] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.617 ops/ms
# Warmup Iteration   2: 9.351 ops/ms
# Warmup Iteration   3: 9.919 ops/ms
Iteration   1: 10.456 ops/ms
Iteration   2: 10.662 ops/ms
Iteration   3: 10.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.600 ±(99.9%) 2.273 ops/ms [Average]
  (min, avg, max) = (10.456, 10.600, 10.681), stdev = 0.125
  CI (99.9%): [8.326, 12.873] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.305 ops/ms
# Warmup Iteration   2: 9.258 ops/ms
# Warmup Iteration   3: 9.704 ops/ms
Iteration   1: 9.693 ops/ms
Iteration   2: 9.860 ops/ms
Iteration   3: 10.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.903 ±(99.9%) 4.278 ops/ms [Average]
  (min, avg, max) = (9.693, 9.903, 10.156), stdev = 0.234
  CI (99.9%): [5.625, 14.181] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.076 ops/ms
# Warmup Iteration   2: 8.010 ops/ms
# Warmup Iteration   3: 8.378 ops/ms
Iteration   1: 8.602 ops/ms
Iteration   2: 8.547 ops/ms
Iteration   3: 8.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.488 ±(99.9%) 2.783 ops/ms [Average]
  (min, avg, max) = (8.315, 8.488, 8.602), stdev = 0.153
  CI (99.9%): [5.705, 11.271] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.575 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.333 ±(99.9%) 0.004 ms/op
Iteration   1: 3.319 ±(99.9%) 0.005 ms/op
Iteration   2: 3.312 ±(99.9%) 0.006 ms/op
Iteration   3: 3.182 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.271 ±(99.9%) 1.411 ms/op [Average]
  (min, avg, max) = (3.182, 3.271, 3.319), stdev = 0.077
  CI (99.9%): [1.860, 4.682] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.739 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.006 ms/op
Iteration   1: 3.006 ±(99.9%) 0.002 ms/op
Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
Iteration   3: 2.996 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.004 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (2.996, 3.004, 3.009), stdev = 0.007
  CI (99.9%): [2.883, 3.124] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.505 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.004 ms/op
Iteration   1: 3.180 ±(99.9%) 0.005 ms/op
Iteration   2: 3.185 ±(99.9%) 0.006 ms/op
Iteration   3: 3.119 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.162 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (3.119, 3.162, 3.185), stdev = 0.037
  CI (99.9%): [2.493, 3.830] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.158 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.004 ms/op
Iteration   1: 3.871 ±(99.9%) 0.003 ms/op
Iteration   2: 3.708 ±(99.9%) 0.009 ms/op
Iteration   3: 3.687 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.756 ±(99.9%) 1.840 ms/op [Average]
  (min, avg, max) = (3.687, 3.756, 3.871), stdev = 0.101
  CI (99.9%): [1.916, 5.595] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.588 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.010 ms/op
Iteration   1: 3.252 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.961 ms/op
                 createUser·p0.999:  18.634 ms/op
                 createUser·p0.9999: 21.163 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   2: 3.210 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   5.271 ms/op
                 createUser·p0.999:  10.272 ms/op
                 createUser·p0.9999: 21.792 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   3: 3.152 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.293 ms/op
                 createUser·p0.95:   3.404 ms/op
                 createUser·p0.99:   5.030 ms/op
                 createUser·p0.999:  14.647 ms/op
                 createUser·p0.9999: 23.916 ms/op
                 createUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299622
  mean =      3.204 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32587 
    [ 2.500,  5.000) = 260862 
    [ 5.000,  7.500) = 5306 
    [ 7.500, 10.000) = 423 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 157 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     17.281 ms/op
     p(99.9900) =     22.483 ms/op
     p(99.9990) =     24.609 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.956 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
Iteration   1: 3.077 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   5.038 ms/op
                 existUser·p0.999:  14.598 ms/op
                 existUser·p0.9999: 19.988 ms/op
                 existUser·p1.00:   20.644 ms/op

Iteration   2: 3.009 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.720 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.133 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  9.151 ms/op
                 existUser·p0.9999: 22.064 ms/op
                 existUser·p1.00:   22.512 ms/op

Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.671 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  11.502 ms/op
                 existUser·p0.9999: 20.864 ms/op
                 existUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313143
  mean =      3.065 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28340 
    [ 2.500,  5.000) = 280532 
    [ 5.000,  7.500) = 3611 
    [ 7.500, 10.000) = 290 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.256 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =     11.633 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     23.126 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.914 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.009 ms/op
Iteration   1: 3.399 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.100 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   7.045 ms/op
                 getUser·p0.999:  19.530 ms/op
                 getUser·p0.9999: 22.171 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   2: 3.190 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  14.382 ms/op
                 getUser·p0.9999: 26.705 ms/op
                 getUser·p1.00:   27.656 ms/op

Iteration   3: 3.194 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  16.411 ms/op
                 getUser·p0.9999: 26.279 ms/op
                 getUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294479
  mean =      3.258 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17609 
    [ 2.500,  5.000) = 267912 
    [ 5.000,  7.500) = 7818 
    [ 7.500, 10.000) = 698 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 78 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     16.548 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     27.145 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.132 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.012 ms/op
Iteration   1: 3.778 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.677 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 22.874 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   2: 3.761 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.509 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  13.123 ms/op
                 listUser·p0.9999: 17.580 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 3.713 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   7.042 ms/op
                 listUser·p0.999:  12.220 ms/op
                 listUser·p0.9999: 19.464 ms/op
                 listUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255863
  mean =      3.750 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 247500 
    [ 5.000,  7.500) = 6378 
    [ 7.500, 10.000) = 1125 
    [10.000, 12.500) = 393 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     21.477 ms/op
     p(99.9990) =     23.214 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.731 ± 3.458  ops/ms
ClientPb.existUser                       thrpt       3  10.600 ± 2.273  ops/ms
ClientPb.getUser                         thrpt       3   9.903 ± 4.278  ops/ms
ClientPb.listUser                        thrpt       3   8.488 ± 2.783  ops/ms
ClientPb.createUser                       avgt       3   3.271 ± 1.411   ms/op
ClientPb.existUser                        avgt       3   3.004 ± 0.121   ms/op
ClientPb.getUser                          avgt       3   3.162 ± 0.668   ms/op
ClientPb.listUser                         avgt       3   3.756 ± 1.840   ms/op
ClientPb.createUser                     sample  299622   3.204 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.065           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.281           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.483           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.838           ms/op
ClientPb.existUser                      sample  313143   3.065 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.235           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.490           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.186           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.633           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.037           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.233           ms/op
ClientPb.getUser                        sample  294479   3.258 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.851           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.686           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.545           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.548           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.214           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.656           ms/op
ClientPb.listUser                       sample  255863   3.750 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.509           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.029           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.156           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.477           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.331           ms/op
