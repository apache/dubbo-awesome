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
# Warmup Iteration   1: 2.015 ops/ms
# Warmup Iteration   2: 5.371 ops/ms
# Warmup Iteration   3: 6.832 ops/ms
Iteration   1: 6.838 ops/ms
Iteration   2: 6.885 ops/ms
Iteration   3: 6.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.898 ±(99.9%) 1.233 ops/ms [Average]
  (min, avg, max) = (6.838, 6.898, 6.971), stdev = 0.068
  CI (99.9%): [5.665, 8.132] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.409 ops/ms
# Warmup Iteration   2: 6.804 ops/ms
# Warmup Iteration   3: 7.113 ops/ms
Iteration   1: 7.459 ops/ms
Iteration   2: 7.702 ops/ms
Iteration   3: 8.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.783 ±(99.9%) 6.775 ops/ms [Average]
  (min, avg, max) = (7.459, 7.783, 8.189), stdev = 0.371
  CI (99.9%): [1.009, 14.558] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.189 ops/ms
# Warmup Iteration   2: 6.587 ops/ms
# Warmup Iteration   3: 6.935 ops/ms
Iteration   1: 7.139 ops/ms
Iteration   2: 7.191 ops/ms
Iteration   3: 7.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.159 ±(99.9%) 0.505 ops/ms [Average]
  (min, avg, max) = (7.139, 7.159, 7.191), stdev = 0.028
  CI (99.9%): [6.654, 7.664] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.327 ops/ms
# Warmup Iteration   2: 5.095 ops/ms
# Warmup Iteration   3: 5.312 ops/ms
Iteration   1: 5.276 ops/ms
Iteration   2: 5.362 ops/ms
Iteration   3: 5.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.367 ±(99.9%) 1.710 ops/ms [Average]
  (min, avg, max) = (5.276, 5.367, 5.463), stdev = 0.094
  CI (99.9%): [3.658, 7.077] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.696 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.989 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.711 ±(99.9%) 0.002 ms/op
Iteration   1: 4.696 ±(99.9%) 0.005 ms/op
Iteration   2: 4.652 ±(99.9%) 0.003 ms/op
Iteration   3: 4.699 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.683 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (4.652, 4.683, 4.699), stdev = 0.026
  CI (99.9%): [4.203, 5.162] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.502 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.140 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.538 ±(99.9%) 0.002 ms/op
Iteration   1: 4.518 ±(99.9%) 0.003 ms/op
Iteration   2: 4.383 ±(99.9%) 0.004 ms/op
Iteration   3: 4.506 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.469 ±(99.9%) 1.361 ms/op [Average]
  (min, avg, max) = (4.383, 4.469, 4.518), stdev = 0.075
  CI (99.9%): [3.108, 5.830] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.178 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.993 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.685 ±(99.9%) 0.005 ms/op
Iteration   1: 4.725 ±(99.9%) 0.007 ms/op
Iteration   2: 4.647 ±(99.9%) 0.004 ms/op
Iteration   3: 4.683 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.685 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (4.647, 4.685, 4.725), stdev = 0.039
  CI (99.9%): [3.971, 5.399] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.231 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 6.267 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.910 ±(99.9%) 0.018 ms/op
Iteration   1: 5.827 ±(99.9%) 0.014 ms/op
Iteration   2: 5.872 ±(99.9%) 0.017 ms/op
Iteration   3: 5.652 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.784 ±(99.9%) 2.118 ms/op [Average]
  (min, avg, max) = (5.652, 5.784, 5.872), stdev = 0.116
  CI (99.9%): [3.666, 7.902] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.754 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 5.018 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.734 ±(99.9%) 0.016 ms/op
Iteration   1: 4.846 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   4.645 ms/op
                 createUser·p0.90:   6.324 ms/op
                 createUser·p0.95:   6.922 ms/op
                 createUser·p0.99:   9.019 ms/op
                 createUser·p0.999:  14.123 ms/op
                 createUser·p0.9999: 17.635 ms/op
                 createUser·p1.00:   18.055 ms/op

Iteration   2: 4.766 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.432 ms/op
                 createUser·p0.50:   4.596 ms/op
                 createUser·p0.90:   6.201 ms/op
                 createUser·p0.95:   6.824 ms/op
                 createUser·p0.99:   9.126 ms/op
                 createUser·p0.999:  14.533 ms/op
                 createUser·p0.9999: 19.211 ms/op
                 createUser·p1.00:   19.628 ms/op

Iteration   3: 4.740 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   4.555 ms/op
                 createUser·p0.90:   6.070 ms/op
                 createUser·p0.95:   6.578 ms/op
                 createUser·p0.99:   8.815 ms/op
                 createUser·p0.999:  22.086 ms/op
                 createUser·p0.9999: 26.976 ms/op
                 createUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 200712
  mean =      4.784 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2519 
    [ 2.500,  5.000) = 126521 
    [ 5.000,  7.500) = 66363 
    [ 7.500, 10.000) = 4199 
    [10.000, 12.500) = 727 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      6.201 ms/op
     p(95.0000) =      6.775 ms/op
     p(99.0000) =      9.011 ms/op
     p(99.9000) =     15.034 ms/op
     p(99.9900) =     26.671 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 6.856 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.894 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.616 ±(99.9%) 0.016 ms/op
Iteration   1: 4.540 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   4.399 ms/op
                 existUser·p0.90:   5.882 ms/op
                 existUser·p0.95:   6.545 ms/op
                 existUser·p0.99:   8.602 ms/op
                 existUser·p0.999:  11.836 ms/op
                 existUser·p0.9999: 17.230 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   2: 4.690 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   6.095 ms/op
                 existUser·p0.95:   6.808 ms/op
                 existUser·p0.99:   9.142 ms/op
                 existUser·p0.999:  13.825 ms/op
                 existUser·p0.9999: 21.152 ms/op
                 existUser·p1.00:   22.184 ms/op

Iteration   3: 4.531 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   4.366 ms/op
                 existUser·p0.90:   5.849 ms/op
                 existUser·p0.95:   6.357 ms/op
                 existUser·p0.99:   8.684 ms/op
                 existUser·p0.999:  13.386 ms/op
                 existUser·p0.9999: 22.774 ms/op
                 existUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 209503
  mean =      4.586 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5287 
    [ 2.500,  5.000) = 141535 
    [ 5.000,  7.500) = 57561 
    [ 7.500, 10.000) = 4122 
    [10.000, 12.500) = 716 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.939 ms/op
     p(95.0000) =      6.570 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     13.132 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     22.902 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 7.021 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.959 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.811 ±(99.9%) 0.017 ms/op
Iteration   1: 4.658 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   4.506 ms/op
                 getUser·p0.90:   5.915 ms/op
                 getUser·p0.95:   6.480 ms/op
                 getUser·p0.99:   8.978 ms/op
                 getUser·p0.999:  12.512 ms/op
                 getUser·p0.9999: 18.942 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   2: 4.690 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   4.571 ms/op
                 getUser·p0.90:   6.095 ms/op
                 getUser·p0.95:   6.521 ms/op
                 getUser·p0.99:   8.225 ms/op
                 getUser·p0.999:  13.996 ms/op
                 getUser·p0.9999: 23.408 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   3: 4.730 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   4.596 ms/op
                 getUser·p0.90:   6.029 ms/op
                 getUser·p0.95:   6.529 ms/op
                 getUser·p0.99:   8.618 ms/op
                 getUser·p0.999:  13.229 ms/op
                 getUser·p0.9999: 26.165 ms/op
                 getUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 204507
  mean =      4.692 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3655 
    [ 2.500,  5.000) = 132053 
    [ 5.000,  7.500) = 64749 
    [ 7.500, 10.000) = 3088 
    [10.000, 12.500) = 697 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      6.513 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     13.263 ms/op
     p(99.9900) =     23.626 ms/op
     p(99.9990) =     26.766 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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
# Warmup Iteration   1: 8.527 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 6.101 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.775 ±(99.9%) 0.024 ms/op
Iteration   1: 5.738 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.876 ms/op
                 listUser·p0.50:   5.390 ms/op
                 listUser·p0.90:   7.750 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.436 ms/op
                 listUser·p0.999:  18.157 ms/op
                 listUser·p0.9999: 25.366 ms/op
                 listUser·p1.00:   29.000 ms/op

Iteration   2: 5.678 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.681 ms/op
                 listUser·p0.50:   5.358 ms/op
                 listUser·p0.90:   7.520 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   11.043 ms/op
                 listUser·p0.999:  18.416 ms/op
                 listUser·p0.9999: 32.042 ms/op
                 listUser·p1.00:   32.473 ms/op

Iteration   3: 5.846 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.874 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   7.946 ms/op
                 listUser·p0.95:   8.847 ms/op
                 listUser·p0.99:   11.158 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 26.367 ms/op
                 listUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166735
  mean =      5.753 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 127 
    [ 2.500,  5.000) = 55399 
    [ 5.000,  7.500) = 91382 
    [ 7.500, 10.000) = 16393 
    [10.000, 12.500) = 2550 
    [12.500, 15.000) = 511 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      5.415 ms/op
     p(90.0000) =      7.750 ms/op
     p(95.0000) =      8.700 ms/op
     p(99.0000) =     11.223 ms/op
     p(99.9000) =     18.949 ms/op
     p(99.9900) =     30.878 ms/op
     p(99.9990) =     32.429 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.898 ± 1.233  ops/ms
ClientGrpc.existUser                       thrpt       3   7.783 ± 6.775  ops/ms
ClientGrpc.getUser                         thrpt       3   7.159 ± 0.505  ops/ms
ClientGrpc.listUser                        thrpt       3   5.367 ± 1.710  ops/ms
ClientGrpc.createUser                       avgt       3   4.683 ± 0.480   ms/op
ClientGrpc.existUser                        avgt       3   4.469 ± 1.361   ms/op
ClientGrpc.getUser                          avgt       3   4.685 ± 0.714   ms/op
ClientGrpc.listUser                         avgt       3   5.784 ± 2.118   ms/op
ClientGrpc.createUser                     sample  200712   4.784 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.890           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.201           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.775           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.011           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.034           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.671           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.329           ms/op
ClientGrpc.existUser                      sample  209503   4.586 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.057           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.939           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.570           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.831           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.132           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.479           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.265           ms/op
ClientGrpc.getUser                        sample  204507   4.692 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.858           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.021           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.513           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.651           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.263           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.626           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.870           ms/op
ClientGrpc.listUser                       sample  166735   5.753 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.874           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.750           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.700           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.223           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.949           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.878           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.473           ms/op
