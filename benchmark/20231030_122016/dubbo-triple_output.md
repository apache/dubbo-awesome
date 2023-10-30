# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.257 ops/ms
# Warmup Iteration   2: 2.705 ops/ms
# Warmup Iteration   3: 5.721 ops/ms
Iteration   1: 5.663 ops/ms
Iteration   2: 5.929 ops/ms
Iteration   3: 6.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.953 ±(99.9%) 5.540 ops/ms [Average]
  (min, avg, max) = (5.663, 5.953, 6.268), stdev = 0.304
  CI (99.9%): [0.414, 11.493] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 2.027 ops/ms
# Warmup Iteration   2: 5.580 ops/ms
# Warmup Iteration   3: 6.232 ops/ms
Iteration   1: 6.329 ops/ms
Iteration   2: 6.132 ops/ms
Iteration   3: 6.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.239 ±(99.9%) 1.818 ops/ms [Average]
  (min, avg, max) = (6.132, 6.239, 6.329), stdev = 0.100
  CI (99.9%): [4.420, 8.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.897 ops/ms
# Warmup Iteration   2: 5.108 ops/ms
# Warmup Iteration   3: 5.913 ops/ms
Iteration   1: 5.946 ops/ms
Iteration   2: 5.830 ops/ms
Iteration   3: 6.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.045 ±(99.9%) 5.073 ops/ms [Average]
  (min, avg, max) = (5.830, 6.045, 6.359), stdev = 0.278
  CI (99.9%): [0.972, 11.119] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.762 ops/ms
# Warmup Iteration   2: 4.413 ops/ms
# Warmup Iteration   3: 5.245 ops/ms
Iteration   1: 5.159 ops/ms
Iteration   2: 5.266 ops/ms
Iteration   3: 5.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.178 ±(99.9%) 1.468 ops/ms [Average]
  (min, avg, max) = (5.108, 5.178, 5.266), stdev = 0.080
  CI (99.9%): [3.710, 6.645] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 16.788 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.942 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.631 ±(99.9%) 0.009 ms/op
Iteration   1: 5.232 ±(99.9%) 0.010 ms/op
Iteration   2: 5.299 ±(99.9%) 0.009 ms/op
Iteration   3: 5.311 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.281 ±(99.9%) 0.777 ms/op [Average]
  (min, avg, max) = (5.232, 5.281, 5.311), stdev = 0.043
  CI (99.9%): [4.504, 6.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 14.865 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.447 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.058 ±(99.9%) 0.013 ms/op
Iteration   1: 5.065 ±(99.9%) 0.008 ms/op
Iteration   2: 5.065 ±(99.9%) 0.007 ms/op
Iteration   3: 4.923 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.018 ±(99.9%) 1.489 ms/op [Average]
  (min, avg, max) = (4.923, 5.018, 5.065), stdev = 0.082
  CI (99.9%): [3.529, 6.506] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 15.617 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.843 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.671 ±(99.9%) 0.008 ms/op
Iteration   1: 5.192 ±(99.9%) 0.008 ms/op
Iteration   2: 5.470 ±(99.9%) 0.008 ms/op
Iteration   3: 5.350 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.337 ±(99.9%) 2.545 ms/op [Average]
  (min, avg, max) = (5.192, 5.337, 5.470), stdev = 0.139
  CI (99.9%): [2.793, 7.882] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.976 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 7.315 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.249 ±(99.9%) 0.012 ms/op
Iteration   1: 6.031 ±(99.9%) 0.011 ms/op
Iteration   2: 6.063 ±(99.9%) 0.013 ms/op
Iteration   3: 6.611 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.235 ±(99.9%) 5.945 ms/op [Average]
  (min, avg, max) = (6.031, 6.235, 6.611), stdev = 0.326
  CI (99.9%): [0.290, 12.180] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.321 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 6.480 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.955 ±(99.9%) 0.027 ms/op
Iteration   1: 5.465 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.363 ms/op
                 createUser·p0.50:   5.218 ms/op
                 createUser·p0.90:   6.742 ms/op
                 createUser·p0.95:   7.651 ms/op
                 createUser·p0.99:   10.273 ms/op
                 createUser·p0.999:  23.069 ms/op
                 createUser·p0.9999: 29.951 ms/op
                 createUser·p1.00:   30.376 ms/op

Iteration   2: 5.843 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   2.050 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   7.676 ms/op
                 createUser·p0.95:   9.208 ms/op
                 createUser·p0.99:   13.435 ms/op
                 createUser·p0.999:  27.410 ms/op
                 createUser·p0.9999: 36.145 ms/op
                 createUser·p1.00:   36.700 ms/op

Iteration   3: 5.947 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.657 ms/op
                 createUser·p0.50:   5.399 ms/op
                 createUser·p0.90:   8.094 ms/op
                 createUser·p0.95:   9.847 ms/op
                 createUser·p0.99:   14.114 ms/op
                 createUser·p0.999:  27.722 ms/op
                 createUser·p0.9999: 41.345 ms/op
                 createUser·p1.00:   42.140 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 167049
  mean =      5.744 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 61134 
    [ 5.000, 10.000) = 100774 
    [10.000, 15.000) = 4365 
    [15.000, 20.000) = 437 
    [20.000, 25.000) = 159 
    [25.000, 30.000) = 111 
    [30.000, 35.000) = 43 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.657 ms/op
     p(50.0000) =      5.317 ms/op
     p(90.0000) =      7.447 ms/op
     p(95.0000) =      8.913 ms/op
     p(99.0000) =     12.780 ms/op
     p(99.9000) =     25.428 ms/op
     p(99.9900) =     36.542 ms/op
     p(99.9990) =     42.008 ms/op
     p(99.9999) =     42.140 ms/op
    p(100.0000) =     42.140 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.925 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 5.516 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.088 ±(99.9%) 0.020 ms/op
Iteration   1: 5.211 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.437 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   6.521 ms/op
                 existUser·p0.95:   7.553 ms/op
                 existUser·p0.99:   10.355 ms/op
                 existUser·p0.999:  23.243 ms/op
                 existUser·p0.9999: 28.368 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   2: 5.179 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.105 ms/op
                 existUser·p0.50:   4.940 ms/op
                 existUser·p0.90:   6.382 ms/op
                 existUser·p0.95:   7.168 ms/op
                 existUser·p0.99:   9.585 ms/op
                 existUser·p0.999:  26.100 ms/op
                 existUser·p0.9999: 32.194 ms/op
                 existUser·p1.00:   32.670 ms/op

Iteration   3: 4.870 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.208 ms/op
                 existUser·p0.50:   4.637 ms/op
                 existUser·p0.90:   5.906 ms/op
                 existUser·p0.95:   6.742 ms/op
                 existUser·p0.99:   9.372 ms/op
                 existUser·p0.999:  25.699 ms/op
                 existUser·p0.9999: 28.588 ms/op
                 existUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188898
  mean =      5.082 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 111889 
    [ 5.000,  7.500) = 69256 
    [ 7.500, 10.000) = 6039 
    [10.000, 12.500) = 990 
    [12.500, 15.000) = 297 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.437 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.283 ms/op
     p(95.0000) =      7.184 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     24.448 ms/op
     p(99.9900) =     30.216 ms/op
     p(99.9990) =     32.670 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.701 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 6.098 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.443 ±(99.9%) 0.022 ms/op
Iteration   1: 5.401 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.445 ms/op
                 getUser·p0.50:   5.022 ms/op
                 getUser·p0.90:   6.734 ms/op
                 getUser·p0.95:   8.249 ms/op
                 getUser·p0.99:   13.443 ms/op
                 getUser·p0.999:  24.183 ms/op
                 getUser·p0.9999: 28.707 ms/op
                 getUser·p1.00:   29.524 ms/op

Iteration   2: 5.729 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.359 ms/op
                 getUser·p0.50:   5.448 ms/op
                 getUser·p0.90:   7.021 ms/op
                 getUser·p0.95:   8.077 ms/op
                 getUser·p0.99:   11.367 ms/op
                 getUser·p0.999:  19.038 ms/op
                 getUser·p0.9999: 31.373 ms/op
                 getUser·p1.00:   36.110 ms/op

Iteration   3: 5.804 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.673 ms/op
                 getUser·p0.50:   5.480 ms/op
                 getUser·p0.90:   7.160 ms/op
                 getUser·p0.95:   8.045 ms/op
                 getUser·p0.99:   11.715 ms/op
                 getUser·p0.999:  27.019 ms/op
                 getUser·p0.9999: 32.718 ms/op
                 getUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170223
  mean =      5.639 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 56813 
    [ 5.000,  7.500) = 101345 
    [ 7.500, 10.000) = 8923 
    [10.000, 12.500) = 1492 
    [12.500, 15.000) = 858 
    [15.000, 17.500) = 339 
    [17.500, 20.000) = 188 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.445 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      7.012 ms/op
     p(95.0000) =      8.126 ms/op
     p(99.0000) =     12.288 ms/op
     p(99.9000) =     24.208 ms/op
     p(99.9900) =     31.882 ms/op
     p(99.9990) =     34.039 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.037 ±(99.9%) 0.358 ms/op
# Warmup Iteration   2: 8.329 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 6.886 ±(99.9%) 0.028 ms/op
Iteration   1: 6.784 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.662 ms/op
                 listUser·p0.50:   6.406 ms/op
                 listUser·p0.90:   8.569 ms/op
                 listUser·p0.95:   9.862 ms/op
                 listUser·p0.99:   13.156 ms/op
                 listUser·p0.999:  23.090 ms/op
                 listUser·p0.9999: 28.002 ms/op
                 listUser·p1.00:   29.360 ms/op

Iteration   2: 6.631 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.548 ms/op
                 listUser·p0.50:   6.259 ms/op
                 listUser·p0.90:   8.217 ms/op
                 listUser·p0.95:   9.650 ms/op
                 listUser·p0.99:   12.629 ms/op
                 listUser·p0.999:  25.792 ms/op
                 listUser·p0.9999: 28.829 ms/op
                 listUser·p1.00:   31.425 ms/op

Iteration   3: 6.443 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.855 ms/op
                 listUser·p0.50:   6.136 ms/op
                 listUser·p0.90:   7.537 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   11.878 ms/op
                 listUser·p0.999:  22.675 ms/op
                 listUser·p0.9999: 31.955 ms/op
                 listUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145024
  mean =      6.617 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 4547 
    [ 5.000,  7.500) = 118435 
    [ 7.500, 10.000) = 16527 
    [10.000, 12.500) = 4003 
    [12.500, 15.000) = 871 
    [15.000, 17.500) = 255 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.548 ms/op
     p(50.0000) =      6.250 ms/op
     p(90.0000) =      8.126 ms/op
     p(95.0000) =      9.503 ms/op
     p(99.0000) =     12.583 ms/op
     p(99.9000) =     24.575 ms/op
     p(99.9900) =     29.245 ms/op
     p(99.9990) =     32.294 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.953 ± 5.540  ops/ms
ClientPb.existUser                       thrpt       3   6.239 ± 1.818  ops/ms
ClientPb.getUser                         thrpt       3   6.045 ± 5.073  ops/ms
ClientPb.listUser                        thrpt       3   5.178 ± 1.468  ops/ms
ClientPb.createUser                       avgt       3   5.281 ± 0.777   ms/op
ClientPb.existUser                        avgt       3   5.018 ± 1.489   ms/op
ClientPb.getUser                          avgt       3   5.337 ± 2.545   ms/op
ClientPb.listUser                         avgt       3   6.235 ± 5.945   ms/op
ClientPb.createUser                     sample  167049   5.744 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.657           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.317           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.447           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.913           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.780           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.428           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.542           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.140           ms/op
ClientPb.existUser                      sample  188898   5.082 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.437           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.825           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.283           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.184           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.781           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.448           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.216           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.670           ms/op
ClientPb.getUser                        sample  170223   5.639 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.445           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.325           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.012           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.126           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.288           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.208           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.882           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.110           ms/op
ClientPb.listUser                       sample  145024   6.617 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.548           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.250           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.126           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.503           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.583           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.575           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.245           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.309           ms/op
