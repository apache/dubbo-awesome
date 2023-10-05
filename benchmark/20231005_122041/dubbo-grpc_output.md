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
# Warmup Iteration   1: 2.095 ops/ms
# Warmup Iteration   2: 4.999 ops/ms
# Warmup Iteration   3: 6.736 ops/ms
Iteration   1: 6.628 ops/ms
Iteration   2: 6.917 ops/ms
Iteration   3: 6.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.839 ±(99.9%) 3.374 ops/ms [Average]
  (min, avg, max) = (6.628, 6.839, 6.972), stdev = 0.185
  CI (99.9%): [3.465, 10.213] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.538 ops/ms
# Warmup Iteration   2: 6.804 ops/ms
# Warmup Iteration   3: 7.199 ops/ms
Iteration   1: 7.261 ops/ms
Iteration   2: 7.225 ops/ms
Iteration   3: 7.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.272 ±(99.9%) 0.980 ops/ms [Average]
  (min, avg, max) = (7.225, 7.272, 7.331), stdev = 0.054
  CI (99.9%): [6.292, 8.253] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.719 ops/ms
# Warmup Iteration   2: 6.266 ops/ms
# Warmup Iteration   3: 6.696 ops/ms
Iteration   1: 6.986 ops/ms
Iteration   2: 6.899 ops/ms
Iteration   3: 6.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.958 ±(99.9%) 0.919 ops/ms [Average]
  (min, avg, max) = (6.899, 6.958, 6.987), stdev = 0.050
  CI (99.9%): [6.038, 7.877] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.473 ops/ms
# Warmup Iteration   2: 5.002 ops/ms
# Warmup Iteration   3: 5.418 ops/ms
Iteration   1: 5.605 ops/ms
Iteration   2: 5.537 ops/ms
Iteration   3: 5.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.571 ±(99.9%) 0.625 ops/ms [Average]
  (min, avg, max) = (5.537, 5.571, 5.605), stdev = 0.034
  CI (99.9%): [4.946, 6.197] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.230 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.916 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.731 ±(99.9%) 0.005 ms/op
Iteration   1: 4.446 ±(99.9%) 0.005 ms/op
Iteration   2: 4.454 ±(99.9%) 0.004 ms/op
Iteration   3: 4.508 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.469 ±(99.9%) 0.618 ms/op [Average]
  (min, avg, max) = (4.446, 4.469, 4.508), stdev = 0.034
  CI (99.9%): [3.851, 5.088] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.049 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.665 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.418 ±(99.9%) 0.003 ms/op
Iteration   1: 4.241 ±(99.9%) 0.007 ms/op
Iteration   2: 4.327 ±(99.9%) 0.004 ms/op
Iteration   3: 4.282 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.283 ±(99.9%) 0.787 ms/op [Average]
  (min, avg, max) = (4.241, 4.283, 4.327), stdev = 0.043
  CI (99.9%): [3.497, 5.070] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.277 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.803 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.647 ±(99.9%) 0.004 ms/op
Iteration   1: 4.622 ±(99.9%) 0.003 ms/op
Iteration   2: 4.573 ±(99.9%) 0.005 ms/op
Iteration   3: 4.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.560 ±(99.9%) 1.278 ms/op [Average]
  (min, avg, max) = (4.484, 4.560, 4.622), stdev = 0.070
  CI (99.9%): [3.282, 5.838] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.154 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 6.209 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.727 ±(99.9%) 0.023 ms/op
Iteration   1: 5.867 ±(99.9%) 0.018 ms/op
Iteration   2: 5.688 ±(99.9%) 0.025 ms/op
Iteration   3: 5.916 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.824 ±(99.9%) 2.186 ms/op [Average]
  (min, avg, max) = (5.688, 5.824, 5.916), stdev = 0.120
  CI (99.9%): [3.638, 8.009] (assumes normal distribution)


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
# Warmup Iteration   1: 7.556 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.003 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.745 ±(99.9%) 0.015 ms/op
Iteration   1: 4.670 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   4.522 ms/op
                 createUser·p0.90:   6.078 ms/op
                 createUser·p0.95:   6.709 ms/op
                 createUser·p0.99:   8.913 ms/op
                 createUser·p0.999:  12.698 ms/op
                 createUser·p0.9999: 19.643 ms/op
                 createUser·p1.00:   20.087 ms/op

Iteration   2: 4.593 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   4.440 ms/op
                 createUser·p0.90:   5.784 ms/op
                 createUser·p0.95:   6.357 ms/op
                 createUser·p0.99:   8.282 ms/op
                 createUser·p0.999:  12.714 ms/op
                 createUser·p0.9999: 21.004 ms/op
                 createUser·p1.00:   21.037 ms/op

Iteration   3: 4.590 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   4.415 ms/op
                 createUser·p0.90:   5.743 ms/op
                 createUser·p0.95:   6.423 ms/op
                 createUser·p0.99:   8.950 ms/op
                 createUser·p0.999:  16.608 ms/op
                 createUser·p0.9999: 22.285 ms/op
                 createUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 207771
  mean =      4.618 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4011 
    [ 2.500,  5.000) = 147237 
    [ 5.000,  7.500) = 52127 
    [ 7.500, 10.000) = 3426 
    [10.000, 12.500) = 630 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.882 ms/op
     p(95.0000) =      6.504 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     22.706 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.782 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.714 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.366 ±(99.9%) 0.013 ms/op
Iteration   1: 4.371 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   4.227 ms/op
                 existUser·p0.90:   5.579 ms/op
                 existUser·p0.95:   6.119 ms/op
                 existUser·p0.99:   8.053 ms/op
                 existUser·p0.999:  13.418 ms/op
                 existUser·p0.9999: 18.057 ms/op
                 existUser·p1.00:   18.874 ms/op

Iteration   2: 4.239 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   4.100 ms/op
                 existUser·p0.90:   5.317 ms/op
                 existUser·p0.95:   5.841 ms/op
                 existUser·p0.99:   8.028 ms/op
                 existUser·p0.999:  10.764 ms/op
                 existUser·p0.9999: 17.662 ms/op
                 existUser·p1.00:   18.579 ms/op

Iteration   3: 4.281 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   4.157 ms/op
                 existUser·p0.90:   5.358 ms/op
                 existUser·p0.95:   5.939 ms/op
                 existUser·p0.99:   7.843 ms/op
                 existUser·p0.999:  11.278 ms/op
                 existUser·p0.9999: 18.780 ms/op
                 existUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 223273
  mean =      4.296 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7568 
    [ 2.500,  5.000) = 177361 
    [ 5.000,  7.500) = 35217 
    [ 7.500, 10.000) = 2487 
    [10.000, 12.500) = 447 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      4.162 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      7.971 ms/op
     p(99.9000) =     11.715 ms/op
     p(99.9900) =     18.405 ms/op
     p(99.9990) =     20.778 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.806 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.886 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.677 ±(99.9%) 0.015 ms/op
Iteration   1: 4.685 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   4.473 ms/op
                 getUser·p0.90:   5.947 ms/op
                 getUser·p0.95:   6.693 ms/op
                 getUser·p0.99:   9.601 ms/op
                 getUser·p0.999:  16.396 ms/op
                 getUser·p0.9999: 80.216 ms/op
                 getUser·p1.00:   84.148 ms/op

Iteration   2: 4.675 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   4.547 ms/op
                 getUser·p0.90:   5.890 ms/op
                 getUser·p0.95:   6.471 ms/op
                 getUser·p0.99:   9.224 ms/op
                 getUser·p0.999:  16.089 ms/op
                 getUser·p0.9999: 30.883 ms/op
                 getUser·p1.00:   31.326 ms/op

Iteration   3: 4.536 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   4.399 ms/op
                 getUser·p0.90:   5.669 ms/op
                 getUser·p0.95:   6.193 ms/op
                 getUser·p0.99:   8.206 ms/op
                 getUser·p0.999:  11.858 ms/op
                 getUser·p0.9999: 21.557 ms/op
                 getUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 207307
  mean =      4.631 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 150774 
    [ 5.000, 10.000) = 55204 
    [10.000, 15.000) = 1051 
    [15.000, 20.000) = 155 
    [20.000, 25.000) = 74 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 15 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 1 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 2 
    [65.000, 70.000) = 3 
    [70.000, 75.000) = 1 
    [75.000, 80.000) = 7 
    [80.000, 85.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      6.447 ms/op
     p(99.0000) =      9.093 ms/op
     p(99.9000) =     15.806 ms/op
     p(99.9900) =     74.983 ms/op
     p(99.9990) =     81.946 ms/op
     p(99.9999) =     84.148 ms/op
    p(100.0000) =     84.148 ms/op


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
# Warmup Iteration   1: 9.045 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 6.342 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 6.112 ±(99.9%) 0.026 ms/op
Iteration   1: 6.025 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   5.579 ms/op
                 listUser·p0.90:   8.282 ms/op
                 listUser·p0.95:   9.355 ms/op
                 listUser·p0.99:   11.977 ms/op
                 listUser·p0.999:  21.133 ms/op
                 listUser·p0.9999: 25.647 ms/op
                 listUser·p1.00:   25.952 ms/op

Iteration   2: 5.945 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.751 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   8.192 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   12.009 ms/op
                 listUser·p0.999:  20.808 ms/op
                 listUser·p0.9999: 22.736 ms/op
                 listUser·p1.00:   31.228 ms/op

Iteration   3: 6.120 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   8.421 ms/op
                 listUser·p0.95:   9.486 ms/op
                 listUser·p0.99:   12.665 ms/op
                 listUser·p0.999:  21.004 ms/op
                 listUser·p0.9999: 35.556 ms/op
                 listUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 159154
  mean =      6.029 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 114 
    [ 2.500,  5.000) = 43470 
    [ 5.000,  7.500) = 90274 
    [ 7.500, 10.000) = 19745 
    [10.000, 12.500) = 4169 
    [12.500, 15.000) = 894 
    [15.000, 17.500) = 214 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      5.587 ms/op
     p(90.0000) =      8.307 ms/op
     p(95.0000) =      9.388 ms/op
     p(99.0000) =     12.190 ms/op
     p(99.9000) =     20.901 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     35.678 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.839 ± 3.374  ops/ms
ClientGrpc.existUser                       thrpt       3   7.272 ± 0.980  ops/ms
ClientGrpc.getUser                         thrpt       3   6.958 ± 0.919  ops/ms
ClientGrpc.listUser                        thrpt       3   5.571 ± 0.625  ops/ms
ClientGrpc.createUser                       avgt       3   4.469 ± 0.618   ms/op
ClientGrpc.existUser                        avgt       3   4.283 ± 0.787   ms/op
ClientGrpc.getUser                          avgt       3   4.560 ± 1.278   ms/op
ClientGrpc.listUser                         avgt       3   5.824 ± 2.186   ms/op
ClientGrpc.createUser                     sample  207771   4.618 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.022           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.882           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.504           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.716           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.762           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.365           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.952           ms/op
ClientGrpc.existUser                      sample  223273   4.296 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.815           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.423           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.972           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.971           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.715           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.405           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.103           ms/op
ClientGrpc.getUser                        sample  207307   4.631 ± 0.011   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.987           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.833           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.447           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.093           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.806           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          74.983           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          84.148           ms/op
ClientGrpc.listUser                       sample  159154   6.029 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.108           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.307           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.388           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.190           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.901           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.144           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.717           ms/op
