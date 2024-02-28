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
# Warmup Iteration   1: 4.999 ops/ms
# Warmup Iteration   2: 11.844 ops/ms
# Warmup Iteration   3: 12.361 ops/ms
Iteration   1: 12.497 ops/ms
Iteration   2: 12.676 ops/ms
Iteration   3: 12.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.613 ±(99.9%) 1.834 ops/ms [Average]
  (min, avg, max) = (12.497, 12.613, 12.676), stdev = 0.101
  CI (99.9%): [10.779, 14.447] (assumes normal distribution)


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
# Warmup Iteration   1: 8.171 ops/ms
# Warmup Iteration   2: 13.211 ops/ms
# Warmup Iteration   3: 13.118 ops/ms
Iteration   1: 13.153 ops/ms
Iteration   2: 13.055 ops/ms
Iteration   3: 13.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.101 ±(99.9%) 0.897 ops/ms [Average]
  (min, avg, max) = (13.055, 13.101, 13.153), stdev = 0.049
  CI (99.9%): [12.204, 13.998] (assumes normal distribution)


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
# Warmup Iteration   1: 7.202 ops/ms
# Warmup Iteration   2: 12.334 ops/ms
# Warmup Iteration   3: 12.807 ops/ms
Iteration   1: 12.831 ops/ms
Iteration   2: 12.776 ops/ms
Iteration   3: 12.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.821 ±(99.9%) 0.761 ops/ms [Average]
  (min, avg, max) = (12.776, 12.821, 12.857), stdev = 0.042
  CI (99.9%): [12.060, 13.582] (assumes normal distribution)


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
# Warmup Iteration   1: 6.812 ops/ms
# Warmup Iteration   2: 10.362 ops/ms
# Warmup Iteration   3: 10.187 ops/ms
Iteration   1: 10.511 ops/ms
Iteration   2: 10.404 ops/ms
Iteration   3: 10.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.431 ±(99.9%) 1.292 ops/ms [Average]
  (min, avg, max) = (10.378, 10.431, 10.511), stdev = 0.071
  CI (99.9%): [9.139, 11.723] (assumes normal distribution)


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
# Warmup Iteration   1: 3.988 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.004 ms/op
Iteration   1: 2.566 ±(99.9%) 0.003 ms/op
Iteration   2: 2.533 ±(99.9%) 0.003 ms/op
Iteration   3: 2.548 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (2.533, 2.549, 2.566), stdev = 0.017
  CI (99.9%): [2.248, 2.850] (assumes normal distribution)


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
# Warmup Iteration   1: 3.626 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.462 ±(99.9%) 0.115 ms/op [Average]
  (min, avg, max) = (2.455, 2.462, 2.468), stdev = 0.006
  CI (99.9%): [2.346, 2.577] (assumes normal distribution)


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
# Warmup Iteration   1: 4.108 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.005 ms/op
Iteration   1: 2.539 ±(99.9%) 0.004 ms/op
Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
Iteration   3: 2.501 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.522 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (2.501, 2.522, 2.539), stdev = 0.019
  CI (99.9%): [2.171, 2.872] (assumes normal distribution)


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
# Warmup Iteration   1: 4.822 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 3.018 ±(99.9%) 0.006 ms/op
Iteration   2: 3.001 ±(99.9%) 0.007 ms/op
Iteration   3: 3.007 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.009 ±(99.9%) 0.159 ms/op [Average]
  (min, avg, max) = (3.001, 3.009, 3.018), stdev = 0.009
  CI (99.9%): [2.850, 3.168] (assumes normal distribution)


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
# Warmup Iteration   1: 4.121 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.679 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.005 ms/op
Iteration   1: 2.546 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.995 ms/op
                 createUser·p0.999:  11.181 ms/op
                 createUser·p0.9999: 13.622 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  9.716 ms/op
                 createUser·p0.9999: 12.994 ms/op
                 createUser·p1.00:   14.090 ms/op

Iteration   3: 2.588 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.297 ms/op
                 createUser·p0.99:   4.055 ms/op
                 createUser·p0.999:  8.594 ms/op
                 createUser·p0.9999: 10.890 ms/op
                 createUser·p1.00:   14.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374858
  mean =      2.558 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 177272 
    [ 2.500,  3.750) = 192311 
    [ 3.750,  5.000) = 4129 
    [ 5.000,  6.250) = 613 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     14.049 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 3.855 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  7.735 ms/op
                 existUser·p0.9999: 14.319 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  5.853 ms/op
                 existUser·p0.9999: 13.320 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  8.795 ms/op
                 existUser·p0.9999: 11.731 ms/op
                 existUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383731
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 189377 
    [ 2.500,  3.750) = 191277 
    [ 3.750,  5.000) = 2348 
    [ 5.000,  6.250) = 256 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.600 ms/op
     p(99.9000) =      6.835 ms/op
     p(99.9900) =     13.330 ms/op
     p(99.9990) =     14.541 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.687 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.006 ms/op
Iteration   1: 2.562 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   3.985 ms/op
                 getUser·p0.999:  12.034 ms/op
                 getUser·p0.9999: 13.797 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   2: 2.563 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.022 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  9.273 ms/op
                 getUser·p0.9999: 12.968 ms/op
                 getUser·p1.00:   13.664 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.034 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.789 ms/op
                 getUser·p0.999:  8.783 ms/op
                 getUser·p0.9999: 12.288 ms/op
                 getUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376009
  mean =      2.551 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 181600 
    [ 2.500,  3.750) = 188646 
    [ 3.750,  5.000) = 4440 
    [ 5.000,  6.250) = 826 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 129 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      4.043 ms/op
     p(99.9000) =      8.945 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     14.434 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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
# Warmup Iteration   1: 4.937 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.009 ms/op
Iteration   1: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  8.806 ms/op
                 listUser·p0.9999: 10.792 ms/op
                 listUser·p1.00:   11.436 ms/op

Iteration   2: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.822 ms/op
                 listUser·p0.9999: 12.033 ms/op
                 listUser·p1.00:   12.763 ms/op

Iteration   3: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.833 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  8.888 ms/op
                 listUser·p0.9999: 10.082 ms/op
                 listUser·p1.00:   10.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316564
  mean =      3.030 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 87024 
    [ 2.500,  3.750) = 188922 
    [ 3.750,  5.000) = 32932 
    [ 5.000,  6.250) = 6122 
    [ 6.250,  7.500) = 796 
    [ 7.500,  8.750) = 307 
    [ 8.750, 10.000) = 245 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      8.838 ms/op
     p(99.9900) =     11.163 ms/op
     p(99.9990) =     12.550 ms/op
     p(99.9999) =     12.763 ms/op
    p(100.0000) =     12.763 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.613 ± 1.834  ops/ms
ClientPb.existUser                       thrpt       3  13.101 ± 0.897  ops/ms
ClientPb.getUser                         thrpt       3  12.821 ± 0.761  ops/ms
ClientPb.listUser                        thrpt       3  10.431 ± 1.292  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.301   ms/op
ClientPb.existUser                        avgt       3   2.462 ± 0.115   ms/op
ClientPb.getUser                          avgt       3   2.522 ± 0.351   ms/op
ClientPb.listUser                         avgt       3   3.009 ± 0.159   ms/op
ClientPb.createUser                     sample  374858   2.558 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.838           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.765           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.320           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.320           ms/op
ClientPb.existUser                      sample  383731   2.499 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.670           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.835           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.330           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.631           ms/op
ClientPb.getUser                        sample  376009   2.551 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.955           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.585           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.945           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.484           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.615           ms/op
ClientPb.listUser                       sample  316564   3.030 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.833           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.838           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.163           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.763           ms/op
