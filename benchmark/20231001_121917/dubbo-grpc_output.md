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
# Warmup Iteration   1: 3.921 ops/ms
# Warmup Iteration   2: 8.477 ops/ms
# Warmup Iteration   3: 9.690 ops/ms
Iteration   1: 10.036 ops/ms
Iteration   2: 10.214 ops/ms
Iteration   3: 10.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.127 ±(99.9%) 1.626 ops/ms [Average]
  (min, avg, max) = (10.036, 10.127, 10.214), stdev = 0.089
  CI (99.9%): [8.501, 11.753] (assumes normal distribution)


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
# Warmup Iteration   1: 7.059 ops/ms
# Warmup Iteration   2: 10.130 ops/ms
# Warmup Iteration   3: 10.637 ops/ms
Iteration   1: 10.586 ops/ms
Iteration   2: 10.634 ops/ms
Iteration   3: 10.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.710 ±(99.9%) 3.199 ops/ms [Average]
  (min, avg, max) = (10.586, 10.710, 10.911), stdev = 0.175
  CI (99.9%): [7.511, 13.910] (assumes normal distribution)


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
# Warmup Iteration   1: 6.894 ops/ms
# Warmup Iteration   2: 9.718 ops/ms
# Warmup Iteration   3: 9.973 ops/ms
Iteration   1: 10.225 ops/ms
Iteration   2: 10.380 ops/ms
Iteration   3: 10.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.253 ±(99.9%) 2.112 ops/ms [Average]
  (min, avg, max) = (10.154, 10.253, 10.380), stdev = 0.116
  CI (99.9%): [8.141, 12.365] (assumes normal distribution)


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
# Warmup Iteration   1: 5.832 ops/ms
# Warmup Iteration   2: 7.406 ops/ms
# Warmup Iteration   3: 7.928 ops/ms
Iteration   1: 8.039 ops/ms
Iteration   2: 8.094 ops/ms
Iteration   3: 8.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.048 ±(99.9%) 0.784 ops/ms [Average]
  (min, avg, max) = (8.010, 8.048, 8.094), stdev = 0.043
  CI (99.9%): [7.264, 8.831] (assumes normal distribution)


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
# Warmup Iteration   1: 4.381 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.323 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.002 ms/op
Iteration   1: 3.156 ±(99.9%) 0.002 ms/op
Iteration   2: 3.084 ±(99.9%) 0.002 ms/op
Iteration   3: 3.177 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.139 ±(99.9%) 0.890 ms/op [Average]
  (min, avg, max) = (3.084, 3.139, 3.177), stdev = 0.049
  CI (99.9%): [2.249, 4.029] (assumes normal distribution)


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
# Warmup Iteration   1: 4.065 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.002 ms/op
Iteration   1: 3.025 ±(99.9%) 0.002 ms/op
Iteration   2: 3.059 ±(99.9%) 0.001 ms/op
Iteration   3: 2.991 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.025 ±(99.9%) 0.624 ms/op [Average]
  (min, avg, max) = (2.991, 3.025, 3.059), stdev = 0.034
  CI (99.9%): [2.401, 3.649] (assumes normal distribution)


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
# Warmup Iteration   1: 4.526 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.003 ms/op
Iteration   1: 3.135 ±(99.9%) 0.002 ms/op
Iteration   2: 3.135 ±(99.9%) 0.001 ms/op
Iteration   3: 3.092 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.121 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (3.092, 3.121, 3.135), stdev = 0.025
  CI (99.9%): [2.663, 3.579] (assumes normal distribution)


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
# Warmup Iteration   1: 5.966 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.016 ms/op
Iteration   1: 3.873 ±(99.9%) 0.043 ms/op
Iteration   2: 3.918 ±(99.9%) 0.026 ms/op
Iteration   3: 3.949 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.913 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (3.873, 3.913, 3.949), stdev = 0.038
  CI (99.9%): [3.218, 4.609] (assumes normal distribution)


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
# Warmup Iteration   1: 4.477 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.007 ms/op
Iteration   1: 3.193 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.596 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.602 ms/op
                 createUser·p0.9999: 17.662 ms/op
                 createUser·p1.00:   18.088 ms/op

Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  8.184 ms/op
                 createUser·p0.9999: 19.035 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   3: 3.095 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  9.273 ms/op
                 createUser·p0.9999: 20.731 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304344
  mean =      3.156 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11856 
    [ 2.500,  5.000) = 290394 
    [ 5.000,  7.500) = 1544 
    [ 7.500, 10.000) = 325 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      4.592 ms/op
     p(99.9000) =      8.238 ms/op
     p(99.9900) =     20.367 ms/op
     p(99.9990) =     21.037 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.499 ms/op
                 existUser·p0.999:  8.173 ms/op
                 existUser·p0.9999: 13.468 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   2: 2.950 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.676 ms/op
                 existUser·p0.999:  10.701 ms/op
                 existUser·p0.9999: 22.784 ms/op
                 existUser·p1.00:   23.331 ms/op

Iteration   3: 2.949 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  8.122 ms/op
                 existUser·p0.9999: 19.928 ms/op
                 existUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322236
  mean =      2.984 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31732 
    [ 2.500,  5.000) = 288290 
    [ 5.000,  7.500) = 1639 
    [ 7.500, 10.000) = 321 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     21.643 ms/op
     p(99.9990) =     23.251 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 4.441 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.006 ms/op
Iteration   1: 3.147 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.973 ms/op
                 getUser·p0.999:  8.282 ms/op
                 getUser·p0.9999: 13.517 ms/op
                 getUser·p1.00:   13.746 ms/op

Iteration   2: 3.127 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  8.123 ms/op
                 getUser·p0.9999: 17.458 ms/op
                 getUser·p1.00:   17.760 ms/op

Iteration   3: 3.125 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.630 ms/op
                 getUser·p0.9999: 16.941 ms/op
                 getUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306121
  mean =      3.133 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 294 
    [ 1.250,  2.500) = 8977 
    [ 2.500,  3.750) = 274372 
    [ 3.750,  5.000) = 20189 
    [ 5.000,  6.250) = 1275 
    [ 6.250,  7.500) = 515 
    [ 7.500,  8.750) = 304 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 49 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =      8.045 ms/op
     p(99.9900) =     17.130 ms/op
     p(99.9990) =     17.793 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 5.785 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.009 ms/op
Iteration   1: 3.969 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.072 ms/op
                 listUser·p0.9999: 14.875 ms/op
                 listUser·p1.00:   15.565 ms/op

Iteration   2: 3.882 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  14.674 ms/op
                 listUser·p0.9999: 16.177 ms/op
                 listUser·p1.00:   16.744 ms/op

Iteration   3: 4.014 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   7.027 ms/op
                 listUser·p0.999:  16.274 ms/op
                 listUser·p0.9999: 19.728 ms/op
                 listUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242641
  mean =      3.954 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2307 
    [ 2.500,  5.000) = 224511 
    [ 5.000,  7.500) = 14213 
    [ 7.500, 10.000) = 1045 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 245 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      6.968 ms/op
     p(99.9000) =     14.407 ms/op
     p(99.9900) =     17.596 ms/op
     p(99.9990) =     20.012 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.127 ± 1.626  ops/ms
ClientGrpc.existUser                       thrpt       3  10.710 ± 3.199  ops/ms
ClientGrpc.getUser                         thrpt       3  10.253 ± 2.112  ops/ms
ClientGrpc.listUser                        thrpt       3   8.048 ± 0.784  ops/ms
ClientGrpc.createUser                       avgt       3   3.139 ± 0.890   ms/op
ClientGrpc.existUser                        avgt       3   3.025 ± 0.624   ms/op
ClientGrpc.getUser                          avgt       3   3.121 ± 0.458   ms/op
ClientGrpc.listUser                         avgt       3   3.913 ± 0.695   ms/op
ClientGrpc.createUser                     sample  304344   3.156 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.596           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.940           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.592           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.238           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.367           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.037           ms/op
ClientGrpc.existUser                      sample  322236   2.984 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.736           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.563           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.552           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.643           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.331           ms/op
ClientGrpc.getUser                        sample  306121   3.133 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.820           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.045           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.130           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.957           ms/op
ClientGrpc.listUser                       sample  242641   3.954 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.904           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.571           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.317           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.968           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.407           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.596           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.349           ms/op
