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
# Warmup Iteration   1: 1.547 ops/ms
# Warmup Iteration   2: 3.424 ops/ms
# Warmup Iteration   3: 6.605 ops/ms
Iteration   1: 7.728 ops/ms
Iteration   2: 7.942 ops/ms
Iteration   3: 7.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.813 ±(99.9%) 2.075 ops/ms [Average]
  (min, avg, max) = (7.728, 7.813, 7.942), stdev = 0.114
  CI (99.9%): [5.738, 9.887] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.015 ops/ms
# Warmup Iteration   2: 6.942 ops/ms
# Warmup Iteration   3: 7.918 ops/ms
Iteration   1: 8.048 ops/ms
Iteration   2: 8.208 ops/ms
Iteration   3: 8.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.286 ±(99.9%) 5.211 ops/ms [Average]
  (min, avg, max) = (8.048, 8.286, 8.603), stdev = 0.286
  CI (99.9%): [3.075, 13.498] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.170 ops/ms
# Warmup Iteration   2: 6.678 ops/ms
# Warmup Iteration   3: 8.000 ops/ms
Iteration   1: 7.723 ops/ms
Iteration   2: 8.003 ops/ms
Iteration   3: 8.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.956 ±(99.9%) 3.894 ops/ms [Average]
  (min, avg, max) = (7.723, 7.956, 8.142), stdev = 0.213
  CI (99.9%): [4.063, 11.850] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.212 ops/ms
# Warmup Iteration   2: 5.414 ops/ms
# Warmup Iteration   3: 6.482 ops/ms
Iteration   1: 6.639 ops/ms
Iteration   2: 6.817 ops/ms
Iteration   3: 6.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.733 ±(99.9%) 1.636 ops/ms [Average]
  (min, avg, max) = (6.639, 6.733, 6.817), stdev = 0.090
  CI (99.9%): [5.097, 8.369] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.294 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.669 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.006 ms/op
Iteration   1: 4.173 ±(99.9%) 0.006 ms/op
Iteration   2: 4.159 ±(99.9%) 0.006 ms/op
Iteration   3: 4.129 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.154 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (4.129, 4.154, 4.173), stdev = 0.023
  CI (99.9%): [3.740, 4.568] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.295 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.359 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.011 ms/op
Iteration   1: 3.962 ±(99.9%) 0.005 ms/op
Iteration   2: 3.811 ±(99.9%) 0.007 ms/op
Iteration   3: 3.868 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.880 ±(99.9%) 1.389 ms/op [Average]
  (min, avg, max) = (3.811, 3.880, 3.962), stdev = 0.076
  CI (99.9%): [2.491, 5.270] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.804 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.825 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.411 ±(99.9%) 0.002 ms/op
Iteration   1: 4.093 ±(99.9%) 0.008 ms/op
Iteration   2: 4.058 ±(99.9%) 0.007 ms/op
Iteration   3: 4.099 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.083 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (4.058, 4.083, 4.099), stdev = 0.022
  CI (99.9%): [3.676, 4.491] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.688 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.693 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.129 ±(99.9%) 0.005 ms/op
Iteration   1: 4.753 ±(99.9%) 0.011 ms/op
Iteration   2: 4.775 ±(99.9%) 0.010 ms/op
Iteration   3: 4.701 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.743 ±(99.9%) 0.697 ms/op [Average]
  (min, avg, max) = (4.701, 4.743, 4.775), stdev = 0.038
  CI (99.9%): [4.046, 5.440] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.172 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.828 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.438 ±(99.9%) 0.019 ms/op
Iteration   1: 4.147 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.681 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   5.456 ms/op
                 createUser·p0.99:   7.733 ms/op
                 createUser·p0.999:  24.244 ms/op
                 createUser·p0.9999: 27.258 ms/op
                 createUser·p1.00:   28.180 ms/op

Iteration   2: 3.986 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   2.083 ms/op
                 createUser·p0.50:   3.916 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  14.467 ms/op
                 createUser·p0.9999: 27.880 ms/op
                 createUser·p1.00:   28.967 ms/op

Iteration   3: 4.002 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.993 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   5.267 ms/op
                 createUser·p0.99:   8.135 ms/op
                 createUser·p0.999:  28.576 ms/op
                 createUser·p0.9999: 32.769 ms/op
                 createUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237395
  mean =      4.044 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 435 
    [ 2.500,  5.000) = 221869 
    [ 5.000,  7.500) = 12690 
    [ 7.500, 10.000) = 1455 
    [10.000, 12.500) = 442 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.681 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     24.235 ms/op
     p(99.9900) =     31.826 ms/op
     p(99.9990) =     33.247 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.185 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.590 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.013 ms/op
Iteration   1: 3.836 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  22.302 ms/op
                 existUser·p0.9999: 37.661 ms/op
                 existUser·p1.00:   41.746 ms/op

Iteration   2: 3.949 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   7.528 ms/op
                 existUser·p0.999:  14.334 ms/op
                 existUser·p0.9999: 25.162 ms/op
                 existUser·p1.00:   26.477 ms/op

Iteration   3: 3.825 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   6.668 ms/op
                 existUser·p0.999:  16.937 ms/op
                 existUser·p0.9999: 25.907 ms/op
                 existUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247917
  mean =      3.869 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 238695 
    [ 5.000, 10.000) = 8591 
    [10.000, 15.000) = 340 
    [15.000, 20.000) = 59 
    [20.000, 25.000) = 157 
    [25.000, 30.000) = 42 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     16.667 ms/op
     p(99.9900) =     36.058 ms/op
     p(99.9990) =     39.092 ms/op
     p(99.9999) =     41.746 ms/op
    p(100.0000) =     41.746 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.863 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.653 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.016 ms/op
Iteration   1: 4.318 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.118 ms/op
                 getUser·p0.50:   4.026 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   6.431 ms/op
                 getUser·p0.99:   8.733 ms/op
                 getUser·p0.999:  22.248 ms/op
                 getUser·p0.9999: 28.266 ms/op
                 getUser·p1.00:   30.147 ms/op

Iteration   2: 4.072 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.001 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   8.176 ms/op
                 getUser·p0.999:  25.865 ms/op
                 getUser·p0.9999: 33.563 ms/op
                 getUser·p1.00:   34.406 ms/op

Iteration   3: 3.929 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.802 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  10.479 ms/op
                 getUser·p0.9999: 31.125 ms/op
                 getUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234086
  mean =      4.100 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 219260 
    [ 5.000,  7.500) = 11092 
    [ 7.500, 10.000) = 2917 
    [10.000, 12.500) = 424 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.802 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      8.159 ms/op
     p(99.9000) =     22.247 ms/op
     p(99.9900) =     31.876 ms/op
     p(99.9990) =     34.186 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.701 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 5.683 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.822 ±(99.9%) 0.015 ms/op
Iteration   1: 4.617 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  23.019 ms/op
                 listUser·p0.9999: 25.609 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 4.770 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.079 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 27.197 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   3: 4.701 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.773 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  16.646 ms/op
                 listUser·p0.9999: 17.879 ms/op
                 listUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204354
  mean =      4.695 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 172713 
    [ 5.000,  7.500) = 27524 
    [ 7.500, 10.000) = 2880 
    [10.000, 12.500) = 522 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      2.079 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     18.360 ms/op
     p(99.9900) =     26.467 ms/op
     p(99.9990) =     27.454 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.813 ± 2.075  ops/ms
ClientPb.existUser                       thrpt       3   8.286 ± 5.211  ops/ms
ClientPb.getUser                         thrpt       3   7.956 ± 3.894  ops/ms
ClientPb.listUser                        thrpt       3   6.733 ± 1.636  ops/ms
ClientPb.createUser                       avgt       3   4.154 ± 0.414   ms/op
ClientPb.existUser                        avgt       3   3.880 ± 1.389   ms/op
ClientPb.getUser                          avgt       3   4.083 ± 0.408   ms/op
ClientPb.listUser                         avgt       3   4.743 ± 0.697   ms/op
ClientPb.createUser                     sample  237395   4.044 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.681           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.645           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.267           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.520           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.235           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.826           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.292           ms/op
ClientPb.existUser                      sample  247917   3.869 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.954           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.176           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.667           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.058           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.746           ms/op
ClientPb.getUser                        sample  234086   4.100 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.802           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.661           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.159           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.247           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.876           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.406           ms/op
ClientPb.listUser                       sample  204354   4.695 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.079           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.259           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.684           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.360           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.467           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.656           ms/op
