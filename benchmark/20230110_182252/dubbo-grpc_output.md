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
# Warmup Iteration   1: 2.985 ops/ms
# Warmup Iteration   2: 6.702 ops/ms
# Warmup Iteration   3: 7.915 ops/ms
Iteration   1: 8.103 ops/ms
Iteration   2: 8.346 ops/ms
Iteration   3: 8.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.172 ±(99.9%) 2.772 ops/ms [Average]
  (min, avg, max) = (8.067, 8.172, 8.346), stdev = 0.152
  CI (99.9%): [5.401, 10.944] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.191 ops/ms
# Warmup Iteration   2: 8.314 ops/ms
# Warmup Iteration   3: 8.455 ops/ms
Iteration   1: 8.330 ops/ms
Iteration   2: 8.529 ops/ms
Iteration   3: 8.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.429 ±(99.9%) 1.814 ops/ms [Average]
  (min, avg, max) = (8.330, 8.429, 8.529), stdev = 0.099
  CI (99.9%): [6.614, 10.243] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.316 ops/ms
# Warmup Iteration   2: 7.307 ops/ms
# Warmup Iteration   3: 7.898 ops/ms
Iteration   1: 7.909 ops/ms
Iteration   2: 7.911 ops/ms
Iteration   3: 7.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.825 ±(99.9%) 2.710 ops/ms [Average]
  (min, avg, max) = (7.653, 7.825, 7.911), stdev = 0.149
  CI (99.9%): [5.115, 10.534] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.315 ops/ms
# Warmup Iteration   2: 5.409 ops/ms
# Warmup Iteration   3: 6.164 ops/ms
Iteration   1: 6.185 ops/ms
Iteration   2: 6.622 ops/ms
Iteration   3: 6.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.450 ±(99.9%) 4.252 ops/ms [Average]
  (min, avg, max) = (6.185, 6.450, 6.622), stdev = 0.233
  CI (99.9%): [2.198, 10.703] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.938 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.241 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.002 ms/op
Iteration   1: 4.081 ±(99.9%) 0.003 ms/op
Iteration   2: 4.085 ±(99.9%) 0.001 ms/op
Iteration   3: 4.175 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.114 ±(99.9%) 0.972 ms/op [Average]
  (min, avg, max) = (4.081, 4.114, 4.175), stdev = 0.053
  CI (99.9%): [3.141, 5.086] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.355 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.002 ms/op
Iteration   1: 3.983 ±(99.9%) 0.003 ms/op
Iteration   2: 3.806 ±(99.9%) 0.002 ms/op
Iteration   3: 3.802 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.864 ±(99.9%) 1.889 ms/op [Average]
  (min, avg, max) = (3.802, 3.864, 3.983), stdev = 0.104
  CI (99.9%): [1.975, 5.753] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.663 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.007 ms/op
Iteration   1: 3.978 ±(99.9%) 0.003 ms/op
Iteration   2: 4.015 ±(99.9%) 0.002 ms/op
Iteration   3: 3.979 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.991 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (3.978, 3.991, 4.015), stdev = 0.021
  CI (99.9%): [3.602, 4.380] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.060 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.458 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.161 ±(99.9%) 0.012 ms/op
Iteration   1: 4.917 ±(99.9%) 0.008 ms/op
Iteration   2: 5.168 ±(99.9%) 0.029 ms/op
Iteration   3: 4.913 ±(99.9%) 0.050 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.999 ±(99.9%) 2.667 ms/op [Average]
  (min, avg, max) = (4.913, 4.999, 5.168), stdev = 0.146
  CI (99.9%): [2.332, 7.667] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.974 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.066 ±(99.9%) 0.012 ms/op
Iteration   1: 3.997 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   5.046 ms/op
                 createUser·p0.95:   5.456 ms/op
                 createUser·p0.99:   6.849 ms/op
                 createUser·p0.999:  13.288 ms/op
                 createUser·p0.9999: 16.941 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   2: 4.072 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   4.018 ms/op
                 createUser·p0.90:   5.235 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  9.944 ms/op
                 createUser·p0.9999: 18.552 ms/op
                 createUser·p1.00:   18.776 ms/op

Iteration   3: 3.715 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  17.397 ms/op
                 createUser·p0.9999: 19.775 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 244590
  mean =      3.922 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5068 
    [ 2.500,  5.000) = 214881 
    [ 5.000,  7.500) = 23280 
    [ 7.500, 10.000) = 827 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     15.156 ms/op
     p(99.9900) =     19.384 ms/op
     p(99.9990) =     21.856 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.505 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.015 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.012 ms/op
Iteration   1: 3.746 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.128 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  11.243 ms/op
                 existUser·p0.9999: 15.188 ms/op
                 existUser·p1.00:   15.466 ms/op

Iteration   2: 3.762 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.071 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  11.760 ms/op
                 existUser·p0.9999: 17.203 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   3: 3.890 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   5.005 ms/op
                 existUser·p0.95:   5.358 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  12.239 ms/op
                 existUser·p0.9999: 17.498 ms/op
                 existUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 252673
  mean =      3.798 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 162 
    [ 1.250,  2.500) = 6620 
    [ 2.500,  3.750) = 125302 
    [ 3.750,  5.000) = 101977 
    [ 5.000,  6.250) = 16065 
    [ 6.250,  7.500) = 1406 
    [ 7.500,  8.750) = 454 
    [ 8.750, 10.000) = 245 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 142 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 55 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     11.736 ms/op
     p(99.9900) =     17.129 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.827 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.429 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.012 ms/op
Iteration   1: 3.854 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.850 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   6.529 ms/op
                 getUser·p0.999:  12.325 ms/op
                 getUser·p0.9999: 14.752 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   2: 3.985 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.040 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   5.063 ms/op
                 getUser·p0.95:   5.374 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  9.988 ms/op
                 getUser·p0.9999: 18.833 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   3: 3.908 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.923 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  9.623 ms/op
                 getUser·p0.9999: 19.610 ms/op
                 getUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 245168
  mean =      3.915 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5153 
    [ 2.500,  5.000) = 217207 
    [ 5.000,  7.500) = 21587 
    [ 7.500, 10.000) = 950 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     10.191 ms/op
     p(99.9900) =     18.692 ms/op
     p(99.9990) =     20.087 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 6.678 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.220 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.037 ±(99.9%) 0.019 ms/op
Iteration   1: 5.034 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.975 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.939 ms/op
                 listUser·p0.95:   7.643 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  16.923 ms/op
                 listUser·p0.9999: 20.609 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   2: 5.146 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   4.866 ms/op
                 listUser·p0.90:   6.824 ms/op
                 listUser·p0.95:   7.692 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 21.810 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   3: 5.105 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   6.922 ms/op
                 listUser·p0.95:   7.700 ms/op
                 listUser·p0.99:   10.732 ms/op
                 listUser·p0.999:  21.301 ms/op
                 listUser·p0.9999: 29.096 ms/op
                 listUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 188298
  mean =      5.094 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 377 
    [ 2.500,  5.000) = 110080 
    [ 5.000,  7.500) = 66644 
    [ 7.500, 10.000) = 9497 
    [10.000, 12.500) = 1026 
    [12.500, 15.000) = 280 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      6.898 ms/op
     p(95.0000) =      7.676 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     27.039 ms/op
     p(99.9990) =     29.427 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.172 ± 2.772  ops/ms
ClientGrpc.existUser                       thrpt       3   8.429 ± 1.814  ops/ms
ClientGrpc.getUser                         thrpt       3   7.825 ± 2.710  ops/ms
ClientGrpc.listUser                        thrpt       3   6.450 ± 4.252  ops/ms
ClientGrpc.createUser                       avgt       3   4.114 ± 0.972   ms/op
ClientGrpc.existUser                        avgt       3   3.864 ± 1.889   ms/op
ClientGrpc.getUser                          avgt       3   3.991 ± 0.389   ms/op
ClientGrpc.listUser                         avgt       3   4.999 ± 2.667   ms/op
ClientGrpc.createUser                     sample  244590   3.922 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.026           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.005           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.382           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.439           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.156           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.384           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.969           ms/op
ClientGrpc.existUser                      sample  252673   3.798 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.800           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.841           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.202           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.259           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.736           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.129           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.793           ms/op
ClientGrpc.getUser                        sample  245168   3.915 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.040           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.956           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.341           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.472           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.191           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.692           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.218           ms/op
ClientGrpc.listUser                       sample  188298   5.094 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.975           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.676           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.781           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.547           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.039           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.688           ms/op
