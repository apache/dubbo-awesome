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
# Warmup Iteration   1: 1.227 ops/ms
# Warmup Iteration   2: 2.764 ops/ms
# Warmup Iteration   3: 5.977 ops/ms
Iteration   1: 5.758 ops/ms
Iteration   2: 6.603 ops/ms
Iteration   3: 6.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.320 ±(99.9%) 8.884 ops/ms [Average]
  (min, avg, max) = (5.758, 6.320, 6.603), stdev = 0.487
  CI (99.9%): [≈ 0, 15.204] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.828 ops/ms
# Warmup Iteration   2: 4.874 ops/ms
# Warmup Iteration   3: 5.725 ops/ms
Iteration   1: 5.829 ops/ms
Iteration   2: 5.945 ops/ms
Iteration   3: 5.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.920 ±(99.9%) 1.473 ops/ms [Average]
  (min, avg, max) = (5.829, 5.920, 5.985), stdev = 0.081
  CI (99.9%): [4.446, 7.393] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.604 ops/ms
# Warmup Iteration   2: 4.623 ops/ms
# Warmup Iteration   3: 6.079 ops/ms
Iteration   1: 6.255 ops/ms
Iteration   2: 5.739 ops/ms
Iteration   3: 6.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.016 ±(99.9%) 4.740 ops/ms [Average]
  (min, avg, max) = (5.739, 6.016, 6.255), stdev = 0.260
  CI (99.9%): [1.276, 10.756] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.691 ops/ms
# Warmup Iteration   2: 4.511 ops/ms
# Warmup Iteration   3: 5.318 ops/ms
Iteration   1: 5.122 ops/ms
Iteration   2: 5.279 ops/ms
Iteration   3: 5.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.209 ±(99.9%) 1.465 ops/ms [Average]
  (min, avg, max) = (5.122, 5.209, 5.279), stdev = 0.080
  CI (99.9%): [3.744, 6.674] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 15.679 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 6.069 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.438 ±(99.9%) 0.008 ms/op
Iteration   1: 5.226 ±(99.9%) 0.018 ms/op
Iteration   2: 5.261 ±(99.9%) 0.019 ms/op
Iteration   3: 5.226 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.238 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (5.226, 5.238, 5.261), stdev = 0.020
  CI (99.9%): [4.865, 5.610] (assumes normal distribution)


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
# Warmup Iteration   1: 14.814 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.384 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.975 ±(99.9%) 0.009 ms/op
Iteration   1: 5.087 ±(99.9%) 0.008 ms/op
Iteration   2: 5.047 ±(99.9%) 0.009 ms/op
Iteration   3: 5.004 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.046 ±(99.9%) 0.757 ms/op [Average]
  (min, avg, max) = (5.004, 5.046, 5.087), stdev = 0.041
  CI (99.9%): [4.289, 5.803] (assumes normal distribution)


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
# Warmup Iteration   1: 16.438 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.680 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.126 ±(99.9%) 0.010 ms/op
Iteration   1: 5.061 ±(99.9%) 0.011 ms/op
Iteration   2: 5.076 ±(99.9%) 0.014 ms/op
Iteration   3: 4.942 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.026 ±(99.9%) 1.340 ms/op [Average]
  (min, avg, max) = (4.942, 5.026, 5.076), stdev = 0.073
  CI (99.9%): [3.687, 6.366] (assumes normal distribution)


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
# Warmup Iteration   1: 19.365 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 7.923 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.233 ±(99.9%) 0.013 ms/op
Iteration   1: 6.070 ±(99.9%) 0.019 ms/op
Iteration   2: 5.983 ±(99.9%) 0.014 ms/op
Iteration   3: 5.927 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.994 ±(99.9%) 1.314 ms/op [Average]
  (min, avg, max) = (5.927, 5.994, 6.070), stdev = 0.072
  CI (99.9%): [4.680, 7.307] (assumes normal distribution)


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
# Warmup Iteration   1: 15.667 ±(99.9%) 0.246 ms/op
# Warmup Iteration   2: 6.720 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.917 ±(99.9%) 0.028 ms/op
Iteration   1: 5.147 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.872 ms/op
                 createUser·p0.50:   4.907 ms/op
                 createUser·p0.90:   6.349 ms/op
                 createUser·p0.95:   7.291 ms/op
                 createUser·p0.99:   10.273 ms/op
                 createUser·p0.999:  22.282 ms/op
                 createUser·p0.9999: 28.191 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   2: 5.352 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.071 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.668 ms/op
                 createUser·p0.95:   7.463 ms/op
                 createUser·p0.99:   9.585 ms/op
                 createUser·p0.999:  25.306 ms/op
                 createUser·p0.9999: 30.412 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   3: 5.134 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.847 ms/op
                 createUser·p0.50:   4.907 ms/op
                 createUser·p0.90:   6.275 ms/op
                 createUser·p0.95:   7.045 ms/op
                 createUser·p0.99:   9.273 ms/op
                 createUser·p0.999:  26.499 ms/op
                 createUser·p0.9999: 32.156 ms/op
                 createUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 184245
  mean =      5.209 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 94713 
    [ 5.000,  7.500) = 81666 
    [ 7.500, 10.000) = 6252 
    [10.000, 12.500) = 1024 
    [12.500, 15.000) = 246 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.847 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.447 ms/op
     p(95.0000) =      7.266 ms/op
     p(99.0000) =      9.667 ms/op
     p(99.9000) =     24.233 ms/op
     p(99.9900) =     30.769 ms/op
     p(99.9990) =     32.423 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


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
# Warmup Iteration   1: 15.767 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 5.810 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.251 ±(99.9%) 0.019 ms/op
Iteration   1: 5.019 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.454 ms/op
                 existUser·p0.50:   4.751 ms/op
                 existUser·p0.90:   6.341 ms/op
                 existUser·p0.95:   7.152 ms/op
                 existUser·p0.99:   9.585 ms/op
                 existUser·p0.999:  23.973 ms/op
                 existUser·p0.9999: 28.758 ms/op
                 existUser·p1.00:   30.048 ms/op

Iteration   2: 4.938 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.507 ms/op
                 existUser·p0.50:   4.727 ms/op
                 existUser·p0.90:   5.988 ms/op
                 existUser·p0.95:   6.783 ms/op
                 existUser·p0.99:   9.404 ms/op
                 existUser·p0.999:  16.208 ms/op
                 existUser·p0.9999: 30.164 ms/op
                 existUser·p1.00:   30.769 ms/op

Iteration   3: 5.183 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.212 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.578 ms/op
                 existUser·p0.95:   7.381 ms/op
                 existUser·p0.99:   10.437 ms/op
                 existUser·p0.999:  17.834 ms/op
                 existUser·p0.9999: 31.479 ms/op
                 existUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 190277
  mean =      5.045 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 115950 
    [ 5.000,  7.500) = 67185 
    [ 7.500, 10.000) = 5363 
    [10.000, 12.500) = 1185 
    [12.500, 15.000) = 275 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.454 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.119 ms/op
     p(99.0000) =      9.765 ms/op
     p(99.9000) =     16.429 ms/op
     p(99.9900) =     30.372 ms/op
     p(99.9990) =     31.936 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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
# Warmup Iteration   1: 16.435 ±(99.9%) 0.257 ms/op
# Warmup Iteration   2: 6.295 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.305 ±(99.9%) 0.019 ms/op
Iteration   1: 5.591 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.733 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   6.906 ms/op
                 getUser·p0.95:   8.438 ms/op
                 getUser·p0.99:   13.633 ms/op
                 getUser·p0.999:  24.897 ms/op
                 getUser·p0.9999: 27.534 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   2: 5.389 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.740 ms/op
                 getUser·p0.50:   5.112 ms/op
                 getUser·p0.90:   6.644 ms/op
                 getUser·p0.95:   7.602 ms/op
                 getUser·p0.99:   10.191 ms/op
                 getUser·p0.999:  30.530 ms/op
                 getUser·p0.9999: 36.766 ms/op
                 getUser·p1.00:   37.552 ms/op

Iteration   3: 5.356 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.392 ms/op
                 getUser·p0.50:   5.153 ms/op
                 getUser·p0.90:   6.644 ms/op
                 getUser·p0.95:   7.348 ms/op
                 getUser·p0.99:   9.290 ms/op
                 getUser·p0.999:  26.683 ms/op
                 getUser·p0.9999: 31.690 ms/op
                 getUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176212
  mean =      5.443 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 72599 
    [ 5.000,  7.500) = 93335 
    [ 7.500, 10.000) = 7687 
    [10.000, 12.500) = 1381 
    [12.500, 15.000) = 640 
    [15.000, 17.500) = 226 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 37 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.733 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.709 ms/op
     p(95.0000) =      7.752 ms/op
     p(99.0000) =     11.043 ms/op
     p(99.9000) =     25.362 ms/op
     p(99.9900) =     34.169 ms/op
     p(99.9990) =     37.053 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


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
# Warmup Iteration   1: 16.840 ±(99.9%) 0.263 ms/op
# Warmup Iteration   2: 7.216 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.061 ±(99.9%) 0.023 ms/op
Iteration   1: 6.166 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.650 ms/op
                 listUser·p0.50:   5.865 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   8.552 ms/op
                 listUser·p0.99:   11.502 ms/op
                 listUser·p0.999:  25.559 ms/op
                 listUser·p0.9999: 29.000 ms/op
                 listUser·p1.00:   30.048 ms/op

Iteration   2: 6.102 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.839 ms/op
                 listUser·p0.50:   5.849 ms/op
                 listUser·p0.90:   7.315 ms/op
                 listUser·p0.95:   8.102 ms/op
                 listUser·p0.99:   10.322 ms/op
                 listUser·p0.999:  28.312 ms/op
                 listUser·p0.9999: 30.919 ms/op
                 listUser·p1.00:   33.817 ms/op

Iteration   3: 6.292 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   7.692 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   11.485 ms/op
                 listUser·p0.999:  22.020 ms/op
                 listUser·p0.9999: 29.858 ms/op
                 listUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 155126
  mean =      6.186 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 13358 
    [ 5.000,  7.500) = 126481 
    [ 7.500, 10.000) = 12410 
    [10.000, 12.500) = 1937 
    [12.500, 15.000) = 447 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.277 ms/op
     p(50.0000) =      5.898 ms/op
     p(90.0000) =      7.487 ms/op
     p(95.0000) =      8.405 ms/op
     p(99.0000) =     11.141 ms/op
     p(99.9000) =     24.961 ms/op
     p(99.9900) =     30.473 ms/op
     p(99.9990) =     33.509 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.320 ± 8.884  ops/ms
ClientPb.existUser                       thrpt       3   5.920 ± 1.473  ops/ms
ClientPb.getUser                         thrpt       3   6.016 ± 4.740  ops/ms
ClientPb.listUser                        thrpt       3   5.209 ± 1.465  ops/ms
ClientPb.createUser                       avgt       3   5.238 ± 0.372   ms/op
ClientPb.existUser                        avgt       3   5.046 ± 0.757   ms/op
ClientPb.getUser                          avgt       3   5.026 ± 1.340   ms/op
ClientPb.listUser                         avgt       3   5.994 ± 1.314   ms/op
ClientPb.createUser                     sample  184245   5.209 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.847           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.973           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.447           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.266           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.667           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.233           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.769           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.506           ms/op
ClientPb.existUser                      sample  190277   5.045 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.454           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.784           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.308           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.119           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.765           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.429           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.372           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.030           ms/op
ClientPb.getUser                        sample  176212   5.443 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.733           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.145           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.709           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.752           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.043           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.362           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.169           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.552           ms/op
ClientPb.listUser                       sample  155126   6.186 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.277           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.898           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.487           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.405           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.141           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.961           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.473           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.817           ms/op
