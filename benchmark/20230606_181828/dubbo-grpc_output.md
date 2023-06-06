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
# Warmup Iteration   1: 4.795 ops/ms
# Warmup Iteration   2: 9.221 ops/ms
# Warmup Iteration   3: 10.244 ops/ms
Iteration   1: 10.814 ops/ms
Iteration   2: 10.806 ops/ms
Iteration   3: 10.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.766 ±(99.9%) 1.378 ops/ms [Average]
  (min, avg, max) = (10.679, 10.766, 10.814), stdev = 0.076
  CI (99.9%): [9.389, 12.144] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.900 ops/ms
# Warmup Iteration   2: 10.607 ops/ms
# Warmup Iteration   3: 11.069 ops/ms
Iteration   1: 11.230 ops/ms
Iteration   2: 11.141 ops/ms
Iteration   3: 11.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.233 ±(99.9%) 1.689 ops/ms [Average]
  (min, avg, max) = (11.141, 11.233, 11.326), stdev = 0.093
  CI (99.9%): [9.544, 12.921] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.625 ops/ms
# Warmup Iteration   2: 10.411 ops/ms
# Warmup Iteration   3: 10.420 ops/ms
Iteration   1: 10.706 ops/ms
Iteration   2: 10.590 ops/ms
Iteration   3: 10.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.617 ±(99.9%) 1.449 ops/ms [Average]
  (min, avg, max) = (10.554, 10.617, 10.706), stdev = 0.079
  CI (99.9%): [9.167, 12.066] (assumes normal distribution)


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
# Warmup Iteration   1: 7.127 ops/ms
# Warmup Iteration   2: 8.162 ops/ms
# Warmup Iteration   3: 8.321 ops/ms
Iteration   1: 8.515 ops/ms
Iteration   2: 8.331 ops/ms
Iteration   3: 8.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.429 ±(99.9%) 1.690 ops/ms [Average]
  (min, avg, max) = (8.331, 8.429, 8.515), stdev = 0.093
  CI (99.9%): [6.739, 10.119] (assumes normal distribution)


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.002 ms/op
Iteration   1: 2.958 ±(99.9%) 0.002 ms/op
Iteration   2: 2.969 ±(99.9%) 0.002 ms/op
Iteration   3: 2.932 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.953 ±(99.9%) 0.350 ms/op [Average]
  (min, avg, max) = (2.932, 2.953, 2.969), stdev = 0.019
  CI (99.9%): [2.603, 3.302] (assumes normal distribution)


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
# Warmup Iteration   1: 3.837 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.893 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.849 ±(99.9%) 0.004 ms/op
Iteration   1: 2.866 ±(99.9%) 0.003 ms/op
Iteration   2: 2.851 ±(99.9%) 0.003 ms/op
Iteration   3: 2.843 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.853 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (2.843, 2.853, 2.866), stdev = 0.012
  CI (99.9%): [2.637, 3.070] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.921 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.003 ms/op
Iteration   1: 2.961 ±(99.9%) 0.008 ms/op
Iteration   2: 2.955 ±(99.9%) 0.003 ms/op
Iteration   3: 2.958 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.958 ±(99.9%) 0.049 ms/op [Average]
  (min, avg, max) = (2.955, 2.958, 2.961), stdev = 0.003
  CI (99.9%): [2.909, 3.006] (assumes normal distribution)


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
# Warmup Iteration   1: 5.109 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.905 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.749 ±(99.9%) 0.009 ms/op
Iteration   1: 3.821 ±(99.9%) 0.013 ms/op
Iteration   2: 3.714 ±(99.9%) 0.004 ms/op
Iteration   3: 3.857 ±(99.9%) 0.044 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.797 ±(99.9%) 1.353 ms/op [Average]
  (min, avg, max) = (3.714, 3.797, 3.857), stdev = 0.074
  CI (99.9%): [2.444, 5.150] (assumes normal distribution)


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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
Iteration   1: 2.937 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   2.908 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  6.292 ms/op
                 createUser·p0.9999: 16.457 ms/op
                 createUser·p1.00:   16.810 ms/op

Iteration   2: 2.961 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  8.103 ms/op
                 createUser·p0.9999: 13.176 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   3: 2.945 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.515 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.422 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325646
  mean =      2.948 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33094 
    [ 2.500,  5.000) = 291217 
    [ 5.000,  7.500) = 1019 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.430 ms/op
     p(99.9900) =     25.704 ms/op
     p(99.9990) =     26.361 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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
# Warmup Iteration   1: 3.814 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.981 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.006 ms/op
Iteration   1: 2.847 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  6.443 ms/op
                 existUser·p0.9999: 15.192 ms/op
                 existUser·p1.00:   15.565 ms/op

Iteration   2: 2.886 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  6.169 ms/op
                 existUser·p0.9999: 15.701 ms/op
                 existUser·p1.00:   16.400 ms/op

Iteration   3: 2.779 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.802 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  6.668 ms/op
                 existUser·p0.9999: 17.596 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 338371
  mean =      2.836 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4065 
    [ 1.250,  2.500) = 51761 
    [ 2.500,  3.750) = 270713 
    [ 3.750,  5.000) = 10799 
    [ 5.000,  6.250) = 663 
    [ 6.250,  7.500) = 195 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      6.367 ms/op
     p(99.9900) =     15.846 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
Iteration   1: 2.947 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.373 ms/op
                 getUser·p0.9999: 25.432 ms/op
                 getUser·p1.00:   25.756 ms/op

Iteration   2: 2.958 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.374 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.283 ms/op
                 getUser·p0.9999: 28.219 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 2.878 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.535 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.019 ms/op
                 getUser·p0.9999: 18.707 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 328048
  mean =      2.927 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37734 
    [ 2.500,  5.000) = 289016 
    [ 5.000,  7.500) = 1027 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      0.374 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.077 ms/op
     p(99.9900) =     27.255 ms/op
     p(99.9990) =     28.499 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 5.385 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.010 ms/op
Iteration   1: 3.810 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  11.338 ms/op
                 listUser·p0.9999: 15.896 ms/op
                 listUser·p1.00:   16.400 ms/op

Iteration   2: 3.849 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.695 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  13.417 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   3: 3.787 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  16.767 ms/op
                 listUser·p0.9999: 20.959 ms/op
                 listUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251794
  mean =      3.815 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4630 
    [ 2.500,  5.000) = 227790 
    [ 5.000,  7.500) = 18294 
    [ 7.500, 10.000) = 586 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     13.815 ms/op
     p(99.9900) =     20.069 ms/op
     p(99.9990) =     21.315 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.766 ± 1.378  ops/ms
ClientGrpc.existUser                       thrpt       3  11.233 ± 1.689  ops/ms
ClientGrpc.getUser                         thrpt       3  10.617 ± 1.449  ops/ms
ClientGrpc.listUser                        thrpt       3   8.429 ± 1.690  ops/ms
ClientGrpc.createUser                       avgt       3   2.953 ± 0.350   ms/op
ClientGrpc.existUser                        avgt       3   2.853 ± 0.216   ms/op
ClientGrpc.getUser                          avgt       3   2.958 ± 0.049   ms/op
ClientGrpc.listUser                         avgt       3   3.797 ± 1.353   ms/op
ClientGrpc.createUser                     sample  325646   2.948 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.515           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.937           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.420           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.430           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.704           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.411           ms/op
ClientGrpc.existUser                      sample  338371   2.836 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.621           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.839           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.367           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.846           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.990           ms/op
ClientGrpc.getUser                        sample  328048   2.927 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.374           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.941           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.412           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.077           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.255           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.574           ms/op
ClientGrpc.listUser                       sample  251794   3.815 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.695           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.674           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.815           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.069           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.430           ms/op
