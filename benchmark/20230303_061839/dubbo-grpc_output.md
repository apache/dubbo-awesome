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
# Warmup Iteration   1: 3.437 ops/ms
# Warmup Iteration   2: 7.254 ops/ms
# Warmup Iteration   3: 8.649 ops/ms
Iteration   1: 8.582 ops/ms
Iteration   2: 8.600 ops/ms
Iteration   3: 8.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.539 ±(99.9%) 1.653 ops/ms [Average]
  (min, avg, max) = (8.435, 8.539, 8.600), stdev = 0.091
  CI (99.9%): [6.886, 10.192] (assumes normal distribution)


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
# Warmup Iteration   1: 5.982 ops/ms
# Warmup Iteration   2: 8.650 ops/ms
# Warmup Iteration   3: 8.840 ops/ms
Iteration   1: 8.619 ops/ms
Iteration   2: 8.975 ops/ms
Iteration   3: 9.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.867 ±(99.9%) 3.941 ops/ms [Average]
  (min, avg, max) = (8.619, 8.867, 9.008), stdev = 0.216
  CI (99.9%): [4.926, 12.809] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.552 ops/ms
# Warmup Iteration   2: 8.024 ops/ms
# Warmup Iteration   3: 8.446 ops/ms
Iteration   1: 8.705 ops/ms
Iteration   2: 8.450 ops/ms
Iteration   3: 8.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.539 ±(99.9%) 2.628 ops/ms [Average]
  (min, avg, max) = (8.450, 8.539, 8.705), stdev = 0.144
  CI (99.9%): [5.911, 11.167] (assumes normal distribution)


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
# Warmup Iteration   1: 4.120 ops/ms
# Warmup Iteration   2: 6.233 ops/ms
# Warmup Iteration   3: 6.776 ops/ms
Iteration   1: 6.683 ops/ms
Iteration   2: 6.697 ops/ms
Iteration   3: 6.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.782 ±(99.9%) 2.908 ops/ms [Average]
  (min, avg, max) = (6.683, 6.782, 6.966), stdev = 0.159
  CI (99.9%): [3.874, 9.690] (assumes normal distribution)


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
# Warmup Iteration   1: 5.229 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.767 ±(99.9%) 0.004 ms/op
Iteration   1: 3.772 ±(99.9%) 0.002 ms/op
Iteration   2: 3.815 ±(99.9%) 0.003 ms/op
Iteration   3: 3.760 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.782 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (3.760, 3.782, 3.815), stdev = 0.029
  CI (99.9%): [3.255, 4.309] (assumes normal distribution)


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
# Warmup Iteration   1: 5.059 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.002 ms/op
Iteration   1: 3.577 ±(99.9%) 0.002 ms/op
Iteration   2: 3.601 ±(99.9%) 0.003 ms/op
Iteration   3: 3.562 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.580 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (3.562, 3.580, 3.601), stdev = 0.020
  CI (99.9%): [3.218, 3.942] (assumes normal distribution)


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
# Warmup Iteration   1: 5.269 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.003 ms/op
Iteration   1: 3.805 ±(99.9%) 0.003 ms/op
Iteration   2: 3.831 ±(99.9%) 0.004 ms/op
Iteration   3: 3.735 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.791 ±(99.9%) 0.907 ms/op [Average]
  (min, avg, max) = (3.735, 3.791, 3.831), stdev = 0.050
  CI (99.9%): [2.884, 4.697] (assumes normal distribution)


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
# Warmup Iteration   1: 5.744 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.202 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.755 ±(99.9%) 0.013 ms/op
Iteration   1: 4.682 ±(99.9%) 0.013 ms/op
Iteration   2: 4.717 ±(99.9%) 0.015 ms/op
Iteration   3: 4.466 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.622 ±(99.9%) 2.475 ms/op [Average]
  (min, avg, max) = (4.466, 4.622, 4.717), stdev = 0.136
  CI (99.9%): [2.147, 7.096] (assumes normal distribution)


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
# Warmup Iteration   1: 5.437 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.070 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.008 ms/op
Iteration   1: 3.841 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  10.699 ms/op
                 createUser·p0.9999: 20.655 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   2: 3.837 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   3.783 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  9.907 ms/op
                 createUser·p0.9999: 20.808 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   3: 3.754 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  19.065 ms/op
                 createUser·p0.9999: 40.074 ms/op
                 createUser·p1.00:   58.720 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 251794
  mean =      3.810 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 241633 
    [ 5.000, 10.000) = 9834 
    [10.000, 15.000) = 140 
    [15.000, 20.000) = 81 
    [20.000, 25.000) = 40 
    [25.000, 30.000) = 30 
    [30.000, 35.000) = 8 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     11.836 ms/op
     p(99.9900) =     39.322 ms/op
     p(99.9990) =     58.621 ms/op
     p(99.9999) =     58.720 ms/op
    p(100.0000) =     58.720 ms/op


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
# Warmup Iteration   1: 4.854 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.008 ms/op
Iteration   1: 3.648 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  10.349 ms/op
                 existUser·p0.9999: 14.737 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   2: 3.652 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  8.428 ms/op
                 existUser·p0.9999: 15.982 ms/op
                 existUser·p1.00:   16.482 ms/op

Iteration   3: 3.596 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   5.485 ms/op
                 existUser·p0.999:  13.337 ms/op
                 existUser·p0.9999: 23.658 ms/op
                 existUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264187
  mean =      3.632 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13962 
    [ 2.500,  5.000) = 244595 
    [ 5.000,  7.500) = 4769 
    [ 7.500, 10.000) = 566 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     10.856 ms/op
     p(99.9900) =     23.186 ms/op
     p(99.9990) =     23.801 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 5.294 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.866 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.010 ms/op
Iteration   1: 3.710 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  8.959 ms/op
                 getUser·p0.9999: 15.232 ms/op
                 getUser·p1.00:   15.630 ms/op

Iteration   2: 3.736 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  11.321 ms/op
                 getUser·p0.9999: 20.116 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   3: 3.803 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  8.389 ms/op
                 getUser·p0.9999: 18.828 ms/op
                 getUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255858
  mean =      3.750 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7301 
    [ 2.500,  5.000) = 240152 
    [ 5.000,  7.500) = 7748 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      8.866 ms/op
     p(99.9900) =     19.209 ms/op
     p(99.9990) =     21.109 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 6.533 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.987 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.644 ±(99.9%) 0.013 ms/op
Iteration   1: 4.754 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.628 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.070 ms/op
                 listUser·p0.95:   6.906 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  14.463 ms/op
                 listUser·p0.9999: 18.371 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   2: 4.792 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.029 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  19.654 ms/op
                 listUser·p0.9999: 22.064 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   3: 4.672 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   6.668 ms/op
                 listUser·p0.99:   8.705 ms/op
                 listUser·p0.999:  18.859 ms/op
                 listUser·p0.9999: 21.375 ms/op
                 listUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202469
  mean =      4.739 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 212 
    [ 2.500,  5.000) = 154608 
    [ 5.000,  7.500) = 42147 
    [ 7.500, 10.000) = 4699 
    [10.000, 12.500) = 394 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.980 ms/op
     p(95.0000) =      6.832 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     16.793 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     23.062 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.539 ± 1.653  ops/ms
ClientGrpc.existUser                       thrpt       3   8.867 ± 3.941  ops/ms
ClientGrpc.getUser                         thrpt       3   8.539 ± 2.628  ops/ms
ClientGrpc.listUser                        thrpt       3   6.782 ± 2.908  ops/ms
ClientGrpc.createUser                       avgt       3   3.782 ± 0.527   ms/op
ClientGrpc.existUser                        avgt       3   3.580 ± 0.362   ms/op
ClientGrpc.getUser                          avgt       3   3.791 ± 0.907   ms/op
ClientGrpc.listUser                         avgt       3   4.622 ± 2.475   ms/op
ClientGrpc.createUser                     sample  251794   3.810 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.844           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.915           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.980           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.836           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          39.322           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          58.720           ms/op
ClientGrpc.existUser                      sample  264187   3.632 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.804           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.702           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.856           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.186           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.642           ms/op
ClientGrpc.getUser                        sample  255858   3.750 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.929           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.636           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.866           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.209           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.234           ms/op
ClientGrpc.listUser                       sample  202469   4.739 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.176           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.530           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.980           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.552           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.793           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.725           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.560           ms/op
