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
# Warmup Iteration   1: 1.491 ops/ms
# Warmup Iteration   2: 3.986 ops/ms
# Warmup Iteration   3: 5.904 ops/ms
Iteration   1: 6.192 ops/ms
Iteration   2: 6.350 ops/ms
Iteration   3: 6.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.301 ±(99.9%) 1.718 ops/ms [Average]
  (min, avg, max) = (6.192, 6.301, 6.360), stdev = 0.094
  CI (99.9%): [4.583, 8.019] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 3.551 ops/ms
# Warmup Iteration   2: 5.872 ops/ms
# Warmup Iteration   3: 6.439 ops/ms
Iteration   1: 6.665 ops/ms
Iteration   2: 6.664 ops/ms
Iteration   3: 6.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.664 ±(99.9%) 0.014 ops/ms [Average]
  (min, avg, max) = (6.664, 6.664, 6.665), stdev = 0.001
  CI (99.9%): [6.651, 6.678] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.259 ops/ms
# Warmup Iteration   2: 5.803 ops/ms
# Warmup Iteration   3: 6.359 ops/ms
Iteration   1: 6.197 ops/ms
Iteration   2: 6.388 ops/ms
Iteration   3: 6.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.302 ±(99.9%) 1.774 ops/ms [Average]
  (min, avg, max) = (6.197, 6.302, 6.388), stdev = 0.097
  CI (99.9%): [4.528, 8.076] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.931 ops/ms
# Warmup Iteration   2: 4.111 ops/ms
# Warmup Iteration   3: 4.762 ops/ms
Iteration   1: 4.872 ops/ms
Iteration   2: 5.047 ops/ms
Iteration   3: 5.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.003 ±(99.9%) 2.098 ops/ms [Average]
  (min, avg, max) = (4.872, 5.003, 5.089), stdev = 0.115
  CI (99.9%): [2.904, 7.101] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 8.653 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.376 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.969 ±(99.9%) 0.005 ms/op
Iteration   1: 5.090 ±(99.9%) 0.004 ms/op
Iteration   2: 5.212 ±(99.9%) 0.004 ms/op
Iteration   3: 5.084 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.129 ±(99.9%) 1.318 ms/op [Average]
  (min, avg, max) = (5.084, 5.129, 5.212), stdev = 0.072
  CI (99.9%): [3.811, 6.446] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.454 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.183 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.933 ±(99.9%) 0.010 ms/op
Iteration   1: 4.907 ±(99.9%) 0.004 ms/op
Iteration   2: 4.884 ±(99.9%) 0.005 ms/op
Iteration   3: 4.842 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.878 ±(99.9%) 0.596 ms/op [Average]
  (min, avg, max) = (4.842, 4.878, 4.907), stdev = 0.033
  CI (99.9%): [4.282, 5.474] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.125 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.590 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.193 ±(99.9%) 0.009 ms/op
Iteration   1: 5.119 ±(99.9%) 0.005 ms/op
Iteration   2: 4.986 ±(99.9%) 0.013 ms/op
Iteration   3: 5.046 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  5.051 ±(99.9%) 1.213 ms/op [Average]
  (min, avg, max) = (4.986, 5.051, 5.119), stdev = 0.066
  CI (99.9%): [3.838, 6.264] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 8.874 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 7.300 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.621 ±(99.9%) 0.029 ms/op
Iteration   1: 6.474 ±(99.9%) 0.014 ms/op
Iteration   2: 6.636 ±(99.9%) 0.017 ms/op
Iteration   3: 6.330 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.480 ±(99.9%) 2.794 ms/op [Average]
  (min, avg, max) = (6.330, 6.480, 6.636), stdev = 0.153
  CI (99.9%): [3.686, 9.274] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 8.474 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 5.659 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.124 ±(99.9%) 0.018 ms/op
Iteration   1: 5.149 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   4.964 ms/op
                 createUser·p0.90:   6.619 ms/op
                 createUser·p0.95:   7.307 ms/op
                 createUser·p0.99:   9.273 ms/op
                 createUser·p0.999:  18.083 ms/op
                 createUser·p0.9999: 20.806 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   2: 5.185 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   4.956 ms/op
                 createUser·p0.90:   6.742 ms/op
                 createUser·p0.95:   7.496 ms/op
                 createUser·p0.99:   9.929 ms/op
                 createUser·p0.999:  17.531 ms/op
                 createUser·p0.9999: 21.986 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   3: 5.301 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   5.112 ms/op
                 createUser·p0.90:   6.799 ms/op
                 createUser·p0.95:   7.479 ms/op
                 createUser·p0.99:   10.300 ms/op
                 createUser·p0.999:  22.020 ms/op
                 createUser·p0.9999: 38.339 ms/op
                 createUser·p1.00:   38.928 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 184162
  mean =      5.211 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1552 
    [ 2.500,  5.000) = 89938 
    [ 5.000,  7.500) = 84032 
    [ 7.500, 10.000) = 6980 
    [10.000, 12.500) = 979 
    [12.500, 15.000) = 323 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.726 ms/op
     p(95.0000) =      7.430 ms/op
     p(99.0000) =      9.798 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     36.580 ms/op
     p(99.9990) =     38.873 ms/op
     p(99.9999) =     38.928 ms/op
    p(100.0000) =     38.928 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 8.066 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 5.472 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.940 ±(99.9%) 0.017 ms/op
Iteration   1: 4.773 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   4.579 ms/op
                 existUser·p0.90:   6.062 ms/op
                 existUser·p0.95:   6.709 ms/op
                 existUser·p0.99:   8.602 ms/op
                 existUser·p0.999:  15.188 ms/op
                 existUser·p0.9999: 22.662 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   2: 4.799 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   4.645 ms/op
                 existUser·p0.90:   6.128 ms/op
                 existUser·p0.95:   6.717 ms/op
                 existUser·p0.99:   8.339 ms/op
                 existUser·p0.999:  11.584 ms/op
                 existUser·p0.9999: 18.373 ms/op
                 existUser·p1.00:   19.071 ms/op

Iteration   3: 4.945 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   4.710 ms/op
                 existUser·p0.90:   6.480 ms/op
                 existUser·p0.95:   7.242 ms/op
                 existUser·p0.99:   9.535 ms/op
                 existUser·p0.999:  15.335 ms/op
                 existUser·p0.9999: 24.038 ms/op
                 existUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 198353
  mean =      4.838 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2259 
    [ 2.500,  5.000) = 123897 
    [ 5.000,  7.500) = 66586 
    [ 7.500, 10.000) = 4656 
    [10.000, 12.500) = 532 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      6.226 ms/op
     p(95.0000) =      6.881 ms/op
     p(99.0000) =      8.839 ms/op
     p(99.9000) =     14.526 ms/op
     p(99.9900) =     23.495 ms/op
     p(99.9990) =     24.643 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 7.871 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 5.492 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.093 ±(99.9%) 0.017 ms/op
Iteration   1: 4.986 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   4.809 ms/op
                 getUser·p0.90:   6.406 ms/op
                 getUser·p0.95:   7.152 ms/op
                 getUser·p0.99:   9.093 ms/op
                 getUser·p0.999:  13.364 ms/op
                 getUser·p0.9999: 34.472 ms/op
                 getUser·p1.00:   34.931 ms/op

Iteration   2: 5.184 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   5.030 ms/op
                 getUser·p0.90:   6.627 ms/op
                 getUser·p0.95:   7.348 ms/op
                 getUser·p0.99:   9.601 ms/op
                 getUser·p0.999:  14.726 ms/op
                 getUser·p0.9999: 28.235 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   3: 5.289 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.783 ms/op
                 getUser·p0.95:   7.515 ms/op
                 getUser·p0.99:   9.716 ms/op
                 getUser·p0.999:  15.959 ms/op
                 getUser·p0.9999: 31.488 ms/op
                 getUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 186356
  mean =      5.150 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1776 
    [ 2.500,  5.000) = 93649 
    [ 5.000,  7.500) = 82848 
    [ 7.500, 10.000) = 6773 
    [10.000, 12.500) = 974 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.619 ms/op
     p(95.0000) =      7.340 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     13.822 ms/op
     p(99.9900) =     33.415 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.045 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 7.267 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.882 ±(99.9%) 0.031 ms/op
Iteration   1: 6.890 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.561 ms/op
                 listUser·p0.50:   6.300 ms/op
                 listUser·p0.90:   9.929 ms/op
                 listUser·p0.95:   11.387 ms/op
                 listUser·p0.99:   14.582 ms/op
                 listUser·p0.999:  18.798 ms/op
                 listUser·p0.9999: 21.606 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   2: 6.520 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   6.107 ms/op
                 listUser·p0.90:   8.765 ms/op
                 listUser·p0.95:   9.912 ms/op
                 listUser·p0.99:   12.812 ms/op
                 listUser·p0.999:  20.151 ms/op
                 listUser·p0.9999: 22.598 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 6.532 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   6.054 ms/op
                 listUser·p0.90:   9.044 ms/op
                 listUser·p0.95:   10.437 ms/op
                 listUser·p0.99:   13.795 ms/op
                 listUser·p0.999:  22.974 ms/op
                 listUser·p0.9999: 26.709 ms/op
                 listUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 144415
  mean =      6.643 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 23402 
    [ 5.000,  7.500) = 86428 
    [ 7.500, 10.000) = 24631 
    [10.000, 12.500) = 7147 
    [12.500, 15.000) = 1830 
    [15.000, 17.500) = 566 
    [17.500, 20.000) = 171 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      6.144 ms/op
     p(90.0000) =      9.257 ms/op
     p(95.0000) =     10.633 ms/op
     p(99.0000) =     13.926 ms/op
     p(99.9000) =     20.532 ms/op
     p(99.9900) =     25.938 ms/op
     p(99.9990) =     27.817 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.301 ± 1.718  ops/ms
ClientGrpc.existUser                       thrpt       3   6.664 ± 0.014  ops/ms
ClientGrpc.getUser                         thrpt       3   6.302 ± 1.774  ops/ms
ClientGrpc.listUser                        thrpt       3   5.003 ± 2.098  ops/ms
ClientGrpc.createUser                       avgt       3   5.129 ± 1.318   ms/op
ClientGrpc.existUser                        avgt       3   4.878 ± 0.596   ms/op
ClientGrpc.getUser                          avgt       3   5.051 ± 1.213   ms/op
ClientGrpc.listUser                         avgt       3   6.480 ± 2.794   ms/op
ClientGrpc.createUser                     sample  184162   5.211 ± 0.011   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.991           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           5.014           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.726           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.430           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.798           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          18.121           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          36.580           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          38.928           ms/op
ClientGrpc.existUser                      sample  198353   4.838 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.057           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.645           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           6.226           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.881           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.839           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.526           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.495           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.707           ms/op
ClientGrpc.getUser                        sample  186356   5.150 ± 0.011   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.309           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.964           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.619           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.340           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.486           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.822           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.415           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.931           ms/op
ClientGrpc.listUser                       sample  144415   6.643 ± 0.018   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.376           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           6.144           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           9.257           ms/op
ClientGrpc.listUser:listUser·p0.95        sample          10.633           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          13.926           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.532           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.938           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.443           ms/op
