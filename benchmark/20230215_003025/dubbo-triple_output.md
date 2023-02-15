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
# Warmup Iteration   1: 1.395 ops/ms
# Warmup Iteration   2: 3.806 ops/ms
# Warmup Iteration   3: 7.714 ops/ms
Iteration   1: 7.594 ops/ms
Iteration   2: 8.497 ops/ms
Iteration   3: 8.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.215 ±(99.9%) 9.812 ops/ms [Average]
  (min, avg, max) = (7.594, 8.215, 8.553), stdev = 0.538
  CI (99.9%): [≈ 0, 18.027] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.671 ops/ms
# Warmup Iteration   2: 7.255 ops/ms
# Warmup Iteration   3: 8.245 ops/ms
Iteration   1: 8.744 ops/ms
Iteration   2: 9.066 ops/ms
Iteration   3: 9.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.983 ±(99.9%) 3.836 ops/ms [Average]
  (min, avg, max) = (8.744, 8.983, 9.140), stdev = 0.210
  CI (99.9%): [5.147, 12.819] (assumes normal distribution)


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
# Warmup Iteration   1: 2.208 ops/ms
# Warmup Iteration   2: 6.820 ops/ms
# Warmup Iteration   3: 7.949 ops/ms
Iteration   1: 8.386 ops/ms
Iteration   2: 8.555 ops/ms
Iteration   3: 8.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.419 ±(99.9%) 2.251 ops/ms [Average]
  (min, avg, max) = (8.315, 8.419, 8.555), stdev = 0.123
  CI (99.9%): [6.168, 10.669] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.257 ops/ms
# Warmup Iteration   2: 6.064 ops/ms
# Warmup Iteration   3: 7.454 ops/ms
Iteration   1: 7.630 ops/ms
Iteration   2: 7.695 ops/ms
Iteration   3: 7.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.565 ±(99.9%) 3.133 ops/ms [Average]
  (min, avg, max) = (7.370, 7.565, 7.695), stdev = 0.172
  CI (99.9%): [4.432, 10.699] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.197 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.372 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.005 ms/op
Iteration   1: 3.395 ±(99.9%) 0.015 ms/op
Iteration   2: 3.452 ±(99.9%) 0.006 ms/op
Iteration   3: 3.576 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.474 ±(99.9%) 1.686 ms/op [Average]
  (min, avg, max) = (3.395, 3.474, 3.576), stdev = 0.092
  CI (99.9%): [1.789, 5.160] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.085 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.006 ms/op
Iteration   1: 3.438 ±(99.9%) 0.006 ms/op
Iteration   2: 3.390 ±(99.9%) 0.004 ms/op
Iteration   3: 3.349 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.393 ±(99.9%) 0.813 ms/op [Average]
  (min, avg, max) = (3.349, 3.393, 3.438), stdev = 0.045
  CI (99.9%): [2.579, 4.206] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.758 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.003 ms/op
Iteration   1: 3.897 ±(99.9%) 0.006 ms/op
Iteration   2: 3.654 ±(99.9%) 0.011 ms/op
Iteration   3: 4.070 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.874 ±(99.9%) 3.811 ms/op [Average]
  (min, avg, max) = (3.654, 3.874, 4.070), stdev = 0.209
  CI (99.9%): [0.063, 7.685] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.280 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.637 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.580 ±(99.9%) 0.008 ms/op
Iteration   1: 4.419 ±(99.9%) 0.019 ms/op
Iteration   2: 4.425 ±(99.9%) 0.012 ms/op
Iteration   3: 4.575 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.473 ±(99.9%) 1.617 ms/op [Average]
  (min, avg, max) = (4.419, 4.473, 4.575), stdev = 0.089
  CI (99.9%): [2.856, 6.090] (assumes normal distribution)


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
# Warmup Iteration   1: 13.561 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 4.764 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.116 ±(99.9%) 0.017 ms/op
Iteration   1: 3.695 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.669 ms/op
                 createUser·p0.50:   3.559 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  21.741 ms/op
                 createUser·p0.9999: 25.964 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   2: 3.861 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.659 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  11.092 ms/op
                 createUser·p0.9999: 26.238 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   3: 3.835 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.865 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   7.079 ms/op
                 createUser·p0.999:  27.951 ms/op
                 createUser·p0.9999: 30.878 ms/op
                 createUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 252812
  mean =      3.796 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1650 
    [ 2.500,  5.000) = 241082 
    [ 5.000,  7.500) = 8684 
    [ 7.500, 10.000) = 917 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     21.100 ms/op
     p(99.9900) =     30.367 ms/op
     p(99.9990) =     31.222 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.408 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.707 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.012 ms/op
Iteration   1: 3.674 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  22.017 ms/op
                 existUser·p0.9999: 25.765 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   2: 3.761 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.520 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  16.776 ms/op
                 existUser·p0.9999: 35.389 ms/op
                 existUser·p1.00:   35.521 ms/op

Iteration   3: 3.902 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.573 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   5.014 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  9.322 ms/op
                 existUser·p0.9999: 33.280 ms/op
                 existUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254034
  mean =      3.776 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2236 
    [ 2.500,  5.000) = 242860 
    [ 5.000,  7.500) = 7617 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 68 
    [32.500, 35.000) = 42 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     16.220 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     35.485 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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
# Warmup Iteration   1: 11.205 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.327 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.013 ms/op
Iteration   1: 3.833 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.634 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   7.315 ms/op
                 getUser·p0.999:  12.157 ms/op
                 getUser·p0.9999: 26.279 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   2: 3.832 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.752 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  24.366 ms/op
                 getUser·p0.9999: 29.849 ms/op
                 getUser·p1.00:   31.883 ms/op

Iteration   3: 3.747 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.898 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  10.072 ms/op
                 getUser·p0.9999: 28.762 ms/op
                 getUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 252261
  mean =      3.804 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 211 
    [ 2.500,  5.000) = 242431 
    [ 5.000,  7.500) = 8178 
    [ 7.500, 10.000) = 931 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     12.127 ms/op
     p(99.9900) =     28.690 ms/op
     p(99.9990) =     31.063 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 13.684 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 5.362 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.668 ±(99.9%) 0.019 ms/op
Iteration   1: 4.611 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  25.810 ms/op
                 listUser·p0.9999: 32.846 ms/op
                 listUser·p1.00:   35.193 ms/op

Iteration   2: 4.559 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 20.546 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   3: 4.247 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   4.141 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  15.288 ms/op
                 listUser·p0.9999: 18.791 ms/op
                 listUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 214787
  mean =      4.466 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 196786 
    [ 5.000,  7.500) = 14214 
    [ 7.500, 10.000) = 2721 
    [10.000, 12.500) = 466 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     31.017 ms/op
     p(99.9990) =     34.824 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.215 ± 9.812  ops/ms
ClientPb.existUser                       thrpt       3   8.983 ± 3.836  ops/ms
ClientPb.getUser                         thrpt       3   8.419 ± 2.251  ops/ms
ClientPb.listUser                        thrpt       3   7.565 ± 3.133  ops/ms
ClientPb.createUser                       avgt       3   3.474 ± 1.686   ms/op
ClientPb.existUser                        avgt       3   3.393 ± 0.813   ms/op
ClientPb.getUser                          avgt       3   3.874 ± 3.811   ms/op
ClientPb.listUser                         avgt       3   4.473 ± 1.617   ms/op
ClientPb.createUser                     sample  252812   3.796 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.865           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.650           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.481           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.850           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.100           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.367           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.982           ms/op
ClientPb.existUser                      sample  254034   3.776 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.403           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.751           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.463           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.220           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.144           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.521           ms/op
ClientPb.getUser                        sample  252261   3.804 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.300           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.690           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.644           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.127           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.690           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.883           ms/op
ClientPb.listUser                       sample  214787   4.466 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.149           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.308           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.503           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.465           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.017           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.193           ms/op
