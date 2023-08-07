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
# Warmup Iteration   1: 3.231 ops/ms
# Warmup Iteration   2: 6.420 ops/ms
# Warmup Iteration   3: 7.923 ops/ms
Iteration   1: 8.530 ops/ms
Iteration   2: 8.221 ops/ms
Iteration   3: 8.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.444 ±(99.9%) 3.544 ops/ms [Average]
  (min, avg, max) = (8.221, 8.444, 8.579), stdev = 0.194
  CI (99.9%): [4.900, 11.987] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.943 ops/ms
# Warmup Iteration   2: 8.530 ops/ms
# Warmup Iteration   3: 8.855 ops/ms
Iteration   1: 8.869 ops/ms
Iteration   2: 9.265 ops/ms
Iteration   3: 9.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.069 ±(99.9%) 3.612 ops/ms [Average]
  (min, avg, max) = (8.869, 9.069, 9.265), stdev = 0.198
  CI (99.9%): [5.457, 12.680] (assumes normal distribution)


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
# Warmup Iteration   1: 5.745 ops/ms
# Warmup Iteration   2: 8.292 ops/ms
# Warmup Iteration   3: 8.325 ops/ms
Iteration   1: 8.345 ops/ms
Iteration   2: 8.519 ops/ms
Iteration   3: 8.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.487 ±(99.9%) 2.351 ops/ms [Average]
  (min, avg, max) = (8.345, 8.487, 8.596), stdev = 0.129
  CI (99.9%): [6.136, 10.837] (assumes normal distribution)


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
# Warmup Iteration   1: 4.542 ops/ms
# Warmup Iteration   2: 6.415 ops/ms
# Warmup Iteration   3: 6.700 ops/ms
Iteration   1: 6.630 ops/ms
Iteration   2: 6.665 ops/ms
Iteration   3: 6.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.662 ±(99.9%) 0.584 ops/ms [Average]
  (min, avg, max) = (6.630, 6.662, 6.693), stdev = 0.032
  CI (99.9%): [6.078, 7.247] (assumes normal distribution)


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
# Warmup Iteration   1: 5.648 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.838 ±(99.9%) 0.006 ms/op
Iteration   1: 3.769 ±(99.9%) 0.004 ms/op
Iteration   2: 3.794 ±(99.9%) 0.003 ms/op
Iteration   3: 3.631 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.732 ±(99.9%) 1.605 ms/op [Average]
  (min, avg, max) = (3.631, 3.732, 3.794), stdev = 0.088
  CI (99.9%): [2.127, 5.337] (assumes normal distribution)


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
# Warmup Iteration   1: 4.943 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.004 ms/op
Iteration   1: 3.516 ±(99.9%) 0.002 ms/op
Iteration   2: 3.572 ±(99.9%) 0.003 ms/op
Iteration   3: 3.628 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.572 ±(99.9%) 1.016 ms/op [Average]
  (min, avg, max) = (3.516, 3.572, 3.628), stdev = 0.056
  CI (99.9%): [2.557, 4.588] (assumes normal distribution)


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
# Warmup Iteration   1: 5.256 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.004 ms/op
Iteration   1: 3.664 ±(99.9%) 0.004 ms/op
Iteration   2: 3.672 ±(99.9%) 0.006 ms/op
Iteration   3: 3.638 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.658 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (3.638, 3.658, 3.672), stdev = 0.018
  CI (99.9%): [3.336, 3.980] (assumes normal distribution)


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
# Warmup Iteration   1: 6.893 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.017 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.892 ±(99.9%) 0.014 ms/op
Iteration   1: 4.981 ±(99.9%) 0.023 ms/op
Iteration   2: 4.765 ±(99.9%) 0.012 ms/op
Iteration   3: 4.882 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.876 ±(99.9%) 1.970 ms/op [Average]
  (min, avg, max) = (4.765, 4.876, 4.981), stdev = 0.108
  CI (99.9%): [2.906, 6.846] (assumes normal distribution)


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
# Warmup Iteration   1: 5.389 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.701 ±(99.9%) 0.010 ms/op
Iteration   1: 3.699 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  12.829 ms/op
                 createUser·p0.9999: 17.092 ms/op
                 createUser·p1.00:   19.399 ms/op

Iteration   2: 3.683 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  10.359 ms/op
                 createUser·p0.9999: 16.181 ms/op
                 createUser·p1.00:   17.891 ms/op

Iteration   3: 3.761 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.824 ms/op
                 createUser·p0.999:  16.755 ms/op
                 createUser·p0.9999: 20.478 ms/op
                 createUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258706
  mean =      3.714 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6127 
    [ 2.500,  5.000) = 243428 
    [ 5.000,  7.500) = 7603 
    [ 7.500, 10.000) = 987 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     12.534 ms/op
     p(99.9900) =     19.894 ms/op
     p(99.9990) =     20.611 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.188 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.996 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.680 ±(99.9%) 0.011 ms/op
Iteration   1: 3.590 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   7.528 ms/op
                 existUser·p0.999:  12.153 ms/op
                 existUser·p0.9999: 17.307 ms/op
                 existUser·p1.00:   20.349 ms/op

Iteration   2: 3.563 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  9.560 ms/op
                 existUser·p0.9999: 16.531 ms/op
                 existUser·p1.00:   16.712 ms/op

Iteration   3: 3.501 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   3.473 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   6.476 ms/op
                 existUser·p0.999:  11.326 ms/op
                 existUser·p0.9999: 22.802 ms/op
                 existUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270315
  mean =      3.551 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15892 
    [ 2.500,  5.000) = 245723 
    [ 5.000,  7.500) = 7019 
    [ 7.500, 10.000) = 1255 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.618 ms/op
     p(99.9000) =     10.945 ms/op
     p(99.9900) =     22.247 ms/op
     p(99.9990) =     23.023 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 5.106 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.696 ±(99.9%) 0.009 ms/op
Iteration   1: 3.725 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.625 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  12.438 ms/op
                 getUser·p0.9999: 18.855 ms/op
                 getUser·p1.00:   19.202 ms/op

Iteration   2: 3.639 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  9.470 ms/op
                 getUser·p0.9999: 20.061 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   3: 3.588 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.779 ms/op
                 getUser·p0.50:   3.527 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  15.555 ms/op
                 getUser·p0.9999: 29.430 ms/op
                 getUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263095
  mean =      3.649 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8422 
    [ 2.500,  5.000) = 246713 
    [ 5.000,  7.500) = 6694 
    [ 7.500, 10.000) = 904 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     11.123 ms/op
     p(99.9900) =     27.984 ms/op
     p(99.9990) =     29.855 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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
# Warmup Iteration   1: 6.750 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.068 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.892 ±(99.9%) 0.017 ms/op
Iteration   1: 4.873 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.578 ms/op
                 listUser·p0.95:   7.422 ms/op
                 listUser·p0.99:   9.503 ms/op
                 listUser·p0.999:  14.850 ms/op
                 listUser·p0.9999: 19.053 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   2: 4.755 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   6.152 ms/op
                 listUser·p0.95:   7.012 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  18.473 ms/op
                 listUser·p0.9999: 34.537 ms/op
                 listUser·p1.00:   35.258 ms/op

Iteration   3: 4.657 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.849 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  19.790 ms/op
                 listUser·p0.9999: 22.393 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201567
  mean =      4.760 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 656 
    [ 2.500,  5.000) = 146860 
    [ 5.000,  7.500) = 46762 
    [ 7.500, 10.000) = 6218 
    [10.000, 12.500) = 603 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      6.234 ms/op
     p(95.0000) =      7.127 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     33.741 ms/op
     p(99.9990) =     35.193 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.444 ± 3.544  ops/ms
ClientGrpc.existUser                       thrpt       3   9.069 ± 3.612  ops/ms
ClientGrpc.getUser                         thrpt       3   8.487 ± 2.351  ops/ms
ClientGrpc.listUser                        thrpt       3   6.662 ± 0.584  ops/ms
ClientGrpc.createUser                       avgt       3   3.732 ± 1.605   ms/op
ClientGrpc.existUser                        avgt       3   3.572 ± 1.016   ms/op
ClientGrpc.getUser                          avgt       3   3.658 ± 0.322   ms/op
ClientGrpc.listUser                         avgt       3   4.876 ± 1.970   ms/op
ClientGrpc.createUser                     sample  258706   3.714 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.753           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.792           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.570           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.534           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.894           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.677           ms/op
ClientGrpc.existUser                      sample  270315   3.551 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.641           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.618           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.945           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.247           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.167           ms/op
ClientGrpc.getUser                        sample  263095   3.649 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.779           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.710           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.103           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.123           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.984           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.097           ms/op
ClientGrpc.listUser                       sample  201567   4.760 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.061           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.489           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.234           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.060           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.481           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.741           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.258           ms/op
