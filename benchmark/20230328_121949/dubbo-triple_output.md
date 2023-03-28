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
# Warmup Iteration   1: 1.548 ops/ms
# Warmup Iteration   2: 3.241 ops/ms
# Warmup Iteration   3: 7.179 ops/ms
Iteration   1: 7.118 ops/ms
Iteration   2: 8.154 ops/ms
Iteration   3: 8.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.766 ±(99.9%) 10.304 ops/ms [Average]
  (min, avg, max) = (7.118, 7.766, 8.154), stdev = 0.565
  CI (99.9%): [≈ 0, 18.070] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.278 ops/ms
# Warmup Iteration   2: 6.339 ops/ms
# Warmup Iteration   3: 7.974 ops/ms
Iteration   1: 8.177 ops/ms
Iteration   2: 8.520 ops/ms
Iteration   3: 8.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.436 ±(99.9%) 4.160 ops/ms [Average]
  (min, avg, max) = (8.177, 8.436, 8.610), stdev = 0.228
  CI (99.9%): [4.275, 12.596] (assumes normal distribution)


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
# Warmup Iteration   1: 2.284 ops/ms
# Warmup Iteration   2: 6.149 ops/ms
# Warmup Iteration   3: 6.441 ops/ms
Iteration   1: 7.952 ops/ms
Iteration   2: 7.989 ops/ms
Iteration   3: 7.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.889 ±(99.9%) 2.610 ops/ms [Average]
  (min, avg, max) = (7.725, 7.889, 7.989), stdev = 0.143
  CI (99.9%): [5.279, 10.499] (assumes normal distribution)


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
# Warmup Iteration   1: 2.090 ops/ms
# Warmup Iteration   2: 5.488 ops/ms
# Warmup Iteration   3: 7.020 ops/ms
Iteration   1: 6.636 ops/ms
Iteration   2: 6.939 ops/ms
Iteration   3: 6.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.856 ±(99.9%) 3.500 ops/ms [Average]
  (min, avg, max) = (6.636, 6.856, 6.992), stdev = 0.192
  CI (99.9%): [3.356, 10.356] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 14.315 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.663 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.275 ±(99.9%) 0.005 ms/op
Iteration   1: 3.833 ±(99.9%) 0.012 ms/op
Iteration   2: 3.970 ±(99.9%) 0.007 ms/op
Iteration   3: 3.882 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.895 ±(99.9%) 1.258 ms/op [Average]
  (min, avg, max) = (3.833, 3.895, 3.970), stdev = 0.069
  CI (99.9%): [2.637, 5.153] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.956 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.441 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.010 ms/op
Iteration   1: 3.936 ±(99.9%) 0.007 ms/op
Iteration   2: 3.736 ±(99.9%) 0.004 ms/op
Iteration   3: 3.674 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.782 ±(99.9%) 2.500 ms/op [Average]
  (min, avg, max) = (3.674, 3.782, 3.936), stdev = 0.137
  CI (99.9%): [1.283, 6.282] (assumes normal distribution)


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
# Warmup Iteration   1: 12.891 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.616 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.004 ms/op
Iteration   1: 3.928 ±(99.9%) 0.002 ms/op
Iteration   2: 4.043 ±(99.9%) 0.003 ms/op
Iteration   3: 3.911 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.961 ±(99.9%) 1.315 ms/op [Average]
  (min, avg, max) = (3.911, 3.961, 4.043), stdev = 0.072
  CI (99.9%): [2.646, 5.276] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 15.056 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.633 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.782 ±(99.9%) 0.007 ms/op
Iteration   1: 4.678 ±(99.9%) 0.016 ms/op
Iteration   2: 4.582 ±(99.9%) 0.014 ms/op
Iteration   3: 4.565 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.608 ±(99.9%) 1.114 ms/op [Average]
  (min, avg, max) = (4.565, 4.608, 4.678), stdev = 0.061
  CI (99.9%): [3.494, 5.722] (assumes normal distribution)


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
# Warmup Iteration   1: 13.632 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 5.307 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.395 ±(99.9%) 0.018 ms/op
Iteration   1: 4.075 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.896 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   5.644 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  24.117 ms/op
                 createUser·p0.9999: 25.925 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   2: 3.749 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.993 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  25.386 ms/op
                 createUser·p0.9999: 31.130 ms/op
                 createUser·p1.00:   31.752 ms/op

Iteration   3: 3.840 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.794 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   6.676 ms/op
                 createUser·p0.999:  9.474 ms/op
                 createUser·p0.9999: 30.179 ms/op
                 createUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 247112
  mean =      3.884 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 612 
    [ 2.500,  5.000) = 233018 
    [ 5.000,  7.500) = 12173 
    [ 7.500, 10.000) = 851 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.794 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     24.015 ms/op
     p(99.9900) =     30.189 ms/op
     p(99.9990) =     31.344 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 11.691 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.346 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.012 ms/op
Iteration   1: 3.707 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.749 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.455 ms/op
                 existUser·p0.999:  10.142 ms/op
                 existUser·p0.9999: 24.582 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   2: 3.873 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   5.128 ms/op
                 existUser·p0.99:   6.955 ms/op
                 existUser·p0.999:  24.356 ms/op
                 existUser·p0.9999: 28.064 ms/op
                 existUser·p1.00:   29.622 ms/op

Iteration   3: 3.794 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   7.111 ms/op
                 existUser·p0.999:  16.163 ms/op
                 existUser·p0.9999: 31.359 ms/op
                 existUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 253484
  mean =      3.790 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1040 
    [ 2.500,  5.000) = 241692 
    [ 5.000,  7.500) = 9232 
    [ 7.500, 10.000) = 1052 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     15.765 ms/op
     p(99.9900) =     29.545 ms/op
     p(99.9990) =     32.110 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 12.694 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.430 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.136 ±(99.9%) 0.014 ms/op
Iteration   1: 3.872 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.054 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   7.307 ms/op
                 getUser·p0.999:  22.206 ms/op
                 getUser·p0.9999: 25.321 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   2: 3.950 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.690 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  10.353 ms/op
                 getUser·p0.9999: 28.275 ms/op
                 getUser·p1.00:   29.950 ms/op

Iteration   3: 3.901 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.722 ms/op
                 getUser·p0.999:  25.888 ms/op
                 getUser·p0.9999: 29.026 ms/op
                 getUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245608
  mean =      3.907 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 139 
    [ 2.500,  5.000) = 238347 
    [ 5.000,  7.500) = 5434 
    [ 7.500, 10.000) = 1159 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 102 

  Percentiles, ms/op:
      p(0.0000) =      1.622 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     22.033 ms/op
     p(99.9900) =     28.654 ms/op
     p(99.9990) =     29.837 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 13.417 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 5.508 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.931 ±(99.9%) 0.019 ms/op
Iteration   1: 4.776 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.572 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   6.545 ms/op
                 listUser·p0.99:   9.421 ms/op
                 listUser·p0.999:  25.657 ms/op
                 listUser·p0.9999: 28.148 ms/op
                 listUser·p1.00:   28.606 ms/op

Iteration   2: 4.757 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.927 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.324 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 25.264 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   3: 4.744 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   8.929 ms/op
                 listUser·p0.999:  17.006 ms/op
                 listUser·p0.9999: 20.586 ms/op
                 listUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201746
  mean =      4.759 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 166020 
    [ 5.000,  7.500) = 29693 
    [ 7.500, 10.000) = 4895 
    [10.000, 12.500) = 612 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 103 

  Percentiles, ms/op:
      p(0.0000) =      1.927 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      6.300 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     20.996 ms/op
     p(99.9900) =     26.984 ms/op
     p(99.9990) =     28.536 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.766 ± 10.304  ops/ms
ClientPb.existUser                       thrpt       3   8.436 ±  4.160  ops/ms
ClientPb.getUser                         thrpt       3   7.889 ±  2.610  ops/ms
ClientPb.listUser                        thrpt       3   6.856 ±  3.500  ops/ms
ClientPb.createUser                       avgt       3   3.895 ±  1.258   ms/op
ClientPb.existUser                        avgt       3   3.782 ±  2.500   ms/op
ClientPb.getUser                          avgt       3   3.961 ±  1.315   ms/op
ClientPb.listUser                         avgt       3   4.608 ±  1.114   ms/op
ClientPb.createUser                     sample  247112   3.884 ±  0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.794            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.752            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.481            ms/op
ClientPb.createUser:createUser·p0.95    sample           5.104            ms/op
ClientPb.createUser:createUser·p0.99    sample           6.676            ms/op
ClientPb.createUser:createUser·p0.999   sample          24.015            ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.189            ms/op
ClientPb.createUser:createUser·p1.00    sample          31.752            ms/op
ClientPb.existUser                      sample  253484   3.790 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.782            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.633            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.325            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.858            ms/op
ClientPb.existUser:existUser·p0.99      sample           6.889            ms/op
ClientPb.existUser:existUser·p0.999     sample          15.765            ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.545            ms/op
ClientPb.existUser:existUser·p1.00      sample          32.801            ms/op
ClientPb.getUser                        sample  245608   3.907 ±  0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.622            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.801            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.268            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.489            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.939            ms/op
ClientPb.getUser:getUser·p0.999         sample          22.033            ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.654            ms/op
ClientPb.getUser:getUser·p1.00          sample          29.950            ms/op
ClientPb.listUser                       sample  201746   4.759 ±  0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.927            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.530            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.399            ms/op
ClientPb.listUser:listUser·p0.95        sample           6.300            ms/op
ClientPb.listUser:listUser·p0.99        sample           9.110            ms/op
ClientPb.listUser:listUser·p0.999       sample          20.996            ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.984            ms/op
ClientPb.listUser:listUser·p1.00        sample          28.606            ms/op
