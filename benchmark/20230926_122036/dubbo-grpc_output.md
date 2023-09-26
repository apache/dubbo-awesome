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
# Warmup Iteration   1: 3.006 ops/ms
# Warmup Iteration   2: 6.720 ops/ms
# Warmup Iteration   3: 7.515 ops/ms
Iteration   1: 7.784 ops/ms
Iteration   2: 8.293 ops/ms
Iteration   3: 8.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.048 ±(99.9%) 4.660 ops/ms [Average]
  (min, avg, max) = (7.784, 8.048, 8.293), stdev = 0.255
  CI (99.9%): [3.388, 12.708] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.895 ops/ms
# Warmup Iteration   2: 8.178 ops/ms
# Warmup Iteration   3: 8.606 ops/ms
Iteration   1: 8.639 ops/ms
Iteration   2: 8.856 ops/ms
Iteration   3: 8.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.693 ±(99.9%) 2.627 ops/ms [Average]
  (min, avg, max) = (8.584, 8.693, 8.856), stdev = 0.144
  CI (99.9%): [6.066, 11.320] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.775 ops/ms
# Warmup Iteration   2: 7.832 ops/ms
# Warmup Iteration   3: 8.216 ops/ms
Iteration   1: 8.038 ops/ms
Iteration   2: 8.439 ops/ms
Iteration   3: 8.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.253 ±(99.9%) 3.689 ops/ms [Average]
  (min, avg, max) = (8.038, 8.253, 8.439), stdev = 0.202
  CI (99.9%): [4.565, 11.942] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.612 ops/ms
# Warmup Iteration   2: 5.814 ops/ms
# Warmup Iteration   3: 6.247 ops/ms
Iteration   1: 6.391 ops/ms
Iteration   2: 6.276 ops/ms
Iteration   3: 6.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.293 ±(99.9%) 1.662 ops/ms [Average]
  (min, avg, max) = (6.211, 6.293, 6.391), stdev = 0.091
  CI (99.9%): [4.631, 7.954] (assumes normal distribution)


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
# Warmup Iteration   1: 5.589 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.036 ms/op
Iteration   1: 3.820 ±(99.9%) 0.003 ms/op
Iteration   2: 3.826 ±(99.9%) 0.003 ms/op
Iteration   3: 3.964 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.870 ±(99.9%) 1.493 ms/op [Average]
  (min, avg, max) = (3.820, 3.870, 3.964), stdev = 0.082
  CI (99.9%): [2.377, 5.363] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.093 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.868 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.831 ±(99.9%) 0.003 ms/op
Iteration   1: 3.820 ±(99.9%) 0.014 ms/op
Iteration   2: 3.514 ±(99.9%) 0.004 ms/op
Iteration   3: 3.694 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.676 ±(99.9%) 2.810 ms/op [Average]
  (min, avg, max) = (3.514, 3.676, 3.820), stdev = 0.154
  CI (99.9%): [0.866, 6.485] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.388 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.724 ±(99.9%) 0.003 ms/op
Iteration   1: 3.806 ±(99.9%) 0.005 ms/op
Iteration   2: 3.893 ±(99.9%) 0.003 ms/op
Iteration   3: 3.932 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.877 ±(99.9%) 1.176 ms/op [Average]
  (min, avg, max) = (3.806, 3.877, 3.932), stdev = 0.064
  CI (99.9%): [2.701, 5.052] (assumes normal distribution)


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
# Warmup Iteration   1: 7.381 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.505 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.984 ±(99.9%) 0.019 ms/op
Iteration   1: 4.889 ±(99.9%) 0.014 ms/op
Iteration   2: 5.071 ±(99.9%) 0.010 ms/op
Iteration   3: 4.714 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.891 ±(99.9%) 3.251 ms/op [Average]
  (min, avg, max) = (4.714, 4.891, 5.071), stdev = 0.178
  CI (99.9%): [1.640, 8.142] (assumes normal distribution)


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
# Warmup Iteration   1: 5.338 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.238 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.013 ms/op
Iteration   1: 3.766 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  9.620 ms/op
                 createUser·p0.9999: 19.628 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   2: 3.952 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.899 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   7.358 ms/op
                 createUser·p0.999:  13.058 ms/op
                 createUser·p0.9999: 29.816 ms/op
                 createUser·p1.00:   31.588 ms/op

Iteration   3: 4.027 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.915 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   7.274 ms/op
                 createUser·p0.999:  9.415 ms/op
                 createUser·p0.9999: 25.926 ms/op
                 createUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 245176
  mean =      3.912 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3602 
    [ 2.500,  5.000) = 223237 
    [ 5.000,  7.500) = 16671 
    [ 7.500, 10.000) = 1346 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     11.026 ms/op
     p(99.9900) =     26.934 ms/op
     p(99.9990) =     29.819 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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
# Warmup Iteration   1: 5.305 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.683 ±(99.9%) 0.009 ms/op
Iteration   1: 3.721 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.563 ms/op
                 existUser·p0.95:   4.981 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  9.664 ms/op
                 existUser·p0.9999: 17.491 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   2: 3.672 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   6.865 ms/op
                 existUser·p0.999:  12.317 ms/op
                 existUser·p0.9999: 20.677 ms/op
                 existUser·p1.00:   21.299 ms/op

Iteration   3: 3.840 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.727 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  9.349 ms/op
                 existUser·p0.9999: 19.901 ms/op
                 existUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 256528
  mean =      3.743 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8763 
    [ 2.500,  5.000) = 234659 
    [ 5.000,  7.500) = 11668 
    [ 7.500, 10.000) = 1182 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     10.002 ms/op
     p(99.9900) =     19.967 ms/op
     p(99.9990) =     21.113 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.275 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.897 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.011 ms/op
Iteration   1: 3.929 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.407 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  10.709 ms/op
                 getUser·p0.9999: 18.313 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   2: 3.866 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   5.263 ms/op
                 getUser·p0.99:   6.658 ms/op
                 getUser·p0.999:  11.119 ms/op
                 getUser·p0.9999: 21.627 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   3: 3.819 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  8.880 ms/op
                 getUser·p0.9999: 20.611 ms/op
                 getUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 247966
  mean =      3.871 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7085 
    [ 2.500,  5.000) = 223277 
    [ 5.000,  7.500) = 16458 
    [ 7.500, 10.000) = 843 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     10.404 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 5.730 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.493 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.915 ±(99.9%) 0.016 ms/op
Iteration   1: 5.042 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.586 ms/op
                 listUser·p0.95:   7.463 ms/op
                 listUser·p0.99:   9.699 ms/op
                 listUser·p0.999:  15.998 ms/op
                 listUser·p0.9999: 17.887 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   2: 5.095 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.751 ms/op
                 listUser·p0.50:   4.833 ms/op
                 listUser·p0.90:   6.537 ms/op
                 listUser·p0.95:   7.430 ms/op
                 listUser·p0.99:   9.568 ms/op
                 listUser·p0.999:  17.473 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   3: 5.077 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.496 ms/op
                 listUser·p0.95:   7.430 ms/op
                 listUser·p0.99:   9.650 ms/op
                 listUser·p0.999:  20.184 ms/op
                 listUser·p0.9999: 25.539 ms/op
                 listUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 189312
  mean =      5.071 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 334 
    [ 2.500,  5.000) = 114440 
    [ 5.000,  7.500) = 65518 
    [ 7.500, 10.000) = 7492 
    [10.000, 12.500) = 937 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      4.792 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      7.447 ms/op
     p(99.0000) =      9.650 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     24.155 ms/op
     p(99.9990) =     25.892 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.048 ± 4.660  ops/ms
ClientGrpc.existUser                       thrpt       3   8.693 ± 2.627  ops/ms
ClientGrpc.getUser                         thrpt       3   8.253 ± 3.689  ops/ms
ClientGrpc.listUser                        thrpt       3   6.293 ± 1.662  ops/ms
ClientGrpc.createUser                       avgt       3   3.870 ± 1.493   ms/op
ClientGrpc.existUser                        avgt       3   3.676 ± 2.810   ms/op
ClientGrpc.getUser                          avgt       3   3.877 ± 1.176   ms/op
ClientGrpc.listUser                         avgt       3   4.891 ± 3.251   ms/op
ClientGrpc.createUser                     sample  245176   3.912 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.643           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.292           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.029           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.026           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.934           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.588           ms/op
ClientGrpc.existUser                      sample  256528   3.743 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.645           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.612           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.014           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.660           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.002           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.967           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.299           ms/op
ClientGrpc.getUser                        sample  247966   3.871 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.815           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.243           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.636           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.404           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.644           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.725           ms/op
ClientGrpc.listUser                       sample  189312   5.071 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.751           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.447           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.650           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.908           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.155           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.214           ms/op
