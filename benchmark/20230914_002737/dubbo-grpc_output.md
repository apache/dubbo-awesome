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
# Warmup Iteration   1: 4.200 ops/ms
# Warmup Iteration   2: 8.637 ops/ms
# Warmup Iteration   3: 9.795 ops/ms
Iteration   1: 10.435 ops/ms
Iteration   2: 10.400 ops/ms
Iteration   3: 10.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.409 ±(99.9%) 0.418 ops/ms [Average]
  (min, avg, max) = (10.392, 10.409, 10.435), stdev = 0.023
  CI (99.9%): [9.992, 10.827] (assumes normal distribution)


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
# Warmup Iteration   1: 7.511 ops/ms
# Warmup Iteration   2: 10.528 ops/ms
# Warmup Iteration   3: 10.854 ops/ms
Iteration   1: 10.861 ops/ms
Iteration   2: 10.844 ops/ms
Iteration   3: 11.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.905 ±(99.9%) 1.644 ops/ms [Average]
  (min, avg, max) = (10.844, 10.905, 11.008), stdev = 0.090
  CI (99.9%): [9.261, 12.549] (assumes normal distribution)


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
# Warmup Iteration   1: 7.326 ops/ms
# Warmup Iteration   2: 10.172 ops/ms
# Warmup Iteration   3: 10.422 ops/ms
Iteration   1: 10.413 ops/ms
Iteration   2: 10.528 ops/ms
Iteration   3: 10.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.521 ±(99.9%) 1.913 ops/ms [Average]
  (min, avg, max) = (10.413, 10.521, 10.622), stdev = 0.105
  CI (99.9%): [8.609, 12.434] (assumes normal distribution)


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
# Warmup Iteration   1: 5.072 ops/ms
# Warmup Iteration   2: 7.792 ops/ms
# Warmup Iteration   3: 7.828 ops/ms
Iteration   1: 7.922 ops/ms
Iteration   2: 8.019 ops/ms
Iteration   3: 8.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.986 ±(99.9%) 1.014 ops/ms [Average]
  (min, avg, max) = (7.922, 7.986, 8.019), stdev = 0.056
  CI (99.9%): [6.972, 9.000] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.308 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.003 ms/op
Iteration   1: 3.128 ±(99.9%) 0.004 ms/op
Iteration   2: 3.071 ±(99.9%) 0.003 ms/op
Iteration   3: 3.073 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.091 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (3.071, 3.091, 3.128), stdev = 0.032
  CI (99.9%): [2.500, 3.681] (assumes normal distribution)


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
# Warmup Iteration   1: 3.718 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.989 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.003 ms/op
Iteration   1: 2.874 ±(99.9%) 0.003 ms/op
Iteration   2: 2.886 ±(99.9%) 0.003 ms/op
Iteration   3: 2.917 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.892 ±(99.9%) 0.403 ms/op [Average]
  (min, avg, max) = (2.874, 2.892, 2.917), stdev = 0.022
  CI (99.9%): [2.489, 3.295] (assumes normal distribution)


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.004 ms/op
Iteration   1: 3.044 ±(99.9%) 0.003 ms/op
Iteration   2: 3.044 ±(99.9%) 0.004 ms/op
Iteration   3: 3.070 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.053 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (3.044, 3.053, 3.070), stdev = 0.015
  CI (99.9%): [2.778, 3.327] (assumes normal distribution)


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
# Warmup Iteration   1: 5.548 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.052 ±(99.9%) 0.053 ms/op
Iteration   1: 4.041 ±(99.9%) 0.031 ms/op
Iteration   2: 4.059 ±(99.9%) 0.015 ms/op
Iteration   3: 3.993 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.031 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (3.993, 4.031, 4.059), stdev = 0.034
  CI (99.9%): [3.414, 4.648] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.542 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.006 ms/op
Iteration   1: 3.103 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  7.945 ms/op
                 createUser·p0.9999: 12.972 ms/op
                 createUser·p1.00:   13.468 ms/op

Iteration   2: 3.109 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.552 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.940 ms/op
                 createUser·p0.999:  8.487 ms/op
                 createUser·p0.9999: 13.901 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   3: 3.097 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  9.912 ms/op
                 createUser·p0.9999: 26.083 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309347
  mean =      3.103 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15998 
    [ 2.500,  5.000) = 290739 
    [ 5.000,  7.500) = 1931 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.825 ms/op
     p(99.9000) =      9.481 ms/op
     p(99.9900) =     24.206 ms/op
     p(99.9990) =     26.703 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 4.349 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
Iteration   1: 2.959 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  8.402 ms/op
                 existUser·p0.9999: 17.138 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   2: 2.914 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.522 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.692 ms/op
                 existUser·p0.9999: 29.721 ms/op
                 existUser·p1.00:   30.015 ms/op

Iteration   3: 2.906 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.563 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  8.904 ms/op
                 existUser·p0.9999: 21.037 ms/op
                 existUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328362
  mean =      2.926 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33171 
    [ 2.500,  5.000) = 293111 
    [ 5.000,  7.500) = 1580 
    [ 7.500, 10.000) = 269 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.274 ms/op
     p(99.9900) =     24.149 ms/op
     p(99.9990) =     29.884 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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
# Warmup Iteration   1: 4.574 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
Iteration   1: 3.064 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  8.536 ms/op
                 getUser·p0.9999: 25.625 ms/op
                 getUser·p1.00:   26.116 ms/op

Iteration   2: 3.023 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  8.350 ms/op
                 getUser·p0.9999: 24.393 ms/op
                 getUser·p1.00:   25.854 ms/op

Iteration   3: 3.034 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.625 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  8.547 ms/op
                 getUser·p0.9999: 27.687 ms/op
                 getUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315622
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23516 
    [ 2.500,  5.000) = 289587 
    [ 5.000,  7.500) = 2032 
    [ 7.500, 10.000) = 289 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     26.847 ms/op
     p(99.9990) =     29.259 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 5.662 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.231 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.011 ms/op
Iteration   1: 4.079 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.289 ms/op
                 listUser·p0.999:  13.459 ms/op
                 listUser·p0.9999: 18.912 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   2: 4.048 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.725 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  15.216 ms/op
                 listUser·p0.9999: 20.229 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 4.028 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  16.990 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237175
  mean =      4.052 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3179 
    [ 2.500,  5.000) = 205962 
    [ 5.000,  7.500) = 26037 
    [ 7.500, 10.000) = 1533 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.988 ms/op
     p(99.0000) =      7.301 ms/op
     p(99.9000) =     14.661 ms/op
     p(99.9900) =     20.138 ms/op
     p(99.9990) =     21.583 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.409 ± 0.418  ops/ms
ClientGrpc.existUser                       thrpt       3  10.905 ± 1.644  ops/ms
ClientGrpc.getUser                         thrpt       3  10.521 ± 1.913  ops/ms
ClientGrpc.listUser                        thrpt       3   7.986 ± 1.014  ops/ms
ClientGrpc.createUser                       avgt       3   3.091 ± 0.591   ms/op
ClientGrpc.existUser                        avgt       3   2.892 ± 0.403   ms/op
ClientGrpc.getUser                          avgt       3   3.053 ± 0.274   ms/op
ClientGrpc.listUser                         avgt       3   4.031 ± 0.617   ms/op
ClientGrpc.createUser                     sample  309347   3.103 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.552           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.825           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.481           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.206           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.165           ms/op
ClientGrpc.existUser                      sample  328362   2.926 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.563           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.274           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.149           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.015           ms/op
ClientGrpc.getUser                        sample  315622   3.040 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.625           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.841           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.503           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.847           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.753           ms/op
ClientGrpc.listUser                       sample  237175   4.052 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.725           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.988           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.301           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.661           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.138           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.823           ms/op
