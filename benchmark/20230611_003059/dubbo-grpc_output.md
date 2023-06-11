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
# Warmup Iteration   1: 4.797 ops/ms
# Warmup Iteration   2: 9.628 ops/ms
# Warmup Iteration   3: 10.137 ops/ms
Iteration   1: 10.738 ops/ms
Iteration   2: 10.625 ops/ms
Iteration   3: 10.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.635 ±(99.9%) 1.797 ops/ms [Average]
  (min, avg, max) = (10.541, 10.635, 10.738), stdev = 0.099
  CI (99.9%): [8.838, 12.432] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.741 ops/ms
# Warmup Iteration   2: 11.018 ops/ms
# Warmup Iteration   3: 11.166 ops/ms
Iteration   1: 11.210 ops/ms
Iteration   2: 11.321 ops/ms
Iteration   3: 11.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.226 ±(99.9%) 1.613 ops/ms [Average]
  (min, avg, max) = (11.147, 11.226, 11.321), stdev = 0.088
  CI (99.9%): [9.613, 12.840] (assumes normal distribution)


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
# Warmup Iteration   1: 7.468 ops/ms
# Warmup Iteration   2: 10.111 ops/ms
# Warmup Iteration   3: 10.655 ops/ms
Iteration   1: 10.819 ops/ms
Iteration   2: 10.981 ops/ms
Iteration   3: 10.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.837 ±(99.9%) 2.467 ops/ms [Average]
  (min, avg, max) = (10.712, 10.837, 10.981), stdev = 0.135
  CI (99.9%): [8.370, 13.305] (assumes normal distribution)


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
# Warmup Iteration   1: 6.172 ops/ms
# Warmup Iteration   2: 8.324 ops/ms
# Warmup Iteration   3: 8.199 ops/ms
Iteration   1: 8.253 ops/ms
Iteration   2: 8.175 ops/ms
Iteration   3: 8.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.219 ±(99.9%) 0.722 ops/ms [Average]
  (min, avg, max) = (8.175, 8.219, 8.253), stdev = 0.040
  CI (99.9%): [7.496, 8.941] (assumes normal distribution)


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.004 ms/op
Iteration   1: 3.022 ±(99.9%) 0.002 ms/op
Iteration   2: 3.033 ±(99.9%) 0.003 ms/op
Iteration   3: 2.983 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.013 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (2.983, 3.013, 3.033), stdev = 0.026
  CI (99.9%): [2.538, 3.488] (assumes normal distribution)


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.942 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.894 ±(99.9%) 0.004 ms/op
Iteration   1: 2.849 ±(99.9%) 0.004 ms/op
Iteration   2: 2.811 ±(99.9%) 0.005 ms/op
Iteration   3: 2.877 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.846 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (2.811, 2.846, 2.877), stdev = 0.033
  CI (99.9%): [2.241, 3.450] (assumes normal distribution)


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
# Warmup Iteration   1: 3.844 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.003 ms/op
Iteration   1: 3.001 ±(99.9%) 0.003 ms/op
Iteration   2: 3.024 ±(99.9%) 0.002 ms/op
Iteration   3: 2.941 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.988 ±(99.9%) 0.779 ms/op [Average]
  (min, avg, max) = (2.941, 2.988, 3.024), stdev = 0.043
  CI (99.9%): [2.210, 3.767] (assumes normal distribution)


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
# Warmup Iteration   1: 4.437 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.020 ms/op
Iteration   1: 3.861 ±(99.9%) 0.018 ms/op
Iteration   2: 3.855 ±(99.9%) 0.044 ms/op
Iteration   3: 3.949 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.888 ±(99.9%) 0.968 ms/op [Average]
  (min, avg, max) = (3.855, 3.888, 3.949), stdev = 0.053
  CI (99.9%): [2.920, 4.857] (assumes normal distribution)


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
Iteration   1: 2.911 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.405 ms/op
                 createUser·p0.9999: 14.418 ms/op
                 createUser·p1.00:   14.680 ms/op

Iteration   2: 2.927 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.497 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.273 ms/op
                 createUser·p0.95:   3.432 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  10.258 ms/op
                 createUser·p0.9999: 17.695 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.580 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.501 ms/op
                 createUser·p0.9999: 22.537 ms/op
                 createUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 327699
  mean =      2.934 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31434 
    [ 2.500,  5.000) = 294685 
    [ 5.000,  7.500) = 1087 
    [ 7.500, 10.000) = 246 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      9.278 ms/op
     p(99.9900) =     20.619 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 3.908 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.918 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.903 ±(99.9%) 0.006 ms/op
Iteration   1: 2.846 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.614 ms/op
                 existUser·p0.9999: 19.005 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   2: 2.879 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  6.791 ms/op
                 existUser·p0.9999: 15.330 ms/op
                 existUser·p1.00:   16.007 ms/op

Iteration   3: 2.931 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  8.149 ms/op
                 existUser·p0.9999: 27.460 ms/op
                 existUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332673
  mean =      2.885 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51368 
    [ 2.500,  5.000) = 280207 
    [ 5.000,  7.500) = 810 
    [ 7.500, 10.000) = 118 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.004 ms/op
     p(99.9900) =     20.611 ms/op
     p(99.9990) =     27.558 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 3.783 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.389 ms/op
                 getUser·p0.999:  6.417 ms/op
                 getUser·p0.9999: 16.985 ms/op
                 getUser·p1.00:   17.269 ms/op

Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.953 ms/op
                 getUser·p0.9999: 13.499 ms/op
                 getUser·p1.00:   13.877 ms/op

Iteration   3: 2.932 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.053 ms/op
                 getUser·p0.9999: 13.517 ms/op
                 getUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321216
  mean =      2.987 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2107 
    [ 1.250,  2.500) = 24100 
    [ 2.500,  3.750) = 278923 
    [ 3.750,  5.000) = 14935 
    [ 5.000,  6.250) = 741 
    [ 6.250,  7.500) = 160 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      6.611 ms/op
     p(99.9900) =     16.206 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 5.407 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.011 ms/op
Iteration   1: 3.855 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  12.421 ms/op
                 listUser·p0.9999: 13.643 ms/op
                 listUser·p1.00:   13.959 ms/op

Iteration   2: 3.844 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  15.911 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   3: 3.913 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  21.110 ms/op
                 listUser·p0.9999: 24.526 ms/op
                 listUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247840
  mean =      3.870 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4521 
    [ 2.500,  5.000) = 224927 
    [ 5.000,  7.500) = 17153 
    [ 7.500, 10.000) = 794 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     24.758 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.635 ± 1.797  ops/ms
ClientGrpc.existUser                       thrpt       3  11.226 ± 1.613  ops/ms
ClientGrpc.getUser                         thrpt       3  10.837 ± 2.467  ops/ms
ClientGrpc.listUser                        thrpt       3   8.219 ± 0.722  ops/ms
ClientGrpc.createUser                       avgt       3   3.013 ± 0.475   ms/op
ClientGrpc.existUser                        avgt       3   2.846 ± 0.604   ms/op
ClientGrpc.getUser                          avgt       3   2.988 ± 0.779   ms/op
ClientGrpc.listUser                         avgt       3   3.888 ± 0.968   ms/op
ClientGrpc.createUser                     sample  327699   2.934 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.497           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.937           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.351           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.278           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.619           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.331           ms/op
ClientGrpc.existUser                      sample  332673   2.885 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.669           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.004           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.611           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.410           ms/op
ClientGrpc.getUser                        sample  321216   2.987 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.637           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.611           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.206           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.269           ms/op
ClientGrpc.listUser                       sample  247840   3.870 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.980           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.628           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.582           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.084           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.871           ms/op
