# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.108 ops/ms
# Warmup Iteration   2: 5.014 ops/ms
# Warmup Iteration   3: 6.473 ops/ms
Iteration   1: 6.908 ops/ms
Iteration   2: 6.939 ops/ms
Iteration   3: 7.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.180 ±(99.9%) 8.100 ops/ms [Average]
  (min, avg, max) = (6.908, 7.180, 7.692), stdev = 0.444
  CI (99.9%): [≈ 0, 15.280] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.229 ops/ms
# Warmup Iteration   2: 7.505 ops/ms
# Warmup Iteration   3: 7.704 ops/ms
Iteration   1: 7.967 ops/ms
Iteration   2: 7.842 ops/ms
Iteration   3: 8.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.965 ±(99.9%) 2.242 ops/ms [Average]
  (min, avg, max) = (7.842, 7.965, 8.087), stdev = 0.123
  CI (99.9%): [5.724, 10.207] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.649 ops/ms
# Warmup Iteration   2: 6.675 ops/ms
# Warmup Iteration   3: 6.944 ops/ms
Iteration   1: 7.070 ops/ms
Iteration   2: 7.075 ops/ms
Iteration   3: 6.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.012 ±(99.9%) 1.910 ops/ms [Average]
  (min, avg, max) = (6.891, 7.012, 7.075), stdev = 0.105
  CI (99.9%): [5.102, 8.922] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.748 ops/ms
# Warmup Iteration   2: 4.974 ops/ms
# Warmup Iteration   3: 5.546 ops/ms
Iteration   1: 5.853 ops/ms
Iteration   2: 5.593 ops/ms
Iteration   3: 5.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.707 ±(99.9%) 2.427 ops/ms [Average]
  (min, avg, max) = (5.593, 5.707, 5.853), stdev = 0.133
  CI (99.9%): [3.280, 8.134] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.383 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.702 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.662 ±(99.9%) 0.006 ms/op
Iteration   1: 4.471 ±(99.9%) 0.004 ms/op
Iteration   2: 4.449 ±(99.9%) 0.003 ms/op
Iteration   3: 4.344 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.422 ±(99.9%) 1.237 ms/op [Average]
  (min, avg, max) = (4.344, 4.422, 4.471), stdev = 0.068
  CI (99.9%): [3.184, 5.659] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.161 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.443 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.320 ±(99.9%) 0.006 ms/op
Iteration   1: 4.237 ±(99.9%) 0.003 ms/op
Iteration   2: 4.275 ±(99.9%) 0.004 ms/op
Iteration   3: 4.134 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.215 ±(99.9%) 1.327 ms/op [Average]
  (min, avg, max) = (4.134, 4.215, 4.275), stdev = 0.073
  CI (99.9%): [2.888, 5.542] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.448 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.005 ms/op
Iteration   1: 4.116 ±(99.9%) 0.005 ms/op
Iteration   2: 4.249 ±(99.9%) 0.004 ms/op
Iteration   3: 4.125 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.164 ±(99.9%) 1.354 ms/op [Average]
  (min, avg, max) = (4.116, 4.164, 4.249), stdev = 0.074
  CI (99.9%): [2.809, 5.518] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.770 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.725 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.627 ±(99.9%) 0.019 ms/op
Iteration   1: 5.720 ±(99.9%) 0.021 ms/op
Iteration   2: 5.604 ±(99.9%) 0.018 ms/op
Iteration   3: 5.580 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.635 ±(99.9%) 1.360 ms/op [Average]
  (min, avg, max) = (5.580, 5.635, 5.720), stdev = 0.075
  CI (99.9%): [4.274, 6.995] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.688 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.849 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.565 ±(99.9%) 0.016 ms/op
Iteration   1: 4.609 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   4.375 ms/op
                 createUser·p0.90:   5.972 ms/op
                 createUser·p0.95:   6.767 ms/op
                 createUser·p0.99:   9.028 ms/op
                 createUser·p0.999:  15.335 ms/op
                 createUser·p0.9999: 23.009 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 4.447 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   5.980 ms/op
                 createUser·p0.99:   8.356 ms/op
                 createUser·p0.999:  14.567 ms/op
                 createUser·p0.9999: 22.538 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   3: 4.420 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.456 ms/op
                 createUser·p0.95:   6.070 ms/op
                 createUser·p0.99:   8.585 ms/op
                 createUser·p0.999:  12.866 ms/op
                 createUser·p0.9999: 27.799 ms/op
                 createUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 213664
  mean =      4.490 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3531 
    [ 2.500,  5.000) = 163994 
    [ 5.000,  7.500) = 41624 
    [ 7.500, 10.000) = 3572 
    [10.000, 12.500) = 664 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      5.628 ms/op
     p(95.0000) =      6.267 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     13.883 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     28.635 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.730 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.728 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.012 ms/op
Iteration   1: 4.192 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   4.035 ms/op
                 existUser·p0.90:   5.366 ms/op
                 existUser·p0.95:   5.931 ms/op
                 existUser·p0.99:   7.929 ms/op
                 existUser·p0.999:  14.632 ms/op
                 existUser·p0.9999: 21.454 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   2: 4.017 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   3.932 ms/op
                 existUser·p0.90:   4.964 ms/op
                 existUser·p0.95:   5.374 ms/op
                 existUser·p0.99:   7.160 ms/op
                 existUser·p0.999:  10.197 ms/op
                 existUser·p0.9999: 17.598 ms/op
                 existUser·p1.00:   19.005 ms/op

Iteration   3: 3.947 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.998 ms/op
                 existUser·p0.50:   3.834 ms/op
                 existUser·p0.90:   4.923 ms/op
                 existUser·p0.95:   5.399 ms/op
                 existUser·p0.99:   7.348 ms/op
                 existUser·p0.999:  13.893 ms/op
                 existUser·p0.9999: 20.277 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236985
  mean =      4.050 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7114 
    [ 2.500,  5.000) = 203326 
    [ 5.000,  7.500) = 24179 
    [ 7.500, 10.000) = 1827 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     13.288 ms/op
     p(99.9900) =     20.313 ms/op
     p(99.9990) =     23.021 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.711 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.453 ±(99.9%) 0.017 ms/op
Iteration   1: 4.204 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   4.080 ms/op
                 getUser·p0.90:   5.210 ms/op
                 getUser·p0.95:   5.677 ms/op
                 getUser·p0.99:   7.602 ms/op
                 getUser·p0.999:  14.314 ms/op
                 getUser·p0.9999: 19.831 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   2: 4.233 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   4.104 ms/op
                 getUser·p0.90:   5.308 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   7.869 ms/op
                 getUser·p0.999:  11.968 ms/op
                 getUser·p0.9999: 18.874 ms/op
                 getUser·p1.00:   19.726 ms/op

Iteration   3: 4.332 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   4.202 ms/op
                 getUser·p0.90:   5.456 ms/op
                 getUser·p0.95:   5.988 ms/op
                 getUser·p0.99:   7.610 ms/op
                 getUser·p0.999:  10.437 ms/op
                 getUser·p0.9999: 23.653 ms/op
                 getUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 225462
  mean =      4.256 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5561 
    [ 2.500,  5.000) = 184832 
    [ 5.000,  7.500) = 32454 
    [ 7.500, 10.000) = 2058 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      4.129 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.700 ms/op
     p(99.9000) =     12.468 ms/op
     p(99.9900) =     21.162 ms/op
     p(99.9990) =     24.125 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.543 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 5.481 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.598 ±(99.9%) 0.020 ms/op
Iteration   1: 5.592 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.537 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   11.158 ms/op
                 listUser·p0.999:  18.049 ms/op
                 listUser·p0.9999: 22.399 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   2: 5.679 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.011 ms/op
                 listUser·p0.50:   5.276 ms/op
                 listUser·p0.90:   7.676 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   12.239 ms/op
                 listUser·p0.999:  17.546 ms/op
                 listUser·p0.9999: 24.633 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   3: 5.580 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.298 ms/op
                 listUser·p0.99:   11.551 ms/op
                 listUser·p0.999:  20.767 ms/op
                 listUser·p0.9999: 29.557 ms/op
                 listUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 170803
  mean =      5.617 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 143 
    [ 2.500,  5.000) = 65394 
    [ 5.000,  7.500) = 88209 
    [ 7.500, 10.000) = 13187 
    [10.000, 12.500) = 2714 
    [12.500, 15.000) = 695 
    [15.000, 17.500) = 270 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      7.496 ms/op
     p(95.0000) =      8.634 ms/op
     p(99.0000) =     11.649 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     27.428 ms/op
     p(99.9990) =     29.796 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.180 ± 8.100  ops/ms
ClientGrpc.existUser                       thrpt       3   7.965 ± 2.242  ops/ms
ClientGrpc.getUser                         thrpt       3   7.012 ± 1.910  ops/ms
ClientGrpc.listUser                        thrpt       3   5.707 ± 2.427  ops/ms
ClientGrpc.createUser                       avgt       3   4.422 ± 1.237   ms/op
ClientGrpc.existUser                        avgt       3   4.215 ± 1.327   ms/op
ClientGrpc.getUser                          avgt       3   4.164 ± 1.354   ms/op
ClientGrpc.listUser                         avgt       3   5.635 ± 1.360   ms/op
ClientGrpc.createUser                     sample  213664   4.490 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.005           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.628           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.267           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.716           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.883           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.723           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.639           ms/op
ClientGrpc.existUser                      sample  236985   4.050 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.899           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.928           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.079           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.587           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.496           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.288           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.313           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.855           ms/op
ClientGrpc.getUser                        sample  225462   4.256 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.933           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.325           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.841           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.700           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.468           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.162           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.281           ms/op
ClientGrpc.listUser                       sample  170803   5.617 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.925           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.267           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.496           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.634           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.649           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.350           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.428           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.819           ms/op
