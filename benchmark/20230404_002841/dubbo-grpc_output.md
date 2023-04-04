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
# Warmup Iteration   1: 4.012 ops/ms
# Warmup Iteration   2: 9.162 ops/ms
# Warmup Iteration   3: 10.125 ops/ms
Iteration   1: 10.552 ops/ms
Iteration   2: 10.706 ops/ms
Iteration   3: 10.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.621 ±(99.9%) 1.430 ops/ms [Average]
  (min, avg, max) = (10.552, 10.621, 10.706), stdev = 0.078
  CI (99.9%): [9.190, 12.051] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.555 ops/ms
# Warmup Iteration   2: 10.841 ops/ms
# Warmup Iteration   3: 11.150 ops/ms
Iteration   1: 10.833 ops/ms
Iteration   2: 10.806 ops/ms
Iteration   3: 11.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.935 ±(99.9%) 3.673 ops/ms [Average]
  (min, avg, max) = (10.806, 10.935, 11.167), stdev = 0.201
  CI (99.9%): [7.263, 14.608] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.904 ops/ms
# Warmup Iteration   2: 10.232 ops/ms
# Warmup Iteration   3: 10.574 ops/ms
Iteration   1: 10.529 ops/ms
Iteration   2: 10.451 ops/ms
Iteration   3: 10.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.484 ±(99.9%) 0.742 ops/ms [Average]
  (min, avg, max) = (10.451, 10.484, 10.529), stdev = 0.041
  CI (99.9%): [9.742, 11.226] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.496 ops/ms
# Warmup Iteration   2: 7.713 ops/ms
# Warmup Iteration   3: 7.907 ops/ms
Iteration   1: 8.029 ops/ms
Iteration   2: 8.095 ops/ms
Iteration   3: 8.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.053 ±(99.9%) 0.661 ops/ms [Average]
  (min, avg, max) = (8.029, 8.053, 8.095), stdev = 0.036
  CI (99.9%): [7.392, 8.714] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.473 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.010 ms/op
Iteration   1: 3.048 ±(99.9%) 0.002 ms/op
Iteration   2: 2.990 ±(99.9%) 0.001 ms/op
Iteration   3: 3.099 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.046 ±(99.9%) 0.989 ms/op [Average]
  (min, avg, max) = (2.990, 3.046, 3.099), stdev = 0.054
  CI (99.9%): [2.057, 4.034] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.931 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.002 ms/op
Iteration   1: 2.949 ±(99.9%) 0.002 ms/op
Iteration   2: 2.891 ±(99.9%) 0.003 ms/op
Iteration   3: 2.884 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.908 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (2.884, 2.908, 2.949), stdev = 0.036
  CI (99.9%): [2.260, 3.556] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.227 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.002 ms/op
Iteration   1: 3.086 ±(99.9%) 0.004 ms/op
Iteration   2: 2.922 ±(99.9%) 0.003 ms/op
Iteration   3: 3.060 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.023 ±(99.9%) 1.605 ms/op [Average]
  (min, avg, max) = (2.922, 3.023, 3.086), stdev = 0.088
  CI (99.9%): [1.418, 4.627] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.566 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.238 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.965 ±(99.9%) 0.027 ms/op
Iteration   1: 3.973 ±(99.9%) 0.027 ms/op
Iteration   2: 4.007 ±(99.9%) 0.012 ms/op
Iteration   3: 3.965 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.981 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (3.965, 3.981, 4.007), stdev = 0.022
  CI (99.9%): [3.576, 4.387] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.408 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.007 ms/op
Iteration   1: 3.021 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.012 ms/op
                 createUser·p0.9999: 12.714 ms/op
                 createUser·p1.00:   13.009 ms/op

Iteration   2: 3.007 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  7.213 ms/op
                 createUser·p0.9999: 14.615 ms/op
                 createUser·p1.00:   15.122 ms/op

Iteration   3: 3.053 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  10.699 ms/op
                 createUser·p0.9999: 30.736 ms/op
                 createUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317001
  mean =      3.027 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25442 
    [ 2.500,  5.000) = 290220 
    [ 5.000,  7.500) = 984 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.766 ms/op
     p(99.9900) =     28.580 ms/op
     p(99.9990) =     30.796 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.139 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.925 ±(99.9%) 0.007 ms/op
Iteration   1: 2.872 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  6.644 ms/op
                 existUser·p0.9999: 12.482 ms/op
                 existUser·p1.00:   12.714 ms/op

Iteration   2: 2.945 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  6.985 ms/op
                 existUser·p0.9999: 16.084 ms/op
                 existUser·p1.00:   18.514 ms/op

Iteration   3: 2.934 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  10.289 ms/op
                 existUser·p0.9999: 25.172 ms/op
                 existUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328997
  mean =      2.917 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41681 
    [ 2.500,  5.000) = 286219 
    [ 5.000,  7.500) = 796 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.078 ms/op
     p(99.9900) =     19.118 ms/op
     p(99.9990) =     26.476 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.342 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.683 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.535 ms/op
                 getUser·p0.99:   4.080 ms/op
                 getUser·p0.999:  6.934 ms/op
                 getUser·p0.9999: 13.610 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  7.991 ms/op
                 getUser·p0.9999: 20.221 ms/op
                 getUser·p1.00:   20.840 ms/op

Iteration   3: 3.008 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  6.396 ms/op
                 getUser·p0.9999: 16.308 ms/op
                 getUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317594
  mean =      3.022 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20053 
    [ 2.500,  5.000) = 296237 
    [ 5.000,  7.500) = 1022 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.257 ms/op
     p(99.9900) =     18.260 ms/op
     p(99.9990) =     20.731 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 5.084 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.011 ms/op
Iteration   1: 4.035 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.454 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  14.414 ms/op
                 listUser·p0.9999: 19.993 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   2: 3.929 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.721 ms/op
                 listUser·p0.9999: 17.780 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   3: 3.978 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  14.146 ms/op
                 listUser·p0.9999: 26.180 ms/op
                 listUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241166
  mean =      3.980 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2280 
    [ 2.500,  5.000) = 215640 
    [ 5.000,  7.500) = 21829 
    [ 7.500, 10.000) = 989 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     14.546 ms/op
     p(99.9900) =     25.719 ms/op
     p(99.9990) =     27.236 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.621 ± 1.430  ops/ms
ClientGrpc.existUser                       thrpt       3  10.935 ± 3.673  ops/ms
ClientGrpc.getUser                         thrpt       3  10.484 ± 0.742  ops/ms
ClientGrpc.listUser                        thrpt       3   8.053 ± 0.661  ops/ms
ClientGrpc.createUser                       avgt       3   3.046 ± 0.989   ms/op
ClientGrpc.existUser                        avgt       3   2.908 ± 0.648   ms/op
ClientGrpc.getUser                          avgt       3   3.023 ± 1.605   ms/op
ClientGrpc.listUser                         avgt       3   3.981 ± 0.406   ms/op
ClientGrpc.createUser                     sample  317001   3.027 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.690           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.766           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.580           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.802           ms/op
ClientGrpc.existUser                      sample  328997   2.917 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.735           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.078           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.118           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.165           ms/op
ClientGrpc.getUser                        sample  317594   3.022 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.683           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.257           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.260           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.840           ms/op
ClientGrpc.listUser                       sample  241166   3.980 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.233           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.546           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.719           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.329           ms/op
