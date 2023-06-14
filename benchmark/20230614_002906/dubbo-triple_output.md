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
# Warmup Iteration   1: 1.418 ops/ms
# Warmup Iteration   2: 2.693 ops/ms
# Warmup Iteration   3: 5.631 ops/ms
Iteration   1: 6.395 ops/ms
Iteration   2: 6.950 ops/ms
Iteration   3: 7.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.848 ±(99.9%) 7.517 ops/ms [Average]
  (min, avg, max) = (6.395, 6.848, 7.200), stdev = 0.412
  CI (99.9%): [≈ 0, 14.366] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.842 ops/ms
# Warmup Iteration   2: 5.532 ops/ms
# Warmup Iteration   3: 7.367 ops/ms
Iteration   1: 7.335 ops/ms
Iteration   2: 7.026 ops/ms
Iteration   3: 7.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.252 ±(99.9%) 3.620 ops/ms [Average]
  (min, avg, max) = (7.026, 7.252, 7.396), stdev = 0.198
  CI (99.9%): [3.632, 10.872] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.011 ops/ms
# Warmup Iteration   2: 5.189 ops/ms
# Warmup Iteration   3: 6.767 ops/ms
Iteration   1: 6.788 ops/ms
Iteration   2: 6.843 ops/ms
Iteration   3: 6.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.876 ±(99.9%) 1.988 ops/ms [Average]
  (min, avg, max) = (6.788, 6.876, 6.998), stdev = 0.109
  CI (99.9%): [4.888, 8.865] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.761 ops/ms
# Warmup Iteration   2: 4.473 ops/ms
# Warmup Iteration   3: 5.885 ops/ms
Iteration   1: 5.905 ops/ms
Iteration   2: 5.989 ops/ms
Iteration   3: 5.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.953 ±(99.9%) 0.787 ops/ms [Average]
  (min, avg, max) = (5.905, 5.953, 5.989), stdev = 0.043
  CI (99.9%): [5.166, 6.741] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 16.862 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.457 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.664 ±(99.9%) 0.007 ms/op
Iteration   1: 4.545 ±(99.9%) 0.012 ms/op
Iteration   2: 4.409 ±(99.9%) 0.012 ms/op
Iteration   3: 4.514 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.489 ±(99.9%) 1.300 ms/op [Average]
  (min, avg, max) = (4.409, 4.489, 4.545), stdev = 0.071
  CI (99.9%): [3.189, 5.789] (assumes normal distribution)


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
# Warmup Iteration   1: 15.254 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.257 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.581 ±(99.9%) 0.008 ms/op
Iteration   1: 4.498 ±(99.9%) 0.006 ms/op
Iteration   2: 4.500 ±(99.9%) 0.005 ms/op
Iteration   3: 4.288 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.429 ±(99.9%) 2.221 ms/op [Average]
  (min, avg, max) = (4.288, 4.429, 4.500), stdev = 0.122
  CI (99.9%): [2.208, 6.650] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.119 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.319 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.649 ±(99.9%) 0.010 ms/op
Iteration   1: 4.720 ±(99.9%) 0.006 ms/op
Iteration   2: 4.451 ±(99.9%) 0.004 ms/op
Iteration   3: 4.269 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.480 ±(99.9%) 4.139 ms/op [Average]
  (min, avg, max) = (4.269, 4.480, 4.720), stdev = 0.227
  CI (99.9%): [0.341, 8.619] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.326 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.406 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.415 ±(99.9%) 0.008 ms/op
Iteration   1: 5.384 ±(99.9%) 0.008 ms/op
Iteration   2: 5.216 ±(99.9%) 0.013 ms/op
Iteration   3: 5.177 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.259 ±(99.9%) 2.010 ms/op [Average]
  (min, avg, max) = (5.177, 5.259, 5.384), stdev = 0.110
  CI (99.9%): [3.248, 7.269] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.264 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 5.749 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.581 ±(99.9%) 0.022 ms/op
Iteration   1: 4.369 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.989 ms/op
                 createUser·p0.50:   4.137 ms/op
                 createUser·p0.90:   5.276 ms/op
                 createUser·p0.95:   6.226 ms/op
                 createUser·p0.99:   8.487 ms/op
                 createUser·p0.999:  14.844 ms/op
                 createUser·p0.9999: 26.040 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   2: 4.284 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   4.022 ms/op
                 createUser·p0.90:   5.161 ms/op
                 createUser·p0.95:   5.808 ms/op
                 createUser·p0.99:   8.864 ms/op
                 createUser·p0.999:  16.417 ms/op
                 createUser·p0.9999: 31.361 ms/op
                 createUser·p1.00:   34.079 ms/op

Iteration   3: 4.403 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   4.104 ms/op
                 createUser·p0.90:   5.292 ms/op
                 createUser·p0.95:   6.267 ms/op
                 createUser·p0.99:   9.601 ms/op
                 createUser·p0.999:  29.065 ms/op
                 createUser·p0.9999: 37.093 ms/op
                 createUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 220567
  mean =      4.351 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 265 
    [ 2.500,  5.000) = 190194 
    [ 5.000,  7.500) = 25659 
    [ 7.500, 10.000) = 3188 
    [10.000, 12.500) = 677 
    [12.500, 15.000) = 281 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      6.128 ms/op
     p(99.0000) =      8.902 ms/op
     p(99.9000) =     22.769 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     37.381 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 11.918 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 5.030 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.412 ±(99.9%) 0.017 ms/op
Iteration   1: 4.155 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.054 ms/op
                 existUser·p0.50:   3.940 ms/op
                 existUser·p0.90:   4.940 ms/op
                 existUser·p0.95:   5.743 ms/op
                 existUser·p0.99:   8.487 ms/op
                 existUser·p0.999:  13.189 ms/op
                 existUser·p0.9999: 27.109 ms/op
                 existUser·p1.00:   28.246 ms/op

Iteration   2: 4.158 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.726 ms/op
                 existUser·p0.50:   3.969 ms/op
                 existUser·p0.90:   4.882 ms/op
                 existUser·p0.95:   5.554 ms/op
                 existUser·p0.99:   7.954 ms/op
                 existUser·p0.999:  12.715 ms/op
                 existUser·p0.9999: 31.556 ms/op
                 existUser·p1.00:   32.702 ms/op

Iteration   3: 4.198 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.806 ms/op
                 existUser·p0.50:   3.920 ms/op
                 existUser·p0.90:   4.907 ms/op
                 existUser·p0.95:   6.128 ms/op
                 existUser·p0.99:   9.798 ms/op
                 existUser·p0.999:  30.333 ms/op
                 existUser·p0.9999: 32.720 ms/op
                 existUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 230086
  mean =      4.170 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 252 
    [ 2.500,  5.000) = 208831 
    [ 5.000,  7.500) = 16747 
    [ 7.500, 10.000) = 2979 
    [10.000, 12.500) = 789 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 91 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.726 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      8.782 ms/op
     p(99.9000) =     21.097 ms/op
     p(99.9900) =     32.210 ms/op
     p(99.9990) =     33.980 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 13.543 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 4.877 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.495 ±(99.9%) 0.017 ms/op
Iteration   1: 4.140 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.716 ms/op
                 getUser·p0.50:   3.883 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   6.193 ms/op
                 getUser·p0.99:   8.552 ms/op
                 getUser·p0.999:  11.928 ms/op
                 getUser·p0.9999: 26.944 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   2: 3.955 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.866 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   7.196 ms/op
                 getUser·p0.999:  26.219 ms/op
                 getUser·p0.9999: 27.817 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   3: 4.153 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.680 ms/op
                 getUser·p0.99:   8.144 ms/op
                 getUser·p0.999:  19.137 ms/op
                 getUser·p0.9999: 33.158 ms/op
                 getUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235095
  mean =      4.081 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 97 
    [ 2.500,  5.000) = 217090 
    [ 5.000,  7.500) = 14391 
    [ 7.500, 10.000) = 2657 
    [10.000, 12.500) = 468 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 135 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      8.176 ms/op
     p(99.9000) =     19.199 ms/op
     p(99.9900) =     31.375 ms/op
     p(99.9990) =     34.137 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 14.582 ±(99.9%) 0.217 ms/op
# Warmup Iteration   2: 5.635 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.025 ±(99.9%) 0.017 ms/op
Iteration   1: 5.004 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.947 ms/op
                 listUser·p0.95:   7.627 ms/op
                 listUser·p0.99:   10.207 ms/op
                 listUser·p0.999:  23.887 ms/op
                 listUser·p0.9999: 26.417 ms/op
                 listUser·p1.00:   26.968 ms/op

Iteration   2: 4.946 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.702 ms/op
                 listUser·p0.95:   6.887 ms/op
                 listUser·p0.99:   9.929 ms/op
                 listUser·p0.999:  18.065 ms/op
                 listUser·p0.9999: 21.467 ms/op
                 listUser·p1.00:   23.724 ms/op

Iteration   3: 5.046 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.503 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   7.127 ms/op
                 listUser·p0.99:   10.785 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 19.650 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 192082
  mean =      4.998 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 135871 
    [ 5.000,  7.500) = 47449 
    [ 7.500, 10.000) = 6526 
    [10.000, 12.500) = 1438 
    [12.500, 15.000) = 302 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.808 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =     10.325 ms/op
     p(99.9000) =     19.595 ms/op
     p(99.9900) =     25.159 ms/op
     p(99.9990) =     26.697 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.848 ± 7.517  ops/ms
ClientPb.existUser                       thrpt       3   7.252 ± 3.620  ops/ms
ClientPb.getUser                         thrpt       3   6.876 ± 1.988  ops/ms
ClientPb.listUser                        thrpt       3   5.953 ± 0.787  ops/ms
ClientPb.createUser                       avgt       3   4.489 ± 1.300   ms/op
ClientPb.existUser                        avgt       3   4.429 ± 2.221   ms/op
ClientPb.getUser                          avgt       3   4.480 ± 4.139   ms/op
ClientPb.listUser                         avgt       3   5.259 ± 2.010   ms/op
ClientPb.createUser                     sample  220567   4.351 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.898           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.235           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.128           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.902           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.769           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.931           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.421           ms/op
ClientPb.existUser                      sample  230086   4.170 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.726           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.782           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.097           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.210           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.734           ms/op
ClientPb.getUser                        sample  235095   4.081 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.077           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.760           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.538           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.176           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.199           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.375           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.406           ms/op
ClientPb.listUser                       sample  192082   4.998 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.171           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.808           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.217           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.325           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.595           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.159           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.968           ms/op
