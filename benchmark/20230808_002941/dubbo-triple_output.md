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
# Warmup Iteration   1: 1.759 ops/ms
# Warmup Iteration   2: 4.043 ops/ms
# Warmup Iteration   3: 7.244 ops/ms
Iteration   1: 7.626 ops/ms
Iteration   2: 7.634 ops/ms
Iteration   3: 8.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.776 ±(99.9%) 4.612 ops/ms [Average]
  (min, avg, max) = (7.626, 7.776, 8.068), stdev = 0.253
  CI (99.9%): [3.164, 12.388] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.528 ops/ms
# Warmup Iteration   2: 7.256 ops/ms
# Warmup Iteration   3: 7.579 ops/ms
Iteration   1: 8.404 ops/ms
Iteration   2: 7.860 ops/ms
Iteration   3: 8.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.176 ±(99.9%) 5.160 ops/ms [Average]
  (min, avg, max) = (7.860, 8.176, 8.404), stdev = 0.283
  CI (99.9%): [3.017, 13.336] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.325 ops/ms
# Warmup Iteration   2: 6.991 ops/ms
# Warmup Iteration   3: 7.680 ops/ms
Iteration   1: 8.008 ops/ms
Iteration   2: 7.722 ops/ms
Iteration   3: 7.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.870 ±(99.9%) 2.610 ops/ms [Average]
  (min, avg, max) = (7.722, 7.870, 8.008), stdev = 0.143
  CI (99.9%): [5.260, 10.480] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.341 ops/ms
# Warmup Iteration   2: 5.903 ops/ms
# Warmup Iteration   3: 6.538 ops/ms
Iteration   1: 6.643 ops/ms
Iteration   2: 6.632 ops/ms
Iteration   3: 6.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.564 ±(99.9%) 2.321 ops/ms [Average]
  (min, avg, max) = (6.417, 6.564, 6.643), stdev = 0.127
  CI (99.9%): [4.243, 8.885] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.100 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.044 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.009 ms/op
Iteration   1: 4.021 ±(99.9%) 0.004 ms/op
Iteration   2: 3.989 ±(99.9%) 0.010 ms/op
Iteration   3: 4.097 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.036 ±(99.9%) 1.013 ms/op [Average]
  (min, avg, max) = (3.989, 4.036, 4.097), stdev = 0.056
  CI (99.9%): [3.023, 5.050] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.282 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.632 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.004 ms/op
Iteration   1: 3.849 ±(99.9%) 0.007 ms/op
Iteration   2: 3.915 ±(99.9%) 0.003 ms/op
Iteration   3: 3.746 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.837 ±(99.9%) 1.552 ms/op [Average]
  (min, avg, max) = (3.746, 3.837, 3.915), stdev = 0.085
  CI (99.9%): [2.285, 5.389] (assumes normal distribution)


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
# Warmup Iteration   1: 11.683 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.959 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.005 ms/op
Iteration   1: 4.184 ±(99.9%) 0.005 ms/op
Iteration   2: 3.901 ±(99.9%) 0.011 ms/op
Iteration   3: 4.078 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.054 ±(99.9%) 2.609 ms/op [Average]
  (min, avg, max) = (3.901, 4.054, 4.184), stdev = 0.143
  CI (99.9%): [1.445, 6.663] (assumes normal distribution)


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
# Warmup Iteration   1: 12.261 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.601 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.734 ±(99.9%) 0.012 ms/op
Iteration   1: 4.867 ±(99.9%) 0.007 ms/op
Iteration   2: 4.566 ±(99.9%) 0.016 ms/op
Iteration   3: 4.721 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.718 ±(99.9%) 2.749 ms/op [Average]
  (min, avg, max) = (4.566, 4.718, 4.867), stdev = 0.151
  CI (99.9%): [1.969, 7.466] (assumes normal distribution)


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
# Warmup Iteration   1: 12.266 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 5.133 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.627 ±(99.9%) 0.020 ms/op
Iteration   1: 4.127 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.899 ms/op
                 createUser·p0.95:   5.456 ms/op
                 createUser·p0.99:   8.133 ms/op
                 createUser·p0.999:  19.694 ms/op
                 createUser·p0.9999: 35.406 ms/op
                 createUser·p1.00:   35.914 ms/op

Iteration   2: 3.940 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.628 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   6.824 ms/op
                 createUser·p0.999:  22.965 ms/op
                 createUser·p0.9999: 28.898 ms/op
                 createUser·p1.00:   29.393 ms/op

Iteration   3: 4.075 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.358 ms/op
                 createUser·p0.99:   7.782 ms/op
                 createUser·p0.999:  14.303 ms/op
                 createUser·p0.9999: 36.185 ms/op
                 createUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237212
  mean =      4.046 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 488 
    [ 2.500,  5.000) = 220481 
    [ 5.000,  7.500) = 13591 
    [ 7.500, 10.000) = 1819 
    [10.000, 12.500) = 487 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      7.716 ms/op
     p(99.9000) =     19.694 ms/op
     p(99.9900) =     35.783 ms/op
     p(99.9990) =     36.545 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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
# Warmup Iteration   1: 10.619 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.393 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.012 ms/op
Iteration   1: 3.866 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   7.586 ms/op
                 existUser·p0.999:  23.658 ms/op
                 existUser·p0.9999: 32.946 ms/op
                 existUser·p1.00:   33.423 ms/op

Iteration   2: 4.050 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.448 ms/op
                 existUser·p0.99:   8.339 ms/op
                 existUser·p0.999:  17.465 ms/op
                 existUser·p0.9999: 28.410 ms/op
                 existUser·p1.00:   29.655 ms/op

Iteration   3: 3.809 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   7.209 ms/op
                 existUser·p0.999:  11.665 ms/op
                 existUser·p0.9999: 31.247 ms/op
                 existUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245711
  mean =      3.906 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 421 
    [ 2.500,  5.000) = 232061 
    [ 5.000,  7.500) = 10334 
    [ 7.500, 10.000) = 2009 
    [10.000, 12.500) = 563 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     16.506 ms/op
     p(99.9900) =     31.874 ms/op
     p(99.9990) =     33.310 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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
# Warmup Iteration   1: 11.130 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 5.143 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.116 ±(99.9%) 0.015 ms/op
Iteration   1: 4.190 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.810 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.850 ms/op
                 getUser·p0.95:   6.414 ms/op
                 getUser·p0.99:   9.355 ms/op
                 getUser·p0.999:  22.895 ms/op
                 getUser·p0.9999: 29.167 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   2: 4.122 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.970 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.374 ms/op
                 getUser·p0.99:   8.045 ms/op
                 getUser·p0.999:  21.346 ms/op
                 getUser·p0.9999: 27.959 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   3: 4.067 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.130 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.194 ms/op
                 getUser·p0.99:   7.733 ms/op
                 getUser·p0.999:  12.239 ms/op
                 getUser·p0.9999: 31.405 ms/op
                 getUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232525
  mean =      4.126 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 127 
    [ 2.500,  5.000) = 215694 
    [ 5.000,  7.500) = 12563 
    [ 7.500, 10.000) = 3058 
    [10.000, 12.500) = 676 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.810 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      8.356 ms/op
     p(99.9000) =     21.496 ms/op
     p(99.9900) =     30.556 ms/op
     p(99.9990) =     31.643 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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
# Warmup Iteration   1: 13.606 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 5.464 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.974 ±(99.9%) 0.021 ms/op
Iteration   1: 4.666 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   6.218 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  25.027 ms/op
                 listUser·p0.9999: 29.627 ms/op
                 listUser·p1.00:   30.179 ms/op

Iteration   2: 4.953 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.095 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   9.880 ms/op
                 listUser·p0.999:  19.413 ms/op
                 listUser·p0.9999: 21.743 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   3: 4.776 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  15.779 ms/op
                 listUser·p0.9999: 21.529 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200103
  mean =      4.795 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 162844 
    [ 5.000,  7.500) = 31100 
    [ 7.500, 10.000) = 4591 
    [10.000, 12.500) = 1011 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      6.169 ms/op
     p(99.0000) =      9.519 ms/op
     p(99.9000) =     20.561 ms/op
     p(99.9900) =     27.491 ms/op
     p(99.9990) =     29.721 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.776 ± 4.612  ops/ms
ClientPb.existUser                       thrpt       3   8.176 ± 5.160  ops/ms
ClientPb.getUser                         thrpt       3   7.870 ± 2.610  ops/ms
ClientPb.listUser                        thrpt       3   6.564 ± 2.321  ops/ms
ClientPb.createUser                       avgt       3   4.036 ± 1.013   ms/op
ClientPb.existUser                        avgt       3   3.837 ± 1.552   ms/op
ClientPb.getUser                          avgt       3   4.054 ± 2.609   ms/op
ClientPb.listUser                         avgt       3   4.718 ± 2.749   ms/op
ClientPb.createUser                     sample  237212   4.046 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.438           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.751           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.251           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.716           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.694           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.783           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.766           ms/op
ClientPb.existUser                      sample  245711   3.906 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.229           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.087           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.750           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.506           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.874           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.423           ms/op
ClientPb.getUser                        sample  232525   4.126 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.810           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.702           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.644           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.356           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.496           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.556           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.654           ms/op
ClientPb.listUser                       sample  200103   4.795 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.581           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.300           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.169           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.519           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.561           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.491           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.179           ms/op
