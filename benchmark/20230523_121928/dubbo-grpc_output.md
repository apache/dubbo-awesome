# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.434 ops/ms
# Warmup Iteration   2: 7.034 ops/ms
# Warmup Iteration   3: 8.430 ops/ms
Iteration   1: 8.720 ops/ms
Iteration   2: 9.140 ops/ms
Iteration   3: 8.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.926 ±(99.9%) 3.834 ops/ms [Average]
  (min, avg, max) = (8.720, 8.926, 9.140), stdev = 0.210
  CI (99.9%): [5.093, 12.760] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.231 ops/ms
# Warmup Iteration   2: 8.902 ops/ms
# Warmup Iteration   3: 9.272 ops/ms
Iteration   1: 9.701 ops/ms
Iteration   2: 9.858 ops/ms
Iteration   3: 9.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.808 ±(99.9%) 1.693 ops/ms [Average]
  (min, avg, max) = (9.701, 9.808, 9.866), stdev = 0.093
  CI (99.9%): [8.116, 11.501] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.694 ops/ms
# Warmup Iteration   2: 8.719 ops/ms
# Warmup Iteration   3: 8.914 ops/ms
Iteration   1: 9.148 ops/ms
Iteration   2: 9.326 ops/ms
Iteration   3: 9.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.256 ±(99.9%) 1.723 ops/ms [Average]
  (min, avg, max) = (9.148, 9.256, 9.326), stdev = 0.094
  CI (99.9%): [7.532, 10.979] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.307 ops/ms
# Warmup Iteration   2: 6.436 ops/ms
# Warmup Iteration   3: 6.791 ops/ms
Iteration   1: 6.990 ops/ms
Iteration   2: 6.857 ops/ms
Iteration   3: 7.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.028 ±(99.9%) 3.521 ops/ms [Average]
  (min, avg, max) = (6.857, 7.028, 7.237), stdev = 0.193
  CI (99.9%): [3.506, 10.549] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.082 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.003 ms/op
Iteration   1: 3.519 ±(99.9%) 0.003 ms/op
Iteration   2: 3.551 ±(99.9%) 0.004 ms/op
Iteration   3: 3.542 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.537 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (3.519, 3.537, 3.551), stdev = 0.016
  CI (99.9%): [3.237, 3.838] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.807 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.446 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.003 ms/op
Iteration   1: 3.401 ±(99.9%) 0.004 ms/op
Iteration   2: 3.195 ±(99.9%) 0.002 ms/op
Iteration   3: 3.116 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.237 ±(99.9%) 2.692 ms/op [Average]
  (min, avg, max) = (3.116, 3.237, 3.401), stdev = 0.148
  CI (99.9%): [0.545, 5.929] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.872 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.581 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.004 ms/op
Iteration   1: 3.590 ±(99.9%) 0.003 ms/op
Iteration   2: 3.568 ±(99.9%) 0.002 ms/op
Iteration   3: 3.507 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.555 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (3.507, 3.555, 3.590), stdev = 0.043
  CI (99.9%): [2.768, 4.341] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.360 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.635 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.416 ±(99.9%) 0.012 ms/op
Iteration   1: 4.333 ±(99.9%) 0.024 ms/op
Iteration   2: 4.310 ±(99.9%) 0.007 ms/op
Iteration   3: 4.593 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.412 ±(99.9%) 2.866 ms/op [Average]
  (min, avg, max) = (4.310, 4.412, 4.593), stdev = 0.157
  CI (99.9%): [1.546, 7.278] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.934 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.008 ms/op
Iteration   1: 3.423 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.149 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  10.608 ms/op
                 createUser·p0.9999: 13.648 ms/op
                 createUser·p1.00:   13.812 ms/op

Iteration   2: 3.454 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  10.912 ms/op
                 createUser·p0.9999: 18.427 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   3: 3.437 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.436 ms/op
                 createUser·p0.999:  11.076 ms/op
                 createUser·p0.9999: 31.928 ms/op
                 createUser·p1.00:   32.637 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 279243
  mean =      3.438 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13159 
    [ 2.500,  5.000) = 260199 
    [ 5.000,  7.500) = 4754 
    [ 7.500, 10.000) = 762 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     10.863 ms/op
     p(99.9900) =     30.474 ms/op
     p(99.9990) =     32.152 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.797 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.582 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.009 ms/op
Iteration   1: 3.375 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  13.571 ms/op
                 existUser·p0.9999: 14.934 ms/op
                 existUser·p1.00:   15.860 ms/op

Iteration   2: 3.334 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.296 ms/op
                 existUser·p0.999:  7.594 ms/op
                 existUser·p0.9999: 19.051 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   3: 3.400 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  13.424 ms/op
                 existUser·p0.9999: 20.709 ms/op
                 existUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 285045
  mean =      3.369 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10085 
    [ 2.500,  5.000) = 270013 
    [ 5.000,  7.500) = 4287 
    [ 7.500, 10.000) = 330 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     10.436 ms/op
     p(99.9900) =     19.660 ms/op
     p(99.9990) =     20.935 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.474 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.009 ms/op
Iteration   1: 3.419 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  10.862 ms/op
                 getUser·p0.9999: 20.578 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   2: 3.525 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  9.798 ms/op
                 getUser·p0.9999: 18.252 ms/op
                 getUser·p1.00:   19.071 ms/op

Iteration   3: 3.452 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  7.643 ms/op
                 getUser·p0.9999: 30.176 ms/op
                 getUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 277158
  mean =      3.465 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10038 
    [ 2.500,  5.000) = 261578 
    [ 5.000,  7.500) = 4915 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.631 ms/op
     p(99.9900) =     28.714 ms/op
     p(99.9990) =     30.875 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.635 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.786 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.604 ±(99.9%) 0.017 ms/op
Iteration   1: 4.478 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   5.808 ms/op
                 listUser·p0.95:   6.652 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  16.147 ms/op
                 listUser·p0.9999: 21.491 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   2: 4.374 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   4.157 ms/op
                 listUser·p0.90:   5.734 ms/op
                 listUser·p0.95:   6.578 ms/op
                 listUser·p0.99:   8.240 ms/op
                 listUser·p0.999:  16.759 ms/op
                 listUser·p0.9999: 28.619 ms/op
                 listUser·p1.00:   30.605 ms/op

Iteration   3: 4.461 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   5.792 ms/op
                 listUser·p0.95:   6.685 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  18.859 ms/op
                 listUser·p0.9999: 23.478 ms/op
                 listUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 216308
  mean =      4.437 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1965 
    [ 2.500,  5.000) = 175604 
    [ 5.000,  7.500) = 34004 
    [ 7.500, 10.000) = 3842 
    [10.000, 12.500) = 383 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.775 ms/op
     p(95.0000) =      6.636 ms/op
     p(99.0000) =      8.356 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     25.821 ms/op
     p(99.9990) =     30.600 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.926 ± 3.834  ops/ms
ClientGrpc.existUser                       thrpt       3   9.808 ± 1.693  ops/ms
ClientGrpc.getUser                         thrpt       3   9.256 ± 1.723  ops/ms
ClientGrpc.listUser                        thrpt       3   7.028 ± 3.521  ops/ms
ClientGrpc.createUser                       avgt       3   3.537 ± 0.301   ms/op
ClientGrpc.existUser                        avgt       3   3.237 ± 2.692   ms/op
ClientGrpc.getUser                          avgt       3   3.555 ± 0.786   ms/op
ClientGrpc.listUser                         avgt       3   4.412 ± 2.866   ms/op
ClientGrpc.createUser                     sample  279243   3.438 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.717           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.391           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.076           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.863           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.474           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.637           ms/op
ClientGrpc.existUser                      sample  285045   3.369 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.685           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.879           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.497           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.436           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.660           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.201           ms/op
ClientGrpc.getUser                        sample  277158   3.465 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.768           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.412           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.108           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.513           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.631           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.714           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.966           ms/op
ClientGrpc.listUser                       sample  216308   4.437 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.902           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.227           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.356           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.728           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.821           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.605           ms/op
