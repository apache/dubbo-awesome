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
# Warmup Iteration   1: 4.188 ops/ms
# Warmup Iteration   2: 8.460 ops/ms
# Warmup Iteration   3: 9.816 ops/ms
Iteration   1: 10.235 ops/ms
Iteration   2: 10.250 ops/ms
Iteration   3: 10.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.271 ±(99.9%) 0.894 ops/ms [Average]
  (min, avg, max) = (10.235, 10.271, 10.327), stdev = 0.049
  CI (99.9%): [9.376, 11.165] (assumes normal distribution)


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
# Warmup Iteration   1: 6.858 ops/ms
# Warmup Iteration   2: 10.287 ops/ms
# Warmup Iteration   3: 10.825 ops/ms
Iteration   1: 10.812 ops/ms
Iteration   2: 10.796 ops/ms
Iteration   3: 10.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.832 ±(99.9%) 0.899 ops/ms [Average]
  (min, avg, max) = (10.796, 10.832, 10.888), stdev = 0.049
  CI (99.9%): [9.933, 11.731] (assumes normal distribution)


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
# Warmup Iteration   1: 6.285 ops/ms
# Warmup Iteration   2: 9.845 ops/ms
# Warmup Iteration   3: 10.354 ops/ms
Iteration   1: 10.212 ops/ms
Iteration   2: 10.185 ops/ms
Iteration   3: 10.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.239 ±(99.9%) 1.303 ops/ms [Average]
  (min, avg, max) = (10.185, 10.239, 10.320), stdev = 0.071
  CI (99.9%): [8.936, 11.541] (assumes normal distribution)


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
# Warmup Iteration   1: 5.100 ops/ms
# Warmup Iteration   2: 7.028 ops/ms
# Warmup Iteration   3: 7.639 ops/ms
Iteration   1: 7.806 ops/ms
Iteration   2: 7.841 ops/ms
Iteration   3: 7.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.736 ±(99.9%) 2.796 ops/ms [Average]
  (min, avg, max) = (7.560, 7.736, 7.841), stdev = 0.153
  CI (99.9%): [4.940, 10.531] (assumes normal distribution)


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
# Warmup Iteration   1: 4.468 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.003 ms/op
Iteration   1: 3.093 ±(99.9%) 0.003 ms/op
Iteration   2: 3.093 ±(99.9%) 0.003 ms/op
Iteration   3: 3.116 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.100 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (3.093, 3.100, 3.116), stdev = 0.014
  CI (99.9%): [2.852, 3.349] (assumes normal distribution)


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
# Warmup Iteration   1: 4.031 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.002 ms/op
Iteration   1: 2.972 ±(99.9%) 0.002 ms/op
Iteration   2: 2.986 ±(99.9%) 0.001 ms/op
Iteration   3: 2.980 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.979 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (2.972, 2.979, 2.986), stdev = 0.007
  CI (99.9%): [2.858, 3.100] (assumes normal distribution)


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
# Warmup Iteration   1: 4.408 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.002 ms/op
Iteration   1: 3.120 ±(99.9%) 0.003 ms/op
Iteration   2: 3.096 ±(99.9%) 0.003 ms/op
Iteration   3: 3.111 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.109 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (3.096, 3.109, 3.120), stdev = 0.012
  CI (99.9%): [2.890, 3.328] (assumes normal distribution)


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
# Warmup Iteration   1: 5.110 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.419 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.012 ms/op
Iteration   1: 4.099 ±(99.9%) 0.018 ms/op
Iteration   2: 4.076 ±(99.9%) 0.013 ms/op
Iteration   3: 4.065 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.080 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (4.065, 4.080, 4.099), stdev = 0.017
  CI (99.9%): [3.763, 4.397] (assumes normal distribution)


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.376 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
Iteration   1: 3.079 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  8.603 ms/op
                 createUser·p0.9999: 17.158 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  8.666 ms/op
                 createUser·p0.9999: 19.318 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.312 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 22.396 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311082
  mean =      3.085 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14416 
    [ 2.500,  5.000) = 294452 
    [ 5.000,  7.500) = 1612 
    [ 7.500, 10.000) = 357 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.312 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     20.542 ms/op
     p(99.9990) =     22.668 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 4.051 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.512 ms/op
                 existUser·p0.9999: 18.973 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   2: 2.948 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  8.184 ms/op
                 existUser·p0.9999: 14.434 ms/op
                 existUser·p1.00:   16.450 ms/op

Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  9.139 ms/op
                 existUser·p0.9999: 17.576 ms/op
                 existUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321840
  mean =      2.982 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23281 
    [ 2.500,  5.000) = 296883 
    [ 5.000,  7.500) = 1254 
    [ 7.500, 10.000) = 230 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.873 ms/op
     p(99.9900) =     18.639 ms/op
     p(99.9990) =     20.335 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 4.552 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
Iteration   1: 3.098 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.038 ms/op
                 getUser·p0.999:  9.467 ms/op
                 getUser·p0.9999: 18.864 ms/op
                 getUser·p1.00:   20.218 ms/op

Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.569 ms/op
                 getUser·p0.9999: 19.202 ms/op
                 getUser·p1.00:   19.759 ms/op

Iteration   3: 3.102 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  8.351 ms/op
                 getUser·p0.9999: 33.216 ms/op
                 getUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309688
  mean =      3.098 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15537 
    [ 2.500,  5.000) = 291741 
    [ 5.000,  7.500) = 1820 
    [ 7.500, 10.000) = 411 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     31.262 ms/op
     p(99.9990) =     33.391 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 5.762 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.446 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.013 ms/op
Iteration   1: 4.095 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.684 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.364 ms/op
                 listUser·p0.999:  14.251 ms/op
                 listUser·p0.9999: 16.628 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   2: 4.121 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  18.776 ms/op
                 listUser·p0.9999: 25.952 ms/op
                 listUser·p1.00:   26.378 ms/op

Iteration   3: 4.072 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  22.020 ms/op
                 listUser·p0.9999: 25.699 ms/op
                 listUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234391
  mean =      4.096 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2744 
    [ 2.500,  5.000) = 204461 
    [ 5.000,  7.500) = 24970 
    [ 7.500, 10.000) = 1629 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     25.661 ms/op
     p(99.9990) =     26.508 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.271 ± 0.894  ops/ms
ClientGrpc.existUser                       thrpt       3  10.832 ± 0.899  ops/ms
ClientGrpc.getUser                         thrpt       3  10.239 ± 1.303  ops/ms
ClientGrpc.listUser                        thrpt       3   7.736 ± 2.796  ops/ms
ClientGrpc.createUser                       avgt       3   3.100 ± 0.249   ms/op
ClientGrpc.existUser                        avgt       3   2.979 ± 0.121   ms/op
ClientGrpc.getUser                          avgt       3   3.109 ± 0.219   ms/op
ClientGrpc.listUser                         avgt       3   4.080 ± 0.317   ms/op
ClientGrpc.createUser                     sample  311082   3.085 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.312           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.569           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.542           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.938           ms/op
ClientGrpc.existUser                      sample  321840   2.982 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.673           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.873           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.639           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.480           ms/op
ClientGrpc.getUser                        sample  309688   3.098 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.775           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.760           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.733           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.262           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.456           ms/op
ClientGrpc.listUser                       sample  234391   4.096 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.684           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.916           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.956           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.414           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.924           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.661           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.197           ms/op
