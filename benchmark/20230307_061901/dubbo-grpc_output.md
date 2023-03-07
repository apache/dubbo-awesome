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
# Warmup Iteration   1: 4.870 ops/ms
# Warmup Iteration   2: 9.438 ops/ms
# Warmup Iteration   3: 10.896 ops/ms
Iteration   1: 10.522 ops/ms
Iteration   2: 10.843 ops/ms
Iteration   3: 10.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.596 ±(99.9%) 4.013 ops/ms [Average]
  (min, avg, max) = (10.422, 10.596, 10.843), stdev = 0.220
  CI (99.9%): [6.583, 14.609] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.412 ops/ms
# Warmup Iteration   2: 10.913 ops/ms
# Warmup Iteration   3: 11.069 ops/ms
Iteration   1: 11.106 ops/ms
Iteration   2: 11.280 ops/ms
Iteration   3: 10.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.111 ±(99.9%) 3.035 ops/ms [Average]
  (min, avg, max) = (10.947, 11.111, 11.280), stdev = 0.166
  CI (99.9%): [8.076, 14.146] (assumes normal distribution)


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
# Warmup Iteration   1: 8.029 ops/ms
# Warmup Iteration   2: 10.687 ops/ms
# Warmup Iteration   3: 10.794 ops/ms
Iteration   1: 10.479 ops/ms
Iteration   2: 10.759 ops/ms
Iteration   3: 10.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.551 ±(99.9%) 3.338 ops/ms [Average]
  (min, avg, max) = (10.416, 10.551, 10.759), stdev = 0.183
  CI (99.9%): [7.213, 13.889] (assumes normal distribution)


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
# Warmup Iteration   1: 7.025 ops/ms
# Warmup Iteration   2: 7.723 ops/ms
# Warmup Iteration   3: 7.967 ops/ms
Iteration   1: 7.931 ops/ms
Iteration   2: 7.956 ops/ms
Iteration   3: 8.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.014 ±(99.9%) 2.239 ops/ms [Average]
  (min, avg, max) = (7.931, 8.014, 8.155), stdev = 0.123
  CI (99.9%): [5.775, 10.253] (assumes normal distribution)


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
# Warmup Iteration   1: 3.790 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.003 ms/op
Iteration   1: 3.009 ±(99.9%) 0.003 ms/op
Iteration   2: 3.011 ±(99.9%) 0.002 ms/op
Iteration   3: 2.949 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.990 ±(99.9%) 0.645 ms/op [Average]
  (min, avg, max) = (2.949, 2.990, 3.011), stdev = 0.035
  CI (99.9%): [2.345, 3.634] (assumes normal distribution)


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
# Warmup Iteration   1: 3.764 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.890 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.002 ms/op
Iteration   1: 2.962 ±(99.9%) 0.002 ms/op
Iteration   2: 2.883 ±(99.9%) 0.002 ms/op
Iteration   3: 2.959 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.935 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (2.883, 2.935, 2.962), stdev = 0.045
  CI (99.9%): [2.117, 3.752] (assumes normal distribution)


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
# Warmup Iteration   1: 4.071 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.002 ms/op
Iteration   1: 2.993 ±(99.9%) 0.002 ms/op
Iteration   2: 3.003 ±(99.9%) 0.002 ms/op
Iteration   3: 3.073 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.023 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (2.993, 3.023, 3.073), stdev = 0.044
  CI (99.9%): [2.225, 3.821] (assumes normal distribution)


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
# Warmup Iteration   1: 5.157 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.011 ms/op
Iteration   1: 3.898 ±(99.9%) 0.041 ms/op
Iteration   2: 3.951 ±(99.9%) 0.022 ms/op
Iteration   3: 3.911 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.920 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (3.898, 3.920, 3.951), stdev = 0.028
  CI (99.9%): [3.415, 4.425] (assumes normal distribution)


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 2.981 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.503 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.494 ms/op
                 createUser·p0.9999: 11.498 ms/op
                 createUser·p1.00:   11.813 ms/op

Iteration   2: 2.957 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.162 ms/op
                 createUser·p0.999:  6.265 ms/op
                 createUser·p0.9999: 14.192 ms/op
                 createUser·p1.00:   14.680 ms/op

Iteration   3: 3.122 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.245 ms/op
                 createUser·p0.999:  6.829 ms/op
                 createUser·p0.9999: 26.444 ms/op
                 createUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318251
  mean =      3.018 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36522 
    [ 2.500,  5.000) = 280806 
    [ 5.000,  7.500) = 624 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.176 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     26.759 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 3.749 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.862 ±(99.9%) 0.006 ms/op
Iteration   1: 2.895 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  6.488 ms/op
                 existUser·p0.9999: 11.764 ms/op
                 existUser·p1.00:   13.468 ms/op

Iteration   2: 2.975 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.796 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  6.602 ms/op
                 existUser·p0.9999: 12.681 ms/op
                 existUser·p1.00:   12.861 ms/op

Iteration   3: 2.837 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  11.460 ms/op
                 existUser·p0.9999: 23.616 ms/op
                 existUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330844
  mean =      2.901 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57441 
    [ 2.500,  5.000) = 272560 
    [ 5.000,  7.500) = 500 
    [ 7.500, 10.000) = 50 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      8.187 ms/op
     p(99.9900) =     14.739 ms/op
     p(99.9990) =     23.921 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 3.625 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.456 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.520 ms/op
                 getUser·p0.9999: 11.813 ms/op
                 getUser·p1.00:   12.141 ms/op

Iteration   2: 3.065 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.987 ms/op
                 getUser·p0.9999: 13.058 ms/op
                 getUser·p1.00:   13.287 ms/op

Iteration   3: 2.978 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.080 ms/op
                 getUser·p0.999:  7.569 ms/op
                 getUser·p0.9999: 17.859 ms/op
                 getUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316829
  mean =      3.030 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1234 
    [ 1.250,  2.500) = 28842 
    [ 2.500,  3.750) = 264138 
    [ 3.750,  5.000) = 21495 
    [ 5.000,  6.250) = 509 
    [ 6.250,  7.500) = 255 
    [ 7.500,  8.750) = 154 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.660 ms/op
     p(99.9900) =     15.024 ms/op
     p(99.9990) =     18.017 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 4.835 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.011 ms/op
Iteration   1: 3.940 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  12.453 ms/op
                 listUser·p0.9999: 14.530 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   2: 3.920 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  13.623 ms/op
                 listUser·p0.9999: 15.735 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   3: 3.962 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.404 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.223 ms/op
                 listUser·p0.9999: 25.354 ms/op
                 listUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243733
  mean =      3.941 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5718 
    [ 2.500,  5.000) = 212675 
    [ 5.000,  7.500) = 23981 
    [ 7.500, 10.000) = 882 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     20.628 ms/op
     p(99.9990) =     25.764 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.596 ± 4.013  ops/ms
ClientGrpc.existUser                       thrpt       3  11.111 ± 3.035  ops/ms
ClientGrpc.getUser                         thrpt       3  10.551 ± 3.338  ops/ms
ClientGrpc.listUser                        thrpt       3   8.014 ± 2.239  ops/ms
ClientGrpc.createUser                       avgt       3   2.990 ± 0.645   ms/op
ClientGrpc.existUser                        avgt       3   2.935 ± 0.817   ms/op
ClientGrpc.getUser                          avgt       3   3.023 ± 0.798   ms/op
ClientGrpc.listUser                         avgt       3   3.920 ± 0.505   ms/op
ClientGrpc.createUser                     sample  318251   3.018 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.503           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.176           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.559           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.968           ms/op
ClientGrpc.existUser                      sample  330844   2.901 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.540           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.187           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.739           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.052           ms/op
ClientGrpc.getUser                        sample  316829   3.030 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.456           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.660           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.024           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.481           ms/op
ClientGrpc.listUser                       sample  243733   3.941 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.404           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.582           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.628           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.854           ms/op
