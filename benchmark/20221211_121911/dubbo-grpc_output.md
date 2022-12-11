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
# Warmup Iteration   1: 3.919 ops/ms
# Warmup Iteration   2: 8.847 ops/ms
# Warmup Iteration   3: 9.792 ops/ms
Iteration   1: 9.859 ops/ms
Iteration   2: 10.206 ops/ms
Iteration   3: 9.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.007 ±(99.9%) 3.266 ops/ms [Average]
  (min, avg, max) = (9.859, 10.007, 10.206), stdev = 0.179
  CI (99.9%): [6.741, 13.273] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.324 ops/ms
# Warmup Iteration   2: 10.181 ops/ms
# Warmup Iteration   3: 10.310 ops/ms
Iteration   1: 10.821 ops/ms
Iteration   2: 10.662 ops/ms
Iteration   3: 10.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.612 ±(99.9%) 4.337 ops/ms [Average]
  (min, avg, max) = (10.353, 10.612, 10.821), stdev = 0.238
  CI (99.9%): [6.275, 14.949] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.465 ops/ms
# Warmup Iteration   2: 9.693 ops/ms
# Warmup Iteration   3: 9.762 ops/ms
Iteration   1: 9.771 ops/ms
Iteration   2: 9.827 ops/ms
Iteration   3: 9.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.791 ±(99.9%) 0.566 ops/ms [Average]
  (min, avg, max) = (9.771, 9.791, 9.827), stdev = 0.031
  CI (99.9%): [9.226, 10.357] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.685 ops/ms
# Warmup Iteration   2: 7.224 ops/ms
# Warmup Iteration   3: 7.490 ops/ms
Iteration   1: 7.710 ops/ms
Iteration   2: 7.815 ops/ms
Iteration   3: 7.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.738 ±(99.9%) 1.229 ops/ms [Average]
  (min, avg, max) = (7.690, 7.738, 7.815), stdev = 0.067
  CI (99.9%): [6.510, 8.967] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.792 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.003 ms/op
Iteration   1: 3.221 ±(99.9%) 0.002 ms/op
Iteration   2: 3.194 ±(99.9%) 0.002 ms/op
Iteration   3: 3.262 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.226 ±(99.9%) 0.633 ms/op [Average]
  (min, avg, max) = (3.194, 3.226, 3.262), stdev = 0.035
  CI (99.9%): [2.593, 3.859] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.235 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.002 ms/op
Iteration   1: 3.100 ±(99.9%) 0.001 ms/op
Iteration   2: 3.052 ±(99.9%) 0.002 ms/op
Iteration   3: 3.062 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.072 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (3.052, 3.072, 3.100), stdev = 0.025
  CI (99.9%): [2.613, 3.530] (assumes normal distribution)


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
# Warmup Iteration   1: 4.353 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.331 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.003 ms/op
Iteration   1: 3.260 ±(99.9%) 0.002 ms/op
Iteration   2: 3.242 ±(99.9%) 0.002 ms/op
Iteration   3: 3.211 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.238 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (3.211, 3.238, 3.260), stdev = 0.025
  CI (99.9%): [2.781, 3.694] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.783 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.337 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.013 ms/op
Iteration   1: 4.093 ±(99.9%) 0.011 ms/op
Iteration   2: 4.205 ±(99.9%) 0.021 ms/op
Iteration   3: 4.236 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.178 ±(99.9%) 1.370 ms/op [Average]
  (min, avg, max) = (4.093, 4.178, 4.236), stdev = 0.075
  CI (99.9%): [2.808, 5.548] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.672 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.399 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.007 ms/op
Iteration   1: 3.246 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   4.877 ms/op
                 createUser·p0.999:  12.010 ms/op
                 createUser·p0.9999: 16.876 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   2: 3.274 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   4.648 ms/op
                 createUser·p0.999:  7.782 ms/op
                 createUser·p0.9999: 15.396 ms/op
                 createUser·p1.00:   15.974 ms/op

Iteration   3: 3.259 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.417 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  9.454 ms/op
                 createUser·p0.9999: 19.857 ms/op
                 createUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 294244
  mean =      3.260 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18608 
    [ 2.500,  5.000) = 273943 
    [ 5.000,  7.500) = 1189 
    [ 7.500, 10.000) = 233 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.417 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      9.384 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     19.927 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 4.283 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.007 ms/op
Iteration   1: 3.072 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.717 ms/op
                 existUser·p0.9999: 20.073 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  11.575 ms/op
                 existUser·p0.9999: 15.458 ms/op
                 existUser·p1.00:   15.778 ms/op

Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  8.143 ms/op
                 existUser·p0.9999: 19.071 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 308595
  mean =      3.109 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33748 
    [ 2.500,  5.000) = 273613 
    [ 5.000,  7.500) = 801 
    [ 7.500, 10.000) = 168 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.343 ms/op
     p(99.9900) =     19.178 ms/op
     p(99.9990) =     20.608 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 4.356 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.007 ms/op
Iteration   1: 3.252 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.942 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.692 ms/op
                 getUser·p0.9999: 14.046 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   2: 3.222 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.784 ms/op
                 getUser·p0.9999: 16.876 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 3.268 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   4.981 ms/op
                 getUser·p0.999:  10.387 ms/op
                 getUser·p0.9999: 17.806 ms/op
                 getUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 295789
  mean =      3.247 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 347 
    [ 1.250,  2.500) = 16397 
    [ 2.500,  3.750) = 226834 
    [ 3.750,  5.000) = 50627 
    [ 5.000,  6.250) = 844 
    [ 6.250,  7.500) = 303 
    [ 7.500,  8.750) = 160 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 59 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      8.474 ms/op
     p(99.9900) =     17.283 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 4.942 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.454 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.138 ±(99.9%) 0.011 ms/op
Iteration   1: 4.123 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.212 ms/op
                 listUser·p0.9999: 21.045 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   2: 4.181 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  16.261 ms/op
                 listUser·p0.9999: 28.148 ms/op
                 listUser·p1.00:   30.474 ms/op

Iteration   3: 4.159 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.038 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  18.550 ms/op
                 listUser·p0.9999: 29.487 ms/op
                 listUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 231058
  mean =      4.154 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2427 
    [ 2.500,  5.000) = 196680 
    [ 5.000,  7.500) = 30104 
    [ 7.500, 10.000) = 1296 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.038 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     15.876 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     30.431 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.007 ± 3.266  ops/ms
ClientGrpc.existUser                       thrpt       3  10.612 ± 4.337  ops/ms
ClientGrpc.getUser                         thrpt       3   9.791 ± 0.566  ops/ms
ClientGrpc.listUser                        thrpt       3   7.738 ± 1.229  ops/ms
ClientGrpc.createUser                       avgt       3   3.226 ± 0.633   ms/op
ClientGrpc.existUser                        avgt       3   3.072 ± 0.458   ms/op
ClientGrpc.getUser                          avgt       3   3.238 ± 0.457   ms/op
ClientGrpc.listUser                         avgt       3   4.178 ± 1.370   ms/op
ClientGrpc.createUser                     sample  294244   3.260 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.417           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.236           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.157           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.384           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.383           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.087           ms/op
ClientGrpc.existUser                      sample  308595   3.109 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.753           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.097           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.969           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.343           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.178           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.742           ms/op
ClientGrpc.getUser                        sample  295789   3.247 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.640           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.215           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.953           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.141           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.474           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.283           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.252           ms/op
ClientGrpc.listUser                       sample  231058   4.154 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.038           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.961           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.046           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.258           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.876           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.213           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.474           ms/op
