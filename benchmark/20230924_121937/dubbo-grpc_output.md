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
# Warmup Iteration   1: 3.138 ops/ms
# Warmup Iteration   2: 6.572 ops/ms
# Warmup Iteration   3: 7.892 ops/ms
Iteration   1: 8.450 ops/ms
Iteration   2: 8.280 ops/ms
Iteration   3: 8.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.421 ±(99.9%) 2.345 ops/ms [Average]
  (min, avg, max) = (8.280, 8.421, 8.532), stdev = 0.129
  CI (99.9%): [6.076, 10.766] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.798 ops/ms
# Warmup Iteration   2: 8.094 ops/ms
# Warmup Iteration   3: 8.712 ops/ms
Iteration   1: 8.531 ops/ms
Iteration   2: 8.558 ops/ms
Iteration   3: 9.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.699 ±(99.9%) 4.878 ops/ms [Average]
  (min, avg, max) = (8.531, 8.699, 9.007), stdev = 0.267
  CI (99.9%): [3.821, 13.577] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.586 ops/ms
# Warmup Iteration   2: 7.981 ops/ms
# Warmup Iteration   3: 8.364 ops/ms
Iteration   1: 8.422 ops/ms
Iteration   2: 8.592 ops/ms
Iteration   3: 8.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.479 ±(99.9%) 1.794 ops/ms [Average]
  (min, avg, max) = (8.422, 8.479, 8.592), stdev = 0.098
  CI (99.9%): [6.684, 10.273] (assumes normal distribution)


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
# Warmup Iteration   1: 4.346 ops/ms
# Warmup Iteration   2: 5.809 ops/ms
# Warmup Iteration   3: 6.509 ops/ms
Iteration   1: 6.472 ops/ms
Iteration   2: 6.735 ops/ms
Iteration   3: 6.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.620 ±(99.9%) 2.449 ops/ms [Average]
  (min, avg, max) = (6.472, 6.620, 6.735), stdev = 0.134
  CI (99.9%): [4.171, 9.069] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.514 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.023 ms/op
Iteration   1: 3.827 ±(99.9%) 0.004 ms/op
Iteration   2: 3.786 ±(99.9%) 0.003 ms/op
Iteration   3: 3.733 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.782 ±(99.9%) 0.859 ms/op [Average]
  (min, avg, max) = (3.733, 3.782, 3.827), stdev = 0.047
  CI (99.9%): [2.923, 4.641] (assumes normal distribution)


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
# Warmup Iteration   1: 5.230 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.002 ms/op
Iteration   1: 3.612 ±(99.9%) 0.002 ms/op
Iteration   2: 3.452 ±(99.9%) 0.003 ms/op
Iteration   3: 3.523 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.529 ±(99.9%) 1.461 ms/op [Average]
  (min, avg, max) = (3.452, 3.529, 3.612), stdev = 0.080
  CI (99.9%): [2.068, 4.990] (assumes normal distribution)


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
# Warmup Iteration   1: 5.151 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.787 ±(99.9%) 0.004 ms/op
Iteration   1: 3.770 ±(99.9%) 0.004 ms/op
Iteration   2: 3.778 ±(99.9%) 0.003 ms/op
Iteration   3: 3.757 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.769 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (3.757, 3.769, 3.778), stdev = 0.010
  CI (99.9%): [3.578, 3.959] (assumes normal distribution)


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
# Warmup Iteration   1: 7.091 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.294 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.930 ±(99.9%) 0.016 ms/op
Iteration   1: 4.758 ±(99.9%) 0.016 ms/op
Iteration   2: 4.648 ±(99.9%) 0.010 ms/op
Iteration   3: 4.760 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.722 ±(99.9%) 1.165 ms/op [Average]
  (min, avg, max) = (4.648, 4.722, 4.760), stdev = 0.064
  CI (99.9%): [3.557, 5.887] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.400 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.012 ms/op
Iteration   1: 3.690 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.350 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   6.953 ms/op
                 createUser·p0.999:  13.765 ms/op
                 createUser·p0.9999: 25.340 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   2: 3.740 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  9.594 ms/op
                 createUser·p0.9999: 29.196 ms/op
                 createUser·p1.00:   29.458 ms/op

Iteration   3: 3.767 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.849 ms/op
                 createUser·p0.999:  12.549 ms/op
                 createUser·p0.9999: 33.914 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 257534
  mean =      3.732 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12508 
    [ 2.500,  5.000) = 232829 
    [ 5.000,  7.500) = 10632 
    [ 7.500, 10.000) = 1138 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.350 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     11.804 ms/op
     p(99.9900) =     31.981 ms/op
     p(99.9990) =     34.238 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 5.110 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.825 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.694 ±(99.9%) 0.010 ms/op
Iteration   1: 3.660 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   3.596 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   6.273 ms/op
                 existUser·p0.999:  9.987 ms/op
                 existUser·p0.9999: 15.008 ms/op
                 existUser·p1.00:   15.647 ms/op

Iteration   2: 3.626 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  9.601 ms/op
                 existUser·p0.9999: 23.921 ms/op
                 existUser·p1.00:   24.412 ms/op

Iteration   3: 3.546 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.285 ms/op
                 existUser·p0.999:  12.190 ms/op
                 existUser·p0.9999: 32.963 ms/op
                 existUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 265795
  mean =      3.610 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10792 
    [ 2.500,  5.000) = 246419 
    [ 5.000,  7.500) = 7364 
    [ 7.500, 10.000) = 914 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     11.144 ms/op
     p(99.9900) =     32.126 ms/op
     p(99.9990) =     33.271 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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
# Warmup Iteration   1: 5.640 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.010 ms/op
Iteration   1: 3.902 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   5.194 ms/op
                 getUser·p0.99:   7.487 ms/op
                 getUser·p0.999:  10.893 ms/op
                 getUser·p0.9999: 14.624 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   2: 3.773 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   3.686 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   6.368 ms/op
                 getUser·p0.999:  8.880 ms/op
                 getUser·p0.9999: 16.368 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 3.838 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  9.740 ms/op
                 getUser·p0.9999: 19.420 ms/op
                 getUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 250349
  mean =      3.837 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 5690 
    [ 2.500,  3.750) = 122269 
    [ 3.750,  5.000) = 108690 
    [ 5.000,  6.250) = 9943 
    [ 6.250,  7.500) = 2094 
    [ 7.500,  8.750) = 973 
    [ 8.750, 10.000) = 383 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     10.158 ms/op
     p(99.9900) =     18.871 ms/op
     p(99.9990) =     19.710 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 6.285 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.290 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.907 ±(99.9%) 0.016 ms/op
Iteration   1: 4.763 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.704 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.808 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  15.708 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   2: 4.753 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.673 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.743 ms/op
                 listUser·p0.95:   6.594 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  16.417 ms/op
                 listUser·p0.9999: 18.457 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   3: 4.673 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.693 ms/op
                 listUser·p0.95:   6.685 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  20.873 ms/op
                 listUser·p0.9999: 23.510 ms/op
                 listUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202887
  mean =      4.729 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 254 
    [ 2.500,  5.000) = 156834 
    [ 5.000,  7.500) = 40424 
    [ 7.500, 10.000) = 4613 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.751 ms/op
     p(95.0000) =      6.660 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     22.408 ms/op
     p(99.9990) =     24.602 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.421 ± 2.345  ops/ms
ClientGrpc.existUser                       thrpt       3   8.699 ± 4.878  ops/ms
ClientGrpc.getUser                         thrpt       3   8.479 ± 1.794  ops/ms
ClientGrpc.listUser                        thrpt       3   6.620 ± 2.449  ops/ms
ClientGrpc.createUser                       avgt       3   3.782 ± 0.859   ms/op
ClientGrpc.existUser                        avgt       3   3.529 ± 1.461   ms/op
ClientGrpc.getUser                          avgt       3   3.769 ± 0.191   ms/op
ClientGrpc.listUser                         avgt       3   4.722 ± 1.165   ms/op
ClientGrpc.createUser                     sample  257534   3.732 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.350           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.964           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.586           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.804           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.981           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.275           ms/op
ClientGrpc.existUser                      sample  265795   3.610 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.857           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.735           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.226           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.144           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.126           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.391           ms/op
ClientGrpc.getUser                        sample  250349   3.837 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.897           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.628           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.063           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.824           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.158           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.871           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.825           ms/op
ClientGrpc.listUser                       sample  202887   4.729 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.916           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.547           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.660           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.520           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.777           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.408           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.674           ms/op
