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
# Warmup Iteration   1: 1.506 ops/ms
# Warmup Iteration   2: 3.760 ops/ms
# Warmup Iteration   3: 6.817 ops/ms
Iteration   1: 6.752 ops/ms
Iteration   2: 7.793 ops/ms
Iteration   3: 7.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.339 ±(99.9%) 9.728 ops/ms [Average]
  (min, avg, max) = (6.752, 7.339, 7.793), stdev = 0.533
  CI (99.9%): [≈ 0, 17.067] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.110 ops/ms
# Warmup Iteration   2: 5.729 ops/ms
# Warmup Iteration   3: 7.467 ops/ms
Iteration   1: 7.885 ops/ms
Iteration   2: 7.905 ops/ms
Iteration   3: 7.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.880 ±(99.9%) 0.524 ops/ms [Average]
  (min, avg, max) = (7.848, 7.880, 7.905), stdev = 0.029
  CI (99.9%): [7.356, 8.403] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.021 ops/ms
# Warmup Iteration   2: 6.260 ops/ms
# Warmup Iteration   3: 7.410 ops/ms
Iteration   1: 7.217 ops/ms
Iteration   2: 7.749 ops/ms
Iteration   3: 7.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.484 ±(99.9%) 4.860 ops/ms [Average]
  (min, avg, max) = (7.217, 7.484, 7.749), stdev = 0.266
  CI (99.9%): [2.624, 12.343] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.893 ops/ms
# Warmup Iteration   2: 5.449 ops/ms
# Warmup Iteration   3: 6.290 ops/ms
Iteration   1: 6.368 ops/ms
Iteration   2: 6.604 ops/ms
Iteration   3: 6.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.523 ±(99.9%) 2.437 ops/ms [Average]
  (min, avg, max) = (6.368, 6.523, 6.604), stdev = 0.134
  CI (99.9%): [4.085, 8.960] (assumes normal distribution)


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
# Warmup Iteration   1: 14.271 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.794 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.274 ±(99.9%) 0.015 ms/op
Iteration   1: 4.249 ±(99.9%) 0.009 ms/op
Iteration   2: 3.963 ±(99.9%) 0.012 ms/op
Iteration   3: 4.252 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.155 ±(99.9%) 3.030 ms/op [Average]
  (min, avg, max) = (3.963, 4.155, 4.252), stdev = 0.166
  CI (99.9%): [1.125, 7.185] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.647 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.604 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.250 ±(99.9%) 0.006 ms/op
Iteration   1: 4.124 ±(99.9%) 0.004 ms/op
Iteration   2: 3.782 ±(99.9%) 0.012 ms/op
Iteration   3: 4.052 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.986 ±(99.9%) 3.294 ms/op [Average]
  (min, avg, max) = (3.782, 3.986, 4.124), stdev = 0.181
  CI (99.9%): [0.692, 7.280] (assumes normal distribution)


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
# Warmup Iteration   1: 14.443 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.345 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.202 ±(99.9%) 0.009 ms/op
Iteration   1: 4.018 ±(99.9%) 0.006 ms/op
Iteration   2: 3.972 ±(99.9%) 0.007 ms/op
Iteration   3: 4.132 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.041 ±(99.9%) 1.506 ms/op [Average]
  (min, avg, max) = (3.972, 4.041, 4.132), stdev = 0.083
  CI (99.9%): [2.535, 5.547] (assumes normal distribution)


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
# Warmup Iteration   1: 15.024 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.750 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.063 ±(99.9%) 0.007 ms/op
Iteration   1: 5.004 ±(99.9%) 0.008 ms/op
Iteration   2: 4.962 ±(99.9%) 0.016 ms/op
Iteration   3: 4.980 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.982 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (4.962, 4.982, 5.004), stdev = 0.021
  CI (99.9%): [4.603, 5.361] (assumes normal distribution)


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
# Warmup Iteration   1: 11.754 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 6.205 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 4.796 ±(99.9%) 0.025 ms/op
Iteration   1: 4.213 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.905 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   6.103 ms/op
                 createUser·p0.99:   8.004 ms/op
                 createUser·p0.999:  12.780 ms/op
                 createUser·p0.9999: 27.570 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   2: 4.242 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.671 ms/op
                 createUser·p0.50:   3.990 ms/op
                 createUser·p0.90:   5.030 ms/op
                 createUser·p0.95:   5.612 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  27.820 ms/op
                 createUser·p0.9999: 33.242 ms/op
                 createUser·p1.00:   34.013 ms/op

Iteration   3: 4.209 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   5.095 ms/op
                 createUser·p0.95:   5.939 ms/op
                 createUser·p0.99:   8.487 ms/op
                 createUser·p0.999:  29.917 ms/op
                 createUser·p0.9999: 44.985 ms/op
                 createUser·p1.00:   45.220 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 227286
  mean =      4.221 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 202358 
    [ 5.000, 10.000) = 23901 
    [10.000, 15.000) = 716 
    [15.000, 20.000) = 52 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 109 
    [30.000, 35.000) = 86 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.671 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      8.307 ms/op
     p(99.9000) =     25.086 ms/op
     p(99.9900) =     39.339 ms/op
     p(99.9990) =     45.154 ms/op
     p(99.9999) =     45.220 ms/op
    p(100.0000) =     45.220 ms/op


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
# Warmup Iteration   1: 12.953 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 4.651 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.014 ms/op
Iteration   1: 3.940 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.843 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   5.317 ms/op
                 existUser·p0.99:   6.971 ms/op
                 existUser·p0.999:  11.223 ms/op
                 existUser·p0.9999: 32.367 ms/op
                 existUser·p1.00:   33.686 ms/op

Iteration   2: 3.952 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   7.586 ms/op
                 existUser·p0.999:  25.241 ms/op
                 existUser·p0.9999: 28.675 ms/op
                 existUser·p1.00:   31.588 ms/op

Iteration   3: 3.833 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   6.758 ms/op
                 existUser·p0.999:  11.862 ms/op
                 existUser·p0.9999: 31.086 ms/op
                 existUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245450
  mean =      3.908 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 208 
    [ 2.500,  5.000) = 232636 
    [ 5.000,  7.500) = 10657 
    [ 7.500, 10.000) = 1421 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 86 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     12.789 ms/op
     p(99.9900) =     31.341 ms/op
     p(99.9990) =     33.459 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 14.416 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 4.760 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.530 ±(99.9%) 0.017 ms/op
Iteration   1: 4.116 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.294 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.964 ms/op
                 getUser·p0.99:   8.648 ms/op
                 getUser·p0.999:  24.621 ms/op
                 getUser·p0.9999: 57.541 ms/op
                 getUser·p1.00:   58.655 ms/op

Iteration   2: 3.943 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.800 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  10.624 ms/op
                 getUser·p0.9999: 27.784 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 4.081 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.013 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   8.389 ms/op
                 getUser·p0.999:  27.351 ms/op
                 getUser·p0.9999: 30.015 ms/op
                 getUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237023
  mean =      4.045 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 224544 
    [ 5.000, 10.000) = 11608 
    [10.000, 15.000) = 609 
    [15.000, 20.000) = 6 
    [20.000, 25.000) = 25 
    [25.000, 30.000) = 161 
    [30.000, 35.000) = 38 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      8.045 ms/op
     p(99.9000) =     24.641 ms/op
     p(99.9900) =     55.266 ms/op
     p(99.9990) =     58.558 ms/op
     p(99.9999) =     58.655 ms/op
    p(100.0000) =     58.655 ms/op


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
# Warmup Iteration   1: 15.700 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 6.245 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.313 ±(99.9%) 0.023 ms/op
Iteration   1: 4.942 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   6.906 ms/op
                 listUser·p0.99:   9.404 ms/op
                 listUser·p0.999:  28.246 ms/op
                 listUser·p0.9999: 31.083 ms/op
                 listUser·p1.00:   31.457 ms/op

Iteration   2: 5.193 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.646 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   6.529 ms/op
                 listUser·p0.95:   8.094 ms/op
                 listUser·p0.99:   11.656 ms/op
                 listUser·p0.999:  27.787 ms/op
                 listUser·p0.9999: 32.206 ms/op
                 listUser·p1.00:   32.965 ms/op

Iteration   3: 5.127 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.661 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.250 ms/op
                 listUser·p0.95:   8.020 ms/op
                 listUser·p0.99:   11.076 ms/op
                 listUser·p0.999:  18.776 ms/op
                 listUser·p0.9999: 21.989 ms/op
                 listUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 188623
  mean =      5.085 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 132742 
    [ 5.000,  7.500) = 45391 
    [ 7.500, 10.000) = 7665 
    [10.000, 12.500) = 1836 
    [12.500, 15.000) = 430 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 104 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      6.103 ms/op
     p(95.0000) =      7.741 ms/op
     p(99.0000) =     10.781 ms/op
     p(99.9000) =     25.592 ms/op
     p(99.9900) =     31.031 ms/op
     p(99.9990) =     32.907 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.339 ± 9.728  ops/ms
ClientPb.existUser                       thrpt       3   7.880 ± 0.524  ops/ms
ClientPb.getUser                         thrpt       3   7.484 ± 4.860  ops/ms
ClientPb.listUser                        thrpt       3   6.523 ± 2.437  ops/ms
ClientPb.createUser                       avgt       3   4.155 ± 3.030   ms/op
ClientPb.existUser                        avgt       3   3.986 ± 3.294   ms/op
ClientPb.getUser                          avgt       3   4.041 ± 1.506   ms/op
ClientPb.listUser                         avgt       3   4.982 ± 0.379   ms/op
ClientPb.createUser                     sample  227286   4.221 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.671           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.087           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.865           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.307           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.086           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.339           ms/op
ClientPb.createUser:createUser·p1.00    sample          45.220           ms/op
ClientPb.existUser                      sample  245450   3.908 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.862           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.407           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.030           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.078           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.789           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.341           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.686           ms/op
ClientPb.getUser                        sample  237023   4.045 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.800           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.071           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.045           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.641           ms/op
ClientPb.getUser:getUser·p0.9999        sample          55.266           ms/op
ClientPb.getUser:getUser·p1.00          sample          58.655           ms/op
ClientPb.listUser                       sample  188623   5.085 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.208           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.103           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.741           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.781           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.592           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.031           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.965           ms/op
