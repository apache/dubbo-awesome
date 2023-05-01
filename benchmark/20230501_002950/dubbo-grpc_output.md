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
# Warmup Iteration   1: 3.963 ops/ms
# Warmup Iteration   2: 8.761 ops/ms
# Warmup Iteration   3: 9.897 ops/ms
Iteration   1: 10.377 ops/ms
Iteration   2: 10.588 ops/ms
Iteration   3: 10.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.483 ±(99.9%) 1.927 ops/ms [Average]
  (min, avg, max) = (10.377, 10.483, 10.588), stdev = 0.106
  CI (99.9%): [8.556, 12.410] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.519 ops/ms
# Warmup Iteration   2: 10.595 ops/ms
# Warmup Iteration   3: 11.037 ops/ms
Iteration   1: 11.265 ops/ms
Iteration   2: 10.922 ops/ms
Iteration   3: 10.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.986 ±(99.9%) 4.611 ops/ms [Average]
  (min, avg, max) = (10.772, 10.986, 11.265), stdev = 0.253
  CI (99.9%): [6.375, 15.597] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.757 ops/ms
# Warmup Iteration   2: 10.099 ops/ms
# Warmup Iteration   3: 10.540 ops/ms
Iteration   1: 10.539 ops/ms
Iteration   2: 10.565 ops/ms
Iteration   3: 10.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.577 ±(99.9%) 0.828 ops/ms [Average]
  (min, avg, max) = (10.539, 10.577, 10.628), stdev = 0.045
  CI (99.9%): [9.749, 11.406] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.608 ops/ms
# Warmup Iteration   2: 7.631 ops/ms
# Warmup Iteration   3: 7.927 ops/ms
Iteration   1: 7.801 ops/ms
Iteration   2: 8.056 ops/ms
Iteration   3: 8.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.032 ±(99.9%) 4.014 ops/ms [Average]
  (min, avg, max) = (7.801, 8.032, 8.240), stdev = 0.220
  CI (99.9%): [4.018, 12.047] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.533 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.005 ms/op
Iteration   1: 3.058 ±(99.9%) 0.003 ms/op
Iteration   2: 3.030 ±(99.9%) 0.002 ms/op
Iteration   3: 3.042 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.043 ±(99.9%) 0.253 ms/op [Average]
  (min, avg, max) = (3.030, 3.043, 3.058), stdev = 0.014
  CI (99.9%): [2.791, 3.296] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.988 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.003 ms/op
Iteration   1: 2.915 ±(99.9%) 0.004 ms/op
Iteration   2: 2.882 ±(99.9%) 0.003 ms/op
Iteration   3: 2.940 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.912 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (2.882, 2.912, 2.940), stdev = 0.029
  CI (99.9%): [2.377, 3.447] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.302 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.002 ms/op
Iteration   1: 3.122 ±(99.9%) 0.002 ms/op
Iteration   2: 3.031 ±(99.9%) 0.003 ms/op
Iteration   3: 3.044 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.066 ±(99.9%) 0.898 ms/op [Average]
  (min, avg, max) = (3.031, 3.066, 3.122), stdev = 0.049
  CI (99.9%): [2.168, 3.963] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.386 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.015 ms/op
Iteration   1: 4.040 ±(99.9%) 0.013 ms/op
Iteration   2: 3.985 ±(99.9%) 0.019 ms/op
Iteration   3: 3.935 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.987 ±(99.9%) 0.961 ms/op [Average]
  (min, avg, max) = (3.935, 3.987, 4.040), stdev = 0.053
  CI (99.9%): [3.026, 4.948] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.432 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.006 ms/op
Iteration   1: 3.022 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.543 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.840 ms/op
                 createUser·p0.9999: 13.350 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  6.963 ms/op
                 createUser·p0.9999: 15.385 ms/op
                 createUser·p1.00:   16.482 ms/op

Iteration   3: 3.063 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  14.034 ms/op
                 createUser·p0.9999: 18.846 ms/op
                 createUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313639
  mean =      3.061 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 401 
    [ 1.250,  2.500) = 21119 
    [ 2.500,  3.750) = 271578 
    [ 3.750,  5.000) = 19310 
    [ 5.000,  6.250) = 531 
    [ 6.250,  7.500) = 292 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     19.169 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.984 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.006 ms/op
Iteration   1: 2.859 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  6.758 ms/op
                 existUser·p0.9999: 13.213 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   2: 2.915 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  6.653 ms/op
                 existUser·p0.9999: 17.629 ms/op
                 existUser·p1.00:   18.219 ms/op

Iteration   3: 2.950 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.412 ms/op
                 existUser·p0.9999: 27.962 ms/op
                 existUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330157
  mean =      2.907 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41774 
    [ 2.500,  5.000) = 287037 
    [ 5.000,  7.500) = 1107 
    [ 7.500, 10.000) = 78 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      6.872 ms/op
     p(99.9900) =     22.642 ms/op
     p(99.9990) =     28.246 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.384 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
Iteration   1: 3.038 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  8.880 ms/op
                 getUser·p0.9999: 16.972 ms/op
                 getUser·p1.00:   19.202 ms/op

Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.952 ms/op
                 getUser·p0.9999: 19.199 ms/op
                 getUser·p1.00:   19.595 ms/op

Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  7.282 ms/op
                 getUser·p0.9999: 20.775 ms/op
                 getUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316826
  mean =      3.030 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20013 
    [ 2.500,  5.000) = 295345 
    [ 5.000,  7.500) = 1162 
    [ 7.500, 10.000) = 109 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.414 ms/op
     p(99.9900) =     20.239 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 5.696 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.207 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.012 ms/op
Iteration   1: 3.970 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  13.506 ms/op
                 listUser·p0.9999: 19.364 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   2: 3.978 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  15.779 ms/op
                 listUser·p0.9999: 23.166 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   3: 3.987 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  15.860 ms/op
                 listUser·p0.9999: 19.562 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241148
  mean =      3.978 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2148 
    [ 2.500,  5.000) = 215893 
    [ 5.000,  7.500) = 21702 
    [ 7.500, 10.000) = 936 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     21.656 ms/op
     p(99.9990) =     23.350 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.483 ± 1.927  ops/ms
ClientGrpc.existUser                       thrpt       3  10.986 ± 4.611  ops/ms
ClientGrpc.getUser                         thrpt       3  10.577 ± 0.828  ops/ms
ClientGrpc.listUser                        thrpt       3   8.032 ± 4.014  ops/ms
ClientGrpc.createUser                       avgt       3   3.043 ± 0.253   ms/op
ClientGrpc.existUser                        avgt       3   2.912 ± 0.535   ms/op
ClientGrpc.getUser                          avgt       3   3.066 ± 0.898   ms/op
ClientGrpc.listUser                         avgt       3   3.987 ± 0.961   ms/op
ClientGrpc.createUser                     sample  313639   3.061 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.543           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.798           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.055           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.890           ms/op
ClientGrpc.existUser                      sample  330157   2.907 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.588           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.872           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.642           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.312           ms/op
ClientGrpc.getUser                        sample  316826   3.030 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.712           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.414           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.239           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.808           ms/op
ClientGrpc.listUser                       sample  241148   3.978 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.145           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.762           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.656           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.396           ms/op
