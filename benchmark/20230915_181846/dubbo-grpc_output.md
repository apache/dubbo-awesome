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
# Warmup Iteration   1: 4.149 ops/ms
# Warmup Iteration   2: 8.766 ops/ms
# Warmup Iteration   3: 9.874 ops/ms
Iteration   1: 9.852 ops/ms
Iteration   2: 9.913 ops/ms
Iteration   3: 10.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.956 ±(99.9%) 2.378 ops/ms [Average]
  (min, avg, max) = (9.852, 9.956, 10.102), stdev = 0.130
  CI (99.9%): [7.578, 12.333] (assumes normal distribution)


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
# Warmup Iteration   1: 7.169 ops/ms
# Warmup Iteration   2: 10.138 ops/ms
# Warmup Iteration   3: 10.840 ops/ms
Iteration   1: 10.320 ops/ms
Iteration   2: 10.697 ops/ms
Iteration   3: 10.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.544 ±(99.9%) 3.621 ops/ms [Average]
  (min, avg, max) = (10.320, 10.544, 10.697), stdev = 0.198
  CI (99.9%): [6.924, 14.165] (assumes normal distribution)


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
# Warmup Iteration   1: 7.431 ops/ms
# Warmup Iteration   2: 9.852 ops/ms
# Warmup Iteration   3: 10.192 ops/ms
Iteration   1: 10.053 ops/ms
Iteration   2: 10.111 ops/ms
Iteration   3: 10.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.130 ±(99.9%) 1.613 ops/ms [Average]
  (min, avg, max) = (10.053, 10.130, 10.226), stdev = 0.088
  CI (99.9%): [8.518, 11.743] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.525 ops/ms
# Warmup Iteration   2: 7.702 ops/ms
# Warmup Iteration   3: 8.121 ops/ms
Iteration   1: 8.188 ops/ms
Iteration   2: 8.141 ops/ms
Iteration   3: 8.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.206 ±(99.9%) 1.373 ops/ms [Average]
  (min, avg, max) = (8.141, 8.206, 8.288), stdev = 0.075
  CI (99.9%): [6.833, 9.578] (assumes normal distribution)


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.317 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.002 ms/op
Iteration   1: 3.098 ±(99.9%) 0.003 ms/op
Iteration   2: 3.101 ±(99.9%) 0.001 ms/op
Iteration   3: 3.155 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.118 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (3.098, 3.118, 3.155), stdev = 0.032
  CI (99.9%): [2.532, 3.704] (assumes normal distribution)


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.001 ms/op
Iteration   1: 3.015 ±(99.9%) 0.003 ms/op
Iteration   2: 3.077 ±(99.9%) 0.003 ms/op
Iteration   3: 2.961 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.018 ±(99.9%) 1.055 ms/op [Average]
  (min, avg, max) = (2.961, 3.018, 3.077), stdev = 0.058
  CI (99.9%): [1.963, 4.072] (assumes normal distribution)


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
# Warmup Iteration   1: 4.283 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.288 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.002 ms/op
Iteration   1: 3.170 ±(99.9%) 0.003 ms/op
Iteration   2: 3.167 ±(99.9%) 0.002 ms/op
Iteration   3: 3.140 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.159 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (3.140, 3.159, 3.170), stdev = 0.016
  CI (99.9%): [2.863, 3.455] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.417 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.020 ms/op
Iteration   1: 3.873 ±(99.9%) 0.038 ms/op
Iteration   2: 3.889 ±(99.9%) 0.009 ms/op
Iteration   3: 3.949 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.904 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (3.873, 3.904, 3.949), stdev = 0.040
  CI (99.9%): [3.175, 4.633] (assumes normal distribution)


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
# Warmup Iteration   1: 4.399 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.209 ±(99.9%) 0.006 ms/op
Iteration   1: 3.150 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.251 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  9.223 ms/op
                 createUser·p0.9999: 13.376 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   2: 3.162 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.651 ms/op
                 createUser·p0.999:  9.406 ms/op
                 createUser·p0.9999: 13.124 ms/op
                 createUser·p1.00:   13.451 ms/op

Iteration   3: 3.183 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.578 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  9.372 ms/op
                 createUser·p0.9999: 16.417 ms/op
                 createUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303263
  mean =      3.165 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 405 
    [ 1.250,  2.500) = 7621 
    [ 2.500,  3.750) = 266588 
    [ 3.750,  5.000) = 26690 
    [ 5.000,  6.250) = 1064 
    [ 6.250,  7.500) = 370 
    [ 7.500,  8.750) = 133 
    [ 8.750, 10.000) = 143 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.251 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      9.330 ms/op
     p(99.9900) =     15.794 ms/op
     p(99.9990) =     16.646 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.005 ms/op
Iteration   1: 3.027 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  8.733 ms/op
                 existUser·p0.9999: 12.089 ms/op
                 existUser·p1.00:   12.272 ms/op

Iteration   2: 2.947 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  8.970 ms/op
                 existUser·p0.9999: 13.737 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   3: 2.964 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  6.718 ms/op
                 existUser·p0.9999: 20.945 ms/op
                 existUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322154
  mean =      2.979 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18438 
    [ 2.500,  5.000) = 302027 
    [ 5.000,  7.500) = 1231 
    [ 7.500, 10.000) = 234 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.517 ms/op
     p(99.9900) =     19.698 ms/op
     p(99.9990) =     21.219 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 4.201 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.007 ms/op
Iteration   1: 3.187 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  7.381 ms/op
                 getUser·p0.9999: 12.713 ms/op
                 getUser·p1.00:   13.009 ms/op

Iteration   2: 3.128 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.109 ms/op
                 getUser·p0.9999: 12.891 ms/op
                 getUser·p1.00:   13.418 ms/op

Iteration   3: 3.115 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  7.739 ms/op
                 getUser·p0.9999: 17.400 ms/op
                 getUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305261
  mean =      3.143 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 445 
    [ 1.250,  2.500) = 8908 
    [ 2.500,  3.750) = 273249 
    [ 3.750,  5.000) = 21006 
    [ 5.000,  6.250) = 1114 
    [ 6.250,  7.500) = 302 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      6.879 ms/op
     p(99.9900) =     15.208 ms/op
     p(99.9990) =     17.433 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 4.766 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.010 ms/op
Iteration   1: 3.951 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  12.480 ms/op
                 listUser·p0.9999: 15.137 ms/op
                 listUser·p1.00:   15.712 ms/op

Iteration   2: 3.862 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.372 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 22.460 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 3.906 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   6.573 ms/op
                 listUser·p0.999:  14.127 ms/op
                 listUser·p0.9999: 16.771 ms/op
                 listUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245886
  mean =      3.906 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2003 
    [ 2.500,  5.000) = 230699 
    [ 5.000,  7.500) = 12149 
    [ 7.500, 10.000) = 486 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     21.503 ms/op
     p(99.9990) =     22.714 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.956 ± 2.378  ops/ms
ClientGrpc.existUser                       thrpt       3  10.544 ± 3.621  ops/ms
ClientGrpc.getUser                         thrpt       3  10.130 ± 1.613  ops/ms
ClientGrpc.listUser                        thrpt       3   8.206 ± 1.373  ops/ms
ClientGrpc.createUser                       avgt       3   3.118 ± 0.586   ms/op
ClientGrpc.existUser                        avgt       3   3.018 ± 1.055   ms/op
ClientGrpc.getUser                          avgt       3   3.159 ± 0.296   ms/op
ClientGrpc.listUser                         avgt       3   3.904 ± 0.729   ms/op
ClientGrpc.createUser                     sample  303263   3.165 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.251           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.109           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.944           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.330           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.794           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.761           ms/op
ClientGrpc.existUser                      sample  322154   2.979 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.640           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.517           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.698           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.332           ms/op
ClientGrpc.getUser                        sample  305261   3.143 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.660           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.879           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.208           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.433           ms/op
ClientGrpc.listUser                       sample  245886   3.906 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.919           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.366           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.353           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.503           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.807           ms/op
