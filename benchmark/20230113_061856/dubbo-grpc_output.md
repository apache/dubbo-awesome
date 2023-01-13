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
# Warmup Iteration   1: 3.686 ops/ms
# Warmup Iteration   2: 9.049 ops/ms
# Warmup Iteration   3: 10.043 ops/ms
Iteration   1: 10.222 ops/ms
Iteration   2: 10.283 ops/ms
Iteration   3: 10.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.290 ±(99.9%) 1.294 ops/ms [Average]
  (min, avg, max) = (10.222, 10.290, 10.364), stdev = 0.071
  CI (99.9%): [8.996, 11.583] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.486 ops/ms
# Warmup Iteration   2: 10.220 ops/ms
# Warmup Iteration   3: 10.516 ops/ms
Iteration   1: 10.559 ops/ms
Iteration   2: 10.645 ops/ms
Iteration   3: 10.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.599 ±(99.9%) 0.791 ops/ms [Average]
  (min, avg, max) = (10.559, 10.599, 10.645), stdev = 0.043
  CI (99.9%): [9.808, 11.390] (assumes normal distribution)


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
# Warmup Iteration   1: 6.550 ops/ms
# Warmup Iteration   2: 10.007 ops/ms
# Warmup Iteration   3: 10.106 ops/ms
Iteration   1: 10.119 ops/ms
Iteration   2: 10.106 ops/ms
Iteration   3: 10.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.123 ±(99.9%) 0.339 ops/ms [Average]
  (min, avg, max) = (10.106, 10.123, 10.142), stdev = 0.019
  CI (99.9%): [9.784, 10.461] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.503 ops/ms
# Warmup Iteration   2: 7.688 ops/ms
# Warmup Iteration   3: 7.767 ops/ms
Iteration   1: 7.982 ops/ms
Iteration   2: 8.085 ops/ms
Iteration   3: 8.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.046 ±(99.9%) 1.027 ops/ms [Average]
  (min, avg, max) = (7.982, 8.046, 8.085), stdev = 0.056
  CI (99.9%): [7.019, 9.072] (assumes normal distribution)


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
# Warmup Iteration   1: 4.298 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.002 ms/op
Iteration   1: 3.101 ±(99.9%) 0.002 ms/op
Iteration   2: 3.146 ±(99.9%) 0.002 ms/op
Iteration   3: 3.129 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.125 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (3.101, 3.125, 3.146), stdev = 0.023
  CI (99.9%): [2.709, 3.542] (assumes normal distribution)


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.002 ms/op
Iteration   1: 3.021 ±(99.9%) 0.002 ms/op
Iteration   2: 3.019 ±(99.9%) 0.003 ms/op
Iteration   3: 2.993 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.011 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (2.993, 3.011, 3.021), stdev = 0.016
  CI (99.9%): [2.726, 3.296] (assumes normal distribution)


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
# Warmup Iteration   1: 4.288 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.001 ms/op
Iteration   1: 3.141 ±(99.9%) 0.002 ms/op
Iteration   2: 3.105 ±(99.9%) 0.002 ms/op
Iteration   3: 3.151 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.132 ±(99.9%) 0.437 ms/op [Average]
  (min, avg, max) = (3.105, 3.132, 3.151), stdev = 0.024
  CI (99.9%): [2.695, 3.569] (assumes normal distribution)


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
# Warmup Iteration   1: 5.008 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.012 ms/op
Iteration   1: 4.055 ±(99.9%) 0.019 ms/op
Iteration   2: 3.994 ±(99.9%) 0.016 ms/op
Iteration   3: 3.845 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.965 ±(99.9%) 1.976 ms/op [Average]
  (min, avg, max) = (3.845, 3.965, 4.055), stdev = 0.108
  CI (99.9%): [1.988, 5.941] (assumes normal distribution)


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
# Warmup Iteration   1: 4.440 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.007 ms/op
Iteration   1: 3.138 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.567 ms/op
                 createUser·p0.9999: 18.835 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   2: 3.166 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  6.816 ms/op
                 createUser·p0.9999: 15.104 ms/op
                 createUser·p1.00:   15.516 ms/op

Iteration   3: 3.211 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  11.797 ms/op
                 createUser·p0.9999: 17.400 ms/op
                 createUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302388
  mean =      3.171 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 815 
    [ 1.250,  2.500) = 28456 
    [ 2.500,  3.750) = 227280 
    [ 3.750,  5.000) = 44704 
    [ 5.000,  6.250) = 550 
    [ 6.250,  7.500) = 290 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.422 ms/op
     p(99.9900) =     17.982 ms/op
     p(99.9990) =     19.070 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
Iteration   1: 2.880 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  5.512 ms/op
                 existUser·p0.9999: 12.576 ms/op
                 existUser·p1.00:   13.091 ms/op

Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  7.780 ms/op
                 existUser·p0.9999: 16.464 ms/op
                 existUser·p1.00:   18.186 ms/op

Iteration   3: 2.973 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  8.770 ms/op
                 existUser·p0.9999: 21.812 ms/op
                 existUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323854
  mean =      2.963 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57922 
    [ 2.500,  5.000) = 264914 
    [ 5.000,  7.500) = 688 
    [ 7.500, 10.000) = 159 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.547 ms/op
     p(99.9900) =     19.971 ms/op
     p(99.9990) =     23.323 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 4.467 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.280 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.007 ms/op
Iteration   1: 3.223 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.557 ms/op
                 getUser·p0.9999: 14.058 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   2: 3.183 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.245 ms/op
                 getUser·p0.9999: 15.151 ms/op
                 getUser·p1.00:   15.614 ms/op

Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.895 ms/op
                 getUser·p0.9999: 18.832 ms/op
                 getUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302329
  mean =      3.177 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21182 
    [ 2.500,  5.000) = 280087 
    [ 5.000,  7.500) = 809 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.152 ms/op
     p(99.9900) =     17.500 ms/op
     p(99.9990) =     20.282 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 5.060 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.011 ms/op
Iteration   1: 3.952 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  19.434 ms/op
                 listUser·p0.9999: 22.309 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   2: 3.944 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.804 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  20.108 ms/op
                 listUser·p0.9999: 24.067 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   3: 3.992 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  18.022 ms/op
                 listUser·p0.9999: 25.132 ms/op
                 listUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242110
  mean =      3.962 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2532 
    [ 2.500,  5.000) = 216509 
    [ 5.000,  7.500) = 21762 
    [ 7.500, 10.000) = 742 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     19.359 ms/op
     p(99.9900) =     24.202 ms/op
     p(99.9990) =     25.531 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.290 ± 1.294  ops/ms
ClientGrpc.existUser                       thrpt       3  10.599 ± 0.791  ops/ms
ClientGrpc.getUser                         thrpt       3  10.123 ± 0.339  ops/ms
ClientGrpc.listUser                        thrpt       3   8.046 ± 1.027  ops/ms
ClientGrpc.createUser                       avgt       3   3.125 ± 0.416   ms/op
ClientGrpc.existUser                        avgt       3   3.011 ± 0.285   ms/op
ClientGrpc.getUser                          avgt       3   3.132 ± 0.437   ms/op
ClientGrpc.listUser                         avgt       3   3.965 ± 1.976   ms/op
ClientGrpc.createUser                     sample  302388   3.171 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.763           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.158           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.051           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.422           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.982           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.169           ms/op
ClientGrpc.existUser                      sample  323854   2.963 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.588           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.547           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.971           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.462           ms/op
ClientGrpc.getUser                        sample  302329   3.177 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.849           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.142           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.051           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.152           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.500           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.546           ms/op
ClientGrpc.listUser                       sample  242110   3.962 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.804           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.359           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.202           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.625           ms/op
