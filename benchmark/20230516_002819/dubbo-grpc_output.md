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
# Warmup Iteration   1: 3.075 ops/ms
# Warmup Iteration   2: 6.269 ops/ms
# Warmup Iteration   3: 7.597 ops/ms
Iteration   1: 8.153 ops/ms
Iteration   2: 8.528 ops/ms
Iteration   3: 8.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.277 ±(99.9%) 3.963 ops/ms [Average]
  (min, avg, max) = (8.151, 8.277, 8.528), stdev = 0.217
  CI (99.9%): [4.313, 12.240] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 6.100 ops/ms
# Warmup Iteration   2: 7.879 ops/ms
# Warmup Iteration   3: 8.809 ops/ms
Iteration   1: 9.110 ops/ms
Iteration   2: 8.950 ops/ms
Iteration   3: 9.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.044 ±(99.9%) 1.521 ops/ms [Average]
  (min, avg, max) = (8.950, 9.044, 9.110), stdev = 0.083
  CI (99.9%): [7.523, 10.564] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.803 ops/ms
# Warmup Iteration   2: 7.777 ops/ms
# Warmup Iteration   3: 8.497 ops/ms
Iteration   1: 8.340 ops/ms
Iteration   2: 8.381 ops/ms
Iteration   3: 8.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.500 ±(99.9%) 4.417 ops/ms [Average]
  (min, avg, max) = (8.340, 8.500, 8.778), stdev = 0.242
  CI (99.9%): [4.083, 12.917] (assumes normal distribution)


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
# Warmup Iteration   1: 4.115 ops/ms
# Warmup Iteration   2: 5.546 ops/ms
# Warmup Iteration   3: 6.207 ops/ms
Iteration   1: 6.329 ops/ms
Iteration   2: 6.277 ops/ms
Iteration   3: 6.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.340 ±(99.9%) 1.271 ops/ms [Average]
  (min, avg, max) = (6.277, 6.340, 6.415), stdev = 0.070
  CI (99.9%): [5.069, 7.611] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.216 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.024 ms/op
Iteration   1: 3.791 ±(99.9%) 0.004 ms/op
Iteration   2: 3.743 ±(99.9%) 0.004 ms/op
Iteration   3: 3.730 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.755 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (3.730, 3.755, 3.791), stdev = 0.033
  CI (99.9%): [3.161, 4.349] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.111 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.002 ms/op
Iteration   1: 3.657 ±(99.9%) 0.004 ms/op
Iteration   2: 3.561 ±(99.9%) 0.002 ms/op
Iteration   3: 3.663 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.627 ±(99.9%) 1.046 ms/op [Average]
  (min, avg, max) = (3.561, 3.627, 3.663), stdev = 0.057
  CI (99.9%): [2.581, 4.673] (assumes normal distribution)


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
# Warmup Iteration   1: 5.025 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.002 ms/op
Iteration   1: 3.869 ±(99.9%) 0.003 ms/op
Iteration   2: 3.991 ±(99.9%) 0.004 ms/op
Iteration   3: 4.080 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.980 ±(99.9%) 1.931 ms/op [Average]
  (min, avg, max) = (3.869, 3.980, 4.080), stdev = 0.106
  CI (99.9%): [2.048, 5.911] (assumes normal distribution)


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
# Warmup Iteration   1: 6.340 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.687 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.047 ±(99.9%) 0.024 ms/op
Iteration   1: 4.997 ±(99.9%) 0.012 ms/op
Iteration   2: 4.754 ±(99.9%) 0.009 ms/op
Iteration   3: 4.954 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.902 ±(99.9%) 2.367 ms/op [Average]
  (min, avg, max) = (4.754, 4.902, 4.997), stdev = 0.130
  CI (99.9%): [2.535, 7.269] (assumes normal distribution)


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
# Warmup Iteration   1: 5.282 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.010 ms/op
Iteration   1: 3.733 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 15.036 ms/op
                 createUser·p1.00:   15.696 ms/op

Iteration   2: 3.814 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.194 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  12.612 ms/op
                 createUser·p0.9999: 26.595 ms/op
                 createUser·p1.00:   26.870 ms/op

Iteration   3: 3.823 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 253131
  mean =      3.790 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4648 
    [ 2.500,  5.000) = 235403 
    [ 5.000,  7.500) = 11957 
    [ 7.500, 10.000) = 870 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     10.006 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     26.820 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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
# Warmup Iteration   1: 4.797 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.622 ±(99.9%) 0.008 ms/op
Iteration   1: 3.590 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   6.122 ms/op
                 existUser·p0.999:  11.778 ms/op
                 existUser·p0.9999: 21.430 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   2: 3.547 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  8.602 ms/op
                 existUser·p0.9999: 15.335 ms/op
                 existUser·p1.00:   16.417 ms/op

Iteration   3: 3.511 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  9.080 ms/op
                 existUser·p0.9999: 18.554 ms/op
                 existUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270522
  mean =      3.549 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8172 
    [ 2.500,  5.000) = 255642 
    [ 5.000,  7.500) = 6100 
    [ 7.500, 10.000) = 371 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     20.804 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 5.700 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.280 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.011 ms/op
Iteration   1: 3.876 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  12.829 ms/op
                 getUser·p0.9999: 14.709 ms/op
                 getUser·p1.00:   15.843 ms/op

Iteration   2: 3.934 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.760 ms/op
                 getUser·p0.95:   5.177 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  11.088 ms/op
                 getUser·p0.9999: 17.817 ms/op
                 getUser·p1.00:   18.153 ms/op

Iteration   3: 3.853 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  9.192 ms/op
                 getUser·p0.9999: 21.224 ms/op
                 getUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 246777
  mean =      3.888 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4028 
    [ 2.500,  5.000) = 227956 
    [ 5.000,  7.500) = 13497 
    [ 7.500, 10.000) = 931 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     11.207 ms/op
     p(99.9900) =     20.326 ms/op
     p(99.9990) =     21.974 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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
# Warmup Iteration   1: 5.707 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.438 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.942 ±(99.9%) 0.014 ms/op
Iteration   1: 4.965 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.480 ms/op
                 listUser·p0.95:   7.406 ms/op
                 listUser·p0.99:   9.469 ms/op
                 listUser·p0.999:  16.099 ms/op
                 listUser·p0.9999: 18.499 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   2: 4.827 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.915 ms/op
                 listUser·p0.95:   6.734 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  21.366 ms/op
                 listUser·p0.9999: 30.179 ms/op
                 listUser·p1.00:   32.080 ms/op

Iteration   3: 4.918 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.647 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   6.218 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  20.545 ms/op
                 listUser·p0.9999: 24.215 ms/op
                 listUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 195664
  mean =      4.903 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 216 
    [ 2.500,  5.000) = 134609 
    [ 5.000,  7.500) = 53963 
    [ 7.500, 10.000) = 5964 
    [10.000, 12.500) = 598 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.226 ms/op
     p(95.0000) =      7.070 ms/op
     p(99.0000) =      9.028 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     29.618 ms/op
     p(99.9990) =     31.672 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.277 ± 3.963  ops/ms
ClientGrpc.existUser                       thrpt       3   9.044 ± 1.521  ops/ms
ClientGrpc.getUser                         thrpt       3   8.500 ± 4.417  ops/ms
ClientGrpc.listUser                        thrpt       3   6.340 ± 1.271  ops/ms
ClientGrpc.createUser                       avgt       3   3.755 ± 0.594   ms/op
ClientGrpc.existUser                        avgt       3   3.627 ± 1.046   ms/op
ClientGrpc.getUser                          avgt       3   3.980 ± 1.931   ms/op
ClientGrpc.listUser                         avgt       3   4.902 ± 2.367   ms/op
ClientGrpc.createUser                     sample  253131   3.790 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.904           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.022           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.529           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.006           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.083           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.870           ms/op
ClientGrpc.existUser                      sample  270522   3.549 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.809           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.579           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.702           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.355           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.804           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.003           ms/op
ClientGrpc.getUser                        sample  246777   3.888 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.654           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.710           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.112           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.578           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.207           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.326           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.675           ms/op
ClientGrpc.listUser                       sample  195664   4.903 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.922           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.028           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.481           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.618           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.080           ms/op
