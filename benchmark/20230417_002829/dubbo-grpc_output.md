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
# Warmup Iteration   1: 3.472 ops/ms
# Warmup Iteration   2: 7.369 ops/ms
# Warmup Iteration   3: 8.660 ops/ms
Iteration   1: 8.833 ops/ms
Iteration   2: 8.952 ops/ms
Iteration   3: 9.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.997 ±(99.9%) 3.468 ops/ms [Average]
  (min, avg, max) = (8.833, 8.997, 9.206), stdev = 0.190
  CI (99.9%): [5.529, 12.465] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.415 ops/ms
# Warmup Iteration   2: 8.963 ops/ms
# Warmup Iteration   3: 9.783 ops/ms
Iteration   1: 9.787 ops/ms
Iteration   2: 9.551 ops/ms
Iteration   3: 9.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.646 ±(99.9%) 2.276 ops/ms [Average]
  (min, avg, max) = (9.551, 9.646, 9.787), stdev = 0.125
  CI (99.9%): [7.370, 11.923] (assumes normal distribution)


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
# Warmup Iteration   1: 5.832 ops/ms
# Warmup Iteration   2: 8.464 ops/ms
# Warmup Iteration   3: 8.823 ops/ms
Iteration   1: 8.926 ops/ms
Iteration   2: 8.917 ops/ms
Iteration   3: 9.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.994 ±(99.9%) 2.299 ops/ms [Average]
  (min, avg, max) = (8.917, 8.994, 9.140), stdev = 0.126
  CI (99.9%): [6.696, 11.293] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.674 ops/ms
# Warmup Iteration   2: 6.586 ops/ms
# Warmup Iteration   3: 6.762 ops/ms
Iteration   1: 6.821 ops/ms
Iteration   2: 7.004 ops/ms
Iteration   3: 6.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.914 ±(99.9%) 1.671 ops/ms [Average]
  (min, avg, max) = (6.821, 6.914, 7.004), stdev = 0.092
  CI (99.9%): [5.243, 8.585] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.946 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.624 ±(99.9%) 0.003 ms/op
Iteration   1: 3.539 ±(99.9%) 0.004 ms/op
Iteration   2: 3.530 ±(99.9%) 0.004 ms/op
Iteration   3: 3.540 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.536 ±(99.9%) 0.103 ms/op [Average]
  (min, avg, max) = (3.530, 3.536, 3.540), stdev = 0.006
  CI (99.9%): [3.434, 3.639] (assumes normal distribution)


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
# Warmup Iteration   1: 4.822 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.472 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.003 ms/op
Iteration   1: 3.388 ±(99.9%) 0.004 ms/op
Iteration   2: 3.403 ±(99.9%) 0.004 ms/op
Iteration   3: 3.375 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.389 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (3.375, 3.389, 3.403), stdev = 0.014
  CI (99.9%): [3.131, 3.646] (assumes normal distribution)


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
# Warmup Iteration   1: 5.113 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.005 ms/op
Iteration   1: 3.605 ±(99.9%) 0.004 ms/op
Iteration   2: 3.547 ±(99.9%) 0.006 ms/op
Iteration   3: 3.543 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.565 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (3.543, 3.565, 3.605), stdev = 0.034
  CI (99.9%): [2.940, 4.190] (assumes normal distribution)


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
# Warmup Iteration   1: 6.349 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.024 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.679 ±(99.9%) 0.014 ms/op
Iteration   1: 4.634 ±(99.9%) 0.011 ms/op
Iteration   2: 4.617 ±(99.9%) 0.010 ms/op
Iteration   3: 4.497 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.583 ±(99.9%) 1.361 ms/op [Average]
  (min, avg, max) = (4.497, 4.583, 4.634), stdev = 0.075
  CI (99.9%): [3.222, 5.944] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.312 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.008 ms/op
Iteration   1: 3.557 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  9.559 ms/op
                 createUser·p0.9999: 14.500 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   2: 3.524 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  7.594 ms/op
                 createUser·p0.9999: 15.745 ms/op
                 createUser·p1.00:   16.253 ms/op

Iteration   3: 3.587 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  16.472 ms/op
                 createUser·p0.9999: 20.944 ms/op
                 createUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 270023
  mean =      3.556 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7492 
    [ 2.500,  5.000) = 258119 
    [ 5.000,  7.500) = 3829 
    [ 7.500, 10.000) = 317 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =      9.911 ms/op
     p(99.9900) =     18.776 ms/op
     p(99.9990) =     21.352 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 4.747 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.006 ms/op
Iteration   1: 3.332 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  8.004 ms/op
                 existUser·p0.9999: 17.590 ms/op
                 existUser·p1.00:   19.464 ms/op

Iteration   2: 3.323 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  7.274 ms/op
                 existUser·p0.9999: 21.627 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   3: 3.412 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  9.470 ms/op
                 existUser·p0.9999: 20.152 ms/op
                 existUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 285976
  mean =      3.355 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9943 
    [ 2.500,  5.000) = 272941 
    [ 5.000,  7.500) = 2803 
    [ 7.500, 10.000) = 113 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.081 ms/op
     p(99.9000) =      7.545 ms/op
     p(99.9900) =     21.194 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 5.433 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.696 ±(99.9%) 0.010 ms/op
Iteration   1: 3.564 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  10.617 ms/op
                 getUser·p0.9999: 14.254 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 3.563 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.518 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  10.502 ms/op
                 getUser·p0.9999: 16.975 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   3: 3.601 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  8.365 ms/op
                 getUser·p0.9999: 17.302 ms/op
                 getUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 268434
  mean =      3.576 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 184 
    [ 1.250,  2.500) = 7427 
    [ 2.500,  3.750) = 177856 
    [ 3.750,  5.000) = 77449 
    [ 5.000,  6.250) = 4085 
    [ 6.250,  7.500) = 727 
    [ 7.500,  8.750) = 301 
    [ 8.750, 10.000) = 116 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     10.207 ms/op
     p(99.9900) =     16.637 ms/op
     p(99.9990) =     18.983 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 6.615 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.057 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.628 ±(99.9%) 0.013 ms/op
Iteration   1: 4.684 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.718 ms/op
                 listUser·p0.95:   6.537 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  15.610 ms/op
                 listUser·p0.9999: 18.558 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   2: 4.661 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.759 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.595 ms/op
                 listUser·p0.99:   8.102 ms/op
                 listUser·p0.999:  17.707 ms/op
                 listUser·p0.9999: 28.251 ms/op
                 listUser·p1.00:   29.524 ms/op

Iteration   3: 4.693 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.407 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.784 ms/op
                 listUser·p0.95:   6.455 ms/op
                 listUser·p0.99:   8.167 ms/op
                 listUser·p0.999:  17.330 ms/op
                 listUser·p0.9999: 20.814 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 205014
  mean =      4.679 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 251 
    [ 2.500,  5.000) = 162154 
    [ 5.000,  7.500) = 38321 
    [ 7.500, 10.000) = 3686 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.669 ms/op
     p(95.0000) =      6.521 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     27.869 ms/op
     p(99.9990) =     28.372 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.997 ± 3.468  ops/ms
ClientGrpc.existUser                       thrpt       3   9.646 ± 2.276  ops/ms
ClientGrpc.getUser                         thrpt       3   8.994 ± 2.299  ops/ms
ClientGrpc.listUser                        thrpt       3   6.914 ± 1.671  ops/ms
ClientGrpc.createUser                       avgt       3   3.536 ± 0.103   ms/op
ClientGrpc.existUser                        avgt       3   3.389 ± 0.258   ms/op
ClientGrpc.getUser                          avgt       3   3.565 ± 0.625   ms/op
ClientGrpc.listUser                         avgt       3   4.583 ± 1.361   ms/op
ClientGrpc.createUser                     sample  270023   3.556 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.728           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.190           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.423           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.911           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.776           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.496           ms/op
ClientGrpc.existUser                      sample  285976   3.355 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.891           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.834           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.092           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.081           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.545           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.194           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.791           ms/op
ClientGrpc.getUser                        sample  268434   3.576 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.723           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.595           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.207           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.637           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.071           ms/op
ClientGrpc.listUser                       sample  205014   4.679 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.407           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.514           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.521           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.135           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.777           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.869           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.524           ms/op
