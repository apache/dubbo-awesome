# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.796 ops/ms
# Warmup Iteration   2: 6.301 ops/ms
# Warmup Iteration   3: 9.032 ops/ms
Iteration   1: 9.615 ops/ms
Iteration   2: 10.037 ops/ms
Iteration   3: 10.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.919 ±(99.9%) 4.847 ops/ms [Average]
  (min, avg, max) = (9.615, 9.919, 10.106), stdev = 0.266
  CI (99.9%): [5.072, 14.766] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.520 ops/ms
# Warmup Iteration   2: 9.570 ops/ms
# Warmup Iteration   3: 9.853 ops/ms
Iteration   1: 10.216 ops/ms
Iteration   2: 10.137 ops/ms
Iteration   3: 10.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.258 ±(99.9%) 2.664 ops/ms [Average]
  (min, avg, max) = (10.137, 10.258, 10.420), stdev = 0.146
  CI (99.9%): [7.593, 12.922] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.658 ops/ms
# Warmup Iteration   2: 9.003 ops/ms
# Warmup Iteration   3: 9.515 ops/ms
Iteration   1: 10.062 ops/ms
Iteration   2: 9.823 ops/ms
Iteration   3: 9.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.919 ±(99.9%) 2.294 ops/ms [Average]
  (min, avg, max) = (9.823, 9.919, 10.062), stdev = 0.126
  CI (99.9%): [7.626, 12.213] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.162 ops/ms
# Warmup Iteration   2: 7.797 ops/ms
# Warmup Iteration   3: 8.330 ops/ms
Iteration   1: 8.495 ops/ms
Iteration   2: 8.394 ops/ms
Iteration   3: 8.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.510 ±(99.9%) 2.269 ops/ms [Average]
  (min, avg, max) = (8.394, 8.510, 8.641), stdev = 0.124
  CI (99.9%): [6.241, 10.779] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.829 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.005 ms/op
Iteration   1: 3.135 ±(99.9%) 0.007 ms/op
Iteration   2: 3.191 ±(99.9%) 0.006 ms/op
Iteration   3: 3.059 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.128 ±(99.9%) 1.208 ms/op [Average]
  (min, avg, max) = (3.059, 3.128, 3.191), stdev = 0.066
  CI (99.9%): [1.920, 4.336] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.716 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.002 ms/op
Iteration   1: 3.079 ±(99.9%) 0.007 ms/op
Iteration   2: 3.082 ±(99.9%) 0.006 ms/op
Iteration   3: 3.028 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.063 ±(99.9%) 0.555 ms/op [Average]
  (min, avg, max) = (3.028, 3.063, 3.082), stdev = 0.030
  CI (99.9%): [2.508, 3.618] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.535 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.453 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.006 ms/op
Iteration   1: 3.249 ±(99.9%) 0.005 ms/op
Iteration   2: 3.281 ±(99.9%) 0.006 ms/op
Iteration   3: 3.108 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.213 ±(99.9%) 1.684 ms/op [Average]
  (min, avg, max) = (3.108, 3.213, 3.281), stdev = 0.092
  CI (99.9%): [1.529, 4.897] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.178 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.004 ms/op
Iteration   1: 3.653 ±(99.9%) 0.010 ms/op
Iteration   2: 3.859 ±(99.9%) 0.005 ms/op
Iteration   3: 3.655 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.722 ±(99.9%) 2.161 ms/op [Average]
  (min, avg, max) = (3.653, 3.722, 3.859), stdev = 0.118
  CI (99.9%): [1.561, 5.883] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.636 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.591 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.008 ms/op
Iteration   1: 3.271 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.681 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  10.682 ms/op
                 createUser·p0.9999: 25.173 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   2: 3.226 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  18.734 ms/op
                 createUser·p0.9999: 26.381 ms/op
                 createUser·p1.00:   26.935 ms/op

Iteration   3: 3.103 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.671 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.555 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  18.217 ms/op
                 createUser·p0.9999: 21.103 ms/op
                 createUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300138
  mean =      3.198 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20798 
    [ 2.500,  5.000) = 272767 
    [ 5.000,  7.500) = 5827 
    [ 7.500, 10.000) = 292 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     25.755 ms/op
     p(99.9990) =     26.673 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.969 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.453 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.008 ms/op
Iteration   1: 3.072 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  11.024 ms/op
                 existUser·p0.9999: 22.910 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  8.124 ms/op
                 existUser·p0.9999: 21.321 ms/op
                 existUser·p1.00:   22.118 ms/op

Iteration   3: 3.126 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  14.287 ms/op
                 existUser·p0.9999: 34.144 ms/op
                 existUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309600
  mean =      3.099 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18015 
    [ 2.500,  5.000) = 286927 
    [ 5.000,  7.500) = 3855 
    [ 7.500, 10.000) = 419 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     32.540 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.341 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.465 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.010 ms/op
Iteration   1: 3.187 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  17.715 ms/op
                 getUser·p0.9999: 21.887 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   2: 3.086 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.502 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  8.294 ms/op
                 getUser·p0.9999: 28.190 ms/op
                 getUser·p1.00:   29.524 ms/op

Iteration   3: 3.159 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.928 ms/op
                 getUser·p0.999:  13.669 ms/op
                 getUser·p0.9999: 21.037 ms/op
                 getUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 305070
  mean =      3.143 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15652 
    [ 2.500,  5.000) = 283594 
    [ 5.000,  7.500) = 4943 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     16.089 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     28.967 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.011 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.010 ms/op
Iteration   1: 3.726 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.927 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 18.514 ms/op
                 listUser·p1.00:   26.378 ms/op

Iteration   2: 3.760 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 15.909 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   3: 3.742 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.250 ms/op
                 listUser·p0.999:  12.599 ms/op
                 listUser·p0.9999: 15.031 ms/op
                 listUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256364
  mean =      3.743 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 249050 
    [ 5.000,  7.500) = 5682 
    [ 7.500, 10.000) = 887 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.927 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     13.849 ms/op
     p(99.9900) =     18.317 ms/op
     p(99.9990) =     19.755 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.919 ± 4.847  ops/ms
ClientPb.existUser                       thrpt       3  10.258 ± 2.664  ops/ms
ClientPb.getUser                         thrpt       3   9.919 ± 2.294  ops/ms
ClientPb.listUser                        thrpt       3   8.510 ± 2.269  ops/ms
ClientPb.createUser                       avgt       3   3.128 ± 1.208   ms/op
ClientPb.existUser                        avgt       3   3.063 ± 0.555   ms/op
ClientPb.getUser                          avgt       3   3.213 ± 1.684   ms/op
ClientPb.listUser                         avgt       3   3.722 ± 2.161   ms/op
ClientPb.createUser                     sample  300138   3.198 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.079           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.568           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.400           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.755           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.935           ms/op
ClientPb.existUser                      sample  309600   3.099 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.847           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.449           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.254           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.540           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.931           ms/op
ClientPb.getUser                        sample  305070   3.143 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.970           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.465           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.775           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.089           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.870           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.524           ms/op
ClientPb.listUser                       sample  256364   3.743 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.927           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.026           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.644           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.849           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.317           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.378           ms/op
