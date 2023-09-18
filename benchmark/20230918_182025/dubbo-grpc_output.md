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
# Warmup Iteration   1: 4.313 ops/ms
# Warmup Iteration   2: 8.587 ops/ms
# Warmup Iteration   3: 9.673 ops/ms
Iteration   1: 10.036 ops/ms
Iteration   2: 10.138 ops/ms
Iteration   3: 10.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.092 ±(99.9%) 0.947 ops/ms [Average]
  (min, avg, max) = (10.036, 10.092, 10.138), stdev = 0.052
  CI (99.9%): [9.145, 11.039] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.336 ops/ms
# Warmup Iteration   2: 10.240 ops/ms
# Warmup Iteration   3: 10.513 ops/ms
Iteration   1: 10.749 ops/ms
Iteration   2: 10.734 ops/ms
Iteration   3: 10.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.741 ±(99.9%) 0.143 ops/ms [Average]
  (min, avg, max) = (10.734, 10.741, 10.749), stdev = 0.008
  CI (99.9%): [10.598, 10.883] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.034 ops/ms
# Warmup Iteration   2: 9.693 ops/ms
# Warmup Iteration   3: 10.157 ops/ms
Iteration   1: 10.345 ops/ms
Iteration   2: 10.151 ops/ms
Iteration   3: 10.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.167 ±(99.9%) 3.103 ops/ms [Average]
  (min, avg, max) = (10.006, 10.167, 10.345), stdev = 0.170
  CI (99.9%): [7.064, 13.271] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.537 ops/ms
# Warmup Iteration   2: 7.916 ops/ms
# Warmup Iteration   3: 8.151 ops/ms
Iteration   1: 8.165 ops/ms
Iteration   2: 8.149 ops/ms
Iteration   3: 8.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.213 ±(99.9%) 1.768 ops/ms [Average]
  (min, avg, max) = (8.149, 8.213, 8.324), stdev = 0.097
  CI (99.9%): [6.445, 9.981] (assumes normal distribution)


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
# Warmup Iteration   1: 4.237 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.001 ms/op
Iteration   1: 3.178 ±(99.9%) 0.010 ms/op
Iteration   2: 3.176 ±(99.9%) 0.011 ms/op
Iteration   3: 3.203 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.186 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (3.176, 3.186, 3.203), stdev = 0.015
  CI (99.9%): [2.908, 3.463] (assumes normal distribution)


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
# Warmup Iteration   1: 3.677 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.002 ms/op
Iteration   1: 3.021 ±(99.9%) 0.002 ms/op
Iteration   2: 3.048 ±(99.9%) 0.002 ms/op
Iteration   3: 3.016 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.029 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (3.016, 3.029, 3.048), stdev = 0.017
  CI (99.9%): [2.719, 3.339] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.913 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.269 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.002 ms/op
Iteration   1: 3.119 ±(99.9%) 0.003 ms/op
Iteration   2: 3.196 ±(99.9%) 0.002 ms/op
Iteration   3: 3.125 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.147 ±(99.9%) 0.777 ms/op [Average]
  (min, avg, max) = (3.119, 3.147, 3.196), stdev = 0.043
  CI (99.9%): [2.369, 3.924] (assumes normal distribution)


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
# Warmup Iteration   1: 4.598 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.009 ms/op
Iteration   1: 3.951 ±(99.9%) 0.024 ms/op
Iteration   2: 3.885 ±(99.9%) 0.034 ms/op
Iteration   3: 3.865 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.900 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (3.865, 3.900, 3.951), stdev = 0.045
  CI (99.9%): [3.074, 4.726] (assumes normal distribution)


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
# Warmup Iteration   1: 4.170 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.006 ms/op
Iteration   1: 3.191 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  10.813 ms/op
                 createUser·p0.9999: 13.040 ms/op
                 createUser·p1.00:   14.483 ms/op

Iteration   2: 3.252 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.856 ms/op
                 createUser·p0.9999: 14.467 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.174 ms/op
                 createUser·p0.999:  11.780 ms/op
                 createUser·p0.9999: 20.513 ms/op
                 createUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301717
  mean =      3.182 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6446 
    [ 2.500,  5.000) = 293391 
    [ 5.000,  7.500) = 1343 
    [ 7.500, 10.000) = 185 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =     10.741 ms/op
     p(99.9900) =     18.252 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 3.834 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.005 ms/op
Iteration   1: 2.999 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.608 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.348 ms/op
                 existUser·p0.999:  6.499 ms/op
                 existUser·p0.9999: 11.414 ms/op
                 existUser·p1.00:   12.796 ms/op

Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  6.971 ms/op
                 existUser·p0.9999: 12.920 ms/op
                 existUser·p1.00:   13.140 ms/op

Iteration   3: 3.040 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  6.221 ms/op
                 existUser·p0.9999: 15.991 ms/op
                 existUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316195
  mean =      3.034 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 887 
    [ 1.250,  2.500) = 16863 
    [ 2.500,  3.750) = 282361 
    [ 3.750,  5.000) = 14927 
    [ 5.000,  6.250) = 697 
    [ 6.250,  7.500) = 278 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.652 ms/op
     p(99.9900) =     14.376 ms/op
     p(99.9990) =     16.163 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 4.149 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
Iteration   1: 3.138 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.481 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  8.110 ms/op
                 getUser·p0.9999: 13.625 ms/op
                 getUser·p1.00:   13.894 ms/op

Iteration   2: 3.177 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  7.616 ms/op
                 getUser·p0.9999: 12.335 ms/op
                 getUser·p1.00:   12.747 ms/op

Iteration   3: 3.167 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.840 ms/op
                 getUser·p0.9999: 23.718 ms/op
                 getUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303645
  mean =      3.161 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9481 
    [ 2.500,  5.000) = 292288 
    [ 5.000,  7.500) = 1524 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      7.777 ms/op
     p(99.9900) =     22.705 ms/op
     p(99.9990) =     25.428 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 5.257 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.009 ms/op
Iteration   1: 3.905 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   6.431 ms/op
                 listUser·p0.999:  11.113 ms/op
                 listUser·p0.9999: 17.135 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   2: 3.873 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  12.827 ms/op
                 listUser·p0.9999: 16.353 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   3: 3.810 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  13.634 ms/op
                 listUser·p0.9999: 18.337 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248532
  mean =      3.862 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2631 
    [ 2.500,  3.750) = 111931 
    [ 3.750,  5.000) = 122076 
    [ 5.000,  6.250) = 8230 
    [ 6.250,  7.500) = 2837 
    [ 7.500,  8.750) = 257 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 132 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     12.993 ms/op
     p(99.9900) =     16.880 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.092 ± 0.947  ops/ms
ClientGrpc.existUser                       thrpt       3  10.741 ± 0.143  ops/ms
ClientGrpc.getUser                         thrpt       3  10.167 ± 3.103  ops/ms
ClientGrpc.listUser                        thrpt       3   8.213 ± 1.768  ops/ms
ClientGrpc.createUser                       avgt       3   3.186 ± 0.277   ms/op
ClientGrpc.existUser                        avgt       3   3.029 ± 0.310   ms/op
ClientGrpc.getUser                          avgt       3   3.147 ± 0.777   ms/op
ClientGrpc.listUser                         avgt       3   3.900 ± 0.826   ms/op
ClientGrpc.createUser                     sample  301717   3.182 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.696           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.741           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.252           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.546           ms/op
ClientGrpc.existUser                      sample  316195   3.034 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.608           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.652           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.376           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.302           ms/op
ClientGrpc.getUser                        sample  303645   3.161 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.481           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.928           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.777           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.705           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.657           ms/op
ClientGrpc.listUser                       sample  248532   3.862 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.343           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.325           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.463           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.993           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.880           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.874           ms/op
