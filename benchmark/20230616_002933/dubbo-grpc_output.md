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
# Warmup Iteration   1: 3.958 ops/ms
# Warmup Iteration   2: 8.799 ops/ms
# Warmup Iteration   3: 10.023 ops/ms
Iteration   1: 10.524 ops/ms
Iteration   2: 10.472 ops/ms
Iteration   3: 10.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.426 ±(99.9%) 2.310 ops/ms [Average]
  (min, avg, max) = (10.283, 10.426, 10.524), stdev = 0.127
  CI (99.9%): [8.117, 12.736] (assumes normal distribution)


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
# Warmup Iteration   1: 7.267 ops/ms
# Warmup Iteration   2: 10.491 ops/ms
# Warmup Iteration   3: 11.009 ops/ms
Iteration   1: 10.931 ops/ms
Iteration   2: 11.004 ops/ms
Iteration   3: 11.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.036 ±(99.9%) 2.261 ops/ms [Average]
  (min, avg, max) = (10.931, 11.036, 11.173), stdev = 0.124
  CI (99.9%): [8.775, 13.297] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.670 ops/ms
# Warmup Iteration   2: 9.899 ops/ms
# Warmup Iteration   3: 10.324 ops/ms
Iteration   1: 10.470 ops/ms
Iteration   2: 10.575 ops/ms
Iteration   3: 10.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.491 ±(99.9%) 1.366 ops/ms [Average]
  (min, avg, max) = (10.430, 10.491, 10.575), stdev = 0.075
  CI (99.9%): [9.126, 11.857] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.494 ops/ms
# Warmup Iteration   2: 7.770 ops/ms
# Warmup Iteration   3: 7.847 ops/ms
Iteration   1: 8.085 ops/ms
Iteration   2: 8.189 ops/ms
Iteration   3: 8.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.174 ±(99.9%) 1.512 ops/ms [Average]
  (min, avg, max) = (8.085, 8.174, 8.249), stdev = 0.083
  CI (99.9%): [6.662, 9.686] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.217 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.006 ms/op
Iteration   1: 3.101 ±(99.9%) 0.003 ms/op
Iteration   2: 3.115 ±(99.9%) 0.003 ms/op
Iteration   3: 3.108 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.108 ±(99.9%) 0.135 ms/op [Average]
  (min, avg, max) = (3.101, 3.108, 3.115), stdev = 0.007
  CI (99.9%): [2.973, 3.243] (assumes normal distribution)


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 2.871 ±(99.9%) 0.003 ms/op
Iteration   1: 2.948 ±(99.9%) 0.003 ms/op
Iteration   2: 2.937 ±(99.9%) 0.002 ms/op
Iteration   3: 2.932 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.939 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (2.932, 2.939, 2.948), stdev = 0.008
  CI (99.9%): [2.796, 3.082] (assumes normal distribution)


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
# Warmup Iteration   1: 4.321 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.002 ms/op
Iteration   1: 3.053 ±(99.9%) 0.003 ms/op
Iteration   2: 3.020 ±(99.9%) 0.002 ms/op
Iteration   3: 3.051 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.041 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (3.020, 3.041, 3.053), stdev = 0.019
  CI (99.9%): [2.703, 3.379] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.720 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.013 ms/op
Iteration   1: 3.991 ±(99.9%) 0.018 ms/op
Iteration   2: 3.961 ±(99.9%) 0.009 ms/op
Iteration   3: 3.945 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.965 ±(99.9%) 0.422 ms/op [Average]
  (min, avg, max) = (3.945, 3.965, 3.991), stdev = 0.023
  CI (99.9%): [3.543, 4.388] (assumes normal distribution)


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
# Warmup Iteration   1: 4.308 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  8.776 ms/op
                 createUser·p0.9999: 13.388 ms/op
                 createUser·p1.00:   14.942 ms/op

Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  7.911 ms/op
                 createUser·p0.9999: 15.757 ms/op
                 createUser·p1.00:   15.991 ms/op

Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.550 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  11.739 ms/op
                 createUser·p0.9999: 22.792 ms/op
                 createUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313196
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21521 
    [ 2.500,  5.000) = 289505 
    [ 5.000,  7.500) = 1681 
    [ 7.500, 10.000) = 186 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      9.087 ms/op
     p(99.9900) =     20.919 ms/op
     p(99.9990) =     23.064 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 4.295 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.006 ms/op
Iteration   1: 2.957 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  8.082 ms/op
                 existUser·p0.9999: 14.407 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   2: 2.962 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  8.831 ms/op
                 existUser·p0.9999: 23.312 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   3: 2.921 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.695 ms/op
                 existUser·p0.999:  7.979 ms/op
                 existUser·p0.9999: 21.170 ms/op
                 existUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325607
  mean =      2.946 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27960 
    [ 2.500,  5.000) = 295787 
    [ 5.000,  7.500) = 1352 
    [ 7.500, 10.000) = 300 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      8.334 ms/op
     p(99.9900) =     22.170 ms/op
     p(99.9990) =     23.650 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 4.399 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.007 ms/op
Iteration   1: 3.082 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.616 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.491 ms/op
                 getUser·p0.999:  7.303 ms/op
                 getUser·p0.9999: 16.054 ms/op
                 getUser·p1.00:   18.055 ms/op

Iteration   2: 3.075 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.310 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  8.650 ms/op
                 getUser·p0.9999: 18.166 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   3: 3.047 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.457 ms/op
                 getUser·p0.9999: 21.807 ms/op
                 getUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312731
  mean =      3.068 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18619 
    [ 2.500,  5.000) = 292303 
    [ 5.000,  7.500) = 1436 
    [ 7.500, 10.000) = 140 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.310 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      8.069 ms/op
     p(99.9900) =     20.471 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 5.087 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.191 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.011 ms/op
Iteration   1: 4.012 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.045 ms/op
                 listUser·p0.9999: 20.907 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   2: 3.971 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.440 ms/op
                 listUser·p0.9999: 23.357 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   3: 4.046 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  17.264 ms/op
                 listUser·p0.9999: 26.848 ms/op
                 listUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239578
  mean =      4.010 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2047 
    [ 2.500,  5.000) = 214140 
    [ 5.000,  7.500) = 21822 
    [ 7.500, 10.000) = 1073 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     14.848 ms/op
     p(99.9900) =     25.266 ms/op
     p(99.9990) =     27.335 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.426 ± 2.310  ops/ms
ClientGrpc.existUser                       thrpt       3  11.036 ± 2.261  ops/ms
ClientGrpc.getUser                         thrpt       3  10.491 ± 1.366  ops/ms
ClientGrpc.listUser                        thrpt       3   8.174 ± 1.512  ops/ms
ClientGrpc.createUser                       avgt       3   3.108 ± 0.135   ms/op
ClientGrpc.existUser                        avgt       3   2.939 ± 0.143   ms/op
ClientGrpc.getUser                          avgt       3   3.041 ± 0.338   ms/op
ClientGrpc.listUser                         avgt       3   3.965 ± 0.422   ms/op
ClientGrpc.createUser                     sample  313196   3.063 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.550           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.087           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.919           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.101           ms/op
ClientGrpc.existUser                      sample  325607   2.946 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.653           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.612           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.334           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.170           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.757           ms/op
ClientGrpc.getUser                        sample  312731   3.068 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.310           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.069           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.471           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.381           ms/op
ClientGrpc.listUser                       sample  239578   4.010 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.878           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.848           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.266           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.492           ms/op
