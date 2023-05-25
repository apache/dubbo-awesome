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
# Warmup Iteration   1: 1.530 ops/ms
# Warmup Iteration   2: 3.557 ops/ms
# Warmup Iteration   3: 6.909 ops/ms
Iteration   1: 7.251 ops/ms
Iteration   2: 7.759 ops/ms
Iteration   3: 7.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.584 ±(99.9%) 5.267 ops/ms [Average]
  (min, avg, max) = (7.251, 7.584, 7.759), stdev = 0.289
  CI (99.9%): [2.317, 12.852] (assumes normal distribution)


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
# Warmup Iteration   1: 2.123 ops/ms
# Warmup Iteration   2: 6.326 ops/ms
# Warmup Iteration   3: 7.950 ops/ms
Iteration   1: 8.134 ops/ms
Iteration   2: 8.257 ops/ms
Iteration   3: 7.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.119 ±(99.9%) 2.674 ops/ms [Average]
  (min, avg, max) = (7.965, 8.119, 8.257), stdev = 0.147
  CI (99.9%): [5.445, 10.793] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.018 ops/ms
# Warmup Iteration   2: 5.622 ops/ms
# Warmup Iteration   3: 7.290 ops/ms
Iteration   1: 7.788 ops/ms
Iteration   2: 7.794 ops/ms
Iteration   3: 7.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.774 ±(99.9%) 0.554 ops/ms [Average]
  (min, avg, max) = (7.739, 7.774, 7.794), stdev = 0.030
  CI (99.9%): [7.219, 8.328] (assumes normal distribution)


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
# Warmup Iteration   1: 2.040 ops/ms
# Warmup Iteration   2: 5.272 ops/ms
# Warmup Iteration   3: 6.761 ops/ms
Iteration   1: 6.158 ops/ms
Iteration   2: 6.530 ops/ms
Iteration   3: 6.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.459 ±(99.9%) 4.961 ops/ms [Average]
  (min, avg, max) = (6.158, 6.459, 6.688), stdev = 0.272
  CI (99.9%): [1.497, 11.420] (assumes normal distribution)


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
# Warmup Iteration   1: 14.291 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.536 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.477 ±(99.9%) 0.008 ms/op
Iteration   1: 4.234 ±(99.9%) 0.005 ms/op
Iteration   2: 4.123 ±(99.9%) 0.011 ms/op
Iteration   3: 4.140 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.166 ±(99.9%) 1.090 ms/op [Average]
  (min, avg, max) = (4.123, 4.166, 4.234), stdev = 0.060
  CI (99.9%): [3.076, 5.256] (assumes normal distribution)


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
# Warmup Iteration   1: 12.829 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.487 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.008 ms/op
Iteration   1: 4.139 ±(99.9%) 0.005 ms/op
Iteration   2: 3.810 ±(99.9%) 0.006 ms/op
Iteration   3: 3.756 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.902 ±(99.9%) 3.783 ms/op [Average]
  (min, avg, max) = (3.756, 3.902, 4.139), stdev = 0.207
  CI (99.9%): [0.119, 7.684] (assumes normal distribution)


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
# Warmup Iteration   1: 14.075 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.991 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.292 ±(99.9%) 0.006 ms/op
Iteration   1: 4.100 ±(99.9%) 0.005 ms/op
Iteration   2: 4.127 ±(99.9%) 0.005 ms/op
Iteration   3: 4.259 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.162 ±(99.9%) 1.551 ms/op [Average]
  (min, avg, max) = (4.100, 4.162, 4.259), stdev = 0.085
  CI (99.9%): [2.611, 5.712] (assumes normal distribution)


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
# Warmup Iteration   1: 14.751 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.910 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.910 ±(99.9%) 0.011 ms/op
Iteration   1: 4.982 ±(99.9%) 0.011 ms/op
Iteration   2: 4.895 ±(99.9%) 0.007 ms/op
Iteration   3: 5.058 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.978 ±(99.9%) 1.490 ms/op [Average]
  (min, avg, max) = (4.895, 4.978, 5.058), stdev = 0.082
  CI (99.9%): [3.489, 6.468] (assumes normal distribution)


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
# Warmup Iteration   1: 13.836 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 5.785 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.479 ±(99.9%) 0.020 ms/op
Iteration   1: 4.451 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.655 ms/op
                 createUser·p0.50:   4.162 ms/op
                 createUser·p0.90:   5.464 ms/op
                 createUser·p0.95:   6.611 ms/op
                 createUser·p0.99:   9.585 ms/op
                 createUser·p0.999:  23.861 ms/op
                 createUser·p0.9999: 26.509 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   2: 4.588 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.944 ms/op
                 createUser·p0.50:   4.252 ms/op
                 createUser·p0.90:   5.786 ms/op
                 createUser·p0.95:   6.914 ms/op
                 createUser·p0.99:   10.111 ms/op
                 createUser·p0.999:  19.966 ms/op
                 createUser·p0.9999: 27.375 ms/op
                 createUser·p1.00:   28.017 ms/op

Iteration   3: 4.374 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.438 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.202 ms/op
                 createUser·p0.95:   5.767 ms/op
                 createUser·p0.99:   7.995 ms/op
                 createUser·p0.999:  20.801 ms/op
                 createUser·p0.9999: 31.086 ms/op
                 createUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 214714
  mean =      4.470 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 360 
    [ 2.500,  5.000) = 178563 
    [ 5.000,  7.500) = 30533 
    [ 7.500, 10.000) = 3616 
    [10.000, 12.500) = 977 
    [12.500, 15.000) = 221 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 106 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.438 ms/op
     p(50.0000) =      4.170 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      6.488 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     22.488 ms/op
     p(99.9900) =     30.426 ms/op
     p(99.9990) =     32.457 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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
# Warmup Iteration   1: 13.297 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 5.193 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.015 ms/op
Iteration   1: 4.284 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.376 ms/op
                 existUser·p0.50:   3.940 ms/op
                 existUser·p0.90:   5.355 ms/op
                 existUser·p0.95:   6.529 ms/op
                 existUser·p0.99:   10.093 ms/op
                 existUser·p0.999:  22.053 ms/op
                 existUser·p0.9999: 24.594 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   2: 3.955 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.436 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   4.948 ms/op
                 existUser·p0.99:   8.684 ms/op
                 existUser·p0.999:  21.037 ms/op
                 existUser·p0.9999: 24.838 ms/op
                 existUser·p1.00:   26.673 ms/op

Iteration   3: 4.246 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.371 ms/op
                 existUser·p0.50:   4.010 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.784 ms/op
                 existUser·p0.99:   8.798 ms/op
                 existUser·p0.999:  27.099 ms/op
                 existUser·p0.9999: 32.292 ms/op
                 existUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 230802
  mean =      4.156 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 417 
    [ 2.500,  5.000) = 209140 
    [ 5.000,  7.500) = 16474 
    [ 7.500, 10.000) = 3068 
    [10.000, 12.500) = 930 
    [12.500, 15.000) = 331 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.371 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     22.190 ms/op
     p(99.9900) =     31.389 ms/op
     p(99.9990) =     33.715 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 14.260 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 5.089 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.014 ms/op
Iteration   1: 4.139 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.429 ms/op
                 getUser·p0.50:   3.969 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   8.782 ms/op
                 getUser·p0.999:  12.429 ms/op
                 getUser·p0.9999: 26.944 ms/op
                 getUser·p1.00:   27.787 ms/op

Iteration   2: 4.273 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.513 ms/op
                 getUser·p0.50:   4.018 ms/op
                 getUser·p0.90:   5.022 ms/op
                 getUser·p0.95:   6.062 ms/op
                 getUser·p0.99:   8.962 ms/op
                 getUser·p0.999:  26.247 ms/op
                 getUser·p0.9999: 30.706 ms/op
                 getUser·p1.00:   31.293 ms/op

Iteration   3: 4.137 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.872 ms/op
                 getUser·p0.50:   3.998 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   7.397 ms/op
                 getUser·p0.999:  15.663 ms/op
                 getUser·p0.9999: 31.031 ms/op
                 getUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 229354
  mean =      4.182 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 211909 
    [ 5.000,  7.500) = 13502 
    [ 7.500, 10.000) = 2765 
    [10.000, 12.500) = 759 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.513 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     19.024 ms/op
     p(99.9900) =     30.509 ms/op
     p(99.9990) =     31.639 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


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
# Warmup Iteration   1: 15.733 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 6.548 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.355 ±(99.9%) 0.027 ms/op
Iteration   1: 4.785 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   8.934 ms/op
                 listUser·p0.999:  26.935 ms/op
                 listUser·p0.9999: 28.836 ms/op
                 listUser·p1.00:   29.688 ms/op

Iteration   2: 4.642 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.034 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  22.780 ms/op
                 listUser·p0.9999: 27.893 ms/op
                 listUser·p1.00:   29.524 ms/op

Iteration   3: 4.694 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.970 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   8.859 ms/op
                 listUser·p0.999:  18.542 ms/op
                 listUser·p0.9999: 24.478 ms/op
                 listUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203912
  mean =      4.706 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 176077 
    [ 5.000,  7.500) = 22607 
    [ 7.500, 10.000) = 4131 
    [10.000, 12.500) = 563 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 102 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     23.661 ms/op
     p(99.9900) =     28.574 ms/op
     p(99.9990) =     29.588 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.584 ± 5.267  ops/ms
ClientPb.existUser                       thrpt       3   8.119 ± 2.674  ops/ms
ClientPb.getUser                         thrpt       3   7.774 ± 0.554  ops/ms
ClientPb.listUser                        thrpt       3   6.459 ± 4.961  ops/ms
ClientPb.createUser                       avgt       3   4.166 ± 1.090   ms/op
ClientPb.existUser                        avgt       3   3.902 ± 3.783   ms/op
ClientPb.getUser                          avgt       3   4.162 ± 1.551   ms/op
ClientPb.listUser                         avgt       3   4.978 ± 1.490   ms/op
ClientPb.createUser                     sample  214714   4.470 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.438           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.488           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.355           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.488           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.426           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.670           ms/op
ClientPb.existUser                      sample  230802   4.156 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.371           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.908           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.816           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.224           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.190           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.389           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.996           ms/op
ClientPb.getUser                        sample  229354   4.182 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.513           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.792           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.546           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.569           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.024           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.509           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.211           ms/op
ClientPb.listUser                       sample  203912   4.706 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.491           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.161           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.618           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.661           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.574           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.688           ms/op
