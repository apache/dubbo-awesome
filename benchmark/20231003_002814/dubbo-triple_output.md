# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.501 ops/ms
# Warmup Iteration   2: 3.390 ops/ms
# Warmup Iteration   3: 7.025 ops/ms
Iteration   1: 7.233 ops/ms
Iteration   2: 7.812 ops/ms
Iteration   3: 7.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.501 ±(99.9%) 5.323 ops/ms [Average]
  (min, avg, max) = (7.233, 7.501, 7.812), stdev = 0.292
  CI (99.9%): [2.178, 12.824] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.215 ops/ms
# Warmup Iteration   2: 6.200 ops/ms
# Warmup Iteration   3: 7.894 ops/ms
Iteration   1: 8.135 ops/ms
Iteration   2: 8.237 ops/ms
Iteration   3: 8.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.209 ±(99.9%) 1.173 ops/ms [Average]
  (min, avg, max) = (8.135, 8.209, 8.254), stdev = 0.064
  CI (99.9%): [7.036, 9.381] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.286 ops/ms
# Warmup Iteration   2: 6.512 ops/ms
# Warmup Iteration   3: 7.622 ops/ms
Iteration   1: 7.576 ops/ms
Iteration   2: 7.732 ops/ms
Iteration   3: 7.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.719 ±(99.9%) 2.506 ops/ms [Average]
  (min, avg, max) = (7.576, 7.719, 7.850), stdev = 0.137
  CI (99.9%): [5.213, 10.225] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.140 ops/ms
# Warmup Iteration   2: 5.887 ops/ms
# Warmup Iteration   3: 6.321 ops/ms
Iteration   1: 6.258 ops/ms
Iteration   2: 6.456 ops/ms
Iteration   3: 6.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.360 ±(99.9%) 1.810 ops/ms [Average]
  (min, avg, max) = (6.258, 6.360, 6.456), stdev = 0.099
  CI (99.9%): [4.551, 8.170] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 13.738 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.618 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.404 ±(99.9%) 0.005 ms/op
Iteration   1: 4.085 ±(99.9%) 0.008 ms/op
Iteration   2: 4.121 ±(99.9%) 0.006 ms/op
Iteration   3: 4.160 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.122 ±(99.9%) 0.692 ms/op [Average]
  (min, avg, max) = (4.085, 4.122, 4.160), stdev = 0.038
  CI (99.9%): [3.430, 4.814] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.841 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.584 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.004 ms/op
Iteration   1: 3.998 ±(99.9%) 0.004 ms/op
Iteration   2: 3.977 ±(99.9%) 0.004 ms/op
Iteration   3: 3.860 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.945 ±(99.9%) 1.363 ms/op [Average]
  (min, avg, max) = (3.860, 3.945, 3.998), stdev = 0.075
  CI (99.9%): [2.582, 5.308] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.944 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.270 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.305 ±(99.9%) 0.003 ms/op
Iteration   1: 4.154 ±(99.9%) 0.003 ms/op
Iteration   2: 4.046 ±(99.9%) 0.008 ms/op
Iteration   3: 4.218 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.139 ±(99.9%) 1.589 ms/op [Average]
  (min, avg, max) = (4.046, 4.139, 4.218), stdev = 0.087
  CI (99.9%): [2.551, 5.728] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.998 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.844 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.001 ±(99.9%) 0.007 ms/op
Iteration   1: 4.743 ±(99.9%) 0.011 ms/op
Iteration   2: 4.853 ±(99.9%) 0.008 ms/op
Iteration   3: 5.089 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.895 ±(99.9%) 3.221 ms/op [Average]
  (min, avg, max) = (4.743, 4.895, 5.089), stdev = 0.177
  CI (99.9%): [1.674, 8.116] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.387 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 4.966 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.702 ±(99.9%) 0.020 ms/op
Iteration   1: 4.100 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.737 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   7.209 ms/op
                 createUser·p0.999:  24.314 ms/op
                 createUser·p0.9999: 26.301 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   2: 4.126 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.050 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  15.647 ms/op
                 createUser·p0.9999: 30.419 ms/op
                 createUser·p1.00:   31.785 ms/op

Iteration   3: 4.136 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.901 ms/op
                 createUser·p0.50:   4.014 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   7.397 ms/op
                 createUser·p0.999:  28.639 ms/op
                 createUser·p0.9999: 33.965 ms/op
                 createUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 232608
  mean =      4.120 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 305 
    [ 2.500,  5.000) = 217066 
    [ 5.000,  7.500) = 13544 
    [ 7.500, 10.000) = 1056 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.737 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     24.379 ms/op
     p(99.9900) =     31.613 ms/op
     p(99.9990) =     34.909 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 11.113 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.349 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.011 ms/op
Iteration   1: 4.107 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.694 ms/op
                 existUser·p0.50:   3.887 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   7.979 ms/op
                 existUser·p0.999:  16.908 ms/op
                 existUser·p0.9999: 27.408 ms/op
                 existUser·p1.00:   28.410 ms/op

Iteration   2: 3.930 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.978 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   6.595 ms/op
                 existUser·p0.999:  25.028 ms/op
                 existUser·p0.9999: 28.012 ms/op
                 existUser·p1.00:   29.884 ms/op

Iteration   3: 4.112 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.810 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   4.792 ms/op
                 existUser·p0.95:   5.136 ms/op
                 existUser·p0.99:   7.164 ms/op
                 existUser·p0.999:  20.677 ms/op
                 existUser·p0.9999: 30.384 ms/op
                 existUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 236810
  mean =      4.048 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 246 
    [ 2.500,  5.000) = 222550 
    [ 5.000,  7.500) = 11561 
    [ 7.500, 10.000) = 1730 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 107 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     20.677 ms/op
     p(99.9900) =     29.721 ms/op
     p(99.9990) =     31.846 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.379 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 4.689 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.235 ±(99.9%) 0.012 ms/op
Iteration   1: 4.230 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.673 ms/op
                 getUser·p0.50:   4.006 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.947 ms/op
                 getUser·p0.99:   9.552 ms/op
                 getUser·p0.999:  18.547 ms/op
                 getUser·p0.9999: 21.478 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   2: 4.039 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.969 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  15.745 ms/op
                 getUser·p0.9999: 21.793 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   3: 4.082 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  21.602 ms/op
                 getUser·p0.9999: 23.828 ms/op
                 getUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233077
  mean =      4.115 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 118 
    [ 2.500,  5.000) = 219972 
    [ 5.000,  7.500) = 10020 
    [ 7.500, 10.000) = 1976 
    [10.000, 12.500) = 530 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     18.642 ms/op
     p(99.9900) =     23.026 ms/op
     p(99.9990) =     24.643 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.375 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 5.888 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.235 ±(99.9%) 0.019 ms/op
Iteration   1: 5.026 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.087 ms/op
                 listUser·p0.50:   4.891 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  26.424 ms/op
                 listUser·p0.9999: 32.449 ms/op
                 listUser·p1.00:   33.227 ms/op

Iteration   2: 5.167 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.912 ms/op
                 listUser·p0.50:   5.038 ms/op
                 listUser·p0.90:   5.644 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   9.294 ms/op
                 listUser·p0.999:  21.914 ms/op
                 listUser·p0.9999: 25.657 ms/op
                 listUser·p1.00:   27.361 ms/op

Iteration   3: 4.863 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.761 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  19.112 ms/op
                 listUser·p0.9999: 29.468 ms/op
                 listUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 191222
  mean =      5.015 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 114593 
    [ 5.000,  7.500) = 72813 
    [ 7.500, 10.000) = 2630 
    [10.000, 12.500) = 439 
    [12.500, 15.000) = 246 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.087 ms/op
     p(50.0000) =      4.891 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     23.061 ms/op
     p(99.9900) =     30.737 ms/op
     p(99.9990) =     33.047 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.501 ± 5.323  ops/ms
ClientPb.existUser                       thrpt       3   8.209 ± 1.173  ops/ms
ClientPb.getUser                         thrpt       3   7.719 ± 2.506  ops/ms
ClientPb.listUser                        thrpt       3   6.360 ± 1.810  ops/ms
ClientPb.createUser                       avgt       3   4.122 ± 0.692   ms/op
ClientPb.existUser                        avgt       3   3.945 ± 1.363   ms/op
ClientPb.getUser                          avgt       3   4.139 ± 1.589   ms/op
ClientPb.listUser                         avgt       3   4.895 ± 3.221   ms/op
ClientPb.createUser                     sample  232608   4.120 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.737           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.751           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.169           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.094           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.379           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.613           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.962           ms/op
ClientPb.existUser                      sample  236810   4.048 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.694           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.669           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.120           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.545           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.677           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.721           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.389           ms/op
ClientPb.getUser                        sample  233077   4.115 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.044           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.120           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.897           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.642           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.026           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.035           ms/op
ClientPb.listUser                       sample  191222   5.015 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.087           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.061           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.737           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.227           ms/op
