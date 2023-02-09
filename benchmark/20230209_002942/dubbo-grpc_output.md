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
# Warmup Iteration   1: 4.184 ops/ms
# Warmup Iteration   2: 9.282 ops/ms
# Warmup Iteration   3: 10.088 ops/ms
Iteration   1: 10.301 ops/ms
Iteration   2: 10.078 ops/ms
Iteration   3: 9.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.077 ±(99.9%) 4.082 ops/ms [Average]
  (min, avg, max) = (9.853, 10.077, 10.301), stdev = 0.224
  CI (99.9%): [5.995, 14.159] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.454 ops/ms
# Warmup Iteration   2: 10.317 ops/ms
# Warmup Iteration   3: 10.540 ops/ms
Iteration   1: 10.355 ops/ms
Iteration   2: 11.027 ops/ms
Iteration   3: 10.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.682 ±(99.9%) 6.136 ops/ms [Average]
  (min, avg, max) = (10.355, 10.682, 11.027), stdev = 0.336
  CI (99.9%): [4.546, 16.818] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.972 ops/ms
# Warmup Iteration   2: 9.775 ops/ms
# Warmup Iteration   3: 10.085 ops/ms
Iteration   1: 10.204 ops/ms
Iteration   2: 10.089 ops/ms
Iteration   3: 10.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.198 ±(99.9%) 1.937 ops/ms [Average]
  (min, avg, max) = (10.089, 10.198, 10.301), stdev = 0.106
  CI (99.9%): [8.261, 12.135] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.149 ops/ms
# Warmup Iteration   2: 7.643 ops/ms
# Warmup Iteration   3: 7.790 ops/ms
Iteration   1: 7.970 ops/ms
Iteration   2: 7.961 ops/ms
Iteration   3: 7.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.960 ±(99.9%) 0.208 ops/ms [Average]
  (min, avg, max) = (7.948, 7.960, 7.970), stdev = 0.011
  CI (99.9%): [7.752, 8.168] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.219 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.004 ms/op
Iteration   1: 3.179 ±(99.9%) 0.010 ms/op
Iteration   2: 3.217 ±(99.9%) 0.002 ms/op
Iteration   3: 3.225 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.207 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (3.179, 3.207, 3.225), stdev = 0.025
  CI (99.9%): [2.755, 3.659] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.983 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.002 ms/op
Iteration   1: 3.027 ±(99.9%) 0.002 ms/op
Iteration   2: 3.030 ±(99.9%) 0.002 ms/op
Iteration   3: 3.070 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.042 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (3.027, 3.042, 3.070), stdev = 0.024
  CI (99.9%): [2.608, 3.476] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.197 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.002 ms/op
Iteration   1: 3.239 ±(99.9%) 0.001 ms/op
Iteration   2: 3.168 ±(99.9%) 0.002 ms/op
Iteration   3: 3.049 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.152 ±(99.9%) 1.749 ms/op [Average]
  (min, avg, max) = (3.049, 3.152, 3.239), stdev = 0.096
  CI (99.9%): [1.403, 4.901] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.706 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.208 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.026 ms/op
Iteration   1: 4.004 ±(99.9%) 0.012 ms/op
Iteration   2: 4.018 ±(99.9%) 0.008 ms/op
Iteration   3: 3.937 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.987 ±(99.9%) 0.793 ms/op [Average]
  (min, avg, max) = (3.937, 3.987, 4.018), stdev = 0.043
  CI (99.9%): [3.193, 4.780] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.439 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
Iteration   1: 3.114 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.715 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.563 ms/op
                 createUser·p0.9999: 17.039 ms/op
                 createUser·p1.00:   18.776 ms/op

Iteration   2: 3.125 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.781 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.068 ms/op
                 createUser·p0.9999: 29.680 ms/op
                 createUser·p1.00:   30.933 ms/op

Iteration   3: 3.237 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  11.492 ms/op
                 createUser·p0.9999: 26.149 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303937
  mean =      3.158 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25647 
    [ 2.500,  5.000) = 277176 
    [ 5.000,  7.500) = 816 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.424 ms/op
     p(99.9900) =     29.112 ms/op
     p(99.9990) =     30.044 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.005 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
Iteration   1: 3.083 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  7.643 ms/op
                 existUser·p0.9999: 15.273 ms/op
                 existUser·p1.00:   15.942 ms/op

Iteration   2: 3.049 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.552 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.323 ms/op
                 existUser·p0.9999: 16.138 ms/op
                 existUser·p1.00:   16.613 ms/op

Iteration   3: 2.999 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.873 ms/op
                 existUser·p0.9999: 16.569 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315546
  mean =      3.043 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1931 
    [ 1.250,  2.500) = 41719 
    [ 2.500,  3.750) = 239474 
    [ 3.750,  5.000) = 31348 
    [ 5.000,  6.250) = 463 
    [ 6.250,  7.500) = 330 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 70 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.274 ms/op
     p(99.9900) =     16.162 ms/op
     p(99.9990) =     17.462 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.267 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.007 ms/op
Iteration   1: 3.238 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.027 ms/op
                 getUser·p0.9999: 11.684 ms/op
                 getUser·p1.00:   11.977 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.176 ms/op
                 getUser·p0.9999: 15.083 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   3: 3.168 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.095 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  6.947 ms/op
                 getUser·p0.9999: 15.301 ms/op
                 getUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303194
  mean =      3.164 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 364 
    [ 1.250,  2.500) = 20175 
    [ 2.500,  3.750) = 242786 
    [ 3.750,  5.000) = 38712 
    [ 5.000,  6.250) = 657 
    [ 6.250,  7.500) = 279 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      6.996 ms/op
     p(99.9900) =     15.101 ms/op
     p(99.9990) =     17.461 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 4.750 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.260 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.010 ms/op
Iteration   1: 4.031 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  13.861 ms/op
                 listUser·p0.9999: 17.042 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   2: 3.966 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.319 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 24.148 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   3: 4.032 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.855 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  17.990 ms/op
                 listUser·p0.9999: 23.235 ms/op
                 listUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239312
  mean =      4.009 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2009 
    [ 2.500,  5.000) = 210393 
    [ 5.000,  7.500) = 25741 
    [ 7.500, 10.000) = 695 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     15.609 ms/op
     p(99.9900) =     23.431 ms/op
     p(99.9990) =     24.609 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.077 ± 4.082  ops/ms
ClientGrpc.existUser                       thrpt       3  10.682 ± 6.136  ops/ms
ClientGrpc.getUser                         thrpt       3  10.198 ± 1.937  ops/ms
ClientGrpc.listUser                        thrpt       3   7.960 ± 0.208  ops/ms
ClientGrpc.createUser                       avgt       3   3.207 ± 0.452   ms/op
ClientGrpc.existUser                        avgt       3   3.042 ± 0.434   ms/op
ClientGrpc.getUser                          avgt       3   3.152 ± 1.749   ms/op
ClientGrpc.listUser                         avgt       3   3.987 ± 0.793   ms/op
ClientGrpc.createUser                     sample  303937   3.158 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.715           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.080           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.424           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.112           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.933           ms/op
ClientGrpc.existUser                      sample  315546   3.043 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.552           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.031           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.940           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.274           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.162           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  303194   3.164 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.667           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.063           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.996           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.101           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.629           ms/op
ClientGrpc.listUser                       sample  239312   4.009 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.855           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.609           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.431           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.740           ms/op
