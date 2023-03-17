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
# Warmup Iteration   1: 2.918 ops/ms
# Warmup Iteration   2: 6.972 ops/ms
# Warmup Iteration   3: 8.333 ops/ms
Iteration   1: 8.309 ops/ms
Iteration   2: 8.562 ops/ms
Iteration   3: 8.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.448 ±(99.9%) 2.337 ops/ms [Average]
  (min, avg, max) = (8.309, 8.448, 8.562), stdev = 0.128
  CI (99.9%): [6.111, 10.785] (assumes normal distribution)


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
# Warmup Iteration   1: 5.971 ops/ms
# Warmup Iteration   2: 8.670 ops/ms
# Warmup Iteration   3: 9.140 ops/ms
Iteration   1: 9.597 ops/ms
Iteration   2: 9.253 ops/ms
Iteration   3: 9.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.324 ±(99.9%) 4.485 ops/ms [Average]
  (min, avg, max) = (9.121, 9.324, 9.597), stdev = 0.246
  CI (99.9%): [4.838, 13.809] (assumes normal distribution)


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
# Warmup Iteration   1: 5.250 ops/ms
# Warmup Iteration   2: 7.879 ops/ms
# Warmup Iteration   3: 8.499 ops/ms
Iteration   1: 8.367 ops/ms
Iteration   2: 8.739 ops/ms
Iteration   3: 8.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.601 ±(99.9%) 3.724 ops/ms [Average]
  (min, avg, max) = (8.367, 8.601, 8.739), stdev = 0.204
  CI (99.9%): [4.878, 12.325] (assumes normal distribution)


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
# Warmup Iteration   1: 4.368 ops/ms
# Warmup Iteration   2: 6.089 ops/ms
# Warmup Iteration   3: 6.386 ops/ms
Iteration   1: 6.656 ops/ms
Iteration   2: 6.303 ops/ms
Iteration   3: 6.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.398 ±(99.9%) 4.113 ops/ms [Average]
  (min, avg, max) = (6.237, 6.398, 6.656), stdev = 0.225
  CI (99.9%): [2.286, 10.511] (assumes normal distribution)


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
# Warmup Iteration   1: 5.599 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.002 ms/op
Iteration   1: 3.723 ±(99.9%) 0.003 ms/op
Iteration   2: 3.810 ±(99.9%) 0.003 ms/op
Iteration   3: 3.835 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.790 ±(99.9%) 1.078 ms/op [Average]
  (min, avg, max) = (3.723, 3.790, 3.835), stdev = 0.059
  CI (99.9%): [2.711, 4.868] (assumes normal distribution)


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
# Warmup Iteration   1: 5.079 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.003 ms/op
Iteration   1: 3.521 ±(99.9%) 0.003 ms/op
Iteration   2: 3.600 ±(99.9%) 0.003 ms/op
Iteration   3: 3.399 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.507 ±(99.9%) 1.841 ms/op [Average]
  (min, avg, max) = (3.399, 3.507, 3.600), stdev = 0.101
  CI (99.9%): [1.666, 5.347] (assumes normal distribution)


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
# Warmup Iteration   1: 5.675 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.010 ms/op
Iteration   1: 3.722 ±(99.9%) 0.003 ms/op
Iteration   2: 3.805 ±(99.9%) 0.004 ms/op
Iteration   3: 3.758 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.762 ±(99.9%) 0.757 ms/op [Average]
  (min, avg, max) = (3.722, 3.762, 3.805), stdev = 0.042
  CI (99.9%): [3.004, 4.519] (assumes normal distribution)


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
# Warmup Iteration   1: 6.860 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.340 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.952 ±(99.9%) 0.020 ms/op
Iteration   1: 4.729 ±(99.9%) 0.007 ms/op
Iteration   2: 4.718 ±(99.9%) 0.016 ms/op
Iteration   3: 4.775 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.741 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (4.718, 4.741, 4.775), stdev = 0.030
  CI (99.9%): [4.188, 5.294] (assumes normal distribution)


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
# Warmup Iteration   1: 6.082 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.024 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.010 ms/op
Iteration   1: 3.839 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  11.546 ms/op
                 createUser·p0.9999: 15.368 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   2: 3.869 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  10.903 ms/op
                 createUser·p0.9999: 19.137 ms/op
                 createUser·p1.00:   19.661 ms/op

Iteration   3: 3.767 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  13.844 ms/op
                 createUser·p0.9999: 29.507 ms/op
                 createUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 251105
  mean =      3.825 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4310 
    [ 2.500,  5.000) = 231315 
    [ 5.000,  7.500) = 14563 
    [ 7.500, 10.000) = 573 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     11.396 ms/op
     p(99.9900) =     29.124 ms/op
     p(99.9990) =     29.900 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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
# Warmup Iteration   1: 4.960 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.628 ±(99.9%) 0.009 ms/op
Iteration   1: 3.492 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  9.574 ms/op
                 existUser·p0.9999: 14.533 ms/op
                 existUser·p1.00:   17.400 ms/op

Iteration   2: 3.395 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  10.142 ms/op
                 existUser·p0.9999: 17.859 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   3: 3.691 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.637 ms/op
                 existUser·p0.95:   5.046 ms/op
                 existUser·p0.99:   6.125 ms/op
                 existUser·p0.999:  9.492 ms/op
                 existUser·p0.9999: 23.036 ms/op
                 existUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272342
  mean =      3.522 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13947 
    [ 2.500,  5.000) = 247805 
    [ 5.000,  7.500) = 9772 
    [ 7.500, 10.000) = 591 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =      9.710 ms/op
     p(99.9900) =     21.284 ms/op
     p(99.9990) =     23.596 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 5.826 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.966 ±(99.9%) 0.011 ms/op
Iteration   1: 3.939 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.964 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   6.720 ms/op
                 getUser·p0.999:  12.415 ms/op
                 getUser·p0.9999: 20.836 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   2: 3.811 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  8.865 ms/op
                 getUser·p0.9999: 34.472 ms/op
                 getUser·p1.00:   34.800 ms/op

Iteration   3: 3.773 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  10.672 ms/op
                 getUser·p0.9999: 22.446 ms/op
                 getUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 249910
  mean =      3.840 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4421 
    [ 2.500,  5.000) = 227654 
    [ 5.000,  7.500) = 16738 
    [ 7.500, 10.000) = 786 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     11.210 ms/op
     p(99.9900) =     34.210 ms/op
     p(99.9990) =     34.701 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 7.191 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.996 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.755 ±(99.9%) 0.016 ms/op
Iteration   1: 4.861 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   6.341 ms/op
                 listUser·p0.95:   7.184 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  14.128 ms/op
                 listUser·p0.9999: 19.084 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   2: 5.023 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   6.930 ms/op
                 listUser·p0.95:   7.782 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  16.559 ms/op
                 listUser·p0.9999: 19.801 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   3: 4.933 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.578 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   9.329 ms/op
                 listUser·p0.999:  24.535 ms/op
                 listUser·p0.9999: 30.032 ms/op
                 listUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194521
  mean =      4.938 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 739 
    [ 2.500,  5.000) = 123617 
    [ 5.000,  7.500) = 60456 
    [ 7.500, 10.000) = 8355 
    [10.000, 12.500) = 834 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      4.653 ms/op
     p(90.0000) =      6.627 ms/op
     p(95.0000) =      7.496 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     16.841 ms/op
     p(99.9900) =     29.360 ms/op
     p(99.9990) =     30.509 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.448 ± 2.337  ops/ms
ClientGrpc.existUser                       thrpt       3   9.324 ± 4.485  ops/ms
ClientGrpc.getUser                         thrpt       3   8.601 ± 3.724  ops/ms
ClientGrpc.listUser                        thrpt       3   6.398 ± 4.113  ops/ms
ClientGrpc.createUser                       avgt       3   3.790 ± 1.078   ms/op
ClientGrpc.existUser                        avgt       3   3.507 ± 1.841   ms/op
ClientGrpc.getUser                          avgt       3   3.762 ± 0.757   ms/op
ClientGrpc.listUser                         avgt       3   4.741 ± 0.553   ms/op
ClientGrpc.createUser                     sample  251105   3.825 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.859           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.112           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.234           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.396           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.124           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.983           ms/op
ClientGrpc.existUser                      sample  272342   3.522 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.845           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.841           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.005           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.710           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.284           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.790           ms/op
ClientGrpc.getUser                        sample  249910   3.840 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.693           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.809           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.202           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.357           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.210           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.210           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.800           ms/op
ClientGrpc.listUser                       sample  194521   4.938 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.108           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.653           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.627           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.496           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.437           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.841           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.360           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.540           ms/op
