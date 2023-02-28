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
# Warmup Iteration   1: 4.249 ops/ms
# Warmup Iteration   2: 9.345 ops/ms
# Warmup Iteration   3: 9.998 ops/ms
Iteration   1: 10.133 ops/ms
Iteration   2: 10.298 ops/ms
Iteration   3: 9.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.124 ±(99.9%) 3.268 ops/ms [Average]
  (min, avg, max) = (9.940, 10.124, 10.298), stdev = 0.179
  CI (99.9%): [6.855, 13.392] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.290 ops/ms
# Warmup Iteration   2: 10.430 ops/ms
# Warmup Iteration   3: 10.518 ops/ms
Iteration   1: 10.590 ops/ms
Iteration   2: 10.982 ops/ms
Iteration   3: 10.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.779 ±(99.9%) 3.580 ops/ms [Average]
  (min, avg, max) = (10.590, 10.779, 10.982), stdev = 0.196
  CI (99.9%): [7.199, 14.359] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.345 ops/ms
# Warmup Iteration   2: 10.241 ops/ms
# Warmup Iteration   3: 10.226 ops/ms
Iteration   1: 10.348 ops/ms
Iteration   2: 10.015 ops/ms
Iteration   3: 10.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.149 ±(99.9%) 3.199 ops/ms [Average]
  (min, avg, max) = (10.015, 10.149, 10.348), stdev = 0.175
  CI (99.9%): [6.951, 13.348] (assumes normal distribution)


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
# Warmup Iteration   1: 5.150 ops/ms
# Warmup Iteration   2: 7.367 ops/ms
# Warmup Iteration   3: 7.770 ops/ms
Iteration   1: 7.763 ops/ms
Iteration   2: 7.806 ops/ms
Iteration   3: 7.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.826 ±(99.9%) 1.362 ops/ms [Average]
  (min, avg, max) = (7.763, 7.826, 7.909), stdev = 0.075
  CI (99.9%): [6.464, 9.188] (assumes normal distribution)


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
# Warmup Iteration   1: 4.496 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.003 ms/op
Iteration   1: 3.152 ±(99.9%) 0.001 ms/op
Iteration   2: 3.185 ±(99.9%) 0.002 ms/op
Iteration   3: 3.201 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.179 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.152, 3.179, 3.201), stdev = 0.025
  CI (99.9%): [2.719, 3.639] (assumes normal distribution)


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.002 ms/op
Iteration   1: 3.005 ±(99.9%) 0.002 ms/op
Iteration   2: 2.959 ±(99.9%) 0.002 ms/op
Iteration   3: 3.037 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.001 ±(99.9%) 0.711 ms/op [Average]
  (min, avg, max) = (2.959, 3.001, 3.037), stdev = 0.039
  CI (99.9%): [2.290, 3.711] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.807 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.004 ms/op
Iteration   1: 3.110 ±(99.9%) 0.003 ms/op
Iteration   2: 3.189 ±(99.9%) 0.003 ms/op
Iteration   3: 3.120 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.140 ±(99.9%) 0.787 ms/op [Average]
  (min, avg, max) = (3.110, 3.140, 3.189), stdev = 0.043
  CI (99.9%): [2.353, 3.927] (assumes normal distribution)


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
# Warmup Iteration   1: 5.044 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.256 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.017 ms/op
Iteration   1: 3.950 ±(99.9%) 0.025 ms/op
Iteration   2: 3.988 ±(99.9%) 0.006 ms/op
Iteration   3: 3.887 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.942 ±(99.9%) 0.930 ms/op [Average]
  (min, avg, max) = (3.887, 3.942, 3.988), stdev = 0.051
  CI (99.9%): [3.012, 4.873] (assumes normal distribution)


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
# Warmup Iteration   1: 4.214 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.007 ms/op
Iteration   1: 3.234 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  8.578 ms/op
                 createUser·p0.9999: 15.532 ms/op
                 createUser·p1.00:   16.171 ms/op

Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  8.221 ms/op
                 createUser·p0.9999: 15.054 ms/op
                 createUser·p1.00:   16.040 ms/op

Iteration   3: 3.161 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.468 ms/op
                 createUser·p0.9999: 15.646 ms/op
                 createUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302072
  mean =      3.178 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 519 
    [ 1.250,  2.500) = 26290 
    [ 2.500,  3.750) = 228119 
    [ 3.750,  5.000) = 45899 
    [ 5.000,  6.250) = 490 
    [ 6.250,  7.500) = 374 
    [ 7.500,  8.750) = 112 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 48 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      8.207 ms/op
     p(99.9900) =     15.378 ms/op
     p(99.9990) =     16.039 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
# Warmup Iteration   1: 3.912 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.362 ms/op
                 existUser·p0.999:  7.348 ms/op
                 existUser·p0.9999: 15.437 ms/op
                 existUser·p1.00:   15.827 ms/op

Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.338 ms/op
                 existUser·p0.9999: 26.730 ms/op
                 existUser·p1.00:   27.132 ms/op

Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.185 ms/op
                 existUser·p0.999:  8.627 ms/op
                 existUser·p0.9999: 18.612 ms/op
                 existUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315630
  mean =      3.042 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44191 
    [ 2.500,  5.000) = 270503 
    [ 5.000,  7.500) = 674 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.991 ms/op
     p(99.9900) =     24.990 ms/op
     p(99.9990) =     27.023 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 4.373 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
Iteration   1: 3.247 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  11.389 ms/op
                 getUser·p0.9999: 16.173 ms/op
                 getUser·p1.00:   16.597 ms/op

Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  11.370 ms/op
                 getUser·p0.9999: 24.040 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   3: 3.209 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.275 ms/op
                 getUser·p0.9999: 21.399 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301563
  mean =      3.181 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21095 
    [ 2.500,  5.000) = 279308 
    [ 5.000,  7.500) = 756 
    [ 7.500, 10.000) = 139 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.838 ms/op
     p(99.9900) =     22.305 ms/op
     p(99.9990) =     24.345 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.230 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.071 ±(99.9%) 0.011 ms/op
Iteration   1: 4.053 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  12.927 ms/op
                 listUser·p0.9999: 15.419 ms/op
                 listUser·p1.00:   15.958 ms/op

Iteration   2: 4.029 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  14.746 ms/op
                 listUser·p0.9999: 24.969 ms/op
                 listUser·p1.00:   25.395 ms/op

Iteration   3: 4.063 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.808 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.035 ms/op
                 listUser·p0.999:  15.409 ms/op
                 listUser·p0.9999: 23.143 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237135
  mean =      4.048 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2045 
    [ 2.500,  5.000) = 207505 
    [ 5.000,  7.500) = 26238 
    [ 7.500, 10.000) = 870 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     14.268 ms/op
     p(99.9900) =     23.439 ms/op
     p(99.9990) =     25.305 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.124 ± 3.268  ops/ms
ClientGrpc.existUser                       thrpt       3  10.779 ± 3.580  ops/ms
ClientGrpc.getUser                         thrpt       3  10.149 ± 3.199  ops/ms
ClientGrpc.listUser                        thrpt       3   7.826 ± 1.362  ops/ms
ClientGrpc.createUser                       avgt       3   3.179 ± 0.460   ms/op
ClientGrpc.existUser                        avgt       3   3.001 ± 0.711   ms/op
ClientGrpc.getUser                          avgt       3   3.140 ± 0.787   ms/op
ClientGrpc.listUser                         avgt       3   3.942 ± 0.930   ms/op
ClientGrpc.createUser                     sample  302072   3.178 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.740           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.150           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.108           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.207           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.378           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.646           ms/op
ClientGrpc.existUser                      sample  315630   3.042 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.656           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.023           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.748           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.940           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.991           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.990           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.132           ms/op
ClientGrpc.getUser                        sample  301563   3.181 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.628           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.146           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.051           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.838           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.305           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.478           ms/op
ClientGrpc.listUser                       sample  237135   4.048 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.808           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.268           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.439           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.395           ms/op
