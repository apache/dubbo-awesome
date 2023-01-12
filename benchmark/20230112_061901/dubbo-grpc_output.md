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
# Warmup Iteration   1: 4.423 ops/ms
# Warmup Iteration   2: 9.211 ops/ms
# Warmup Iteration   3: 9.827 ops/ms
Iteration   1: 10.011 ops/ms
Iteration   2: 10.162 ops/ms
Iteration   3: 9.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.019 ±(99.9%) 2.558 ops/ms [Average]
  (min, avg, max) = (9.882, 10.019, 10.162), stdev = 0.140
  CI (99.9%): [7.460, 12.577] (assumes normal distribution)


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
# Warmup Iteration   1: 7.614 ops/ms
# Warmup Iteration   2: 10.160 ops/ms
# Warmup Iteration   3: 10.209 ops/ms
Iteration   1: 10.993 ops/ms
Iteration   2: 10.536 ops/ms
Iteration   3: 10.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.667 ±(99.9%) 5.187 ops/ms [Average]
  (min, avg, max) = (10.472, 10.667, 10.993), stdev = 0.284
  CI (99.9%): [5.480, 15.853] (assumes normal distribution)


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
# Warmup Iteration   1: 6.764 ops/ms
# Warmup Iteration   2: 9.989 ops/ms
# Warmup Iteration   3: 10.314 ops/ms
Iteration   1: 9.969 ops/ms
Iteration   2: 9.930 ops/ms
Iteration   3: 10.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.983 ±(99.9%) 1.119 ops/ms [Average]
  (min, avg, max) = (9.930, 9.983, 10.050), stdev = 0.061
  CI (99.9%): [8.865, 11.102] (assumes normal distribution)


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
# Warmup Iteration   1: 5.260 ops/ms
# Warmup Iteration   2: 7.539 ops/ms
# Warmup Iteration   3: 7.683 ops/ms
Iteration   1: 7.780 ops/ms
Iteration   2: 7.735 ops/ms
Iteration   3: 7.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.774 ±(99.9%) 0.670 ops/ms [Average]
  (min, avg, max) = (7.735, 7.774, 7.807), stdev = 0.037
  CI (99.9%): [7.105, 8.444] (assumes normal distribution)


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
# Warmup Iteration   1: 4.323 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.002 ms/op
Iteration   1: 3.188 ±(99.9%) 0.011 ms/op
Iteration   2: 3.227 ±(99.9%) 0.001 ms/op
Iteration   3: 3.217 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.211 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (3.188, 3.211, 3.227), stdev = 0.020
  CI (99.9%): [2.845, 3.577] (assumes normal distribution)


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
# Warmup Iteration   1: 3.722 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.002 ms/op
Iteration   1: 3.063 ±(99.9%) 0.003 ms/op
Iteration   2: 3.057 ±(99.9%) 0.002 ms/op
Iteration   3: 3.024 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.048 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (3.024, 3.048, 3.063), stdev = 0.021
  CI (99.9%): [2.665, 3.431] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.378 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.003 ms/op
Iteration   1: 3.195 ±(99.9%) 0.003 ms/op
Iteration   2: 3.564 ±(99.9%) 0.004 ms/op
Iteration   3: 3.368 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.376 ±(99.9%) 3.372 ms/op [Average]
  (min, avg, max) = (3.195, 3.376, 3.564), stdev = 0.185
  CI (99.9%): [0.004, 6.748] (assumes normal distribution)


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
# Warmup Iteration   1: 6.256 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.481 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.460 ±(99.9%) 0.010 ms/op
Iteration   1: 4.384 ±(99.9%) 0.005 ms/op
Iteration   2: 4.338 ±(99.9%) 0.009 ms/op
Iteration   3: 4.348 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.357 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (4.338, 4.357, 4.384), stdev = 0.024
  CI (99.9%): [3.918, 4.795] (assumes normal distribution)


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
# Warmup Iteration   1: 4.975 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.009 ms/op
Iteration   1: 3.439 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  8.684 ms/op
                 createUser·p0.9999: 13.747 ms/op
                 createUser·p1.00:   14.156 ms/op

Iteration   2: 3.377 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.770 ms/op
                 createUser·p0.999:  12.485 ms/op
                 createUser·p0.9999: 16.697 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   3: 3.299 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.161 ms/op
                 createUser·p0.999:  15.499 ms/op
                 createUser·p0.9999: 20.752 ms/op
                 createUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 284751
  mean =      3.371 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14069 
    [ 2.500,  5.000) = 266493 
    [ 5.000,  7.500) = 3121 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     12.706 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     21.009 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 4.605 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.007 ms/op
Iteration   1: 3.260 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  7.552 ms/op
                 existUser·p0.9999: 14.683 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   2: 3.225 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  11.158 ms/op
                 existUser·p0.9999: 14.451 ms/op
                 existUser·p1.00:   16.237 ms/op

Iteration   3: 3.091 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.004 ms/op
                 existUser·p0.9999: 20.796 ms/op
                 existUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 300857
  mean =      3.190 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20093 
    [ 2.500,  5.000) = 279440 
    [ 5.000,  7.500) = 841 
    [ 7.500, 10.000) = 237 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     19.400 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 4.754 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.443 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.008 ms/op
Iteration   1: 3.223 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  8.844 ms/op
                 getUser·p0.9999: 21.040 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   2: 3.354 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   4.948 ms/op
                 getUser·p0.999:  12.446 ms/op
                 getUser·p0.9999: 23.903 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   3: 3.412 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.100 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  7.653 ms/op
                 getUser·p0.9999: 26.116 ms/op
                 getUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 288210
  mean =      3.328 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11374 
    [ 2.500,  5.000) = 274639 
    [ 5.000,  7.500) = 1654 
    [ 7.500, 10.000) = 277 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =      9.581 ms/op
     p(99.9900) =     25.178 ms/op
     p(99.9990) =     26.149 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 6.707 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.012 ms/op
Iteration   1: 4.124 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  16.179 ms/op
                 listUser·p0.9999: 20.643 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   2: 4.088 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  16.760 ms/op
                 listUser·p0.9999: 23.631 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   3: 4.144 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  15.792 ms/op
                 listUser·p0.9999: 18.425 ms/op
                 listUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232926
  mean =      4.119 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1965 
    [ 2.500,  5.000) = 205420 
    [ 5.000,  7.500) = 23878 
    [ 7.500, 10.000) = 1160 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     22.928 ms/op
     p(99.9990) =     23.866 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.019 ± 2.558  ops/ms
ClientGrpc.existUser                       thrpt       3  10.667 ± 5.187  ops/ms
ClientGrpc.getUser                         thrpt       3   9.983 ± 1.119  ops/ms
ClientGrpc.listUser                        thrpt       3   7.774 ± 0.670  ops/ms
ClientGrpc.createUser                       avgt       3   3.211 ± 0.366   ms/op
ClientGrpc.existUser                        avgt       3   3.048 ± 0.383   ms/op
ClientGrpc.getUser                          avgt       3   3.376 ± 3.372   ms/op
ClientGrpc.listUser                         avgt       3   4.357 ± 0.439   ms/op
ClientGrpc.createUser                     sample  284751   3.371 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.746           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.322           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.104           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.706           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.825           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.070           ms/op
ClientGrpc.existUser                      sample  300857   3.190 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.718           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.166           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.051           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.471           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.400           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.594           ms/op
ClientGrpc.getUser                        sample  288210   3.328 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.786           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.281           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.014           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.858           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.581           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.178           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.182           ms/op
ClientGrpc.listUser                       sample  232926   4.119 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.067           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.957           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.849           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.152           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.073           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.928           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.986           ms/op
