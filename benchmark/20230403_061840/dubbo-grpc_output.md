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
# Warmup Iteration   1: 3.233 ops/ms
# Warmup Iteration   2: 6.597 ops/ms
# Warmup Iteration   3: 7.750 ops/ms
Iteration   1: 8.044 ops/ms
Iteration   2: 8.329 ops/ms
Iteration   3: 8.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.220 ±(99.9%) 2.809 ops/ms [Average]
  (min, avg, max) = (8.044, 8.220, 8.329), stdev = 0.154
  CI (99.9%): [5.411, 11.028] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.480 ops/ms
# Warmup Iteration   2: 8.010 ops/ms
# Warmup Iteration   3: 8.480 ops/ms
Iteration   1: 8.844 ops/ms
Iteration   2: 8.875 ops/ms
Iteration   3: 8.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.771 ±(99.9%) 2.803 ops/ms [Average]
  (min, avg, max) = (8.594, 8.771, 8.875), stdev = 0.154
  CI (99.9%): [5.968, 11.574] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.106 ops/ms
# Warmup Iteration   2: 7.996 ops/ms
# Warmup Iteration   3: 7.993 ops/ms
Iteration   1: 8.269 ops/ms
Iteration   2: 8.203 ops/ms
Iteration   3: 8.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.309 ±(99.9%) 2.391 ops/ms [Average]
  (min, avg, max) = (8.203, 8.309, 8.456), stdev = 0.131
  CI (99.9%): [5.918, 10.701] (assumes normal distribution)


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
# Warmup Iteration   1: 3.996 ops/ms
# Warmup Iteration   2: 5.757 ops/ms
# Warmup Iteration   3: 6.354 ops/ms
Iteration   1: 6.431 ops/ms
Iteration   2: 6.463 ops/ms
Iteration   3: 6.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.397 ±(99.9%) 1.628 ops/ms [Average]
  (min, avg, max) = (6.295, 6.397, 6.463), stdev = 0.089
  CI (99.9%): [4.768, 8.025] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.708 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.004 ms/op
Iteration   1: 3.948 ±(99.9%) 0.003 ms/op
Iteration   2: 3.905 ±(99.9%) 0.004 ms/op
Iteration   3: 3.825 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.893 ±(99.9%) 1.139 ms/op [Average]
  (min, avg, max) = (3.825, 3.893, 3.948), stdev = 0.062
  CI (99.9%): [2.754, 5.032] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.216 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.772 ±(99.9%) 0.003 ms/op
Iteration   1: 3.868 ±(99.9%) 0.003 ms/op
Iteration   2: 3.902 ±(99.9%) 0.003 ms/op
Iteration   3: 3.731 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.834 ±(99.9%) 1.656 ms/op [Average]
  (min, avg, max) = (3.731, 3.834, 3.902), stdev = 0.091
  CI (99.9%): [2.178, 5.490] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.739 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.003 ms/op
Iteration   1: 4.045 ±(99.9%) 0.003 ms/op
Iteration   2: 3.943 ±(99.9%) 0.003 ms/op
Iteration   3: 3.912 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.967 ±(99.9%) 1.273 ms/op [Average]
  (min, avg, max) = (3.912, 3.967, 4.045), stdev = 0.070
  CI (99.9%): [2.693, 5.240] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.704 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.351 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.927 ±(99.9%) 0.022 ms/op
Iteration   1: 4.856 ±(99.9%) 0.009 ms/op
Iteration   2: 4.901 ±(99.9%) 0.021 ms/op
Iteration   3: 4.908 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.888 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (4.856, 4.888, 4.908), stdev = 0.028
  CI (99.9%): [4.376, 5.401] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.413 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.012 ms/op
Iteration   1: 3.813 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  11.108 ms/op
                 createUser·p0.9999: 24.104 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   2: 3.909 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.308 ms/op
                 createUser·p0.99:   7.004 ms/op
                 createUser·p0.999:  11.387 ms/op
                 createUser·p0.9999: 17.525 ms/op
                 createUser·p1.00:   18.088 ms/op

Iteration   3: 3.914 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   7.602 ms/op
                 createUser·p0.999:  13.469 ms/op
                 createUser·p0.9999: 31.752 ms/op
                 createUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 247830
  mean =      3.878 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6965 
    [ 2.500,  5.000) = 225774 
    [ 5.000,  7.500) = 13040 
    [ 7.500, 10.000) = 1436 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.132 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     12.520 ms/op
     p(99.9900) =     31.399 ms/op
     p(99.9990) =     32.154 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.502 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 3.857 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.649 ±(99.9%) 0.010 ms/op
Iteration   1: 3.641 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   3.523 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   6.857 ms/op
                 existUser·p0.999:  10.194 ms/op
                 existUser·p0.9999: 15.945 ms/op
                 existUser·p1.00:   16.351 ms/op

Iteration   2: 3.631 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  11.384 ms/op
                 existUser·p0.9999: 19.169 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   3: 3.445 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.340 ms/op
                 existUser·p0.50:   3.465 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  11.671 ms/op
                 existUser·p0.9999: 18.931 ms/op
                 existUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268700
  mean =      3.570 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13245 
    [ 2.500,  5.000) = 247145 
    [ 5.000,  7.500) = 6915 
    [ 7.500, 10.000) = 1068 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.340 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     11.062 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     21.058 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 5.689 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.011 ms/op
Iteration   1: 3.791 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  11.232 ms/op
                 getUser·p0.9999: 15.721 ms/op
                 getUser·p1.00:   16.122 ms/op

Iteration   2: 3.821 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  11.277 ms/op
                 getUser·p0.9999: 28.299 ms/op
                 getUser·p1.00:   28.606 ms/op

Iteration   3: 3.814 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  10.715 ms/op
                 getUser·p0.9999: 20.782 ms/op
                 getUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 252015
  mean =      3.809 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6381 
    [ 2.500,  5.000) = 233248 
    [ 5.000,  7.500) = 11091 
    [ 7.500, 10.000) = 933 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     11.108 ms/op
     p(99.9900) =     27.715 ms/op
     p(99.9990) =     28.491 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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
# Warmup Iteration   1: 7.727 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.144 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.802 ±(99.9%) 0.015 ms/op
Iteration   1: 4.900 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.357 ms/op
                 listUser·p0.95:   7.217 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  15.245 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   2: 4.779 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.535 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.185 ms/op
                 listUser·p0.95:   7.111 ms/op
                 listUser·p0.99:   9.585 ms/op
                 listUser·p0.999:  17.960 ms/op
                 listUser·p0.9999: 30.573 ms/op
                 listUser·p1.00:   30.835 ms/op

Iteration   3: 4.727 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   6.169 ms/op
                 listUser·p0.95:   7.062 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  21.585 ms/op
                 listUser·p0.9999: 32.940 ms/op
                 listUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199829
  mean =      4.801 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 309 
    [ 2.500,  5.000) = 143520 
    [ 5.000,  7.500) = 48727 
    [ 7.500, 10.000) = 5927 
    [10.000, 12.500) = 742 
    [12.500, 15.000) = 282 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      6.242 ms/op
     p(95.0000) =      7.127 ms/op
     p(99.0000) =      9.273 ms/op
     p(99.9000) =     17.810 ms/op
     p(99.9900) =     31.850 ms/op
     p(99.9990) =     36.308 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.220 ± 2.809  ops/ms
ClientGrpc.existUser                       thrpt       3   8.771 ± 2.803  ops/ms
ClientGrpc.getUser                         thrpt       3   8.309 ± 2.391  ops/ms
ClientGrpc.listUser                        thrpt       3   6.397 ± 1.628  ops/ms
ClientGrpc.createUser                       avgt       3   3.893 ± 1.139   ms/op
ClientGrpc.existUser                        avgt       3   3.834 ± 1.656   ms/op
ClientGrpc.getUser                          avgt       3   3.967 ± 1.273   ms/op
ClientGrpc.listUser                         avgt       3   4.888 ± 0.512   ms/op
ClientGrpc.createUser                     sample  247830   3.878 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.906           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.132           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.045           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.520           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.399           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.013           ms/op
ClientGrpc.existUser                      sample  268700   3.570 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.340           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.382           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.062           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.038           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.496           ms/op
ClientGrpc.getUser                        sample  252015   3.809 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.770           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.989           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.480           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.108           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.715           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.606           ms/op
ClientGrpc.listUser                       sample  199829   4.801 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.535           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.555           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.242           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.273           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.810           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.850           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.700           ms/op
