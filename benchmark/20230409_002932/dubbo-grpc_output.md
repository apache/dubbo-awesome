# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.557 ops/ms
# Warmup Iteration   2: 5.601 ops/ms
# Warmup Iteration   3: 7.741 ops/ms
Iteration   1: 8.009 ops/ms
Iteration   2: 7.993 ops/ms
Iteration   3: 7.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.766 ±(99.9%) 7.435 ops/ms [Average]
  (min, avg, max) = (7.295, 7.766, 8.009), stdev = 0.408
  CI (99.9%): [0.331, 15.201] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.932 ops/ms
# Warmup Iteration   2: 7.929 ops/ms
# Warmup Iteration   3: 8.594 ops/ms
Iteration   1: 8.500 ops/ms
Iteration   2: 8.554 ops/ms
Iteration   3: 8.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.402 ±(99.9%) 3.990 ops/ms [Average]
  (min, avg, max) = (8.151, 8.402, 8.554), stdev = 0.219
  CI (99.9%): [4.412, 12.392] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.615 ops/ms
# Warmup Iteration   2: 7.361 ops/ms
# Warmup Iteration   3: 7.766 ops/ms
Iteration   1: 7.859 ops/ms
Iteration   2: 7.782 ops/ms
Iteration   3: 7.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.858 ±(99.9%) 1.365 ops/ms [Average]
  (min, avg, max) = (7.782, 7.858, 7.932), stdev = 0.075
  CI (99.9%): [6.493, 9.222] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.639 ops/ms
# Warmup Iteration   2: 5.792 ops/ms
# Warmup Iteration   3: 6.195 ops/ms
Iteration   1: 6.178 ops/ms
Iteration   2: 6.002 ops/ms
Iteration   3: 6.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.172 ±(99.9%) 3.048 ops/ms [Average]
  (min, avg, max) = (6.002, 6.172, 6.336), stdev = 0.167
  CI (99.9%): [3.124, 9.220] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.102 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.393 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.009 ms/op
Iteration   1: 4.322 ±(99.9%) 0.003 ms/op
Iteration   2: 3.984 ±(99.9%) 0.003 ms/op
Iteration   3: 4.032 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.112 ±(99.9%) 3.333 ms/op [Average]
  (min, avg, max) = (3.984, 4.112, 4.322), stdev = 0.183
  CI (99.9%): [0.780, 7.445] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.693 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.003 ms/op
Iteration   1: 3.877 ±(99.9%) 0.003 ms/op
Iteration   2: 3.695 ±(99.9%) 0.003 ms/op
Iteration   3: 3.729 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.767 ±(99.9%) 1.769 ms/op [Average]
  (min, avg, max) = (3.695, 3.767, 3.877), stdev = 0.097
  CI (99.9%): [1.998, 5.537] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.001 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.326 ±(99.9%) 0.004 ms/op
Iteration   1: 3.942 ±(99.9%) 0.009 ms/op
Iteration   2: 3.865 ±(99.9%) 0.003 ms/op
Iteration   3: 3.884 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.897 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (3.865, 3.897, 3.942), stdev = 0.040
  CI (99.9%): [3.168, 4.626] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.862 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.688 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.252 ±(99.9%) 0.015 ms/op
Iteration   1: 5.045 ±(99.9%) 0.012 ms/op
Iteration   2: 5.009 ±(99.9%) 0.006 ms/op
Iteration   3: 5.209 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.088 ±(99.9%) 1.949 ms/op [Average]
  (min, avg, max) = (5.009, 5.088, 5.209), stdev = 0.107
  CI (99.9%): [3.139, 7.037] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.061 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.011 ms/op
Iteration   1: 3.927 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   5.022 ms/op
                 createUser·p0.95:   5.513 ms/op
                 createUser·p0.99:   7.067 ms/op
                 createUser·p0.999:  13.634 ms/op
                 createUser·p0.9999: 18.664 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   2: 4.119 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   3.994 ms/op
                 createUser·p0.90:   5.333 ms/op
                 createUser·p0.95:   5.865 ms/op
                 createUser·p0.99:   7.617 ms/op
                 createUser·p0.999:  13.484 ms/op
                 createUser·p0.9999: 20.528 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   3: 4.058 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   5.276 ms/op
                 createUser·p0.95:   5.808 ms/op
                 createUser·p0.99:   7.643 ms/op
                 createUser·p0.999:  14.262 ms/op
                 createUser·p0.9999: 22.122 ms/op
                 createUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 237850
  mean =      4.033 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6507 
    [ 2.500,  5.000) = 200196 
    [ 5.000,  7.500) = 28793 
    [ 7.500, 10.000) = 1688 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     13.763 ms/op
     p(99.9900) =     21.426 ms/op
     p(99.9990) =     22.389 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.972 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.020 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.011 ms/op
Iteration   1: 3.766 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   3.627 ms/op
                 existUser·p0.90:   4.792 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   7.271 ms/op
                 existUser·p0.999:  12.768 ms/op
                 existUser·p0.9999: 18.236 ms/op
                 existUser·p1.00:   18.579 ms/op

Iteration   2: 3.719 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.210 ms/op
                 existUser·p0.99:   6.717 ms/op
                 existUser·p0.999:  9.501 ms/op
                 existUser·p0.9999: 30.152 ms/op
                 existUser·p1.00:   30.900 ms/op

Iteration   3: 3.727 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.809 ms/op
                 existUser·p0.95:   5.349 ms/op
                 existUser·p0.99:   7.307 ms/op
                 existUser·p0.999:  16.253 ms/op
                 existUser·p0.9999: 34.865 ms/op
                 existUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 256940
  mean =      3.737 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11228 
    [ 2.500,  5.000) = 226701 
    [ 5.000,  7.500) = 17085 
    [ 7.500, 10.000) = 1384 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     12.174 ms/op
     p(99.9900) =     34.079 ms/op
     p(99.9990) =     35.062 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.375 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.153 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.012 ms/op
Iteration   1: 3.951 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   5.120 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   7.441 ms/op
                 getUser·p0.999:  10.830 ms/op
                 getUser·p0.9999: 18.584 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   2: 4.067 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   5.194 ms/op
                 getUser·p0.95:   5.661 ms/op
                 getUser·p0.99:   7.324 ms/op
                 getUser·p0.999:  10.000 ms/op
                 getUser·p0.9999: 26.617 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   3: 4.268 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   4.149 ms/op
                 getUser·p0.90:   5.456 ms/op
                 getUser·p0.95:   6.029 ms/op
                 getUser·p0.99:   7.668 ms/op
                 getUser·p0.999:  11.601 ms/op
                 getUser·p0.9999: 25.183 ms/op
                 getUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 234542
  mean =      4.091 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5798 
    [ 2.500,  5.000) = 195471 
    [ 5.000,  7.500) = 30904 
    [ 7.500, 10.000) = 2004 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     11.099 ms/op
     p(99.9900) =     26.331 ms/op
     p(99.9990) =     26.727 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.989 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.554 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.280 ±(99.9%) 0.021 ms/op
Iteration   1: 5.323 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   5.104 ms/op
                 listUser·p0.90:   6.980 ms/op
                 listUser·p0.95:   8.028 ms/op
                 listUser·p0.99:   10.437 ms/op
                 listUser·p0.999:  18.576 ms/op
                 listUser·p0.9999: 20.577 ms/op
                 listUser·p1.00:   23.069 ms/op

Iteration   2: 5.159 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   4.891 ms/op
                 listUser·p0.90:   6.791 ms/op
                 listUser·p0.95:   7.676 ms/op
                 listUser·p0.99:   10.101 ms/op
                 listUser·p0.999:  19.038 ms/op
                 listUser·p0.9999: 25.565 ms/op
                 listUser·p1.00:   26.542 ms/op

Iteration   3: 5.474 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.518 ms/op
                 listUser·p0.50:   5.259 ms/op
                 listUser·p0.90:   7.127 ms/op
                 listUser·p0.95:   8.004 ms/op
                 listUser·p0.99:   10.371 ms/op
                 listUser·p0.999:  28.757 ms/op
                 listUser·p0.9999: 36.045 ms/op
                 listUser·p1.00:   38.797 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180562
  mean =      5.315 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 330 
    [ 2.500,  5.000) = 84782 
    [ 5.000,  7.500) = 83300 
    [ 7.500, 10.000) = 9981 
    [10.000, 12.500) = 1562 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      7.905 ms/op
     p(99.0000) =     10.295 ms/op
     p(99.9000) =     19.610 ms/op
     p(99.9900) =     34.927 ms/op
     p(99.9990) =     38.797 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.766 ± 7.435  ops/ms
ClientGrpc.existUser                       thrpt       3   8.402 ± 3.990  ops/ms
ClientGrpc.getUser                         thrpt       3   7.858 ± 1.365  ops/ms
ClientGrpc.listUser                        thrpt       3   6.172 ± 3.048  ops/ms
ClientGrpc.createUser                       avgt       3   4.112 ± 3.333   ms/op
ClientGrpc.existUser                        avgt       3   3.767 ± 1.769   ms/op
ClientGrpc.getUser                          avgt       3   3.897 ± 0.729   ms/op
ClientGrpc.listUser                         avgt       3   5.088 ± 1.949   ms/op
ClientGrpc.createUser                     sample  237850   4.033 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.887           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.210           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.734           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.479           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.763           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.426           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.512           ms/op
ClientGrpc.existUser                      sample  256940   3.737 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.825           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.784           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.276           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.086           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.174           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          34.079           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.127           ms/op
ClientGrpc.getUser                        sample  234542   4.091 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.558           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.267           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.792           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.512           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.099           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.331           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.739           ms/op
ClientGrpc.listUser                       sample  180562   5.315 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.292           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.905           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.295           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.610           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.927           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.797           ms/op
