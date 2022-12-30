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
# Warmup Iteration   1: 3.283 ops/ms
# Warmup Iteration   2: 7.047 ops/ms
# Warmup Iteration   3: 8.363 ops/ms
Iteration   1: 8.592 ops/ms
Iteration   2: 8.722 ops/ms
Iteration   3: 8.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.670 ±(99.9%) 1.254 ops/ms [Average]
  (min, avg, max) = (8.592, 8.670, 8.722), stdev = 0.069
  CI (99.9%): [7.416, 9.925] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.155 ops/ms
# Warmup Iteration   2: 8.556 ops/ms
# Warmup Iteration   3: 9.247 ops/ms
Iteration   1: 8.781 ops/ms
Iteration   2: 8.950 ops/ms
Iteration   3: 8.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.858 ±(99.9%) 1.557 ops/ms [Average]
  (min, avg, max) = (8.781, 8.858, 8.950), stdev = 0.085
  CI (99.9%): [7.301, 10.414] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.559 ops/ms
# Warmup Iteration   2: 8.406 ops/ms
# Warmup Iteration   3: 8.324 ops/ms
Iteration   1: 8.766 ops/ms
Iteration   2: 8.762 ops/ms
Iteration   3: 8.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.675 ±(99.9%) 2.826 ops/ms [Average]
  (min, avg, max) = (8.496, 8.675, 8.766), stdev = 0.155
  CI (99.9%): [5.848, 11.501] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.495 ops/ms
# Warmup Iteration   2: 6.659 ops/ms
# Warmup Iteration   3: 7.004 ops/ms
Iteration   1: 7.159 ops/ms
Iteration   2: 7.165 ops/ms
Iteration   3: 7.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.135 ±(99.9%) 0.854 ops/ms [Average]
  (min, avg, max) = (7.081, 7.135, 7.165), stdev = 0.047
  CI (99.9%): [6.281, 7.989] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.109 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.603 ±(99.9%) 0.005 ms/op
Iteration   1: 3.637 ±(99.9%) 0.005 ms/op
Iteration   2: 3.690 ±(99.9%) 0.003 ms/op
Iteration   3: 3.745 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.691 ±(99.9%) 0.983 ms/op [Average]
  (min, avg, max) = (3.637, 3.691, 3.745), stdev = 0.054
  CI (99.9%): [2.707, 4.674] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.978 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.592 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.003 ms/op
Iteration   1: 3.506 ±(99.9%) 0.003 ms/op
Iteration   2: 3.469 ±(99.9%) 0.003 ms/op
Iteration   3: 3.525 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.500 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (3.469, 3.500, 3.525), stdev = 0.028
  CI (99.9%): [2.988, 4.012] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.845 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.002 ms/op
Iteration   1: 3.700 ±(99.9%) 0.003 ms/op
Iteration   2: 3.732 ±(99.9%) 0.003 ms/op
Iteration   3: 3.653 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.695 ±(99.9%) 0.731 ms/op [Average]
  (min, avg, max) = (3.653, 3.695, 3.732), stdev = 0.040
  CI (99.9%): [2.964, 4.426] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.079 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.741 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.678 ±(99.9%) 0.032 ms/op
Iteration   1: 4.465 ±(99.9%) 0.014 ms/op
Iteration   2: 4.469 ±(99.9%) 0.021 ms/op
Iteration   3: 4.484 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.473 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (4.465, 4.473, 4.484), stdev = 0.010
  CI (99.9%): [4.292, 4.654] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.048 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.762 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.679 ±(99.9%) 0.008 ms/op
Iteration   1: 3.733 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  14.129 ms/op
                 createUser·p0.9999: 16.529 ms/op
                 createUser·p1.00:   16.761 ms/op

Iteration   2: 3.703 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  10.584 ms/op
                 createUser·p0.9999: 14.676 ms/op
                 createUser·p1.00:   16.007 ms/op

Iteration   3: 3.456 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   3.463 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  15.391 ms/op
                 createUser·p0.9999: 19.488 ms/op
                 createUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264575
  mean =      3.626 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 612 
    [ 1.250,  2.500) = 9743 
    [ 2.500,  3.750) = 150883 
    [ 3.750,  5.000) = 98184 
    [ 5.000,  6.250) = 4137 
    [ 6.250,  7.500) = 401 
    [ 7.500,  8.750) = 183 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 77 
    [15.000, 16.250) = 58 
    [16.250, 17.500) = 50 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     12.154 ms/op
     p(99.9900) =     17.811 ms/op
     p(99.9990) =     19.750 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.549 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.611 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.007 ms/op
Iteration   1: 3.441 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  9.048 ms/op
                 existUser·p0.9999: 15.101 ms/op
                 existUser·p1.00:   16.712 ms/op

Iteration   2: 3.518 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  11.750 ms/op
                 existUser·p0.9999: 15.416 ms/op
                 existUser·p1.00:   15.876 ms/op

Iteration   3: 3.472 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   3.465 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  9.779 ms/op
                 existUser·p0.9999: 27.551 ms/op
                 existUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275959
  mean =      3.477 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13648 
    [ 2.500,  5.000) = 258872 
    [ 5.000,  7.500) = 2904 
    [ 7.500, 10.000) = 201 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =     10.813 ms/op
     p(99.9900) =     25.526 ms/op
     p(99.9990) =     27.901 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.219 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.007 ms/op
Iteration   1: 3.581 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.153 ms/op
                 getUser·p0.999:  8.463 ms/op
                 getUser·p0.9999: 16.633 ms/op
                 getUser·p1.00:   16.974 ms/op

Iteration   2: 3.631 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.095 ms/op
                 getUser·p0.999:  7.504 ms/op
                 getUser·p0.9999: 16.505 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   3: 3.653 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   5.276 ms/op
                 getUser·p0.999:  10.255 ms/op
                 getUser·p0.9999: 19.341 ms/op
                 getUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 264950
  mean =      3.622 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8087 
    [ 2.500,  5.000) = 252740 
    [ 5.000,  7.500) = 3700 
    [ 7.500, 10.000) = 238 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.898 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.733 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.506 ±(99.9%) 0.013 ms/op
Iteration   1: 4.472 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   5.693 ms/op
                 listUser·p0.95:   6.426 ms/op
                 listUser·p0.99:   7.905 ms/op
                 listUser·p0.999:  14.048 ms/op
                 listUser·p0.9999: 22.993 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   2: 4.581 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   6.398 ms/op
                 listUser·p0.99:   7.886 ms/op
                 listUser·p0.999:  16.651 ms/op
                 listUser·p0.9999: 24.741 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   3: 4.539 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   6.595 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  20.156 ms/op
                 listUser·p0.9999: 27.327 ms/op
                 listUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 211807
  mean =      4.530 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 698 
    [ 2.500,  5.000) = 172161 
    [ 5.000,  7.500) = 35766 
    [ 7.500, 10.000) = 2582 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.792 ms/op
     p(95.0000) =      6.472 ms/op
     p(99.0000) =      7.873 ms/op
     p(99.9000) =     17.373 ms/op
     p(99.9900) =     26.077 ms/op
     p(99.9990) =     27.874 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.670 ± 1.254  ops/ms
ClientGrpc.existUser                       thrpt       3   8.858 ± 1.557  ops/ms
ClientGrpc.getUser                         thrpt       3   8.675 ± 2.826  ops/ms
ClientGrpc.listUser                        thrpt       3   7.135 ± 0.854  ops/ms
ClientGrpc.createUser                       avgt       3   3.691 ± 0.983   ms/op
ClientGrpc.existUser                        avgt       3   3.500 ± 0.512   ms/op
ClientGrpc.getUser                          avgt       3   3.695 ± 0.731   ms/op
ClientGrpc.listUser                         avgt       3   4.473 ± 0.181   ms/op
ClientGrpc.createUser                     sample  264575   3.626 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.734           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.308           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.154           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.811           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.857           ms/op
ClientGrpc.existUser                      sample  275959   3.477 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.876           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.169           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.813           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.526           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.049           ms/op
ClientGrpc.getUser                        sample  264950   3.622 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.717           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.169           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.126           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.350           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.004           ms/op
ClientGrpc.listUser                       sample  211807   4.530 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.880           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.342           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.373           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.077           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.951           ms/op
