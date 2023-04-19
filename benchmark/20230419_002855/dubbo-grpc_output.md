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
# Warmup Iteration   1: 4.070 ops/ms
# Warmup Iteration   2: 8.556 ops/ms
# Warmup Iteration   3: 9.962 ops/ms
Iteration   1: 10.384 ops/ms
Iteration   2: 10.480 ops/ms
Iteration   3: 10.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.410 ±(99.9%) 1.120 ops/ms [Average]
  (min, avg, max) = (10.366, 10.410, 10.480), stdev = 0.061
  CI (99.9%): [9.290, 11.531] (assumes normal distribution)


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
# Warmup Iteration   1: 7.722 ops/ms
# Warmup Iteration   2: 10.520 ops/ms
# Warmup Iteration   3: 11.031 ops/ms
Iteration   1: 10.928 ops/ms
Iteration   2: 10.926 ops/ms
Iteration   3: 10.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.922 ±(99.9%) 0.148 ops/ms [Average]
  (min, avg, max) = (10.913, 10.922, 10.928), stdev = 0.008
  CI (99.9%): [10.775, 11.070] (assumes normal distribution)


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
# Warmup Iteration   1: 6.912 ops/ms
# Warmup Iteration   2: 9.755 ops/ms
# Warmup Iteration   3: 10.407 ops/ms
Iteration   1: 10.501 ops/ms
Iteration   2: 10.490 ops/ms
Iteration   3: 10.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.465 ±(99.9%) 0.960 ops/ms [Average]
  (min, avg, max) = (10.405, 10.465, 10.501), stdev = 0.053
  CI (99.9%): [9.505, 11.425] (assumes normal distribution)


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
# Warmup Iteration   1: 6.271 ops/ms
# Warmup Iteration   2: 7.521 ops/ms
# Warmup Iteration   3: 8.024 ops/ms
Iteration   1: 8.013 ops/ms
Iteration   2: 8.060 ops/ms
Iteration   3: 8.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.050 ±(99.9%) 0.597 ops/ms [Average]
  (min, avg, max) = (8.013, 8.050, 8.076), stdev = 0.033
  CI (99.9%): [7.452, 8.647] (assumes normal distribution)


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.004 ms/op
Iteration   1: 3.013 ±(99.9%) 0.003 ms/op
Iteration   2: 3.016 ±(99.9%) 0.004 ms/op
Iteration   3: 3.012 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.013 ±(99.9%) 0.041 ms/op [Average]
  (min, avg, max) = (3.012, 3.013, 3.016), stdev = 0.002
  CI (99.9%): [2.973, 3.054] (assumes normal distribution)


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
# Warmup Iteration   1: 4.030 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.004 ms/op
Iteration   1: 2.894 ±(99.9%) 0.003 ms/op
Iteration   2: 2.884 ±(99.9%) 0.004 ms/op
Iteration   3: 2.857 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.878 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (2.857, 2.878, 2.894), stdev = 0.019
  CI (99.9%): [2.530, 3.227] (assumes normal distribution)


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
# Warmup Iteration   1: 4.196 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.003 ms/op
Iteration   1: 3.059 ±(99.9%) 0.003 ms/op
Iteration   2: 3.097 ±(99.9%) 0.002 ms/op
Iteration   3: 3.043 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.066 ±(99.9%) 0.499 ms/op [Average]
  (min, avg, max) = (3.043, 3.066, 3.097), stdev = 0.027
  CI (99.9%): [2.567, 3.566] (assumes normal distribution)


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
# Warmup Iteration   1: 5.642 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.021 ms/op
Iteration   1: 4.028 ±(99.9%) 0.020 ms/op
Iteration   2: 4.016 ±(99.9%) 0.006 ms/op
Iteration   3: 4.060 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.035 ±(99.9%) 0.418 ms/op [Average]
  (min, avg, max) = (4.016, 4.035, 4.060), stdev = 0.023
  CI (99.9%): [3.616, 4.453] (assumes normal distribution)


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
# Warmup Iteration   1: 4.489 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.007 ms/op
Iteration   1: 3.062 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  11.141 ms/op
                 createUser·p0.9999: 12.747 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   2: 3.062 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.699 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  9.597 ms/op
                 createUser·p0.9999: 14.494 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  7.483 ms/op
                 createUser·p0.9999: 17.465 ms/op
                 createUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313686
  mean =      3.058 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 362 
    [ 1.250,  2.500) = 19154 
    [ 2.500,  3.750) = 274813 
    [ 3.750,  5.000) = 17713 
    [ 5.000,  6.250) = 852 
    [ 6.250,  7.500) = 362 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =     11.015 ms/op
     p(99.9900) =     16.462 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.414 ms/op
                 existUser·p0.9999: 14.598 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   2: 2.900 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  6.598 ms/op
                 existUser·p0.9999: 12.992 ms/op
                 existUser·p1.00:   13.189 ms/op

Iteration   3: 2.851 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.170 ms/op
                 existUser·p0.95:   3.330 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.849 ms/op
                 existUser·p0.9999: 21.292 ms/op
                 existUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331559
  mean =      2.896 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39212 
    [ 2.500,  5.000) = 291196 
    [ 5.000,  7.500) = 873 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      6.996 ms/op
     p(99.9900) =     19.262 ms/op
     p(99.9990) =     21.387 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 4.171 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.005 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  8.087 ms/op
                 getUser·p0.9999: 12.469 ms/op
                 getUser·p1.00:   12.927 ms/op

Iteration   2: 3.051 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.382 ms/op
                 getUser·p0.9999: 13.976 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  9.503 ms/op
                 getUser·p0.9999: 16.430 ms/op
                 getUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315612
  mean =      3.040 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 629 
    [ 1.250,  2.500) = 23100 
    [ 2.500,  3.750) = 273760 
    [ 3.750,  5.000) = 16345 
    [ 5.000,  6.250) = 1103 
    [ 6.250,  7.500) = 287 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     15.204 ms/op
     p(99.9990) =     16.734 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 5.399 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.011 ms/op
Iteration   1: 4.021 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.030 ms/op
                 listUser·p0.9999: 19.957 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   2: 3.959 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 17.030 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   3: 3.938 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.921 ms/op
                 listUser·p0.999:  17.131 ms/op
                 listUser·p0.9999: 25.351 ms/op
                 listUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241811
  mean =      3.972 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2371 
    [ 2.500,  5.000) = 217405 
    [ 5.000,  7.500) = 20844 
    [ 7.500, 10.000) = 772 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     14.274 ms/op
     p(99.9900) =     23.891 ms/op
     p(99.9990) =     25.859 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.410 ± 1.120  ops/ms
ClientGrpc.existUser                       thrpt       3  10.922 ± 0.148  ops/ms
ClientGrpc.getUser                         thrpt       3  10.465 ± 0.960  ops/ms
ClientGrpc.listUser                        thrpt       3   8.050 ± 0.597  ops/ms
ClientGrpc.createUser                       avgt       3   3.013 ± 0.041   ms/op
ClientGrpc.existUser                        avgt       3   2.878 ± 0.349   ms/op
ClientGrpc.getUser                          avgt       3   3.066 ± 0.499   ms/op
ClientGrpc.listUser                         avgt       3   4.035 ± 0.418   ms/op
ClientGrpc.createUser                     sample  313686   3.058 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.699           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.015           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.462           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.662           ms/op
ClientGrpc.existUser                      sample  331559   2.896 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.537           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.996           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.262           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.561           ms/op
ClientGrpc.getUser                        sample  315612   3.040 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.746           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.569           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.204           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.876           ms/op
ClientGrpc.listUser                       sample  241811   3.972 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.098           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.274           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.891           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.985           ms/op
