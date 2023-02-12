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
# Warmup Iteration   1: 3.294 ops/ms
# Warmup Iteration   2: 7.075 ops/ms
# Warmup Iteration   3: 8.195 ops/ms
Iteration   1: 8.646 ops/ms
Iteration   2: 8.531 ops/ms
Iteration   3: 8.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.549 ±(99.9%) 1.641 ops/ms [Average]
  (min, avg, max) = (8.469, 8.549, 8.646), stdev = 0.090
  CI (99.9%): [6.908, 10.190] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.949 ops/ms
# Warmup Iteration   2: 8.553 ops/ms
# Warmup Iteration   3: 8.730 ops/ms
Iteration   1: 9.081 ops/ms
Iteration   2: 9.222 ops/ms
Iteration   3: 8.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.083 ±(99.9%) 2.503 ops/ms [Average]
  (min, avg, max) = (8.947, 9.083, 9.222), stdev = 0.137
  CI (99.9%): [6.580, 11.586] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.967 ops/ms
# Warmup Iteration   2: 7.912 ops/ms
# Warmup Iteration   3: 8.187 ops/ms
Iteration   1: 8.400 ops/ms
Iteration   2: 8.319 ops/ms
Iteration   3: 8.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.423 ±(99.9%) 2.149 ops/ms [Average]
  (min, avg, max) = (8.319, 8.423, 8.551), stdev = 0.118
  CI (99.9%): [6.274, 10.572] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.569 ops/ms
# Warmup Iteration   2: 6.316 ops/ms
# Warmup Iteration   3: 6.610 ops/ms
Iteration   1: 6.597 ops/ms
Iteration   2: 6.788 ops/ms
Iteration   3: 6.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.645 ±(99.9%) 2.301 ops/ms [Average]
  (min, avg, max) = (6.550, 6.645, 6.788), stdev = 0.126
  CI (99.9%): [4.344, 8.946] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.242 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.775 ±(99.9%) 0.002 ms/op
Iteration   1: 3.861 ±(99.9%) 0.002 ms/op
Iteration   2: 3.808 ±(99.9%) 0.003 ms/op
Iteration   3: 3.758 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.809 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (3.758, 3.809, 3.861), stdev = 0.051
  CI (99.9%): [2.870, 4.749] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.872 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.822 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.643 ±(99.9%) 0.002 ms/op
Iteration   1: 3.642 ±(99.9%) 0.003 ms/op
Iteration   2: 3.625 ±(99.9%) 0.003 ms/op
Iteration   3: 3.581 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.616 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (3.581, 3.616, 3.642), stdev = 0.032
  CI (99.9%): [3.037, 4.196] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.382 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.692 ±(99.9%) 0.004 ms/op
Iteration   1: 3.703 ±(99.9%) 0.002 ms/op
Iteration   2: 3.807 ±(99.9%) 0.003 ms/op
Iteration   3: 3.738 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.749 ±(99.9%) 0.963 ms/op [Average]
  (min, avg, max) = (3.703, 3.749, 3.807), stdev = 0.053
  CI (99.9%): [2.786, 4.712] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.845 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 5.157 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.801 ±(99.9%) 0.016 ms/op
Iteration   1: 4.838 ±(99.9%) 0.019 ms/op
Iteration   2: 4.798 ±(99.9%) 0.016 ms/op
Iteration   3: 4.701 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.779 ±(99.9%) 1.281 ms/op [Average]
  (min, avg, max) = (4.701, 4.779, 4.838), stdev = 0.070
  CI (99.9%): [3.498, 6.060] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.474 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.009 ms/op
Iteration   1: 3.778 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   4.940 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  12.811 ms/op
                 createUser·p0.9999: 17.908 ms/op
                 createUser·p1.00:   18.219 ms/op

Iteration   2: 3.734 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   4.940 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  8.227 ms/op
                 createUser·p0.9999: 17.564 ms/op
                 createUser·p1.00:   17.859 ms/op

Iteration   3: 3.753 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.667 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  19.137 ms/op
                 createUser·p0.9999: 27.754 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255643
  mean =      3.755 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8780 
    [ 2.500,  5.000) = 236548 
    [ 5.000,  7.500) = 9593 
    [ 7.500, 10.000) = 387 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     12.097 ms/op
     p(99.9900) =     27.062 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.754 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.668 ±(99.9%) 0.009 ms/op
Iteration   1: 3.559 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.630 ms/op
                 existUser·p0.50:   3.568 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  8.225 ms/op
                 existUser·p0.9999: 14.926 ms/op
                 existUser·p1.00:   15.352 ms/op

Iteration   2: 3.615 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.873 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  7.476 ms/op
                 existUser·p0.9999: 18.126 ms/op
                 existUser·p1.00:   18.743 ms/op

Iteration   3: 3.631 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  11.731 ms/op
                 existUser·p0.9999: 19.280 ms/op
                 existUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266624
  mean =      3.602 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 429 
    [ 1.250,  2.500) = 13634 
    [ 2.500,  3.750) = 148201 
    [ 3.750,  5.000) = 98257 
    [ 5.000,  6.250) = 5067 
    [ 6.250,  7.500) = 610 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      5.446 ms/op
     p(99.9000) =      8.280 ms/op
     p(99.9900) =     18.678 ms/op
     p(99.9990) =     19.694 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.068 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.010 ms/op
Iteration   1: 3.869 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  8.193 ms/op
                 getUser·p0.9999: 24.609 ms/op
                 getUser·p1.00:   25.133 ms/op

Iteration   2: 3.837 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  10.420 ms/op
                 getUser·p0.9999: 20.240 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   3: 3.843 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.072 ms/op
                 getUser·p0.999:  12.042 ms/op
                 getUser·p0.9999: 25.407 ms/op
                 getUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 249223
  mean =      3.850 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6297 
    [ 2.500,  5.000) = 231575 
    [ 5.000,  7.500) = 10650 
    [ 7.500, 10.000) = 403 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     10.466 ms/op
     p(99.9900) =     24.674 ms/op
     p(99.9990) =     25.789 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 6.550 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.104 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.579 ±(99.9%) 0.014 ms/op
Iteration   1: 4.911 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.640 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.398 ms/op
                 listUser·p0.95:   7.168 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  20.334 ms/op
                 listUser·p0.9999: 22.084 ms/op
                 listUser·p1.00:   28.508 ms/op

Iteration   2: 4.856 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.250 ms/op
                 listUser·p0.95:   7.012 ms/op
                 listUser·p0.99:   8.494 ms/op
                 listUser·p0.999:  18.088 ms/op
                 listUser·p0.9999: 26.236 ms/op
                 listUser·p1.00:   26.640 ms/op

Iteration   3: 4.800 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   6.930 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  21.312 ms/op
                 listUser·p0.9999: 23.888 ms/op
                 listUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197688
  mean =      4.855 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 385 
    [ 2.500,  5.000) = 138328 
    [ 5.000,  7.500) = 52683 
    [ 7.500, 10.000) = 5544 
    [10.000, 12.500) = 363 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      6.259 ms/op
     p(95.0000) =      7.045 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     19.497 ms/op
     p(99.9900) =     24.460 ms/op
     p(99.9990) =     28.444 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.549 ± 1.641  ops/ms
ClientGrpc.existUser                       thrpt       3   9.083 ± 2.503  ops/ms
ClientGrpc.getUser                         thrpt       3   8.423 ± 2.149  ops/ms
ClientGrpc.listUser                        thrpt       3   6.645 ± 2.301  ops/ms
ClientGrpc.createUser                       avgt       3   3.809 ± 0.939   ms/op
ClientGrpc.existUser                        avgt       3   3.616 ± 0.579   ms/op
ClientGrpc.getUser                          avgt       3   3.749 ± 0.963   ms/op
ClientGrpc.listUser                         avgt       3   4.779 ± 1.281   ms/op
ClientGrpc.createUser                     sample  255643   3.755 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.667           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.915           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.849           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.097           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.062           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.213           ms/op
ClientGrpc.existUser                      sample  266624   3.602 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.630           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.719           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.446           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.280           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.678           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.857           ms/op
ClientGrpc.getUser                        sample  249223   3.850 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.772           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.710           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.964           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.890           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.466           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.674           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.887           ms/op
ClientGrpc.listUser                       sample  197688   4.855 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.061           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.259           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.651           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.497           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.460           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.508           ms/op
