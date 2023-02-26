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
# Warmup Iteration   1: 2.361 ops/ms
# Warmup Iteration   2: 5.733 ops/ms
# Warmup Iteration   3: 7.205 ops/ms
Iteration   1: 7.525 ops/ms
Iteration   2: 7.338 ops/ms
Iteration   3: 7.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.417 ±(99.9%) 1.758 ops/ms [Average]
  (min, avg, max) = (7.338, 7.417, 7.525), stdev = 0.096
  CI (99.9%): [5.659, 9.175] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.901 ops/ms
# Warmup Iteration   2: 7.333 ops/ms
# Warmup Iteration   3: 7.991 ops/ms
Iteration   1: 8.154 ops/ms
Iteration   2: 7.913 ops/ms
Iteration   3: 7.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.953 ±(99.9%) 3.366 ops/ms [Average]
  (min, avg, max) = (7.792, 7.953, 8.154), stdev = 0.185
  CI (99.9%): [4.587, 11.319] (assumes normal distribution)


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
# Warmup Iteration   1: 4.443 ops/ms
# Warmup Iteration   2: 6.835 ops/ms
# Warmup Iteration   3: 7.232 ops/ms
Iteration   1: 7.403 ops/ms
Iteration   2: 7.749 ops/ms
Iteration   3: 7.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.572 ±(99.9%) 3.157 ops/ms [Average]
  (min, avg, max) = (7.403, 7.572, 7.749), stdev = 0.173
  CI (99.9%): [4.415, 10.729] (assumes normal distribution)


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
# Warmup Iteration   1: 3.641 ops/ms
# Warmup Iteration   2: 5.456 ops/ms
# Warmup Iteration   3: 5.827 ops/ms
Iteration   1: 5.800 ops/ms
Iteration   2: 5.755 ops/ms
Iteration   3: 5.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.804 ±(99.9%) 0.933 ops/ms [Average]
  (min, avg, max) = (5.755, 5.804, 5.857), stdev = 0.051
  CI (99.9%): [4.871, 6.737] (assumes normal distribution)


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
# Warmup Iteration   1: 6.327 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.604 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.370 ±(99.9%) 0.003 ms/op
Iteration   1: 4.298 ±(99.9%) 0.004 ms/op
Iteration   2: 4.395 ±(99.9%) 0.002 ms/op
Iteration   3: 4.270 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.321 ±(99.9%) 1.195 ms/op [Average]
  (min, avg, max) = (4.270, 4.321, 4.395), stdev = 0.065
  CI (99.9%): [3.126, 5.515] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.643 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.405 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.494 ±(99.9%) 0.017 ms/op
Iteration   1: 4.119 ±(99.9%) 0.004 ms/op
Iteration   2: 4.155 ±(99.9%) 0.003 ms/op
Iteration   3: 3.958 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.077 ±(99.9%) 1.919 ms/op [Average]
  (min, avg, max) = (3.958, 4.077, 4.155), stdev = 0.105
  CI (99.9%): [2.158, 5.996] (assumes normal distribution)


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
# Warmup Iteration   1: 6.392 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.263 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.218 ±(99.9%) 0.003 ms/op
Iteration   1: 4.336 ±(99.9%) 0.002 ms/op
Iteration   2: 4.385 ±(99.9%) 0.003 ms/op
Iteration   3: 4.267 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.329 ±(99.9%) 1.079 ms/op [Average]
  (min, avg, max) = (4.267, 4.329, 4.385), stdev = 0.059
  CI (99.9%): [3.250, 5.409] (assumes normal distribution)


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
# Warmup Iteration   1: 8.920 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.832 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.479 ±(99.9%) 0.020 ms/op
Iteration   1: 5.427 ±(99.9%) 0.011 ms/op
Iteration   2: 5.252 ±(99.9%) 0.010 ms/op
Iteration   3: 5.216 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.298 ±(99.9%) 2.063 ms/op [Average]
  (min, avg, max) = (5.216, 5.298, 5.427), stdev = 0.113
  CI (99.9%): [3.236, 7.361] (assumes normal distribution)


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
# Warmup Iteration   1: 6.688 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.453 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.013 ms/op
Iteration   1: 4.259 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   4.133 ms/op
                 createUser·p0.90:   5.489 ms/op
                 createUser·p0.95:   5.915 ms/op
                 createUser·p0.99:   7.479 ms/op
                 createUser·p0.999:  10.828 ms/op
                 createUser·p0.9999: 15.729 ms/op
                 createUser·p1.00:   16.007 ms/op

Iteration   2: 4.313 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.757 ms/op
                 createUser·p0.50:   4.190 ms/op
                 createUser·p0.90:   5.505 ms/op
                 createUser·p0.95:   6.029 ms/op
                 createUser·p0.99:   8.339 ms/op
                 createUser·p0.999:  14.321 ms/op
                 createUser·p0.9999: 20.288 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   3: 4.237 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   4.067 ms/op
                 createUser·p0.90:   5.341 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  13.543 ms/op
                 createUser·p0.9999: 19.759 ms/op
                 createUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 225009
  mean =      4.269 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5333 
    [ 2.500,  5.000) = 177747 
    [ 5.000,  7.500) = 38742 
    [ 7.500, 10.000) = 2445 
    [10.000, 12.500) = 510 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      4.125 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     12.616 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     20.734 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 6.132 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.302 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.012 ms/op
Iteration   1: 3.891 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   5.087 ms/op
                 existUser·p0.95:   5.579 ms/op
                 existUser·p0.99:   7.554 ms/op
                 existUser·p0.999:  10.519 ms/op
                 existUser·p0.9999: 15.481 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 3.817 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.784 ms/op
                 existUser·p0.95:   5.186 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  10.125 ms/op
                 existUser·p0.9999: 24.027 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   3: 3.929 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.915 ms/op
                 existUser·p0.95:   5.390 ms/op
                 existUser·p0.99:   6.988 ms/op
                 existUser·p0.999:  12.870 ms/op
                 existUser·p0.9999: 19.626 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 247568
  mean =      3.878 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12730 
    [ 2.500,  5.000) = 212656 
    [ 5.000,  7.500) = 20400 
    [ 7.500, 10.000) = 1277 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     11.993 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     24.298 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 6.573 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.675 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.479 ±(99.9%) 0.016 ms/op
Iteration   1: 4.538 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.906 ms/op
                 getUser·p0.95:   6.513 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  13.952 ms/op
                 getUser·p0.9999: 16.709 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   2: 4.346 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   4.190 ms/op
                 getUser·p0.90:   5.431 ms/op
                 getUser·p0.95:   5.947 ms/op
                 getUser·p0.99:   7.938 ms/op
                 getUser·p0.999:  14.107 ms/op
                 getUser·p0.9999: 22.553 ms/op
                 getUser·p1.00:   22.905 ms/op

Iteration   3: 4.322 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   4.166 ms/op
                 getUser·p0.90:   5.530 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   7.979 ms/op
                 getUser·p0.999:  13.288 ms/op
                 getUser·p0.9999: 22.289 ms/op
                 getUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218174
  mean =      4.400 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3907 
    [ 2.500,  5.000) = 165937 
    [ 5.000,  7.500) = 44932 
    [ 7.500, 10.000) = 2471 
    [10.000, 12.500) = 553 
    [12.500, 15.000) = 208 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.177 ms/op
     p(99.0000) =      8.192 ms/op
     p(99.9000) =     13.907 ms/op
     p(99.9900) =     22.092 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 7.791 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.574 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.318 ±(99.9%) 0.019 ms/op
Iteration   1: 5.209 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.741 ms/op
                 listUser·p0.50:   4.948 ms/op
                 listUser·p0.90:   6.840 ms/op
                 listUser·p0.95:   7.643 ms/op
                 listUser·p0.99:   10.061 ms/op
                 listUser·p0.999:  14.907 ms/op
                 listUser·p0.9999: 28.368 ms/op
                 listUser·p1.00:   29.590 ms/op

Iteration   2: 5.287 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   4.973 ms/op
                 listUser·p0.90:   7.045 ms/op
                 listUser·p0.95:   7.856 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  24.720 ms/op
                 listUser·p0.9999: 26.669 ms/op
                 listUser·p1.00:   27.263 ms/op

Iteration   3: 5.352 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   5.005 ms/op
                 listUser·p0.90:   7.217 ms/op
                 listUser·p0.95:   8.053 ms/op
                 listUser·p0.99:   10.437 ms/op
                 listUser·p0.999:  20.882 ms/op
                 listUser·p0.9999: 27.279 ms/op
                 listUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 181718
  mean =      5.282 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 233 
    [ 2.500,  5.000) = 92775 
    [ 5.000,  7.500) = 76335 
    [ 7.500, 10.000) = 10319 
    [10.000, 12.500) = 1530 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 97 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      7.037 ms/op
     p(95.0000) =      7.865 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     27.764 ms/op
     p(99.9990) =     29.375 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.417 ± 1.758  ops/ms
ClientGrpc.existUser                       thrpt       3   7.953 ± 3.366  ops/ms
ClientGrpc.getUser                         thrpt       3   7.572 ± 3.157  ops/ms
ClientGrpc.listUser                        thrpt       3   5.804 ± 0.933  ops/ms
ClientGrpc.createUser                       avgt       3   4.321 ± 1.195   ms/op
ClientGrpc.existUser                        avgt       3   4.077 ± 1.919   ms/op
ClientGrpc.getUser                          avgt       3   4.329 ± 1.079   ms/op
ClientGrpc.listUser                         avgt       3   5.298 ± 2.063   ms/op
ClientGrpc.createUser                     sample  225009   4.269 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.757           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.456           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.964           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.086           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.616           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.628           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.742           ms/op
ClientGrpc.existUser                      sample  247568   3.878 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.911           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.932           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.399           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.988           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.993           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.167           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.066           ms/op
ClientGrpc.getUser                        sample  218174   4.400 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.641           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.636           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.177           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.192           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.907           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.092           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.036           ms/op
ClientGrpc.listUser                       sample  181718   5.282 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.233           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.207           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.513           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.764           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.590           ms/op
