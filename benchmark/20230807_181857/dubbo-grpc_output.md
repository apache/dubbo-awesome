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
# Warmup Iteration   1: 2.405 ops/ms
# Warmup Iteration   2: 6.333 ops/ms
# Warmup Iteration   3: 7.805 ops/ms
Iteration   1: 8.190 ops/ms
Iteration   2: 8.167 ops/ms
Iteration   3: 8.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.191 ±(99.9%) 0.448 ops/ms [Average]
  (min, avg, max) = (8.167, 8.191, 8.216), stdev = 0.025
  CI (99.9%): [7.743, 8.639] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.497 ops/ms
# Warmup Iteration   2: 8.222 ops/ms
# Warmup Iteration   3: 8.668 ops/ms
Iteration   1: 9.076 ops/ms
Iteration   2: 8.919 ops/ms
Iteration   3: 9.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.041 ±(99.9%) 1.982 ops/ms [Average]
  (min, avg, max) = (8.919, 9.041, 9.127), stdev = 0.109
  CI (99.9%): [7.059, 11.023] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.685 ops/ms
# Warmup Iteration   2: 7.379 ops/ms
# Warmup Iteration   3: 7.911 ops/ms
Iteration   1: 8.220 ops/ms
Iteration   2: 8.113 ops/ms
Iteration   3: 8.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.174 ±(99.9%) 1.002 ops/ms [Average]
  (min, avg, max) = (8.113, 8.174, 8.220), stdev = 0.055
  CI (99.9%): [7.172, 9.176] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.354 ops/ms
# Warmup Iteration   2: 5.777 ops/ms
# Warmup Iteration   3: 6.189 ops/ms
Iteration   1: 6.266 ops/ms
Iteration   2: 6.253 ops/ms
Iteration   3: 6.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.278 ±(99.9%) 0.587 ops/ms [Average]
  (min, avg, max) = (6.253, 6.278, 6.314), stdev = 0.032
  CI (99.9%): [5.691, 6.866] (assumes normal distribution)


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
# Warmup Iteration   1: 5.823 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.211 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.005 ms/op
Iteration   1: 4.009 ±(99.9%) 0.002 ms/op
Iteration   2: 3.939 ±(99.9%) 0.005 ms/op
Iteration   3: 3.898 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.948 ±(99.9%) 1.019 ms/op [Average]
  (min, avg, max) = (3.898, 3.948, 4.009), stdev = 0.056
  CI (99.9%): [2.929, 4.968] (assumes normal distribution)


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
# Warmup Iteration   1: 5.605 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.799 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.672 ±(99.9%) 0.003 ms/op
Iteration   1: 3.635 ±(99.9%) 0.003 ms/op
Iteration   2: 3.512 ±(99.9%) 0.004 ms/op
Iteration   3: 3.556 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.568 ±(99.9%) 1.136 ms/op [Average]
  (min, avg, max) = (3.512, 3.568, 3.635), stdev = 0.062
  CI (99.9%): [2.431, 4.704] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.972 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.013 ms/op
Iteration   1: 3.882 ±(99.9%) 0.005 ms/op
Iteration   2: 3.909 ±(99.9%) 0.004 ms/op
Iteration   3: 3.830 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.874 ±(99.9%) 0.726 ms/op [Average]
  (min, avg, max) = (3.830, 3.874, 3.909), stdev = 0.040
  CI (99.9%): [3.148, 4.599] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.029 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.552 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.020 ±(99.9%) 0.018 ms/op
Iteration   1: 4.973 ±(99.9%) 0.015 ms/op
Iteration   2: 4.912 ±(99.9%) 0.027 ms/op
Iteration   3: 4.902 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.929 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (4.902, 4.929, 4.973), stdev = 0.038
  CI (99.9%): [4.228, 5.629] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.863 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.152 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.012 ms/op
Iteration   1: 3.933 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.932 ms/op
                 createUser·p0.95:   5.366 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  11.747 ms/op
                 createUser·p0.9999: 17.518 ms/op
                 createUser·p1.00:   17.924 ms/op

Iteration   2: 3.995 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   5.278 ms/op
                 createUser·p0.99:   6.498 ms/op
                 createUser·p0.999:  10.158 ms/op
                 createUser·p0.9999: 17.596 ms/op
                 createUser·p1.00:   18.219 ms/op

Iteration   3: 3.931 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   6.586 ms/op
                 createUser·p0.999:  16.204 ms/op
                 createUser·p0.9999: 20.892 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 242855
  mean =      3.953 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5907 
    [ 2.500,  5.000) = 216516 
    [ 5.000,  7.500) = 19034 
    [ 7.500, 10.000) = 964 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     11.764 ms/op
     p(99.9900) =     18.308 ms/op
     p(99.9990) =     21.107 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 5.559 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.992 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.009 ms/op
Iteration   1: 3.667 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   6.182 ms/op
                 existUser·p0.999:  10.835 ms/op
                 existUser·p0.9999: 17.041 ms/op
                 existUser·p1.00:   17.760 ms/op

Iteration   2: 3.577 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   5.924 ms/op
                 existUser·p0.999:  11.017 ms/op
                 existUser·p0.9999: 17.148 ms/op
                 existUser·p1.00:   18.121 ms/op

Iteration   3: 3.612 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  16.012 ms/op
                 existUser·p0.9999: 25.105 ms/op
                 existUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 265438
  mean =      3.618 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10204 
    [ 2.500,  5.000) = 247022 
    [ 5.000,  7.500) = 6990 
    [ 7.500, 10.000) = 785 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     11.504 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.409 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.924 ±(99.9%) 0.011 ms/op
Iteration   1: 3.828 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   6.947 ms/op
                 getUser·p0.999:  13.623 ms/op
                 getUser·p0.9999: 15.629 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   2: 3.793 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  11.053 ms/op
                 getUser·p0.9999: 27.515 ms/op
                 getUser·p1.00:   27.918 ms/op

Iteration   3: 3.821 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  14.270 ms/op
                 getUser·p0.9999: 22.093 ms/op
                 getUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251720
  mean =      3.814 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12259 
    [ 2.500,  5.000) = 224895 
    [ 5.000,  7.500) = 12979 
    [ 7.500, 10.000) = 1027 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.111 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     26.837 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.574 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.518 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.154 ±(99.9%) 0.019 ms/op
Iteration   1: 5.207 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.563 ms/op
                 listUser·p0.50:   4.882 ms/op
                 listUser·p0.90:   6.963 ms/op
                 listUser·p0.95:   7.905 ms/op
                 listUser·p0.99:   10.207 ms/op
                 listUser·p0.999:  17.840 ms/op
                 listUser·p0.9999: 22.315 ms/op
                 listUser·p1.00:   22.643 ms/op

Iteration   2: 5.119 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   4.833 ms/op
                 listUser·p0.90:   6.873 ms/op
                 listUser·p0.95:   7.766 ms/op
                 listUser·p0.99:   9.896 ms/op
                 listUser·p0.999:  16.522 ms/op
                 listUser·p0.9999: 20.611 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   3: 5.126 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   6.578 ms/op
                 listUser·p0.95:   7.447 ms/op
                 listUser·p0.99:   9.716 ms/op
                 listUser·p0.999:  20.139 ms/op
                 listUser·p0.9999: 22.905 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 186553
  mean =      5.150 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 244 
    [ 2.500,  5.000) = 105817 
    [ 5.000,  7.500) = 69196 
    [ 7.500, 10.000) = 9459 
    [10.000, 12.500) = 1233 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      6.808 ms/op
     p(95.0000) =      7.717 ms/op
     p(99.0000) =      9.978 ms/op
     p(99.9000) =     17.953 ms/op
     p(99.9900) =     22.621 ms/op
     p(99.9990) =     23.438 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.191 ± 0.448  ops/ms
ClientGrpc.existUser                       thrpt       3   9.041 ± 1.982  ops/ms
ClientGrpc.getUser                         thrpt       3   8.174 ± 1.002  ops/ms
ClientGrpc.listUser                        thrpt       3   6.278 ± 0.587  ops/ms
ClientGrpc.createUser                       avgt       3   3.948 ± 1.019   ms/op
ClientGrpc.existUser                        avgt       3   3.568 ± 1.136   ms/op
ClientGrpc.getUser                          avgt       3   3.874 ± 0.726   ms/op
ClientGrpc.listUser                         avgt       3   4.929 ± 0.701   ms/op
ClientGrpc.createUser                     sample  242855   3.953 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.869           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.899           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.300           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.570           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.764           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.308           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.234           ms/op
ClientGrpc.existUser                      sample  265438   3.618 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.816           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.694           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.997           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.504           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.773           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.264           ms/op
ClientGrpc.getUser                        sample  251720   3.814 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.818           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.111           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.562           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.484           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.837           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.918           ms/op
ClientGrpc.listUser                       sample  186553   5.150 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.292           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.717           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.978           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.953           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.621           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.495           ms/op
