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
# Warmup Iteration   1: 1.734 ops/ms
# Warmup Iteration   2: 3.774 ops/ms
# Warmup Iteration   3: 7.163 ops/ms
Iteration   1: 7.115 ops/ms
Iteration   2: 7.611 ops/ms
Iteration   3: 7.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.473 ±(99.9%) 5.709 ops/ms [Average]
  (min, avg, max) = (7.115, 7.473, 7.694), stdev = 0.313
  CI (99.9%): [1.764, 13.183] (assumes normal distribution)


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
# Warmup Iteration   1: 2.012 ops/ms
# Warmup Iteration   2: 6.518 ops/ms
# Warmup Iteration   3: 8.316 ops/ms
Iteration   1: 7.654 ops/ms
Iteration   2: 7.719 ops/ms
Iteration   3: 8.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.858 ±(99.9%) 5.444 ops/ms [Average]
  (min, avg, max) = (7.654, 7.858, 8.200), stdev = 0.298
  CI (99.9%): [2.413, 13.302] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.327 ops/ms
# Warmup Iteration   2: 6.851 ops/ms
# Warmup Iteration   3: 8.000 ops/ms
Iteration   1: 7.915 ops/ms
Iteration   2: 7.751 ops/ms
Iteration   3: 7.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.872 ±(99.9%) 1.940 ops/ms [Average]
  (min, avg, max) = (7.751, 7.872, 7.951), stdev = 0.106
  CI (99.9%): [5.932, 9.813] (assumes normal distribution)


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
# Warmup Iteration   1: 1.902 ops/ms
# Warmup Iteration   2: 5.775 ops/ms
# Warmup Iteration   3: 6.526 ops/ms
Iteration   1: 6.887 ops/ms
Iteration   2: 6.595 ops/ms
Iteration   3: 6.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.777 ±(99.9%) 2.896 ops/ms [Average]
  (min, avg, max) = (6.595, 6.777, 6.887), stdev = 0.159
  CI (99.9%): [3.882, 9.673] (assumes normal distribution)


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
# Warmup Iteration   1: 14.827 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 5.257 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.007 ms/op
Iteration   1: 4.204 ±(99.9%) 0.011 ms/op
Iteration   2: 3.971 ±(99.9%) 0.007 ms/op
Iteration   3: 3.886 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.020 ±(99.9%) 3.008 ms/op [Average]
  (min, avg, max) = (3.886, 4.020, 4.204), stdev = 0.165
  CI (99.9%): [1.012, 7.028] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 13.426 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.144 ±(99.9%) 0.005 ms/op
Iteration   1: 3.804 ±(99.9%) 0.009 ms/op
Iteration   2: 3.918 ±(99.9%) 0.008 ms/op
Iteration   3: 3.761 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.827 ±(99.9%) 1.486 ms/op [Average]
  (min, avg, max) = (3.761, 3.827, 3.918), stdev = 0.081
  CI (99.9%): [2.341, 5.314] (assumes normal distribution)


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
# Warmup Iteration   1: 11.956 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.552 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.007 ms/op
Iteration   1: 3.902 ±(99.9%) 0.012 ms/op
Iteration   2: 4.005 ±(99.9%) 0.003 ms/op
Iteration   3: 4.028 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.978 ±(99.9%) 1.228 ms/op [Average]
  (min, avg, max) = (3.902, 3.978, 4.028), stdev = 0.067
  CI (99.9%): [2.750, 5.207] (assumes normal distribution)


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
# Warmup Iteration   1: 13.370 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.469 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.909 ±(99.9%) 0.008 ms/op
Iteration   1: 4.631 ±(99.9%) 0.012 ms/op
Iteration   2: 4.586 ±(99.9%) 0.005 ms/op
Iteration   3: 4.648 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.622 ±(99.9%) 0.585 ms/op [Average]
  (min, avg, max) = (4.586, 4.622, 4.648), stdev = 0.032
  CI (99.9%): [4.037, 5.206] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.831 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 4.811 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.393 ±(99.9%) 0.018 ms/op
Iteration   1: 3.927 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.868 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  12.789 ms/op
                 createUser·p0.9999: 24.599 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   2: 4.102 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.419 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.874 ms/op
                 createUser·p0.95:   5.456 ms/op
                 createUser·p0.99:   7.365 ms/op
                 createUser·p0.999:  23.198 ms/op
                 createUser·p0.9999: 25.172 ms/op
                 createUser·p1.00:   27.099 ms/op

Iteration   3: 4.055 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.960 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.292 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  24.714 ms/op
                 createUser·p0.9999: 29.888 ms/op
                 createUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238370
  mean =      4.027 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 487 
    [ 2.500,  5.000) = 223040 
    [ 5.000,  7.500) = 12893 
    [ 7.500, 10.000) = 1297 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.419 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     22.434 ms/op
     p(99.9900) =     28.246 ms/op
     p(99.9990) =     31.062 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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
# Warmup Iteration   1: 10.989 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.396 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.013 ms/op
Iteration   1: 3.823 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.925 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.957 ms/op
                 existUser·p0.99:   7.397 ms/op
                 existUser·p0.999:  12.386 ms/op
                 existUser·p0.9999: 26.464 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   2: 3.820 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.837 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   5.054 ms/op
                 existUser·p0.99:   7.160 ms/op
                 existUser·p0.999:  23.928 ms/op
                 existUser·p0.9999: 33.792 ms/op
                 existUser·p1.00:   34.341 ms/op

Iteration   3: 3.746 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.250 ms/op
                 existUser·p0.999:  11.676 ms/op
                 existUser·p0.9999: 33.209 ms/op
                 existUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252829
  mean =      3.796 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 462 
    [ 2.500,  5.000) = 241932 
    [ 5.000,  7.500) = 8751 
    [ 7.500, 10.000) = 1101 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.018 ms/op
     p(99.9000) =     12.392 ms/op
     p(99.9900) =     32.899 ms/op
     p(99.9990) =     34.206 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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
# Warmup Iteration   1: 13.632 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 4.728 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.012 ms/op
Iteration   1: 4.178 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.782 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   4.915 ms/op
                 getUser·p0.95:   6.103 ms/op
                 getUser·p0.99:   8.667 ms/op
                 getUser·p0.999:  24.604 ms/op
                 getUser·p0.9999: 26.740 ms/op
                 getUser·p1.00:   27.525 ms/op

Iteration   2: 4.111 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.896 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.809 ms/op
                 getUser·p0.95:   5.448 ms/op
                 getUser·p0.99:   7.979 ms/op
                 getUser·p0.999:  12.555 ms/op
                 getUser·p0.9999: 29.808 ms/op
                 getUser·p1.00:   30.769 ms/op

Iteration   3: 4.096 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.952 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   4.760 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   7.919 ms/op
                 getUser·p0.999:  26.870 ms/op
                 getUser·p0.9999: 30.448 ms/op
                 getUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232409
  mean =      4.128 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 147 
    [ 2.500,  5.000) = 213601 
    [ 5.000,  7.500) = 15104 
    [ 7.500, 10.000) = 2601 
    [10.000, 12.500) = 488 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 120 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.782 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      8.158 ms/op
     p(99.9000) =     24.759 ms/op
     p(99.9900) =     29.877 ms/op
     p(99.9990) =     30.858 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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
# Warmup Iteration   1: 14.920 ±(99.9%) 0.290 ms/op
# Warmup Iteration   2: 5.979 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.959 ±(99.9%) 0.019 ms/op
Iteration   1: 4.853 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.609 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.685 ms/op
                 listUser·p0.95:   6.865 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  26.219 ms/op
                 listUser·p0.9999: 31.192 ms/op
                 listUser·p1.00:   31.719 ms/op

Iteration   2: 4.613 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  20.508 ms/op
                 listUser·p0.9999: 24.872 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   3: 4.843 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.521 ms/op
                 listUser·p0.99:   9.519 ms/op
                 listUser·p0.999:  19.038 ms/op
                 listUser·p0.9999: 22.539 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201228
  mean =      4.767 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 163014 
    [ 5.000,  7.500) = 32129 
    [ 7.500, 10.000) = 4696 
    [10.000, 12.500) = 814 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      6.390 ms/op
     p(99.0000) =      9.154 ms/op
     p(99.9000) =     22.292 ms/op
     p(99.9900) =     29.688 ms/op
     p(99.9990) =     31.620 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.473 ± 5.709  ops/ms
ClientPb.existUser                       thrpt       3   7.858 ± 5.444  ops/ms
ClientPb.getUser                         thrpt       3   7.872 ± 1.940  ops/ms
ClientPb.listUser                        thrpt       3   6.777 ± 2.896  ops/ms
ClientPb.createUser                       avgt       3   4.020 ± 3.008   ms/op
ClientPb.existUser                        avgt       3   3.827 ± 1.486   ms/op
ClientPb.getUser                          avgt       3   3.978 ± 1.228   ms/op
ClientPb.listUser                         avgt       3   4.622 ± 0.585   ms/op
ClientPb.createUser                     sample  238370   4.027 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.419           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.177           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.102           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.434           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.246           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.195           ms/op
ClientPb.existUser                      sample  252829   3.796 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.006           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.792           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.018           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.392           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.899           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.341           ms/op
ClientPb.getUser                        sample  232409   4.128 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.782           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.571           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.158           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.759           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.877           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.162           ms/op
ClientPb.listUser                       sample  201228   4.767 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.958           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.390           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.154           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.292           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.688           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.719           ms/op
