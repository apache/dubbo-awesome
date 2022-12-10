# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.197 ops/ms
# Warmup Iteration   2: 9.037 ops/ms
# Warmup Iteration   3: 9.836 ops/ms
Iteration   1: 10.149 ops/ms
Iteration   2: 9.917 ops/ms
Iteration   3: 10.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.054 ±(99.9%) 2.210 ops/ms [Average]
  (min, avg, max) = (9.917, 10.054, 10.149), stdev = 0.121
  CI (99.9%): [7.844, 12.263] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.579 ops/ms
# Warmup Iteration   2: 10.370 ops/ms
# Warmup Iteration   3: 10.568 ops/ms
Iteration   1: 10.914 ops/ms
Iteration   2: 10.590 ops/ms
Iteration   3: 10.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.670 ±(99.9%) 3.916 ops/ms [Average]
  (min, avg, max) = (10.508, 10.670, 10.914), stdev = 0.215
  CI (99.9%): [6.755, 14.586] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.854 ops/ms
# Warmup Iteration   2: 9.910 ops/ms
# Warmup Iteration   3: 10.230 ops/ms
Iteration   1: 10.315 ops/ms
Iteration   2: 9.970 ops/ms
Iteration   3: 10.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.217 ±(99.9%) 3.934 ops/ms [Average]
  (min, avg, max) = (9.970, 10.217, 10.366), stdev = 0.216
  CI (99.9%): [6.283, 14.152] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.546 ops/ms
# Warmup Iteration   2: 7.467 ops/ms
# Warmup Iteration   3: 7.703 ops/ms
Iteration   1: 7.818 ops/ms
Iteration   2: 7.730 ops/ms
Iteration   3: 7.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.836 ±(99.9%) 2.096 ops/ms [Average]
  (min, avg, max) = (7.730, 7.836, 7.958), stdev = 0.115
  CI (99.9%): [5.739, 9.932] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.376 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.003 ms/op
Iteration   1: 3.200 ±(99.9%) 0.002 ms/op
Iteration   2: 3.180 ±(99.9%) 0.002 ms/op
Iteration   3: 3.203 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.195 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (3.180, 3.195, 3.203), stdev = 0.012
  CI (99.9%): [2.971, 3.418] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.997 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.002 ms/op
Iteration   1: 3.067 ±(99.9%) 0.002 ms/op
Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
Iteration   3: 3.034 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.034 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (3.000, 3.034, 3.067), stdev = 0.033
  CI (99.9%): [2.425, 3.643] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.956 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.003 ms/op
Iteration   1: 3.179 ±(99.9%) 0.002 ms/op
Iteration   2: 3.173 ±(99.9%) 0.003 ms/op
Iteration   3: 3.164 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.172 ±(99.9%) 0.134 ms/op [Average]
  (min, avg, max) = (3.164, 3.172, 3.179), stdev = 0.007
  CI (99.9%): [3.038, 3.307] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.843 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.232 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.011 ms/op
Iteration   1: 4.117 ±(99.9%) 0.009 ms/op
Iteration   2: 3.901 ±(99.9%) 0.004 ms/op
Iteration   3: 3.941 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.986 ±(99.9%) 2.099 ms/op [Average]
  (min, avg, max) = (3.901, 3.986, 4.117), stdev = 0.115
  CI (99.9%): [1.888, 6.085] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.287 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.007 ms/op
Iteration   1: 3.180 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.442 ms/op
                 createUser·p0.9999: 11.910 ms/op
                 createUser·p1.00:   13.484 ms/op

Iteration   2: 3.264 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.980 ms/op
                 createUser·p0.9999: 14.700 ms/op
                 createUser·p1.00:   14.909 ms/op

Iteration   3: 3.157 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.964 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.007 ms/op
                 createUser·p0.9999: 32.465 ms/op
                 createUser·p1.00:   33.227 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 299853
  mean =      3.200 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22894 
    [ 2.500,  5.000) = 275920 
    [ 5.000,  7.500) = 649 
    [ 7.500, 10.000) = 157 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.127 ms/op
     p(99.9900) =     30.999 ms/op
     p(99.9990) =     33.030 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.030 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
Iteration   1: 3.084 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.447 ms/op
                 existUser·p0.9999: 15.198 ms/op
                 existUser·p1.00:   15.450 ms/op

Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.441 ms/op
                 existUser·p0.999:  10.093 ms/op
                 existUser·p0.9999: 14.514 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  5.780 ms/op
                 existUser·p0.9999: 16.937 ms/op
                 existUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315200
  mean =      3.047 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1640 
    [ 1.250,  2.500) = 41723 
    [ 2.500,  3.750) = 239959 
    [ 3.750,  5.000) = 30881 
    [ 5.000,  6.250) = 389 
    [ 6.250,  7.500) = 233 
    [ 7.500,  8.750) = 113 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 81 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.918 ms/op
     p(99.9900) =     16.457 ms/op
     p(99.9990) =     17.324 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.273 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.220 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
Iteration   1: 3.166 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.929 ms/op
                 getUser·p0.9999: 14.562 ms/op
                 getUser·p1.00:   15.106 ms/op

Iteration   2: 3.184 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.837 ms/op
                 getUser·p0.9999: 14.416 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.808 ms/op
                 getUser·p0.9999: 18.005 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304072
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 352 
    [ 1.250,  2.500) = 22914 
    [ 2.500,  3.750) = 240777 
    [ 3.750,  5.000) = 39131 
    [ 5.000,  6.250) = 342 
    [ 6.250,  7.500) = 261 
    [ 7.500,  8.750) = 83 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.446 ms/op
     p(99.9900) =     16.928 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.369 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.013 ms/op
Iteration   1: 4.130 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.546 ms/op
                 listUser·p0.95:   6.185 ms/op
                 listUser·p0.99:   7.379 ms/op
                 listUser·p0.999:  19.876 ms/op
                 listUser·p0.9999: 25.543 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   2: 4.064 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.563 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  16.390 ms/op
                 listUser·p0.9999: 19.740 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   3: 4.111 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  16.212 ms/op
                 listUser·p0.9999: 20.632 ms/op
                 listUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233921
  mean =      4.102 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1673 
    [ 2.500,  5.000) = 201100 
    [ 5.000,  7.500) = 29495 
    [ 7.500, 10.000) = 1152 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     16.785 ms/op
     p(99.9900) =     23.987 ms/op
     p(99.9990) =     25.918 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.054 ± 2.210  ops/ms
ClientGrpc.existUser                       thrpt       3  10.670 ± 3.916  ops/ms
ClientGrpc.getUser                         thrpt       3  10.217 ± 3.934  ops/ms
ClientGrpc.listUser                        thrpt       3   7.836 ± 2.096  ops/ms
ClientGrpc.createUser                       avgt       3   3.195 ± 0.223   ms/op
ClientGrpc.existUser                        avgt       3   3.034 ± 0.609   ms/op
ClientGrpc.getUser                          avgt       3   3.172 ± 0.134   ms/op
ClientGrpc.listUser                         avgt       3   3.986 ± 2.099   ms/op
ClientGrpc.createUser                     sample  299853   3.200 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.724           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.174           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.092           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.127           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.999           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.227           ms/op
ClientGrpc.existUser                      sample  315200   3.047 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.657           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.027           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.918           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.457           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.433           ms/op
ClientGrpc.getUser                        sample  304072   3.155 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.751           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.125           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.006           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.446           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.928           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.153           ms/op
ClientGrpc.listUser                       sample  233921   4.102 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.915           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.898           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.785           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.987           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.116           ms/op
