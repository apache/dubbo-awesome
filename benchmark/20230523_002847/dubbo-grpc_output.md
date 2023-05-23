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
# Warmup Iteration   1: 4.672 ops/ms
# Warmup Iteration   2: 9.284 ops/ms
# Warmup Iteration   3: 10.549 ops/ms
Iteration   1: 10.621 ops/ms
Iteration   2: 11.073 ops/ms
Iteration   3: 10.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.728 ±(99.9%) 5.586 ops/ms [Average]
  (min, avg, max) = (10.489, 10.728, 11.073), stdev = 0.306
  CI (99.9%): [5.141, 16.314] (assumes normal distribution)


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
# Warmup Iteration   1: 7.749 ops/ms
# Warmup Iteration   2: 10.750 ops/ms
# Warmup Iteration   3: 10.934 ops/ms
Iteration   1: 11.146 ops/ms
Iteration   2: 11.169 ops/ms
Iteration   3: 11.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.179 ±(99.9%) 0.730 ops/ms [Average]
  (min, avg, max) = (11.146, 11.179, 11.224), stdev = 0.040
  CI (99.9%): [10.449, 11.910] (assumes normal distribution)


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
# Warmup Iteration   1: 7.709 ops/ms
# Warmup Iteration   2: 10.329 ops/ms
# Warmup Iteration   3: 10.856 ops/ms
Iteration   1: 10.826 ops/ms
Iteration   2: 10.703 ops/ms
Iteration   3: 10.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.780 ±(99.9%) 1.226 ops/ms [Average]
  (min, avg, max) = (10.703, 10.780, 10.826), stdev = 0.067
  CI (99.9%): [9.554, 12.005] (assumes normal distribution)


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
# Warmup Iteration   1: 5.949 ops/ms
# Warmup Iteration   2: 8.217 ops/ms
# Warmup Iteration   3: 8.275 ops/ms
Iteration   1: 8.309 ops/ms
Iteration   2: 8.321 ops/ms
Iteration   3: 8.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.331 ±(99.9%) 0.517 ops/ms [Average]
  (min, avg, max) = (8.309, 8.331, 8.363), stdev = 0.028
  CI (99.9%): [7.814, 8.847] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.003 ms/op
Iteration   1: 3.008 ±(99.9%) 0.002 ms/op
Iteration   2: 3.026 ±(99.9%) 0.002 ms/op
Iteration   3: 3.013 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.016 ±(99.9%) 0.171 ms/op [Average]
  (min, avg, max) = (3.008, 3.016, 3.026), stdev = 0.009
  CI (99.9%): [2.845, 3.187] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.891 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.003 ms/op
Iteration   1: 2.940 ±(99.9%) 0.002 ms/op
Iteration   2: 2.868 ±(99.9%) 0.004 ms/op
Iteration   3: 2.850 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.886 ±(99.9%) 0.871 ms/op [Average]
  (min, avg, max) = (2.850, 2.886, 2.940), stdev = 0.048
  CI (99.9%): [2.015, 3.757] (assumes normal distribution)


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.003 ms/op
Iteration   1: 2.973 ±(99.9%) 0.003 ms/op
Iteration   2: 2.999 ±(99.9%) 0.002 ms/op
Iteration   3: 2.959 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.977 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (2.959, 2.977, 2.999), stdev = 0.020
  CI (99.9%): [2.608, 3.347] (assumes normal distribution)


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
# Warmup Iteration   1: 5.088 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.955 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.764 ±(99.9%) 0.015 ms/op
Iteration   1: 3.924 ±(99.9%) 0.029 ms/op
Iteration   2: 3.843 ±(99.9%) 0.023 ms/op
Iteration   3: 3.849 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.872 ±(99.9%) 0.825 ms/op [Average]
  (min, avg, max) = (3.843, 3.872, 3.924), stdev = 0.045
  CI (99.9%): [3.047, 4.698] (assumes normal distribution)


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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.007 ms/op
Iteration   1: 2.967 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  6.267 ms/op
                 createUser·p0.9999: 11.751 ms/op
                 createUser·p1.00:   12.009 ms/op

Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.607 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.676 ms/op
                 createUser·p0.9999: 13.904 ms/op
                 createUser·p1.00:   16.286 ms/op

Iteration   3: 2.971 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.334 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  14.025 ms/op
                 createUser·p0.9999: 23.462 ms/op
                 createUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322269
  mean =      2.978 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26682 
    [ 2.500,  5.000) = 294529 
    [ 5.000,  7.500) = 683 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      9.063 ms/op
     p(99.9900) =     20.854 ms/op
     p(99.9990) =     23.939 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 3.605 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.794 ±(99.9%) 0.006 ms/op
Iteration   1: 2.781 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.757 ms/op
                 existUser·p0.9999: 18.169 ms/op
                 existUser·p1.00:   19.661 ms/op

Iteration   2: 2.925 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.561 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  6.923 ms/op
                 existUser·p0.9999: 20.087 ms/op
                 existUser·p1.00:   22.479 ms/op

Iteration   3: 2.872 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  7.115 ms/op
                 existUser·p0.9999: 28.597 ms/op
                 existUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336106
  mean =      2.858 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50520 
    [ 2.500,  5.000) = 284693 
    [ 5.000,  7.500) = 697 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.914 ms/op
     p(99.9900) =     22.399 ms/op
     p(99.9990) =     28.726 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
Iteration   1: 3.020 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.761 ms/op
                 getUser·p0.999:  8.152 ms/op
                 getUser·p0.9999: 19.557 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   2: 2.962 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  6.956 ms/op
                 getUser·p0.9999: 16.083 ms/op
                 getUser·p1.00:   16.417 ms/op

Iteration   3: 2.986 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  8.730 ms/op
                 getUser·p0.9999: 17.311 ms/op
                 getUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320843
  mean =      2.989 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28785 
    [ 2.500,  5.000) = 290243 
    [ 5.000,  7.500) = 1356 
    [ 7.500, 10.000) = 257 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.225 ms/op
     p(99.9900) =     18.393 ms/op
     p(99.9990) =     19.975 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 5.122 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.010 ms/op
Iteration   1: 3.867 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.838 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  12.651 ms/op
                 listUser·p0.9999: 19.773 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   2: 3.671 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  13.435 ms/op
                 listUser·p0.9999: 19.940 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   3: 3.924 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.729 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  13.651 ms/op
                 listUser·p0.9999: 17.526 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251594
  mean =      3.817 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5816 
    [ 2.500,  5.000) = 226805 
    [ 5.000,  7.500) = 17775 
    [ 7.500, 10.000) = 627 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 233 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.665 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     13.294 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     20.791 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.728 ± 5.586  ops/ms
ClientGrpc.existUser                       thrpt       3  11.179 ± 0.730  ops/ms
ClientGrpc.getUser                         thrpt       3  10.780 ± 1.226  ops/ms
ClientGrpc.listUser                        thrpt       3   8.331 ± 0.517  ops/ms
ClientGrpc.createUser                       avgt       3   3.016 ± 0.171   ms/op
ClientGrpc.existUser                        avgt       3   2.886 ± 0.871   ms/op
ClientGrpc.getUser                          avgt       3   2.977 ± 0.370   ms/op
ClientGrpc.listUser                         avgt       3   3.872 ± 0.825   ms/op
ClientGrpc.createUser                     sample  322269   2.978 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.607           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.063           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.854           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.084           ms/op
ClientGrpc.existUser                      sample  336106   2.858 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.561           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.914           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.399           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.803           ms/op
ClientGrpc.getUser                        sample  320843   2.989 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.554           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.225           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.393           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.087           ms/op
ClientGrpc.listUser                       sample  251594   3.817 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.729           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.707           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.665           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.489           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.294           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.661           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.939           ms/op
