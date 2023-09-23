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
# Warmup Iteration   1: 3.483 ops/ms
# Warmup Iteration   2: 8.064 ops/ms
# Warmup Iteration   3: 9.341 ops/ms
Iteration   1: 9.347 ops/ms
Iteration   2: 8.935 ops/ms
Iteration   3: 9.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.425 ±(99.9%) 9.734 ops/ms [Average]
  (min, avg, max) = (8.935, 9.425, 9.994), stdev = 0.534
  CI (99.9%): [≈ 0, 19.159] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.769 ops/ms
# Warmup Iteration   2: 9.518 ops/ms
# Warmup Iteration   3: 10.049 ops/ms
Iteration   1: 9.214 ops/ms
Iteration   2: 9.745 ops/ms
Iteration   3: 9.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.519 ±(99.9%) 5.007 ops/ms [Average]
  (min, avg, max) = (9.214, 9.519, 9.745), stdev = 0.274
  CI (99.9%): [4.513, 14.526] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.719 ops/ms
# Warmup Iteration   2: 9.439 ops/ms
# Warmup Iteration   3: 9.764 ops/ms
Iteration   1: 9.614 ops/ms
Iteration   2: 9.866 ops/ms
Iteration   3: 9.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.796 ±(99.9%) 2.896 ops/ms [Average]
  (min, avg, max) = (9.614, 9.796, 9.908), stdev = 0.159
  CI (99.9%): [6.900, 12.692] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.930 ops/ms
# Warmup Iteration   2: 6.863 ops/ms
# Warmup Iteration   3: 7.425 ops/ms
Iteration   1: 7.797 ops/ms
Iteration   2: 7.814 ops/ms
Iteration   3: 7.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.831 ±(99.9%) 0.824 ops/ms [Average]
  (min, avg, max) = (7.797, 7.831, 7.882), stdev = 0.045
  CI (99.9%): [7.007, 8.655] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.798 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.332 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.002 ms/op
Iteration   1: 3.338 ±(99.9%) 0.002 ms/op
Iteration   2: 3.189 ±(99.9%) 0.003 ms/op
Iteration   3: 3.231 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.253 ±(99.9%) 1.399 ms/op [Average]
  (min, avg, max) = (3.189, 3.253, 3.338), stdev = 0.077
  CI (99.9%): [1.854, 4.651] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.076 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.002 ms/op
Iteration   2: 2.926 ±(99.9%) 0.002 ms/op
Iteration   3: 2.980 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.978 ±(99.9%) 0.934 ms/op [Average]
  (min, avg, max) = (2.926, 2.978, 3.028), stdev = 0.051
  CI (99.9%): [2.044, 3.912] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.744 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.002 ms/op
Iteration   1: 3.425 ±(99.9%) 0.001 ms/op
Iteration   2: 3.414 ±(99.9%) 0.003 ms/op
Iteration   3: 3.409 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.416 ±(99.9%) 0.154 ms/op [Average]
  (min, avg, max) = (3.409, 3.416, 3.425), stdev = 0.008
  CI (99.9%): [3.262, 3.569] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.045 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.627 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.542 ±(99.9%) 0.024 ms/op
Iteration   1: 4.245 ±(99.9%) 0.030 ms/op
Iteration   2: 4.457 ±(99.9%) 0.019 ms/op
Iteration   3: 4.385 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.362 ±(99.9%) 1.961 ms/op [Average]
  (min, avg, max) = (4.245, 4.362, 4.457), stdev = 0.107
  CI (99.9%): [2.402, 6.323] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.107 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.630 ±(99.9%) 0.010 ms/op
Iteration   1: 3.422 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.889 ms/op
                 createUser·p0.999:  11.623 ms/op
                 createUser·p0.9999: 14.117 ms/op
                 createUser·p1.00:   15.139 ms/op

Iteration   2: 3.715 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.707 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.415 ms/op
                 createUser·p0.99:   8.339 ms/op
                 createUser·p0.999:  13.052 ms/op
                 createUser·p0.9999: 21.455 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   3: 3.551 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  18.659 ms/op
                 createUser·p0.9999: 31.588 ms/op
                 createUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 269986
  mean =      3.558 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7700 
    [ 2.500,  5.000) = 251724 
    [ 5.000,  7.500) = 7812 
    [ 7.500, 10.000) = 2030 
    [10.000, 12.500) = 363 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     13.386 ms/op
     p(99.9900) =     30.835 ms/op
     p(99.9990) =     31.828 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.804 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.529 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.008 ms/op
Iteration   1: 3.092 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.428 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.955 ms/op
                 existUser·p0.999:  8.012 ms/op
                 existUser·p0.9999: 13.511 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   2: 3.083 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  9.985 ms/op
                 existUser·p0.9999: 16.397 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   3: 2.996 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.857 ms/op
                 existUser·p0.9999: 15.827 ms/op
                 existUser·p1.00:   16.253 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314228
  mean =      3.056 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 569 
    [ 1.250,  2.500) = 13888 
    [ 2.500,  3.750) = 283404 
    [ 3.750,  5.000) = 13576 
    [ 5.000,  6.250) = 1256 
    [ 6.250,  7.500) = 875 
    [ 7.500,  8.750) = 423 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =      8.362 ms/op
     p(99.9900) =     15.827 ms/op
     p(99.9990) =     16.667 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.775 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.459 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.007 ms/op
Iteration   1: 3.158 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  13.496 ms/op
                 getUser·p0.9999: 19.251 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   2: 3.378 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.683 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.149 ms/op
                 getUser·p0.999:  8.634 ms/op
                 getUser·p0.9999: 16.035 ms/op
                 getUser·p1.00:   16.581 ms/op

Iteration   3: 3.245 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  8.772 ms/op
                 getUser·p0.9999: 17.765 ms/op
                 getUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 294543
  mean =      3.258 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 311 
    [ 1.250,  2.500) = 9582 
    [ 2.500,  3.750) = 245109 
    [ 3.750,  5.000) = 33655 
    [ 5.000,  6.250) = 2998 
    [ 6.250,  7.500) = 1723 
    [ 7.500,  8.750) = 755 
    [ 8.750, 10.000) = 151 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 64 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     19.663 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 5.684 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.366 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.012 ms/op
Iteration   1: 4.252 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   6.169 ms/op
                 listUser·p0.99:   8.012 ms/op
                 listUser·p0.999:  15.434 ms/op
                 listUser·p0.9999: 17.055 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   2: 4.095 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.013 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  18.311 ms/op
                 listUser·p0.9999: 19.759 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   3: 4.140 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  15.897 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230633
  mean =      4.161 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 821 
    [ 2.500,  5.000) = 204051 
    [ 5.000,  7.500) = 23065 
    [ 7.500, 10.000) = 2001 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 211 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      6.021 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     16.243 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     20.669 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.425 ± 9.734  ops/ms
ClientGrpc.existUser                       thrpt       3   9.519 ± 5.007  ops/ms
ClientGrpc.getUser                         thrpt       3   9.796 ± 2.896  ops/ms
ClientGrpc.listUser                        thrpt       3   7.831 ± 0.824  ops/ms
ClientGrpc.createUser                       avgt       3   3.253 ± 1.399   ms/op
ClientGrpc.existUser                        avgt       3   2.978 ± 0.934   ms/op
ClientGrpc.getUser                          avgt       3   3.416 ± 0.154   ms/op
ClientGrpc.listUser                         avgt       3   4.362 ± 1.961   ms/op
ClientGrpc.createUser                     sample  269986   3.558 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.707           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.416           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.776           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.528           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.386           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.835           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.472           ms/op
ClientGrpc.existUser                      sample  314228   3.056 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.428           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.006           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.764           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.817           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.362           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.827           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.810           ms/op
ClientGrpc.getUser                        sample  294543   3.258 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.683           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.162           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.891           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.218           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.388           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.760           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.694           ms/op
ClientGrpc.listUser                       sample  230633   4.161 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.013           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.998           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.021           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.243           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.661           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.972           ms/op
