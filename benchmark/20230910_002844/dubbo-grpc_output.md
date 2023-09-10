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
# Warmup Iteration   1: 3.806 ops/ms
# Warmup Iteration   2: 8.273 ops/ms
# Warmup Iteration   3: 9.751 ops/ms
Iteration   1: 10.615 ops/ms
Iteration   2: 10.169 ops/ms
Iteration   3: 10.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.283 ±(99.9%) 5.328 ops/ms [Average]
  (min, avg, max) = (10.066, 10.283, 10.615), stdev = 0.292
  CI (99.9%): [4.955, 15.612] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.336 ops/ms
# Warmup Iteration   2: 9.991 ops/ms
# Warmup Iteration   3: 10.650 ops/ms
Iteration   1: 11.222 ops/ms
Iteration   2: 10.754 ops/ms
Iteration   3: 10.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.852 ±(99.9%) 6.050 ops/ms [Average]
  (min, avg, max) = (10.581, 10.852, 11.222), stdev = 0.332
  CI (99.9%): [4.802, 16.902] (assumes normal distribution)


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
# Warmup Iteration   1: 6.120 ops/ms
# Warmup Iteration   2: 9.812 ops/ms
# Warmup Iteration   3: 10.218 ops/ms
Iteration   1: 10.234 ops/ms
Iteration   2: 10.375 ops/ms
Iteration   3: 10.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.354 ±(99.9%) 2.012 ops/ms [Average]
  (min, avg, max) = (10.234, 10.354, 10.451), stdev = 0.110
  CI (99.9%): [8.341, 12.366] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.242 ops/ms
# Warmup Iteration   2: 7.384 ops/ms
# Warmup Iteration   3: 7.847 ops/ms
Iteration   1: 7.878 ops/ms
Iteration   2: 7.807 ops/ms
Iteration   3: 8.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.902 ±(99.9%) 1.991 ops/ms [Average]
  (min, avg, max) = (7.807, 7.902, 8.021), stdev = 0.109
  CI (99.9%): [5.911, 9.893] (assumes normal distribution)


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
# Warmup Iteration   1: 4.508 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.318 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.004 ms/op
Iteration   1: 3.143 ±(99.9%) 0.018 ms/op
Iteration   2: 3.106 ±(99.9%) 0.003 ms/op
Iteration   3: 3.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.107 ±(99.9%) 0.640 ms/op [Average]
  (min, avg, max) = (3.072, 3.107, 3.143), stdev = 0.035
  CI (99.9%): [2.467, 3.747] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.090 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.002 ms/op
Iteration   1: 2.855 ±(99.9%) 0.004 ms/op
Iteration   2: 2.963 ±(99.9%) 0.002 ms/op
Iteration   3: 2.922 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.913 ±(99.9%) 0.988 ms/op [Average]
  (min, avg, max) = (2.855, 2.913, 2.963), stdev = 0.054
  CI (99.9%): [1.926, 3.901] (assumes normal distribution)


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
# Warmup Iteration   1: 4.294 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.004 ms/op
Iteration   1: 3.102 ±(99.9%) 0.009 ms/op
Iteration   2: 3.105 ±(99.9%) 0.003 ms/op
Iteration   3: 3.063 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.090 ±(99.9%) 0.429 ms/op [Average]
  (min, avg, max) = (3.063, 3.090, 3.105), stdev = 0.023
  CI (99.9%): [2.662, 3.519] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.158 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.319 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.025 ms/op
Iteration   1: 4.046 ±(99.9%) 0.020 ms/op
Iteration   2: 4.010 ±(99.9%) 0.029 ms/op
Iteration   3: 4.048 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.035 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (4.010, 4.035, 4.048), stdev = 0.021
  CI (99.9%): [3.649, 4.421] (assumes normal distribution)


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
# Warmup Iteration   1: 4.771 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.007 ms/op
Iteration   1: 3.117 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  9.781 ms/op
                 createUser·p0.9999: 14.016 ms/op
                 createUser·p1.00:   19.857 ms/op

Iteration   2: 3.048 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.701 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.923 ms/op
                 createUser·p0.999:  8.605 ms/op
                 createUser·p0.9999: 14.910 ms/op
                 createUser·p1.00:   15.204 ms/op

Iteration   3: 3.175 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.848 ms/op
                 createUser·p0.999:  14.607 ms/op
                 createUser·p0.9999: 18.801 ms/op
                 createUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308310
  mean =      3.113 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16879 
    [ 2.500,  5.000) = 288742 
    [ 5.000,  7.500) = 1928 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =     10.728 ms/op
     p(99.9900) =     18.585 ms/op
     p(99.9990) =     20.021 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 4.426 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.005 ms/op
Iteration   1: 2.967 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  8.700 ms/op
                 existUser·p0.9999: 14.097 ms/op
                 existUser·p1.00:   16.646 ms/op

Iteration   2: 2.975 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.702 ms/op
                 existUser·p0.999:  10.150 ms/op
                 existUser·p0.9999: 23.175 ms/op
                 existUser·p1.00:   23.822 ms/op

Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.360 ms/op
                 existUser·p0.999:  8.373 ms/op
                 existUser·p0.9999: 20.808 ms/op
                 existUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322681
  mean =      2.972 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32482 
    [ 2.500,  5.000) = 288102 
    [ 5.000,  7.500) = 1406 
    [ 7.500, 10.000) = 455 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.902 ms/op
     p(99.9900) =     21.471 ms/op
     p(99.9990) =     23.676 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.369 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.007 ms/op
Iteration   1: 3.208 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   5.062 ms/op
                 getUser·p0.999:  9.617 ms/op
                 getUser·p0.9999: 25.232 ms/op
                 getUser·p1.00:   28.115 ms/op

Iteration   2: 3.120 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.907 ms/op
                 getUser·p0.999:  7.848 ms/op
                 getUser·p0.9999: 23.454 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   3: 3.060 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.535 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  8.795 ms/op
                 getUser·p0.9999: 20.361 ms/op
                 getUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306860
  mean =      3.128 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14034 
    [ 2.500,  5.000) = 290190 
    [ 5.000,  7.500) = 2012 
    [ 7.500, 10.000) = 368 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =      8.784 ms/op
     p(99.9900) =     24.376 ms/op
     p(99.9990) =     27.473 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 5.306 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.407 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.011 ms/op
Iteration   1: 4.059 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.446 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.226 ms/op
                 listUser·p0.999:  14.081 ms/op
                 listUser·p0.9999: 20.189 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   2: 4.160 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 18.861 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 4.193 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.538 ms/op
                 listUser·p0.95:   6.218 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  17.225 ms/op
                 listUser·p0.9999: 30.704 ms/op
                 listUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232094
  mean =      4.137 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1601 
    [ 2.500,  5.000) = 199675 
    [ 5.000,  7.500) = 28570 
    [ 7.500, 10.000) = 1686 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     29.648 ms/op
     p(99.9990) =     30.901 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.283 ± 5.328  ops/ms
ClientGrpc.existUser                       thrpt       3  10.852 ± 6.050  ops/ms
ClientGrpc.getUser                         thrpt       3  10.354 ± 2.012  ops/ms
ClientGrpc.listUser                        thrpt       3   7.902 ± 1.991  ops/ms
ClientGrpc.createUser                       avgt       3   3.107 ± 0.640   ms/op
ClientGrpc.existUser                        avgt       3   2.913 ± 0.988   ms/op
ClientGrpc.getUser                          avgt       3   3.090 ± 0.429   ms/op
ClientGrpc.listUser                         avgt       3   4.035 ± 0.386   ms/op
ClientGrpc.createUser                     sample  308310   3.113 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.660           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.858           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.728           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.585           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.299           ms/op
ClientGrpc.existUser                      sample  322681   2.972 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.721           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.902           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.471           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.822           ms/op
ClientGrpc.getUser                        sample  306860   3.128 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.535           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.784           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.376           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.115           ms/op
ClientGrpc.listUser                       sample  232094   4.137 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.033           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.920           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.038           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.463           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.401           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.648           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.966           ms/op
