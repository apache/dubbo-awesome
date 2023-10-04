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
# Warmup Iteration   1: 3.641 ops/ms
# Warmup Iteration   2: 8.151 ops/ms
# Warmup Iteration   3: 9.544 ops/ms
Iteration   1: 10.184 ops/ms
Iteration   2: 10.093 ops/ms
Iteration   3: 10.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.192 ±(99.9%) 1.880 ops/ms [Average]
  (min, avg, max) = (10.093, 10.192, 10.298), stdev = 0.103
  CI (99.9%): [8.312, 12.071] (assumes normal distribution)


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
# Warmup Iteration   1: 7.052 ops/ms
# Warmup Iteration   2: 10.200 ops/ms
# Warmup Iteration   3: 10.743 ops/ms
Iteration   1: 10.763 ops/ms
Iteration   2: 10.775 ops/ms
Iteration   3: 10.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.714 ±(99.9%) 1.747 ops/ms [Average]
  (min, avg, max) = (10.604, 10.714, 10.775), stdev = 0.096
  CI (99.9%): [8.967, 12.461] (assumes normal distribution)


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
# Warmup Iteration   1: 6.554 ops/ms
# Warmup Iteration   2: 9.595 ops/ms
# Warmup Iteration   3: 9.921 ops/ms
Iteration   1: 9.973 ops/ms
Iteration   2: 10.229 ops/ms
Iteration   3: 10.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.114 ±(99.9%) 2.368 ops/ms [Average]
  (min, avg, max) = (9.973, 10.114, 10.229), stdev = 0.130
  CI (99.9%): [7.747, 12.482] (assumes normal distribution)


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
# Warmup Iteration   1: 5.359 ops/ms
# Warmup Iteration   2: 7.349 ops/ms
# Warmup Iteration   3: 7.688 ops/ms
Iteration   1: 7.874 ops/ms
Iteration   2: 7.912 ops/ms
Iteration   3: 7.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.926 ±(99.9%) 1.092 ops/ms [Average]
  (min, avg, max) = (7.874, 7.926, 7.991), stdev = 0.060
  CI (99.9%): [6.833, 9.018] (assumes normal distribution)


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
# Warmup Iteration   1: 4.372 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.350 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.004 ms/op
Iteration   1: 3.195 ±(99.9%) 0.006 ms/op
Iteration   2: 3.148 ±(99.9%) 0.004 ms/op
Iteration   3: 3.132 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.159 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (3.132, 3.159, 3.195), stdev = 0.033
  CI (99.9%): [2.557, 3.761] (assumes normal distribution)


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
# Warmup Iteration   1: 4.171 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.004 ms/op
Iteration   1: 2.951 ±(99.9%) 0.004 ms/op
Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
Iteration   3: 3.029 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.000 ±(99.9%) 0.774 ms/op [Average]
  (min, avg, max) = (2.951, 3.000, 3.029), stdev = 0.042
  CI (99.9%): [2.226, 3.774] (assumes normal distribution)


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
# Warmup Iteration   1: 4.399 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.003 ms/op
Iteration   1: 3.201 ±(99.9%) 0.004 ms/op
Iteration   2: 3.151 ±(99.9%) 0.003 ms/op
Iteration   3: 3.149 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.167 ±(99.9%) 0.533 ms/op [Average]
  (min, avg, max) = (3.149, 3.167, 3.201), stdev = 0.029
  CI (99.9%): [2.634, 3.700] (assumes normal distribution)


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
# Warmup Iteration   1: 5.224 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.010 ms/op
Iteration   1: 3.994 ±(99.9%) 0.013 ms/op
Iteration   2: 3.962 ±(99.9%) 0.011 ms/op
Iteration   3: 4.014 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.990 ±(99.9%) 0.483 ms/op [Average]
  (min, avg, max) = (3.962, 3.990, 4.014), stdev = 0.026
  CI (99.9%): [3.507, 4.473] (assumes normal distribution)


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
# Warmup Iteration   1: 4.331 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.007 ms/op
Iteration   1: 3.182 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  15.252 ms/op
                 createUser·p0.9999: 27.197 ms/op
                 createUser·p1.00:   28.606 ms/op

Iteration   2: 3.159 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  15.794 ms/op
                 createUser·p0.9999: 30.858 ms/op
                 createUser·p1.00:   32.571 ms/op

Iteration   3: 3.063 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.308 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   5.202 ms/op
                 createUser·p0.999:  10.360 ms/op
                 createUser·p0.9999: 22.714 ms/op
                 createUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306609
  mean =      3.134 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20255 
    [ 2.500,  5.000) = 281736 
    [ 5.000,  7.500) = 3575 
    [ 7.500, 10.000) = 666 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.308 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     12.399 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     32.401 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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
# Warmup Iteration   1: 4.143 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.007 ms/op
Iteration   1: 3.001 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  10.878 ms/op
                 existUser·p0.9999: 19.770 ms/op
                 existUser·p1.00:   20.775 ms/op

Iteration   2: 3.030 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  8.920 ms/op
                 existUser·p0.9999: 14.604 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   3: 2.941 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.211 ms/op
                 existUser·p0.999:  11.150 ms/op
                 existUser·p0.9999: 17.269 ms/op
                 existUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321121
  mean =      2.990 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31176 
    [ 2.500,  5.000) = 286428 
    [ 5.000,  7.500) = 2515 
    [ 7.500, 10.000) = 663 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =     10.453 ms/op
     p(99.9900) =     16.362 ms/op
     p(99.9990) =     20.616 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 4.307 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
Iteration   1: 3.199 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   5.251 ms/op
                 getUser·p0.999:  10.193 ms/op
                 getUser·p0.9999: 24.543 ms/op
                 getUser·p1.00:   25.199 ms/op

Iteration   2: 3.081 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  12.198 ms/op
                 getUser·p0.9999: 22.564 ms/op
                 getUser·p1.00:   35.258 ms/op

Iteration   3: 3.146 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  8.071 ms/op
                 getUser·p0.9999: 24.341 ms/op
                 getUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305529
  mean =      3.141 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17740 
    [ 2.500,  5.000) = 284014 
    [ 5.000,  7.500) = 2996 
    [ 7.500, 10.000) = 419 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.024 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     11.092 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     34.144 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 5.734 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.224 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.011 ms/op
Iteration   1: 4.092 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.454 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  13.836 ms/op
                 listUser·p0.9999: 24.889 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   2: 3.990 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  16.835 ms/op
                 listUser·p0.9999: 23.624 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   3: 4.073 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.812 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.532 ms/op
                 listUser·p0.999:  16.699 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237247
  mean =      4.051 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1965 
    [ 2.500,  5.000) = 213422 
    [ 5.000,  7.500) = 19452 
    [ 7.500, 10.000) = 1695 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 226 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     16.069 ms/op
     p(99.9900) =     23.307 ms/op
     p(99.9990) =     26.026 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.192 ± 1.880  ops/ms
ClientGrpc.existUser                       thrpt       3  10.714 ± 1.747  ops/ms
ClientGrpc.getUser                         thrpt       3  10.114 ± 2.368  ops/ms
ClientGrpc.listUser                        thrpt       3   7.926 ± 1.092  ops/ms
ClientGrpc.createUser                       avgt       3   3.159 ± 0.602   ms/op
ClientGrpc.existUser                        avgt       3   3.000 ± 0.774   ms/op
ClientGrpc.getUser                          avgt       3   3.167 ± 0.533   ms/op
ClientGrpc.listUser                         avgt       3   3.990 ± 0.483   ms/op
ClientGrpc.createUser                     sample  306609   3.134 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.308           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.006           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.399           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.197           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.571           ms/op
ClientGrpc.existUser                      sample  321121   2.990 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.529           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.128           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.453           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.362           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.775           ms/op
ClientGrpc.getUser                        sample  305529   3.141 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.609           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.024           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.226           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.092           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.478           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.258           ms/op
ClientGrpc.listUser                       sample  237247   4.051 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.812           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.512           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.069           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.307           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.149           ms/op
