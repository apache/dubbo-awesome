# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.494 ops/ms
# Warmup Iteration   2: 3.513 ops/ms
# Warmup Iteration   3: 6.890 ops/ms
Iteration   1: 7.627 ops/ms
Iteration   2: 7.981 ops/ms
Iteration   3: 7.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.818 ±(99.9%) 3.257 ops/ms [Average]
  (min, avg, max) = (7.627, 7.818, 7.981), stdev = 0.179
  CI (99.9%): [4.561, 11.075] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.323 ops/ms
# Warmup Iteration   2: 6.882 ops/ms
# Warmup Iteration   3: 7.710 ops/ms
Iteration   1: 8.097 ops/ms
Iteration   2: 7.440 ops/ms
Iteration   3: 8.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.904 ±(99.9%) 7.359 ops/ms [Average]
  (min, avg, max) = (7.440, 7.904, 8.173), stdev = 0.403
  CI (99.9%): [0.545, 15.262] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.061 ops/ms
# Warmup Iteration   2: 5.464 ops/ms
# Warmup Iteration   3: 7.320 ops/ms
Iteration   1: 7.672 ops/ms
Iteration   2: 7.496 ops/ms
Iteration   3: 8.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.725 ±(99.9%) 4.755 ops/ms [Average]
  (min, avg, max) = (7.496, 7.725, 8.009), stdev = 0.261
  CI (99.9%): [2.971, 12.480] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.146 ops/ms
# Warmup Iteration   2: 5.230 ops/ms
# Warmup Iteration   3: 6.560 ops/ms
Iteration   1: 6.587 ops/ms
Iteration   2: 7.008 ops/ms
Iteration   3: 6.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.775 ±(99.9%) 3.912 ops/ms [Average]
  (min, avg, max) = (6.587, 6.775, 7.008), stdev = 0.214
  CI (99.9%): [2.864, 10.687] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 13.342 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.912 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.347 ±(99.9%) 0.007 ms/op
Iteration   1: 4.019 ±(99.9%) 0.014 ms/op
Iteration   2: 4.113 ±(99.9%) 0.012 ms/op
Iteration   3: 4.124 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.085 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (4.019, 4.085, 4.124), stdev = 0.058
  CI (99.9%): [3.034, 5.137] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.545 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.434 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.006 ms/op
Iteration   1: 3.806 ±(99.9%) 0.004 ms/op
Iteration   2: 3.804 ±(99.9%) 0.010 ms/op
Iteration   3: 3.808 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.806 ±(99.9%) 0.038 ms/op [Average]
  (min, avg, max) = (3.804, 3.806, 3.808), stdev = 0.002
  CI (99.9%): [3.768, 3.845] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.120 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.797 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.361 ±(99.9%) 0.011 ms/op
Iteration   1: 3.965 ±(99.9%) 0.007 ms/op
Iteration   2: 4.195 ±(99.9%) 0.004 ms/op
Iteration   3: 4.086 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.082 ±(99.9%) 2.098 ms/op [Average]
  (min, avg, max) = (3.965, 4.082, 4.195), stdev = 0.115
  CI (99.9%): [1.984, 6.180] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.402 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.666 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.963 ±(99.9%) 0.010 ms/op
Iteration   1: 4.847 ±(99.9%) 0.011 ms/op
Iteration   2: 4.717 ±(99.9%) 0.017 ms/op
Iteration   3: 4.722 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.762 ±(99.9%) 1.344 ms/op [Average]
  (min, avg, max) = (4.717, 4.762, 4.847), stdev = 0.074
  CI (99.9%): [3.418, 6.106] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 14.046 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.586 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.828 ±(99.9%) 0.023 ms/op
Iteration   1: 4.267 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.118 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   5.276 ms/op
                 createUser·p0.95:   6.717 ms/op
                 createUser·p0.99:   9.896 ms/op
                 createUser·p0.999:  21.105 ms/op
                 createUser·p0.9999: 25.114 ms/op
                 createUser·p1.00:   27.001 ms/op

Iteration   2: 4.103 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.556 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   7.848 ms/op
                 createUser·p0.999:  23.265 ms/op
                 createUser·p0.9999: 26.188 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   3: 4.084 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.782 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   7.782 ms/op
                 createUser·p0.999:  20.273 ms/op
                 createUser·p0.9999: 33.927 ms/op
                 createUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 231215
  mean =      4.150 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 323 
    [ 2.500,  5.000) = 210962 
    [ 5.000,  7.500) = 15487 
    [ 7.500, 10.000) = 3095 
    [10.000, 12.500) = 797 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     21.660 ms/op
     p(99.9900) =     32.494 ms/op
     p(99.9990) =     35.107 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 13.185 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.016 ms/op
Iteration   1: 3.937 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.095 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   5.341 ms/op
                 existUser·p0.99:   8.421 ms/op
                 existUser·p0.999:  13.982 ms/op
                 existUser·p0.9999: 25.293 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   2: 4.166 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.200 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   4.973 ms/op
                 existUser·p0.95:   5.939 ms/op
                 existUser·p0.99:   8.405 ms/op
                 existUser·p0.999:  26.025 ms/op
                 existUser·p0.9999: 28.321 ms/op
                 existUser·p1.00:   29.753 ms/op

Iteration   3: 3.959 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.761 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   7.610 ms/op
                 existUser·p0.999:  10.819 ms/op
                 existUser·p0.9999: 32.994 ms/op
                 existUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 238981
  mean =      4.018 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 155 
    [ 2.500,  5.000) = 222349 
    [ 5.000,  7.500) = 12880 
    [ 7.500, 10.000) = 2608 
    [10.000, 12.500) = 690 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.761 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      8.036 ms/op
     p(99.9000) =     14.156 ms/op
     p(99.9900) =     31.395 ms/op
     p(99.9990) =     33.392 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.831 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 4.821 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.196 ±(99.9%) 0.013 ms/op
Iteration   1: 4.142 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.978 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   5.383 ms/op
                 getUser·p0.99:   8.995 ms/op
                 getUser·p0.999:  21.457 ms/op
                 getUser·p0.9999: 23.986 ms/op
                 getUser·p1.00:   24.412 ms/op

Iteration   2: 4.351 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.985 ms/op
                 getUser·p0.50:   4.043 ms/op
                 getUser·p0.90:   5.235 ms/op
                 getUser·p0.95:   6.324 ms/op
                 getUser·p0.99:   8.733 ms/op
                 getUser·p0.999:  16.893 ms/op
                 getUser·p0.9999: 31.883 ms/op
                 getUser·p1.00:   33.161 ms/op

Iteration   3: 4.194 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.179 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   8.510 ms/op
                 getUser·p0.999:  15.204 ms/op
                 getUser·p0.9999: 34.931 ms/op
                 getUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 226933
  mean =      4.227 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 204559 
    [ 5.000,  7.500) = 18210 
    [ 7.500, 10.000) = 2796 
    [10.000, 12.500) = 801 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.978 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     19.796 ms/op
     p(99.9900) =     33.620 ms/op
     p(99.9990) =     35.354 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.934 ±(99.9%) 0.231 ms/op
# Warmup Iteration   2: 5.927 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.189 ±(99.9%) 0.021 ms/op
Iteration   1: 4.890 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.538 ms/op
                 listUser·p0.95:   7.177 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  24.453 ms/op
                 listUser·p0.9999: 27.278 ms/op
                 listUser·p1.00:   29.229 ms/op

Iteration   2: 4.787 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.064 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   9.421 ms/op
                 listUser·p0.999:  20.480 ms/op
                 listUser·p0.9999: 26.094 ms/op
                 listUser·p1.00:   26.444 ms/op

Iteration   3: 4.675 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.814 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  17.548 ms/op
                 listUser·p0.9999: 21.173 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200565
  mean =      4.782 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 162572 
    [ 5.000,  7.500) = 32096 
    [ 7.500, 10.000) = 4430 
    [10.000, 12.500) = 793 
    [12.500, 15.000) = 246 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 72 

  Percentiles, ms/op:
      p(0.0000) =      2.064 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      9.191 ms/op
     p(99.9000) =     20.546 ms/op
     p(99.9900) =     26.569 ms/op
     p(99.9990) =     29.097 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.818 ± 3.257  ops/ms
ClientPb.existUser                       thrpt       3   7.904 ± 7.359  ops/ms
ClientPb.getUser                         thrpt       3   7.725 ± 4.755  ops/ms
ClientPb.listUser                        thrpt       3   6.775 ± 3.912  ops/ms
ClientPb.createUser                       avgt       3   4.085 ± 1.051   ms/op
ClientPb.existUser                        avgt       3   3.806 ± 0.038   ms/op
ClientPb.getUser                          avgt       3   4.082 ± 2.098   ms/op
ClientPb.listUser                         avgt       3   4.762 ± 1.344   ms/op
ClientPb.createUser                     sample  231215   4.150 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.556           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.874           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.685           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.651           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.660           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.494           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.193           ms/op
ClientPb.existUser                      sample  238981   4.018 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.761           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.661           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.036           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.156           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.395           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.620           ms/op
ClientPb.getUser                        sample  226933   4.227 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.978           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.989           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.857           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.733           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.796           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.620           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.521           ms/op
ClientPb.listUser                       sample  200565   4.782 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.064           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.308           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.972           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.191           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.546           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.569           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.229           ms/op
