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
# Warmup Iteration   1: 1.863 ops/ms
# Warmup Iteration   2: 4.677 ops/ms
# Warmup Iteration   3: 6.033 ops/ms
Iteration   1: 6.030 ops/ms
Iteration   2: 6.350 ops/ms
Iteration   3: 6.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.193 ±(99.9%) 2.923 ops/ms [Average]
  (min, avg, max) = (6.030, 6.193, 6.350), stdev = 0.160
  CI (99.9%): [3.270, 9.117] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.513 ops/ms
# Warmup Iteration   2: 6.830 ops/ms
# Warmup Iteration   3: 6.942 ops/ms
Iteration   1: 6.825 ops/ms
Iteration   2: 6.764 ops/ms
Iteration   3: 6.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.752 ±(99.9%) 1.451 ops/ms [Average]
  (min, avg, max) = (6.667, 6.752, 6.825), stdev = 0.080
  CI (99.9%): [5.300, 8.203] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.605 ops/ms
# Warmup Iteration   2: 5.912 ops/ms
# Warmup Iteration   3: 6.287 ops/ms
Iteration   1: 6.637 ops/ms
Iteration   2: 6.474 ops/ms
Iteration   3: 6.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.555 ±(99.9%) 1.493 ops/ms [Average]
  (min, avg, max) = (6.474, 6.555, 6.637), stdev = 0.082
  CI (99.9%): [5.062, 8.049] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.109 ops/ms
# Warmup Iteration   2: 4.657 ops/ms
# Warmup Iteration   3: 4.866 ops/ms
Iteration   1: 4.955 ops/ms
Iteration   2: 4.977 ops/ms
Iteration   3: 5.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.017 ±(99.9%) 1.637 ops/ms [Average]
  (min, avg, max) = (4.955, 5.017, 5.120), stdev = 0.090
  CI (99.9%): [3.381, 6.654] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.330 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.167 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 5.168 ±(99.9%) 0.022 ms/op
Iteration   1: 5.202 ±(99.9%) 0.005 ms/op
Iteration   2: 5.175 ±(99.9%) 0.005 ms/op
Iteration   3: 5.129 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.169 ±(99.9%) 0.674 ms/op [Average]
  (min, avg, max) = (5.129, 5.169, 5.202), stdev = 0.037
  CI (99.9%): [4.495, 5.842] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.287 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.007 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.907 ±(99.9%) 0.019 ms/op
Iteration   1: 4.734 ±(99.9%) 0.005 ms/op
Iteration   2: 4.566 ±(99.9%) 0.004 ms/op
Iteration   3: 4.708 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.669 ±(99.9%) 1.645 ms/op [Average]
  (min, avg, max) = (4.566, 4.669, 4.734), stdev = 0.090
  CI (99.9%): [3.024, 6.315] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.766 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.285 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.124 ±(99.9%) 0.006 ms/op
Iteration   1: 4.894 ±(99.9%) 0.005 ms/op
Iteration   2: 5.122 ±(99.9%) 0.006 ms/op
Iteration   3: 4.958 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.991 ±(99.9%) 2.140 ms/op [Average]
  (min, avg, max) = (4.894, 4.991, 5.122), stdev = 0.117
  CI (99.9%): [2.852, 7.131] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 8.975 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 6.773 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 6.455 ±(99.9%) 0.058 ms/op
Iteration   1: 6.691 ±(99.9%) 0.040 ms/op
Iteration   2: 6.722 ±(99.9%) 0.053 ms/op
Iteration   3: 6.724 ±(99.9%) 0.049 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.712 ±(99.9%) 0.336 ms/op [Average]
  (min, avg, max) = (6.691, 6.712, 6.724), stdev = 0.018
  CI (99.9%): [6.376, 7.048] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.710 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 5.280 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.043 ±(99.9%) 0.019 ms/op
Iteration   1: 5.122 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   4.907 ms/op
                 createUser·p0.90:   6.693 ms/op
                 createUser·p0.95:   7.504 ms/op
                 createUser·p0.99:   10.273 ms/op
                 createUser·p0.999:  14.512 ms/op
                 createUser·p0.9999: 16.552 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   2: 5.059 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   4.858 ms/op
                 createUser·p0.90:   6.472 ms/op
                 createUser·p0.95:   7.176 ms/op
                 createUser·p0.99:   9.339 ms/op
                 createUser·p0.999:  15.204 ms/op
                 createUser·p0.9999: 21.422 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 5.159 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   5.014 ms/op
                 createUser·p0.90:   6.660 ms/op
                 createUser·p0.95:   7.340 ms/op
                 createUser·p0.99:   9.552 ms/op
                 createUser·p0.999:  18.256 ms/op
                 createUser·p0.9999: 23.031 ms/op
                 createUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 187790
  mean =      5.113 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2138 
    [ 2.500,  5.000) = 97434 
    [ 5.000,  7.500) = 80041 
    [ 7.500, 10.000) = 6594 
    [10.000, 12.500) = 1113 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      4.915 ms/op
     p(90.0000) =      6.611 ms/op
     p(95.0000) =      7.340 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     15.909 ms/op
     p(99.9900) =     22.093 ms/op
     p(99.9990) =     25.259 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.543 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.442 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.966 ±(99.9%) 0.018 ms/op
Iteration   1: 4.777 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   4.637 ms/op
                 existUser·p0.90:   6.259 ms/op
                 existUser·p0.95:   6.889 ms/op
                 existUser·p0.99:   8.946 ms/op
                 existUser·p0.999:  16.139 ms/op
                 existUser·p0.9999: 20.139 ms/op
                 existUser·p1.00:   20.775 ms/op

Iteration   2: 4.779 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   4.645 ms/op
                 existUser·p0.90:   6.201 ms/op
                 existUser·p0.95:   6.849 ms/op
                 existUser·p0.99:   8.684 ms/op
                 existUser·p0.999:  12.919 ms/op
                 existUser·p0.9999: 22.466 ms/op
                 existUser·p1.00:   22.839 ms/op

Iteration   3: 4.513 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   4.317 ms/op
                 existUser·p0.90:   5.693 ms/op
                 existUser·p0.95:   6.382 ms/op
                 existUser·p0.99:   8.765 ms/op
                 existUser·p0.999:  18.789 ms/op
                 existUser·p0.9999: 25.196 ms/op
                 existUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 204723
  mean =      4.686 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4900 
    [ 2.500,  5.000) = 135397 
    [ 5.000,  7.500) = 59195 
    [ 7.500, 10.000) = 4263 
    [10.000, 12.500) = 617 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      6.087 ms/op
     p(95.0000) =      6.734 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     15.815 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     28.078 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.535 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 5.141 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.832 ±(99.9%) 0.017 ms/op
Iteration   1: 4.770 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   4.604 ms/op
                 getUser·p0.90:   6.218 ms/op
                 getUser·p0.95:   6.849 ms/op
                 getUser·p0.99:   9.306 ms/op
                 getUser·p0.999:  13.250 ms/op
                 getUser·p0.9999: 24.553 ms/op
                 getUser·p1.00:   24.904 ms/op

Iteration   2: 5.142 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.540 ms/op
                 getUser·p0.50:   4.964 ms/op
                 getUser·p0.90:   6.586 ms/op
                 getUser·p0.95:   7.348 ms/op
                 getUser·p0.99:   9.659 ms/op
                 getUser·p0.999:  13.859 ms/op
                 getUser·p0.9999: 25.494 ms/op
                 getUser·p1.00:   26.182 ms/op

Iteration   3: 5.032 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   4.850 ms/op
                 getUser·p0.90:   6.431 ms/op
                 getUser·p0.95:   7.127 ms/op
                 getUser·p0.99:   10.011 ms/op
                 getUser·p0.999:  15.172 ms/op
                 getUser·p0.9999: 29.557 ms/op
                 getUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 192951
  mean =      4.977 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3495 
    [ 2.500,  5.000) = 106980 
    [ 5.000,  7.500) = 75299 
    [ 7.500, 10.000) = 5590 
    [10.000, 12.500) = 1171 
    [12.500, 15.000) = 247 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      4.801 ms/op
     p(90.0000) =      6.414 ms/op
     p(95.0000) =      7.119 ms/op
     p(99.0000) =      9.650 ms/op
     p(99.9000) =     14.402 ms/op
     p(99.9900) =     29.262 ms/op
     p(99.9990) =     30.278 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.728 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 7.322 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 6.696 ±(99.9%) 0.029 ms/op
Iteration   1: 6.467 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.657 ms/op
                 listUser·p0.50:   6.070 ms/op
                 listUser·p0.90:   8.700 ms/op
                 listUser·p0.95:   9.863 ms/op
                 listUser·p0.99:   12.686 ms/op
                 listUser·p0.999:  19.680 ms/op
                 listUser·p0.9999: 21.210 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   2: 6.557 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   8.880 ms/op
                 listUser·p0.95:   10.093 ms/op
                 listUser·p0.99:   12.615 ms/op
                 listUser·p0.999:  22.596 ms/op
                 listUser·p0.9999: 26.918 ms/op
                 listUser·p1.00:   27.263 ms/op

Iteration   3: 6.228 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.927 ms/op
                 listUser·p0.50:   5.865 ms/op
                 listUser·p0.90:   8.315 ms/op
                 listUser·p0.95:   9.437 ms/op
                 listUser·p0.99:   12.485 ms/op
                 listUser·p0.999:  22.793 ms/op
                 listUser·p0.9999: 27.109 ms/op
                 listUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 149688
  mean =      6.414 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 23904 
    [ 5.000,  7.500) = 97187 
    [ 7.500, 10.000) = 21822 
    [10.000, 12.500) = 5167 
    [12.500, 15.000) = 1056 
    [15.000, 17.500) = 222 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      6.029 ms/op
     p(90.0000) =      8.634 ms/op
     p(95.0000) =      9.814 ms/op
     p(99.0000) =     12.583 ms/op
     p(99.9000) =     20.457 ms/op
     p(99.9900) =     26.739 ms/op
     p(99.9990) =     27.575 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.193 ± 2.923  ops/ms
ClientGrpc.existUser                       thrpt       3   6.752 ± 1.451  ops/ms
ClientGrpc.getUser                         thrpt       3   6.555 ± 1.493  ops/ms
ClientGrpc.listUser                        thrpt       3   5.017 ± 1.637  ops/ms
ClientGrpc.createUser                       avgt       3   5.169 ± 0.674   ms/op
ClientGrpc.existUser                        avgt       3   4.669 ± 1.645   ms/op
ClientGrpc.getUser                          avgt       3   4.991 ± 2.140   ms/op
ClientGrpc.listUser                         avgt       3   6.712 ± 0.336   ms/op
ClientGrpc.createUser                     sample  187790   5.113 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.041           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.915           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.611           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.340           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.732           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.909           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.093           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.461           ms/op
ClientGrpc.existUser                      sample  204723   4.686 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.645           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           6.087           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.734           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.798           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          15.815           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.740           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.246           ms/op
ClientGrpc.getUser                        sample  192951   4.977 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.958           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.801           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.414           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.119           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.650           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.402           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.262           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.278           ms/op
ClientGrpc.listUser                       sample  149688   6.414 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.473           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           6.029           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.634           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.814           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.583           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.457           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.739           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.623           ms/op
