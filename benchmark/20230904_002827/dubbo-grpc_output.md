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
# Warmup Iteration   1: 3.961 ops/ms
# Warmup Iteration   2: 8.722 ops/ms
# Warmup Iteration   3: 9.750 ops/ms
Iteration   1: 10.200 ops/ms
Iteration   2: 10.224 ops/ms
Iteration   3: 10.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.306 ±(99.9%) 2.951 ops/ms [Average]
  (min, avg, max) = (10.200, 10.306, 10.492), stdev = 0.162
  CI (99.9%): [7.354, 13.257] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.536 ops/ms
# Warmup Iteration   2: 10.635 ops/ms
# Warmup Iteration   3: 10.874 ops/ms
Iteration   1: 11.004 ops/ms
Iteration   2: 11.158 ops/ms
Iteration   3: 11.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.056 ±(99.9%) 1.599 ops/ms [Average]
  (min, avg, max) = (11.004, 11.056, 11.158), stdev = 0.088
  CI (99.9%): [9.457, 12.656] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.378 ops/ms
# Warmup Iteration   2: 9.857 ops/ms
# Warmup Iteration   3: 10.538 ops/ms
Iteration   1: 10.373 ops/ms
Iteration   2: 10.491 ops/ms
Iteration   3: 10.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.455 ±(99.9%) 1.301 ops/ms [Average]
  (min, avg, max) = (10.373, 10.455, 10.501), stdev = 0.071
  CI (99.9%): [9.154, 11.757] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.027 ops/ms
# Warmup Iteration   2: 7.516 ops/ms
# Warmup Iteration   3: 7.725 ops/ms
Iteration   1: 8.023 ops/ms
Iteration   2: 7.970 ops/ms
Iteration   3: 7.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.985 ±(99.9%) 0.605 ops/ms [Average]
  (min, avg, max) = (7.963, 7.985, 8.023), stdev = 0.033
  CI (99.9%): [7.380, 8.590] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.492 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.003 ms/op
Iteration   1: 3.052 ±(99.9%) 0.002 ms/op
Iteration   2: 2.992 ±(99.9%) 0.002 ms/op
Iteration   3: 3.133 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.059 ±(99.9%) 1.289 ms/op [Average]
  (min, avg, max) = (2.992, 3.059, 3.133), stdev = 0.071
  CI (99.9%): [1.770, 4.348] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.918 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.004 ms/op
Iteration   1: 2.863 ±(99.9%) 0.003 ms/op
Iteration   2: 2.808 ±(99.9%) 0.003 ms/op
Iteration   3: 2.917 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.863 ±(99.9%) 0.998 ms/op [Average]
  (min, avg, max) = (2.808, 2.863, 2.917), stdev = 0.055
  CI (99.9%): [1.864, 3.861] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.141 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.009 ms/op
Iteration   1: 3.031 ±(99.9%) 0.003 ms/op
Iteration   2: 3.041 ±(99.9%) 0.005 ms/op
Iteration   3: 3.029 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.034 ±(99.9%) 0.117 ms/op [Average]
  (min, avg, max) = (3.029, 3.034, 3.041), stdev = 0.006
  CI (99.9%): [2.917, 3.150] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.433 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.337 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.014 ms/op
Iteration   1: 4.027 ±(99.9%) 0.015 ms/op
Iteration   2: 4.066 ±(99.9%) 0.011 ms/op
Iteration   3: 4.035 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.043 ±(99.9%) 0.378 ms/op [Average]
  (min, avg, max) = (4.027, 4.043, 4.066), stdev = 0.021
  CI (99.9%): [3.665, 4.420] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.223 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.006 ms/op
Iteration   1: 3.102 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  9.552 ms/op
                 createUser·p0.9999: 19.585 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  7.569 ms/op
                 createUser·p0.9999: 18.366 ms/op
                 createUser·p1.00:   20.316 ms/op

Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  11.169 ms/op
                 createUser·p0.9999: 20.447 ms/op
                 createUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312666
  mean =      3.069 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20320 
    [ 2.500,  5.000) = 290193 
    [ 5.000,  7.500) = 1611 
    [ 7.500, 10.000) = 266 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      9.131 ms/op
     p(99.9900) =     20.021 ms/op
     p(99.9990) =     20.541 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.075 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
Iteration   1: 2.918 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  7.415 ms/op
                 existUser·p0.9999: 12.633 ms/op
                 existUser·p1.00:   12.943 ms/op

Iteration   2: 2.950 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  8.782 ms/op
                 existUser·p0.9999: 14.816 ms/op
                 existUser·p1.00:   15.155 ms/op

Iteration   3: 2.911 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  8.947 ms/op
                 existUser·p0.9999: 19.628 ms/op
                 existUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328061
  mean =      2.926 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35997 
    [ 2.500,  5.000) = 290374 
    [ 5.000,  7.500) = 1182 
    [ 7.500, 10.000) = 257 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.364 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     20.045 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.445 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.006 ms/op
Iteration   1: 3.067 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.606 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  7.668 ms/op
                 getUser·p0.9999: 16.131 ms/op
                 getUser·p1.00:   16.663 ms/op

Iteration   2: 3.062 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  8.804 ms/op
                 getUser·p0.9999: 20.251 ms/op
                 getUser·p1.00:   20.546 ms/op

Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  7.173 ms/op
                 getUser·p0.9999: 21.713 ms/op
                 getUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312448
  mean =      3.070 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20159 
    [ 2.500,  5.000) = 289938 
    [ 5.000,  7.500) = 1989 
    [ 7.500, 10.000) = 174 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =      7.938 ms/op
     p(99.9900) =     20.972 ms/op
     p(99.9990) =     22.233 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 4.815 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.011 ms/op
Iteration   1: 3.970 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  14.565 ms/op
                 listUser·p0.9999: 16.995 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   2: 4.061 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.771 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  14.406 ms/op
                 listUser·p0.9999: 27.796 ms/op
                 listUser·p1.00:   28.541 ms/op

Iteration   3: 4.056 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  16.174 ms/op
                 listUser·p0.9999: 27.336 ms/op
                 listUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238279
  mean =      4.029 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3000 
    [ 2.500,  5.000) = 209213 
    [ 5.000,  7.500) = 24284 
    [ 7.500, 10.000) = 1251 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 96 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     15.434 ms/op
     p(99.9900) =     27.263 ms/op
     p(99.9990) =     28.342 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.306 ± 2.951  ops/ms
ClientGrpc.existUser                       thrpt       3  11.056 ± 1.599  ops/ms
ClientGrpc.getUser                         thrpt       3  10.455 ± 1.301  ops/ms
ClientGrpc.listUser                        thrpt       3   7.985 ± 0.605  ops/ms
ClientGrpc.createUser                       avgt       3   3.059 ± 1.289   ms/op
ClientGrpc.existUser                        avgt       3   2.863 ± 0.998   ms/op
ClientGrpc.getUser                          avgt       3   3.034 ± 0.117   ms/op
ClientGrpc.listUser                         avgt       3   4.043 ± 0.378   ms/op
ClientGrpc.createUser                     sample  312666   3.069 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.748           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.131           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.021           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.463           ms/op
ClientGrpc.existUser                      sample  328061   2.926 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.537           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.364           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.990           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.152           ms/op
ClientGrpc.getUser                        sample  312448   3.070 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.606           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.841           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.938           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.972           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.413           ms/op
ClientGrpc.listUser                       sample  238279   4.029 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.771           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.209           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.434           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.263           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.541           ms/op
