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
# Warmup Iteration   1: 3.206 ops/ms
# Warmup Iteration   2: 6.246 ops/ms
# Warmup Iteration   3: 7.833 ops/ms
Iteration   1: 8.682 ops/ms
Iteration   2: 8.780 ops/ms
Iteration   3: 8.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.769 ±(99.9%) 1.495 ops/ms [Average]
  (min, avg, max) = (8.682, 8.769, 8.845), stdev = 0.082
  CI (99.9%): [7.274, 10.264] (assumes normal distribution)


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
# Warmup Iteration   1: 6.147 ops/ms
# Warmup Iteration   2: 8.618 ops/ms
# Warmup Iteration   3: 8.984 ops/ms
Iteration   1: 9.006 ops/ms
Iteration   2: 9.219 ops/ms
Iteration   3: 9.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.123 ±(99.9%) 1.973 ops/ms [Average]
  (min, avg, max) = (9.006, 9.123, 9.219), stdev = 0.108
  CI (99.9%): [7.150, 11.096] (assumes normal distribution)


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
# Warmup Iteration   1: 5.881 ops/ms
# Warmup Iteration   2: 8.064 ops/ms
# Warmup Iteration   3: 8.507 ops/ms
Iteration   1: 8.721 ops/ms
Iteration   2: 8.595 ops/ms
Iteration   3: 8.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.670 ±(99.9%) 1.202 ops/ms [Average]
  (min, avg, max) = (8.595, 8.670, 8.721), stdev = 0.066
  CI (99.9%): [7.468, 9.872] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.123 ops/ms
# Warmup Iteration   2: 6.255 ops/ms
# Warmup Iteration   3: 6.742 ops/ms
Iteration   1: 6.634 ops/ms
Iteration   2: 6.728 ops/ms
Iteration   3: 6.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.725 ±(99.9%) 1.645 ops/ms [Average]
  (min, avg, max) = (6.634, 6.725, 6.814), stdev = 0.090
  CI (99.9%): [5.080, 8.370] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.573 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.004 ms/op
Iteration   1: 3.655 ±(99.9%) 0.004 ms/op
Iteration   2: 3.678 ±(99.9%) 0.003 ms/op
Iteration   3: 3.574 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.636 ±(99.9%) 0.997 ms/op [Average]
  (min, avg, max) = (3.574, 3.636, 3.678), stdev = 0.055
  CI (99.9%): [2.639, 4.633] (assumes normal distribution)


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
# Warmup Iteration   1: 4.956 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.004 ms/op
Iteration   1: 3.487 ±(99.9%) 0.002 ms/op
Iteration   2: 3.545 ±(99.9%) 0.003 ms/op
Iteration   3: 3.599 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.544 ±(99.9%) 1.020 ms/op [Average]
  (min, avg, max) = (3.487, 3.544, 3.599), stdev = 0.056
  CI (99.9%): [2.524, 4.563] (assumes normal distribution)


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
# Warmup Iteration   1: 5.108 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.852 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.003 ms/op
Iteration   1: 3.732 ±(99.9%) 0.004 ms/op
Iteration   2: 3.702 ±(99.9%) 0.003 ms/op
Iteration   3: 3.746 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.727 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (3.702, 3.727, 3.746), stdev = 0.022
  CI (99.9%): [3.316, 4.137] (assumes normal distribution)


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
# Warmup Iteration   1: 6.766 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.011 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.775 ±(99.9%) 0.016 ms/op
Iteration   1: 4.732 ±(99.9%) 0.018 ms/op
Iteration   2: 4.858 ±(99.9%) 0.014 ms/op
Iteration   3: 4.855 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.815 ±(99.9%) 1.311 ms/op [Average]
  (min, avg, max) = (4.732, 4.815, 4.858), stdev = 0.072
  CI (99.9%): [3.504, 6.126] (assumes normal distribution)


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
# Warmup Iteration   1: 5.479 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.009 ms/op
Iteration   1: 3.711 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  10.776 ms/op
                 createUser·p0.9999: 14.175 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   2: 3.712 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  10.940 ms/op
                 createUser·p0.9999: 21.487 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   3: 3.757 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  13.861 ms/op
                 createUser·p0.9999: 20.889 ms/op
                 createUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 257603
  mean =      3.727 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6502 
    [ 2.500,  5.000) = 243666 
    [ 5.000,  7.500) = 6530 
    [ 7.500, 10.000) = 505 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     12.029 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 5.186 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.009 ms/op
Iteration   1: 3.522 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.448 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  10.489 ms/op
                 existUser·p0.9999: 17.039 ms/op
                 existUser·p1.00:   17.465 ms/op

Iteration   2: 3.571 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  9.508 ms/op
                 existUser·p0.9999: 16.813 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   3: 3.508 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   3.457 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  11.872 ms/op
                 existUser·p0.9999: 18.047 ms/op
                 existUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271561
  mean =      3.533 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7891 
    [ 2.500,  5.000) = 258140 
    [ 5.000,  7.500) = 4729 
    [ 7.500, 10.000) = 435 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.448 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     11.043 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     19.942 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 5.451 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.008 ms/op
Iteration   1: 3.626 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  11.349 ms/op
                 getUser·p0.9999: 14.912 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   2: 3.649 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.497 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  9.318 ms/op
                 getUser·p0.9999: 14.011 ms/op
                 getUser·p1.00:   15.073 ms/op

Iteration   3: 3.654 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  11.376 ms/op
                 getUser·p0.9999: 29.597 ms/op
                 getUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263596
  mean =      3.643 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6518 
    [ 2.500,  5.000) = 250581 
    [ 5.000,  7.500) = 5679 
    [ 7.500, 10.000) = 447 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     10.846 ms/op
     p(99.9900) =     26.813 ms/op
     p(99.9990) =     29.887 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 6.146 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.013 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.904 ±(99.9%) 0.015 ms/op
Iteration   1: 4.792 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   6.791 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  16.394 ms/op
                 listUser·p0.9999: 24.718 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   2: 4.845 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.062 ms/op
                 listUser·p0.95:   6.783 ms/op
                 listUser·p0.99:   8.323 ms/op
                 listUser·p0.999:  17.065 ms/op
                 listUser·p0.9999: 19.162 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   3: 4.864 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.038 ms/op
                 listUser·p0.95:   7.012 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  19.994 ms/op
                 listUser·p0.9999: 24.210 ms/op
                 listUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198646
  mean =      4.833 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 360 
    [ 2.500,  5.000) = 144075 
    [ 5.000,  7.500) = 48634 
    [ 7.500, 10.000) = 4842 
    [10.000, 12.500) = 423 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      5.997 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     17.215 ms/op
     p(99.9900) =     24.290 ms/op
     p(99.9990) =     25.789 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.769 ± 1.495  ops/ms
ClientGrpc.existUser                       thrpt       3   9.123 ± 1.973  ops/ms
ClientGrpc.getUser                         thrpt       3   8.670 ± 1.202  ops/ms
ClientGrpc.listUser                        thrpt       3   6.725 ± 1.645  ops/ms
ClientGrpc.createUser                       avgt       3   3.636 ± 0.997   ms/op
ClientGrpc.existUser                        avgt       3   3.544 ± 1.020   ms/op
ClientGrpc.getUser                          avgt       3   3.727 ± 0.410   ms/op
ClientGrpc.listUser                         avgt       3   4.815 ± 1.311   ms/op
ClientGrpc.createUser                     sample  257603   3.727 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.737           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.735           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.939           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.029           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.004           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.003           ms/op
ClientGrpc.existUser                      sample  271561   3.533 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.448           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.141           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.685           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.043           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.793           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.054           ms/op
ClientGrpc.getUser                        sample  263596   3.643 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.497           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.800           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.846           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.813           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.950           ms/op
ClientGrpc.listUser                       sample  198646   4.833 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.190           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.645           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.552           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.215           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.290           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.854           ms/op
