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
# Warmup Iteration   1: 2.487 ops/ms
# Warmup Iteration   2: 6.440 ops/ms
# Warmup Iteration   3: 9.135 ops/ms
Iteration   1: 9.554 ops/ms
Iteration   2: 10.155 ops/ms
Iteration   3: 9.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.873 ±(99.9%) 5.507 ops/ms [Average]
  (min, avg, max) = (9.554, 9.873, 10.155), stdev = 0.302
  CI (99.9%): [4.366, 15.379] (assumes normal distribution)


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
# Warmup Iteration   1: 3.904 ops/ms
# Warmup Iteration   2: 9.464 ops/ms
# Warmup Iteration   3: 10.230 ops/ms
Iteration   1: 10.128 ops/ms
Iteration   2: 10.182 ops/ms
Iteration   3: 10.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.236 ±(99.9%) 2.610 ops/ms [Average]
  (min, avg, max) = (10.128, 10.236, 10.398), stdev = 0.143
  CI (99.9%): [7.626, 12.846] (assumes normal distribution)


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
# Warmup Iteration   1: 3.530 ops/ms
# Warmup Iteration   2: 8.773 ops/ms
# Warmup Iteration   3: 9.746 ops/ms
Iteration   1: 10.157 ops/ms
Iteration   2: 9.844 ops/ms
Iteration   3: 9.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.916 ±(99.9%) 3.911 ops/ms [Average]
  (min, avg, max) = (9.748, 9.916, 10.157), stdev = 0.214
  CI (99.9%): [6.005, 13.827] (assumes normal distribution)


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
# Warmup Iteration   1: 3.408 ops/ms
# Warmup Iteration   2: 7.983 ops/ms
# Warmup Iteration   3: 8.363 ops/ms
Iteration   1: 8.507 ops/ms
Iteration   2: 8.762 ops/ms
Iteration   3: 8.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.664 ±(99.9%) 2.509 ops/ms [Average]
  (min, avg, max) = (8.507, 8.664, 8.762), stdev = 0.138
  CI (99.9%): [6.156, 11.173] (assumes normal distribution)


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
# Warmup Iteration   1: 8.680 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.005 ms/op
Iteration   1: 3.136 ±(99.9%) 0.006 ms/op
Iteration   2: 3.355 ±(99.9%) 0.007 ms/op
Iteration   3: 3.137 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.209 ±(99.9%) 2.297 ms/op [Average]
  (min, avg, max) = (3.136, 3.209, 3.355), stdev = 0.126
  CI (99.9%): [0.912, 5.506] (assumes normal distribution)


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
# Warmup Iteration   1: 6.781 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.288 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.005 ms/op
Iteration   1: 3.212 ±(99.9%) 0.007 ms/op
Iteration   2: 3.105 ±(99.9%) 0.007 ms/op
Iteration   3: 3.051 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.123 ±(99.9%) 1.492 ms/op [Average]
  (min, avg, max) = (3.051, 3.123, 3.212), stdev = 0.082
  CI (99.9%): [1.631, 4.614] (assumes normal distribution)


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
# Warmup Iteration   1: 7.655 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.529 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.004 ms/op
Iteration   1: 3.209 ±(99.9%) 0.006 ms/op
Iteration   2: 3.218 ±(99.9%) 0.004 ms/op
Iteration   3: 3.083 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.170 ±(99.9%) 1.372 ms/op [Average]
  (min, avg, max) = (3.083, 3.170, 3.218), stdev = 0.075
  CI (99.9%): [1.798, 4.542] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.440 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.763 ±(99.9%) 0.010 ms/op
Iteration   1: 3.733 ±(99.9%) 0.008 ms/op
Iteration   2: 3.784 ±(99.9%) 0.006 ms/op
Iteration   3: 3.647 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.722 ±(99.9%) 1.260 ms/op [Average]
  (min, avg, max) = (3.647, 3.722, 3.784), stdev = 0.069
  CI (99.9%): [2.462, 4.982] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.209 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.009 ms/op
Iteration   1: 3.197 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  9.951 ms/op
                 createUser·p0.9999: 19.922 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   2: 3.059 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.649 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.174 ms/op
                 createUser·p0.95:   3.539 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  9.010 ms/op
                 createUser·p0.9999: 23.119 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   3: 3.214 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.278 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  15.192 ms/op
                 createUser·p0.9999: 20.890 ms/op
                 createUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304180
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16572 
    [ 2.500,  5.000) = 281851 
    [ 5.000,  7.500) = 4882 
    [ 7.500, 10.000) = 440 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     15.103 ms/op
     p(99.9900) =     21.548 ms/op
     p(99.9990) =     24.311 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 6.923 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.441 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
Iteration   1: 3.099 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  9.400 ms/op
                 existUser·p0.9999: 19.300 ms/op
                 existUser·p1.00:   20.218 ms/op

Iteration   2: 3.118 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   4.040 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  13.271 ms/op
                 existUser·p0.9999: 22.405 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   3: 3.069 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.321 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  14.680 ms/op
                 existUser·p0.9999: 25.060 ms/op
                 existUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310072
  mean =      3.095 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17397 
    [ 2.500,  5.000) = 287840 
    [ 5.000,  7.500) = 3840 
    [ 7.500, 10.000) = 497 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.311 ms/op
     p(99.9000) =     14.122 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     25.261 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 7.366 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.009 ms/op
Iteration   1: 3.168 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.565 ms/op
                 getUser·p0.999:  13.868 ms/op
                 getUser·p0.9999: 20.644 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.534 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  11.649 ms/op
                 getUser·p0.9999: 27.394 ms/op
                 getUser·p1.00:   29.131 ms/op

Iteration   3: 3.188 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.382 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   4.007 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  11.370 ms/op
                 getUser·p0.9999: 20.217 ms/op
                 getUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302313
  mean =      3.175 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12464 
    [ 2.500,  5.000) = 284055 
    [ 5.000,  7.500) = 4958 
    [ 7.500, 10.000) = 457 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     12.911 ms/op
     p(99.9900) =     25.872 ms/op
     p(99.9990) =     28.638 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 8.378 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.012 ms/op
Iteration   1: 3.687 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.470 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 22.290 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   2: 3.752 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  14.250 ms/op
                 listUser·p0.9999: 19.562 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 3.720 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.999 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  12.599 ms/op
                 listUser·p0.9999: 16.187 ms/op
                 listUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258004
  mean =      3.720 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 249621 
    [ 5.000,  7.500) = 6302 
    [ 7.500, 10.000) = 1273 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     15.024 ms/op
     p(99.9900) =     20.578 ms/op
     p(99.9990) =     22.911 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.873 ± 5.507  ops/ms
ClientPb.existUser                       thrpt       3  10.236 ± 2.610  ops/ms
ClientPb.getUser                         thrpt       3   9.916 ± 3.911  ops/ms
ClientPb.listUser                        thrpt       3   8.664 ± 2.509  ops/ms
ClientPb.createUser                       avgt       3   3.209 ± 2.297   ms/op
ClientPb.existUser                        avgt       3   3.123 ± 1.492   ms/op
ClientPb.getUser                          avgt       3   3.170 ± 1.372   ms/op
ClientPb.listUser                         avgt       3   3.722 ± 1.260   ms/op
ClientPb.createUser                     sample  304180   3.155 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.971           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.506           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.103           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.548           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.592           ms/op
ClientPb.existUser                      sample  310072   3.095 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.780           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.404           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.311           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.122           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.117           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.461           ms/op
ClientPb.getUser                        sample  302313   3.175 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.023           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.514           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.702           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.911           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.872           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.131           ms/op
ClientPb.listUser                       sample  258004   3.720 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.470           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.576           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.024           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.578           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.200           ms/op
