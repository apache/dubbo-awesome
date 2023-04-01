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
# Warmup Iteration   1: 2.237 ops/ms
# Warmup Iteration   2: 5.671 ops/ms
# Warmup Iteration   3: 7.350 ops/ms
Iteration   1: 7.610 ops/ms
Iteration   2: 7.884 ops/ms
Iteration   3: 7.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.776 ±(99.9%) 2.660 ops/ms [Average]
  (min, avg, max) = (7.610, 7.776, 7.884), stdev = 0.146
  CI (99.9%): [5.116, 10.436] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.875 ops/ms
# Warmup Iteration   2: 7.602 ops/ms
# Warmup Iteration   3: 8.086 ops/ms
Iteration   1: 8.191 ops/ms
Iteration   2: 8.047 ops/ms
Iteration   3: 8.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.143 ±(99.9%) 1.517 ops/ms [Average]
  (min, avg, max) = (8.047, 8.143, 8.192), stdev = 0.083
  CI (99.9%): [6.627, 9.660] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.158 ops/ms
# Warmup Iteration   2: 7.036 ops/ms
# Warmup Iteration   3: 7.530 ops/ms
Iteration   1: 7.564 ops/ms
Iteration   2: 7.766 ops/ms
Iteration   3: 7.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.693 ±(99.9%) 2.051 ops/ms [Average]
  (min, avg, max) = (7.564, 7.693, 7.766), stdev = 0.112
  CI (99.9%): [5.643, 9.744] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.642 ops/ms
# Warmup Iteration   2: 5.157 ops/ms
# Warmup Iteration   3: 5.584 ops/ms
Iteration   1: 5.738 ops/ms
Iteration   2: 5.646 ops/ms
Iteration   3: 5.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.728 ±(99.9%) 1.416 ops/ms [Average]
  (min, avg, max) = (5.646, 5.728, 5.801), stdev = 0.078
  CI (99.9%): [4.312, 7.145] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.559 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.678 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.440 ±(99.9%) 0.003 ms/op
Iteration   1: 4.296 ±(99.9%) 0.003 ms/op
Iteration   2: 4.148 ±(99.9%) 0.005 ms/op
Iteration   3: 4.214 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.219 ±(99.9%) 1.352 ms/op [Average]
  (min, avg, max) = (4.148, 4.219, 4.296), stdev = 0.074
  CI (99.9%): [2.867, 5.572] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.899 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.006 ms/op
Iteration   1: 3.952 ±(99.9%) 0.002 ms/op
Iteration   2: 3.856 ±(99.9%) 0.003 ms/op
Iteration   3: 3.929 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.912 ±(99.9%) 0.907 ms/op [Average]
  (min, avg, max) = (3.856, 3.912, 3.952), stdev = 0.050
  CI (99.9%): [3.005, 4.820] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.093 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.694 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.349 ±(99.9%) 0.005 ms/op
Iteration   1: 4.233 ±(99.9%) 0.014 ms/op
Iteration   2: 4.273 ±(99.9%) 0.010 ms/op
Iteration   3: 4.323 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.276 ±(99.9%) 0.824 ms/op [Average]
  (min, avg, max) = (4.233, 4.276, 4.323), stdev = 0.045
  CI (99.9%): [3.452, 5.100] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.385 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 6.265 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.456 ±(99.9%) 0.017 ms/op
Iteration   1: 5.441 ±(99.9%) 0.019 ms/op
Iteration   2: 5.360 ±(99.9%) 0.021 ms/op
Iteration   3: 5.329 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.377 ±(99.9%) 1.052 ms/op [Average]
  (min, avg, max) = (5.329, 5.377, 5.441), stdev = 0.058
  CI (99.9%): [4.325, 6.429] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.803 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.626 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.011 ms/op
Iteration   1: 4.169 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   4.071 ms/op
                 createUser·p0.90:   5.243 ms/op
                 createUser·p0.95:   5.702 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  12.931 ms/op
                 createUser·p0.9999: 22.184 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 4.254 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   4.100 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.808 ms/op
                 createUser·p0.99:   7.823 ms/op
                 createUser·p0.999:  12.244 ms/op
                 createUser·p0.9999: 21.446 ms/op
                 createUser·p1.00:   21.725 ms/op

Iteration   3: 4.234 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   4.088 ms/op
                 createUser·p0.90:   5.366 ms/op
                 createUser·p0.95:   5.906 ms/op
                 createUser·p0.99:   8.086 ms/op
                 createUser·p0.999:  13.598 ms/op
                 createUser·p0.9999: 21.674 ms/op
                 createUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 227363
  mean =      4.219 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5377 
    [ 2.500,  5.000) = 186438 
    [ 5.000,  7.500) = 33025 
    [ 7.500, 10.000) = 1873 
    [10.000, 12.500) = 388 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      4.088 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.806 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     13.091 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     23.333 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 6.359 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.011 ms/op
Iteration   1: 3.883 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.891 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   7.070 ms/op
                 existUser·p0.999:  11.305 ms/op
                 existUser·p0.9999: 21.160 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   2: 3.933 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.891 ms/op
                 existUser·p0.95:   5.399 ms/op
                 existUser·p0.99:   6.930 ms/op
                 existUser·p0.999:  10.184 ms/op
                 existUser·p0.9999: 19.328 ms/op
                 existUser·p1.00:   19.366 ms/op

Iteration   3: 3.925 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.809 ms/op
                 existUser·p0.95:   5.317 ms/op
                 existUser·p0.99:   6.742 ms/op
                 existUser·p0.999:  13.402 ms/op
                 existUser·p0.9999: 40.754 ms/op
                 existUser·p1.00:   42.140 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 245271
  mean =      3.914 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 225042 
    [ 5.000, 10.000) = 19766 
    [10.000, 15.000) = 335 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 42 
    [40.000, 45.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     11.600 ms/op
     p(99.9900) =     39.846 ms/op
     p(99.9990) =     41.175 ms/op
     p(99.9999) =     42.140 ms/op
    p(100.0000) =     42.140 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.398 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.533 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.256 ±(99.9%) 0.013 ms/op
Iteration   1: 4.201 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   4.071 ms/op
                 getUser·p0.90:   5.226 ms/op
                 getUser·p0.95:   5.759 ms/op
                 getUser·p0.99:   7.774 ms/op
                 getUser·p0.999:  13.056 ms/op
                 getUser·p0.9999: 16.597 ms/op
                 getUser·p1.00:   17.007 ms/op

Iteration   2: 4.145 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   4.022 ms/op
                 getUser·p0.90:   5.145 ms/op
                 getUser·p0.95:   5.652 ms/op
                 getUser·p0.99:   7.717 ms/op
                 getUser·p0.999:  14.217 ms/op
                 getUser·p0.9999: 17.985 ms/op
                 getUser·p1.00:   21.201 ms/op

Iteration   3: 4.207 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.243 ms/op
                 getUser·p0.95:   5.743 ms/op
                 getUser·p0.99:   7.430 ms/op
                 getUser·p0.999:  15.139 ms/op
                 getUser·p0.9999: 26.286 ms/op
                 getUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 229222
  mean =      4.184 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5473 
    [ 2.500,  5.000) = 193044 
    [ 5.000,  7.500) = 28191 
    [ 7.500, 10.000) = 1813 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      4.051 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     13.903 ms/op
     p(99.9900) =     24.904 ms/op
     p(99.9990) =     28.104 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.605 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.898 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.559 ±(99.9%) 0.023 ms/op
Iteration   1: 5.394 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   5.063 ms/op
                 listUser·p0.90:   7.248 ms/op
                 listUser·p0.95:   8.282 ms/op
                 listUser·p0.99:   10.650 ms/op
                 listUser·p0.999:  19.599 ms/op
                 listUser·p0.9999: 22.652 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   2: 5.321 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   4.964 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.307 ms/op
                 listUser·p0.99:   10.289 ms/op
                 listUser·p0.999:  18.042 ms/op
                 listUser·p0.9999: 30.572 ms/op
                 listUser·p1.00:   30.999 ms/op

Iteration   3: 5.395 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   5.005 ms/op
                 listUser·p0.90:   7.414 ms/op
                 listUser·p0.95:   8.298 ms/op
                 listUser·p0.99:   10.846 ms/op
                 listUser·p0.999:  20.120 ms/op
                 listUser·p0.9999: 27.167 ms/op
                 listUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 178717
  mean =      5.369 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 436 
    [ 2.500,  5.000) = 88147 
    [ 5.000,  7.500) = 73849 
    [ 7.500, 10.000) = 13672 
    [10.000, 12.500) = 1842 
    [12.500, 15.000) = 331 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      7.365 ms/op
     p(95.0000) =      8.298 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     30.028 ms/op
     p(99.9990) =     30.895 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.776 ± 2.660  ops/ms
ClientGrpc.existUser                       thrpt       3   8.143 ± 1.517  ops/ms
ClientGrpc.getUser                         thrpt       3   7.693 ± 2.051  ops/ms
ClientGrpc.listUser                        thrpt       3   5.728 ± 1.416  ops/ms
ClientGrpc.createUser                       avgt       3   4.219 ± 1.352   ms/op
ClientGrpc.existUser                        avgt       3   3.912 ± 0.907   ms/op
ClientGrpc.getUser                          avgt       3   4.276 ± 0.824   ms/op
ClientGrpc.listUser                         avgt       3   5.377 ± 1.052   ms/op
ClientGrpc.createUser                     sample  227363   4.219 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.768           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.308           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.806           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.676           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.091           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.856           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.593           ms/op
ClientGrpc.existUser                      sample  245271   3.914 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.786           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.866           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.374           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.914           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.600           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          39.846           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          42.140           ms/op
ClientGrpc.getUser                        sample  229222   4.184 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.766           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.051           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.202           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.718           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.651           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.903           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.904           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.048           ms/op
ClientGrpc.listUser                       sample  178717   5.369 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.153           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.365           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.298           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.568           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.628           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.028           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.999           ms/op
