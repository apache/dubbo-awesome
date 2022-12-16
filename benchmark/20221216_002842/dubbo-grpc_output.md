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
# Warmup Iteration   1: 4.570 ops/ms
# Warmup Iteration   2: 9.389 ops/ms
# Warmup Iteration   3: 10.400 ops/ms
Iteration   1: 10.602 ops/ms
Iteration   2: 10.559 ops/ms
Iteration   3: 10.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.616 ±(99.9%) 1.175 ops/ms [Average]
  (min, avg, max) = (10.559, 10.616, 10.686), stdev = 0.064
  CI (99.9%): [9.440, 11.791] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.418 ops/ms
# Warmup Iteration   2: 10.396 ops/ms
# Warmup Iteration   3: 10.589 ops/ms
Iteration   1: 10.871 ops/ms
Iteration   2: 10.820 ops/ms
Iteration   3: 10.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.811 ±(99.9%) 1.169 ops/ms [Average]
  (min, avg, max) = (10.744, 10.811, 10.871), stdev = 0.064
  CI (99.9%): [9.643, 11.980] (assumes normal distribution)


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
# Warmup Iteration   1: 7.468 ops/ms
# Warmup Iteration   2: 10.517 ops/ms
# Warmup Iteration   3: 10.656 ops/ms
Iteration   1: 10.323 ops/ms
Iteration   2: 10.443 ops/ms
Iteration   3: 10.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.389 ±(99.9%) 1.114 ops/ms [Average]
  (min, avg, max) = (10.323, 10.389, 10.443), stdev = 0.061
  CI (99.9%): [9.275, 11.503] (assumes normal distribution)


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
# Warmup Iteration   1: 5.895 ops/ms
# Warmup Iteration   2: 7.976 ops/ms
# Warmup Iteration   3: 8.069 ops/ms
Iteration   1: 8.089 ops/ms
Iteration   2: 7.714 ops/ms
Iteration   3: 8.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.964 ±(99.9%) 3.951 ops/ms [Average]
  (min, avg, max) = (7.714, 7.964, 8.089), stdev = 0.217
  CI (99.9%): [4.012, 11.915] (assumes normal distribution)


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
# Warmup Iteration   1: 4.003 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.001 ms/op
Iteration   1: 2.958 ±(99.9%) 0.002 ms/op
Iteration   2: 3.021 ±(99.9%) 0.002 ms/op
Iteration   3: 3.146 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.042 ±(99.9%) 1.747 ms/op [Average]
  (min, avg, max) = (2.958, 3.042, 3.146), stdev = 0.096
  CI (99.9%): [1.295, 4.789] (assumes normal distribution)


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
# Warmup Iteration   1: 3.781 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.938 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.002 ms/op
Iteration   1: 2.939 ±(99.9%) 0.002 ms/op
Iteration   2: 2.918 ±(99.9%) 0.003 ms/op
Iteration   3: 2.861 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.906 ±(99.9%) 0.735 ms/op [Average]
  (min, avg, max) = (2.861, 2.906, 2.939), stdev = 0.040
  CI (99.9%): [2.171, 3.641] (assumes normal distribution)


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
# Warmup Iteration   1: 3.972 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.918 ±(99.9%) 0.003 ms/op
Iteration   1: 3.070 ±(99.9%) 0.003 ms/op
Iteration   2: 3.051 ±(99.9%) 0.002 ms/op
Iteration   3: 3.021 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.047 ±(99.9%) 0.451 ms/op [Average]
  (min, avg, max) = (3.021, 3.047, 3.070), stdev = 0.025
  CI (99.9%): [2.597, 3.498] (assumes normal distribution)


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.021 ms/op
Iteration   1: 3.890 ±(99.9%) 0.007 ms/op
Iteration   2: 3.834 ±(99.9%) 0.009 ms/op
Iteration   3: 3.811 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.845 ±(99.9%) 0.735 ms/op [Average]
  (min, avg, max) = (3.811, 3.845, 3.890), stdev = 0.040
  CI (99.9%): [3.110, 4.580] (assumes normal distribution)


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
# Warmup Iteration   1: 3.858 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
Iteration   1: 3.036 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.268 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  6.494 ms/op
                 createUser·p0.9999: 17.710 ms/op
                 createUser·p1.00:   18.153 ms/op

Iteration   2: 3.030 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  9.568 ms/op
                 createUser·p0.9999: 17.218 ms/op
                 createUser·p1.00:   18.514 ms/op

Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.369 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.174 ms/op
                 createUser·p0.999:  7.823 ms/op
                 createUser·p0.9999: 18.198 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317101
  mean =      3.026 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2192 
    [ 1.250,  2.500) = 32197 
    [ 2.500,  3.750) = 262828 
    [ 3.750,  5.000) = 18897 
    [ 5.000,  6.250) = 412 
    [ 6.250,  7.500) = 191 
    [ 7.500,  8.750) = 103 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.268 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      8.017 ms/op
     p(99.9900) =     17.868 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.007 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.353 ms/op
                 existUser·p0.9999: 15.254 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   2: 2.965 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.610 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  6.218 ms/op
                 existUser·p0.9999: 13.943 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   3: 2.926 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.917 ms/op
                 existUser·p0.9999: 18.194 ms/op
                 existUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324526
  mean =      2.959 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2656 
    [ 1.250,  2.500) = 43524 
    [ 2.500,  3.750) = 261181 
    [ 3.750,  5.000) = 16146 
    [ 5.000,  6.250) = 570 
    [ 6.250,  7.500) = 167 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      2.951 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.225 ms/op
     p(99.9900) =     17.376 ms/op
     p(99.9990) =     19.579 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 3.697 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.642 ms/op
                 getUser·p0.9999: 11.673 ms/op
                 getUser·p1.00:   11.895 ms/op

Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.688 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.502 ms/op
                 getUser·p0.9999: 22.883 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   3: 3.121 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  6.227 ms/op
                 getUser·p0.9999: 25.084 ms/op
                 getUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314478
  mean =      3.050 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27094 
    [ 2.500,  5.000) = 286507 
    [ 5.000,  7.500) = 664 
    [ 7.500, 10.000) = 53 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.414 ms/op
     p(99.9900) =     24.171 ms/op
     p(99.9990) =     25.325 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 5.044 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.011 ms/op
Iteration   1: 3.998 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.823 ms/op
                 listUser·p0.999:  11.551 ms/op
                 listUser·p0.9999: 14.237 ms/op
                 listUser·p1.00:   15.254 ms/op

Iteration   2: 3.869 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  13.245 ms/op
                 listUser·p0.9999: 15.851 ms/op
                 listUser·p1.00:   16.302 ms/op

Iteration   3: 3.985 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.730 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  15.126 ms/op
                 listUser·p0.9999: 21.167 ms/op
                 listUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243011
  mean =      3.950 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4011 
    [ 2.500,  5.000) = 212611 
    [ 5.000,  7.500) = 25315 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     13.205 ms/op
     p(99.9900) =     19.454 ms/op
     p(99.9990) =     22.086 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.616 ± 1.175  ops/ms
ClientGrpc.existUser                       thrpt       3  10.811 ± 1.169  ops/ms
ClientGrpc.getUser                         thrpt       3  10.389 ± 1.114  ops/ms
ClientGrpc.listUser                        thrpt       3   7.964 ± 3.951  ops/ms
ClientGrpc.createUser                       avgt       3   3.042 ± 1.747   ms/op
ClientGrpc.existUser                        avgt       3   2.906 ± 0.735   ms/op
ClientGrpc.getUser                          avgt       3   3.047 ± 0.451   ms/op
ClientGrpc.listUser                         avgt       3   3.845 ± 0.735   ms/op
ClientGrpc.createUser                     sample  317101   3.026 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.268           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.017           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.868           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.547           ms/op
ClientGrpc.existUser                      sample  324526   2.959 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.610           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.951           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.764           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.225           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.376           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.726           ms/op
ClientGrpc.getUser                        sample  314478   3.050 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.628           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.414           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.171           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.395           ms/op
ClientGrpc.listUser                       sample  243011   3.950 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.730           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.205           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.454           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.118           ms/op
