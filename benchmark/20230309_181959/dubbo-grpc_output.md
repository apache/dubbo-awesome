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
# Warmup Iteration   1: 3.248 ops/ms
# Warmup Iteration   2: 6.241 ops/ms
# Warmup Iteration   3: 7.842 ops/ms
Iteration   1: 8.575 ops/ms
Iteration   2: 8.528 ops/ms
Iteration   3: 8.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.545 ±(99.9%) 0.471 ops/ms [Average]
  (min, avg, max) = (8.528, 8.545, 8.575), stdev = 0.026
  CI (99.9%): [8.074, 9.017] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.930 ops/ms
# Warmup Iteration   2: 8.344 ops/ms
# Warmup Iteration   3: 9.003 ops/ms
Iteration   1: 9.020 ops/ms
Iteration   2: 9.275 ops/ms
Iteration   3: 9.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.166 ±(99.9%) 2.405 ops/ms [Average]
  (min, avg, max) = (9.020, 9.166, 9.275), stdev = 0.132
  CI (99.9%): [6.761, 11.571] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.291 ops/ms
# Warmup Iteration   2: 8.200 ops/ms
# Warmup Iteration   3: 8.145 ops/ms
Iteration   1: 8.680 ops/ms
Iteration   2: 8.735 ops/ms
Iteration   3: 8.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.727 ±(99.9%) 0.796 ops/ms [Average]
  (min, avg, max) = (8.680, 8.727, 8.766), stdev = 0.044
  CI (99.9%): [7.931, 9.523] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.426 ops/ms
# Warmup Iteration   2: 6.593 ops/ms
# Warmup Iteration   3: 6.717 ops/ms
Iteration   1: 6.770 ops/ms
Iteration   2: 6.918 ops/ms
Iteration   3: 6.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.835 ±(99.9%) 1.379 ops/ms [Average]
  (min, avg, max) = (6.770, 6.835, 6.918), stdev = 0.076
  CI (99.9%): [5.456, 8.214] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.676 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.896 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.006 ms/op
Iteration   1: 3.842 ±(99.9%) 0.004 ms/op
Iteration   2: 3.705 ±(99.9%) 0.003 ms/op
Iteration   3: 3.652 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.733 ±(99.9%) 1.793 ms/op [Average]
  (min, avg, max) = (3.652, 3.733, 3.842), stdev = 0.098
  CI (99.9%): [1.940, 5.526] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.128 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.003 ms/op
Iteration   1: 3.499 ±(99.9%) 0.004 ms/op
Iteration   2: 3.446 ±(99.9%) 0.004 ms/op
Iteration   3: 3.501 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.482 ±(99.9%) 0.570 ms/op [Average]
  (min, avg, max) = (3.446, 3.482, 3.501), stdev = 0.031
  CI (99.9%): [2.912, 4.052] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.205 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.735 ±(99.9%) 0.007 ms/op
Iteration   1: 3.627 ±(99.9%) 0.005 ms/op
Iteration   2: 3.533 ±(99.9%) 0.005 ms/op
Iteration   3: 3.606 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.588 ±(99.9%) 0.900 ms/op [Average]
  (min, avg, max) = (3.533, 3.588, 3.627), stdev = 0.049
  CI (99.9%): [2.688, 4.489] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.022 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.878 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.720 ±(99.9%) 0.016 ms/op
Iteration   1: 4.636 ±(99.9%) 0.011 ms/op
Iteration   2: 4.594 ±(99.9%) 0.008 ms/op
Iteration   3: 4.514 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.582 ±(99.9%) 1.130 ms/op [Average]
  (min, avg, max) = (4.514, 4.582, 4.636), stdev = 0.062
  CI (99.9%): [3.451, 5.712] (assumes normal distribution)


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
# Warmup Iteration   1: 5.399 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.624 ±(99.9%) 0.008 ms/op
Iteration   1: 3.651 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  9.181 ms/op
                 createUser·p0.9999: 15.962 ms/op
                 createUser·p1.00:   16.286 ms/op

Iteration   2: 3.565 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   3.527 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  9.555 ms/op
                 createUser·p0.9999: 15.828 ms/op
                 createUser·p1.00:   18.055 ms/op

Iteration   3: 3.637 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.867 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  16.843 ms/op
                 createUser·p0.9999: 24.327 ms/op
                 createUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265522
  mean =      3.617 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5307 
    [ 2.500,  5.000) = 255464 
    [ 5.000,  7.500) = 4063 
    [ 7.500, 10.000) = 450 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     22.020 ms/op
     p(99.9990) =     24.577 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.012 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.007 ms/op
Iteration   1: 3.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  8.306 ms/op
                 existUser·p0.9999: 14.162 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 3.469 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  9.726 ms/op
                 existUser·p0.9999: 16.138 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   3: 3.340 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  8.121 ms/op
                 existUser·p0.9999: 35.156 ms/op
                 existUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 280902
  mean =      3.416 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11819 
    [ 2.500,  5.000) = 265792 
    [ 5.000,  7.500) = 2720 
    [ 7.500, 10.000) = 358 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.145 ms/op
     p(99.9000) =      8.636 ms/op
     p(99.9900) =     33.120 ms/op
     p(99.9990) =     35.336 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


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
# Warmup Iteration   1: 5.550 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.008 ms/op
Iteration   1: 3.601 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.555 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  9.045 ms/op
                 getUser·p0.9999: 15.849 ms/op
                 getUser·p1.00:   16.286 ms/op

Iteration   2: 3.580 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  8.049 ms/op
                 getUser·p0.9999: 15.516 ms/op
                 getUser·p1.00:   16.155 ms/op

Iteration   3: 3.549 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  11.369 ms/op
                 getUser·p0.9999: 19.169 ms/op
                 getUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 268530
  mean =      3.576 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12267 
    [ 2.500,  5.000) = 249352 
    [ 5.000,  7.500) = 6364 
    [ 7.500, 10.000) = 328 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =      8.888 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 6.233 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.080 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.639 ±(99.9%) 0.013 ms/op
Iteration   1: 4.629 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.520 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.784 ms/op
                 listUser·p0.95:   6.746 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  13.876 ms/op
                 listUser·p0.9999: 18.124 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   2: 4.642 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.620 ms/op
                 listUser·p0.95:   6.537 ms/op
                 listUser·p0.99:   8.287 ms/op
                 listUser·p0.999:  16.518 ms/op
                 listUser·p0.9999: 18.377 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 4.812 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.136 ms/op
                 listUser·p0.95:   6.963 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  19.144 ms/op
                 listUser·p0.9999: 32.005 ms/op
                 listUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204366
  mean =      4.693 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 338 
    [ 2.500,  5.000) = 157993 
    [ 5.000,  7.500) = 41000 
    [ 7.500, 10.000) = 4346 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.890 ms/op
     p(95.0000) =      6.767 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     16.531 ms/op
     p(99.9900) =     31.199 ms/op
     p(99.9990) =     32.275 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.545 ± 0.471  ops/ms
ClientGrpc.existUser                       thrpt       3   9.166 ± 2.405  ops/ms
ClientGrpc.getUser                         thrpt       3   8.727 ± 0.796  ops/ms
ClientGrpc.listUser                        thrpt       3   6.835 ± 1.379  ops/ms
ClientGrpc.createUser                       avgt       3   3.733 ± 1.793   ms/op
ClientGrpc.existUser                        avgt       3   3.482 ± 0.570   ms/op
ClientGrpc.getUser                          avgt       3   3.588 ± 0.900   ms/op
ClientGrpc.listUser                         avgt       3   4.582 ± 1.130   ms/op
ClientGrpc.createUser                     sample  265522   3.617 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.867           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.227           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.521           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.634           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.020           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.740           ms/op
ClientGrpc.existUser                      sample  280902   3.416 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.768           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.949           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.145           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.636           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.120           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.455           ms/op
ClientGrpc.getUser                        sample  268530   3.576 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.835           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.734           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.888           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.071           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.201           ms/op
ClientGrpc.listUser                       sample  204366   4.693 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.284           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.481           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.389           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.531           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.199           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.342           ms/op
