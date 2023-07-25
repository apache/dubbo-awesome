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
# Warmup Iteration   1: 3.349 ops/ms
# Warmup Iteration   2: 6.419 ops/ms
# Warmup Iteration   3: 7.952 ops/ms
Iteration   1: 8.320 ops/ms
Iteration   2: 8.496 ops/ms
Iteration   3: 8.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.357 ±(99.9%) 2.272 ops/ms [Average]
  (min, avg, max) = (8.256, 8.357, 8.496), stdev = 0.125
  CI (99.9%): [6.086, 10.629] (assumes normal distribution)


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
# Warmup Iteration   1: 5.834 ops/ms
# Warmup Iteration   2: 8.560 ops/ms
# Warmup Iteration   3: 8.885 ops/ms
Iteration   1: 8.971 ops/ms
Iteration   2: 9.165 ops/ms
Iteration   3: 9.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.106 ±(99.9%) 2.141 ops/ms [Average]
  (min, avg, max) = (8.971, 9.106, 9.182), stdev = 0.117
  CI (99.9%): [6.965, 11.247] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.822 ops/ms
# Warmup Iteration   2: 8.304 ops/ms
# Warmup Iteration   3: 8.524 ops/ms
Iteration   1: 8.581 ops/ms
Iteration   2: 8.837 ops/ms
Iteration   3: 8.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.675 ±(99.9%) 2.571 ops/ms [Average]
  (min, avg, max) = (8.581, 8.675, 8.837), stdev = 0.141
  CI (99.9%): [6.104, 11.247] (assumes normal distribution)


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
# Warmup Iteration   1: 4.108 ops/ms
# Warmup Iteration   2: 6.289 ops/ms
# Warmup Iteration   3: 6.770 ops/ms
Iteration   1: 6.765 ops/ms
Iteration   2: 6.779 ops/ms
Iteration   3: 6.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.787 ±(99.9%) 0.489 ops/ms [Average]
  (min, avg, max) = (6.765, 6.787, 6.817), stdev = 0.027
  CI (99.9%): [6.298, 7.276] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.738 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.958 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.006 ms/op
Iteration   1: 3.820 ±(99.9%) 0.003 ms/op
Iteration   2: 3.633 ±(99.9%) 0.003 ms/op
Iteration   3: 3.656 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.703 ±(99.9%) 1.863 ms/op [Average]
  (min, avg, max) = (3.633, 3.703, 3.820), stdev = 0.102
  CI (99.9%): [1.840, 5.566] (assumes normal distribution)


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
# Warmup Iteration   1: 4.971 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.003 ms/op
Iteration   1: 3.448 ±(99.9%) 0.002 ms/op
Iteration   2: 3.589 ±(99.9%) 0.003 ms/op
Iteration   3: 3.430 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.489 ±(99.9%) 1.585 ms/op [Average]
  (min, avg, max) = (3.430, 3.489, 3.589), stdev = 0.087
  CI (99.9%): [1.904, 5.074] (assumes normal distribution)


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
# Warmup Iteration   1: 5.579 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.723 ±(99.9%) 0.003 ms/op
Iteration   1: 3.674 ±(99.9%) 0.003 ms/op
Iteration   2: 3.712 ±(99.9%) 0.004 ms/op
Iteration   3: 3.650 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.679 ±(99.9%) 0.575 ms/op [Average]
  (min, avg, max) = (3.650, 3.679, 3.712), stdev = 0.032
  CI (99.9%): [3.103, 4.254] (assumes normal distribution)


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
# Warmup Iteration   1: 6.420 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.107 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.807 ±(99.9%) 0.020 ms/op
Iteration   1: 4.724 ±(99.9%) 0.014 ms/op
Iteration   2: 4.823 ±(99.9%) 0.015 ms/op
Iteration   3: 4.780 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.775 ±(99.9%) 0.905 ms/op [Average]
  (min, avg, max) = (4.724, 4.775, 4.823), stdev = 0.050
  CI (99.9%): [3.871, 5.680] (assumes normal distribution)


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
# Warmup Iteration   1: 5.560 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.937 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.728 ±(99.9%) 0.009 ms/op
Iteration   1: 3.651 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  10.313 ms/op
                 createUser·p0.9999: 16.703 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   2: 3.666 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  8.536 ms/op
                 createUser·p0.9999: 18.326 ms/op
                 createUser·p1.00:   18.579 ms/op

Iteration   3: 3.658 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  10.455 ms/op
                 createUser·p0.9999: 29.663 ms/op
                 createUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 262242
  mean =      3.658 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5094 
    [ 2.500,  5.000) = 251793 
    [ 5.000,  7.500) = 4610 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.597 ms/op
     p(99.9900) =     27.984 ms/op
     p(99.9990) =     29.954 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 4.771 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.657 ±(99.9%) 0.008 ms/op
Iteration   1: 3.556 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  10.125 ms/op
                 existUser·p0.9999: 19.235 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   2: 3.595 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.033 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  12.389 ms/op
                 existUser·p0.9999: 18.091 ms/op
                 existUser·p1.00:   18.579 ms/op

Iteration   3: 3.510 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  8.418 ms/op
                 existUser·p0.9999: 18.806 ms/op
                 existUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270127
  mean =      3.553 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8231 
    [ 2.500,  5.000) = 256737 
    [ 5.000,  7.500) = 4512 
    [ 7.500, 10.000) = 387 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     18.710 ms/op
     p(99.9990) =     20.457 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 5.452 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.934 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.703 ±(99.9%) 0.008 ms/op
Iteration   1: 3.705 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  11.344 ms/op
                 getUser·p0.9999: 15.611 ms/op
                 getUser·p1.00:   16.335 ms/op

Iteration   2: 3.660 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  8.847 ms/op
                 getUser·p0.9999: 15.765 ms/op
                 getUser·p1.00:   16.105 ms/op

Iteration   3: 3.626 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   4.477 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  7.896 ms/op
                 getUser·p0.9999: 30.126 ms/op
                 getUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262153
  mean =      3.663 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7516 
    [ 2.500,  5.000) = 248856 
    [ 5.000,  7.500) = 5137 
    [ 7.500, 10.000) = 444 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.107 ms/op
     p(99.9900) =     29.353 ms/op
     p(99.9990) =     30.380 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 6.760 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.272 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.797 ±(99.9%) 0.013 ms/op
Iteration   1: 4.845 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.532 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.980 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  16.409 ms/op
                 listUser·p0.9999: 19.810 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   2: 4.817 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   6.013 ms/op
                 listUser·p0.95:   6.906 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  16.433 ms/op
                 listUser·p0.9999: 20.331 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 4.666 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.505 ms/op
                 listUser·p0.95:   6.816 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  18.645 ms/op
                 listUser·p0.9999: 23.958 ms/op
                 listUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201033
  mean =      4.775 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 148 
    [ 2.500,  5.000) = 153373 
    [ 5.000,  7.500) = 42330 
    [ 7.500, 10.000) = 4595 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.882 ms/op
     p(95.0000) =      6.849 ms/op
     p(99.0000) =      8.356 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     21.820 ms/op
     p(99.9990) =     25.129 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.357 ± 2.272  ops/ms
ClientGrpc.existUser                       thrpt       3   9.106 ± 2.141  ops/ms
ClientGrpc.getUser                         thrpt       3   8.675 ± 2.571  ops/ms
ClientGrpc.listUser                        thrpt       3   6.787 ± 0.489  ops/ms
ClientGrpc.createUser                       avgt       3   3.703 ± 1.863   ms/op
ClientGrpc.existUser                        avgt       3   3.489 ± 1.585   ms/op
ClientGrpc.getUser                          avgt       3   3.679 ± 0.575   ms/op
ClientGrpc.listUser                         avgt       3   4.775 ± 0.905   ms/op
ClientGrpc.createUser                     sample  262242   3.658 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.884           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.597           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.984           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.179           ms/op
ClientGrpc.existUser                      sample  270127   3.553 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.868           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.521           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.748           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.710           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.546           ms/op
ClientGrpc.getUser                        sample  262153   3.663 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.909           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.693           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.107           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.353           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.671           ms/op
ClientGrpc.listUser                       sample  201033   4.775 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.491           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.356           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.072           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.820           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.166           ms/op
