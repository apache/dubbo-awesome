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
# Warmup Iteration   1: 4.039 ops/ms
# Warmup Iteration   2: 9.136 ops/ms
# Warmup Iteration   3: 9.866 ops/ms
Iteration   1: 10.214 ops/ms
Iteration   2: 10.308 ops/ms
Iteration   3: 10.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.271 ±(99.9%) 0.913 ops/ms [Average]
  (min, avg, max) = (10.214, 10.271, 10.308), stdev = 0.050
  CI (99.9%): [9.358, 11.184] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.317 ops/ms
# Warmup Iteration   2: 10.288 ops/ms
# Warmup Iteration   3: 10.730 ops/ms
Iteration   1: 10.866 ops/ms
Iteration   2: 10.941 ops/ms
Iteration   3: 10.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.868 ±(99.9%) 1.306 ops/ms [Average]
  (min, avg, max) = (10.798, 10.868, 10.941), stdev = 0.072
  CI (99.9%): [9.563, 12.174] (assumes normal distribution)


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
# Warmup Iteration   1: 7.931 ops/ms
# Warmup Iteration   2: 9.955 ops/ms
# Warmup Iteration   3: 10.073 ops/ms
Iteration   1: 10.102 ops/ms
Iteration   2: 10.277 ops/ms
Iteration   3: 10.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.234 ±(99.9%) 2.134 ops/ms [Average]
  (min, avg, max) = (10.102, 10.234, 10.324), stdev = 0.117
  CI (99.9%): [8.100, 12.369] (assumes normal distribution)


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
# Warmup Iteration   1: 5.979 ops/ms
# Warmup Iteration   2: 7.296 ops/ms
# Warmup Iteration   3: 7.706 ops/ms
Iteration   1: 7.892 ops/ms
Iteration   2: 7.780 ops/ms
Iteration   3: 7.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.820 ±(99.9%) 1.143 ops/ms [Average]
  (min, avg, max) = (7.780, 7.820, 7.892), stdev = 0.063
  CI (99.9%): [6.677, 8.963] (assumes normal distribution)


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
# Warmup Iteration   1: 4.454 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.008 ms/op
Iteration   1: 3.064 ±(99.9%) 0.003 ms/op
Iteration   2: 3.102 ±(99.9%) 0.002 ms/op
Iteration   3: 3.108 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.091 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (3.064, 3.091, 3.108), stdev = 0.024
  CI (99.9%): [2.656, 3.526] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.965 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.005 ms/op
Iteration   1: 3.020 ±(99.9%) 0.003 ms/op
Iteration   2: 2.932 ±(99.9%) 0.004 ms/op
Iteration   3: 3.026 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.993 ±(99.9%) 0.953 ms/op [Average]
  (min, avg, max) = (2.932, 2.993, 3.026), stdev = 0.052
  CI (99.9%): [2.039, 3.946] (assumes normal distribution)


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
# Warmup Iteration   1: 4.429 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.002 ms/op
Iteration   1: 3.138 ±(99.9%) 0.002 ms/op
Iteration   2: 3.079 ±(99.9%) 0.003 ms/op
Iteration   3: 3.212 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.143 ±(99.9%) 1.213 ms/op [Average]
  (min, avg, max) = (3.079, 3.143, 3.212), stdev = 0.066
  CI (99.9%): [1.930, 4.356] (assumes normal distribution)


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
# Warmup Iteration   1: 5.427 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.028 ms/op
Iteration   1: 4.296 ±(99.9%) 0.016 ms/op
Iteration   2: 4.061 ±(99.9%) 0.006 ms/op
Iteration   3: 4.049 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.135 ±(99.9%) 2.538 ms/op [Average]
  (min, avg, max) = (4.049, 4.135, 4.296), stdev = 0.139
  CI (99.9%): [1.597, 6.673] (assumes normal distribution)


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
# Warmup Iteration   1: 4.338 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.007 ms/op
Iteration   1: 3.195 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.081 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  9.110 ms/op
                 createUser·p0.9999: 16.122 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   2: 3.091 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  12.583 ms/op
                 createUser·p0.9999: 18.022 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.624 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  8.200 ms/op
                 createUser·p0.9999: 21.561 ms/op
                 createUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306892
  mean =      3.126 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19863 
    [ 2.500,  5.000) = 284857 
    [ 5.000,  7.500) = 1452 
    [ 7.500, 10.000) = 419 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      9.657 ms/op
     p(99.9900) =     19.769 ms/op
     p(99.9990) =     21.819 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.944 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.007 ms/op
Iteration   1: 2.966 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.776 ms/op
                 existUser·p0.999:  7.990 ms/op
                 existUser·p0.9999: 12.459 ms/op
                 existUser·p1.00:   12.780 ms/op

Iteration   2: 2.962 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  8.266 ms/op
                 existUser·p0.9999: 17.314 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  8.656 ms/op
                 existUser·p0.9999: 14.254 ms/op
                 existUser·p1.00:   15.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322583
  mean =      2.976 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1916 
    [ 1.250,  2.500) = 31813 
    [ 2.500,  3.750) = 273013 
    [ 3.750,  5.000) = 13708 
    [ 5.000,  6.250) = 1152 
    [ 6.250,  7.500) = 392 
    [ 7.500,  8.750) = 362 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      8.331 ms/op
     p(99.9900) =     15.359 ms/op
     p(99.9990) =     17.767 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 4.237 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.007 ms/op
Iteration   1: 3.164 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   5.014 ms/op
                 getUser·p0.999:  8.879 ms/op
                 getUser·p0.9999: 12.911 ms/op
                 getUser·p1.00:   13.173 ms/op

Iteration   2: 3.188 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  8.995 ms/op
                 getUser·p0.9999: 13.926 ms/op
                 getUser·p1.00:   14.303 ms/op

Iteration   3: 3.137 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  8.209 ms/op
                 getUser·p0.9999: 20.113 ms/op
                 getUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303343
  mean =      3.163 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16627 
    [ 2.500,  5.000) = 284282 
    [ 5.000,  7.500) = 1769 
    [ 7.500, 10.000) = 472 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     19.300 ms/op
     p(99.9990) =     20.573 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 5.769 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.010 ms/op
Iteration   1: 3.993 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  10.949 ms/op
                 listUser·p0.9999: 15.056 ms/op
                 listUser·p1.00:   15.483 ms/op

Iteration   2: 4.018 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  16.265 ms/op
                 listUser·p0.9999: 25.035 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   3: 3.856 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.974 ms/op
                 listUser·p0.999:  16.286 ms/op
                 listUser·p0.9999: 18.350 ms/op
                 listUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242931
  mean =      3.954 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4532 
    [ 2.500,  5.000) = 213324 
    [ 5.000,  7.500) = 23322 
    [ 7.500, 10.000) = 1194 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     24.501 ms/op
     p(99.9990) =     25.582 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.271 ± 0.913  ops/ms
ClientGrpc.existUser                       thrpt       3  10.868 ± 1.306  ops/ms
ClientGrpc.getUser                         thrpt       3  10.234 ± 2.134  ops/ms
ClientGrpc.listUser                        thrpt       3   7.820 ± 1.143  ops/ms
ClientGrpc.createUser                       avgt       3   3.091 ± 0.435   ms/op
ClientGrpc.existUser                        avgt       3   2.993 ± 0.953   ms/op
ClientGrpc.getUser                          avgt       3   3.143 ± 1.213   ms/op
ClientGrpc.listUser                         avgt       3   4.135 ± 2.538   ms/op
ClientGrpc.createUser                     sample  306892   3.126 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.599           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.117           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.657           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.769           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.889           ms/op
ClientGrpc.existUser                      sample  322583   2.976 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.615           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.744           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.702           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.331           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.359           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.990           ms/op
ClientGrpc.getUser                        sample  303343   3.163 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.563           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.998           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.841           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.798           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.300           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.709           ms/op
ClientGrpc.listUser                       sample  242931   3.954 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.901           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.352           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.501           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.625           ms/op
