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
# Warmup Iteration   1: 5.211 ops/ms
# Warmup Iteration   2: 9.770 ops/ms
# Warmup Iteration   3: 10.746 ops/ms
Iteration   1: 10.706 ops/ms
Iteration   2: 10.637 ops/ms
Iteration   3: 10.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.497 ±(99.9%) 5.559 ops/ms [Average]
  (min, avg, max) = (10.147, 10.497, 10.706), stdev = 0.305
  CI (99.9%): [4.938, 16.056] (assumes normal distribution)


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
# Warmup Iteration   1: 8.224 ops/ms
# Warmup Iteration   2: 10.701 ops/ms
# Warmup Iteration   3: 11.084 ops/ms
Iteration   1: 10.903 ops/ms
Iteration   2: 10.684 ops/ms
Iteration   3: 10.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.836 ±(99.9%) 2.401 ops/ms [Average]
  (min, avg, max) = (10.684, 10.836, 10.919), stdev = 0.132
  CI (99.9%): [8.435, 13.236] (assumes normal distribution)


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
# Warmup Iteration   1: 8.316 ops/ms
# Warmup Iteration   2: 10.069 ops/ms
# Warmup Iteration   3: 10.316 ops/ms
Iteration   1: 10.469 ops/ms
Iteration   2: 10.428 ops/ms
Iteration   3: 10.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.532 ±(99.9%) 2.644 ops/ms [Average]
  (min, avg, max) = (10.428, 10.532, 10.697), stdev = 0.145
  CI (99.9%): [7.887, 13.176] (assumes normal distribution)


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
# Warmup Iteration   1: 5.742 ops/ms
# Warmup Iteration   2: 7.776 ops/ms
# Warmup Iteration   3: 8.109 ops/ms
Iteration   1: 7.862 ops/ms
Iteration   2: 7.980 ops/ms
Iteration   3: 7.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.922 ±(99.9%) 1.076 ops/ms [Average]
  (min, avg, max) = (7.862, 7.922, 7.980), stdev = 0.059
  CI (99.9%): [6.846, 8.998] (assumes normal distribution)


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
# Warmup Iteration   1: 4.183 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.002 ms/op
Iteration   1: 3.083 ±(99.9%) 0.002 ms/op
Iteration   2: 3.081 ±(99.9%) 0.002 ms/op
Iteration   3: 3.095 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.086 ±(99.9%) 0.135 ms/op [Average]
  (min, avg, max) = (3.081, 3.086, 3.095), stdev = 0.007
  CI (99.9%): [2.952, 3.221] (assumes normal distribution)


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.888 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.003 ms/op
Iteration   1: 2.930 ±(99.9%) 0.002 ms/op
Iteration   2: 2.938 ±(99.9%) 0.002 ms/op
Iteration   3: 2.877 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.915 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (2.877, 2.915, 2.938), stdev = 0.033
  CI (99.9%): [2.304, 3.526] (assumes normal distribution)


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
# Warmup Iteration   1: 3.919 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.003 ms/op
Iteration   1: 3.027 ±(99.9%) 0.002 ms/op
Iteration   2: 3.021 ±(99.9%) 0.003 ms/op
Iteration   3: 3.021 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.023 ±(99.9%) 0.064 ms/op [Average]
  (min, avg, max) = (3.021, 3.023, 3.027), stdev = 0.004
  CI (99.9%): [2.959, 3.088] (assumes normal distribution)


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
# Warmup Iteration   1: 4.746 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.015 ms/op
Iteration   1: 4.066 ±(99.9%) 0.014 ms/op
Iteration   2: 4.034 ±(99.9%) 0.015 ms/op
Iteration   3: 3.926 ±(99.9%) 0.060 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.009 ±(99.9%) 1.336 ms/op [Average]
  (min, avg, max) = (3.926, 4.009, 4.066), stdev = 0.073
  CI (99.9%): [2.672, 5.345] (assumes normal distribution)


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
# Warmup Iteration   1: 3.695 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.007 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  8.331 ms/op
                 createUser·p0.9999: 16.529 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.608 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  13.058 ms/op
                 createUser·p0.9999: 17.489 ms/op
                 createUser·p1.00:   18.743 ms/op

Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.574 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  6.529 ms/op
                 createUser·p0.9999: 19.125 ms/op
                 createUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312113
  mean =      3.077 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30869 
    [ 2.500,  5.000) = 280035 
    [ 5.000,  7.500) = 742 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =     10.072 ms/op
     p(99.9900) =     18.769 ms/op
     p(99.9990) =     21.127 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


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
# Warmup Iteration   1: 3.742 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.970 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.915 ±(99.9%) 0.006 ms/op
Iteration   1: 2.844 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.649 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  5.493 ms/op
                 existUser·p0.9999: 14.299 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 2.965 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.516 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  6.531 ms/op
                 existUser·p0.9999: 16.056 ms/op
                 existUser·p1.00:   16.318 ms/op

Iteration   3: 2.902 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  8.338 ms/op
                 existUser·p0.9999: 17.661 ms/op
                 existUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330546
  mean =      2.903 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3578 
    [ 1.250,  2.500) = 48824 
    [ 2.500,  3.750) = 264577 
    [ 3.750,  5.000) = 12922 
    [ 5.000,  6.250) = 280 
    [ 6.250,  7.500) = 108 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.092 ms/op
     p(99.9000) =      6.565 ms/op
     p(99.9900) =     16.055 ms/op
     p(99.9990) =     17.980 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 3.830 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.007 ms/op
Iteration   1: 3.109 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  10.357 ms/op
                 getUser·p0.9999: 11.750 ms/op
                 getUser·p1.00:   12.173 ms/op

Iteration   2: 2.948 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.544 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.092 ms/op
                 getUser·p0.999:  5.801 ms/op
                 getUser·p0.9999: 16.605 ms/op
                 getUser·p1.00:   17.105 ms/op

Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.503 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  7.023 ms/op
                 getUser·p0.9999: 14.239 ms/op
                 getUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317740
  mean =      3.020 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3173 
    [ 1.250,  2.500) = 25280 
    [ 2.500,  3.750) = 270967 
    [ 3.750,  5.000) = 17509 
    [ 5.000,  6.250) = 386 
    [ 6.250,  7.500) = 134 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =      7.166 ms/op
     p(99.9900) =     15.847 ms/op
     p(99.9990) =     16.995 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 5.346 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.009 ms/op
Iteration   1: 3.947 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  16.055 ms/op
                 listUser·p0.9999: 18.805 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   2: 4.001 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.271 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 4.102 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.690 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  15.123 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238965
  mean =      4.015 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4373 
    [ 2.500,  5.000) = 206828 
    [ 5.000,  7.500) = 26541 
    [ 7.500, 10.000) = 741 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     20.200 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.497 ± 5.559  ops/ms
ClientGrpc.existUser                       thrpt       3  10.836 ± 2.401  ops/ms
ClientGrpc.getUser                         thrpt       3  10.532 ± 2.644  ops/ms
ClientGrpc.listUser                        thrpt       3   7.922 ± 1.076  ops/ms
ClientGrpc.createUser                       avgt       3   3.086 ± 0.135   ms/op
ClientGrpc.existUser                        avgt       3   2.915 ± 0.611   ms/op
ClientGrpc.getUser                          avgt       3   3.023 ± 0.064   ms/op
ClientGrpc.listUser                         avgt       3   4.009 ± 1.336   ms/op
ClientGrpc.createUser                     sample  312113   3.077 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.574           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.072           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.769           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.266           ms/op
ClientGrpc.existUser                      sample  330546   2.903 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.516           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.092           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.565           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.055           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.121           ms/op
ClientGrpc.getUser                        sample  317740   3.020 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.503           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.153           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.166           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.847           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.105           ms/op
ClientGrpc.listUser                       sample  238965   4.015 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.690           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.139           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.497           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.283           ms/op
