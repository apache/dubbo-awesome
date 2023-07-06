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
# Warmup Iteration   1: 2.893 ops/ms
# Warmup Iteration   2: 6.411 ops/ms
# Warmup Iteration   3: 7.641 ops/ms
Iteration   1: 8.066 ops/ms
Iteration   2: 8.368 ops/ms
Iteration   3: 8.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.281 ±(99.9%) 3.410 ops/ms [Average]
  (min, avg, max) = (8.066, 8.281, 8.408), stdev = 0.187
  CI (99.9%): [4.871, 11.691] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.294 ops/ms
# Warmup Iteration   2: 8.153 ops/ms
# Warmup Iteration   3: 8.332 ops/ms
Iteration   1: 8.879 ops/ms
Iteration   2: 8.967 ops/ms
Iteration   3: 8.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.834 ±(99.9%) 2.915 ops/ms [Average]
  (min, avg, max) = (8.657, 8.834, 8.967), stdev = 0.160
  CI (99.9%): [5.919, 11.749] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.301 ops/ms
# Warmup Iteration   2: 7.659 ops/ms
# Warmup Iteration   3: 8.020 ops/ms
Iteration   1: 8.338 ops/ms
Iteration   2: 8.209 ops/ms
Iteration   3: 8.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.234 ±(99.9%) 1.712 ops/ms [Average]
  (min, avg, max) = (8.155, 8.234, 8.338), stdev = 0.094
  CI (99.9%): [6.522, 9.946] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.124 ops/ms
# Warmup Iteration   2: 5.812 ops/ms
# Warmup Iteration   3: 6.367 ops/ms
Iteration   1: 6.268 ops/ms
Iteration   2: 6.319 ops/ms
Iteration   3: 6.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.223 ±(99.9%) 2.281 ops/ms [Average]
  (min, avg, max) = (6.081, 6.223, 6.319), stdev = 0.125
  CI (99.9%): [3.941, 8.504] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.438 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.008 ms/op
Iteration   1: 3.979 ±(99.9%) 0.004 ms/op
Iteration   2: 3.889 ±(99.9%) 0.004 ms/op
Iteration   3: 3.918 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.929 ±(99.9%) 0.836 ms/op [Average]
  (min, avg, max) = (3.889, 3.929, 3.979), stdev = 0.046
  CI (99.9%): [3.093, 4.765] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.088 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.705 ±(99.9%) 0.004 ms/op
Iteration   1: 3.708 ±(99.9%) 0.004 ms/op
Iteration   2: 3.731 ±(99.9%) 0.003 ms/op
Iteration   3: 3.693 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.710 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (3.693, 3.710, 3.731), stdev = 0.019
  CI (99.9%): [3.362, 4.058] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.598 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.005 ms/op
Iteration   1: 3.827 ±(99.9%) 0.005 ms/op
Iteration   2: 3.902 ±(99.9%) 0.003 ms/op
Iteration   3: 3.875 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.868 ±(99.9%) 0.692 ms/op [Average]
  (min, avg, max) = (3.827, 3.868, 3.902), stdev = 0.038
  CI (99.9%): [3.176, 4.560] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.354 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.300 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.134 ±(99.9%) 0.016 ms/op
Iteration   1: 5.244 ±(99.9%) 0.017 ms/op
Iteration   2: 4.993 ±(99.9%) 0.011 ms/op
Iteration   3: 4.926 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.054 ±(99.9%) 3.055 ms/op [Average]
  (min, avg, max) = (4.926, 5.054, 5.244), stdev = 0.167
  CI (99.9%): [1.999, 8.110] (assumes normal distribution)


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
# Warmup Iteration   1: 5.771 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.012 ms/op
Iteration   1: 3.962 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.407 ms/op
                 createUser·p0.99:   7.504 ms/op
                 createUser·p0.999:  13.702 ms/op
                 createUser·p0.9999: 19.294 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   2: 3.911 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   7.307 ms/op
                 createUser·p0.999:  11.757 ms/op
                 createUser·p0.9999: 20.343 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   3: 3.868 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.276 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  12.222 ms/op
                 createUser·p0.9999: 20.209 ms/op
                 createUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 245159
  mean =      3.913 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6900 
    [ 2.500,  5.000) = 219698 
    [ 5.000,  7.500) = 16205 
    [ 7.500, 10.000) = 1819 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     12.351 ms/op
     p(99.9900) =     20.120 ms/op
     p(99.9990) =     21.650 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.401 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.694 ±(99.9%) 0.010 ms/op
Iteration   1: 3.691 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   3.568 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   4.948 ms/op
                 existUser·p0.99:   6.914 ms/op
                 existUser·p0.999:  10.475 ms/op
                 existUser·p0.9999: 16.122 ms/op
                 existUser·p1.00:   16.646 ms/op

Iteration   2: 3.706 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  13.437 ms/op
                 existUser·p0.9999: 20.033 ms/op
                 existUser·p1.00:   20.316 ms/op

Iteration   3: 3.664 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.989 ms/op
                 existUser·p0.99:   7.184 ms/op
                 existUser·p0.999:  11.583 ms/op
                 existUser·p0.9999: 27.984 ms/op
                 existUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 260224
  mean =      3.687 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6965 
    [ 2.500,  5.000) = 241512 
    [ 5.000,  7.500) = 9964 
    [ 7.500, 10.000) = 1332 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     11.465 ms/op
     p(99.9900) =     26.411 ms/op
     p(99.9990) =     28.148 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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
# Warmup Iteration   1: 5.489 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.011 ms/op
Iteration   1: 3.953 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.866 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  13.763 ms/op
                 getUser·p0.9999: 27.676 ms/op
                 getUser·p1.00:   28.148 ms/op

Iteration   2: 3.854 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   7.315 ms/op
                 getUser·p0.999:  10.059 ms/op
                 getUser·p0.9999: 16.772 ms/op
                 getUser·p1.00:   20.382 ms/op

Iteration   3: 3.842 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   6.819 ms/op
                 getUser·p0.999:  11.338 ms/op
                 getUser·p0.9999: 20.840 ms/op
                 getUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 247380
  mean =      3.882 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7001 
    [ 2.500,  5.000) = 223291 
    [ 5.000,  7.500) = 15294 
    [ 7.500, 10.000) = 1369 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     11.106 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     28.115 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 6.460 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.366 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.098 ±(99.9%) 0.019 ms/op
Iteration   1: 5.001 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.452 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.390 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   9.748 ms/op
                 listUser·p0.999:  16.450 ms/op
                 listUser·p0.9999: 20.520 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   2: 5.023 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   6.521 ms/op
                 listUser·p0.95:   7.561 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 20.390 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   3: 4.945 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.717 ms/op
                 listUser·p0.95:   7.528 ms/op
                 listUser·p0.99:   9.683 ms/op
                 listUser·p0.999:  19.944 ms/op
                 listUser·p0.9999: 24.530 ms/op
                 listUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 192281
  mean =      4.989 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 279 
    [ 2.500,  5.000) = 125969 
    [ 5.000,  7.500) = 56449 
    [ 7.500, 10.000) = 7888 
    [10.000, 12.500) = 1029 
    [12.500, 15.000) = 290 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.545 ms/op
     p(95.0000) =      7.496 ms/op
     p(99.0000) =      9.798 ms/op
     p(99.9000) =     17.208 ms/op
     p(99.9900) =     22.507 ms/op
     p(99.9990) =     25.085 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.281 ± 3.410  ops/ms
ClientGrpc.existUser                       thrpt       3   8.834 ± 2.915  ops/ms
ClientGrpc.getUser                         thrpt       3   8.234 ± 1.712  ops/ms
ClientGrpc.listUser                        thrpt       3   6.223 ± 2.281  ops/ms
ClientGrpc.createUser                       avgt       3   3.929 ± 0.836   ms/op
ClientGrpc.existUser                        avgt       3   3.710 ± 0.348   ms/op
ClientGrpc.getUser                          avgt       3   3.868 ± 0.692   ms/op
ClientGrpc.listUser                         avgt       3   5.054 ± 3.055   ms/op
ClientGrpc.createUser                     sample  245159   3.913 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.762           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.317           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.430           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.351           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.120           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.281           ms/op
ClientGrpc.existUser                      sample  260224   3.687 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.651           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.915           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.849           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.465           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.411           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.312           ms/op
ClientGrpc.getUser                        sample  247380   3.882 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.973           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.768           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.226           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.021           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.106           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.673           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.148           ms/op
ClientGrpc.listUser                       sample  192281   4.989 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.206           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.702           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.545           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.496           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.798           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.208           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.507           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.297           ms/op
