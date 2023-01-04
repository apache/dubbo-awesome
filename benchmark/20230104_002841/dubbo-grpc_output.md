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
# Warmup Iteration   1: 5.011 ops/ms
# Warmup Iteration   2: 9.595 ops/ms
# Warmup Iteration   3: 10.484 ops/ms
Iteration   1: 10.470 ops/ms
Iteration   2: 10.027 ops/ms
Iteration   3: 10.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.308 ±(99.9%) 4.461 ops/ms [Average]
  (min, avg, max) = (10.027, 10.308, 10.470), stdev = 0.245
  CI (99.9%): [5.847, 14.769] (assumes normal distribution)


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
# Warmup Iteration   1: 8.627 ops/ms
# Warmup Iteration   2: 10.453 ops/ms
# Warmup Iteration   3: 10.815 ops/ms
Iteration   1: 10.678 ops/ms
Iteration   2: 10.856 ops/ms
Iteration   3: 10.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.829 ±(99.9%) 2.554 ops/ms [Average]
  (min, avg, max) = (10.678, 10.829, 10.954), stdev = 0.140
  CI (99.9%): [8.275, 13.382] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.406 ops/ms
# Warmup Iteration   2: 10.185 ops/ms
# Warmup Iteration   3: 10.212 ops/ms
Iteration   1: 10.200 ops/ms
Iteration   2: 10.366 ops/ms
Iteration   3: 10.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.349 ±(99.9%) 2.593 ops/ms [Average]
  (min, avg, max) = (10.200, 10.349, 10.482), stdev = 0.142
  CI (99.9%): [7.757, 12.942] (assumes normal distribution)


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
# Warmup Iteration   1: 6.203 ops/ms
# Warmup Iteration   2: 7.760 ops/ms
# Warmup Iteration   3: 8.012 ops/ms
Iteration   1: 7.807 ops/ms
Iteration   2: 7.975 ops/ms
Iteration   3: 8.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.927 ±(99.9%) 1.915 ops/ms [Average]
  (min, avg, max) = (7.807, 7.927, 8.000), stdev = 0.105
  CI (99.9%): [6.012, 9.842] (assumes normal distribution)


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
# Warmup Iteration   1: 3.806 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.003 ms/op
Iteration   1: 3.169 ±(99.9%) 0.002 ms/op
Iteration   2: 3.197 ±(99.9%) 0.002 ms/op
Iteration   3: 3.161 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.175 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (3.161, 3.175, 3.197), stdev = 0.019
  CI (99.9%): [2.827, 3.524] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.801 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.830 ±(99.9%) 0.004 ms/op
Iteration   1: 2.994 ±(99.9%) 0.003 ms/op
Iteration   2: 2.903 ±(99.9%) 0.003 ms/op
Iteration   3: 3.007 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.968 ±(99.9%) 1.029 ms/op [Average]
  (min, avg, max) = (2.903, 2.968, 3.007), stdev = 0.056
  CI (99.9%): [1.939, 3.997] (assumes normal distribution)


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.003 ms/op
Iteration   1: 3.108 ±(99.9%) 0.002 ms/op
Iteration   2: 3.049 ±(99.9%) 0.004 ms/op
Iteration   3: 3.096 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.084 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (3.049, 3.084, 3.108), stdev = 0.031
  CI (99.9%): [2.516, 3.653] (assumes normal distribution)


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
# Warmup Iteration   1: 4.090 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.278 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.023 ms/op
Iteration   1: 4.116 ±(99.9%) 0.023 ms/op
Iteration   2: 4.196 ±(99.9%) 0.012 ms/op
Iteration   3: 3.964 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.092 ±(99.9%) 2.150 ms/op [Average]
  (min, avg, max) = (3.964, 4.092, 4.196), stdev = 0.118
  CI (99.9%): [1.942, 6.242] (assumes normal distribution)


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
# Warmup Iteration   1: 4.073 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
Iteration   1: 2.992 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.507 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  6.391 ms/op
                 createUser·p0.9999: 16.766 ms/op
                 createUser·p1.00:   17.072 ms/op

Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  6.813 ms/op
                 createUser·p0.9999: 16.625 ms/op
                 createUser·p1.00:   18.055 ms/op

Iteration   3: 3.095 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.520 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.399 ms/op
                 createUser·p0.9999: 15.663 ms/op
                 createUser·p1.00:   15.909 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314525
  mean =      3.050 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1217 
    [ 1.250,  2.500) = 25658 
    [ 2.500,  3.750) = 263749 
    [ 3.750,  5.000) = 23025 
    [ 5.000,  6.250) = 473 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 78 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 56 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.744 ms/op
     p(99.9900) =     16.557 ms/op
     p(99.9990) =     17.428 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 3.773 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.928 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.918 ±(99.9%) 0.006 ms/op
Iteration   1: 3.009 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.272 ms/op
                 existUser·p0.999:  9.175 ms/op
                 existUser·p0.9999: 11.487 ms/op
                 existUser·p1.00:   11.928 ms/op

Iteration   2: 2.847 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.313 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  6.717 ms/op
                 existUser·p0.9999: 19.227 ms/op
                 existUser·p1.00:   19.497 ms/op

Iteration   3: 2.843 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  6.173 ms/op
                 existUser·p0.9999: 20.013 ms/op
                 existUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331153
  mean =      2.898 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51291 
    [ 2.500,  5.000) = 278867 
    [ 5.000,  7.500) = 699 
    [ 7.500, 10.000) = 113 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.313 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.291 ms/op
     p(99.9900) =     19.300 ms/op
     p(99.9990) =     20.253 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 3.945 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.007 ms/op
Iteration   1: 3.110 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  8.181 ms/op
                 getUser·p0.9999: 18.430 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   2: 3.122 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.221 ms/op
                 getUser·p0.9999: 13.062 ms/op
                 getUser·p1.00:   15.679 ms/op

Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.178 ms/op
                 getUser·p0.9999: 18.106 ms/op
                 getUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309984
  mean =      3.097 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1421 
    [ 1.250,  2.500) = 18723 
    [ 2.500,  3.750) = 265437 
    [ 3.750,  5.000) = 23424 
    [ 5.000,  6.250) = 496 
    [ 6.250,  7.500) = 156 
    [ 7.500,  8.750) = 138 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.660 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     18.740 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 5.069 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.012 ms/op
Iteration   1: 3.987 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.848 ms/op
                 listUser·p0.999:  11.777 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   2: 4.001 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.019 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.610 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.582 ms/op
                 listUser·p0.9999: 20.709 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   3: 4.023 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.462 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.968 ms/op
                 listUser·p0.999:  16.164 ms/op
                 listUser·p0.9999: 21.469 ms/op
                 listUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239613
  mean =      4.004 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3880 
    [ 2.500,  5.000) = 210531 
    [ 5.000,  7.500) = 24038 
    [ 7.500, 10.000) = 705 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     13.654 ms/op
     p(99.9900) =     20.711 ms/op
     p(99.9990) =     23.129 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.308 ± 4.461  ops/ms
ClientGrpc.existUser                       thrpt       3  10.829 ± 2.554  ops/ms
ClientGrpc.getUser                         thrpt       3  10.349 ± 2.593  ops/ms
ClientGrpc.listUser                        thrpt       3   7.927 ± 1.915  ops/ms
ClientGrpc.createUser                       avgt       3   3.175 ± 0.349   ms/op
ClientGrpc.existUser                        avgt       3   2.968 ± 1.029   ms/op
ClientGrpc.getUser                          avgt       3   3.084 ± 0.568   ms/op
ClientGrpc.listUser                         avgt       3   4.092 ± 2.150   ms/op
ClientGrpc.createUser                     sample  314525   3.050 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.507           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.744           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.557           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.055           ms/op
ClientGrpc.existUser                      sample  331153   2.898 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.313           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.445           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.291           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.300           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.414           ms/op
ClientGrpc.getUser                        sample  309984   3.097 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.699           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.903           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.660           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.990           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.842           ms/op
ClientGrpc.listUser                       sample  239613   4.004 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.462           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.654           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.711           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.953           ms/op
