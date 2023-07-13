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
# Warmup Iteration   1: 5.156 ops/ms
# Warmup Iteration   2: 9.597 ops/ms
# Warmup Iteration   3: 10.300 ops/ms
Iteration   1: 10.545 ops/ms
Iteration   2: 10.658 ops/ms
Iteration   3: 10.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.582 ±(99.9%) 1.194 ops/ms [Average]
  (min, avg, max) = (10.544, 10.582, 10.658), stdev = 0.065
  CI (99.9%): [9.388, 11.777] (assumes normal distribution)


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
# Warmup Iteration   1: 7.846 ops/ms
# Warmup Iteration   2: 10.859 ops/ms
# Warmup Iteration   3: 11.027 ops/ms
Iteration   1: 11.199 ops/ms
Iteration   2: 11.155 ops/ms
Iteration   3: 11.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.156 ±(99.9%) 0.787 ops/ms [Average]
  (min, avg, max) = (11.113, 11.156, 11.199), stdev = 0.043
  CI (99.9%): [10.369, 11.942] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.569 ops/ms
# Warmup Iteration   2: 10.399 ops/ms
# Warmup Iteration   3: 10.627 ops/ms
Iteration   1: 10.500 ops/ms
Iteration   2: 10.827 ops/ms
Iteration   3: 10.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.675 ±(99.9%) 3.010 ops/ms [Average]
  (min, avg, max) = (10.500, 10.675, 10.827), stdev = 0.165
  CI (99.9%): [7.665, 13.686] (assumes normal distribution)


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
# Warmup Iteration   1: 7.024 ops/ms
# Warmup Iteration   2: 7.986 ops/ms
# Warmup Iteration   3: 8.140 ops/ms
Iteration   1: 8.193 ops/ms
Iteration   2: 8.157 ops/ms
Iteration   3: 8.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.217 ±(99.9%) 1.360 ops/ms [Average]
  (min, avg, max) = (8.157, 8.217, 8.301), stdev = 0.075
  CI (99.9%): [6.858, 9.577] (assumes normal distribution)


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
# Warmup Iteration   1: 3.866 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.002 ms/op
Iteration   1: 2.971 ±(99.9%) 0.003 ms/op
Iteration   2: 2.998 ±(99.9%) 0.003 ms/op
Iteration   3: 3.011 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.993 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (2.971, 2.993, 3.011), stdev = 0.021
  CI (99.9%): [2.617, 3.369] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.845 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.910 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.868 ±(99.9%) 0.003 ms/op
Iteration   1: 2.840 ±(99.9%) 0.003 ms/op
Iteration   2: 2.900 ±(99.9%) 0.003 ms/op
Iteration   3: 2.861 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.867 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (2.840, 2.867, 2.900), stdev = 0.030
  CI (99.9%): [2.313, 3.422] (assumes normal distribution)


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
# Warmup Iteration   1: 4.378 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.003 ms/op
Iteration   1: 2.986 ±(99.9%) 0.002 ms/op
Iteration   2: 3.056 ±(99.9%) 0.004 ms/op
Iteration   3: 3.003 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.015 ±(99.9%) 0.670 ms/op [Average]
  (min, avg, max) = (2.986, 3.015, 3.056), stdev = 0.037
  CI (99.9%): [2.345, 3.685] (assumes normal distribution)


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
# Warmup Iteration   1: 4.359 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.254 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.024 ms/op
Iteration   1: 3.975 ±(99.9%) 0.005 ms/op
Iteration   2: 3.954 ±(99.9%) 0.024 ms/op
Iteration   3: 3.896 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.942 ±(99.9%) 0.745 ms/op [Average]
  (min, avg, max) = (3.896, 3.942, 3.975), stdev = 0.041
  CI (99.9%): [3.197, 4.687] (assumes normal distribution)


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
Iteration   1: 3.001 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  7.460 ms/op
                 createUser·p0.9999: 16.920 ms/op
                 createUser·p1.00:   17.826 ms/op

Iteration   2: 2.991 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.053 ms/op
                 createUser·p0.9999: 14.624 ms/op
                 createUser·p1.00:   14.811 ms/op

Iteration   3: 2.976 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.244 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.856 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  9.011 ms/op
                 createUser·p0.9999: 17.775 ms/op
                 createUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321244
  mean =      2.989 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1820 
    [ 1.250,  2.500) = 28215 
    [ 2.500,  3.750) = 274428 
    [ 3.750,  5.000) = 15211 
    [ 5.000,  6.250) = 812 
    [ 6.250,  7.500) = 414 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.244 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.799 ms/op
     p(99.9900) =     16.900 ms/op
     p(99.9990) =     18.179 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.950 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.006 ms/op
Iteration   1: 2.808 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  6.440 ms/op
                 existUser·p0.9999: 11.495 ms/op
                 existUser·p1.00:   12.730 ms/op

Iteration   2: 2.862 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.314 ms/op
                 existUser·p0.9999: 15.365 ms/op
                 existUser·p1.00:   15.827 ms/op

Iteration   3: 2.857 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.608 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  6.020 ms/op
                 existUser·p0.9999: 17.976 ms/op
                 existUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337810
  mean =      2.842 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5776 
    [ 1.250,  2.500) = 41812 
    [ 2.500,  3.750) = 280970 
    [ 3.750,  5.000) = 8287 
    [ 5.000,  6.250) = 630 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.242 ms/op
     p(99.9900) =     15.699 ms/op
     p(99.9990) =     18.174 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.005 ms/op
Iteration   1: 2.977 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.779 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.547 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  7.038 ms/op
                 getUser·p0.9999: 13.419 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  9.442 ms/op
                 getUser·p0.9999: 16.777 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.618 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  11.026 ms/op
                 getUser·p0.9999: 24.490 ms/op
                 getUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316889
  mean =      3.028 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20348 
    [ 2.500,  5.000) = 295251 
    [ 5.000,  7.500) = 823 
    [ 7.500, 10.000) = 208 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     24.865 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 4.738 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.011 ms/op
Iteration   1: 3.946 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  12.976 ms/op
                 listUser·p0.9999: 15.319 ms/op
                 listUser·p1.00:   15.598 ms/op

Iteration   2: 3.983 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  21.692 ms/op
                 listUser·p0.9999: 23.921 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   3: 3.990 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  14.643 ms/op
                 listUser·p0.9999: 15.663 ms/op
                 listUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241762
  mean =      3.973 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4467 
    [ 2.500,  5.000) = 214030 
    [ 5.000,  7.500) = 21967 
    [ 7.500, 10.000) = 807 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     14.192 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     24.267 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.582 ± 1.194  ops/ms
ClientGrpc.existUser                       thrpt       3  11.156 ± 0.787  ops/ms
ClientGrpc.getUser                         thrpt       3  10.675 ± 3.010  ops/ms
ClientGrpc.listUser                        thrpt       3   8.217 ± 1.360  ops/ms
ClientGrpc.createUser                       avgt       3   2.993 ± 0.376   ms/op
ClientGrpc.existUser                        avgt       3   2.867 ± 0.554   ms/op
ClientGrpc.getUser                          avgt       3   3.015 ± 0.670   ms/op
ClientGrpc.listUser                         avgt       3   3.942 ± 0.745   ms/op
ClientGrpc.createUser                     sample  321244   2.989 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.244           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.799           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.900           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.579           ms/op
ClientGrpc.existUser                      sample  337810   2.842 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.534           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.289           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.242           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.699           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.219           ms/op
ClientGrpc.getUser                        sample  316889   3.028 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.618           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.946           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.381           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.002           ms/op
ClientGrpc.listUser                       sample  241762   3.973 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.114           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.192           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.200           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.347           ms/op
