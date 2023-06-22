# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.611 ops/ms
# Warmup Iteration   2: 3.969 ops/ms
# Warmup Iteration   3: 6.917 ops/ms
Iteration   1: 7.081 ops/ms
Iteration   2: 8.088 ops/ms
Iteration   3: 7.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.564 ±(99.9%) 9.206 ops/ms [Average]
  (min, avg, max) = (7.081, 7.564, 8.088), stdev = 0.505
  CI (99.9%): [≈ 0, 16.770] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.218 ops/ms
# Warmup Iteration   2: 6.458 ops/ms
# Warmup Iteration   3: 8.096 ops/ms
Iteration   1: 7.923 ops/ms
Iteration   2: 8.465 ops/ms
Iteration   3: 8.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.323 ±(99.9%) 6.404 ops/ms [Average]
  (min, avg, max) = (7.923, 8.323, 8.581), stdev = 0.351
  CI (99.9%): [1.919, 14.726] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.294 ops/ms
# Warmup Iteration   2: 6.348 ops/ms
# Warmup Iteration   3: 7.649 ops/ms
Iteration   1: 7.876 ops/ms
Iteration   2: 8.296 ops/ms
Iteration   3: 8.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.083 ±(99.9%) 3.834 ops/ms [Average]
  (min, avg, max) = (7.876, 8.083, 8.296), stdev = 0.210
  CI (99.9%): [4.249, 11.917] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.956 ops/ms
# Warmup Iteration   2: 5.518 ops/ms
# Warmup Iteration   3: 6.687 ops/ms
Iteration   1: 6.804 ops/ms
Iteration   2: 6.931 ops/ms
Iteration   3: 6.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.872 ±(99.9%) 1.162 ops/ms [Average]
  (min, avg, max) = (6.804, 6.872, 6.931), stdev = 0.064
  CI (99.9%): [5.710, 8.033] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.593 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.581 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.477 ±(99.9%) 0.004 ms/op
Iteration   1: 3.976 ±(99.9%) 0.013 ms/op
Iteration   2: 3.996 ±(99.9%) 0.007 ms/op
Iteration   3: 4.147 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.039 ±(99.9%) 1.705 ms/op [Average]
  (min, avg, max) = (3.976, 4.039, 4.147), stdev = 0.093
  CI (99.9%): [2.334, 5.745] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.892 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.511 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.004 ms/op
Iteration   1: 3.741 ±(99.9%) 0.009 ms/op
Iteration   2: 3.869 ±(99.9%) 0.007 ms/op
Iteration   3: 3.802 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.804 ±(99.9%) 1.169 ms/op [Average]
  (min, avg, max) = (3.741, 3.804, 3.869), stdev = 0.064
  CI (99.9%): [2.635, 4.974] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.457 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.651 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.008 ms/op
Iteration   1: 4.168 ±(99.9%) 0.007 ms/op
Iteration   2: 3.982 ±(99.9%) 0.011 ms/op
Iteration   3: 3.933 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.028 ±(99.9%) 2.263 ms/op [Average]
  (min, avg, max) = (3.933, 4.028, 4.168), stdev = 0.124
  CI (99.9%): [1.765, 6.291] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.357 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.264 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.914 ±(99.9%) 0.007 ms/op
Iteration   1: 4.774 ±(99.9%) 0.011 ms/op
Iteration   2: 4.726 ±(99.9%) 0.013 ms/op
Iteration   3: 4.653 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.718 ±(99.9%) 1.106 ms/op [Average]
  (min, avg, max) = (4.653, 4.718, 4.774), stdev = 0.061
  CI (99.9%): [3.612, 5.823] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.155 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 5.193 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.523 ±(99.9%) 0.019 ms/op
Iteration   1: 3.984 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   6.783 ms/op
                 createUser·p0.999:  12.201 ms/op
                 createUser·p0.9999: 25.230 ms/op
                 createUser·p1.00:   25.854 ms/op

Iteration   2: 3.940 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.868 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   6.660 ms/op
                 createUser·p0.999:  24.740 ms/op
                 createUser·p0.9999: 34.210 ms/op
                 createUser·p1.00:   35.848 ms/op

Iteration   3: 3.992 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.563 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   7.635 ms/op
                 createUser·p0.999:  26.280 ms/op
                 createUser·p0.9999: 29.491 ms/op
                 createUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241604
  mean =      3.972 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 292 
    [ 2.500,  5.000) = 230315 
    [ 5.000,  7.500) = 9156 
    [ 7.500, 10.000) = 1338 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     23.462 ms/op
     p(99.9900) =     31.124 ms/op
     p(99.9990) =     35.362 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.272 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.731 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.012 ms/op
Iteration   1: 3.967 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.686 ms/op
                 existUser·p0.95:   5.161 ms/op
                 existUser·p0.99:   6.996 ms/op
                 existUser·p0.999:  11.047 ms/op
                 existUser·p0.9999: 30.802 ms/op
                 existUser·p1.00:   31.752 ms/op

Iteration   2: 3.929 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   6.946 ms/op
                 existUser·p0.999:  26.689 ms/op
                 existUser·p0.9999: 32.239 ms/op
                 existUser·p1.00:   33.292 ms/op

Iteration   3: 3.849 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.880 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.186 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   7.791 ms/op
                 existUser·p0.999:  14.254 ms/op
                 existUser·p0.9999: 31.460 ms/op
                 existUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245325
  mean =      3.915 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 357 
    [ 2.500,  5.000) = 231009 
    [ 5.000,  7.500) = 11870 
    [ 7.500, 10.000) = 1532 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 63 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.483 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     14.232 ms/op
     p(99.9900) =     31.521 ms/op
     p(99.9990) =     32.625 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.197 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.012 ms/op
Iteration   1: 4.166 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.808 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   5.734 ms/op
                 getUser·p0.99:   8.061 ms/op
                 getUser·p0.999:  22.680 ms/op
                 getUser·p0.9999: 24.455 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   2: 3.980 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.552 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  11.408 ms/op
                 getUser·p0.9999: 26.180 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   3: 3.980 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.708 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  25.876 ms/op
                 getUser·p0.9999: 28.931 ms/op
                 getUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237628
  mean =      4.040 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 96 
    [ 2.500,  5.000) = 226193 
    [ 5.000,  7.500) = 9479 
    [ 7.500, 10.000) = 1216 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 76 

  Percentiles, ms/op:
      p(0.0000) =      1.552 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     22.634 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     29.290 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.511 ±(99.9%) 0.225 ms/op
# Warmup Iteration   2: 5.402 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.700 ±(99.9%) 0.015 ms/op
Iteration   1: 4.663 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   8.379 ms/op
                 listUser·p0.999:  24.642 ms/op
                 listUser·p0.9999: 30.680 ms/op
                 listUser·p1.00:   31.228 ms/op

Iteration   2: 4.712 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   8.322 ms/op
                 listUser·p0.999:  20.120 ms/op
                 listUser·p0.9999: 23.039 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   3: 4.626 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.765 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.573 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  16.708 ms/op
                 listUser·p0.9999: 20.362 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205649
  mean =      4.667 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 184175 
    [ 5.000,  7.500) = 17649 
    [ 7.500, 10.000) = 2678 
    [10.000, 12.500) = 484 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.142 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.476 ms/op
     p(99.0000) =      8.397 ms/op
     p(99.9000) =     20.929 ms/op
     p(99.9900) =     29.272 ms/op
     p(99.9990) =     31.222 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.564 ± 9.206  ops/ms
ClientPb.existUser                       thrpt       3   8.323 ± 6.404  ops/ms
ClientPb.getUser                         thrpt       3   8.083 ± 3.834  ops/ms
ClientPb.listUser                        thrpt       3   6.872 ± 1.162  ops/ms
ClientPb.createUser                       avgt       3   4.039 ± 1.705   ms/op
ClientPb.existUser                        avgt       3   3.804 ± 1.169   ms/op
ClientPb.getUser                          avgt       3   4.028 ± 2.263   ms/op
ClientPb.listUser                         avgt       3   4.718 ± 1.106   ms/op
ClientPb.createUser                     sample  241604   3.972 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.362           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.456           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.915           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.201           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.462           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.124           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.848           ms/op
ClientPb.existUser                      sample  245325   3.915 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.483           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.538           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.095           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.250           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.232           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.521           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.292           ms/op
ClientPb.getUser                        sample  237628   4.040 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.552           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.634           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.541           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.753           ms/op
ClientPb.listUser                       sample  205649   4.667 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.142           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.476           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.397           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.929           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.272           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.228           ms/op
