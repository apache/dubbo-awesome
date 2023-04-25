# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
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
# Warmup Iteration   2: 8.808 ops/ms
# Warmup Iteration   3: 10.331 ops/ms
Iteration   1: 10.575 ops/ms
Iteration   2: 10.582 ops/ms
Iteration   3: 10.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.584 ±(99.9%) 0.163 ops/ms [Average]
  (min, avg, max) = (10.575, 10.584, 10.593), stdev = 0.009
  CI (99.9%): [10.421, 10.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.491 ops/ms
# Warmup Iteration   2: 10.859 ops/ms
# Warmup Iteration   3: 11.045 ops/ms
Iteration   1: 11.178 ops/ms
Iteration   2: 11.109 ops/ms
Iteration   3: 11.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.161 ±(99.9%) 0.853 ops/ms [Average]
  (min, avg, max) = (11.109, 11.161, 11.197), stdev = 0.047
  CI (99.9%): [10.308, 12.015] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.654 ops/ms
# Warmup Iteration   2: 10.417 ops/ms
# Warmup Iteration   3: 10.671 ops/ms
Iteration   1: 10.682 ops/ms
Iteration   2: 10.745 ops/ms
Iteration   3: 10.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.723 ±(99.9%) 0.643 ops/ms [Average]
  (min, avg, max) = (10.682, 10.723, 10.745), stdev = 0.035
  CI (99.9%): [10.079, 11.366] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.848 ops/ms
# Warmup Iteration   2: 7.878 ops/ms
# Warmup Iteration   3: 8.429 ops/ms
Iteration   1: 8.076 ops/ms
Iteration   2: 8.089 ops/ms
Iteration   3: 8.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.135 ±(99.9%) 1.666 ops/ms [Average]
  (min, avg, max) = (8.076, 8.135, 8.240), stdev = 0.091
  CI (99.9%): [6.469, 9.802] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.965 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.011 ms/op
Iteration   1: 3.042 ±(99.9%) 0.002 ms/op
Iteration   2: 2.975 ±(99.9%) 0.003 ms/op
Iteration   3: 3.000 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.006 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (2.975, 3.006, 3.042), stdev = 0.034
  CI (99.9%): [2.390, 3.621] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.852 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.968 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.002 ms/op
Iteration   1: 2.844 ±(99.9%) 0.003 ms/op
Iteration   2: 2.824 ±(99.9%) 0.003 ms/op
Iteration   3: 2.884 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.851 ±(99.9%) 0.563 ms/op [Average]
  (min, avg, max) = (2.824, 2.851, 2.884), stdev = 0.031
  CI (99.9%): [2.287, 3.414] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.076 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.003 ms/op
Iteration   1: 3.017 ±(99.9%) 0.002 ms/op
Iteration   2: 3.093 ±(99.9%) 0.004 ms/op
Iteration   3: 3.046 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.052 ±(99.9%) 0.700 ms/op [Average]
  (min, avg, max) = (3.017, 3.052, 3.093), stdev = 0.038
  CI (99.9%): [2.352, 3.752] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.941 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.010 ms/op
Iteration   1: 3.916 ±(99.9%) 0.032 ms/op
Iteration   2: 3.957 ±(99.9%) 0.015 ms/op
Iteration   3: 3.835 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.903 ±(99.9%) 1.132 ms/op [Average]
  (min, avg, max) = (3.835, 3.903, 3.957), stdev = 0.062
  CI (99.9%): [2.771, 5.035] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.027 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.008 ms/op
Iteration   1: 2.997 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.924 ms/op
                 createUser·p0.9999: 15.657 ms/op
                 createUser·p1.00:   15.974 ms/op

Iteration   2: 3.026 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.347 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  9.378 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  9.590 ms/op
                 createUser·p0.9999: 19.366 ms/op
                 createUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318999
  mean =      3.010 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25962 
    [ 2.500,  5.000) = 291127 
    [ 5.000,  7.500) = 1408 
    [ 7.500, 10.000) = 214 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.347 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     21.106 ms/op
     p(99.9990) =     23.908 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.652 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.961 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.006 ms/op
Iteration   1: 2.832 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.178 ms/op
                 existUser·p0.95:   3.301 ms/op
                 existUser·p0.99:   4.059 ms/op
                 existUser·p0.999:  7.041 ms/op
                 existUser·p0.9999: 13.950 ms/op
                 existUser·p1.00:   15.679 ms/op

Iteration   2: 2.884 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.567 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  6.820 ms/op
                 existUser·p0.9999: 11.862 ms/op
                 existUser·p1.00:   12.075 ms/op

Iteration   3: 2.833 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.059 ms/op
                 existUser·p0.999:  6.579 ms/op
                 existUser·p0.9999: 14.153 ms/op
                 existUser·p1.00:   14.713 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336638
  mean =      2.850 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4179 
    [ 1.250,  2.500) = 40765 
    [ 2.500,  3.750) = 282635 
    [ 3.750,  5.000) = 7900 
    [ 5.000,  6.250) = 706 
    [ 6.250,  7.500) = 226 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      6.783 ms/op
     p(99.9900) =     13.697 ms/op
     p(99.9990) =     14.707 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.627 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
Iteration   1: 3.006 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.436 ms/op
                 getUser·p0.999:  7.513 ms/op
                 getUser·p0.9999: 12.785 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.580 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.520 ms/op
                 getUser·p0.9999: 20.709 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.464 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  8.421 ms/op
                 getUser·p0.9999: 26.837 ms/op
                 getUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319146
  mean =      3.007 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23514 
    [ 2.500,  5.000) = 293761 
    [ 5.000,  7.500) = 1503 
    [ 7.500, 10.000) = 188 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      7.716 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     27.066 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.693 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.010 ms/op
Iteration   1: 3.895 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  12.131 ms/op
                 listUser·p0.9999: 13.517 ms/op
                 listUser·p1.00:   14.795 ms/op

Iteration   2: 3.973 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 26.704 ms/op
                 listUser·p1.00:   27.099 ms/op

Iteration   3: 3.894 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.857 ms/op
                 listUser·p0.9999: 18.310 ms/op
                 listUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244844
  mean =      3.921 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4091 
    [ 2.500,  5.000) = 219200 
    [ 5.000,  7.500) = 20017 
    [ 7.500, 10.000) = 997 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     21.873 ms/op
     p(99.9990) =     26.971 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.584 ± 0.163  ops/ms
ClientGrpc.existUser                       thrpt       3  11.161 ± 0.853  ops/ms
ClientGrpc.getUser                         thrpt       3  10.723 ± 0.643  ops/ms
ClientGrpc.listUser                        thrpt       3   8.135 ± 1.666  ops/ms
ClientGrpc.createUser                       avgt       3   3.006 ± 0.616   ms/op
ClientGrpc.existUser                        avgt       3   2.851 ± 0.563   ms/op
ClientGrpc.getUser                          avgt       3   3.052 ± 0.700   ms/op
ClientGrpc.listUser                         avgt       3   3.903 ± 1.132   ms/op
ClientGrpc.createUser                     sample  318999   3.010 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.347           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.339           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.106           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.052           ms/op
ClientGrpc.existUser                      sample  336638   2.850 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.560           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.783           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.697           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.679           ms/op
ClientGrpc.getUser                        sample  319146   3.007 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.464           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.716           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.313           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.296           ms/op
ClientGrpc.listUser                       sample  244844   3.921 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.024           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.926           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.873           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.099           ms/op
