# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.236 ops/ms
# Warmup Iteration   2: 9.293 ops/ms
# Warmup Iteration   3: 10.235 ops/ms
Iteration   1: 10.276 ops/ms
Iteration   2: 10.207 ops/ms
Iteration   3: 10.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.304 ±(99.9%) 2.068 ops/ms [Average]
  (min, avg, max) = (10.207, 10.304, 10.429), stdev = 0.113
  CI (99.9%): [8.237, 12.372] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.400 ops/ms
# Warmup Iteration   2: 10.062 ops/ms
# Warmup Iteration   3: 10.629 ops/ms
Iteration   1: 10.558 ops/ms
Iteration   2: 10.848 ops/ms
Iteration   3: 10.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.690 ±(99.9%) 2.675 ops/ms [Average]
  (min, avg, max) = (10.558, 10.690, 10.848), stdev = 0.147
  CI (99.9%): [8.015, 13.365] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.042 ops/ms
# Warmup Iteration   2: 9.956 ops/ms
# Warmup Iteration   3: 9.991 ops/ms
Iteration   1: 10.303 ops/ms
Iteration   2: 10.196 ops/ms
Iteration   3: 10.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.268 ±(99.9%) 1.142 ops/ms [Average]
  (min, avg, max) = (10.196, 10.268, 10.306), stdev = 0.063
  CI (99.9%): [9.126, 11.410] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.351 ops/ms
# Warmup Iteration   2: 7.718 ops/ms
# Warmup Iteration   3: 7.747 ops/ms
Iteration   1: 8.018 ops/ms
Iteration   2: 8.058 ops/ms
Iteration   3: 7.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.012 ±(99.9%) 0.885 ops/ms [Average]
  (min, avg, max) = (7.961, 8.012, 8.058), stdev = 0.048
  CI (99.9%): [7.128, 8.897] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.340 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.003 ms/op
Iteration   1: 3.111 ±(99.9%) 0.011 ms/op
Iteration   2: 3.221 ±(99.9%) 0.002 ms/op
Iteration   3: 3.153 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.162 ±(99.9%) 1.006 ms/op [Average]
  (min, avg, max) = (3.111, 3.162, 3.221), stdev = 0.055
  CI (99.9%): [2.155, 4.168] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.960 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.002 ms/op
Iteration   1: 3.009 ±(99.9%) 0.002 ms/op
Iteration   2: 3.001 ±(99.9%) 0.002 ms/op
Iteration   3: 2.963 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.991 ±(99.9%) 0.450 ms/op [Average]
  (min, avg, max) = (2.963, 2.991, 3.009), stdev = 0.025
  CI (99.9%): [2.541, 3.441] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.288 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.007 ms/op
Iteration   1: 3.076 ±(99.9%) 0.007 ms/op
Iteration   2: 3.141 ±(99.9%) 0.001 ms/op
Iteration   3: 3.132 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.117 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (3.076, 3.117, 3.141), stdev = 0.035
  CI (99.9%): [2.469, 3.764] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.885 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.015 ms/op
Iteration   1: 4.097 ±(99.9%) 0.026 ms/op
Iteration   2: 4.022 ±(99.9%) 0.013 ms/op
Iteration   3: 4.021 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.047 ±(99.9%) 0.794 ms/op [Average]
  (min, avg, max) = (4.021, 4.047, 4.097), stdev = 0.044
  CI (99.9%): [3.253, 4.841] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.151 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
Iteration   1: 3.117 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  6.535 ms/op
                 createUser·p0.9999: 12.792 ms/op
                 createUser·p1.00:   13.369 ms/op

Iteration   2: 3.161 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.551 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  9.585 ms/op
                 createUser·p0.9999: 15.548 ms/op
                 createUser·p1.00:   15.860 ms/op

Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  9.312 ms/op
                 createUser·p0.9999: 18.436 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307666
  mean =      3.119 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 409 
    [ 1.250,  2.500) = 28700 
    [ 2.500,  3.750) = 244629 
    [ 3.750,  5.000) = 32734 
    [ 5.000,  6.250) = 580 
    [ 6.250,  7.500) = 224 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     16.818 ms/op
     p(99.9990) =     18.645 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.991 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.722 ms/op
                 existUser·p0.9999: 19.183 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  8.592 ms/op
                 existUser·p0.9999: 15.122 ms/op
                 existUser·p1.00:   16.613 ms/op

Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  6.406 ms/op
                 existUser·p0.9999: 16.079 ms/op
                 existUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316690
  mean =      3.030 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 652 
    [ 1.250,  2.500) = 42412 
    [ 2.500,  3.750) = 247353 
    [ 3.750,  5.000) = 25512 
    [ 5.000,  6.250) = 307 
    [ 6.250,  7.500) = 196 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.979 ms/op
     p(99.9900) =     18.525 ms/op
     p(99.9990) =     19.328 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.090 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.007 ms/op
Iteration   1: 3.197 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.076 ms/op
                 getUser·p0.9999: 14.221 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.914 ms/op
                 getUser·p0.9999: 17.036 ms/op
                 getUser·p1.00:   18.285 ms/op

Iteration   3: 3.239 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.636 ms/op
                 getUser·p0.9999: 17.470 ms/op
                 getUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299858
  mean =      3.201 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 398 
    [ 1.250,  2.500) = 22880 
    [ 2.500,  3.750) = 227272 
    [ 3.750,  5.000) = 48175 
    [ 5.000,  6.250) = 486 
    [ 6.250,  7.500) = 334 
    [ 7.500,  8.750) = 110 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 74 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.597 ms/op
     p(99.9900) =     17.269 ms/op
     p(99.9990) =     18.154 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.520 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.012 ms/op
Iteration   1: 4.208 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.586 ms/op
                 listUser·p0.999:  15.384 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   2: 4.041 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.038 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  16.660 ms/op
                 listUser·p0.9999: 21.105 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   3: 3.979 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.552 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.090 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  19.001 ms/op
                 listUser·p0.9999: 24.833 ms/op
                 listUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235528
  mean =      4.074 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3020 
    [ 2.500,  5.000) = 200754 
    [ 5.000,  7.500) = 30114 
    [ 7.500, 10.000) = 1050 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     16.769 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     25.449 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.304 ± 2.068  ops/ms
ClientGrpc.existUser                       thrpt       3  10.690 ± 2.675  ops/ms
ClientGrpc.getUser                         thrpt       3  10.268 ± 1.142  ops/ms
ClientGrpc.listUser                        thrpt       3   8.012 ± 0.885  ops/ms
ClientGrpc.createUser                       avgt       3   3.162 ± 1.006   ms/op
ClientGrpc.existUser                        avgt       3   2.991 ± 0.450   ms/op
ClientGrpc.getUser                          avgt       3   3.117 ± 0.648   ms/op
ClientGrpc.listUser                         avgt       3   4.047 ± 0.794   ms/op
ClientGrpc.createUser                     sample  307666   3.119 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.551           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.998           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.978           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.818           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.776           ms/op
ClientGrpc.existUser                      sample  316690   3.030 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.714           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.875           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.979           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.525           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.399           ms/op
ClientGrpc.getUser                        sample  299858   3.201 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.711           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.174           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.100           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.597           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.269           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.285           ms/op
ClientGrpc.listUser                       sample  235528   4.074 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.552           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.875           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.259           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.769           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.248           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.559           ms/op
