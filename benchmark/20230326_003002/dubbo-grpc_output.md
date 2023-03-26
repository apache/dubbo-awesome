# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.418 ops/ms
# Warmup Iteration   2: 9.340 ops/ms
# Warmup Iteration   3: 10.273 ops/ms
Iteration   1: 10.615 ops/ms
Iteration   2: 10.567 ops/ms
Iteration   3: 10.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.649 ±(99.9%) 1.874 ops/ms [Average]
  (min, avg, max) = (10.567, 10.649, 10.764), stdev = 0.103
  CI (99.9%): [8.775, 12.522] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.006 ops/ms
# Warmup Iteration   2: 10.692 ops/ms
# Warmup Iteration   3: 11.077 ops/ms
Iteration   1: 11.340 ops/ms
Iteration   2: 11.223 ops/ms
Iteration   3: 11.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.202 ±(99.9%) 2.719 ops/ms [Average]
  (min, avg, max) = (11.044, 11.202, 11.340), stdev = 0.149
  CI (99.9%): [8.483, 13.921] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.648 ops/ms
# Warmup Iteration   2: 10.376 ops/ms
# Warmup Iteration   3: 10.616 ops/ms
Iteration   1: 10.530 ops/ms
Iteration   2: 10.753 ops/ms
Iteration   3: 10.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.628 ±(99.9%) 2.080 ops/ms [Average]
  (min, avg, max) = (10.530, 10.628, 10.753), stdev = 0.114
  CI (99.9%): [8.548, 12.709] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.850 ops/ms
# Warmup Iteration   2: 8.005 ops/ms
# Warmup Iteration   3: 8.412 ops/ms
Iteration   1: 8.120 ops/ms
Iteration   2: 8.116 ops/ms
Iteration   3: 8.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.209 ±(99.9%) 2.874 ops/ms [Average]
  (min, avg, max) = (8.116, 8.209, 8.391), stdev = 0.158
  CI (99.9%): [5.335, 11.083] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.710 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.002 ms/op
Iteration   1: 2.990 ±(99.9%) 0.002 ms/op
Iteration   2: 2.991 ±(99.9%) 0.002 ms/op
Iteration   3: 2.983 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.988 ±(99.9%) 0.077 ms/op [Average]
  (min, avg, max) = (2.983, 2.988, 2.991), stdev = 0.004
  CI (99.9%): [2.911, 3.065] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.784 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 2.888 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 2.866 ±(99.9%) 0.004 ms/op
Iteration   1: 2.824 ±(99.9%) 0.003 ms/op
Iteration   2: 2.899 ±(99.9%) 0.005 ms/op
Iteration   3: 2.868 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.864 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (2.824, 2.864, 2.899), stdev = 0.038
  CI (99.9%): [2.173, 3.554] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.074 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.003 ms/op
Iteration   1: 2.961 ±(99.9%) 0.003 ms/op
Iteration   2: 2.971 ±(99.9%) 0.002 ms/op
Iteration   3: 2.927 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.953 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (2.927, 2.953, 2.971), stdev = 0.023
  CI (99.9%): [2.539, 3.368] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.790 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.861 ±(99.9%) 0.016 ms/op
Iteration   1: 3.819 ±(99.9%) 0.047 ms/op
Iteration   2: 3.850 ±(99.9%) 0.014 ms/op
Iteration   3: 3.856 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.842 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (3.819, 3.842, 3.856), stdev = 0.020
  CI (99.9%): [3.471, 4.213] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.977 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.641 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.093 ms/op
                 createUser·p0.9999: 11.689 ms/op
                 createUser·p1.00:   12.616 ms/op

Iteration   2: 2.968 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.552 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  6.654 ms/op
                 createUser·p0.9999: 13.095 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   3: 3.061 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.626 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.850 ms/op
                 createUser·p0.9999: 17.221 ms/op
                 createUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317796
  mean =      3.019 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2092 
    [ 1.250,  2.500) = 23032 
    [ 2.500,  3.750) = 274624 
    [ 3.750,  5.000) = 16468 
    [ 5.000,  6.250) = 987 
    [ 6.250,  7.500) = 283 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.278 ms/op
     p(99.9900) =     16.666 ms/op
     p(99.9990) =     17.460 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.002 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.006 ms/op
Iteration   1: 2.876 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.508 ms/op
                 existUser·p0.999:  7.634 ms/op
                 existUser·p0.9999: 20.840 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   2: 2.870 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.611 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  8.906 ms/op
                 existUser·p0.9999: 12.892 ms/op
                 existUser·p1.00:   13.074 ms/op

Iteration   3: 2.865 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.791 ms/op
                 existUser·p0.9999: 15.608 ms/op
                 existUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334291
  mean =      2.870 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51359 
    [ 2.500,  5.000) = 281761 
    [ 5.000,  7.500) = 789 
    [ 7.500, 10.000) = 140 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.018 ms/op
     p(99.9900) =     16.077 ms/op
     p(99.9990) =     20.993 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.022 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.007 ms/op
Iteration   1: 2.984 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  7.240 ms/op
                 getUser·p0.9999: 19.333 ms/op
                 getUser·p1.00:   19.661 ms/op

Iteration   2: 2.991 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.513 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  7.062 ms/op
                 getUser·p0.9999: 16.810 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.779 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.537 ms/op
                 getUser·p0.9999: 18.137 ms/op
                 getUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321618
  mean =      2.983 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1202 
    [ 1.250,  2.500) = 24243 
    [ 2.500,  3.750) = 283077 
    [ 3.750,  5.000) = 11968 
    [ 5.000,  6.250) = 612 
    [ 6.250,  7.500) = 274 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.925 ms/op
     p(99.9900) =     18.339 ms/op
     p(99.9990) =     19.607 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.045 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.955 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.010 ms/op
Iteration   1: 3.914 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.797 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  12.509 ms/op
                 listUser·p0.9999: 21.053 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   2: 3.842 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  13.994 ms/op
                 listUser·p0.9999: 19.933 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   3: 3.924 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  17.055 ms/op
                 listUser·p0.9999: 21.388 ms/op
                 listUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246725
  mean =      3.893 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4716 
    [ 2.500,  5.000) = 220882 
    [ 5.000,  7.500) = 20107 
    [ 7.500, 10.000) = 597 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.715 ms/op
     p(99.9000) =     14.013 ms/op
     p(99.9900) =     20.982 ms/op
     p(99.9990) =     23.779 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.649 ± 1.874  ops/ms
ClientGrpc.existUser                       thrpt       3  11.202 ± 2.719  ops/ms
ClientGrpc.getUser                         thrpt       3  10.628 ± 2.080  ops/ms
ClientGrpc.listUser                        thrpt       3   8.209 ± 2.874  ops/ms
ClientGrpc.createUser                       avgt       3   2.988 ± 0.077   ms/op
ClientGrpc.existUser                        avgt       3   2.864 ± 0.691   ms/op
ClientGrpc.getUser                          avgt       3   2.953 ± 0.414   ms/op
ClientGrpc.listUser                         avgt       3   3.842 ± 0.371   ms/op
ClientGrpc.createUser                     sample  317796   3.019 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.552           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.278           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.666           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.531           ms/op
ClientGrpc.existUser                      sample  334291   2.870 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.611           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.018           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.077           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.070           ms/op
ClientGrpc.getUser                        sample  321618   2.983 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.513           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.925           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.339           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.661           ms/op
ClientGrpc.listUser                       sample  246725   3.893 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.797           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.715           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.013           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.982           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.084           ms/op
