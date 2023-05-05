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
# Warmup Iteration   1: 3.199 ops/ms
# Warmup Iteration   2: 6.872 ops/ms
# Warmup Iteration   3: 7.682 ops/ms
Iteration   1: 8.030 ops/ms
Iteration   2: 8.180 ops/ms
Iteration   3: 8.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.179 ±(99.9%) 2.721 ops/ms [Average]
  (min, avg, max) = (8.030, 8.179, 8.328), stdev = 0.149
  CI (99.9%): [5.458, 10.901] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.676 ops/ms
# Warmup Iteration   2: 8.207 ops/ms
# Warmup Iteration   3: 8.510 ops/ms
Iteration   1: 8.897 ops/ms
Iteration   2: 9.072 ops/ms
Iteration   3: 8.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.951 ±(99.9%) 1.912 ops/ms [Average]
  (min, avg, max) = (8.884, 8.951, 9.072), stdev = 0.105
  CI (99.9%): [7.039, 10.863] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.042 ops/ms
# Warmup Iteration   2: 8.254 ops/ms
# Warmup Iteration   3: 8.462 ops/ms
Iteration   1: 8.554 ops/ms
Iteration   2: 8.450 ops/ms
Iteration   3: 8.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.465 ±(99.9%) 1.509 ops/ms [Average]
  (min, avg, max) = (8.391, 8.465, 8.554), stdev = 0.083
  CI (99.9%): [6.956, 9.975] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.387 ops/ms
# Warmup Iteration   2: 5.419 ops/ms
# Warmup Iteration   3: 6.180 ops/ms
Iteration   1: 6.114 ops/ms
Iteration   2: 6.233 ops/ms
Iteration   3: 6.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.201 ±(99.9%) 1.385 ops/ms [Average]
  (min, avg, max) = (6.114, 6.201, 6.255), stdev = 0.076
  CI (99.9%): [4.816, 7.585] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.228 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.869 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.011 ms/op
Iteration   1: 3.762 ±(99.9%) 0.004 ms/op
Iteration   2: 3.887 ±(99.9%) 0.003 ms/op
Iteration   3: 3.839 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.829 ±(99.9%) 1.156 ms/op [Average]
  (min, avg, max) = (3.762, 3.829, 3.887), stdev = 0.063
  CI (99.9%): [2.673, 4.986] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.796 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.799 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.004 ms/op
Iteration   1: 3.645 ±(99.9%) 0.003 ms/op
Iteration   2: 3.640 ±(99.9%) 0.003 ms/op
Iteration   3: 3.603 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.629 ±(99.9%) 0.415 ms/op [Average]
  (min, avg, max) = (3.603, 3.629, 3.645), stdev = 0.023
  CI (99.9%): [3.215, 4.044] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.566 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.005 ms/op
Iteration   1: 3.825 ±(99.9%) 0.004 ms/op
Iteration   2: 3.820 ±(99.9%) 0.004 ms/op
Iteration   3: 3.996 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.880 ±(99.9%) 1.832 ms/op [Average]
  (min, avg, max) = (3.820, 3.880, 3.996), stdev = 0.100
  CI (99.9%): [2.049, 5.712] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.197 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.617 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.108 ±(99.9%) 0.012 ms/op
Iteration   1: 5.144 ±(99.9%) 0.012 ms/op
Iteration   2: 5.132 ±(99.9%) 0.022 ms/op
Iteration   3: 5.022 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.100 ±(99.9%) 1.227 ms/op [Average]
  (min, avg, max) = (5.022, 5.100, 5.144), stdev = 0.067
  CI (99.9%): [3.873, 6.326] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.852 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.849 ±(99.9%) 0.011 ms/op
Iteration   1: 3.849 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.087 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  10.024 ms/op
                 createUser·p0.9999: 15.681 ms/op
                 createUser·p1.00:   15.925 ms/op

Iteration   2: 3.853 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.267 ms/op
                 createUser·p0.99:   8.010 ms/op
                 createUser·p0.999:  12.120 ms/op
                 createUser·p0.9999: 17.271 ms/op
                 createUser·p1.00:   19.661 ms/op

Iteration   3: 3.767 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   6.644 ms/op
                 createUser·p0.999:  9.815 ms/op
                 createUser·p0.9999: 23.380 ms/op
                 createUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 251172
  mean =      3.822 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7584 
    [ 2.500,  5.000) = 228810 
    [ 5.000,  7.500) = 12696 
    [ 7.500, 10.000) = 1604 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     11.420 ms/op
     p(99.9900) =     23.032 ms/op
     p(99.9990) =     23.559 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.876 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.992 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.708 ±(99.9%) 0.011 ms/op
Iteration   1: 3.834 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.792 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   7.881 ms/op
                 existUser·p0.999:  11.160 ms/op
                 existUser·p0.9999: 16.078 ms/op
                 existUser·p1.00:   16.482 ms/op

Iteration   2: 3.696 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.563 ms/op
                 existUser·p0.95:   5.095 ms/op
                 existUser·p0.99:   7.207 ms/op
                 existUser·p0.999:  11.362 ms/op
                 existUser·p0.9999: 17.588 ms/op
                 existUser·p1.00:   19.038 ms/op

Iteration   3: 3.627 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   7.184 ms/op
                 existUser·p0.999:  12.179 ms/op
                 existUser·p0.9999: 23.265 ms/op
                 existUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 258091
  mean =      3.717 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11990 
    [ 2.500,  5.000) = 231194 
    [ 5.000,  7.500) = 12418 
    [ 7.500, 10.000) = 1960 
    [10.000, 12.500) = 328 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     11.715 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     23.522 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.440 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.011 ms/op
Iteration   1: 3.841 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   8.184 ms/op
                 getUser·p0.999:  14.610 ms/op
                 getUser·p0.9999: 17.804 ms/op
                 getUser·p1.00:   18.055 ms/op

Iteration   2: 3.774 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  13.268 ms/op
                 getUser·p0.9999: 16.860 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   3: 3.804 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.605 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   7.700 ms/op
                 getUser·p0.999:  15.858 ms/op
                 getUser·p0.9999: 20.584 ms/op
                 getUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 252073
  mean =      3.806 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10408 
    [ 2.500,  5.000) = 226589 
    [ 5.000,  7.500) = 12375 
    [ 7.500, 10.000) = 1914 
    [10.000, 12.500) = 359 
    [12.500, 15.000) = 251 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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
# Warmup Iteration   1: 6.275 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.470 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.134 ±(99.9%) 0.020 ms/op
Iteration   1: 5.150 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   6.889 ms/op
                 listUser·p0.95:   7.864 ms/op
                 listUser·p0.99:   10.207 ms/op
                 listUser·p0.999:  21.970 ms/op
                 listUser·p0.9999: 29.418 ms/op
                 listUser·p1.00:   29.753 ms/op

Iteration   2: 4.951 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.710 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.459 ms/op
                 listUser·p0.95:   7.422 ms/op
                 listUser·p0.99:   9.748 ms/op
                 listUser·p0.999:  17.813 ms/op
                 listUser·p0.9999: 20.992 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   3: 5.047 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   6.529 ms/op
                 listUser·p0.95:   7.479 ms/op
                 listUser·p0.99:   10.568 ms/op
                 listUser·p0.999:  24.331 ms/op
                 listUser·p0.9999: 31.455 ms/op
                 listUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 190303
  mean =      5.048 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 573 
    [ 2.500,  5.000) = 121474 
    [ 5.000,  7.500) = 58002 
    [ 7.500, 10.000) = 8225 
    [10.000, 12.500) = 1267 
    [12.500, 15.000) = 368 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      4.727 ms/op
     p(90.0000) =      6.627 ms/op
     p(95.0000) =      7.586 ms/op
     p(99.0000) =     10.158 ms/op
     p(99.9000) =     20.218 ms/op
     p(99.9900) =     30.342 ms/op
     p(99.9990) =     31.556 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.179 ± 2.721  ops/ms
ClientGrpc.existUser                       thrpt       3   8.951 ± 1.912  ops/ms
ClientGrpc.getUser                         thrpt       3   8.465 ± 1.509  ops/ms
ClientGrpc.listUser                        thrpt       3   6.201 ± 1.385  ops/ms
ClientGrpc.createUser                       avgt       3   3.829 ± 1.156   ms/op
ClientGrpc.existUser                        avgt       3   3.629 ± 0.415   ms/op
ClientGrpc.getUser                          avgt       3   3.880 ± 1.832   ms/op
ClientGrpc.listUser                         avgt       3   5.100 ± 1.227   ms/op
ClientGrpc.createUser                     sample  251172   3.822 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.680           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.120           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.201           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.420           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.032           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.674           ms/op
ClientGrpc.existUser                      sample  258091   3.717 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.819           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.596           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.128           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.422           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.715           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.430           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.560           ms/op
ClientGrpc.getUser                        sample  252073   3.806 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.605           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.161           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.643           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.107           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.825           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.463           ms/op
ClientGrpc.listUser                       sample  190303   5.048 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.141           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.627           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.586           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.158           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.218           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.342           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.556           ms/op
