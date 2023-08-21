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
# Warmup Iteration   1: 3.175 ops/ms
# Warmup Iteration   2: 7.133 ops/ms
# Warmup Iteration   3: 7.989 ops/ms
Iteration   1: 8.421 ops/ms
Iteration   2: 8.521 ops/ms
Iteration   3: 8.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.509 ±(99.9%) 1.502 ops/ms [Average]
  (min, avg, max) = (8.421, 8.509, 8.584), stdev = 0.082
  CI (99.9%): [7.007, 10.011] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.717 ops/ms
# Warmup Iteration   2: 8.859 ops/ms
# Warmup Iteration   3: 9.088 ops/ms
Iteration   1: 9.416 ops/ms
Iteration   2: 9.134 ops/ms
Iteration   3: 9.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.241 ±(99.9%) 2.789 ops/ms [Average]
  (min, avg, max) = (9.134, 9.241, 9.416), stdev = 0.153
  CI (99.9%): [6.452, 12.031] (assumes normal distribution)


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
# Warmup Iteration   1: 5.255 ops/ms
# Warmup Iteration   2: 7.977 ops/ms
# Warmup Iteration   3: 8.401 ops/ms
Iteration   1: 8.182 ops/ms
Iteration   2: 8.575 ops/ms
Iteration   3: 8.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.462 ±(99.9%) 4.459 ops/ms [Average]
  (min, avg, max) = (8.182, 8.462, 8.630), stdev = 0.244
  CI (99.9%): [4.003, 12.922] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.027 ops/ms
# Warmup Iteration   2: 6.266 ops/ms
# Warmup Iteration   3: 6.430 ops/ms
Iteration   1: 6.462 ops/ms
Iteration   2: 6.638 ops/ms
Iteration   3: 6.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.604 ±(99.9%) 2.350 ops/ms [Average]
  (min, avg, max) = (6.462, 6.604, 6.713), stdev = 0.129
  CI (99.9%): [4.255, 8.954] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.928 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.007 ms/op
Iteration   1: 3.786 ±(99.9%) 0.005 ms/op
Iteration   2: 3.750 ±(99.9%) 0.003 ms/op
Iteration   3: 3.663 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.733 ±(99.9%) 1.152 ms/op [Average]
  (min, avg, max) = (3.663, 3.733, 3.786), stdev = 0.063
  CI (99.9%): [2.582, 4.885] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.087 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.004 ms/op
Iteration   1: 3.461 ±(99.9%) 0.005 ms/op
Iteration   2: 3.503 ±(99.9%) 0.004 ms/op
Iteration   3: 3.512 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.492 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (3.461, 3.492, 3.512), stdev = 0.027
  CI (99.9%): [2.996, 3.988] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.319 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.005 ms/op
Iteration   1: 3.803 ±(99.9%) 0.007 ms/op
Iteration   2: 3.752 ±(99.9%) 0.004 ms/op
Iteration   3: 3.757 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.771 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (3.752, 3.771, 3.803), stdev = 0.028
  CI (99.9%): [3.260, 4.282] (assumes normal distribution)


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
# Warmup Iteration   1: 6.226 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 5.209 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.811 ±(99.9%) 0.015 ms/op
Iteration   1: 4.776 ±(99.9%) 0.019 ms/op
Iteration   2: 4.679 ±(99.9%) 0.012 ms/op
Iteration   3: 4.714 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.723 ±(99.9%) 0.893 ms/op [Average]
  (min, avg, max) = (4.679, 4.723, 4.776), stdev = 0.049
  CI (99.9%): [3.830, 5.616] (assumes normal distribution)


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
# Warmup Iteration   1: 5.494 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.732 ±(99.9%) 0.011 ms/op
Iteration   1: 3.660 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  10.938 ms/op
                 createUser·p0.9999: 19.800 ms/op
                 createUser·p1.00:   20.316 ms/op

Iteration   2: 3.620 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   3.539 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   7.133 ms/op
                 createUser·p0.999:  12.245 ms/op
                 createUser·p0.9999: 22.026 ms/op
                 createUser·p1.00:   22.479 ms/op

Iteration   3: 3.714 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.644 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.666 ms/op
                 createUser·p0.95:   5.210 ms/op
                 createUser·p0.99:   7.692 ms/op
                 createUser·p0.999:  13.091 ms/op
                 createUser·p0.9999: 23.704 ms/op
                 createUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261932
  mean =      3.664 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12990 
    [ 2.500,  5.000) = 236164 
    [ 5.000,  7.500) = 10545 
    [ 7.500, 10.000) = 1669 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     12.455 ms/op
     p(99.9900) =     22.997 ms/op
     p(99.9990) =     24.306 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 4.991 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.010 ms/op
Iteration   1: 3.482 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   4.022 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  10.125 ms/op
                 existUser·p0.9999: 14.385 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   2: 3.391 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   6.283 ms/op
                 existUser·p0.999:  9.545 ms/op
                 existUser·p0.9999: 14.902 ms/op
                 existUser·p1.00:   16.187 ms/op

Iteration   3: 3.473 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  8.631 ms/op
                 existUser·p0.9999: 19.005 ms/op
                 existUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 278533
  mean =      3.448 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 490 
    [ 1.250,  2.500) = 10329 
    [ 2.500,  3.750) = 208761 
    [ 3.750,  5.000) = 52205 
    [ 5.000,  6.250) = 4429 
    [ 6.250,  7.500) = 1269 
    [ 7.500,  8.750) = 612 
    [ 8.750, 10.000) = 241 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 79 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.994 ms/op
     p(99.9000) =      9.445 ms/op
     p(99.9900) =     18.781 ms/op
     p(99.9990) =     19.380 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 5.654 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 3.983 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.010 ms/op
Iteration   1: 3.912 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.899 ms/op
                 getUser·p0.95:   5.464 ms/op
                 getUser·p0.99:   7.649 ms/op
                 getUser·p0.999:  11.248 ms/op
                 getUser·p0.9999: 15.234 ms/op
                 getUser·p1.00:   15.434 ms/op

Iteration   2: 3.769 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.906 ms/op
                 getUser·p0.999:  14.241 ms/op
                 getUser·p0.9999: 18.465 ms/op
                 getUser·p1.00:   18.809 ms/op

Iteration   3: 3.742 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.467 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  11.991 ms/op
                 getUser·p0.9999: 34.079 ms/op
                 getUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 252122
  mean =      3.806 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6248 
    [ 2.500,  5.000) = 230877 
    [ 5.000,  7.500) = 12875 
    [ 7.500, 10.000) = 1661 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     11.796 ms/op
     p(99.9900) =     33.751 ms/op
     p(99.9990) =     36.239 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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
# Warmup Iteration   1: 5.754 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.153 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.771 ±(99.9%) 0.017 ms/op
Iteration   1: 4.866 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.660 ms/op
                 listUser·p0.95:   7.447 ms/op
                 listUser·p0.99:   9.437 ms/op
                 listUser·p0.999:  19.956 ms/op
                 listUser·p0.9999: 23.616 ms/op
                 listUser·p1.00:   25.559 ms/op

Iteration   2: 4.830 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.373 ms/op
                 listUser·p0.95:   7.206 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  19.726 ms/op
                 listUser·p0.9999: 30.650 ms/op
                 listUser·p1.00:   32.408 ms/op

Iteration   3: 4.870 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.636 ms/op
                 listUser·p0.95:   7.438 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  19.503 ms/op
                 listUser·p0.9999: 24.964 ms/op
                 listUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197823
  mean =      4.855 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 941 
    [ 2.500,  5.000) = 135239 
    [ 5.000,  7.500) = 52880 
    [ 7.500, 10.000) = 7453 
    [10.000, 12.500) = 748 
    [12.500, 15.000) = 244 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      6.562 ms/op
     p(95.0000) =      7.373 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     19.726 ms/op
     p(99.9900) =     30.226 ms/op
     p(99.9990) =     31.093 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.509 ± 1.502  ops/ms
ClientGrpc.existUser                       thrpt       3   9.241 ± 2.789  ops/ms
ClientGrpc.getUser                         thrpt       3   8.462 ± 4.459  ops/ms
ClientGrpc.listUser                        thrpt       3   6.604 ± 2.350  ops/ms
ClientGrpc.createUser                       avgt       3   3.733 ± 1.152   ms/op
ClientGrpc.existUser                        avgt       3   3.492 ± 0.496   ms/op
ClientGrpc.getUser                          avgt       3   3.771 ± 0.511   ms/op
ClientGrpc.listUser                         avgt       3   4.723 ± 0.893   ms/op
ClientGrpc.createUser                     sample  261932   3.664 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.644           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.981           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.234           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.455           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.997           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.347           ms/op
ClientGrpc.existUser                      sample  278533   3.448 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.805           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.067           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.994           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.445           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.781           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.464           ms/op
ClientGrpc.getUser                        sample  252122   3.806 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.467           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.145           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.209           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.796           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.751           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          36.569           ms/op
ClientGrpc.listUser                       sample  197823   4.855 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.100           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.538           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.562           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.373           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.322           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.726           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.226           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.408           ms/op
