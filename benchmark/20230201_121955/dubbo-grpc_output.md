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
# Warmup Iteration   1: 4.522 ops/ms
# Warmup Iteration   2: 9.255 ops/ms
# Warmup Iteration   3: 9.961 ops/ms
Iteration   1: 9.917 ops/ms
Iteration   2: 10.000 ops/ms
Iteration   3: 9.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.908 ±(99.9%) 1.775 ops/ms [Average]
  (min, avg, max) = (9.806, 9.908, 10.000), stdev = 0.097
  CI (99.9%): [8.133, 11.683] (assumes normal distribution)


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
# Warmup Iteration   1: 7.889 ops/ms
# Warmup Iteration   2: 10.249 ops/ms
# Warmup Iteration   3: 10.636 ops/ms
Iteration   1: 10.572 ops/ms
Iteration   2: 10.384 ops/ms
Iteration   3: 10.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.489 ±(99.9%) 1.755 ops/ms [Average]
  (min, avg, max) = (10.384, 10.489, 10.572), stdev = 0.096
  CI (99.9%): [8.734, 12.244] (assumes normal distribution)


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
# Warmup Iteration   1: 6.854 ops/ms
# Warmup Iteration   2: 9.772 ops/ms
# Warmup Iteration   3: 9.903 ops/ms
Iteration   1: 10.102 ops/ms
Iteration   2: 10.152 ops/ms
Iteration   3: 10.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.169 ±(99.9%) 1.393 ops/ms [Average]
  (min, avg, max) = (10.102, 10.169, 10.252), stdev = 0.076
  CI (99.9%): [8.776, 11.562] (assumes normal distribution)


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
# Warmup Iteration   1: 5.679 ops/ms
# Warmup Iteration   2: 7.474 ops/ms
# Warmup Iteration   3: 7.712 ops/ms
Iteration   1: 7.752 ops/ms
Iteration   2: 7.745 ops/ms
Iteration   3: 8.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.953 ±(99.9%) 6.470 ops/ms [Average]
  (min, avg, max) = (7.745, 7.953, 8.363), stdev = 0.355
  CI (99.9%): [1.483, 14.423] (assumes normal distribution)


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
# Warmup Iteration   1: 4.333 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.003 ms/op
Iteration   1: 3.249 ±(99.9%) 0.008 ms/op
Iteration   2: 3.242 ±(99.9%) 0.002 ms/op
Iteration   3: 3.221 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.237 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (3.221, 3.237, 3.249), stdev = 0.015
  CI (99.9%): [2.965, 3.510] (assumes normal distribution)


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
# Warmup Iteration   1: 4.161 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.004 ms/op
Iteration   1: 3.089 ±(99.9%) 0.004 ms/op
Iteration   2: 3.065 ±(99.9%) 0.002 ms/op
Iteration   3: 3.101 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.085 ±(99.9%) 0.331 ms/op [Average]
  (min, avg, max) = (3.065, 3.085, 3.101), stdev = 0.018
  CI (99.9%): [2.754, 3.417] (assumes normal distribution)


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
# Warmup Iteration   1: 4.713 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.003 ms/op
Iteration   1: 3.171 ±(99.9%) 0.002 ms/op
Iteration   2: 3.170 ±(99.9%) 0.002 ms/op
Iteration   3: 3.188 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.176 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (3.170, 3.176, 3.188), stdev = 0.010
  CI (99.9%): [2.990, 3.362] (assumes normal distribution)


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
# Warmup Iteration   1: 5.152 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.277 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.010 ms/op
Iteration   1: 4.169 ±(99.9%) 0.012 ms/op
Iteration   2: 3.991 ±(99.9%) 0.007 ms/op
Iteration   3: 4.077 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.079 ±(99.9%) 1.625 ms/op [Average]
  (min, avg, max) = (3.991, 4.079, 4.169), stdev = 0.089
  CI (99.9%): [2.454, 5.704] (assumes normal distribution)


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
# Warmup Iteration   1: 4.396 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.326 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.008 ms/op
Iteration   1: 3.231 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  6.423 ms/op
                 createUser·p0.9999: 12.949 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   2: 3.252 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.487 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.156 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.905 ms/op
                 createUser·p0.9999: 20.972 ms/op
                 createUser·p1.00:   21.430 ms/op

Iteration   3: 3.245 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.937 ms/op
                 createUser·p0.9999: 20.615 ms/op
                 createUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 296187
  mean =      3.243 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17417 
    [ 2.500,  5.000) = 277765 
    [ 5.000,  7.500) = 678 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.617 ms/op
     p(99.9900) =     20.624 ms/op
     p(99.9990) =     21.235 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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
# Warmup Iteration   1: 4.052 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
Iteration   1: 3.090 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.286 ms/op
                 existUser·p0.999:  7.213 ms/op
                 existUser·p0.9999: 12.763 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  7.193 ms/op
                 existUser·p0.9999: 14.330 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   3: 2.995 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.008 ms/op
                 existUser·p0.9999: 16.755 ms/op
                 existUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312356
  mean =      3.073 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 979 
    [ 1.250,  2.500) = 31447 
    [ 2.500,  3.750) = 251093 
    [ 3.750,  5.000) = 28104 
    [ 5.000,  6.250) = 280 
    [ 6.250,  7.500) = 212 
    [ 7.500,  8.750) = 112 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.152 ms/op
     p(99.9900) =     14.615 ms/op
     p(99.9990) =     17.003 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 4.337 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.297 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.006 ms/op
Iteration   1: 3.233 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.955 ms/op
                 getUser·p0.9999: 14.964 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   2: 3.231 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.362 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  8.667 ms/op
                 getUser·p0.9999: 14.215 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   3: 3.202 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.957 ms/op
                 getUser·p0.9999: 17.991 ms/op
                 getUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297917
  mean =      3.222 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 326 
    [ 1.250,  2.500) = 13688 
    [ 2.500,  3.750) = 240541 
    [ 3.750,  5.000) = 41908 
    [ 5.000,  6.250) = 649 
    [ 6.250,  7.500) = 308 
    [ 7.500,  8.750) = 281 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.362 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.208 ms/op
     p(99.9900) =     16.634 ms/op
     p(99.9990) =     18.417 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 4.528 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.310 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.011 ms/op
Iteration   1: 4.095 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  14.266 ms/op
                 listUser·p0.9999: 16.368 ms/op
                 listUser·p1.00:   16.663 ms/op

Iteration   2: 4.073 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.197 ms/op
                 listUser·p0.9999: 22.909 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   3: 4.080 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.626 ms/op
                 listUser·p0.9999: 26.051 ms/op
                 listUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235110
  mean =      4.083 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2462 
    [ 2.500,  5.000) = 204212 
    [ 5.000,  7.500) = 27058 
    [ 7.500, 10.000) = 1000 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     14.975 ms/op
     p(99.9900) =     24.100 ms/op
     p(99.9990) =     26.454 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.908 ± 1.775  ops/ms
ClientGrpc.existUser                       thrpt       3  10.489 ± 1.755  ops/ms
ClientGrpc.getUser                         thrpt       3  10.169 ± 1.393  ops/ms
ClientGrpc.listUser                        thrpt       3   7.953 ± 6.470  ops/ms
ClientGrpc.createUser                       avgt       3   3.237 ± 0.272   ms/op
ClientGrpc.existUser                        avgt       3   3.085 ± 0.331   ms/op
ClientGrpc.getUser                          avgt       3   3.176 ± 0.186   ms/op
ClientGrpc.listUser                         avgt       3   4.079 ± 1.625   ms/op
ClientGrpc.createUser                     sample  296187   3.243 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.487           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.203           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.157           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.617           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.624           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.430           ms/op
ClientGrpc.existUser                      sample  312356   3.073 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.592           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.060           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.152           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.615           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.367           ms/op
ClientGrpc.getUser                        sample  297917   3.222 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.362           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.191           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.047           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.208           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.634           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.547           ms/op
ClientGrpc.listUser                       sample  235110   4.083 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.892           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.975           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.100           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.542           ms/op
