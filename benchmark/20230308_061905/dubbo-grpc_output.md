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
# Warmup Iteration   1: 3.836 ops/ms
# Warmup Iteration   2: 8.653 ops/ms
# Warmup Iteration   3: 9.447 ops/ms
Iteration   1: 10.274 ops/ms
Iteration   2: 9.998 ops/ms
Iteration   3: 10.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.229 ±(99.9%) 3.872 ops/ms [Average]
  (min, avg, max) = (9.998, 10.229, 10.416), stdev = 0.212
  CI (99.9%): [6.357, 14.102] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.052 ops/ms
# Warmup Iteration   2: 10.824 ops/ms
# Warmup Iteration   3: 11.206 ops/ms
Iteration   1: 11.318 ops/ms
Iteration   2: 11.081 ops/ms
Iteration   3: 10.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.032 ±(99.9%) 5.712 ops/ms [Average]
  (min, avg, max) = (10.698, 11.032, 11.318), stdev = 0.313
  CI (99.9%): [5.321, 16.744] (assumes normal distribution)


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
# Warmup Iteration   1: 4.133 ops/ms
# Warmup Iteration   2: 9.350 ops/ms
# Warmup Iteration   3: 9.997 ops/ms
Iteration   1: 9.700 ops/ms
Iteration   2: 10.055 ops/ms
Iteration   3: 10.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.135 ±(99.9%) 8.752 ops/ms [Average]
  (min, avg, max) = (9.700, 10.135, 10.650), stdev = 0.480
  CI (99.9%): [1.383, 18.887] (assumes normal distribution)


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
# Warmup Iteration   1: 5.121 ops/ms
# Warmup Iteration   2: 7.860 ops/ms
# Warmup Iteration   3: 8.308 ops/ms
Iteration   1: 8.263 ops/ms
Iteration   2: 8.174 ops/ms
Iteration   3: 8.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.190 ±(99.9%) 1.200 ops/ms [Average]
  (min, avg, max) = (8.134, 8.190, 8.263), stdev = 0.066
  CI (99.9%): [6.990, 9.390] (assumes normal distribution)


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
# Warmup Iteration   1: 4.220 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.003 ms/op
Iteration   1: 3.301 ±(99.9%) 0.004 ms/op
Iteration   2: 3.155 ±(99.9%) 0.003 ms/op
Iteration   3: 3.249 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.235 ±(99.9%) 1.354 ms/op [Average]
  (min, avg, max) = (3.155, 3.235, 3.301), stdev = 0.074
  CI (99.9%): [1.881, 4.589] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.233 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.002 ms/op
Iteration   1: 3.041 ±(99.9%) 0.002 ms/op
Iteration   2: 3.147 ±(99.9%) 0.002 ms/op
Iteration   3: 3.091 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.093 ±(99.9%) 0.968 ms/op [Average]
  (min, avg, max) = (3.041, 3.093, 3.147), stdev = 0.053
  CI (99.9%): [2.125, 4.061] (assumes normal distribution)


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
# Warmup Iteration   1: 4.418 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.357 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.004 ms/op
Iteration   1: 3.274 ±(99.9%) 0.002 ms/op
Iteration   2: 3.202 ±(99.9%) 0.003 ms/op
Iteration   3: 3.230 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.235 ±(99.9%) 0.660 ms/op [Average]
  (min, avg, max) = (3.202, 3.235, 3.274), stdev = 0.036
  CI (99.9%): [2.576, 3.895] (assumes normal distribution)


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
# Warmup Iteration   1: 5.671 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.015 ms/op
Iteration   1: 4.004 ±(99.9%) 0.010 ms/op
Iteration   2: 4.053 ±(99.9%) 0.034 ms/op
Iteration   3: 3.956 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.004 ±(99.9%) 0.879 ms/op [Average]
  (min, avg, max) = (3.956, 4.004, 4.053), stdev = 0.048
  CI (99.9%): [3.126, 4.883] (assumes normal distribution)


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
# Warmup Iteration   1: 4.332 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.430 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.006 ms/op
Iteration   1: 3.214 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  8.515 ms/op
                 createUser·p0.9999: 13.486 ms/op
                 createUser·p1.00:   13.844 ms/op

Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  10.389 ms/op
                 createUser·p0.9999: 15.401 ms/op
                 createUser·p1.00:   15.958 ms/op

Iteration   3: 3.112 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.149 ms/op
                 createUser·p0.999:  12.698 ms/op
                 createUser·p0.9999: 18.011 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303070
  mean =      3.168 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 446 
    [ 1.250,  2.500) = 19896 
    [ 2.500,  3.750) = 248134 
    [ 3.750,  5.000) = 33184 
    [ 5.000,  6.250) = 672 
    [ 6.250,  7.500) = 283 
    [ 7.500,  8.750) = 92 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      9.846 ms/op
     p(99.9900) =     16.637 ms/op
     p(99.9990) =     18.415 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.007 ms/op
Iteration   1: 3.008 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  6.641 ms/op
                 existUser·p0.9999: 17.838 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   2: 2.911 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.443 ms/op
                 existUser·p0.999:  7.300 ms/op
                 existUser·p0.9999: 14.550 ms/op
                 existUser·p1.00:   15.270 ms/op

Iteration   3: 3.032 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.495 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  10.502 ms/op
                 existUser·p0.9999: 27.816 ms/op
                 existUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321839
  mean =      2.983 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46506 
    [ 2.500,  5.000) = 274196 
    [ 5.000,  7.500) = 749 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      9.587 ms/op
     p(99.9900) =     26.023 ms/op
     p(99.9990) =     28.101 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 4.346 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.006 ms/op
Iteration   1: 3.122 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  8.236 ms/op
                 getUser·p0.9999: 15.921 ms/op
                 getUser·p1.00:   16.138 ms/op

Iteration   2: 3.141 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.557 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.701 ms/op
                 getUser·p0.9999: 15.299 ms/op
                 getUser·p1.00:   15.729 ms/op

Iteration   3: 3.179 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.303 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.534 ms/op
                 getUser·p0.9999: 20.019 ms/op
                 getUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305347
  mean =      3.147 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17787 
    [ 2.500,  5.000) = 285993 
    [ 5.000,  7.500) = 1190 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.303 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.886 ms/op
     p(99.9900) =     18.262 ms/op
     p(99.9990) =     20.249 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 5.525 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.199 ±(99.9%) 0.012 ms/op
Iteration   1: 4.049 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  13.435 ms/op
                 listUser·p0.9999: 21.398 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   2: 4.034 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  13.992 ms/op
                 listUser·p0.9999: 17.404 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   3: 4.089 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  16.066 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236496
  mean =      4.057 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2479 
    [ 2.500,  5.000) = 208492 
    [ 5.000,  7.500) = 24277 
    [ 7.500, 10.000) = 864 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     13.902 ms/op
     p(99.9900) =     21.311 ms/op
     p(99.9990) =     22.923 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.229 ± 3.872  ops/ms
ClientGrpc.existUser                       thrpt       3  11.032 ± 5.712  ops/ms
ClientGrpc.getUser                         thrpt       3  10.135 ± 8.752  ops/ms
ClientGrpc.listUser                        thrpt       3   8.190 ± 1.200  ops/ms
ClientGrpc.createUser                       avgt       3   3.235 ± 1.354   ms/op
ClientGrpc.existUser                        avgt       3   3.093 ± 0.968   ms/op
ClientGrpc.getUser                          avgt       3   3.235 ± 0.660   ms/op
ClientGrpc.listUser                         avgt       3   4.004 ± 0.879   ms/op
ClientGrpc.createUser                     sample  303070   3.168 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.717           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.142           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.998           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.846           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.637           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.514           ms/op
ClientGrpc.existUser                      sample  321839   2.983 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.495           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.834           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.587           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.023           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.443           ms/op
ClientGrpc.getUser                        sample  305347   3.147 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.303           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.125           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.886           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.262           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.349           ms/op
ClientGrpc.listUser                       sample  236496   4.057 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.028           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.902           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.311           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.069           ms/op
