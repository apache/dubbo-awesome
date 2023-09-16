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
# Warmup Iteration   1: 3.693 ops/ms
# Warmup Iteration   2: 8.445 ops/ms
# Warmup Iteration   3: 9.398 ops/ms
Iteration   1: 9.827 ops/ms
Iteration   2: 9.757 ops/ms
Iteration   3: 10.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.871 ±(99.9%) 2.586 ops/ms [Average]
  (min, avg, max) = (9.757, 9.871, 10.030), stdev = 0.142
  CI (99.9%): [7.285, 12.457] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.895 ops/ms
# Warmup Iteration   2: 10.103 ops/ms
# Warmup Iteration   3: 10.186 ops/ms
Iteration   1: 10.518 ops/ms
Iteration   2: 10.392 ops/ms
Iteration   3: 10.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.485 ±(99.9%) 1.480 ops/ms [Average]
  (min, avg, max) = (10.392, 10.485, 10.544), stdev = 0.081
  CI (99.9%): [9.005, 11.965] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.249 ops/ms
# Warmup Iteration   2: 9.641 ops/ms
# Warmup Iteration   3: 10.134 ops/ms
Iteration   1: 9.956 ops/ms
Iteration   2: 10.091 ops/ms
Iteration   3: 9.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.945 ±(99.9%) 2.759 ops/ms [Average]
  (min, avg, max) = (9.789, 9.945, 10.091), stdev = 0.151
  CI (99.9%): [7.186, 12.705] (assumes normal distribution)


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
# Warmup Iteration   1: 5.544 ops/ms
# Warmup Iteration   2: 7.847 ops/ms
# Warmup Iteration   3: 7.869 ops/ms
Iteration   1: 8.016 ops/ms
Iteration   2: 7.901 ops/ms
Iteration   3: 8.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.042 ±(99.9%) 2.839 ops/ms [Average]
  (min, avg, max) = (7.901, 8.042, 8.209), stdev = 0.156
  CI (99.9%): [5.203, 10.881] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.557 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.377 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.002 ms/op
Iteration   1: 3.138 ±(99.9%) 0.015 ms/op
Iteration   2: 3.277 ±(99.9%) 0.002 ms/op
Iteration   3: 3.269 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.228 ±(99.9%) 1.425 ms/op [Average]
  (min, avg, max) = (3.138, 3.228, 3.277), stdev = 0.078
  CI (99.9%): [1.802, 4.653] (assumes normal distribution)


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
# Warmup Iteration   1: 4.335 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.336 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.001 ms/op
Iteration   1: 3.133 ±(99.9%) 0.001 ms/op
Iteration   2: 3.069 ±(99.9%) 0.002 ms/op
Iteration   3: 3.021 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.074 ±(99.9%) 1.028 ms/op [Average]
  (min, avg, max) = (3.021, 3.074, 3.133), stdev = 0.056
  CI (99.9%): [2.046, 4.103] (assumes normal distribution)


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
# Warmup Iteration   1: 4.619 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.002 ms/op
Iteration   1: 3.144 ±(99.9%) 0.002 ms/op
Iteration   2: 3.111 ±(99.9%) 0.002 ms/op
Iteration   3: 3.216 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.157 ±(99.9%) 0.978 ms/op [Average]
  (min, avg, max) = (3.111, 3.157, 3.216), stdev = 0.054
  CI (99.9%): [2.179, 4.135] (assumes normal distribution)


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
# Warmup Iteration   1: 6.432 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.034 ms/op
Iteration   1: 3.889 ±(99.9%) 0.016 ms/op
Iteration   2: 3.967 ±(99.9%) 0.023 ms/op
Iteration   3: 3.951 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.936 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (3.889, 3.936, 3.967), stdev = 0.041
  CI (99.9%): [3.186, 4.686] (assumes normal distribution)


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
# Warmup Iteration   1: 4.522 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.301 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.006 ms/op
Iteration   1: 3.204 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  6.686 ms/op
                 createUser·p0.9999: 17.400 ms/op
                 createUser·p1.00:   18.088 ms/op

Iteration   2: 3.179 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  8.138 ms/op
                 createUser·p0.9999: 18.151 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   3: 3.226 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.375 ms/op
                 createUser·p0.9999: 19.104 ms/op
                 createUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 299833
  mean =      3.203 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 6690 
    [ 2.500,  3.750) = 257832 
    [ 3.750,  5.000) = 33514 
    [ 5.000,  6.250) = 863 
    [ 6.250,  7.500) = 472 
    [ 7.500,  8.750) = 115 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 64 
    [17.500, 18.750) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.710 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 4.225 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.005 ms/op
Iteration   1: 3.115 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.638 ms/op
                 existUser·p0.999:  7.749 ms/op
                 existUser·p0.9999: 12.550 ms/op
                 existUser·p1.00:   12.911 ms/op

Iteration   2: 2.969 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.026 ms/op
                 existUser·p0.999:  7.013 ms/op
                 existUser·p0.9999: 13.921 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   3: 2.951 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  8.643 ms/op
                 existUser·p0.9999: 14.210 ms/op
                 existUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318886
  mean =      3.010 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1082 
    [ 1.250,  2.500) = 21610 
    [ 2.500,  3.750) = 281282 
    [ 3.750,  5.000) = 13291 
    [ 5.000,  6.250) = 821 
    [ 6.250,  7.500) = 415 
    [ 7.500,  8.750) = 149 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.809 ms/op
     p(99.9900) =     13.961 ms/op
     p(99.9990) =     14.589 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 4.409 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.006 ms/op
Iteration   1: 3.164 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.580 ms/op
                 getUser·p0.999:  7.511 ms/op
                 getUser·p0.9999: 12.889 ms/op
                 getUser·p1.00:   13.255 ms/op

Iteration   2: 3.124 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  9.586 ms/op
                 getUser·p0.9999: 14.258 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   3: 3.151 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.468 ms/op
                 getUser·p0.9999: 27.225 ms/op
                 getUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305016
  mean =      3.146 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7478 
    [ 2.500,  5.000) = 295801 
    [ 5.000,  7.500) = 1420 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.594 ms/op
     p(99.9900) =     26.526 ms/op
     p(99.9990) =     27.522 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 5.154 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.009 ms/op
Iteration   1: 3.957 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.737 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.386 ms/op
                 listUser·p0.9999: 16.843 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   2: 3.977 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.640 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   6.749 ms/op
                 listUser·p0.999:  14.437 ms/op
                 listUser·p0.9999: 15.958 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   3: 3.906 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   6.651 ms/op
                 listUser·p0.999:  14.454 ms/op
                 listUser·p0.9999: 17.617 ms/op
                 listUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243127
  mean =      3.947 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 2419 
    [ 2.500,  3.750) = 91662 
    [ 3.750,  5.000) = 135658 
    [ 5.000,  6.250) = 7903 
    [ 6.250,  7.500) = 4434 
    [ 7.500,  8.750) = 379 
    [ 8.750, 10.000) = 200 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 120 
    [15.000, 16.250) = 118 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     14.086 ms/op
     p(99.9900) =     16.745 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.871 ± 2.586  ops/ms
ClientGrpc.existUser                       thrpt       3  10.485 ± 1.480  ops/ms
ClientGrpc.getUser                         thrpt       3   9.945 ± 2.759  ops/ms
ClientGrpc.listUser                        thrpt       3   8.042 ± 2.839  ops/ms
ClientGrpc.createUser                       avgt       3   3.228 ± 1.425   ms/op
ClientGrpc.existUser                        avgt       3   3.074 ± 1.028   ms/op
ClientGrpc.getUser                          avgt       3   3.157 ± 0.978   ms/op
ClientGrpc.listUser                         avgt       3   3.936 ± 0.750   ms/op
ClientGrpc.createUser                     sample  299833   3.203 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.679           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.154           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.710           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.383           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.399           ms/op
ClientGrpc.existUser                      sample  318886   3.010 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.725           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.809           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.961           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.877           ms/op
ClientGrpc.getUser                        sample  305016   3.146 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.819           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.594           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.526           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.623           ms/op
ClientGrpc.listUser                       sample  243127   3.947 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.737           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.424           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.086           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.745           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.186           ms/op
