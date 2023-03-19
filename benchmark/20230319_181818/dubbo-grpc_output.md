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
# Warmup Iteration   1: 4.196 ops/ms
# Warmup Iteration   2: 8.989 ops/ms
# Warmup Iteration   3: 10.344 ops/ms
Iteration   1: 10.595 ops/ms
Iteration   2: 10.605 ops/ms
Iteration   3: 10.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.540 ±(99.9%) 1.889 ops/ms [Average]
  (min, avg, max) = (10.421, 10.540, 10.605), stdev = 0.104
  CI (99.9%): [8.651, 12.430] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.866 ops/ms
# Warmup Iteration   2: 10.698 ops/ms
# Warmup Iteration   3: 10.923 ops/ms
Iteration   1: 10.985 ops/ms
Iteration   2: 10.920 ops/ms
Iteration   3: 11.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.043 ±(99.9%) 2.932 ops/ms [Average]
  (min, avg, max) = (10.920, 11.043, 11.225), stdev = 0.161
  CI (99.9%): [8.111, 13.975] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.237 ops/ms
# Warmup Iteration   2: 10.216 ops/ms
# Warmup Iteration   3: 10.693 ops/ms
Iteration   1: 10.743 ops/ms
Iteration   2: 10.730 ops/ms
Iteration   3: 10.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.749 ±(99.9%) 0.421 ops/ms [Average]
  (min, avg, max) = (10.730, 10.749, 10.775), stdev = 0.023
  CI (99.9%): [10.328, 11.170] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.054 ops/ms
# Warmup Iteration   2: 7.868 ops/ms
# Warmup Iteration   3: 8.138 ops/ms
Iteration   1: 8.057 ops/ms
Iteration   2: 8.390 ops/ms
Iteration   3: 8.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.166 ±(99.9%) 3.536 ops/ms [Average]
  (min, avg, max) = (8.051, 8.166, 8.390), stdev = 0.194
  CI (99.9%): [4.630, 11.702] (assumes normal distribution)


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
# Warmup Iteration   1: 4.257 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.003 ms/op
Iteration   1: 3.014 ±(99.9%) 0.003 ms/op
Iteration   2: 3.054 ±(99.9%) 0.003 ms/op
Iteration   3: 3.041 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.036 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (3.014, 3.036, 3.054), stdev = 0.021
  CI (99.9%): [2.659, 3.413] (assumes normal distribution)


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.838 ±(99.9%) 0.003 ms/op
Iteration   1: 2.948 ±(99.9%) 0.002 ms/op
Iteration   2: 2.933 ±(99.9%) 0.002 ms/op
Iteration   3: 2.970 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.950 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (2.933, 2.950, 2.970), stdev = 0.019
  CI (99.9%): [2.611, 3.290] (assumes normal distribution)


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
# Warmup Iteration   1: 4.093 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.002 ms/op
Iteration   1: 3.014 ±(99.9%) 0.003 ms/op
Iteration   2: 3.081 ±(99.9%) 0.003 ms/op
Iteration   3: 3.051 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.049 ±(99.9%) 0.614 ms/op [Average]
  (min, avg, max) = (3.014, 3.049, 3.081), stdev = 0.034
  CI (99.9%): [2.435, 3.663] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.193 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.220 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.015 ms/op
Iteration   1: 3.900 ±(99.9%) 0.022 ms/op
Iteration   2: 4.005 ±(99.9%) 0.009 ms/op
Iteration   3: 3.969 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.958 ±(99.9%) 0.973 ms/op [Average]
  (min, avg, max) = (3.900, 3.958, 4.005), stdev = 0.053
  CI (99.9%): [2.985, 4.931] (assumes normal distribution)


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
# Warmup Iteration   1: 4.344 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.007 ms/op
Iteration   1: 3.214 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.559 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  11.098 ms/op
                 createUser·p0.9999: 13.568 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   2: 3.141 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.828 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.907 ms/op
                 createUser·p0.999:  8.031 ms/op
                 createUser·p0.9999: 13.907 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.515 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   4.857 ms/op
                 createUser·p0.999:  9.340 ms/op
                 createUser·p0.9999: 20.709 ms/op
                 createUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303385
  mean =      3.164 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17792 
    [ 2.500,  5.000) = 282188 
    [ 5.000,  7.500) = 2591 
    [ 7.500, 10.000) = 489 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =     10.348 ms/op
     p(99.9900) =     20.272 ms/op
     p(99.9990) =     21.363 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 4.047 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.901 ±(99.9%) 0.007 ms/op
Iteration   1: 2.935 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.743 ms/op
                 existUser·p0.999:  8.553 ms/op
                 existUser·p0.9999: 13.240 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   2: 2.926 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  7.778 ms/op
                 existUser·p0.9999: 16.681 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   3: 2.929 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  11.665 ms/op
                 existUser·p0.9999: 17.337 ms/op
                 existUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327414
  mean =      2.930 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2341 
    [ 1.250,  2.500) = 37590 
    [ 2.500,  3.750) = 276194 
    [ 3.750,  5.000) = 9245 
    [ 5.000,  6.250) = 1276 
    [ 6.250,  7.500) = 286 
    [ 7.500,  8.750) = 156 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      8.749 ms/op
     p(99.9900) =     16.597 ms/op
     p(99.9990) =     17.710 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.006 ms/op
Iteration   1: 3.067 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  9.829 ms/op
                 getUser·p0.9999: 12.766 ms/op
                 getUser·p1.00:   13.025 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  8.687 ms/op
                 getUser·p0.9999: 14.713 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   3: 3.163 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.487 ms/op
                 getUser·p0.9999: 24.609 ms/op
                 getUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308757
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14258 
    [ 2.500,  5.000) = 292920 
    [ 5.000,  7.500) = 1196 
    [ 7.500, 10.000) = 145 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      9.232 ms/op
     p(99.9900) =     23.585 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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
# Warmup Iteration   1: 5.472 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.201 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.012 ms/op
Iteration   1: 4.187 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   7.628 ms/op
                 listUser·p0.999:  14.455 ms/op
                 listUser·p0.9999: 18.001 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   2: 4.218 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.485 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 21.097 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   3: 4.156 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.335 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 229356
  mean =      4.187 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1548 
    [ 2.500,  5.000) = 195410 
    [ 5.000,  7.500) = 29943 
    [ 7.500, 10.000) = 1893 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     16.204 ms/op
     p(99.9900) =     21.170 ms/op
     p(99.9990) =     21.683 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.540 ± 1.889  ops/ms
ClientGrpc.existUser                       thrpt       3  11.043 ± 2.932  ops/ms
ClientGrpc.getUser                         thrpt       3  10.749 ± 0.421  ops/ms
ClientGrpc.listUser                        thrpt       3   8.166 ± 3.536  ops/ms
ClientGrpc.createUser                       avgt       3   3.036 ± 0.377   ms/op
ClientGrpc.existUser                        avgt       3   2.950 ± 0.339   ms/op
ClientGrpc.getUser                          avgt       3   3.049 ± 0.614   ms/op
ClientGrpc.listUser                         avgt       3   3.958 ± 0.973   ms/op
ClientGrpc.createUser                     sample  303385   3.164 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.515           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.113           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.047           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.128           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.348           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.272           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.529           ms/op
ClientGrpc.existUser                      sample  327414   2.930 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.635           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.628           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.749           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.597           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.859           ms/op
ClientGrpc.getUser                        sample  308757   3.106 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.847           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.232           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.585           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.707           ms/op
ClientGrpc.listUser                       sample  229356   4.187 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.157           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.969           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.087           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.569           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.204           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.170           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.823           ms/op
