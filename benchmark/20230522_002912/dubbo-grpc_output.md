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
# Warmup Iteration   1: 3.281 ops/ms
# Warmup Iteration   2: 6.660 ops/ms
# Warmup Iteration   3: 8.045 ops/ms
Iteration   1: 8.651 ops/ms
Iteration   2: 8.739 ops/ms
Iteration   3: 8.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.717 ±(99.9%) 1.059 ops/ms [Average]
  (min, avg, max) = (8.651, 8.717, 8.761), stdev = 0.058
  CI (99.9%): [7.658, 9.776] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.968 ops/ms
# Warmup Iteration   2: 8.378 ops/ms
# Warmup Iteration   3: 9.075 ops/ms
Iteration   1: 8.953 ops/ms
Iteration   2: 9.298 ops/ms
Iteration   3: 9.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.138 ±(99.9%) 3.174 ops/ms [Average]
  (min, avg, max) = (8.953, 9.138, 9.298), stdev = 0.174
  CI (99.9%): [5.964, 12.312] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.549 ops/ms
# Warmup Iteration   2: 8.461 ops/ms
# Warmup Iteration   3: 8.712 ops/ms
Iteration   1: 8.631 ops/ms
Iteration   2: 8.889 ops/ms
Iteration   3: 8.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.795 ±(99.9%) 2.589 ops/ms [Average]
  (min, avg, max) = (8.631, 8.795, 8.889), stdev = 0.142
  CI (99.9%): [6.206, 11.384] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.989 ops/ms
# Warmup Iteration   2: 6.314 ops/ms
# Warmup Iteration   3: 6.578 ops/ms
Iteration   1: 6.777 ops/ms
Iteration   2: 6.777 ops/ms
Iteration   3: 6.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.764 ±(99.9%) 0.404 ops/ms [Average]
  (min, avg, max) = (6.738, 6.764, 6.777), stdev = 0.022
  CI (99.9%): [6.360, 7.168] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.411 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.812 ±(99.9%) 0.004 ms/op
Iteration   1: 3.636 ±(99.9%) 0.003 ms/op
Iteration   2: 3.532 ±(99.9%) 0.003 ms/op
Iteration   3: 3.615 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.594 ±(99.9%) 1.001 ms/op [Average]
  (min, avg, max) = (3.532, 3.594, 3.636), stdev = 0.055
  CI (99.9%): [2.593, 4.596] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.064 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.003 ms/op
Iteration   1: 3.344 ±(99.9%) 0.005 ms/op
Iteration   2: 3.414 ±(99.9%) 0.002 ms/op
Iteration   3: 3.460 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.406 ±(99.9%) 1.071 ms/op [Average]
  (min, avg, max) = (3.344, 3.406, 3.460), stdev = 0.059
  CI (99.9%): [2.335, 4.477] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.587 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.643 ±(99.9%) 0.003 ms/op
Iteration   1: 3.630 ±(99.9%) 0.005 ms/op
Iteration   2: 3.562 ±(99.9%) 0.005 ms/op
Iteration   3: 3.676 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.623 ±(99.9%) 1.046 ms/op [Average]
  (min, avg, max) = (3.562, 3.623, 3.676), stdev = 0.057
  CI (99.9%): [2.577, 4.669] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.255 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 5.018 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.778 ±(99.9%) 0.009 ms/op
Iteration   1: 4.712 ±(99.9%) 0.036 ms/op
Iteration   2: 4.651 ±(99.9%) 0.012 ms/op
Iteration   3: 4.686 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.683 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (4.651, 4.683, 4.712), stdev = 0.031
  CI (99.9%): [4.121, 5.245] (assumes normal distribution)


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
# Warmup Iteration   1: 5.097 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.738 ±(99.9%) 0.008 ms/op
Iteration   1: 3.686 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   3.609 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.915 ms/op
                 createUser·p0.99:   7.135 ms/op
                 createUser·p0.999:  11.930 ms/op
                 createUser·p0.9999: 15.171 ms/op
                 createUser·p1.00:   16.646 ms/op

Iteration   2: 3.533 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.711 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  8.985 ms/op
                 createUser·p0.9999: 16.219 ms/op
                 createUser·p1.00:   18.153 ms/op

Iteration   3: 3.616 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.444 ms/op
                 createUser·p0.50:   3.551 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  18.094 ms/op
                 createUser·p0.9999: 23.702 ms/op
                 createUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265783
  mean =      3.611 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11520 
    [ 2.500,  5.000) = 246002 
    [ 5.000,  7.500) = 6873 
    [ 7.500, 10.000) = 858 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     11.751 ms/op
     p(99.9900) =     21.542 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 4.554 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.008 ms/op
Iteration   1: 3.425 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  7.717 ms/op
                 existUser·p0.9999: 18.940 ms/op
                 existUser·p1.00:   19.464 ms/op

Iteration   2: 3.401 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  7.331 ms/op
                 existUser·p0.9999: 20.322 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   3: 3.423 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  9.421 ms/op
                 existUser·p0.9999: 22.981 ms/op
                 existUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 280954
  mean =      3.416 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7822 
    [ 2.500,  5.000) = 269247 
    [ 5.000,  7.500) = 3324 
    [ 7.500, 10.000) = 418 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.158 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =      8.847 ms/op
     p(99.9900) =     22.017 ms/op
     p(99.9990) =     23.081 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 5.221 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.869 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.008 ms/op
Iteration   1: 3.748 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  9.894 ms/op
                 getUser·p0.9999: 14.933 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   2: 3.607 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  8.680 ms/op
                 getUser·p0.9999: 14.696 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   3: 3.685 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.018 ms/op
                 getUser·p0.999:  12.173 ms/op
                 getUser·p0.9999: 20.382 ms/op
                 getUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260827
  mean =      3.679 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6363 
    [ 2.500,  5.000) = 247018 
    [ 5.000,  7.500) = 6444 
    [ 7.500, 10.000) = 740 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     10.049 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     20.932 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 6.473 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.866 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.675 ±(99.9%) 0.014 ms/op
Iteration   1: 4.741 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.659 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   6.603 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  15.319 ms/op
                 listUser·p0.9999: 22.184 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   2: 4.668 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.804 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.669 ms/op
                 listUser·p0.95:   6.660 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  15.565 ms/op
                 listUser·p0.9999: 21.276 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   3: 4.687 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.417 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   6.021 ms/op
                 listUser·p0.95:   6.734 ms/op
                 listUser·p0.99:   8.380 ms/op
                 listUser·p0.999:  18.142 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204275
  mean =      4.698 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 489 
    [ 2.500,  5.000) = 157936 
    [ 5.000,  7.500) = 40916 
    [ 7.500, 10.000) = 4292 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.417 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.890 ms/op
     p(95.0000) =      6.668 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     16.120 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     22.378 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.717 ± 1.059  ops/ms
ClientGrpc.existUser                       thrpt       3   9.138 ± 3.174  ops/ms
ClientGrpc.getUser                         thrpt       3   8.795 ± 2.589  ops/ms
ClientGrpc.listUser                        thrpt       3   6.764 ± 0.404  ops/ms
ClientGrpc.createUser                       avgt       3   3.594 ± 1.001   ms/op
ClientGrpc.existUser                        avgt       3   3.406 ± 1.071   ms/op
ClientGrpc.getUser                          avgt       3   3.623 ± 1.046   ms/op
ClientGrpc.listUser                         avgt       3   4.683 ± 0.562   ms/op
ClientGrpc.createUser                     sample  265783   3.611 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.444           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.103           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.751           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.542           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.248           ms/op
ClientGrpc.existUser                      sample  280954   3.416 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.735           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.903           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.158           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.847           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.017           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.167           ms/op
ClientGrpc.getUser                        sample  260827   3.679 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.667           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.661           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.029           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.049           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.792           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.135           ms/op
ClientGrpc.listUser                       sample  204275   4.698 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.417           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.405           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.120           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.725           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.610           ms/op
