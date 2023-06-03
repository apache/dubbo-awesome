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
# Warmup Iteration   1: 4.029 ops/ms
# Warmup Iteration   2: 8.994 ops/ms
# Warmup Iteration   3: 9.904 ops/ms
Iteration   1: 10.619 ops/ms
Iteration   2: 10.882 ops/ms
Iteration   3: 10.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.644 ±(99.9%) 4.126 ops/ms [Average]
  (min, avg, max) = (10.432, 10.644, 10.882), stdev = 0.226
  CI (99.9%): [6.518, 14.770] (assumes normal distribution)


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
# Warmup Iteration   1: 7.115 ops/ms
# Warmup Iteration   2: 10.345 ops/ms
# Warmup Iteration   3: 10.954 ops/ms
Iteration   1: 10.860 ops/ms
Iteration   2: 11.073 ops/ms
Iteration   3: 10.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.942 ±(99.9%) 2.086 ops/ms [Average]
  (min, avg, max) = (10.860, 10.942, 11.073), stdev = 0.114
  CI (99.9%): [8.857, 13.028] (assumes normal distribution)


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
# Warmup Iteration   1: 7.008 ops/ms
# Warmup Iteration   2: 9.962 ops/ms
# Warmup Iteration   3: 10.405 ops/ms
Iteration   1: 10.492 ops/ms
Iteration   2: 10.591 ops/ms
Iteration   3: 10.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.508 ±(99.9%) 1.396 ops/ms [Average]
  (min, avg, max) = (10.441, 10.508, 10.591), stdev = 0.076
  CI (99.9%): [9.112, 11.904] (assumes normal distribution)


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
# Warmup Iteration   1: 5.605 ops/ms
# Warmup Iteration   2: 7.689 ops/ms
# Warmup Iteration   3: 7.818 ops/ms
Iteration   1: 7.999 ops/ms
Iteration   2: 7.872 ops/ms
Iteration   3: 7.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.920 ±(99.9%) 1.265 ops/ms [Average]
  (min, avg, max) = (7.872, 7.920, 7.999), stdev = 0.069
  CI (99.9%): [6.655, 9.185] (assumes normal distribution)


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
# Warmup Iteration   1: 4.683 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.003 ms/op
Iteration   1: 3.082 ±(99.9%) 0.002 ms/op
Iteration   2: 3.070 ±(99.9%) 0.002 ms/op
Iteration   3: 2.995 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.049 ±(99.9%) 0.859 ms/op [Average]
  (min, avg, max) = (2.995, 3.049, 3.082), stdev = 0.047
  CI (99.9%): [2.190, 3.908] (assumes normal distribution)


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
# Warmup Iteration   1: 4.176 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.861 ±(99.9%) 0.002 ms/op
Iteration   1: 2.840 ±(99.9%) 0.002 ms/op
Iteration   2: 2.902 ±(99.9%) 0.002 ms/op
Iteration   3: 2.930 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.891 ±(99.9%) 0.842 ms/op [Average]
  (min, avg, max) = (2.840, 2.891, 2.930), stdev = 0.046
  CI (99.9%): [2.048, 3.733] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.184 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.004 ms/op
Iteration   1: 3.054 ±(99.9%) 0.002 ms/op
Iteration   2: 3.005 ±(99.9%) 0.004 ms/op
Iteration   3: 3.047 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.035 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (3.005, 3.035, 3.054), stdev = 0.026
  CI (99.9%): [2.559, 3.512] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.616 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.009 ms/op
Iteration   1: 3.976 ±(99.9%) 0.009 ms/op
Iteration   2: 3.964 ±(99.9%) 0.026 ms/op
Iteration   3: 3.945 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.962 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (3.945, 3.962, 3.976), stdev = 0.016
  CI (99.9%): [3.669, 4.254] (assumes normal distribution)


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
# Warmup Iteration   1: 4.194 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.726 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  7.863 ms/op
                 createUser·p0.9999: 16.703 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   2: 3.037 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.543 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  8.117 ms/op
                 createUser·p0.9999: 19.087 ms/op
                 createUser·p1.00:   19.497 ms/op

Iteration   3: 3.091 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  12.892 ms/op
                 createUser·p0.9999: 27.448 ms/op
                 createUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314415
  mean =      3.052 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15832 
    [ 2.500,  5.000) = 296863 
    [ 5.000,  7.500) = 1294 
    [ 7.500, 10.000) = 118 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     26.531 ms/op
     p(99.9990) =     27.712 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 3.896 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 2.947 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.356 ms/op
                 existUser·p0.999:  6.615 ms/op
                 existUser·p0.9999: 13.339 ms/op
                 existUser·p1.00:   13.730 ms/op

Iteration   2: 2.985 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  8.860 ms/op
                 existUser·p0.9999: 15.357 ms/op
                 existUser·p1.00:   16.531 ms/op

Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.207 ms/op
                 existUser·p0.999:  11.190 ms/op
                 existUser·p0.9999: 17.243 ms/op
                 existUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323481
  mean =      2.966 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 722 
    [ 1.250,  2.500) = 26259 
    [ 2.500,  3.750) = 287120 
    [ 3.750,  5.000) = 8315 
    [ 5.000,  6.250) = 460 
    [ 6.250,  7.500) = 274 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 57 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.681 ms/op
     p(99.9900) =     16.679 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 4.479 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.006 ms/op
Iteration   1: 3.072 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.175 ms/op
                 getUser·p0.9999: 13.457 ms/op
                 getUser·p1.00:   13.795 ms/op

Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.783 ms/op
                 getUser·p0.999:  8.147 ms/op
                 getUser·p0.9999: 15.475 ms/op
                 getUser·p1.00:   15.974 ms/op

Iteration   3: 3.042 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.896 ms/op
                 getUser·p0.9999: 17.612 ms/op
                 getUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313737
  mean =      3.060 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 480 
    [ 1.250,  2.500) = 14690 
    [ 2.500,  3.750) = 281850 
    [ 3.750,  5.000) = 14987 
    [ 5.000,  6.250) = 1024 
    [ 6.250,  7.500) = 377 
    [ 7.500,  8.750) = 132 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.535 ms/op
     p(99.9000) =      7.604 ms/op
     p(99.9900) =     17.191 ms/op
     p(99.9990) =     18.477 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 5.759 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.239 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.011 ms/op
Iteration   1: 4.034 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  13.391 ms/op
                 listUser·p0.9999: 22.089 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 4.050 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.924 ms/op
                 listUser·p0.9999: 18.419 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   3: 4.061 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 24.126 ms/op
                 listUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237212
  mean =      4.048 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2442 
    [ 2.500,  5.000) = 209724 
    [ 5.000,  7.500) = 23687 
    [ 7.500, 10.000) = 958 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.052 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     23.471 ms/op
     p(99.9990) =     25.445 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.644 ± 4.126  ops/ms
ClientGrpc.existUser                       thrpt       3  10.942 ± 2.086  ops/ms
ClientGrpc.getUser                         thrpt       3  10.508 ± 1.396  ops/ms
ClientGrpc.listUser                        thrpt       3   7.920 ± 1.265  ops/ms
ClientGrpc.createUser                       avgt       3   3.049 ± 0.859   ms/op
ClientGrpc.existUser                        avgt       3   2.891 ± 0.842   ms/op
ClientGrpc.getUser                          avgt       3   3.035 ± 0.477   ms/op
ClientGrpc.listUser                         avgt       3   3.962 ± 0.293   ms/op
ClientGrpc.createUser                     sample  314415   3.052 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.645           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.732           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.531           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.886           ms/op
ClientGrpc.existUser                      sample  323481   2.966 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.734           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.681           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.679           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.367           ms/op
ClientGrpc.getUser                        sample  313737   3.060 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.686           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.535           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.604           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.191           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.530           ms/op
ClientGrpc.listUser                       sample  237212   4.048 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.063           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.052           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.139           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.471           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.690           ms/op
