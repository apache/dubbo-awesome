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
# Warmup Iteration   1: 2.342 ops/ms
# Warmup Iteration   2: 5.960 ops/ms
# Warmup Iteration   3: 7.642 ops/ms
Iteration   1: 7.667 ops/ms
Iteration   2: 7.841 ops/ms
Iteration   3: 7.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.823 ±(99.9%) 2.692 ops/ms [Average]
  (min, avg, max) = (7.667, 7.823, 7.961), stdev = 0.148
  CI (99.9%): [5.131, 10.515] (assumes normal distribution)


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
# Warmup Iteration   1: 4.863 ops/ms
# Warmup Iteration   2: 7.745 ops/ms
# Warmup Iteration   3: 8.305 ops/ms
Iteration   1: 8.527 ops/ms
Iteration   2: 8.466 ops/ms
Iteration   3: 8.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.444 ±(99.9%) 1.760 ops/ms [Average]
  (min, avg, max) = (8.338, 8.444, 8.527), stdev = 0.096
  CI (99.9%): [6.684, 10.204] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.427 ops/ms
# Warmup Iteration   2: 7.503 ops/ms
# Warmup Iteration   3: 7.831 ops/ms
Iteration   1: 7.733 ops/ms
Iteration   2: 7.934 ops/ms
Iteration   3: 8.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.913 ±(99.9%) 3.102 ops/ms [Average]
  (min, avg, max) = (7.733, 7.913, 8.072), stdev = 0.170
  CI (99.9%): [4.811, 11.015] (assumes normal distribution)


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
# Warmup Iteration   1: 3.985 ops/ms
# Warmup Iteration   2: 5.767 ops/ms
# Warmup Iteration   3: 6.374 ops/ms
Iteration   1: 6.251 ops/ms
Iteration   2: 6.223 ops/ms
Iteration   3: 6.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.315 ±(99.9%) 2.475 ops/ms [Average]
  (min, avg, max) = (6.223, 6.315, 6.471), stdev = 0.136
  CI (99.9%): [3.840, 8.790] (assumes normal distribution)


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
# Warmup Iteration   1: 5.966 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.293 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.026 ms/op
Iteration   1: 3.812 ±(99.9%) 0.007 ms/op
Iteration   2: 3.960 ±(99.9%) 0.003 ms/op
Iteration   3: 4.071 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.948 ±(99.9%) 2.368 ms/op [Average]
  (min, avg, max) = (3.812, 3.948, 4.071), stdev = 0.130
  CI (99.9%): [1.579, 6.316] (assumes normal distribution)


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
# Warmup Iteration   1: 6.086 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.773 ±(99.9%) 0.010 ms/op
Iteration   1: 3.874 ±(99.9%) 0.003 ms/op
Iteration   2: 3.757 ±(99.9%) 0.004 ms/op
Iteration   3: 3.607 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.746 ±(99.9%) 2.444 ms/op [Average]
  (min, avg, max) = (3.607, 3.746, 3.874), stdev = 0.134
  CI (99.9%): [1.302, 6.190] (assumes normal distribution)


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
# Warmup Iteration   1: 5.861 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.012 ms/op
Iteration   1: 3.940 ±(99.9%) 0.004 ms/op
Iteration   2: 4.026 ±(99.9%) 0.003 ms/op
Iteration   3: 3.917 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.961 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (3.917, 3.961, 4.026), stdev = 0.058
  CI (99.9%): [2.908, 5.015] (assumes normal distribution)


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
# Warmup Iteration   1: 7.336 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.444 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.136 ±(99.9%) 0.016 ms/op
Iteration   1: 5.050 ±(99.9%) 0.031 ms/op
Iteration   2: 5.132 ±(99.9%) 0.019 ms/op
Iteration   3: 5.070 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.084 ±(99.9%) 0.785 ms/op [Average]
  (min, avg, max) = (5.050, 5.084, 5.132), stdev = 0.043
  CI (99.9%): [4.299, 5.869] (assumes normal distribution)


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
# Warmup Iteration   1: 6.021 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.102 ±(99.9%) 0.014 ms/op
Iteration   1: 4.052 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   5.095 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   7.209 ms/op
                 createUser·p0.999:  13.240 ms/op
                 createUser·p0.9999: 22.807 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   2: 3.994 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   5.210 ms/op
                 createUser·p0.95:   5.718 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  12.039 ms/op
                 createUser·p0.9999: 26.280 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   3: 3.985 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   5.087 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   7.553 ms/op
                 createUser·p0.999:  16.567 ms/op
                 createUser·p0.9999: 25.491 ms/op
                 createUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 239261
  mean =      4.010 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6679 
    [ 2.500,  5.000) = 203948 
    [ 5.000,  7.500) = 26619 
    [ 7.500, 10.000) = 1316 
    [10.000, 12.500) = 409 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     13.271 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     26.509 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 6.177 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.011 ms/op
Iteration   1: 3.874 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.997 ms/op
                 existUser·p0.95:   5.464 ms/op
                 existUser·p0.99:   7.222 ms/op
                 existUser·p0.999:  10.977 ms/op
                 existUser·p0.9999: 21.627 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   2: 3.774 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.825 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   6.627 ms/op
                 existUser·p0.999:  10.886 ms/op
                 existUser·p0.9999: 18.645 ms/op
                 existUser·p1.00:   19.726 ms/op

Iteration   3: 3.913 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.825 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   6.808 ms/op
                 existUser·p0.999:  11.228 ms/op
                 existUser·p0.9999: 21.168 ms/op
                 existUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 249134
  mean =      3.853 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5750 
    [ 2.500,  5.000) = 222746 
    [ 5.000,  7.500) = 19021 
    [ 7.500, 10.000) = 1193 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     10.977 ms/op
     p(99.9900) =     21.201 ms/op
     p(99.9990) =     21.840 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 5.958 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.219 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.212 ±(99.9%) 0.015 ms/op
Iteration   1: 4.228 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   4.022 ms/op
                 getUser·p0.90:   5.530 ms/op
                 getUser·p0.95:   6.472 ms/op
                 getUser·p0.99:   9.470 ms/op
                 getUser·p0.999:  12.884 ms/op
                 getUser·p0.9999: 20.083 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   2: 4.031 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   5.136 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   7.421 ms/op
                 getUser·p0.999:  13.313 ms/op
                 getUser·p0.9999: 17.388 ms/op
                 getUser·p1.00:   19.726 ms/op

Iteration   3: 3.943 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.989 ms/op
                 getUser·p0.95:   5.407 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  9.203 ms/op
                 getUser·p0.9999: 20.454 ms/op
                 getUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 236188
  mean =      4.064 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7502 
    [ 2.500,  5.000) = 197861 
    [ 5.000,  7.500) = 27679 
    [ 7.500, 10.000) = 2366 
    [10.000, 12.500) = 514 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      8.069 ms/op
     p(99.9000) =     12.911 ms/op
     p(99.9900) =     19.751 ms/op
     p(99.9990) =     23.165 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 7.867 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.517 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.218 ±(99.9%) 0.017 ms/op
Iteration   1: 5.185 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   4.899 ms/op
                 listUser·p0.90:   6.750 ms/op
                 listUser·p0.95:   7.782 ms/op
                 listUser·p0.99:   10.256 ms/op
                 listUser·p0.999:  16.438 ms/op
                 listUser·p0.9999: 19.983 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   2: 5.087 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.808 ms/op
                 listUser·p0.95:   7.750 ms/op
                 listUser·p0.99:   9.814 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 22.469 ms/op
                 listUser·p1.00:   23.069 ms/op

Iteration   3: 5.073 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.661 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.701 ms/op
                 listUser·p0.95:   7.537 ms/op
                 listUser·p0.99:   9.568 ms/op
                 listUser·p0.999:  20.703 ms/op
                 listUser·p0.9999: 24.897 ms/op
                 listUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 187661
  mean =      5.115 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 349 
    [ 2.500,  5.000) = 106646 
    [ 5.000,  7.500) = 69792 
    [ 7.500, 10.000) = 9151 
    [10.000, 12.500) = 1153 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      4.841 ms/op
     p(90.0000) =      6.750 ms/op
     p(95.0000) =      7.684 ms/op
     p(99.0000) =      9.863 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     23.689 ms/op
     p(99.9990) =     27.340 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.823 ± 2.692  ops/ms
ClientGrpc.existUser                       thrpt       3   8.444 ± 1.760  ops/ms
ClientGrpc.getUser                         thrpt       3   7.913 ± 3.102  ops/ms
ClientGrpc.listUser                        thrpt       3   6.315 ± 2.475  ops/ms
ClientGrpc.createUser                       avgt       3   3.948 ± 2.368   ms/op
ClientGrpc.existUser                        avgt       3   3.746 ± 2.444   ms/op
ClientGrpc.getUser                          avgt       3   3.961 ± 1.054   ms/op
ClientGrpc.listUser                         avgt       3   5.084 ± 0.785   ms/op
ClientGrpc.createUser                     sample  239261   4.010 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.918           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.128           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.644           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.234           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.271           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.919           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.608           ms/op
ClientGrpc.existUser                      sample  249134   3.853 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.864           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.882           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.325           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.857           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.977           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.201           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.856           ms/op
ClientGrpc.getUser                        sample  236188   4.064 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.820           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.912           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.202           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.759           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.069           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.911           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.751           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.462           ms/op
ClientGrpc.listUser                       sample  187661   5.115 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.493           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.684           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.863           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.170           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.689           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.656           ms/op
