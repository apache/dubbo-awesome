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
# Warmup Iteration   1: 4.250 ops/ms
# Warmup Iteration   2: 9.181 ops/ms
# Warmup Iteration   3: 10.079 ops/ms
Iteration   1: 10.427 ops/ms
Iteration   2: 10.713 ops/ms
Iteration   3: 10.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.646 ±(99.9%) 3.559 ops/ms [Average]
  (min, avg, max) = (10.427, 10.646, 10.799), stdev = 0.195
  CI (99.9%): [7.088, 14.205] (assumes normal distribution)


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
# Warmup Iteration   1: 7.731 ops/ms
# Warmup Iteration   2: 10.635 ops/ms
# Warmup Iteration   3: 10.796 ops/ms
Iteration   1: 10.823 ops/ms
Iteration   2: 10.960 ops/ms
Iteration   3: 11.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.054 ±(99.9%) 5.276 ops/ms [Average]
  (min, avg, max) = (10.823, 11.054, 11.378), stdev = 0.289
  CI (99.9%): [5.777, 16.330] (assumes normal distribution)


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
# Warmup Iteration   1: 7.090 ops/ms
# Warmup Iteration   2: 10.111 ops/ms
# Warmup Iteration   3: 10.297 ops/ms
Iteration   1: 10.122 ops/ms
Iteration   2: 10.207 ops/ms
Iteration   3: 10.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.284 ±(99.9%) 3.862 ops/ms [Average]
  (min, avg, max) = (10.122, 10.284, 10.524), stdev = 0.212
  CI (99.9%): [6.422, 14.146] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.480 ops/ms
# Warmup Iteration   2: 7.657 ops/ms
# Warmup Iteration   3: 7.701 ops/ms
Iteration   1: 7.887 ops/ms
Iteration   2: 7.951 ops/ms
Iteration   3: 7.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.929 ±(99.9%) 0.675 ops/ms [Average]
  (min, avg, max) = (7.887, 7.929, 7.951), stdev = 0.037
  CI (99.9%): [7.254, 8.604] (assumes normal distribution)


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.004 ms/op
Iteration   1: 2.965 ±(99.9%) 0.003 ms/op
Iteration   2: 3.056 ±(99.9%) 0.002 ms/op
Iteration   3: 2.940 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.987 ±(99.9%) 1.117 ms/op [Average]
  (min, avg, max) = (2.940, 2.987, 3.056), stdev = 0.061
  CI (99.9%): [1.870, 4.104] (assumes normal distribution)


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.812 ±(99.9%) 0.003 ms/op
Iteration   1: 2.884 ±(99.9%) 0.003 ms/op
Iteration   2: 2.869 ±(99.9%) 0.002 ms/op
Iteration   3: 2.890 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.881 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (2.869, 2.881, 2.890), stdev = 0.011
  CI (99.9%): [2.684, 3.078] (assumes normal distribution)


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 3.024 ±(99.9%) 0.003 ms/op
Iteration   2: 2.972 ±(99.9%) 0.003 ms/op
Iteration   3: 3.031 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.009 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (2.972, 3.009, 3.031), stdev = 0.033
  CI (99.9%): [2.415, 3.603] (assumes normal distribution)


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
# Warmup Iteration   1: 4.425 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.011 ms/op
Iteration   1: 3.954 ±(99.9%) 0.012 ms/op
Iteration   2: 4.031 ±(99.9%) 0.016 ms/op
Iteration   3: 3.971 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.986 ±(99.9%) 0.739 ms/op [Average]
  (min, avg, max) = (3.954, 3.986, 4.031), stdev = 0.041
  CI (99.9%): [3.246, 4.725] (assumes normal distribution)


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
# Warmup Iteration   1: 4.413 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
Iteration   1: 3.101 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  8.499 ms/op
                 createUser·p0.9999: 21.802 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   2: 3.047 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.923 ms/op
                 createUser·p0.999:  9.946 ms/op
                 createUser·p0.9999: 21.414 ms/op
                 createUser·p1.00:   23.265 ms/op

Iteration   3: 3.073 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.536 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  10.174 ms/op
                 createUser·p0.9999: 26.739 ms/op
                 createUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312292
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27355 
    [ 2.500,  5.000) = 282378 
    [ 5.000,  7.500) = 1970 
    [ 7.500, 10.000) = 307 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =      9.765 ms/op
     p(99.9900) =     22.340 ms/op
     p(99.9990) =     26.833 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 3.995 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.867 ±(99.9%) 0.007 ms/op
Iteration   1: 2.961 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.610 ms/op
                 existUser·p0.9999: 13.356 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   2: 2.890 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  10.869 ms/op
                 existUser·p0.9999: 14.138 ms/op
                 existUser·p1.00:   15.352 ms/op

Iteration   3: 2.874 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  9.157 ms/op
                 existUser·p0.9999: 17.855 ms/op
                 existUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329707
  mean =      2.908 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1015 
    [ 1.250,  2.500) = 34695 
    [ 2.500,  3.750) = 283555 
    [ 3.750,  5.000) = 8774 
    [ 5.000,  6.250) = 681 
    [ 6.250,  7.500) = 547 
    [ 7.500,  8.750) = 150 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      8.017 ms/op
     p(99.9900) =     16.368 ms/op
     p(99.9990) =     18.200 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
Iteration   1: 3.033 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  8.267 ms/op
                 getUser·p0.9999: 13.508 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.657 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.061 ms/op
                 getUser·p0.9999: 13.721 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  8.421 ms/op
                 getUser·p0.9999: 18.581 ms/op
                 getUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315454
  mean =      3.044 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 884 
    [ 1.250,  2.500) = 16899 
    [ 2.500,  3.750) = 279886 
    [ 3.750,  5.000) = 16182 
    [ 5.000,  6.250) = 762 
    [ 6.250,  7.500) = 323 
    [ 7.500,  8.750) = 243 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      8.266 ms/op
     p(99.9900) =     16.630 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 5.045 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.205 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.011 ms/op
Iteration   1: 4.006 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.417 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  14.173 ms/op
                 listUser·p0.9999: 21.299 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   2: 3.982 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.915 ms/op
                 listUser·p0.999:  17.582 ms/op
                 listUser·p0.9999: 27.492 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   3: 4.008 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.042 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.794 ms/op
                 listUser·p0.9999: 24.543 ms/op
                 listUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240471
  mean =      3.999 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3131 
    [ 2.500,  5.000) = 214107 
    [ 5.000,  7.500) = 21711 
    [ 7.500, 10.000) = 993 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      0.417 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     15.974 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     27.610 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.646 ± 3.559  ops/ms
ClientGrpc.existUser                       thrpt       3  11.054 ± 5.276  ops/ms
ClientGrpc.getUser                         thrpt       3  10.284 ± 3.862  ops/ms
ClientGrpc.listUser                        thrpt       3   7.929 ± 0.675  ops/ms
ClientGrpc.createUser                       avgt       3   2.987 ± 1.117   ms/op
ClientGrpc.existUser                        avgt       3   2.881 ± 0.197   ms/op
ClientGrpc.getUser                          avgt       3   3.009 ± 0.594   ms/op
ClientGrpc.listUser                         avgt       3   3.986 ± 0.739   ms/op
ClientGrpc.createUser                     sample  312292   3.073 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.536           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.866           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.765           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.340           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.968           ms/op
ClientGrpc.existUser                      sample  329707   2.908 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.700           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.017           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.368           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.317           ms/op
ClientGrpc.getUser                        sample  315454   3.044 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.657           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.266           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.630           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.202           ms/op
ClientGrpc.listUser                       sample  240471   3.999 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.417           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.974           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.903           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.656           ms/op
