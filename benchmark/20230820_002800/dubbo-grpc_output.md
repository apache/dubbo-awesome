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
# Warmup Iteration   1: 3.080 ops/ms
# Warmup Iteration   2: 7.163 ops/ms
# Warmup Iteration   3: 8.293 ops/ms
Iteration   1: 8.596 ops/ms
Iteration   2: 8.764 ops/ms
Iteration   3: 8.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.658 ±(99.9%) 1.671 ops/ms [Average]
  (min, avg, max) = (8.596, 8.658, 8.764), stdev = 0.092
  CI (99.9%): [6.987, 10.330] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.130 ops/ms
# Warmup Iteration   2: 8.762 ops/ms
# Warmup Iteration   3: 9.164 ops/ms
Iteration   1: 9.271 ops/ms
Iteration   2: 9.180 ops/ms
Iteration   3: 9.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.181 ±(99.9%) 1.611 ops/ms [Average]
  (min, avg, max) = (9.094, 9.181, 9.271), stdev = 0.088
  CI (99.9%): [7.570, 10.793] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.531 ops/ms
# Warmup Iteration   2: 8.042 ops/ms
# Warmup Iteration   3: 8.613 ops/ms
Iteration   1: 8.834 ops/ms
Iteration   2: 8.882 ops/ms
Iteration   3: 8.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.858 ±(99.9%) 0.431 ops/ms [Average]
  (min, avg, max) = (8.834, 8.858, 8.882), stdev = 0.024
  CI (99.9%): [8.428, 9.289] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.463 ops/ms
# Warmup Iteration   2: 6.514 ops/ms
# Warmup Iteration   3: 6.554 ops/ms
Iteration   1: 6.808 ops/ms
Iteration   2: 6.777 ops/ms
Iteration   3: 6.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.756 ±(99.9%) 1.186 ops/ms [Average]
  (min, avg, max) = (6.683, 6.756, 6.808), stdev = 0.065
  CI (99.9%): [5.571, 7.942] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.545 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.736 ±(99.9%) 0.004 ms/op
Iteration   1: 3.725 ±(99.9%) 0.002 ms/op
Iteration   2: 3.705 ±(99.9%) 0.002 ms/op
Iteration   3: 3.708 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.713 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (3.705, 3.713, 3.725), stdev = 0.011
  CI (99.9%): [3.518, 3.907] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.014 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.738 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.005 ms/op
Iteration   1: 3.511 ±(99.9%) 0.003 ms/op
Iteration   2: 3.550 ±(99.9%) 0.002 ms/op
Iteration   3: 3.349 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.470 ±(99.9%) 1.944 ms/op [Average]
  (min, avg, max) = (3.349, 3.470, 3.550), stdev = 0.107
  CI (99.9%): [1.526, 5.414] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.286 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.004 ms/op
Iteration   1: 3.735 ±(99.9%) 0.003 ms/op
Iteration   2: 3.666 ±(99.9%) 0.003 ms/op
Iteration   3: 3.738 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.713 ±(99.9%) 0.743 ms/op [Average]
  (min, avg, max) = (3.666, 3.713, 3.738), stdev = 0.041
  CI (99.9%): [2.970, 4.456] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.892 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.987 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.837 ±(99.9%) 0.015 ms/op
Iteration   1: 4.824 ±(99.9%) 0.013 ms/op
Iteration   2: 4.823 ±(99.9%) 0.013 ms/op
Iteration   3: 4.954 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.867 ±(99.9%) 1.371 ms/op [Average]
  (min, avg, max) = (4.823, 4.867, 4.954), stdev = 0.075
  CI (99.9%): [3.496, 6.238] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.527 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.714 ±(99.9%) 0.010 ms/op
Iteration   1: 3.634 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   5.754 ms/op
                 createUser·p0.999:  9.552 ms/op
                 createUser·p0.9999: 25.932 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   2: 3.731 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  11.933 ms/op
                 createUser·p0.9999: 24.183 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 3.642 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.581 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  21.387 ms/op
                 createUser·p0.9999: 27.572 ms/op
                 createUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261799
  mean =      3.668 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10739 
    [ 2.500,  5.000) = 242754 
    [ 5.000,  7.500) = 7258 
    [ 7.500, 10.000) = 580 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     12.291 ms/op
     p(99.9900) =     27.060 ms/op
     p(99.9990) =     27.845 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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
# Warmup Iteration   1: 5.200 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.009 ms/op
Iteration   1: 3.624 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.707 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   6.804 ms/op
                 existUser·p0.999:  12.169 ms/op
                 existUser·p0.9999: 20.193 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   2: 3.504 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   3.465 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  10.622 ms/op
                 existUser·p0.9999: 16.838 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   3: 3.631 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   6.966 ms/op
                 existUser·p0.999:  13.147 ms/op
                 existUser·p0.9999: 19.903 ms/op
                 existUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267662
  mean =      3.586 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11779 
    [ 2.500,  5.000) = 247282 
    [ 5.000,  7.500) = 6726 
    [ 7.500, 10.000) = 1452 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.802 ms/op
     p(99.9000) =     11.272 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     21.240 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 5.520 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.663 ±(99.9%) 0.008 ms/op
Iteration   1: 3.744 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  12.409 ms/op
                 getUser·p0.9999: 16.938 ms/op
                 getUser·p1.00:   17.498 ms/op

Iteration   2: 3.656 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  8.471 ms/op
                 getUser·p0.9999: 17.408 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   3: 3.644 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.377 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.491 ms/op
                 getUser·p0.999:  11.595 ms/op
                 getUser·p0.9999: 28.515 ms/op
                 getUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260860
  mean =      3.681 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11514 
    [ 2.500,  5.000) = 241489 
    [ 5.000,  7.500) = 6636 
    [ 7.500, 10.000) = 886 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.377 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     11.045 ms/op
     p(99.9900) =     28.017 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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
# Warmup Iteration   1: 6.700 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.984 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.852 ±(99.9%) 0.015 ms/op
Iteration   1: 4.729 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.915 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   8.549 ms/op
                 listUser·p0.999:  16.538 ms/op
                 listUser·p0.9999: 22.086 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   2: 4.760 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.453 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.201 ms/op
                 listUser·p0.95:   7.135 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  16.245 ms/op
                 listUser·p0.9999: 24.154 ms/op
                 listUser·p1.00:   24.936 ms/op

Iteration   3: 4.776 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.816 ms/op
                 listUser·p0.95:   6.767 ms/op
                 listUser·p0.99:   8.859 ms/op
                 listUser·p0.999:  19.562 ms/op
                 listUser·p0.9999: 34.295 ms/op
                 listUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201817
  mean =      4.755 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 458 
    [ 2.500,  5.000) = 152846 
    [ 5.000,  7.500) = 42347 
    [ 7.500, 10.000) = 5214 
    [10.000, 12.500) = 487 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.988 ms/op
     p(95.0000) =      6.963 ms/op
     p(99.0000) =      8.730 ms/op
     p(99.9000) =     18.127 ms/op
     p(99.9900) =     32.467 ms/op
     p(99.9990) =     34.733 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.658 ± 1.671  ops/ms
ClientGrpc.existUser                       thrpt       3   9.181 ± 1.611  ops/ms
ClientGrpc.getUser                         thrpt       3   8.858 ± 0.431  ops/ms
ClientGrpc.listUser                        thrpt       3   6.756 ± 1.186  ops/ms
ClientGrpc.createUser                       avgt       3   3.713 ± 0.194   ms/op
ClientGrpc.existUser                        avgt       3   3.470 ± 1.944   ms/op
ClientGrpc.getUser                          avgt       3   3.713 ± 0.743   ms/op
ClientGrpc.listUser                         avgt       3   4.867 ± 1.371   ms/op
ClientGrpc.createUser                     sample  261799   3.668 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.581           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.087           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.291           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.060           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.984           ms/op
ClientGrpc.existUser                      sample  267662   3.586 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.707           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.669           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.802           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.272           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.628           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.848           ms/op
ClientGrpc.getUser                        sample  260860   3.681 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.377           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.735           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.177           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.045           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.017           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.869           ms/op
ClientGrpc.listUser                       sample  201817   4.755 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.453           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.547           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.988           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.730           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.127           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.467           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.734           ms/op
